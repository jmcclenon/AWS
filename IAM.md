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


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEwNTg0MTQ5MywxODcxMTgwMTMwLC0xMj
U5MDI5ODg1LC0xNTYzNzY1ODgzLDEyNTc0MDQ1MDldfQ==
-->