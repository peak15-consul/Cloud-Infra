# User Authentication & Identity Management

Authentication ensures that only legitimate users can access cloud resources. The following methods are commonly used:

|Method|Description|Recommended Use Case|
|------|-----------|--------------------|
|Username & Password|Standard authentication using credentials.|Basic access but vulnerable if not secured with MFA.|
|Multi-Factor Authentication (MFA)|Requires additional authentication factors like OTP, biometrics.|Highly recommended for all users.|
|Single Sign-On (SSO)|Allows users to log in once and access multiple cloud services.|Enterprises with multiple cloud services.|
|Identity Federation|Integrates with external identity providers (Okta, Azure AD, Google IAM).|Large organizations with existing authentication systems.|