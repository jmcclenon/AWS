## Elastic Cloud Compute (EC2)

**EC2 Options**

**On Demand**: Allows you to pay a fixed rate by the hour (or by the second) with no commitment. Linux instances are by the second. Windows instances are by the hour (for now).

**Use case:** 

 - Perfect for users that want the low cost and flexibility of Amazon
   EC2 without any up-front payment or long-term commitment.
 - Applications with short term, spiky, or unpredictable workloads that
   cannot be interrupted.
 - Applications being developed or tested on Amazon EC2 for the first
   time.

---

**Reserved**: Provides you with a capacity reservation, and offers a significant discount on the hourly charge for an instance. 1 year or 3 year terms.

**Use case**: 

 - Applications with steady state or predictable usage. Applications
   that require reserved capacity.

 - Users can make up-front payments to reduce their total computing
   costs even further.

 - Standard RIs (up to 75% off on-demand) Convertible RIs (up to 54% off
   on-demand feature the capacity to change the attributes

---

**Spot**: Enables you to bid whatever price you want for instance capacity, providing for even greater savings if your applications have flexible start and end times. Pricing varies...

**Use case**:

---

**Dedicated Hosts**: Physical EC2 server dedicated for your use. Dedicated hosts can help you reduce costs by allowing you to use your existing server-bound software licenses.

**Use Case**:

---
**EC2 Instance Types**
*(Family, Type, vCPUs, Memory, Instance Storage, EBS Opt., Network Performance, IPv6 Support)*

11 Type Families: T, M, C, F, G, P, R, X, D, I, H (*fight mc px rd*)

 - General purpose,t2.nano,1,0.5,EBS only,-,Low to Moderate,Yes
 - General purpose,t2.micro,1,1,EBS only,-,Low to Moderate,Yes
 - General purpose,t2.small,1,2,EBS only,-,Low to Moderate,Yes,
 - General purpose,t2.medium,2,4,EBS only,-,Low to Moderate,Yes
 - General purpose,t2.large,2,8,EBS only,-,Low to Moderate,Yes
 - General purpose,t2.xlarge,4,16,EBS only,-,Moderate,Yes
 - General purpose,t2.2xlarge,8,32,EBS only,-,Moderate,Yes
 - General purpose,m5d.large,2,8,1 x 75 (SSD),Yes,Up to 10 Gigabit,Yes
 - General purpose,m5d.xlarge,4,16,1 x 150 (SSD),Yes,Up to 10
   Gigabit,Yes
 - General purpose,m5d.2xlarge,8,32,1 x 300 (SSD),Yes,Up to 10
   Gigabit,Yes
 - General purpose,m5d.4xlarge,16,64,2 x 300 (SSD),Yes,Up to 10
   Gigabit,Yes
 - General purpose,m5d.12xlarge,48,192,2 x 900 (SSD),Yes,10 Gigabit,Yes
 - General purpose,m5d.24xlarge,96,384,4 x 900 (SSD),Yes,25 Gigabit,Yes
 - General purpose,m5.large,2,8,EBS only,Yes,Up to 10 Gigabit,Yes
 - General purpose,m5.xlarge,4,16,EBS only,Yes,Up to 10 Gigabit,Yes
 - General purpose,m5.2xlarge,8,32,EBS only,Yes,Up to 10 Gigabit,Yes
 - General purpose,m5.4xlarge,16,64,EBS only,Yes,Up to 10 Gigabit,Yes
 - General purpose,m5.12xlarge,48,192,EBS only,Yes,10 Gigabit,Yes
 - General purpose,m5.24xlarge,96,384,EBS only,Yes,25 Gigabit,Yes
 - General purpose,m4.large,2,8,EBS only,Yes,Moderate,Yes
 - General purpose,m4.xlarge,4,16,EBS only,Yes,High,Yes
 - General purpose,m4.2xlarge,8,32,EBS only,Yes,High,Yes
 - General purpose,,m4.4xlarge,16,64,EBS only,Yes,High,Yes
 - General purpose,m4.10xlarge,40,160,EBS only,Yes,10 Gigabit,Yes
 - General purpose,m4.16xlarge,64,256,EBS only,Yes,25 Gigabit,Yes
 - Compute optimized,c5d.large,2,4,1 x 50 (SSD),Yes,Up to 10 Gigabit,Yes
 - Compute optimized,c5d.xlarge,4,8,1 x 100 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Compute optimized,c5d.2xlarge,8,16,1 x 200 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Compute optimized,c5d.4xlarge,16,32,1 x 400 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Compute optimized,c5d.9xlarge,36,72,1 x 900 (SSD),Yes,10 Gigabit,Yes
 - Compute optimized,c5d.18xlarge,72,144,2 x 900 (SSD),Yes,25
   Gigabit,Yes
 - Compute optimized,c5.large,2,4,EBS only,Yes,Up to 10 Gigabit,Yes
 - Compute optimized,c5.xlarge,4,8,EBS only,Yes,Up to 10 Gigabit,Yes
 - Compute optimized,c5.2xlarge,8,16,EBS only,Yes,Up to 10 Gigabit,Yes
 - Compute optimized,c5.4xlarge,16,32,EBS only,Yes,Up to 10 Gigabit,Yes
 - Compute optimized,c5.9xlarge,36,72,EBS only,Yes,10 Gigabit,Yes
 - Compute optimized,c5.18xlarge,72,144,EBS only,Yes,25 Gigabit,Yes
 - Compute optimized,c4.large,2,3.75,EBS only,Yes,Moderate,Yes
 - Compute optimized,c4.xlarge,4,7.5,EBS only,Yes,High,Yes
 - Compute optimized,c4.2xlarge,8,15,EBS only,Yes,High,Yes
 - Compute optimized,c4.4xlarge,16,30,EBS only,Yes,High,Yes
 - Compute optimized,c4.8xlarge,36,60,EBS only,Yes,10 Gigabit,Yes
 - FPGA instances,f1.2xlarge,8,122,1 x 470 (SSD),Yes,Up to 10
   Gigabit,Yes
 - FPGA instances,f1.16xlarge,64,976,4 x 940 (SSD),Yes,25 Gigabit,Yes
 - GPU graphics,g3.4xlarge,16,122,EBS only,Yes,Up to 10 Gigabit,Yes
 - GPU graphics,g3.8xlarge,32,244,EBS only,Yes,10 Gigabit,Yes
 - GPU graphics,g3.16xlarge,64,488,EBS only,Yes,25 Gigabit,Yes
 - GPU instances,g2.2xlarge,8,15,1 x 60 (SSD),Yes,High,-
 - GPU instances,g2.8xlarge,32,60,2 x 120 (SSD),-,10 Gigabit,-
 - GPU compute,p2.xlarge,4,61,EBS only,Yes,High,Yes
 - GPU compute,p2.8xlarge,32,488,EBS only,Yes,10 Gigabit,Yes
 - GPU compute,p2.16xlarge,64,732,EBS only,Yes,25 Gigabit,Yes
 - GPU compute,p3.2xlarge,8,61,EBS only,Yes,Up to 10 Gigabit,Yes
 - GPU compute,p3.8xlarge,32,244,EBS only,Yes,10 Gigabit,Yes
 - GPU compute,p3.16xlarge,64,488,EBS only,Yes,25 Gigabit,Yes
 - Memory optimized,r4.large,2,15.25,EBS only,Yes,Up to 10 Gigabit,Yes
 - Memory optimized,r4.xlarge,4,30.5,EBS only,Yes,Up to 10 Gigabit,Yes
 - Memory optimized,r4.2xlarge,8,61,EBS only,Yes,Up to 10 Gigabit,Yes
 - Memory optimized,r4.4xlarge,16,122,EBS only,Yes,Up to 10 Gigabit,Yes
 - Memory optimized,r4.8xlarge,32,244,EBS only,Yes,10 Gigabit,Yes
 - Memory optimized,r4.16xlarge,64,488,EBS only,Yes,25 Gigabit,Yes
 - Memory optimized,x1.16xlarge,64,976,1 x 1920 (SSD),Yes,10 Gigabit,Yes
 - Memory optimized,x1e.xlarge,4,122,1 x 120 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Memory optimized,x1e.2xlarge,8,244,1 x 240 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Memory optimized,x1e.4xlarge,16,488,1 x 480 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Memory optimized,x1e.8xlarge,32,976,1 x 960 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Memory optimized,x1e.16xlarge,64,1952,1 x 1920 (SSD),Yes,10
   Gigabit,Yes
 - Memory optimized,x1e.32xlarge,128,3904,2 x 1920 (SSD),Yes,25
   Gigabit,Yes
 - Memory optimized,x1.32xlarge,128,1952,2 x 1920 (SSD),Yes,25
   Gigabit,Yes
 - Storage optimized,d2.xlarge,4,30.5,3 x 2048,Yes,Moderate,Yes
 - Storage optimized,d2.2xlarge,8,61,6 x 2048,Yes,High,Yes
 - Storage optimized,d2.4xlarge,16,122,12 x 2048,Yes,High,Yes
 - Storage optimized,d2.8xlarge,36,244,24 x 2048,Yes,10 Gigabit,Yes
 - Storage optimized,i2.xlarge,4,30.5,1 x 800 (SSD),Yes,Moderate,Yes
 - Storage optimized,i2.2xlarge,8,61,2 x 800 (SSD),Yes,High,Yes
 - Storage optimized,i2.4xlarge,16,122,4 x 800 (SSD),Yes,High,Yes
 - Storage optimized,i2.8xlarge,32,244,8 x 800 (SSD),-,10 Gigabit,Yes
 - Storage optimized,h1.2xlarge,8,32,1 x 2000,Yes,Up to 10 Gigabit,Yes
 - Storage optimized,h1.4xlarge,16,64,2 x 2000,Yes,Up to 10 Gigabit,Yes
 - Storage optimized,h1.8xlarge,32,128,4 x 2000,Yes,10 Gigabit,Yes
 - Storage optimized,h1.16xlarge,64,256,8 x 2000,Yes,25 Gigabit,Yes
 - Storage optimized,i3.large,2,15.25,1 x 475 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Storage optimized,i3.xlarge,4,30.5,1 x 950 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Storage optimized,i3.2xlarge,8,61,1 x 1900 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Storage optimized,i3.4xlarge,16,122,2 x 1900 (SSD),Yes,Up to 10
   Gigabit,Yes
 - Storage optimized,i3.8xlarge,32,244,4 x 1900 (SSD),Yes,10 Gigabit,Yes
 - Storage optimized,i3.16xlarge,64,488,8 x 1900 (SSD),Yes,25
   Gigabit,Yes
 - Storage optimized,i3.metal,72,512,8 x 1900 (SSD),Yes,25 Gigabit,Yes

---
Additional Information:

See the following website for a very comprehensive view of EC2 instances, and comparative information:

http://ec2instances.info
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMzczNTY1MTMsLTg0NTY3OTQyOSwtMj
kwNDAwMDMxLC04MDExOTg5NjYsLTkxNzgxNTE0LC0xNTIzNDY1
NzY3LC0xNjQxMTY2NjM2LDIxMTE0ODgyODAsLTE3NTg3MDM0NT
csODc4ODU5MTQyXX0=
-->