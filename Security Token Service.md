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

Key Terms

Federation: Combining or joining a list of user in one domain (such as IAM) with a list of users in another domain (such as Active Directory, Facebook, etc.)

Identity Broker: A service that allows you to take an identity from point A and join it (federate it) to point B

Identity Store: Ser

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ3NDU0MzMxNSwxMTU3MzUyMzY0XX0=
-->