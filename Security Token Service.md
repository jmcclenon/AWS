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

Federation: Combining or joining a list of user in one domain (such as IAM) with a list of users in another domain (such as Ac

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2OTA4MjY4NjYsMTE1NzM1MjM2NF19
-->