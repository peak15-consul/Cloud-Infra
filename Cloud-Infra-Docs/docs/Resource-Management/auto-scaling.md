# Auto-Scaling

Auto-scaling dynamically adjusts computing resources based on demand, ensuring performance efficiency and cost savings.

## Types of Auto-Scaling

|Scaling Type|Description|Example Use Case|
|------------|-----------|---------------|
|Vertical Scaling|Adjusts the size of a single instance (CPU, RAM).|Scaling up a database server during peak hours.|
|Horizontal Scaling|Adds or removes instances based on load.|Increasing web server instances to handle traffic.|
|Scheduled Scaling|Adjusts resources based on predefined schedules.|Scaling up at 9 AM and scaling down at 6 PM.|
|Predictive Scaling|Uses AI/ML to anticipate workload demands.|Automatically scaling before expected high traffic.|

## Auto-Scaling in Major Cloud Providers

*   **AWS:** Auto Scaling Groups (ASG) with Elastic Load Balancers (ELB).

*   **Azure:** Virtual Machine Scale Sets (VMSS).

*   **Google Cloud:** Google Cloud: Managed Instance Groups (MIG).

## Best Practices for Auto-Scaling

*   Use threshold-based triggers to scale resources efficiently.

*   Define cool-down periods to prevent unnecessary scaling.

*   Monitor scaling events to fine-tune performance.

*   Combine load balancing with auto-scaling for resilience.