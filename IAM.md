Identity Access Management

IAM consists of the following:

Users
Groups (a way to group our users and apply policies to them collectively)
Roles
Policy Documents (written in JSON using attributes and values)

IAM is universal. It does not apply to regions at this time.

The root account is simply the account created when first your account is first setup. It has complete admin access.

New users have NO permissions when first created.

New users are assigned Access Key ID and Secret Access Keys when first created.

The Access Key ID/Secret Access Keys are not the same as a password, and you cannot use the Access Key ID/Secret Key to login to the console. 

You can use the Access Key ID/Secret Access Key to access AWS via the APIs and command line.

The Access Key/Secret Key are only accessed once, and must be downloaded when presented, usually in CSV format. If these keys are lost, they must be regenerated, resulting in different keys.

It is good


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY1MTA1NzM4MiwtMTU2Mzc2NTg4MywxMj
U3NDA0NTA5XX0=
-->