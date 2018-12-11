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
**SaaS, PaaS, and IaaS**

![Stack and responsibility seperation ](https://thebpmfreak.files.wordpress.com/2012/09/cloud_service_types.jpg)

Cloud computing is a broad term and covers many services. Common cloud computing models are:

Infrastructure as a Service (IaaS)
Platform as a Service (PaaS)
Software as a Service (SaaS)

Iaas: When a service provider offers virtualized hardware or computing infrastructure as a service, such an offering is called IaaS.

PaaS: PaaS is a type of cloud computing service in which a service provider offers application platforms and tools over the cloud, usually to enable application development. In this service model, underlying hardware and software are hosted on the service provider's infrastructure.

SaaS: In the SaaS model, the service provider offers software or applications as services. Such services are hosted by the providers and the end customer simply consumes this SaaS without worrying about the underlying platform, infrastructure, and maintenance.

---

**NIST Definition of Cloud Computing**

Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction. 

This cloud model is composed of five essential characteristics, three service models, and four deployment models. 

**Essential Characteristics:** 

*On-demand self-service:* 

A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction with each service provider. 

*Broad network access:*

 Capabilities are available over the network and accessed through standard mechanisms that promote use by heterogeneous thin or thick client platforms (e.g., mobile phones, tablets, laptops, and workstations). 

*Resource pooling:* 

The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically assigned and reassigned according to consumer demand. There is a sense of location independence in that the customer generally has no control or knowledge over the exact location of the provided resources but may be able to specify location at a higher level of abstraction (e.g., country, state, or datacenter). Examples of resources include storage, processing, memory, and network bandwidth. 

*Rapid elasticity:* 

Capabilities can be elastically provisioned and released, in some cases automatically, to scale rapidly outward and inward commensurate with demand. To the consumer, the capabilities available for provisioning often appear to be unlimited and can be appropriated in any quantity at any time. 

*Measured service:* 

Cloud systems automatically control and optimize resource use by leveraging a metering capability1 at some level of abstraction appropriate to the type of service (e.g., storage, processing, bandwidth, and active user accounts). Resource usage can be monitored, controlled, and reported, providing transparency for both the provider and consumer of the utilized service. 

**Service Models:** 

***Software as a Service (SaaS:.*** 

The capability provided to the consumer is to use the provider’s applications running on a cloud infrastructure2 . The applications are accessible from various client devices through either a thin client interface, such as a web browser (e.g., web-based email), or a program interface. The consumer does not manage or control the underlying cloud infrastructure including network, servers, operating systems, storage, or even individual application capabilities, with the possible exception of limited userspecific application configuration settings. 

***Platform as a Service (PaaS):*** 

The capability provided to the consumer is to deploy onto the cloud infrastructure consumer-created or acquired applications created using programming languages, libraries, services, and tools supported by the provider.

The consumer does not manage or control the underlying cloud infrastructure including network, servers, operating systems, or storage, but has control over the deployed applications and possibly configuration settings for the application-hosting environment. 

***Infrastructure as a Service (IaaS):*** 

The capability provided to the consumer is to provision processing, storage, networks, and other fundamental computing resources where the consumer is able to deploy and run arbitrary software, which can include operating systems and applications. 

The consumer does not manage or control the underlying cloud infrastructure but has control over operating systems, storage, and deployed applications; and possibly limited control of select networking components (e.g., host firewalls). 

**Deployment Models:** 

***Private cloud:*** 

The cloud infrastructure is provisioned for exclusive use by a single organization comprising multiple consumers (e.g., business units). It may be owned, managed, and operated by the organization, a third party, or some combination of them, and it may exist on or off premises. 

**Community cloud:** 

The cloud infrastructure is provisioned for exclusive use by a specific community of consumers from organizations that have shared concerns (e.g., mission, security requirements, policy, and compliance considerations). It may be owned, managed, and operated by one or more of the organizations in the community, a third party, or some combination of them, and it may exist on or off premises. 

***Public cloud:*** 

The cloud infrastructure is provisioned for open use by the general public. It may be owned, managed, and operated by a business, academic, or government organization, or some combination of them. It exists on the premises of the cloud provider. 

***Hybrid cloud:*** 

The cloud infrastructure is a composition of two or more distinct cloud infrastructures (private, community, or public) that remain unique entities, but are bound together by standardized or proprietary technology that enables data and application portability (e.g., cloud bursting for load balancing between clouds).


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUwNjE2MjU5MCwtMjgyNjQ0MDY5LDEzNT
g3NTU0NjMsLTE1MTU5MjU1NDYsMTM1MTc0NDQ4NywtMTQwNDgw
NDk5MiwxMTUzMDc0MDU2LDQ5MDExNjA3MCwtMTU3MDI4NDE2OC
wtMTYwNDcwMDg2NywxNTk4MDE2OTM5LDkyNjMwMjkwNiw5Njkw
ODU3OTYsLTE1MDQ2MjkwNSwtMTc3MTIyOTY0M119
-->