# Policy Management

Policy management helps enforce governance, security, and compliance across cloud environments. Policies define how resources should be configured and accessed.

## Types of Cloud Policies

|Policy Type|Purpose|Example Use Case|
|-----------|-------|---------------|
|Access Control Policies|Restrict who can access or modify resources.|IAM policies for role-based access control.|
|Security Policies|Ensure encryption, firewall settings, and compliance.|Enforce TLS encryption for cloud storage.|
|Cost Management Policies|Prevent cost overruns by restricting high-cost instances.|Limit VM instance types based on budget.|
|Backup & Retention Policies|Define backup frequency and data retention duration.|Maintain daily database backups for 30 days.|

## Implementing Policies

*   **AWS:** Use AWS Organizations & Service Control Policies (SCPs).

*   **Azure:** Implement Azure Policy to enforce compliance.

*   **Google Cloud:** Use Organization Policies for governance.

## Best Practices for Policy Management

*   Define least privilege access to minimize risk.

*   Use automated policy enforcement tools.

*   Regularly audit policies for compliance.

*   Implement tagging policies to track resource usage.