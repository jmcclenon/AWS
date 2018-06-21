## Identity Access Management

IAM consists of the following:

 - Users
 - Groups (a way to group our users and apply policies to them
   collectively)
 - Roles
 - Policy Documents (written in [JSON](https://www.json.org/) using attributes and values)

IAM is universal. It does not apply to regions at this time.

The [root account](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html) is the account created when your account is first setup. It has complete admin access. The user's email address is used to set this up. The user provides a password during the sign-up process.

AWS strongly recommends that you do not use the root user for your everyday tasks, even the administrative ones. Instead, adhere to the [best practice of using the root user only to create your first IAM user](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#create-iam-users). Then securely lock away the root user credentials and use them to perform only a few account and service management tasks. 

To view the tasks that require you to sign in as the root user, see [AWS Tasks That Require Root User](http://docs.aws.amazon.com/general/latest/gr/aws_tasks-that-require-root.html). For a tutorial on how to set up an administrator for daily use, see [Creating Your First IAM Admin User and Group](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html).

New users have NO permissions when they are first created. Permission must be assigned to all new users of the admin console.

New users are assigned Access Key ID/Secret Access Keys when first created.

The Access Key ID/Secret Access Keys are not the same as a password, and you cannot use the Access Key ID/Secret Key to login to the console. 

You can use the Access Key ID/Secret Access Key to access AWS via the APIs and command line. The username/password cannot be used to access the APIs.

The Access Key/Secret Key can only be accessed once, when the user is created, and must be downloaded when presented, usually in CSV format. If these keys are lost, they must be regenerated, resulting in different keys.

It is a best practice to setup [Multi-factor Authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) on your root account.

You can create and customize your own password rotation policies from the console.

---

**Question**: 
When using Active Directory to authenticate to AWS, what are the correct steps performed?

**Answer**:
1. The user navigates to ADFS webserver.
2. The user enters their single sign on credentials.
3. The user's web browser receives a SAML assertion from the AD server.
4. The user's browser then posts the SAML assertion to the AWS SAML end point for SAML and the [AssumeRoleWithSAML API](https://docs.aws.amazon.com/STS/latest/APIReference/API_AssumeRoleWithSAML.html) request is used to request temporary security credentials.
5. The user is then able to access the AWS console.

---
**Question**:
When using Web Identity Federation to allow a user to access an AWS service (such as an S3 bucket) what is the correct order of steps?

**Answer**:
The user authenticates with Facebook/Twitter/Google first. They are then given an ID token by the Identity Store (Facebook, etc.). The AssumeRoleWithWebIdentity API is then used in conjunction with the ID token. The user is then granted temporary security credentials, and is then able to complete their tasks.


---


## AWS tasks that require root access:

The tasks listed below require you to sign in as the AWS account root user.  [We normally recommend that you use a standard IAM user with appropriate permissions to perform all normal user or administrative tasks](http://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials). However, you can perform the tasks listed below only when you sign in as the root user of an account.

-   [Modify root user details](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html#email-and-password-for-your-AWS-account). This includes changing the root user's password.
    
-   [Change your AWS support plan](http://docs.aws.amazon.com/awssupport/latest/user/getting-started.html).
    
-   [Change or delete your payment options](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/manage-payments.html)  - an IAM user can perform this after you enable billing access for IAM users. For more information, see  [Activating Access to the Billing and Cost Management Console](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/grantaccess.html#ControllingAccessWebsite-Activate).
    
-   [View your account's billing information](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/getting-viewing-bill.html)  - an IAM user can perform this after you enable billing access for IAM users. For more information, see  [Activating Access to the Billing and Cost Management Console](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/grantaccess.html#ControllingAccessWebsite-Activate).
    
-   [Contact Customer Support about your bill](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-get-answers.html).
    
-   [Close an AWS account](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/close-account.html).
    
-   [Sign up for GovCloud](http://docs.aws.amazon.com/govcloud-us/latest/UserGuide/getting-started-sign-up.html).
    
-   [Submit a Reverse DNS for Amazon EC2 request](https://aws.amazon.com/blogs/aws/reverse-dns-for-ec2s-elastic-ip-addresses/). The "[this form](https://aws-portal.amazon.com/gp/aws/html-forms-controller/contactus/ec2-email-limit-rdns-request)" link on that page to submit a request works only if you sign in with root user credentials.
    
-   [Create a CloudFront key pair](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-trusted-signers.html#private-content-creating-cloudfront-key-pairs).
    
-   [Create an AWS-created X.509 signing certificate](http://docs.aws.amazon.com/AmazonDevPay/latest/DevPayDeveloperGuide/X509Certificates.html#UsingAWSCertificate). (You can still make self-created certificates for IAM users.)
    
-   [Transfer an Route 53 domain to another AWS account](http://docs.aws.amazon.com/Route53/latest/DeveloperGuide/domain-transfer-between-aws-accounts.html).
    
-   [Change the Amazon EC2 setting for longer resource IDs](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/resource-ids.html#resource-ids-working-with-self). Changing this setting as the root user affects all users and roles in the account. Changing it as an IAM user or IAM role affects only that user or role.
    
-   [Submit a request to perform penetration testing on your AWS infrastructure using the web form](https://aws.amazon.com/premiumsupport/knowledge-center/penetration-testing/). Alternatively, you can submit your request via email without needing root user access.
    
-   [Request removal of the port 25 email throttle on your EC2 instance](https://aws.amazon.com/premiumsupport/knowledge-center/ec2-port-25-throttle/).
    
-   [Find your AWS account canonical user ID](https://docs.aws.amazon.com/general/latest/gr/acct-identifiers.html#FindingCanonicalId). You can view your canonical user ID from the AWS Management Console only while signed in as the AWS account root user. You can view your canonical user ID as an IAM user with the AWS API or AWS CLI.
    
-   [Reassigning permissions in a resource-based policy (such as an S3 bucket policy) that were revoked by explicitly denying IAM users access.](http://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_manage-edit.html)  Root users are not blocked by an explicit deny like IAM users can be.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI4Nzc0MzAwMiwtOTA3MTY0OTU2LDE4Nz
ExODAxMzAsLTEyNTkwMjk4ODUsLTE1NjM3NjU4ODMsMTI1NzQw
NDUwOV19
-->