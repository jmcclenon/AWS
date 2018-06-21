## Identity Access Management

IAM consists of the following:

 - Users
 - Groups (a way to group our users and apply policies to them
   collectively)
 - Roles
 - Policy Documents (written in [JSON](https://www.json.org/) using attributes and values)

IAM is universal. It does not apply to regions at this time.

The root account is the account created when your account is first setup. It has complete admin access. The user's email address is used to set this up. The user provides a password during the sign-up process.

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
eyJoaXN0b3J5IjpbMTg3MTE4MDEzMCwtMTI1OTAyOTg4NSwtMT
U2Mzc2NTg4MywxMjU3NDA0NTA5XX0=
-->