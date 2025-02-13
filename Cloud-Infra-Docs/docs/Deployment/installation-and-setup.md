# Installation & Setup

This section of the document explains the installation methods, deployment details for on-premise and cloud environments, and troubleshooting inforamation.

## Installation Methods

CloudOps Manager supports multiple deployment methods:

*   On-Premise Deployment (for private data centers)

*   Cloud-Based Deployment (for public cloud providers like AWS, Azure, GCP)

*   Containerized Deployment (via Docker & Kubernetes)

## On-Premise Deployment

### Prerequisites

*   Ensure the system meets the hardware and software requirements.

*   Install necessary dependencies:

    ```sudo apt update && sudo apt install -y docker.io docker-compose python3-pip```

*   Verify Docker installation:

    ```docker --version```

### Installation Steps

*   Download Installer:

    ```curl -O https://cloudops.example.com/install.sh && chmod +x install.sh```

*   Run Installer:

    ```./install.sh```

*   Verify Installation:

    ```cloudops --version```

## Cloud-Based Deployment

**Deploying with Terraform**

*   Clone the CloudOps Terraform Repository:

    `git clone https://github.com/cloudops/terraform-cloudops.git`
    `cd terraform-cloudops`

*   Initialize Terraform:

    `terraform init`

*   Plan Deployment:

    `terraform plan`

*   Apply Configuration:

    `terraform apply --auto-approve`

**Deploying with Pre-Configured Docker Image**

*   Pull and run the CloudOps container:

    `docker run -d -p 8080:80 cloudops/manager:latest`

*   Verify the service is running:

    `docker ps`

## Initial Configuration

*   *Access the Web UI:* Navigate to `http://<server-ip>:8080`.

*   *Create an Admin Account:* Follow the setup wizard.

*   *Configure Cloud Accounts:* Add API credentials for AWS/Azure/GCP.

*   *Enable Security Settings:* Set up Multi-Factor Authentication (MFA).

## Troubleshooting Installation Issues

| Issue | Solution |
| - | - |
| Installer fails to run | Ensure `install.sh` has execute permissions (`chmod +x install.sh`).|
| Docker containers not starting | Check `docker ps -a` for error messages. Restart Docker if necessary. |
| Cannot access web UI | Ensure firewall rules allow traffic on port 8080. |
| Terraform deployment fails | Validate cloud provider API keys and IAM permissions.|