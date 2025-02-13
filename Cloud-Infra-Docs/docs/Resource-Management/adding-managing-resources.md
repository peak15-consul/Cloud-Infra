# Adding & Managing Resources

Cloud resources include compute instances, storage, databases, networking components, and application services. Efficiently managing these resources ensures optimal performance, security, and cost efficiency.

## Types of Cloud Resources

|Resource Type|Description|Examples|
|-------------|-----------|--------|
|Compute|Virtual machines, containers, and serverless functions for running applications.|AWS EC2, Azure VMs, Google Compute Engine, Kubernetes|
|Storage|Object, block, and file storage for data persistence.|S3, Azure Blob Storage, Google Cloud Storage|
|Networking|Virtual networks, firewalls, and load balancers.|AWS VPC, Azure VNets, Google Cloud VPC|
|Databases|Managed SQL and NoSQL databases.|RDS, Azure SQL, Firestore|
|Identity & Security|User authentication, encryption, and security groups.|IAM, Key Management Service, Security Groups|

## Provisioning Cloud Resources

Cloud providers offer multiple ways to provision resources:

*   **Manual Provisioning:** Using cloud consoles or CLI commands.

*   **Infrastructure as Code (IaC):** Automating resource deployment via Terraform, CloudFormation, or ARM templates.

*   **Automated Resource Scaling:** Enabling auto-scaling to adjust resources dynamically.

## Best Practices for Resource Management

*   Use tags and naming conventions for better visibility.

*   Implement IAM roles to control access.

*   Use infrastructure as code (IaC) to standardize deployments.

*   Set up resource quotas to prevent over-provisioning.