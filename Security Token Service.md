## Security Token Service (STS)

Grants users limited and temporary access to AWS resources. Users can come from three sources:

**FEDERATION (typically [Active Directory](https://en.wikipedia.org/wiki/Active_Directory))**

 - Uses Security Assertion Markup Language ([SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language)) 
 - Grants temporary access based off the users Active Directory credentials. 
 - Does not need to be a user in IAM. Single sign on allows users to log into AWS console ***without*** assigning IAM credentials.

**Federation with Mobile Apps**

 - Use Facebook/Amazon/Google or other [OpenID](https://en.wikipedia.org/wiki/OpenID) providers to log in.

**Cross Account Access**

 - Lets users from one AWS account access resources in another AWS account.

---
**Key Terms**

 - [Federation](https://en.wikipedia.org/wiki/Federation_%28information_technology%29): Combining or joining a list of users in one domain (such   as IAM) with a list of users in another domain (such as Active  Directory, Facebook, etc.).

- [Identity Broker](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_common-scenarios_federated-users.html): A service that allows you to take an identity from point A and join it (federate it) to point B.

- [Identity Store](https://en.wikipedia.org/wiki/Identity_management_system): Services like Active Directory, Facebook, Google, etc.

- Identities: a user of service like Facebook, etc.

---

SCENARIO

You are hosting a company website on some EC2 web servers in your VPC. Users of the website must log in to the site which then authenticates against the companies active directory servers which are based on site at the companies headquarters. You VPC is connected to your company HQ via a secure [IPSEC VPN](https://en.wikipedia.org/wiki/IPsec). Once logged in the user can only have access to their own S3 bucket. How do you set this up?

**Scenario 1 Answer (User credentials)**

1. Employee enters their username and password.
2. The application calls an Identity Broker (developed in-house). The broker captures the username and password.
3. The Identity Broker uses the organization's [LDAP](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) directory to validate the employee's identity.
4. The Identity Broker calls the new [GetFederationToken](https://docs.aws.amazon.com/STS/latest/APIReference/API_GetFederationToken.html) function using IAM credentials. The call must include an IAM policy and a duration (1 to 36 hours), along with a policy that specifies the permissions to be granted to the temporary security credentials.
5. The Security Token Service confirms that the policy of the IAM user making the call to GetFederationToken gives permission to create new tokens and then return four values to the application: An access key, a secret access key, a token, and a duration (the token's lifetime).
6. The Identity Broker returns the temporary security credentials to the reporting application.
7. The data storage application uses the temporary security credentials (including the token) to make requests to Amazon S3.
8. Amazon S3 uses IAM to verify that the credentials allow the requested operation on the given S3 bucket and key.
9. IAM provides S3 with the go-ahead to perform the requested operation.

**Scenario 2 Answer (using Roles)**

1.  Develop an Identity Broker to communicate with LDAP and AWS STS.
2. Identity Broker always authenticates with LDAP first, gets an IAM Role associated with the user.
3. Application then authenticates with STS and assumes that IAM role.
4. Application uses that IAM role to interact with S3.

**STEPS (Distilled)**

1. Develop an Identity Broker to communicate with LDAP and AWS STS
2. Identity Broker always authenticated with LDAP first, THEN with AWS STS
3. Application then gets temporary access to AWS resources 

---
**Questions**:

1. What is the name of the service to allow users to use their social media account to gain temporary access to the AWS platform: Web Identity Federation.
2. What is the API call used to obtain temporary security credentials when authenticating using Web Identity Federation: AssumeRoleWithWebIdentity.

  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc3NDk1MDAzOF19
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjA4MTI0NjU4LDIwMjcxNzQ3MDgsMTIxMT
I5MzQwOSw1NTg4NzQwNzksMTM3MTUxNTQyMV19
-->