## Identity Access Management

IAM consists of the following:

 - Users
 - Groups (a way to group our users and apply policies to them
   collectively)
 - Roles
 - Policy Documents (written in [JSON](https://www.json.org/) using attributes and values)

IAM is universal. It does not apply to regions at this time.

The root account is simply the account created when your account is first setup. It has complete admin access.

New users have NO permissions when they are first created. Permission must be assigned to all new users of the admin console.

New users are assigned Access Key ID/Secret Access Keys when first created.

The Access Key ID/Secret Access Keys are not the same as a password, and you cannot use the Access Key ID/Secret Key to login to the console. 

You can use the Access Key ID/Secret Access Key to access AWS via the APIs and command line. The username/password cannot be used to access the APIs.

The Access Key/Secret Key are only accessed once, when the user is created, and must be downloaded when presented, usually in CSV format. If these keys are lost, they must be regenerated, resulting in different keys.

It is a best practice to setup Multifactor Authentication on your root account.

You can create and customize your own password rotation policies from the console.

---

Question: When using Active Directory to authenticate to AWS, what are the correct steps performed?

Answer:
1. The user navigates to ADFS webserver.
2. The user enters their single sign on credentials.
3. The user's web browser receives a SAML a


<!--stackedit_data:
eyJoaXN0b3J5IjpbNDk0MjA3NDA2LC0xMjU5MDI5ODg1LC0xNT
YzNzY1ODgzLDEyNTc0MDQ1MDldfQ==
-->