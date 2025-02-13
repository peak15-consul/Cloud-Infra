# Access Control & Policy Management

Access control determines how users interact with cloud resources. Cloud platforms provide various access control mechanisms to enforce security policies.

## Identity and Access Management (IAM)
IAM is the core framework for managing user access in cloud environments. It includes:

*   **Users:** Individual accounts with specific permissions.

*   **Groups:** Collections of users with shared permissions.

*   **Roles:** Predefined access levels assigned to users or groups.

*   **Policies:** JSON-based documents that define access permissions for users, groups, and roles.

## Role-Based Access Control (RBAC) vs. Attribute-Based Access Control (ABAC)

|Access Control Model|Description|Best Use Case|
|--------------------|-----------|-------------|
|RBAC|Assigns permissions based on user roles.|Organizations with structured job roles.|
|ABAC|Grants access based on attributes like location, device, or department.|Dynamic environments needing granular control.|