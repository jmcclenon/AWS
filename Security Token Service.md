## Security Token Service (STS)

Grants users limited and temporary access to AWS resources. Users can come from three sources:

**FEDERATION (typically Active Directory)**

 - Uses Security Assertion Markup Language (SAML) 
 - Grants temporary access based off the users Active Directory credentials. 
 - Does not need to be a user in IAM Single sign on allows users to log into AWS console without assigning IAM credentials

**Federation with Mobile Apps**

 - Use Facebook/Amazon/Google or other OpenID providers to log in

**Cross Account Access**

 - Lets users from one AWS account account access resources in another  AWS account
---
**Key Terms**

 - [Federation](https://en.wikipedia.org/wiki/Federation_%28information_technology%29): Combining or joining a list of users in one domain (such   as IAM) with a list of users in another domain (such as Active  Directory, Facebook, etc.)

- Identity Broker: A service that allows you to take an identity from point A and join it (federate it) to point B

- Identity Store: Services like Active Directory, Facebook, Google, etc.

- Identities: a user of service like Facebook, etc.

---

SCENARIO

You are hosting a company website on some EC2 web servers in your VPC. Users of the website must log in to the site which then authenticates against the companies active directory servers which are based on site at the companies headquaters. You VPC is connected to your company HQ via a secure IPSEC VPN. Once logged in the user can only have access to their own S3 bucket. How do you set this up?

1. Employee enters their usern

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc4OTIzNzM0NywxNzk0NDQyNDQ2LDEwMz
c2Mjc0NSw2ODA3MzkxMTgsMTE1NzM1MjM2NF19
-->