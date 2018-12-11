### Numbers and Symbols

**100-continue**

A method that enables a client to see if a server can accept a request before actually sending it. For large PUT requests, this method can save both time and bandwidth charges.

### A

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

**AAD**

See  [additional authenticated data](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#additional_authenticated_data).

**access control list  (ACL)**

A document that defines who can access a particular  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  or object. Each  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  and object in  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  has an ACL. The document defines what each type of user can do, such as write and read permissions.

**access identifiers**

See  [credentials](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#accesscredentials).

**access key**

The combination of an  [access key ID](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#accesskeyID)  (like  AKIAIOSFODNN7EXAMPLE`) and a  [secret access key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecretAccessKey)(like wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY`). You use access keys to sign API requests that you make to AWS.

**access key ID**

A unique identifier that's associated with a  [secret access key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecretAccessKey); the access key ID and secret access key are used together to sign programmatic AWS requests cryptographically.

**access key rotation**

A method to increase security by changing the AWS access key ID. This method enables you to retire an old key at your discretion.

**access policy language**

A language for writing documents (that is,  [_policies_](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)) that specify who can access a particular AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  and under what conditions.

**account**

A formal relationship with AWS that is associated with (1) the owner email address and password, (2) the control of  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s created under its umbrella, and (3) payment for the AWS activity related to those resources. The AWS account has permission to do anything and everything with all the AWS account resources. This is in contrast to a  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser), which is an entity contained within the account.

**account activity**

A web page showing your month-to-date AWS usage and costs. The account activity page is located at  [https://aws.amazon.com/account-activity/](https://aws.amazon.com/account-activity/).

**ACL**

See  [access control list (ACL)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ACL).

**ACM**

See  [AWS Certificate Manager (ACM)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#acm).

**ACM PCA**

See  [AWS Certificate Manager Private Certificate Authority (ACM PCA)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#acm-pca).

**ACM Private CA**

See  [AWS Certificate Manager Private Certificate Authority (ACM PCA)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#acm-pca).

**action**

An API function. Also called  _operation_  or  _call_. The activity the  [principal](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#principal)  has permission to perform. The action is B in the statement "A has permission to do B to C where D applies." For example, Jane sends a request to  [Amazon SQS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleQueueService)  with Action=ReceiveMessage.

[**Amazon CloudWatch**](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCW): The response initiated by the change in an alarm's state: for example, from OK to ALARM. The state change may be triggered by a metric reaching the alarm threshold, or by a SetAlarmState request. Each alarm can have one or more actions assigned to each state. Actions are performed once each time the alarm changes to a state that has an action assigned, such as an  [Amazon Simple Notification Service](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SNS)notification, an  [Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling)  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  execution or an  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  stop/terminate action.

**active trusted signers**

A list showing each of the trusted signers you've specified and the IDs of the corresponding active key pairs that  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  is aware of. To be able to create working signed URLs, a trusted signer must appear in this list with at least one key pair ID.

**additional authenticated data**

Information that is checked for integrity but not encrypted, such as headers or other contextual metadata.

**administrative suspension**

[Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling)  might suspend processes for  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)  that repeatedly fail to launch instances. Auto Scaling groups that most commonly experience administrative suspension have zero running instances, have been trying to launch instances for more than 24 hours, and have not succeeded in that time.

**alarm**

An item that watches a single metric over a specified time period, and triggers an  [Amazon SNS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SNS)  [topic](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#topic)  or an  [Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling)  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  if the value of the metric crosses a threshold value over a predetermined number of time periods.

**allow**

One of two possible outcomes (the other is  [deny](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#deny)) when an  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  access  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  is evaluated. When a user makes a request to AWS, AWS evaluates the request based on all permissions that apply to the user and then returns either allow or deny.

**Amazon API Gateway**

A fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

See Also  [https://aws.amazon.com/api-gateway](https://aws.amazon.com/apigateway/).

**Amazon AppStream**

A web service for streaming existing Windows applications from the cloud to any device.

See Also  [https://aws.amazon.com/appstream/](https://aws.amazon.com/appstream/).

**Amazon Aurora**

A fully managed MySQL-compatible relational database engine that combines the speed and availability of commercial databases with the simplicity and cost-effectiveness of open source databases.

See Also  [https://aws.amazon.com/rds/aurora/](https://aws.amazon.com/rds/aurora/).

**Amazon Cloud Directory  (Cloud Directory)**

A service that provides a highly scalable directory store for your application’s multihierarchical data.

See Also  [https://aws.amazon.com/cloud-directory/](https://aws.amazon.com/cloud-directory/).

**Amazon CloudFront**

(CloudFront)

An AWS content delivery service that helps you improve the performance, reliability, and availability of your websites and applications.

See Also  [https://aws.amazon.com/cloudfront](https://aws.amazon.com/cloudfront/).

**Amazon CloudSearch**

A fully managed service in the AWS cloud that makes it easy to set up, manage, and scale a search solution for your website or application.

**Amazon CloudWatch**

A web service that enables you to monitor and manage various metrics, and configure alarm actions based on data from those metrics.

See Also  [https://aws.amazon.com/cloudwatch](https://aws.amazon.com/cloudwatch/).

**Amazon CloudWatch Events**

A web service that enables you to deliver a timely stream of system events that describe changes in AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s to  [AWS Lambda](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#lambda)  functions, streams in  [Amazon Kinesis Data Streams](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonKinesisStreams),  [Amazon Simple Notification Service](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SNS)  topics, or built-in targets.

See Also  [https://aws.amazon.com/cloudwatch](https://aws.amazon.com/cloudwatch/).

**Amazon CloudWatch Logs**

A web service for monitoring and troubleshooting your systems and applications from your existing system, application, and custom log files. You can send your existing log files to CloudWatch Logs and monitor these logs in near real-time.

See Also  [https://aws.amazon.com/cloudwatch](https://aws.amazon.com/cloudwatch/).

**Amazon Cognito**

A web service that makes it easy to save mobile user data, such as app preferences or game state, in the AWS cloud without writing any back-end code or managing any infrastructure. Amazon Cognito offers mobile identity management and data synchronization across devices.

See Also  [https://aws.amazon.com/cognito/](https://aws.amazon.com/cognito/).

**Amazon DynamoDB**

A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.

See Also  [https://aws.amazon.com/dynamodb/](https://aws.amazon.com/dynamodb/).

**Amazon DynamoDB Storage Backend for Titan**

A storage backend for the Titan graph database implemented on top of Amazon DynamoDB. Titan is a scalable graph database optimized for storing and querying graphs.

See Also  [https://aws.amazon.com/dynamodb/](https://aws.amazon.com/dynamodb/).

**Amazon DynamoDB Streams**

An AWS service that captures a time-ordered sequence of item-level modifications in any Amazon DynamoDB table, and stores this information in a log for up to 24 hours. Applications can access this log and view the data items as they appeared before and after they were modified, in near real time.

See Also  [https://aws.amazon.com/dynamodb/](https://aws.amazon.com/dynamodb/).

**Amazon Elastic Block Store  (Amazon EBS)**

A service that provides block level storage  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)s for use with  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s.

See Also  [https://aws.amazon.com/ebs](https://aws.amazon.com/ebs/).

**Amazon EBS-backed AMI**

A type of  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  whose  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s use an  [Amazon EBS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS)  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)  as their root device. Compare this with instances launched from  [instance store-backed AMI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancebacked)s, which use the  [instance store](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancestore)  as the root device.

**Amazon Elastic Container Registry  (Amazon ECR)**

A fully managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images. Amazon ECR is integrated with  [Amazon Elastic Container Service  (Amazon ECS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ecs)  and  [AWS Identity and Access Management  (IAM)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM).

See Also  [https://aws.amazon.com/ecr](https://aws.amazon.com/ecr).

Amazon Elastic Container Service  (Amazon ECS)

A highly scalable, fast,  [container](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container)  management service that makes it easy to run, stop, and manage Docker containers on a  [cluster](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cluster)  of  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s.

See Also  [https://aws.amazon.com/ecs](https://aws.amazon.com/ecs).

Amazon ECS service

A service for running and maintaining a specified number of  [task](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task)s (instantiations of a  [task definition](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task_definition)) simultaneously.

Amazon EC2 VM Import Connector

See  [https://aws.amazon.com/ec2/vm-import](https://aws.amazon.com/ec2/vm-import/).

Amazon Elastic Compute Cloud  (Amazon EC2)

A web service that enables you to launch and manage Linux/UNIX and Windows server[instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s in Amazon's data centers.

See Also  [https://aws.amazon.com/ec2](https://aws.amazon.com/ec2/).

Amazon Elastic File System  (Amazon EFS)

A file storage service for  [EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s. Amazon EFS is easy to use and provides a simple interface with which you can create and configure file systems. Amazon EFS storage capacity grows and shrinks automatically as you add and remove files.

See Also  [https://aws.amazon.com/efs/](https://aws.amazon.com/efs/).

Amazon EMR  (Amazon EMR)

A web service that makes it easy to process large amounts of data efficiently. Amazon EMR uses  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  processing combined with several AWS products to do such tasks as web indexing, data mining, log file analysis, machine learning, scientific simulation, and data warehousing.

See Also  [https://aws.amazon.com/elasticmapreduce](https://aws.amazon.com/elasticmapreduce/).

Amazon Elastic Transcoder

A cloud-based media transcoding service. Elastic Transcoder is a highly scalable tool for converting (or  _transcoding_) media files from their source format into versions that will play on devices like smartphones, tablets, and PCs.

See Also  [https://aws.amazon.com/elastictranscoder/](https://aws.amazon.com/elastictranscoder/).

Amazon ElastiCache

A web service that simplifies deploying, operating, and scaling an in-memory cache in the cloud. The service improves the performance of web applications by providing information retrieval from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases.

See Also  [https://aws.amazon.com/elasticache/](https://aws.amazon.com/elasticache/).

Amazon Elasticsearch Service  (Amazon ES)

An AWS managed service for deploying, operating, and scaling Elasticsearch, an open-source search and analytics engine, in the AWS Cloud. Amazon Elasticsearch Service (Amazon ES) also offers security options, high availability, data durability, and direct access to the Elasticsearch APIs.

See Also  [https://aws.amazon.com/elasticsearch-service](https://aws.amazon.com/elasticsearch-service/).

Amazon GameLift

A managed service for deploying, operating, and scaling session-based multiplayer games.

See Also  [https://aws.amazon.com/gamelift/](https://aws.amazon.com/gamelift/).

Amazon Glacier

A secure, durable, and low-cost storage service for data archiving and long-term backup. You can reliably store large or small amounts of data for significantly less than on-premises solutions. Amazon Glacier is optimized for infrequently accessed data, where a retrieval time of several hours is suitable.

See Also  [https://aws.amazon.com/glacier/](https://aws.amazon.com/glacier/).

Amazon GuardDuty

A continuous security monitoring service. Amazon GuardDuty can help to identify unexpected and potentially unauthorized or malicious activity in your AWS environment.

See Also  [https://aws.amazon.com/guardduty/](https://aws.amazon.com/guardduty/).

Amazon Inspector

An automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for vulnerabilities or deviations from best practices. After performing an assessment, Amazon Inspector produces a detailed report with prioritized steps for remediation.

See Also  [https://aws.amazon.com/inspector](https://aws.amazon.com/inspector/).

Amazon Kinesis

A platform for streaming data on AWS. Kinesis offers services that simplify the loading and analysis of streaming data.

See Also  [https://aws.amazon.com/kinesis/](https://aws.amazon.com/kinesis/).

Amazon Kinesis Data Firehose

A fully managed service for loading streaming data into AWS. Kinesis Data Firehose can capture and automatically load streaming data into  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  and  [Amazon Redshift](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#redshift) , enabling near real-time analytics with existing business intelligence tools and dashboards. Kinesis Data Firehose automatically scales to match the throughput of your data and requires no ongoing administration. It can also batch, compress, and encrypt the data before loading it.

See Also  [https://aws.amazon.com/kinesis/firehose/](https://aws.amazon.com/kinesis/firehose/).

Amazon Kinesis Data Streams

A web service for building custom applications that process or analyze streaming data for specialized needs. Amazon Kinesis Data Streams can continuously capture and store terabytes of data per hour from hundreds of thousands of sources.

See Also  [https://aws.amazon.com/kinesis/streams/](https://aws.amazon.com/kinesis/streams/).

Amazon Lightsail

Lightsail is designed to be the easiest way to launch and manage a virtual private server with AWS. Lightsail offers bundled plans that include everything you need to deploy a virtual private server, for a low monthly rate.

See Also  [https://aws.amazon.com/lightsail/](https://aws.amazon.com/lightsail/).

Amazon Lumberyard

A cross-platform, 3D game engine for creating high-quality games. You can connect games to the compute and storage of the AWS cloud and engage fans on Twitch.

See Also  [https://aws.amazon.com/lumberyard/](https://aws.amazon.com/lumberyard/).

Amazon Machine Image  (AMI)

An encrypted machine image stored in  [Amazon Elastic Block Store  (Amazon EBS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS)  or  [Amazon Simple Storage Service](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService). AMIs are like a template of a computer's root drive. They contain the operating system and can also include software and layers of your application, such as database servers, middleware, web servers, and so on.

Amazon Machine Learning

A cloud-based service that creates machine learning (ML) models by finding patterns in your data, and uses these models to process new data and generate predictions.

See Also  [http://aws.amazon.com/machine-learning/](http://aws.amazon.com/machine-learning/).

Amazon Macie

A security service that uses machine learning to automatically discover, classify, and protect sensitive data in AWS.

See Also  [http://aws.amazon.com/macie/](http://aws.amazon.com/macie/).

Amazon ML

See  [Amazon Machine Learning](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#machine-learning).

Amazon Mobile Analytics

(Mobile Analytics)

A service for collecting, visualizing, understanding, and extracting mobile app usage data at scale.

See Also  [https://aws.amazon.com/mobileanalytics](https://aws.amazon.com/mobileanalytics/).

Amazon MQ

A managed message broker service for Apache ActiveMQ that makes it easy to set up and operate message brokers in the cloud.

See Also  [https://aws.amazon.com/amazon-mq/](https://aws.amazon.com/amazon-mq/).

Amazon QuickSight

A fast, cloud-powered business analytics service that makes it easy to build visualizations, perform analysis, and quickly get business insights from your data.

See Also  [https://aws.amazon.com/quicksight/](https://aws.amazon.com/redshift/).

Amazon Redshift

A fully managed, petabyte-scale data warehouse service in the cloud. With Amazon Redshift, you can analyze your data using your existing business intelligence tools.

See Also  [https://aws.amazon.com/redshift/](https://aws.amazon.com/redshift/).

Amazon Relational Database Service  (Amazon RDS)

A web service that makes it easier to set up, operate, and scale a relational database in the cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.

See Also  [https://aws.amazon.com/rds](https://aws.amazon.com/rds/).

Amazon Resource Name  (ARN)

A standardized way to refer to an AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource). For example: arn:aws:iam::123456789012:user/division_abc/subdivision_xyz/Bob.

Amazon Route 53

(Route 53)

A web service you can use to create a new DNS service or to migrate your existing DNS service to the cloud.

See Also  [https://aws.amazon.com/route53](https://aws.amazon.com/route53/).

Amazon S3

See  [Amazon Simple Storage Service (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService).

Amazon S3-Backed AMI

See  [instance store-backed AMI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancebacked).

Amazon Silk

A next-generation web browser available only on Fire OS tablets and phones. Built on a split architecture that divides processing between the client and the AWS cloud, Amazon Silk is designed to create a faster, more responsive mobile browsing experience.

Amazon Simple Email Service  (Amazon SES)

An easy-to-use, cost-effective email solution for applications.

See Also  [https://aws.amazon.com/ses](https://aws.amazon.com/ses/).

Amazon Simple Notification Service  (Amazon SNS)

A web service that enables applications, end-users, and devices to instantly send and receive notifications from the cloud.

See Also  [https://aws.amazon.com/sns](https://aws.amazon.com/sns/).

Amazon Simple Queue Service  (Amazon SQS)

Reliable and scalable hosted queues for storing messages as they travel between computers.

See Also  [https://aws.amazon.com/sqs](https://aws.amazon.com/sqs/).

Amazon Simple Storage Service  (Amazon S3)

Storage for the internet. You can use it to store and retrieve any amount of data at any time, from anywhere on the web.

See Also  [https://aws.amazon.com/s3](https://aws.amazon.com/s3/).

Amazon Simple Workflow Service  (Amazon SWF)

A fully managed service that helps developers build, run, and scale background jobs that have parallel or sequential steps. Amazon SWF is like a state tracker and task coordinator in the cloud.

See Also  [https://aws.amazon.com/swf/](https://aws.amazon.com/swf/).

Amazon Sumerian

A set of tools for creating and running high-quality 3D, augmented reality (AR), and virtual reality (VR) applications on the web.

See Also  [https://aws.amazon.com/sumerian/](https://aws.amazon.com/sumerian/).

Amazon Virtual Private Cloud  (Amazon VPC)

A web service for provisioning a logically isolated section of the AWS cloud where you can launch AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s in a virtual network that you define. You control your virtual networking environment, including selection of your own IP address range, creation of  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet)s, and configuration of  [route table](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#routetable)s and network gateways.

See Also  [https://aws.amazon.com/vpc](https://aws.amazon.com/vpc/).

Amazon VPC

See  [Amazon Virtual Private Cloud (Amazon VPC)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud).

Amazon Web Services  (AWS)

An infrastructure web services platform in the cloud for companies of all sizes.

See Also  [https://aws.amazon.com/what-is-cloud-computing/](https://aws.amazon.com/what-is-cloud-computing/).

Amazon WorkDocs

A managed, secure enterprise document storage and sharing service with administrative controls and feedback capabilities.

See Also  [https://aws.amazon.com/workdocs/](https://aws.amazon.com/workdocs/).

Amazon WorkMail

A managed, secure business email and calendar service with support for existing desktop and mobile email clients.

See Also  [https://aws.amazon.com/workmail/](https://aws.amazon.com/workmail/).

Amazon WorkSpaces

A managed, secure desktop computing service for provisioning cloud-based desktops and providing users access to documents, applications, and  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s from supported devices.

See Also  [https://aws.amazon.com/workspaces/](https://aws.amazon.com/workspaces/).

Amazon WorkSpaces Application Manager  (Amazon WAM)

A web service for deploying and managing applications for Amazon WorkSpaces. Amazon WAM accelerates software deployment, upgrades, patching, and retirement by packaging Windows desktop applications into virtualized application containers.

See Also  [https://aws.amazon.com/workspaces/applicationmanager](https://aws.amazon.com/workspaces/applicationmanager).

AMI

See  [Amazon Machine Image (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage).

analysis scheme

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): Language-specific text analysis options that are applied to a text field to control stemming and configure stopwords and synonyms.

application

[AWS Elastic Beanstalk](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Beanstalk): A logical collection of components, including environments, versions, and environment configurations. An application is conceptually similar to a folder.

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): A name that uniquely identifies the application to be deployed. AWS CodeDeploy uses this name to ensure the correct combination of revision, deployment configuration, and deployment group are referenced during a deployment.

Application Billing

The location where your customers manage the Amazon DevPay products they've purchased. The web address is  [http://www.amazon.com/dp-applications](http://www.amazon.com/dp-applications).

application revision

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): An archive file containing source content—such as source code, web pages, executable files, and deployment scripts—along with an  [application specification file](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#applicationspecificationfile). Revisions are stored in  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)s or  [GitHub](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#github)  repositories. For Amazon S3, a revision is uniquely identified by its Amazon S3 object key and its ETag, version, or both. For GitHub, a revision is uniquely identified by its commit ID.

application specification file

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): A YAML-formatted file used to map the source files in an application revision to destinations on the instance; specify custom permissions for deployed files; and specify scripts to be run on each instance at various stages of the deployment process.

application version

[AWS Elastic Beanstalk](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Beanstalk): A specific, labeled iteration of an application that represents a functionally consistent set of deployable application code. A version points to an  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  object (a JAVA WAR file) that contains the application code.

AppSpec file

See  [application specification file](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#applicationspecificationfile).

AUC

Area Under a Curve. An industry-standard metric to evaluate the quality of a binary classification machine learning model. AUC measures the ability of the model to predict a higher score for positive examples, those that are “correct,” than for negative examples, those that are “incorrect.” The AUC metric returns a decimal value from 0 to 1. AUC values near 1 indicate an ML model that is highly accurate.

ARN

See  [Amazon Resource Name (ARN)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ARN).

artifact

[AWS CodePipeline](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodePipeline): A copy of the files or changes that will be worked upon by the pipeline.

asymmetric encryption

[Encryption](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt)  that uses both a public key and a private key.

asynchronous bounce

A type of  [bounce](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bounce)  that occurs when a  [receiver](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#receiver)  initially accepts an email message for delivery and then subsequently fails to deliver it.

atomic counter

DynamoDB: A method of incrementing or decrementing the value of an existing attribute without interfering with other write requests.

attribute

A fundamental data element, something that does not need to be broken down any further. In DynamoDB, attributes are similar in many ways to fields or columns in other database systems.

Amazon Machine Learning: A unique, named property within an observation in a data set. In tabular data, such as spreadsheets or comma-separated values (.csv) files, the column headings represent the attributes, and the rows contain values for each attribute.

Aurora

See  [Amazon Aurora](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#aurora).

authenticated encryption

[Encryption](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt)  that provides confidentiality, data integrity, and authenticity assurances of the encrypted data.

authentication

The process of proving your identity to a system.

Auto Scaling

A web service designed to launch or terminate  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s automatically based on user-defined  [policies](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy), schedules, and  [health check](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#healthcheck)s.

See Also  [https://aws.amazon.com//autoscaling](https://aws.amazon.com//autoscaling/).

Auto Scaling group

A representation of multiple  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s that share similar characteristics, and that are treated as a logical grouping for the purposes of instance scaling and management.

Availability Zone

A distinct location within a  [Region](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#region)  that is insulated from failures in other Availability Zones, and provides inexpensive, low-latency network connectivity to other Availability Zones in the same Region.

AWS

See  [Amazon Web Services (AWS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#amazonwebservices).

AWS Application Discovery Service

A web service that helps you plan to migrate to AWS by identifying IT assets in a data center—including servers, virtual machines, applications, application dependencies, and network infrastructure.

See Also  [https://aws.amazon.com/about-aws/whats-new/2016/04/aws-application-discovery-service/](https://aws.amazon.com/about-aws/whats-new/2016/04/aws-application-discovery-service/).

AWS AppSync

An enterprise level, fully managed GraphQL service with real-time data synchronization and offline programming features.

See Also  [https://aws.amazon.com/appsync/](https://aws.amazon.com/appsync/).

AWS Billing and Cost Management

The AWS cloud computing model in which you pay for services on demand and use as much or as little at any given time as you need. While  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s are active under your account, you pay for the cost of allocating those resources and for any incidental usage associated with those resources, such as data transfer or allocated storage.

See Also  [https://aws.amazon.com/billing/new-user-faqs/](https://aws.amazon.com/billing/new-user-faqs/).

AWS Certificate Manager  (ACM)

A web service for provisioning, managing, and deploying Secure Sockets Layer/[Transport Layer Security](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#transportlayersecurity)  (SSL/TLS) certificates for use with AWS services.

See Also  [https://aws.amazon.com/certificate-manager/](https://aws.amazon.com/certificate-manager/).

AWS Certificate Manager Private Certificate Authority  (ACM PCA)

A hosted private certificate authority service for issuing and revoking private digital[certificate](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#certificate)s.

See Also  [https://aws.amazon.com/certificate-manager/private-certificate-authority/](https://aws.amazon.com/certificate-manager/private-certificate-authority/).

AWS Cloud9

A cloud-based integrated development environment (IDE) that you use to write, run, and debug code.

See Also  [https://aws.amazon.com/cloud9/](https://aws.amazon.com/cloud9/).

AWS CloudFormation

A service for writing or changing templates that create and delete related AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s together as a unit.

See Also  [https://aws.amazon.com/cloudformation](https://aws.amazon.com/cloudformation/).

AWS CloudHSM

A web service that helps you meet corporate, contractual, and regulatory compliance requirements for data security by using dedicated hardware security module (HSM) appliances within the AWS cloud.

See Also  [https://aws.amazon.com/cloudhsm/](https://aws.amazon.com/cloudhsm/).

AWS CloudTrail

A web service that records AWS API calls for your account and delivers log files to you. The recorded information includes the identity of the API caller, the time of the API call, the source IP address of the API caller, the request parameters, and the response elements returned by the AWS service.

See Also  [https://aws.amazon.com/cloudtrail/](https://aws.amazon.com/cloudtrail/).

AWS CodeCommit

(CodeCommit)

A fully managed source control service that makes it easy for companies to host secure and highly scalable private Git repositories.

See Also  [https://aws.amazon.com/codecommit](https://aws.amazon.com/codecommit/).

AWS CodeDeploy  (CodeDeploy)

A service that automates code deployments to any instance, including  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s and  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s running on-premises.

See Also  [https://aws.amazon.com/codedeploy](https://aws.amazon.com/codedeploy/).

AWS CodeDeploy agent

A software package that, when installed and configured on an instance, enables that instance to be used in AWS CodeDeploy deployments.

AWS CodePipeline

(CodePipeline)

A continuous delivery service for fast and reliable application updates.

See Also  [https://aws.amazon.com/codepipeline](https://aws.amazon.com/codepipeline/).

AWS Command Line Interface  (AWS CLI)

A unified downloadable and configurable tool for managing AWS services. Control multiple AWS services from the command line and automate them through scripts.

See Also  [https://aws.amazon.com/cli/](https://aws.amazon.com/cli/).

AWS Config

A fully managed service that provides an AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  inventory, configuration history, and configuration change notifications for better security and governance. You can create rules that automatically check the configuration of AWS resources that AWS Config records.

See Also  [https://aws.amazon.com/config/](https://aws.amazon.com/config/).

AWS Elemental MediaConvert

A file-based video conversion service that transforms media into formats required for traditional broadcast and for internet streaming to multi-screen devices.

See Also  [https://aws.amazon.com/mediaconvert](https://aws.amazon.com/mediaconvert).

AWS Elemental MediaLive

A video service that lets you easily create live outputs for broadcast and streaming delivery.

See Also  [https://aws.amazon.com/medialive](https://aws.amazon.com/medialive).

AWS Elemental MediaPackage

A just-in-time packaging and origination service that lets you format highly secure and reliable live outputs for a variety of devices.

See Also  [https://aws.amazon.com/mediapackage](https://aws.amazon.com/mediapackage).

AWS Elemental MediaStore

A storage service optimized for media that provides the performance, consistency, and low latency required to deliver live and on-demand video content at scale.

See Also  [https://aws.amazon.com/mediastore](https://aws.amazon.com/mediastore).

AWS Elemental MediaTailor

A video service that lets you serve targeted ads to viewers while maintaining broadcast quality in over-the-top (OTT) video applications.

See Also  [https://aws.amazon.com/mediatailor](https://aws.amazon.com/mediatailor).

AWS Database Migration Service

A web service that can help you migrate data to and from many widely used commercial and open-source databases.

See Also  [https://aws.amazon.com/dms](https://aws.amazon.com/dms).

AWS Data Pipeline

A web service for processing and moving data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals.

See Also  [https://aws.amazon.com/datapipeline](https://aws.amazon.com/datapipeline).

AWS Device Farm

(Device Farm)

An app testing service that allows developers to test Android, iOS, and Fire OS devices on real, physical phones and tablets that are hosted by AWS.

See Also  [https://aws.amazon.com/device-farm](https://aws.amazon.com/device-farm/).

AWS Direct Connect

A web service that simplifies establishing a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your data center, office, or colocation environment.

See Also  [https://aws.amazon.com/directconnect](https://aws.amazon.com/directconnect/).

AWS Directory Service

A managed service for connecting your AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s to an existing on-premises Microsoft Active Directory or to set up and operate a new, standalone directory in the AWS cloud.

See Also  [https://aws.amazon.com/directoryservice](https://aws.amazon.com/directoryservice/).

AWS Elastic Beanstalk

A web service for deploying and managing applications in the AWS Cloud without worrying about the infrastructure that runs those applications.

See Also  [https://aws.amazon.com/elasticbeanstalk](https://aws.amazon.com/elasticbeanstalk/).

AWS Glue

A fully managed  [extract, transform, and load (ETL)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#extracttransformload)  service that you can use to catalog data and load it for analytics. With AWS Glue, you can discover your data, develop scripts to transform sources into targets, and schedule and run ETL jobs in a serverless environment.

See Also  [https://aws.amazon.com/glue](https://aws.amazon.com/glue/).

AWS GovCloud (US)

An isolated AWS Region designed to host sensitive workloads in the cloud, ensuring that this work meets the US government's regulatory and compliance requirements. The AWS GovCloud (US) Region adheres to United States International Traffic in Arms Regulations (ITAR), Federal Risk and Authorization Management Program (FedRAMP) requirements, Department of Defense (DOD) Cloud Security Requirements Guide (SRG) Levels 2 and 4, and Criminal Justice Information Services (CJIS) Security Policy requirements.

See Also  [https://aws.amazon.com/govcloud-us/](https://aws.amazon.com/govcloud-us/).

AWS Glue

Software that lets you run local compute, messaging, data caching, sync, and ML inference capabilities for connected devices in a secure way.

See Also  [https://aws.amazon.com/greengrass](https://aws.amazon.com/greengrass/).

AWS Identity and Access Management  (IAM)

A web service that enables  [Amazon Web Services  (AWS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#amazonwebservices)  customers to manage users and user permissions within AWS.

See Also  [https://aws.amazon.com/iam](https://aws.amazon.com/iam/).

AWS Import/Export

A service for transferring large amounts of data between AWS and portable storage devices.

See Also  [https://aws.amazon.com/importexport](https://aws.amazon.com/importexport/).

AWS IoT

A managed cloud platform that lets connected devices easily and securely interact with cloud applications and other devices.

See Also  [https://aws.amazon.com/iot](https://aws.amazon.com/iot/).

AWS IoT 1-Click

A service that enables simple devices to trigger AWS Lambda functions that can execute an action.

See Also  [https://aws.amazon.com/iot-1-click](https://aws.amazon.com/iot-1-click/).

AWS IoT Analytics

A fully managed service used to run sophisticated analytics on massive volumes of IoT data.

See Also  [https://aws.amazon.com/iot-analytics](https://aws.amazon.com/iot-analytics/).

AWS IoT Device Management

A service used to securely onboard, organize, monitor, and remotely manage IoT devices at scale.

See Also  [https://aws.amazon.com/iot-device-management](https://aws.amazon.com/iot-device-management/).

AWS Key Management Service  (AWS KMS)

A managed service that simplifies the creation and control of  [encryption](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt)  keys that are used to encrypt data.

See Also  [https://aws.amazon.com/kms](https://aws.amazon.com/kms/).

AWS Lambda

A web service that lets you run code without provisioning or managing servers. You can run code for virtually any type of application or back-end service with zero administration. You can set up your code to automatically trigger from other AWS services or call it directly from any web or mobile app.

See Also  [https://aws.amazon.com/lambda/](https://aws.amazon.com/lambda/).

AWS managed key

One of two types of  [customer master key  (CMK)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#customer_master_key)s in  [AWS Key Management Service  (AWS KMS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWS_KMS).

AWS managed policy

An  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [managed policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#managed_policy)  that is created and managed by AWS.

AWS Management Console

A graphical interface to manage compute, storage, and other cloud  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s.

See Also  [https://aws.amazon.com/console](https://aws.amazon.com/console/).

AWS Management Portal for vCenter

A web service for managing your AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s using VMware vCenter. You install the portal as a vCenter plug-in within your existing vCenter environment. Once installed, you can migrate VMware VMs to  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  and manage AWS resources from within vCenter.

See Also  [https://aws.amazon.com/ec2/vcenter-portal/](https://aws.amazon.com/ec2/vcenter-portal/).

AWS Marketplace

A web portal where qualified partners to market and sell their software to AWS customers. AWS Marketplace is an online software store that helps customers find, buy, and immediately start using the software and services that run on AWS.

See Also  [https://aws.amazon.com/partners/aws-marketplace/](https://aws.amazon.com/partners/aws-marketplace/).

AWS Mobile Hub

(Mobile Hub)

An integrated console that for building, testing, and monitoring mobile apps.

See Also  [https://aws.amazon.com/mobile](https://aws.amazon.com/console/).

AWS Mobile SDK

A software development kit whose libraries, code samples, and documentation help you build high quality mobile apps for the iOS, Android, Fire OS, Unity, and Xamarin platforms.

See Also  [https://aws.amazon.com/mobile/sdk](https://aws.amazon.com/mobile/sdk).

AWS OpsWorks

A configuration management service that helps you use Chef to configure and operate groups of instances and applications. You can define the application’s architecture and the specification of each component including package installation, software configuration, and  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s such as storage. You can automate tasks based on time, load, lifecycle events, and more.

See Also  [https://aws.amazon.com/opsworks/](https://aws.amazon.com/opsworks/).

AWS Organizations

An account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage.

See Also  [https://aws.amazon.com/organizations/](https://aws.amazon.com/organizations/).

AWS SDK for C++

A software development kit for that provides C++ APIs for many AWS services including[Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2),  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb), and more. The single, downloadable package includes the AWS C++ library, code samples, and documentation.

See Also  [https://aws.amazon.com/sdk-for-cpp/](https://aws.amazon.com/sdk-for-cpp/).

AWS SDK for Go

A software development kit for integrating your Go application with the full suite of AWS services.

See Also  [https://aws.amazon.com/sdk-for-go/](https://aws.amazon.com/sdk-for-go/).

AWS SDK for Java

A software development kit that provides Java APIs for many AWS services including[Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2),  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb), and more. The single, downloadable package includes the AWS Java library, code samples, and documentation.

See Also  [https://aws.amazon.com/sdk-for-java/](https://aws.amazon.com/sdk-for-java/).

AWS SDK for JavaScript in the Browser

A software development kit for accessing AWS services from JavaScript code running in the browser. Authenticate users through Facebook, Google, or Login with Amazon using web identity federation. Store application data in  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb), and save user files to  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService).

See Also  [http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/](http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/).

AWS SDK for JavaScript in Node.js

A software development kit for accessing AWS services from JavaScript in Node.js. The SDK provides JavaScript objects for AWS services, including  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2),  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb), and  [Amazon Simple Workflow Service  (Amazon SWF)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#swf)  . The single, downloadable package includes the AWS JavaScript library and documentation.

See Also  [http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/](http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/).

AWS SDK for .NET

A software development kit that provides .NET API actions for AWS services including[Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2),  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM), and more. You can download the SDK as multiple service-specific packages on NuGet.

See Also  [https://aws.amazon.com/sdk-for-net/](https://aws.amazon.com/sdk-for-net/).

AWS SDK for PHP

A software development kit and open-source PHP library for integrating your PHP application with AWS services like  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon Glacier](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#glacier), and  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb).

See Also  [https://aws.amazon.com/sdk-for-php/](https://aws.amazon.com/sdk-for-php/).

AWS SDK for Python (Boto)

A software development kit for using Python to access AWS services like  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2),  [Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce),  [Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling),  [Amazon Kinesis](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonKinesis),  [AWS Lambda](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#lambda), and more.

See Also  [http://boto.readthedocs.org/en/latest/](http://boto.readthedocs.org/en/latest/).

AWS SDK for Ruby

A software development kit for accessing AWS services from Ruby. The SDK provides Ruby classes for many AWS services including  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2),  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb). and more. The single, downloadable package includes the AWS Ruby Library and documentation.

See Also  [https://aws.amazon.com/sdk-for-ruby/](https://aws.amazon.com/sdk-for-ruby/).

AWS Security Token Service  (AWS STS)

A web service for requesting temporary, limited-privilege credentials for  [AWS Identity and Access Management  (IAM)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  users or for users that you authenticate ([federated users](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#fed_identity)).

See Also  [https://aws.amazon.com/iam/](https://aws.amazon.com/iam/).

AWS Service Catalog

A web service that helps organizations create and manage catalogs of IT services that are approved for use on AWS. These IT services can include everything from virtual machine images, servers, software, and databases to complete multitier application architectures.

See Also  [https://aws.amazon.com/servicecatalog/](https://aws.amazon.com/servicecatalog/).

AWS Single Sign-On

A cloud-based service that simplifies managing SSO access to AWS accounts and business applications. You can control SSO access and user permissions across all your AWS accounts in AWS Organizations.

See Also  [https://aws.amazon.com/single-sign-on/](https://aws.amazon.com/single-sign-on/).

AWS Step Functions

A web service that coordinates the components of distributed applications as a series of steps in a visual workflow.

See Also  [https://aws.amazon.com/step-functions/](https://aws.amazon.com/step-functions/).

AWS Snowball

A petabyte-scale data transport solution that uses devices designed to be secure to transfer large amounts of data into and out of the AWS Cloud.

See Also  [https://aws.amazon.com/snowball](https://aws.amazon.com/importexport/).

AWS Storage Gateway

A web service that connects an on-premises software appliance with cloud-based storage to provide seamless and secure integration between an organization’s on-premises IT environment and AWS’s storage infrastructure.

See Also  [https://aws.amazon.com/storagegateway/](https://aws.amazon.com/storagegateway/).

AWS Toolkit for Eclipse

An open-source plug-in for the Eclipse Java IDE that makes it easier for developers to develop, debug, and deploy Java applications using Amazon Web Services.

See Also  [https://aws.amazon.com/eclipse/](https://aws.amazon.com/eclipse/).

AWS Toolkit for Visual Studio

An extension for Microsoft Visual Studio that helps developers develop, debug, and deploy .NET applications using Amazon Web Services.

See Also  [https://aws.amazon.com/visualstudio/](https://aws.amazon.com/visualstudio/).

AWS Tools for Windows PowerShell

A set of PowerShell cmdlets to help developers and administrators manage their AWS services from the Windows PowerShell scripting environment.

See Also  [https://aws.amazon.com/powershell/](https://aws.amazon.com/powershell/).

AWS Tools for Microsoft Visual Studio Team Services

Provides tasks you can use in build and release definitions in VSTS to interact with AWS services.

See Also  [https://aws.amazon.com/vsts/](https://aws.amazon.com/vsts/).

AWS Trusted Advisor

A web service that inspects your AWS environment and makes recommendations for saving money, improving system availability and performance, and helping to close security gaps.

See Also  [https://aws.amazon.com/premiumsupport/trustedadvisor/](https://aws.amazon.com/premiumsupport/trustedadvisor/).

AWS VPN CloudHub

Enables secure communication between branch offices using a simple hub-and-spoke model, with or without a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC).

AWS WAF

A web application firewall service that controls access to content by allowing or blocking web requests based on criteria that you specify, such as header values or the IP addresses that the requests originate from. AWS WAF helps protect web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources.

See Also  [https://aws.amazon.com/waf/](https://aws.amazon.com/waf/).

AWS X-Ray

A web service that collects data about requests that your application serves, and provides tools you can use to view, filter, and gain insights into that data to identify issues and opportunities for optimization.

See Also  [https://aws.amazon.com/xray/](https://aws.amazon.com/xray/).

### B

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

basic monitoring

Monitoring of AWS provided metrics derived at a 5-minute frequency.

batch

See  [document batch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#documentbatch).

BGP ASN

Border Gateway Protocol Autonomous System Number. A unique identifier for a network, for use in BGP routing.  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  supports all 2-byte ASN numbers in the range of 1 – 65335, with the exception of 7224, which is reserved.

batch prediction

Amazon Machine Learning: An operation that processes multiple input data observations at one time (asynchronously). Unlike real-time predictions, batch predictions are not available until all predictions have been processed.

See Also  [real-time predictions](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#real-time-predictions).

billing

See  [AWS Billing and Cost Management](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#billing).

binary attribute

Amazon Machine Learning: An attribute for which one of two possible values is possible. Valid positive values are 1, y, yes, t, and true answers. Valid negative values are 0, n, no, f, and false. Amazon Machine Learning outputs 1 for positive values and 0 for negative values.

See Also  [attribute](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#attribute).

binary classification model

Amazon Machine Learning: A machine learning model that predicts the answer to questions where the answer can be expressed as a binary variable. For example, questions with answers of “1” or “0”, “yes” or “no”, “will click” or “will not click” are questions that have binary answers. The result for a binary classification model is always either a “1” (for a “true” or affirmative answers) or a “0” (for a “false” or negative answers).

blacklist

A list of IP addresses, email addresses, or domains that an  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider)suspects to be the source of  [spam](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#spam). The ISP blocks incoming email from these addresses or domains.

block

A data set.  [Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce)  breaks large amounts of data into subsets. Each subset is called a data block. Amazon EMR assigns an ID to each block and uses a hash table to keep track of block processing.

block device

A storage device that supports reading and (optionally) writing data in fixed-size blocks, sectors, or clusters.

block device mapping

A mapping structure for every  [AMI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  and  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  that specifies the block devices attached to the instance.

blue/green deployment

AWS CodeDeploy: A deployment method in which the instances in a deployment group (the original environment) are replaced by a different set of instances (the replacement environment).

bootstrap action

A user-specified default or custom action that runs a script or an application on all nodes of a job flow before  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  starts.

Border Gateway Protocol Autonomous System Number

See  [BGP ASN](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#BGPASN).

bounce

A failed email delivery attempt.

breach

[Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling): The condition in which a user-set threshold (upper or lower boundary) is passed. If the duration of the breach is significant, as set by a breach duration parameter, it can possibly start a  [scaling activity](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ScalingActivity).

bucket

[Amazon Simple Storage Service  (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService): A container for stored objects. Every object is contained in a bucket. For example, if the object named  `photos/puppy.jpg`  is stored in the  `johnsmith`  bucket, then authorized users can access the object with the URL`http://johnsmith.s3.amazonaws.com/photos/puppy.jpg`.

bucket owner

The person or organization that owns a  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  in  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService). Just as Amazon is the only owner of the domain name Amazon.com, only one person or organization can own a bucket.

bundling

A commonly used term for creating an  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage). It specifically refers to creating  [instance store-backed AMI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancebacked)s.

### C

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

cache cluster

A logical cache distributed over multiple  [cache node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CacheNode)s. A cache cluster can be set up with a specific number of cache nodes.

cache cluster identifier

Customer-supplied identifier for the cache cluster that must be unique for that customer in an AWS  [Region](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#region).

cache engine version

The version of the Memcached service that is running on the cache node.

cache node

A fixed-size chunk of secure, network-attached RAM. Each cache node runs an instance of the Memcached service, and has its own DNS name and port. Multiple types of cache nodes are supported, each with varying amounts of associated memory.

cache node type

An  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  type used to run the cache node.

cache parameter group

A container for cache engine parameter values that can be applied to one or more cache clusters.

cache security group

A group maintained by ElastiCache that combines ingress authorizations to cache nodes for hosts belonging to  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  [security group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecurityGroup)s specified through the console or the API or command line tools.

canned access policy

A standard access control policy that you can apply to a  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  or object. Options include: private, public-read, public-read-write, and authenticated-read.

canonicalization

The process of converting data into a standard format that a service such as  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)can recognize.

capacity

The amount of available compute size at a given time. Each  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)  is defined with a minimum and maximum compute size. A  [scaling activity](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ScalingActivity)  increases or decreases the capacity within the defined minimum and maximum values.

cartesian product processor

A processor that calculates a cartesian product. Also known as a  _cartesian data processor_.

cartesian product

A mathematical operation that returns a product from multiple sets.

CDN

See  [content delivery network (CDN)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#content-delivery-network).

certificate

A credential that some AWS products use to authenticate AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)s and users. Also known as an  [X.509 certificate](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#X509)  . The certificate is paired with a private key.

chargeable resources

Features or services whose use incurs fees. Although some AWS products are free, others include charges. For example, in an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  [stack](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#stack), AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s that have been created incur charges. The amount charged depends on the usage load. Use the Amazon Web Services Simple Monthly Calculator at  [http://calculator.s3.amazonaws.com/calc5.html](http://calculator.s3.amazonaws.com/calc5.html)  to estimate your cost prior to creating instances, stacks, or other resources.

CIDR block

Classless Inter-Domain Routing. An internet protocol address allocation and route aggregation methodology.

See Also  [Classless Inter-Domain Routing](http://en.wikipedia.org/wiki/CIDR_notation)  in Wikipedia.

ciphertext

Information that has been  [encrypted](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt), as opposed to  [plaintext](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#plain_text), which is information that has not.

ClassicLink

A feature for linking an EC2-Classic  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  to a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC), allowing your EC2-Classic instance to communicate with VPC instances using private IP addresses.

See Also  [link to VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#LinkToVpc).

See Also  [unlink from VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#UnlinkFromVpc).

classification

In machine learning, a type of problem that seeks to place (classify) a data sample into a single category or “class.” Often, classification problems are modeled to choose one category (class) out of two. These are binary classification problems. Problems where more than two categories (classes) are available are called "multiclass classification" problems.

See Also  [binary classification model](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#binary-classification-model).

See Also  [multiclass classification model](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#multiclass-classification-model).

CLI

See  [AWS Command Line Interface (AWS CLI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awscli).

Cloud Directory

See  [Amazon Cloud Directory (Cloud Directory)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#clouddirectory).

cloud service provider  (CSP)

A company that provides subscribers with access to internet-hosted computing, storage, and software services.

CloudHub

See  [AWS VPN CloudHub](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awsvpncloudhub).

cluster

A logical grouping of  [container instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container_instance)s that you can place  [task](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task)s on.

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): A logical grouping of one or more data nodes, optional dedicated master nodes, and storage required to run Amazon Elasticsearch Service (Amazon ES) and operate your Amazon ES domain.

See Also  [data node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#data-node).

See Also  [dedicated master node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dedicatedmasternode).

See Also  [node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#node).

cluster compute instance

A type of  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  that provides a great amount of CPU power coupled with increased networking performance, making it well suited for High Performance Compute (HPC) applications and other demanding network-bound applications.

cluster placement group

A logical  [cluster compute instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ClusterCompute)  grouping to provide lower latency and high-bandwidth connectivity between the  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s.

cluster status

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): An indicator of the health of a cluster. A status can be green, yellow, or red. At the shard level, green means that all shards are allocated to nodes in a cluster, yellow means that the primary shard is allocated but the replica shards are not, and red means that the primary and replica shards of at least one index are not allocated. The shard status determines the index status, and the index status determines the cluster status.

CMK

See  [customer master key (CMK)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#customer_master_key).

CNAME

Canonical Name Record. A type of  [resource record](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resourcerecord)  in the Domain Name System (DNS) that specifies that the domain name is an alias of another, canonical domain name. More simply, it is an entry in a DNS table that lets you alias one fully qualified domain name to another.

complaint

The event in which a  [recipient](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#recipient)  who does not want to receive an email message clicks "Mark as Spam" within the email client, and the  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider)  sends a notification to  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES).

compound query

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A search request that specifies multiple search criteria using the Amazon CloudSearch structured search syntax.

condition

[IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM): Any restriction or detail about a permission. The condition is  _D_  in the statement "A has permission to do B to C where D applies."

[AWS WAF](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awswaf): A set of attributes that AWS WAF searches for in web requests to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s such as  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  distributions. Conditions can include values such as the IP addresses that web requests originate from or values in request headers. Based on the specified conditions, you can configure AWS WAF to allow or block web requests to AWS resources.

conditional parameter

See  [mapping](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#mapping).

configuration API

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): The API call that you use to create, configure, and manage search domains.

configuration template

A series of key–value pairs that define parameters for various AWS products so that  [AWS Elastic Beanstalk](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Beanstalk)  can provision them for an environment.

consistency model

The method a service uses to achieve high availability. For example, it could involve replicating data across multiple servers in a data center.

See Also  [eventual consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventualconsistency).

console

See  [AWS Management Console](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSManagementConsole).

consolidated billing

A feature of the AWS Organizations service for consolidating payment for multiple AWS accounts. You create an organization that contains your AWS accounts, and you use the master account of your organization to pay for all member accounts. You can see a combined view of AWS costs that are incurred by all accounts in your organization, and you can get detailed cost reports for individual accounts.

container

A Linux container that was created from a Docker image as part of a  [task](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task).

container definition

Specifies which  [Docker image](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#docker_image)  to use for a  [container](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container), how much CPU and memory the container is allocated, and more options. The container definition is included as part of a  [task definition](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task_definition).

container instance

An  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  that is running the  [Amazon Elastic Container Service  (Amazon ECS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ecs)  agent and has been registered into a  [cluster](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cluster). Amazon ECS  [task](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task)s are placed on active container instances.

container registry

Stores, manages, and deploys  [Docker image](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#docker_image)s.

content delivery network (CDN)

A web service that speeds up distribution of your static and dynamic web content—such as .html, .css, .js, media files, and image files—to your users by using a worldwide network of data centers. When a user requests your content, the request is routed to the data center that provides the lowest latency (time delay). If the content is already in the location with the lowest latency, the CDN delivers it immediately. If not, the CDN retrieves it from an origin that you specify (for example, a web server or an Amazon S3 bucket). With some CDNs, you can help secure your content by configuring an HTTPS connection between users and data centers, and between data centers and your origin. Amazon CloudFront is an example of a CDN.

continuous delivery

A software development practice in which code changes are automatically built, tested, and prepared for a release to production.

See Also  [https://aws.amazon.com/devops/continuous-delivery/](https://aws.amazon.com/devops/continuous-delivery/).

continuous integration

A software development practice in which developers regularly merge code changes into a central repository, after which automated builds and tests are run.

See Also  [https://aws.amazon.com/devops/continuous-integration/](https://aws.amazon.com/devops/continuous-integration/).

cooldown period

Amount of time during which  [Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling)  does not allow the desired size of the  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)  to be changed by any other notification from an  [Amazon CloudWatch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCW)  [alarm](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#alarm).

core node

An  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  that runs  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  map and reduce tasks and stores data using the Hadoop Distributed File System (HDFS). Core nodes are managed by the  [master node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#masternode), which assigns Hadoop tasks to nodes and monitors their status. The EC2 instances you assign as core nodes are capacity that must be allotted for the entire job flow run. Because core nodes store data, you can't remove them from a job flow. However, you can add more core nodes to a running job flow.

Core nodes run both the DataNodes and TaskTracker Hadoop daemons.

corpus

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A collection of data that you want to search.

credential helper

[AWS CodeCommit](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeCommit): A program that stores credentials for repositories and supplies them to Git when making connections to those repositories. The  [AWS CLI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awscli)  includes a credential helper that you can use with Git when connecting to AWS CodeCommit repositories.

credentials

Also called  _access credentials_  or  _security credentials_. In authentication and authorization, a system uses credentials to identify who is making a call and whether to allow the requested access.  In AWS, these credentials are typically the  [access key ID](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#accesskeyID)  and the  [secret access key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecretAccessKey).

cross-account access

The process of permitting limited, controlled use of  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s in one AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)  by a user in another AWS account. For example, in  [AWS CodeCommit](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeCommit)  and  [AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy)  you can configure cross-account access so that a user in AWS account A can access an AWS CodeCommit repository created by account B. Or a pipeline in  [AWS CodePipeline](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodePipeline)  created by account A can use AWS CodeDeploy resources created by account B. In  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  you use a  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role)  to  [delegate](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#delegation)  temporary access to a  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)  in one account to resources in another.

cross-Region replication

A client-side solution for maintaining identical copies of  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)  tables across different AWS  [Region](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#region)s, in near real time.

customer gateway

A router or software application on your side of a VPN tunnel that is managed by  [Amazon VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud). The internal interfaces of the customer gateway are attached to one or more devices in your home network. The external interface is attached to the  [virtual private gateway](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPNgateway)across the VPN tunnel.

customer managed policy

An  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [managed policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#managed_policy)  that you create and manage in your AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account).

customer master key  (CMK)

The fundamental  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  that  [AWS Key Management Service  (AWS KMS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWS_KMS)  manages. CMKs can be either customer managed keys or AWS managed keys. Use CMKs inside AWS KMS to  [encrypt](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt)  or decrypt up to 4 kilobytes of data directly or to encrypt generated data keys, which are then used to encrypt or decrypt larger amounts of data outside of the service.

### D

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

dashboard

See  [service health dashboard](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#servicehealthdashboard).

data consistency

A concept that describes when data is written or updated successfully and all copies of the data are updated in all AWS  [Region](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#region)s. However, it takes time for the data to propagate to all storage locations. To support varied application requirements,  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)supports both eventually consistent and strongly consistent reads.

See Also  [eventual consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventualconsistency).

See Also  [eventually consistent read](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventually-consistent-read).

See Also  [strongly consistent read](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#strongly-consistent-read).

data node

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): An Elasticsearch instance that holds data and responds to data upload requests.

See Also  [dedicated master node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dedicatedmasternode).

See Also  [node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#node).

data schema

See  [schema](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#schema).

data source

The database, file, or repository that provides information required by an application or database. For example, in  [AWS OpsWorks](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#opsworks), valid data sources include an  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  for a stack’s MySQL layer or a stack’s  [Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService)  service layer. In  [Amazon Redshift](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#redshift) , valid data sources include text files in an  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket), in an  [Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce)  cluster, or on a remote host that a cluster can access through an SSH connection.

See Also  [datasource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#datasource).

database engine

The database software and version running on the  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance).

database name

The name of a database hosted in a  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance). A DB instance can host multiple databases, but databases hosted by the same DB instance must each have a unique name within that instance.

datasource

[Amazon Machine Learning](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#machine-learning): An object that contains metadata about the input data. Amazon ML reads the input data, computes descriptive statistics on its attributes, and stores the statistics—along with a schema and other information—as part of the datasource object. Amazon ML uses datasources to train and evaluate a machine learning model and generate batch predictions.

See Also  [data source](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#data_source).

DB compute class

Size of the database compute platform used to run the instance.

DB instance

An isolated database environment running in the cloud. A DB instance can contain multiple user-created databases.

DB instance identifier

User-supplied identifier for the DB instance. The identifier must be unique for that user in an AWS  [Region](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#region).

DB parameter group

A container for database engine parameter values that apply to one or more  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance)s.

DB security group

A method that controls access to the  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance). By default, network access is turned off to DB instances. After ingress is configured for a  [security group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecurityGroup), the same rules apply to all DB instances associated with that group.

DB snapshot

A user-initiated point backup of a  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance).

Dedicated Host

A physical server with  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  capacity fully dedicated to a user.

Dedicated Instance

An  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  that is physically isolated at the host hardware level and launched within a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC).

dedicated master node

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): An Elasticsearch instance that performs cluster management tasks, but does not hold data or respond to data upload requests. Amazon Elasticsearch Service (Amazon ES) uses dedicated master nodes to increase cluster stability.

See Also  [data node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#data-node).

See Also  [node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#node).

Dedicated Reserved Instance

An option that you purchase to guarantee that sufficient capacity will be available to launch  [Dedicated Instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#DedicatedInstance)s into a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC).

delegation

Within a single AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account): Giving AWS  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)s access to  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s in your AWS account.

Between two AWS accounts: Setting up a trust between the account that owns the resource (the trusting account), and the account that contains the users that need to access the resource (the trusted account).

See Also  [trust policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#trust_policy).

delete marker

An object with a key and version ID, but without content.  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  inserts delete markers automatically into versioned  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)s when an object is deleted.

deliverability

The likelihood that an email message will arrive at its intended destination.

deliveries

The number of email messages, sent through  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES), that were accepted by an  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider)  for delivery to  [recipient](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#recipient)s over a period of time.

deny

The result of a  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  statement that includes deny as the effect, so that a specific action or actions are expressly forbidden for a user, group, or role. Explicit deny take precedence over explicit  [allow](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#allow).

deployment configuration

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): A set of deployment rules and success and failure conditions used by the service during a deployment.

deployment group

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): A set of individually tagged  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s,  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s in  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)s, or both.

detailed monitoring

Monitoring of AWS provided metrics derived at a 1-minute frequency.

Description property

A property added to parameters,  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s, resource properties, mappings, and outputs to help you to document  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template elements.

dimension

A name–value pair (for example, InstanceType=m1.small, or EngineName=mysql), that contains additional information to identify a metric.

discussion forums

A place where AWS users can post technical questions and feedback to help accelerate their development efforts and to engage with the AWS community. The discussion forums are located at  [https://aws.amazon.com/forums/](https://aws.amazon.com/forums/).

distribution

A link between an origin server (such as an  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)) and a domain name, which  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  automatically assigns. Through this link, CloudFront identifies the object you have stored in your  [origin server](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#originserver).

DKIM

DomainKeys Identified Mail. A standard that email senders use to sign their messages. ISPs use those signatures to verify that messages are legitimate. For more information, see  [http://www.dkim.org](http://www.dkim.org/).

DNS

See  [Domain Name System](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#domainnamesystem).

Docker image

A layered file system template that is the basis of a Docker  [container](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container). Docker images can comprise specific operating systems or applications.

document

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An item that can be returned as a search result. Each document has a collection of fields that contain the data that can be searched or returned. The value of a field can be either a string or a number. Each document must have a unique ID and at least one field.

document batch

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A collection of add and delete document operations. You use the document service API to submit batches to update the data in your search domain.

document service API

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): The API call that you use to submit document batches to update the data in a search domain.

document service endpoint

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): The URL that you connect to when sending document updates to an Amazon CloudSearch domain. Each search domain has a unique document service endpoint that remains the same for the life of the domain.

domain

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): The hardware, software, and data exposed by Amazon Elasticsearch Service (Amazon ES) endpoints. An Amazon ES domain is a service wrapper around an Elasticsearch cluster. An Amazon ES domain encapsulates the engine instances that process Amazon ES requests, the indexed data that you want to search, snapshots of the domain, access policies, and metadata.

See Also  [cluster](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cluster).

See Also  [Elasticsearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Elasticsearch).

Domain Name System

A service that routes internet traffic to websites by translating friendly domain names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.

Donation button

An HTML-coded button to provide an easy and secure way for US-based, IRS-certified 501(c)3 nonprofit organizations to solicit donations.

DynamoDB stream

An ordered flow of information about changes to items in an[Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)  table. When you enable a stream on a table, DynamoDB captures information about every modification to data items in the table.

See Also  [Amazon DynamoDB Streams](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb-streams).

### E

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

EBS

See  [Amazon Elastic Block Store (Amazon EBS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS).

EC2

See  [Amazon Elastic Compute Cloud (Amazon EC2)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2).

EC2 compute unit

(ECU)

An AWS standard for compute CPU and memory. You can use this measure to evaluate the CPU capacity of different  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  types.

EC2 instance

A compute  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  in the  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  service. Other AWS services use the term  _EC2 instance_  to distinguish these instances from other types of instances they support.

ECR

See  [Amazon Elastic Container Registry (Amazon ECR)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ecr).

ECS

See  [Amazon Elastic Container Service (Amazon ECS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ecs).

edge location

A site that  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  uses to cache copies of your content for faster delivery to users at any location.

EFS

See  [Amazon Elastic File System (Amazon EFS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#efs).

Elastic

A company that provides open-source solutions—including Elasticsearch, Logstash, Kibana, and Beats—that are designed to take data from any source and search, analyze, and visualize it in real time.

Amazon Elasticsearch Service (Amazon ES) is an AWS managed service for deploying, operating, and scaling Elasticsearch in the AWS Cloud.

See Also  [Amazon Elasticsearch Service (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService).

See Also  [Elasticsearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Elasticsearch).

Elastic Block Store

See  [Amazon Elastic Block Store (Amazon EBS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS).

Elastic IP address

A fixed (static) IP address that you have allocated in  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  or  [Amazon VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud)  and then attached to an  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance). Elastic IP addresses are associated with your account, not a specific instance. They are  _elastic_  because you can easily allocate, attach, detach, and free them as your needs change. Unlike traditional static IP addresses, Elastic IP addresses allow you to mask instance or  [Availability Zone](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AZ)  failures by rapidly remapping your public IP addresses to another instance.

Elastic Load Balancing

A web service that improves an application's availability by distributing incoming traffic between two or more  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s.

See Also  [https://aws.amazon.com/elasticloadbalancing](https://aws.amazon.com/elasticloadbalancing/).

elastic network interface

An additional network interface that can be attached to an  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance). Elastic network interfaces include a primary private IP address, one or more secondary private IP addresses, an elastic IP address (optional), a MAC address, membership in specified  [security group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecurityGroup)s, a description, and a source/destination check flag. You can create an elastic network interface, attach it to an instance, detach it from an instance, and attach it to another instance.

Elasticsearch

An open source, real-time distributed search and analytics engine used for full-text search, structured search, and analytics. Elasticsearch was developed by the Elastic company.

Amazon Elasticsearch Service (Amazon ES) is an AWS managed service for deploying, operating, and scaling Elasticsearch in the AWS Cloud.

See Also  [Amazon Elasticsearch Service (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService).

See Also  [Elastic](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Elastic).

EMR

See  [Amazon EMR (Amazon EMR)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce).

encrypt

To use a mathematical algorithm to make data unintelligible to unauthorized  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)s while allowing authorized users a method (such as a key or password) to convert the altered data back to its original state.

encryption context

A set of key–value pairs that contains additional information associated with  [AWS Key Management Service  (AWS KMS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWS_KMS)–encrypted information.

endpoint

A URL that identifies a host and port as the entry point for a web service. Every web service request contains an endpoint. Most AWS products provide endpoints for a Region to enable faster connectivity.

[Amazon ElastiCache](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#elasticache): The DNS name of a  [cache node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CacheNode).

[Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService): The DNS name of a  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance).

[AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation): The DNS name or IP address of the server that receives an HTTP request.

endpoint port

[Amazon ElastiCache](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#elasticache): The port number used by a  [cache node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CacheNode).

[Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService): The port number used by a  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance).

envelope encryption

The use of a master key and a data key to algorithmically protect data. The master key is used to encrypt and decrypt the data key and the data key is used to encrypt and decrypt the data itself.

environment

[AWS Elastic Beanstalk](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Beanstalk): A specific running instance of an  [application](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#application). The application has a CNAME and includes an application version and a customizable configuration (which is inherited from the default container type).

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): Instances in a deployment group in a blue/green deployment. At the start of a blue/green deployment, the deployment group is made up of instances in the original environment. At the end of the deployment, the deployment group is made up of instances in the replacement environment.

environment configuration

A collection of parameters and settings that define how an environment and its associated resources behave.

ephemeral store

See  [instance store](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancestore).

epoch

The date from which time is measured. For most Unix environments, the epoch is January 1, 1970.

ETL

See  [extract, transform, and load (ETL)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#extracttransformload).

evaluation

Amazon Machine Learning: The process of measuring the predictive performance of a machine learning (ML) model.

Also a machine learning object that stores the details and result of an ML model evaluation.

evaluation datasource

The data that Amazon Machine Learning uses to evaluate the predictive accuracy of a machine learning model.

eventual consistency

The method through which AWS products achieve high availability, which involves replicating data across multiple servers in Amazon's data centers. When data is written or updated and  `Success`  is returned, all copies of the data are updated. However, it takes time for the data to propagate to all storage locations. The data will eventually be consistent, but an immediate read might not show the change. Consistency is usually reached within seconds.

See Also  [data consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#data-consistency).

See Also  [eventually consistent read](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventually-consistent-read).

See Also  [strongly consistent read](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#strongly-consistent-read).

eventually consistent read

A read process that returns data from only one region and might not show the most recent write information. However, if you repeat your read request after a short time, the response should eventually return the latest data.

See Also  [data consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#data-consistency).

See Also  [eventual consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventualconsistency).

See Also  [strongly consistent read](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#strongly-consistent-read).

eviction

The deletion by  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  of an object from an  [edge location](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#edgeloc)  before its expiration time. If an object in an edge location isn't frequently requested, CloudFront might evict the object (remove the object before its expiration date) to make room for objects that are more popular.

exbibyte

(EiB)

A contraction of exa binary byte, an exbibyte is 2^60 or 1,152,921,504,606,846,976 bytes. An exabyte (EB) is 10^18 or 1,000,000,000,000,000,000 bytes. 1,024 EiB is a  [zebibyte](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#zebibyte).

expiration

For  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  caching, the time when CloudFront stops responding to user requests with an object. If you don't use headers or CloudFront  [distribution](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#distribution)  settings to specify how long you want objects to stay in an  [edge location](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#edgeloc), the objects expire after 24 hours. The next time a user requests an object that has expired, CloudFront forwards the request to the  [origin](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#originserver).

explicit launch permission

An  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  launch permission granted to a specific AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account).

exponential backoff

A strategy that incrementally increases the wait between retry attempts in order to reduce the load on the system and increase the likelihood that repeated requests will succeed. For example, client applications might wait up to 400 milliseconds before attempting the first retry, up to 1600 milliseconds before the second, up to 6400 milliseconds (6.4 seconds) before the third, and so on.

expression

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A numeric expression that you can use to control how search hits are sorted. You can construct Amazon CloudSearch expressions using numeric fields, other rank expressions, a document's default relevance score, and standard numeric operators and functions. When you use the  `sort`  option to specify an expression in a search request, the expression is evaluated for each search hit and the hits are listed according to their expression values.

extract, transform, and load (ETL)

A process that is used to integrate data from multiple sources. Data is collected from sources (extract), converted to an appropriate format (transform), and written to a target data store (load) for purposes of analysis and querying.

ETL tools combine these three functions to consolidate and move data from one environment to another.  [AWS Glue](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Glue)  is a fully managed ETL service for discovering and organizing data, transforming it, and making it available for search and analytics.

### F

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

facet

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An index field that represents a category that you want to use to refine and filter search results.

facet enabled

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An index field option that enables facet information to be calculated for the field.

FBL

See  [feedback loop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#feedbackloop).

feature transformation

Amazon Machine Learning: The machine learning process of constructing more predictive input representations or “features” from the raw input variables to optimize a machine learning model’s ability to learn and generalize. Also known as  _data transformation_  or  _feature engineering_.

federated identity management

(FIM)

Allows individuals to sign in to different networks or services, using the same group or personal credentials to access data across all networks. With identity federation in AWS, external identities (federated users) are granted secure access to  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s in an AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)  without having to create IAM  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)s. These external identities can come from a corporate identity store (such as LDAP or Windows Active Directory) or from a third party (such as Login with Amazon, Facebook, or Google). AWS federation also supports SAML 2.0.

federated user

See  [federated identity management](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#fed_identity).

federation

See  [federated identity management](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#fed_identity).

feedback loop

(FBL)

The mechanism by which a mailbox provider (for example, an  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider)) forwards a  [recipient](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#recipient)'s  [complaint](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#complaint)  back to the  [sender](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sender).

field weight

The relative importance of a text field in a search index. Field weights control how much matches in particular text fields affect a document's relevance score.

filter

A criterion that you specify to limit the results when you list or describe your  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)[resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s.

filter query

A way to filter search results without affecting how the results are scored and sorted. Specified with the  [Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch)  `fq`  parameter.

FIM

See  [federated identity management](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#fed_identity).

Firehose

See  [Amazon Kinesis Data Firehose](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonKinesisFirehose).

format version

See  [template format version](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#template-format-version).

forums

See  [discussion forums](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#discussionforums).

function

See  [intrinsic function](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#intrinsicfunction).

fuzzy search

A simple search query that uses approximate string matching (fuzzy matching) to correct for typographical errors and misspellings.

### G

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

geospatial search

A search query that uses locations specified as a latitude and longitude to determine matches and sort the results.

gibibyte

(GiB)

A contraction of giga binary byte, a gibibyte is 2^30 or 1,073,741,824 bytes. A gigabyte (GB) is 10^9 or 1,000,000,000 bytes. 1,024 GiB is a  [tebibyte](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#tebibyte).

GitHub

A web-based repository that uses Git for version control.

global secondary index

An index with a partition key and a sort key that can be different from those on the table. A global secondary index is considered global because queries on the index can span all of the data in a table, across all partitions.

See Also  [local secondary index](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#local-secondary-index).

grant

[AWS Key Management Service  (AWS KMS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWS_KMS): A mechanism for giving AWS  [principal](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#principal)s long-term permissions to use  [customer master key  (CMK)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#customer_master_key)s.

grant token

A type of identifier that allows the permissions in a  [grant](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#grant_perms)  to take effect immediately.

ground truth

The observations used in the machine learning (ML) model training process that include the correct value for the target attribute. To train an ML model to predict house sales prices, the input observations would typically include prices of previous house sales in the area. The sale prices of these houses constitute the ground truth.

group

A collection of  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)s. You can use IAM groups to simplify specifying and managing permissions for multiple users.

### H

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

Hadoop

Software that enables distributed processing for big data by using clusters and simple programming models. For more information, see  [http://hadoop.apache.org](http://hadoop.apache.org/).

hard bounce

A persistent email delivery failure such as "mailbox does not exist."

hardware VPN

A hardware-based IPsec VPN connection over the internet.

health check

A system call to check on the health status of each instance in an  [Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling)  group.

high-quality email

Email that recipients find valuable and want to receive. Value means different things to different recipients and can come in the form of offers, order confirmations, receipts, newsletters, etc.

highlights

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): Excerpts returned with search results that show where the search terms appear within the text of the matching documents.

highlight enabled

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An index field option that enables matches within the field to be highlighted.

hit

A document that matches the criteria specified in a search request. Also referred to as a  _search result_.

HMAC

Hash-based Message Authentication Code. A specific construction for calculating a message authentication code (MAC) involving a cryptographic hash function in combination with a secret key. You can use it to verify both the data integrity and the authenticity of a message at the same time. AWS calculates the HMAC using a standard, cryptographic hash algorithm, such as SHA-256.

hosted zone

A collection of  [resource record](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resourcerecord)  sets that  [Amazon Route 53](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Route53)  hosts. Like a traditional DNS zone file, a hosted zone represents a collection of records that are managed together under a single domain name.

HVM virtualization

Hardware Virtual Machine virtualization. Allows the guest VM to run as though it is on a native hardware platform, except that it still uses paravirtual (PV) network and storage drivers for improved performance.

See Also  [PV virtualization](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#PV).

### I

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

IAM

See  [AWS Identity and Access Management (IAM)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM).

IAM group

See  [group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#group).

IAM policy simulator

See  [policy simulator](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy_simulator).

IAM role

See  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role).

IAM user

See  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser).

Identity and Access Management

See  [AWS Identity and Access Management (IAM)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM).

identity provider (IdP)

An  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  entity that holds metadata about external identity providers.

IdP

See  [identity provider (IdP)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#identity_provider) .

image

See  [Amazon Machine Image (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage).

import/export station

A machine that uploads or downloads your data to or from  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService).

import log

A report that contains details about how  [AWS Import/Export](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSImportExport)  processed your data.

in-place deployment

AWS CodeDeploy: A deployment method in which the application on each instance in the deployment group is stopped, the latest application revision is installed, and the new version of the application is started and validated. You can choose to use a load balancer so each instance is deregistered during its deployment and then restored to service after the deployment is complete.

index

See  [search index](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#searchindex).

index field

A name–value pair that is included in an  [Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch)  domain's index. An index field can contain text or numeric data, dates, or a location.

indexing options

Configuration settings that define an  [Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch)  domain's index fields, how document data is mapped to those index fields, and how the index fields can be used.

inline policy

An  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  that is embedded in a single IAM  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser),  [group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#group), or  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role).

input data

Amazon Machine Learning: The observations that you provide to Amazon Machine Learning to train and evaluate a machine learning model and generate predictions.

instance

A copy of an  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  running as a virtual server in the AWS cloud.

instance family

A general  [instance type](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancetype)  grouping using either storage or CPU capacity.

instance group

A  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  cluster contains one master instance group that contains one  [master node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#masternode), a core instance group containing one or more  [core node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#corenode)  and an optional  [task node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#tasknode)  instance group, which can contain any number of task nodes.

instance profile

A container that passes  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role)  information to an  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  at launch.

instance store

Disk storage that is physically attached to the host computer for an  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance), and therefore has the same lifespan as the instance. When the instance is terminated, you lose any data in the instance store.

instance store-backed AMI

A type of  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  whose  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)s use an  [instance store](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancestore)  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)  as the root device. Compare this with instances launched from  [Amazon EBS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS)-backed AMIs, which use an Amazon EBS volume as the root device.

instance type

A specification that defines the memory, CPU, storage capacity, and usage cost for an  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance). Some instance types are designed for standard applications, whereas others are designed for CPU-intensive, memory-intensive applications, and so on.

internet gateway

Connects a network to the internet. You can route traffic for IP addresses outside your  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC)  to the internet gateway.

internet service provider

(ISP)

A company that provides subscribers with access to the internet. Many ISPs are also[mailbox provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#mailboxprovider)s. Mailbox providers are sometimes referred to as ISPs, even if they only provide mailbox services.

intrinsic function

A special action in a  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template that assigns values to properties not available until runtime. These functions follow the format  _Fn::Attribute_, such as  `Fn::GetAtt`. Arguments for intrinsic functions can be parameters, pseudo parameters, or the output of other intrinsic functions.

IP address

A numerical address (for example, 192.0.2.44) that networked devices use to communicate with one another using the Internet Protocol (IP). All  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s are assigned two IP addresses at launch, which are directly mapped to each other through network address translation ([NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)): a private IP address (following RFC 1918) and a public IP address. Instances launched in a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud)  are assigned only a private IP address. Instances launched in your default VPC are assigned both a private IP address and a public IP address.

IP match condition

[AWS WAF](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awswaf): An attribute that specifies the IP addresses or IP address ranges that web requests originate from. Based on the specified IP addresses, you can configure AWS WAF to allow or block web requests to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s such as  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)distributions.

ISP

See  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider).

issuer

The person who writes a  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  to grant permissions to a  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource). The issuer (by definition) is always the resource owner. AWS does not permit  [Amazon SQS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleQueueService)  users to create policies for resources they don't own. If John is the resource owner, AWS authenticates John's identity when he submits the policy he's written to grant permissions for that resource.

item

A group of attributes that is uniquely identifiable among all of the other items. Items in  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)  are similar in many ways to rows, records, or tuples in other database systems.

### J

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

job flow

[Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce): One or more  [step](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#step)s that specify all of the functions to be performed on the data.

job ID

A five-character, alphanumeric string that uniquely identifies an  [AWS Import/Export](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSImportExport)storage device in your shipment. AWS issues the job ID in response to a  `CREATE JOB`  email command.

job prefix

An optional string that you can add to the beginning of an  [AWS Import/Export](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSImportExport)  log file name to prevent collisions with objects of the same name.

See Also  [key prefix](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#keyprefix).

JSON

JavaScript Object Notation. A lightweight data interchange format. For information about JSON, see  [http://www.json.org/](http://www.json.org/).

junk folder

The location where email messages that various filters determine to be of lesser value are collected so that they do not arrive in the  [recipient](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#recipient)'s inbox but are still accessible to the recipient. This is also referred to as a  [spam](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#spam)  or bulk folder.

### K

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

key

A credential that identifies an AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)  or  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)  to AWS (such as the AWS  [secret access key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecretAccessKey)).

[Amazon Simple Storage Service  (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon EMR  (Amazon EMR)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce): The unique identifier for an object in a  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket). Every object in a bucket has exactly one key. Because a bucket and key together uniquely identify each object, you can think of Amazon S3 as a basic data map between the  _bucket + key_, and the object itself. You can uniquely address every object in Amazon S3 through the combination of the web service endpoint, bucket name, and key, as in this example:  `http://doc.s3.amazonaws.com/2006-03-01/AmazonS3.wsdl`, where  `doc`  is the name of the bucket, and  `2006-03-01/AmazonS3.wsdl`is the key.

[AWS Import/Export](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSImportExport): The name of an object in Amazon S3. It is a sequence of Unicode characters whose UTF-8 encoding cannot exceed 1024 bytes. If a key, for example, logPrefix + import-log-JOBID, is longer than 1024 bytes,  [AWS Elastic Beanstalk](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Beanstalk)  returns an  `InvalidManifestField`  error.

[IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM): In a  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy), a specific characteristic that is the basis for restricting access (such as the current time, or the IP address of the requester).

Tagging resources: A general  [tag](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#tag)  label that acts like a category for more specific tag values. For example, you might have  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  with the tag key of  _Owner_  and the tag value of_Jan_. You can tag an AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  with up to 10 key–value pairs. Not all AWS resources can be tagged.

key pair

A set of security credentials that you use to prove your identity electronically. A key pair consists of a private key and a public key.

key prefix

A logical grouping of the objects in a  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket). The prefix value is similar to a directory name that enables you to store similar data under the same directory in a bucket.

kibibyte

(KiB)

A contraction of kilo binary byte, a kibibyte is 2^10 or 1,024 bytes. A kilobyte (KB) is 10^3 or 1,000 bytes. 1,024 KiB is a  [mebibyte](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#mebibyte).

KMS

See  [AWS Key Management Service (AWS KMS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWS_KMS).

### L

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

labeled data

In machine learning, data for which you already know the target or “correct” answer.

launch configuration

A set of descriptive parameters used to create new  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s in an  [Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling)activity.

A template that an  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)  uses to launch new EC2 instances. The launch configuration contains information such as the  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  ID, the instance type, key pairs,  [security group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecurityGroup)s, and block device mappings, among other configuration settings.

launch permission

An  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  attribute that allows users to launch an AMI.

lifecycle

The lifecycle state of the  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  contained in an  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup). EC2 instances progress through several states over their lifespan; these include  _Pending_,  _InService_,  _Terminating_  and  _Terminated_.

lifecycle action

An action that can be paused by Auto Scaling, such as launching or terminating an EC2 instance.

lifecycle hook

Enables you to pause Auto Scaling after it launches or terminates an EC2 instance so that you can perform a custom action while the instance is not in service.

link to VPC

The process of linking (or attaching) an EC2-Classic  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  to a ClassicLink-enabled  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC).

See Also  [ClassicLink](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ClassicLink).

See Also  [unlink from VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#UnlinkFromVpc).

load balancer

A DNS name combined with a set of ports, which together provide a destination for all requests intended for your application. A load balancer can distribute traffic to multiple application instances across every  [Availability Zone](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AZ)  within a  [Region](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#region). Load balancers can span multiple Availability Zones within an AWS Region into which an  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  instance was launched. But load balancers cannot span multiple Regions.

local secondary index

An index that has the same partition key as the table, but a different sort key. A local secondary index is local in the sense that every partition of a local secondary index is scoped to a table partition that has the same partition key value.

See Also  [local secondary index](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#local-secondary-index).

logical name

A case-sensitive unique string within an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template that identifies a  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource),  [mapping](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#mapping), parameter, or output. In an AWS CloudFormation template, each parameter,  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource), property, mapping, and output must be declared with a unique logical name. You use the logical name when dereferencing these items using the  `Ref`function.

### M

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

Mail Transfer Agent (MTA)

Software that transports email messages from one computer to another by using a client-server architecture.

mailbox provider

An organization that provides email mailbox hosting services. Mailbox providers are sometimes referred to as  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider)s, even if they only provide mailbox services.

mailbox simulator

A set of email addresses that you can use to test an  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES)-based email sending application without sending messages to actual recipients. Each email address represents a specific scenario (such as a bounce or complaint) and generates a typical response that is specific to the scenario.

main route table

The default  [route table](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#routetable)  that any new  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC)  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet)  uses for routing. You can associate a subnet with a different route table of your choice. You can also change which route table is the main route table.

managed policy

A standalone  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  that you can attach to multiple  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)s,  [group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#group)s, and  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role)s in your IAM  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account). Managed policies can either be AWS managed policies (which are created and managed by AWS) or customer managed policies (which you create and manage in your AWS account).

manifest

When sending a  _create job_  request for an import or export operation, you describe your job in a text file called a manifest. The manifest file is a YAML-formatted file that specifies how to transfer data between your storage device and the AWS cloud.

manifest file

Amazon Machine Learning: The file used for describing batch predictions. The manifest file relates each input data file with its associated batch prediction results. It is stored in the Amazon S3 output location.

mapping

A way to add conditional parameter values to an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template. You specify mappings in the template's optional Mappings section and retrieve the desired value using the  `FN::FindInMap`  function.

marker

See  [pagination token](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#PaginationToken).

master node

A process running on an  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  that keeps track of the work its core and task nodes complete.

maximum price

The maximum price you will pay to launch one or more  [Spot Instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SpotInstance)s. If your maximum price exceeds the current  [Spot price](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SpotPrice)  and your restrictions are met,  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  launches instances on your behalf.

maximum send rate

The maximum number of email messages that you can send per second using  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES).

mebibyte

(MiB)

A contraction of mega binary byte, a mebibyte is 2^20 or 1,048,576 bytes. A megabyte (MB) is 10^6 or 1,000,000 bytes. 1,024 MiB is a  [gibibyte](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#gibibyte).

member resources

See  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource).

message ID

[Amazon Simple Email Service  (Amazon SES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES): A unique identifier that is assigned to every email message that is sent.

[Amazon Simple Queue Service  (Amazon SQS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleQueueService): The identifier returned when you send a message to a queue.

metadata

Information about other data or objects. In  [Amazon Simple Storage Service  (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)and  [Amazon EMR  (Amazon EMR)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce)  metadata takes the form of name–value pairs that describe the object. These include default metadata such as the date last modified and standard HTTP metadata such as Content-Type. Users can also specify custom metadata at the time they store an object. In  [Amazon Elastic Compute Cloud  (Amazon EC2)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)metadata includes data about an  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  that the instance can retrieve to determine things about itself, such as the instance type, the IP address, and so on.

metric

An element of time-series data defined by a unique combination of exactly one  [namespace](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#namespace), exactly one metric name, and between zero and ten dimensions. Metrics and the statistics derived from them are the basis of  [Amazon CloudWatch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCW).

metric name

The primary identifier of a metric, used in combination with a  [namespace](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#namespace)  and optional dimensions.

MFA

See  [multi-factor authentication (MFA)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSMultiFactorAuthentication).

micro instance

A type of  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  that is more economical to use if you have occasional bursts of high CPU activity.

MIME

See  [Multipurpose Internet Mail Extensions (MIME)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#multipurposeinternetmailextensions).

ML model

In machine learning (ML), a mathematical model that generates predictions by finding patterns in data. Amazon Machine Learning supports three types of ML models: binary classification, multiclass classification, and regression. Also known as a  _predictive model_.

See Also  [binary classification model](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#binary-classification-model).

See Also  [multiclass classification model](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#multiclass-classification-model).

See Also  [regression model](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#regression-model).

MTA

See  [Mail Transfer Agent (MTA)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#mailtransferagent).

Multi-AZ deployment

A primary  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance)  that has a synchronous standby replica in a different  [Availability Zone](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AZ). The primary DB instance is synchronously replicated across Availability Zones to the standby replica.

multiclass classification model

A machine learning model that predicts values that belong to a limited, pre-defined set of permissible values. For example, "Is this product a book, movie, or clothing?"

multi-factor authentication  (MFA)

An optional AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)  security feature. Once you enable AWS MFA, you must provide a six-digit, single-use code in addition to your sign-in credentials whenever you access secure AWS webpages or the  [AWS Management Console](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSManagementConsole). You get this single-use code from an authentication device that you keep in your physical possession.

See Also  [https://aws.amazon.com/mfa/](https://aws.amazon.com/mfa/).

multi-valued attribute

An attribute with more than one value.

multipart upload

A feature that allows you to upload a single object as a set of parts.

Multipurpose Internet Mail Extensions (MIME)

An internet standard that extends the email protocol to include non-ASCII text and nontext elements like attachments.

Multitool

A cascading application that provides a simple command-line interface for managing large datasets.

### N

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

namespace

An abstract container that provides context for the items (names, or technical terms, or words) it holds, and allows disambiguation of homonym items residing in different namespaces.

NAT

Network address translation. A strategy of mapping one or more IP addresses to another while data packets are in transit across a traffic routing device. This is commonly used to restrict internet communication to private instances while allowing outgoing traffic.

See Also  [Network Address Translation and Protocol Translation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#networkAddressTranslation).

See Also  [NAT gateway](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#natGateway).

See Also  [NAT instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#natInstance).

NAT gateway

A  [NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)  device, managed by AWS, that performs network address translation in a private  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet), to secure inbound internet traffic. A NAT gateway uses both NAT and port address translation.

See Also  [NAT instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#natInstance).

NAT instance

A  [NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)  device, configured by a user, that performs network address translation in a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC)public  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet)  to secure inbound internet traffic.

See Also  [NAT gateway](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#natGateway).

network ACL

An optional layer of security that acts as a firewall for controlling traffic in and out of a  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet). You can associate multiple subnets with a single network  [ACL](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ACL), but a subnet can be associated with only one network ACL at a time.

Network Address Translation and Protocol Translation

([NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)-PT) An internet protocol standard defined in RFC 2766.

See Also  [NAT instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#natInstance).

See Also  [NAT gateway](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#natGateway).

n-gram processor

A processor that performs n-gram transformations.

See Also  [n-gram transformation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#n-gram-transformation).

n-gram transformation

Amazon Machine Learning: A transformation that aids in text string analysis. An n-gram transformation takes a text variable as input and outputs strings by sliding a window of size  _n_  words, where  _n_  is specified by the user, over the text, and outputting every string of words of size  _n_  and all smaller sizes. For example, specifying the n-gram transformation with window size =2 returns all the two-word combinations and all of the single words.

node

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): An Elasticsearch instance. A node can be either a data instance or a dedicated master instance.

See Also  [dedicated master node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dedicatedmasternode).

NoEcho

A property of  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  parameters that prevent the otherwise default reporting of names and values of a template parameter. Declaring the  `NoEcho`  property causes the parameter value to be masked with asterisks in the report by the  `cfn-describe-stacks`  command.

NoSQL

Nonrelational database systems that are highly available, scalable, and optimized for high performance. Instead of the relational model, NoSQL databases (like  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)) use alternate models for data management, such as key–value pairs or document storage.

null object

A null object is one whose version ID is null.  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  adds a null object to a  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)when  [versioning](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#versioning)  for that bucket is suspended. It is possible to have only one null object for each key in a bucket.

number of passes

The number of times that you allow Amazon Machine Learning to use the same data records to train a machine learning model.

### O

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

object

[Amazon Simple Storage Service  (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService): The fundamental entity type stored in Amazon S3. Objects consist of object data and metadata. The data portion is opaque to Amazon S3.

[Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF): Any entity that can be served either over HTTP or a version of RTMP.

observation

Amazon Machine Learning: A single instance of data that Amazon Machine Learning (Amazon ML) uses to either train a machine learning model how to predict or to generate a prediction. Each row in an Amazon ML input data file is an observation.

On-Demand Instance

An  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  pricing option that charges you for compute capacity by the hour with no long-term commitment.

operation

An API function. Also called an  _action_.

optimistic locking

A strategy to ensure that an item that you want to update has not been modified by others before you perform the update. For  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb), optimistic locking support is provided by the AWS SDKs.

organization

[AWS Organizations](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awsorganizations): An entity that you create to consolidate and manage your AWS accounts. An organization has one master account along with zero or more member accounts.

organizational unit

[AWS Organizations](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awsorganizations): A container for accounts within a  [root](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#root)  of an organization. An organizational unit (OU) can contain other OUs.

origin access identity

Also called OAI. When using  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  to serve content with an  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)[bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  as the origin, a virtual identity that you use to require users to access your content through CloudFront URLs instead of Amazon S3 URLs. Usually used with CloudFront  [private content](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#privatecontent).

origin server

The  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  or custom origin containing the definitive original version of the content you deliver through  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF).

original environment

The instances in a deployment group at the start of an AWS CodeDeploy blue/green deployment.

OSB transformation

Orthogonal sparse bigram transformation. In machine learning, a transformation that aids in text string analysis and that is an alternative to the n-gram transformation. OSB transformations are generated by sliding the window of size  _n_  words over the text, and outputting every pair of words that includes the first word in the window.

See Also  [n-gram transformation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#n-gram-transformation).

OU

See  [organizational unit](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#organizational-unit).

output location

Amazon Machine Learning: An Amazon S3 location where the results of a batch prediction are stored.

### P

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

pagination

The process of responding to an API request by returning a large list of records in small separate parts. Pagination can occur in the following situations:

-   The client sets the maximum number of returned records to a value below the total number of records.
    
-   The service has a default maximum number of returned records that is lower than the total number of records.
    

When an API response is paginated, the service sends a subset of the large list of records and a pagination token that indicates that more records are available. The client includes this pagination token in a subsequent API request, and the service responds with the next subset of records. This continues until the service responds with a subset of records and no pagination token, indicating that all records have been sent.

pagination token

A marker that indicates that an API response contains a subset of a larger list of records. The client can return this marker in a subsequent API request to retrieve the next subset of records until the service responds with a subset of records and no pagination token, indicating that all records have been sent.

See Also  [pagination](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Pagination).

paid AMI

An  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  that you sell to other  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  users on  [AWS Marketplace](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#marketplace).

paravirtual virtualization

See  [PV virtualization](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#PV).

part

A contiguous portion of the object's data in a multipart upload request.

partition key

A simple primary key, composed of one attribute (also known as a  _hash attribute_).

See Also  [partition key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#partition-key).

See Also  [sort key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sort-key).

PAT

Port address translation.

pebibyte

(PiB)

A contraction of peta binary byte, a pebibyte is 2^50 or 1,125,899,906,842,624 bytes. A petabyte (PB) is 10^15 or 1,000,000,000,000,000 bytes. 1,024 PiB is an  [exbibyte](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#exbibyte).

period

See  [sampling period](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SamplingPeriod).

permission

A statement within a  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  that allows or denies access to a particular  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource). You can state any permission like this: "A has permission to do B to C." For example, Jane (A) has permission to read messages (B) from John's  [Amazon SQS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleQueueService)  queue (C). Whenever Jane sends a request to Amazon SQS to use John's queue, the service checks to see if she has permission and if the request satisfies the conditions John set forth in the permission.

persistent storage

A data storage solution where the data remains intact until it is deleted. Options within  [AWS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#amazonwebservices)  include:  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService),  [Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService),  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb), and other services.

physical name

A unique label that  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  assigns to each  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  when creating a  [stack](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#stack). Some AWS CloudFormation commands accept the physical name as a value with the  `--physical-name`  parameter.

pipeline

[AWS CodePipeline](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodePipeline): A workflow construct that defines the way software changes go through a release process.

plaintext

Information that has not been  [encrypted](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt), as opposed to  [ciphertext](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cipher_text).

policy

[IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM): A document defining permissions that apply to a user, group, or role; the permissions in turn determine what users can do in AWS. A policy typically  [allow](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#allow)s access to specific actions, and can optionally grant that the actions are allowed for specific  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s, like  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s,  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)s, and so on. Policies can also explicitly  [deny](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#deny)  access.

[Auto Scaling](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScaling): An object that stores the information needed to launch or terminate instances for an Auto Scaling group. Executing the policy causes instances to be launched or terminated. You can configure an  [alarm](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#alarm)  to invoke an Auto Scaling policy.

policy generator

A tool in the  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [AWS Management Console](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSManagementConsole)  that helps you build a  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  by selecting elements from lists of available options.

policy simulator

A tool in the  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [AWS Management Console](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSManagementConsole)  that helps you test and troubleshoot  [policies](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)so you can see their effects in real-world scenarios.

policy validator

A tool in the  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [AWS Management Console](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSManagementConsole)  that examines your existing IAM access control  [policies](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  to ensure that they comply with the IAM policy grammar.

presigned URL

A web address that uses  [query string authentication](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#querystringauthentication).

prefix

See  [job prefix](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#jobprefix).

Premium Support

A one-on-one, fast-response support channel that AWS customers can subscribe to for support for AWS infrastructure services.

See Also  [https://aws.amazon.com/premiumsupport/](https://aws.amazon.com/premiumsupport/).

primary key

One or two attributes that uniquely identify each item in a  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)  table, so that no two items can have the same key.

See Also  [partition key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#partition-key).

See Also  [sort key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sort-key).

primary shard

See  [shard](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#shard).

principal

The  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser), service, or  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)  that receives permissions that are defined in a  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy). The principal is A in the statement "A has permission to do B to C."

private content

When using  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  to serve content with an  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  as the origin, a method of controlling access to your content by requiring users to use signed URLs. Signed URLs can restrict user access based on the current date and time and/or the IP addresses that the requests originate from.

private IP address

A private numerical address (for example, 192.0.2.44) that networked devices use to communicate with one another using the Internet Protocol (IP). All  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)ss are assigned two IP addresses at launch, which are directly mapped to each other through Network Address Translation ([NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)): a private address (following RFC 1918) and a public address.  _Exception:_  Instances launched in  [Amazon VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud)  are assigned only a private IP address.

private subnet

A  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC)  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet)  whose instances cannot be reached from the internet.

product code

An identifier provided by AWS when you submit a product to  [AWS Marketplace](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#marketplace).

properties

See  [resource property](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resourceproperty).

property rule

A  [JSON](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#json)-compliant markup standard for declaring properties, mappings, and output values in an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template.

Provisioned IOPS

A storage option designed to deliver fast, predictable, and consistent I/O performance. When you specify an IOPS rate while creating a DB instance,  [Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService)  provisions that IOPS rate for the lifetime of the DB instance.

pseudo parameter

A predefined setting, such as  `AWS:StackName`  that can be used in  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)templates without having to declare them. You can use pseudo parameters anywhere you can use a regular parameter.

public AMI

An  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  that all AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)s have permission to launch.

public data set

A large collection of public information that can be seamlessly integrated into AWS cloud-based applications. Amazon stores public data sets at no charge to the community and, like all AWS services, users pay only for the compute and storage they use for their own applications. These data sets currently include data from the Human Genome Project, the U.S. Census, Wikipedia, and other sources.

See Also  [https://aws.amazon.com/publicdatasets](https://aws.amazon.com/publicdatasets/).

public IP address

A pubic numerical address (for example, 192.0.2.44) that networked devices use to communicate with one another using the Internet Protocol (IP).  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s are assigned two IP addresses at launch, which are directly mapped to each other through Network Address Translation ([NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)): a private address (following RFC 1918) and a public address.  _Exception:_  Instances launched in  [Amazon VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud)  are assigned only a private IP address.

public subnet

A  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet)  whose instances can be reached from the internet.

PV virtualization

Paravirtual virtualization. Allows guest VMs to run on host systems that do not have special support extensions for full hardware and CPU virtualization. Because PV guests run a modified operating system that does not use hardware emulation, they cannot provide hardware-related features such as enhanced networking or GPU support.

See Also  [HVM virtualization](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#HVM).

### Q

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

quartile binning transformation

Amazon Machine Learning: A process that takes two inputs, a numerical variable and a parameter called a bin number, and outputs a categorical variable. Quartile binning transformations discover non-linearity in a variable's distribution by enabling the machine learning model to learn separate importance values for parts of the numeric variable’s distribution.

Query

A type of web service that generally uses only the GET or POST HTTP method and a query string with parameters in the URL.

See Also  [REST](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#REST).

query string authentication

An AWS feature that lets you place the authentication information in the HTTP request query string instead of in the  `Authorization`  header, which enables URL-based access to objects in a  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket).

queue

A sequence of messages or jobs that are held in temporary storage awaiting transmission or processing.

queue URL

A web address that uniquely identifies a queue.

quota

[Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService): The maximum number of  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance)s and available storage you can use.

[Amazon ElastiCache](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#elasticache): The maximum number of the following items:

-   The number of cache clusters for each AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)
    
-   The number of cache nodes per cache cluster
    
-   The total number of cache nodes per AWS account across all cache clusters created by that AWS account
    

### R

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

range GET

A request that specifies a byte range of data to get for a download. If an object is large, you can break up a download into smaller units by sending multiple range GET requests that each specify a different byte range to GET.

raw email

A type of  _sendmail_  request with which you can specify the email headers and MIME types.

RDS

See  [Amazon Relational Database Service (Amazon RDS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService).

read replica

[Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService): An active copy of another DB instance. Any updates to the data on the source DB instance are replicated to the read replica DB instance using the built-in replication feature of MySQL 5.1.

real-time predictions

Amazon Machine Learning: Synchronously generated predictions for individual data observations.

See Also  [batch prediction](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#batch-prediction).

receipt handle

[Amazon SQS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleQueueService): An identifier that you get when you receive a message from the queue. This identifier is required to delete a message from the queue or when changing a message's visibility timeout.

receiver

The entity that consists of the network systems, software, and policies that manage email delivery for a  [recipient](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#recipient).

recipient

[Amazon Simple Email Service  (Amazon SES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES): The person or entity receiving an email message. For example, a person named in the "To" field of a message.

Redis

A fast, open source, in-memory key-value data structure store. Redis comes with a set of versatile in-memory data structures with which you can easily create a variety of custom applications.

reference

A means of inserting a property from one AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  into another. For example, you could insert an  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  [security group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecurityGroup)  property into an  [Amazon RDS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonRelationalDatabaseService)  resource.

Region

A named set of AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s in the same geographical area. A Region comprises at least two  [Availability Zone](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AZ)s.

regression model

Amazon Machine Learning: Preformatted instructions for common data transformations that fine-tune machine learning model performance.

regression model

A type of machine learning model that predicts a numeric value, such as the exact purchase price of a house.

regularization

A machine learning (ML) parameter that you can tune to obtain higher-quality ML models. Regularization helps prevent ML models from memorizing training data examples instead of learning how to generalize the patterns it sees (called overfitting). When training data is overfitted, the ML model performs well on the training data but does not perform well on the evaluation data or on new data.

replacement environment

The instances in a deployment group after the AWS CodeDeploy blue/green deployment.

replica shard

See  [shard](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#shard).

reply path

The email address to which an email reply is sent. This is different from the  [return path](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#returnpath).

representational state transfer

See  [REST](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#REST).

reputation

1. An  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES)  metric, based on factors that might include  [bounce](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bounce)s,  [complaint](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#complaint)s, and other metrics, regarding whether or not a customer is sending high-quality email.

2. A measure of confidence, as judged by an  [internet service provider](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#internetserviceprovider)  or other entity that an IP address that they are receiving email from is not the source of  [spam](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#spam).

requester

The person (or application) that sends a request to AWS to perform a specific action. When AWS receives a request, it first evaluates the requester's permissions to determine whether the requester is allowed to perform the request action (if applicable, for the requested  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)).

Requester Pays

An  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  feature that allows a  [bucket owner](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucketowner)  to specify that anyone who requests access to objects in a particular  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket)  must pay the data transfer and request costs.

reservation

A collection of  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s started as part of the same launch request.  Not to be confused with a  [Reserved Instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#reservedinstance).

Reserved Instance

A pricing option for  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s that discounts the  [on-demand](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ondemandinstance)  usage charge for instances that meet the specified parameters. Customers pay for the entire term of the instance, regardless of how they use it.

Reserved Instance Marketplace

An online exchange that matches sellers who have reserved capacity that they no longer need with buyers who are looking to purchase additional capacity.  [Reserved Instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#reservedinstance)s that you purchase from third-party sellers have less than a full standard term remaining and can be sold at different upfront prices. The usage or reoccurring fees remain the same as the fees set when the Reserved Instances were originally purchased. Full standard terms for Reserved Instances available from AWS run for one year or three years.

resource

An entity that users can work with in AWS, such as an  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance), an  [Amazon DynamoDB](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dynamodb)  table, an  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket), an  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  user, an  [AWS OpsWorks](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#opsworks)  [stack](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#stack), and so on.

resource property

A value required when including an AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  in an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  [stack](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#stack). Each resource may have one or more properties associated with it. For example, an`AWS::EC2::Instance`  resource may have a  `UserData`  property. In an AWS CloudFormation template, resources must declare a properties section, even if the resource has no properties.

resource record

Also called  _resource record set_. The fundamental information elements in the Domain Name System (DNS).

See Also  [Domain Name System](http://en.wikipedia.org/wiki/Domain_Name_System)  in Wikipedia.

REST

Representational state transfer. A simple stateless architecture that generally runs over HTTPS/TLS. REST emphasizes that resources have unique and hierarchical identifiers (URIs), are represented by common media types (HTML, XML,  [JSON](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#json), and so on), and that operations on the resources are either predefined or discoverable within the media type. In practice, this generally results in a limited number of operations.

See Also  [Query](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Query).

See Also  [WSDL](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#WSDL).

See Also  [SOAP](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SOAP).

RESTful web service

Also known as RESTful API. A web service that follows  [REST](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#REST)  architectural constraints. The API operations must use HTTP methods explicitly; expose hierarchical URIs; and transfer either XML,  [JSON](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#json), or both.

HTTP-Query

See  [Query](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Query).

return enabled

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An index field option that enables the field's values to be returned in the search results.

return path

The email address to which bounced email is returned. The return path is specified in the header of the original email. This is different from the  [reply path](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#replypath).

revision

[AWS CodePipeline](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodePipeline): A change made to a source that is configured in a source action, such as a pushed commit to a  [GitHub](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#github)  repository or an update to a file in a versioned  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  [bucket](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bucket).

role

A tool for giving temporary access to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s in your AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account).

rollback

A return to a previous state that follows the failure to create an object, such as  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  [stack](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#stack). All  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s associated with the failure are deleted during the rollback. For AWS CloudFormation, you can override this behavior using the  `--disable-rollback`  option on the command line.

root

[AWS Organizations](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awsorganizations): A parent container for the accounts in your organization. If you apply a  [service control policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#service-control-policy)  to the root, it applies to every  [organizational unit](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#organizational-unit)  and account in the organization.

root credentials

Authentication information associated with the AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)  owner.

root device volume

A  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)  that contains the image used to boot the  [instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instance)  (also known as a  _root device_). If you launched the instance from an  [AMI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  backed by  [instance store](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#instancestore), this is an instance store  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)  created from a template stored in  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService). If you launched the instance from an AMI backed by  [Amazon EBS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS), this is an Amazon EBS volume created from an Amazon EBS snapshot.

route table

A set of routing rules that controls the traffic leaving any  [subnet](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#subnet)  that is associated with the route table. You can associate multiple subnets with a single route table, but a subnet can be associated with only one route table at a time.

row identifier

row ID.Amazon Machine Learning: An attribute in the input data that you can include in the evaluation or prediction output to make it easier to associate a prediction with an observation.

rule

[AWS WAF](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awswaf): A set of conditions that AWS WAF searches for in web requests to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s such as  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  distributions. You add rules to a  [web ACL](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#webacl), and then specify whether you want to allow or block web requests based on each rule.

### S

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

S3

See  [Amazon Simple Storage Service (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService).

sampling period

A defined duration of time, such as one minute, over which  [Amazon CloudWatch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCW)computes a  [statistic](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#statistic).

sandbox

A testing location where you can test the functionality of your application without affecting production, incurring charges, or purchasing products.

[Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES): An environment that is designed for developers to test and evaluate the service. In the sandbox, you have full access to the Amazon SES API, but you can only send messages to verified email addresses and the mailbox simulator. To get out of the sandbox, you need to apply for production access. Accounts in the sandbox also have lower  [sending limits](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sendinglimits)  than production accounts.

scale in

To remove EC2 instances from an  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup).

scale out

To add EC2 instances to an  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup).

scaling policy

A description of how Auto Scaling should automatically scale an  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)  in response to changing demand.

See Also  [scale in](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#scale-in).

See Also  [scale out](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#scale-out).

scaling activity

A process that changes the size, configuration, or makeup of an  [Auto Scaling group](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AutoScalingGroup)  by launching or terminating instances.

scheduler

The method used for placing  [task](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task)s on  [container instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container_instance)s.

schema

Amazon Machine Learning: The information needed to interpret the input data for a machine learning model, including attribute names and their assigned data types, and the names of special attributes.

score cut-off value

Amazon Machine Learning: A binary classification models output a score that ranges from 0 to 1. To decide whether an observation should be classified as 1 or 0, you pick a classification threshold, or cut-off, and Amazon ML compares the score against it. Observations with scores higher than the cut-off are predicted as target equals 1, and scores lower than the cut-off are predicted as target equals 0.

SCP

See  [service control policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#service-control-policy).

search API

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): The API that you use to submit search requests to a  [search domain](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#searchdomain).

search domain

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): Encapsulates your searchable data and the search instances that handle your search requests. You typically set up a separate Amazon CloudSearch domain for each different collection of data that you want to search.

search domain configuration

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An domain's indexing options,  [analysis scheme](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#analysisscheme)s,  [expression](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#expression)s,  [suggester](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#suggester)s, access policies, and scaling and availability options.

search enabled

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An index field option that enables the field data to be searched.

search endpoint

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): The URL that you connect to when sending search requests to a search domain. Each Amazon CloudSearch domain has a unique search endpoint that remains the same for the life of the domain.

search index

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A representation of your searchable data that facilitates fast and accurate data retrieval.

search instance

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A compute  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)  that indexes your data and processes search requests. An Amazon CloudSearch domain has one or more search instances, each with a finite amount of RAM and CPU resources. As your data volume grows, more search instances or larger search instances are deployed to contain your indexed data. When necessary, your index is automatically partitioned across multiple search instances. As your request volume or complexity increases, each search partition is automatically replicated to provide additional processing capacity.

search request

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A request that is sent to an Amazon CloudSearch domain's search endpoint to retrieve documents from the index that match particular search criteria.

search result

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): A document that matches a search request. Also referred to as a  _search hit_.

secret access key

A key that is used in conjunction with the  [access key ID](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#accesskeyID)  to cryptographically sign programmatic AWS requests. Signing a request identifies the sender and prevents the request from being altered. You can generate secret access keys for your AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account), individual IAM  [user](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSUser)s, and temporary sessions.

security group

A named set of allowed inbound network connections for an instance. (Security groups in  [Amazon VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonVirtualPrivateCloud)  also include support for outbound connections.) Each security group consists of a list of protocols, ports, and IP address ranges. A security group can apply to multiple instances, and multiple groups can regulate a single instance.

sender

The person or entity sending an email message.

Sender ID

A Microsoft-controlled version of  [SPF](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SPF). An email authentication and anti-spoofing system. For more information about Sender ID, see  [Sender ID](http://wikipedia.org/wiki/Sender_ID)  in Wikipedia.

sending limits

The  [sending quota](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sendingquota)  and  [maximum send rate](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#maximumsendrate)  that are associated with every  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES)account.

sending quota

The maximum number of email messages that you can send using  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES)  in a 24-hour period.

server-side encryption (SSE)

The  [encrypting](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt)  of data at the server level.  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  supports three modes of server-side encryption: SSE-S3, in which Amazon S3 manages the keys; SSE-C, in which the customer manages the keys; and SSE-KMS, in which  [AWS Key Management Service  (AWS KMS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWS_KMS)manages keys.

service

See  [Amazon ECS service](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ecs_service).

service control policy

[AWS Organizations](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awsorganizations): A policy-based control that specifies the services and actions that users and roles can use in the accounts that the service control policy (SCP) affects.

service endpoint

See  [endpoint](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#endpoint).

service health dashboard

A web page showing up-to-the-minute information about AWS service availability. The dashboard is located at  [http://status.aws.amazon.com/](http://status.aws.amazon.com/).

service role

An  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role)  that grants permissions to an AWS service so it can access AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s. The policies that you attach to the service role determine which AWS resources the service can access and what it can do with those resources.

SES

See  [Amazon Simple Email Service (Amazon SES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES).

session

The period during which the temporary security credentials provided by  [AWS Security Token Service  (AWS STS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#STS)  allow access to your AWS account.

SHA

Secure Hash Algorithm. SHA1 is an earlier version of the algorithm, which AWS has deprecated in favor of SHA256.

shard

[Amazon Elasticsearch Service  (Amazon ES)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticsearchService): A partition of data in an index. You can split an index into multiple shards, which can include primary shards (original shards) and replica shards (copies of the primary shards). Replica shards provide failover, which means that a replica shard is promoted to a primary shard if a cluster node that contains a primary shard fails. Replica shards also can handle requests.

shared AMI

An  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  that a developer builds and makes available for others to use.

shutdown action

[Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce): A predefined bootstrap action that launches a script that executes a series of commands in parallel before terminating the job flow.

signature

Refers to a  _digital signature_, which is a mathematical way to confirm the authenticity of a digital message. AWS uses signatures to authenticate the requests you send to our web services. For more information, to  [https://aws.amazon.com/security](https://aws.amazon.com/security/).

SIGNATURE file

[AWS Import/Export](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSImportExport): A file you copy to the root directory of your storage device. The file contains a job ID, manifest file, and a signature.

Signature Version 4

Protocol for authenticating inbound API requests to AWS services in all AWS Regions.

Simple Mail Transfer Protocol

See  [SMTP](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#smtp).

Simple Object Access Protocol

See  [SOAP](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SOAP).

Simple Storage Service

See  [Amazon Simple Storage Service (Amazon S3)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService).

Single Sign-On

See  [AWS Single Sign-On](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#aws-sso).

Single-AZ DB instance

A standard (non-Multi-AZ)  [DB instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#dbinstance)  that is deployed in one  [Availability Zone](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AZ), without a standby replica in another Availability Zone.

See Also  [Multi-AZ deployment](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#multiAZ).

sloppy phrase search

A search for a phrase that specifies how close the terms must be to one another to be considered a match.

SMTP

Simple Mail Transfer Protocol. The standard that is used to exchange email messages between internet hosts for the purpose of routing and delivery.

snapshot

[Amazon Elastic Block Store  (Amazon EBS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#EBS): A backup of your  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)s that is stored in  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService). You can use these snapshots as the starting point for new Amazon EBS volumes or to protect your data for long-term durability.

See Also  [DB snapshot](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#DBSnapshot).

SNS

See  [Amazon Simple Notification Service (Amazon SNS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SNS).

SOAP

Simple Object Access Protocol. An XML-based protocol that lets you exchange information over a particular protocol (HTTP or SMTP, for example) between applications.

See Also  [REST](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#REST).

See Also  [WSDL](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#WSDL).

soft bounce

A temporary email delivery failure such as one resulting from a full mailbox.

software VPN

A software appliance-based VPN connection over the internet.

sort enabled

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): An index field option that enables a field to be used to sort the search results.

sort key

An attribute used to sort the order of partition keys in a composite primary key (also known as a  _range attribute_).

See Also  [partition key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#partition-key).

See Also  [primary key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#primary-key).

source/destination checking

A security measure to verify that an  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  is the origin of all traffic that it sends and the ultimate destination of all traffic that it receives; that is, that the instance is not relaying traffic. Source/destination checking is enabled by default. For instances that function as gateways, such as  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC)  [NAT](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#nat)  instances, source/destination checking must be disabled.

spam

Unsolicited bulk email.

spamtrap

An email address that is set up by an anti-[spam](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#spam)  entity, not for correspondence, but to monitor unsolicited email. This is also called a  _honeypot_.

SPF

Sender Policy Framework. A standard for authenticating email.

See Also  [http://www.openspf.org](http://www.openspf.org/).

Spot Instance

A type of  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  that you can bid on to take advantage of unused  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)capacity.

Spot price

The price for a  [Spot Instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SpotInstance)  at any given time. If your maximum price exceeds the current price and your restrictions are met,  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  launches instances on your behalf.

SQL injection match condition

[AWS WAF](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awswaf): An attribute that specifies the part of web requests, such as a header or a query string, that AWS WAF inspects for malicious SQL code. Based on the specified conditions, you can configure AWS WAF to allow or block web requests to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s such as  [Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  distributions.

SQS

See  [Amazon Simple Queue Service (Amazon SQS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleQueueService).

SSE

See  [server-side encryption (SSE)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#server_side_encryption).

SSL

Secure Sockets Layer

See Also  [Transport Layer Security](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#transportlayersecurity).

SSO

See  [AWS Single Sign-On](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#aws-sso).

stack

[AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation): A collection of AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s that you create and delete as a single unit.

[AWS OpsWorks](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#opsworks): A set of instances that you manage collectively, typically because they have a common purpose such as serving PHP applications. A stack serves as a container and handles tasks that apply to the group of instances as a whole, such as managing applications and cookbooks.

station

[AWS CodePipeline](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodePipeline): A portion of a pipeline workflow where one or more actions are performed.

station

A place at an AWS facility where your AWS Import/Export data is transferred on to, or off of, your storage device.

statistic

One of five functions of the values submitted for a given  [sampling period](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SamplingPeriod). These functions are  `Maximum`,  `Minimum`,  `Sum`,  `Average`, and  `SampleCount`.

stem

The common root or substring shared by a set of related words.

stemming

The process of mapping related words to a common stem. This enables matching on variants of a word. For example, a search for "horse" could return matches for horses, horseback, and horsing, as well as horse.  [Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch)  supports both dictionary based and algorithmic stemming.

step

[Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce): A single function applied to the data in a  [job flow](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#jobflow). The sum of all steps comprises a job flow.

step type

[Amazon EMR](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce): The type of work done in a step. There are a limited number of step types, such as moving data from  [Amazon S3](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonSimpleStorageService)  to  [Amazon EC2](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2)  or from Amazon EC2 to Amazon S3.

sticky session

A feature of the  [Elastic Load Balancing](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ELB)  load balancer that binds a user's session to a specific application instance so that all requests coming from the user during the session are sent to the same application instance. By contrast, a load balancer defaults to route each request independently to the application instance with the smallest load.

stopping

The process of filtering stop words from an index or search request.

stopword

A word that is not indexed and is automatically filtered out of search requests because it is either insignificant or so common that including it would result in too many matches to be useful. Stop words are language-specific.

streaming

[Amazon EMR  (Amazon EMR)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonElasticMapReduce): A utility that comes with  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  that enables you to develop MapReduce executables in languages other than Java.

[Amazon CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF): The ability to use a media file in real time—as it is transmitted in a steady stream from a server.

streaming distribution

A special kind of  [distribution](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#distribution)  that serves streamed media files using a Real Time Messaging Protocol (RTMP) connection.

Streams

See  [Amazon Kinesis Data Streams](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonKinesisStreams).

string-to-sign

Before you calculate an  [HMAC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#HMAC)  signature, you first assemble the required components in a canonical order. The preencrypted string is the string-to-sign.

string match condition

[AWS WAF](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#awswaf): An attribute that specifies the strings that AWS WAF searches for in a web request, such as a value in a header or a query string. Based on the specified strings, you can configure AWS WAF to allow or block web requests to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s such as  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  distributions.

strongly consistent read

A read process that returns a response with the most up-to-date data, reflecting the updates from all prior write operations that were successful—regardless of the region.

See Also  [data consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#data-consistency).

See Also  [eventual consistency](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventualconsistency).

See Also  [eventually consistent read](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#eventually-consistent-read).

structured query

Search criteria specified using the  [Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch)  structured query language. You use the structured query language to construct compound queries that use advanced search options and combine multiple search criteria using Boolean operators.

STS

See  [AWS Security Token Service (AWS STS)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#STS).

subnet

A segment of the IP address range of a  [VPC](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VPC)  that  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)s can be attached to. You can create subnets to group instances according to security and operational needs.

Subscription button

An HTML-coded button that enables an easy way to charge customers a recurring fee.

suggester

[Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch): Specifies an index field you want to use to get autocomplete suggestions and options that can enable fuzzy matches and control how suggestions are sorted.

suggestions

Documents that contain a match for the partial search string in the field designated by the  [suggester](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#suggester).  [Amazon CloudSearch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#cloudSearch)  suggestions include the document IDs and field values for each matching document. To be a match, the string must match the contents of the field starting from the beginning of the field.

supported AMI

An  [Amazon Machine Image  (AMI)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  similar to a  [paid AMI](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#paidAMI), except that the owner charges for additional software or a service that customers use with their own AMIs.

SWF

See  [Amazon Simple Workflow Service (Amazon SWF)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#swf).

symmetric encryption

[Encryption](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#encrypt)  that uses a private key only.

See Also  [asymmetric encryption](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#asymmetric_encryption).

synchronous bounce

A type of  [bounce](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#bounce)  that occurs while the email servers of the  [sender](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sender)  and  [receiver](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#receiver)  are actively communicating.

synonym

A word that is the same or nearly the same as an indexed word and that should produce the same results when specified in a search request. For example, a search for "Rocky Four" or "Rocky 4" should return the fourth  _Rocky_  movie. This can be done by designating that  `four`  and  `4`  are synonyms for  `IV`. Synonyms are language-specific.

### T

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

table

A collection of data. Similar to other database systems, DynamoDB stores data in tables.

tag

Metadata that you can define and assign to AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource)s, such as an  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance). Not all AWS resources can be tagged.

tagging

Tagging resources: Applying a  [tag](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#tag)  to an AWS  [resource](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#resource).

[Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES): Also called  _labeling_. A way to format  [return path](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#returnpath)  email addresses so that you can specify a different return path for each recipient of a message. Tagging enables you to support  [VERP](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#VERP). For example, if Andrew manages a mailing list, he can use the return paths andrew+recipient1@example.net and andrew+recipient2@example.net so that he can determine which email bounced.

target attribute

Amazon Machine Learning (Amazon ML ): The attribute in the input data that contains the “correct” answers. Amazon ML uses the target attribute to learn how to make predictions on new data. For example, if you were building a model for predicting the sale price of a house, the target attribute would be “target sale price in USD.”

target revision

[AWS CodeDeploy  (CodeDeploy)](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodeDeploy): The most recent version of the application revision that has been uploaded to the repository and will be deployed to the instances in a deployment group. In other words, the application revision currently targeted for deployment. This is also the revision that will be pulled for automatic deployments.

task

An instantiation of a  [task definition](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task_definition)  that is running on a  [container instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container_instance).

task definition

The blueprint for your task. Specifies the name of the  [task](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#task), revisions,  [container definition](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#container_definition)s, and  [volume](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#volume)  information.

task node

An  [EC2 instance](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#ec2instance)  that runs  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  map and reduce tasks, but does not store data. Task nodes are managed by the  [master node](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#masternode), which assigns Hadoop tasks to nodes and monitors their status. While a job flow is running you can increase and decrease the number of task nodes. Because they don't store data and can be added and removed from a job flow, you can use task nodes to manage the EC2 instance capacity your job flow uses, increasing capacity to handle peak loads and decreasing it later.

Task nodes only run a TaskTracker Hadoop daemon.

tebibyte

(TiB)

A contraction of tera binary byte, a tebibyte is 2^40 or 1,099,511,627,776 bytes. A terabyte (TB) is 10^12 or 1,000,000,000,000 bytes. 1,024 TiB is a  [pebibyte](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#pebibyte).

template format version

The version of an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template design that determines the available features. If you omit the  `AWSTemplateFormatVersion`  section from your template, AWS CloudFormation assumes the most recent format version.

template validation

The process of confirming the use of  [JSON](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#json)  code in an  [AWS CloudFormation](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#CloudFormation)  template. You can validate any AWS CloudFormation template using the  `cfn-validate-template`command.

temporary security credentials

Authentication information that is provided by  [AWS STS](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#STS)  when you call an STS API action. Includes an  [access key ID](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#accesskeyID), a  [secret access key](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SecretAccessKey), a  [session](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#session)  token, and an expiration time.

throttling

The automatic restricting or slowing down of a process based on one or more limits. Examples:  [Amazon Kinesis Data Streams](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonKinesisStreams)  throttles operations if an application (or group of applications operating on the same stream) attempts to get data from a shard at a rate faster than the shard limit.  [Amazon API Gateway](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#APIGateway)  uses throttling to limit the steady-state request rates for a single account.  [Amazon SES](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#SES)  uses throttling to reject attempts to send email that exceeds the  [sending limits](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#sendinglimits).

time series data

Data provided as part of a metric. The time value is assumed to be when the value occurred. A metric is the fundamental concept for  [Amazon CloudWatch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCW)  and represents a time-ordered set of data points. You publish metric data points into CloudWatch and later retrieve statistics about those data points as a time-series ordered data set.

time stamp

A date/time string in ISO 8601 format.

TLS

See  [Transport Layer Security](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#transportlayersecurity).

tokenization

The process of splitting a stream of text into separate tokens on detectable boundaries such as whitespace and hyphens.

topic

A communication channel to send messages and subscribe to notifications. It provides an access point for publishers and subscribers to communicate with each other.

training datasource

A datasource that contains the data that Amazon Machine Learning uses to train the machine learning model to make predictions.

transition

[AWS CodePipeline](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AWSCodePipeline): The act of a revision in a pipeline continuing from one stage to the next in a workflow.

Transport Layer Security

(TLS)

A cryptographic protocol that provides security for communication over the internet. Its predecessor is Secure Sockets Layer (SSL).

trust policy

An  [IAM](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#IAM)  [policy](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#policy)  that is an inherent part of an IAM  [role](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#role). The trust policy specifies which  [principal](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#principal)s are allowed to use the role.

trusted signers

AWS  [account](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#account)s that the  [CloudFront](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCF)  distribution owner has given permission to create signed URLs for a distribution's content.

tuning

Selecting the number and type of  [AMIs](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonMachineImage)  to run a  [Hadoop](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Hadoop)  job flow most efficiently.

tunnel

A route for transmission of private network traffic that uses the internet to connect nodes in the private network. The tunnel uses encryption and secure protocols such as PPTP to prevent the traffic from being intercepted as it passes through public routing nodes.

### U

[Numbers and Symbols](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#numbers)  |  [A](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#A)  |  [B](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#B)  |  [C](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#C)  |  [D](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#D)  |  [E](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#E)  |  [F](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#F)  |  [G](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#G)  |  [H](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#H)  |  [I](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#I)  |  [J](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#J)  |  [K](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#K)  |  [L](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#L)  |  [M](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#M)  |  [N](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#N)  |  [O](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#O)  |  [P](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#P)  |  [Q](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#Q)  |  [R](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#R)  |  [S](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#S)  |  [T](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#T)|  [U](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#U)  |  [V](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#V)  |  [W](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#W)  |  [X, Y, Z](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#XYZ)

unbounded

The number of potential occurrences is not limited by a set number. This value is often used when defining a data type that is a list (for example,  `maxOccurs="unbounded"`), in  [WSDL](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#WSDL).

unit

Standard measurement for the values submitted to  [Amazon CloudWatch](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html#AmazonCW)  as metric data. Units include seconds, percent, bytes, bits, count, bytes/second, bits/second, count/second, and none.

unlink from VPC

The process of unli
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ1NjQ3NzEzOCwtOTczOTE2MDY3LDY1Mj
U3NTEzMywxMDk0NTQ1MTczXX0=
-->