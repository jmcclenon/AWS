AWS Basic Concepts
-
**Infrastructure**

The AWS Global Infrastructure is currently comprised of **16 AWS Regions** worldwide and 42 availability zones, with **two** additional regions scheduled to come online in 2017. 

**Region**: 
Each **AWS Region** is a separate geographic area. Each **AWS Region** has multiple, isolated locations known as Availability Zones.
Each Amazon EC2 region is designed to be completely isolated from the other Amazon EC2 regions. This achieves the greatest possible fault tolerance and stability.

US East (Ohio)
US East (N. Virginia)
US West (N. California)
US West (Oregon)
Asia Pacific (Tokyo)
Asia Pacific (Seoul)
Asia Pacific (Osaka-Local)
Asia Pacific (Mumbai)
Asia Pacific (Singapore)
Asia Pacific (Sydney)
Canada (Central)
China (Beijing)



**Availability Zone**:
An **Availability Zone** is an isolated location inside a region. Each region is made up by several **Availability Zones**. Each **Availability Zone** belongs to a single region. Also, each AZ (as **AWS** expert commonly call **Availability Zones**) is isolated, but the AZs in a region are connected through low-latency links.

**Edge Location**:
An **edge location** is where end users access services located at AWS. They are located in most of the major cities around the world and are specifically used by CloudFront (CDN) to distribute content to end user to reduce latency. It is like frontend for the service we access which are located in AWS cloud.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk4NjQyNDQ5MywtMTYwNDcwMDg2NywxNT
k4MDE2OTM5LDkyNjMwMjkwNiw5NjkwODU3OTYsLTE1MDQ2Mjkw
NSwtMTc3MTIyOTY0M119
-->