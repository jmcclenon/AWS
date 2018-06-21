AWS Basic Concepts
-
**Infrastructure**

The AWS Global Infrastructure is currently comprised of **18 AWS Regions** worldwide and **55 Availability Zones**.

---

**Region**: 
Each **AWS Region** is a separate geographic area. Each **AWS Region** has multiple, isolated locations known as Availability Zones.
Each Amazon EC2 region is designed to be completely isolated from the other Amazon EC2 regions. This achieves the greatest possible fault tolerance and stability.

 - US East (**Ohio**) *us-east-2*
 - US East (**N. Virginia**) *us-east-1*
 - US West (**N. California**) *us-west-1*
 - US West (**Oregon**) *us-west-2*
 - Asia Pacific (**Tokyo**) *ap-northeast-1*
 - Asia Pacific (**Seoul**) *ap-northeast-2*
 - Asia Pacific (**Osaka-Local**) *ap-northeast-3*
 - Asia Pacific (**Mumbai**) *ap-south-1*
 - Asia Pacific (**Singapore**) *ap-southeast-1*
 - Asia Pacific (**Sydney**) *ap-southeast-2*
 - Canada (**Central**) *ca-central-1*
 - China (**Beijing**) *cn-north-1*
 - China (**Ningxia**) *cn-northwest-1*
 - EU (**Frankfurt**) *eu-central-1*
 - EU (**Ireland**) *eu-west-1*
 - EU (**London**) *eu-west-2*
 - EU (**Paris**) *eu-west-3*
 - South America (**São Paulo**) *sa-east-1*

---
**Availability Zone**:

An **Availability Zone** is an isolated location inside a region. Each region is made up of several **Availability Zones**. Each **Availability Zone** belongs to a single region. Also, each AZ (as **AWS** experts commonly call **Availability Zones**) is isolated, but the AZs in a region are connected through low-latency links.

---

**Edge Location**:
An **edge location** is where end users access services located at AWS. They are located in most of the major cities around the world and are specifically used by **CloudFront** (CDN) to distribute content to end user to reduce latency. It is like frontend for the service we access which are located in **AWS** cloud.

There are more **Edge Locations** than **Availability Zones**.

---

SaaS, Paas, and Iaas

Cloud computing is a broad term and covers many services. Common cloud computing models are:

Infrastructure as 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTExNzg1MTU2MiwxMTUzMDc0MDU2LDQ5MD
ExNjA3MCwtMTU3MDI4NDE2OCwtMTYwNDcwMDg2NywxNTk4MDE2
OTM5LDkyNjMwMjkwNiw5NjkwODU3OTYsLTE1MDQ2MjkwNSwtMT
c3MTIyOTY0M119
-->