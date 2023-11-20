## AWS Identity and Access Management
* AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.
### IAM features
* **Shared access to your AWS account:** 
    * You can grant other people permission to administer and use resources in your AWS account without having to share your password or access key.
* **Granular permissions:** 
    * You can grant different permissions to different people for different resources. 
* **Secure access to AWS resources for applications that run on Amazon EC2:** 
    * You can use IAM features to securely provide credentials for applications that run on EC2 instances. These credentials provide permissions for your application to access other AWS resources.
* **Multi-factor authentication (MFA):** 
    * You can add two-factor authentication to your account and to individual users for extra security. With MFA you or your users must provide not only a password or access key to work with your account, but also a code from a specially configured device.
* **Identity federation:** 
    * You can allow users who already have passwords elsewhere—for example, in your corporate network or with an internet identity provider—to get temporary access to your AWS account.
* **Identity information for assurance:**
    * If you use AWS CloudTrail, you receive log records that include information about those who made requests for resources in your account. That information is based on IAM identities.
* **PCI DSS Compliance:**
    * IAM supports the processing, storage, and transmission of credit card data by a merchant or service provider, and has been validated as being compliant with Payment Card Industry (PCI) Data Security Standard (DSS).
* **Integrated with many AWS services:**
    * For a list of AWS services that work with IAM
        * Service.
        * Actions.
        * Resource-level permissions.
        * Resource-based policies.
        * ABAC (authorization based on tags).
        * Temporary credentials.
        * Service-linked roles.
### 