# AWS vs Azure services
- https://learn.microsoft.com/en-us/azure/architecture/aws-professional/services

| Use case   |      AWS      |  Azure | Description |
|:-------------:|:-------------:|:-------------:|:-------------:|
| Regions  |  ap-south-1 | London , Mumbai| |
| Zones |    ap-south-1-a ap-south-b   |   | |
| Fixed IP | Elastic IP |  Static IP | fixed the public IP |
| Monitoring | CloudWatch, X-Ray, Systems Manager | Monitor | |
| Spot instance | Spot instance | Spot instance /vm | temporary compute |
| Resevation compute | reserve instance | reservevm |  |
|  logs |CloudTrail	  | Activity log|The Activity log is a platform log in Azure that provides insight into subscription-level events, such as when a resource is modified or when a virtual machine is started.|
| Paas  | Elastic Beanstalk |App Service | Managed hosting platform providing easy to use services for deploying and scaling web applications and services.|
|Amazon Elastic Container Service (Amazon ECS),AWS Fargate	|   Azure Container Apps | 	Azure Container Apps is a scalable service that lets you deploy thousands of containers without requiring access to the control plane.|
|Amazon Elastic Container Registry (Amazon ECR)|	Azure Container Registry	Container registries store Docker formatted images and create all types of container deployments in the cloud.|
|Amazon Elastic Kubernetes Service (EKS)|	Azure Kubernetes Service (AKS)|	EKS and AKS let you orchestrate Docker containerized application deployments with Kubernetes. AKS simplifies monitoring and cluster management through auto upgrades and a built-in operations console. See Container runtime configuration for specifics on the hosting environment.|
|AWS App Mesh	|Open Service Mesh on AKS|	The Open Service Mesh add-on integrates with features provided by Azure as well as open source projects.|
|AWS Lambda	|Azure Functions, WebJobs in Azure App Service|	Azure Functions is the primary equivalent of AWS Lambda in providing serverless, on-demand code. AWS Lambda functionality also overlaps with Azure WebJobs, which let you schedule or continuously run background tasks.|
|  DataSync | DataSync	 | File Sync| |
|  Simple Storage Services (S3) |Simple Storage Services (S3)  |Blob storage | 	Object storage service, for use cases including cloud applications, content distribution, backup, archiving, disaster recovery, and big data analytics.|
|  EBS | Disk volumes on Amazon Elastic Block Store (EBS) | Data disks in Azure Blob Storage.|Data disks in blob storage provide durable data storage for Azure VMs. This storage is similar to AWS EC2 instance disk volumes on EBS. |
|  Athena |  Azure Synapse Analytics | | |
|  Redshift | Synapse Analytics | | |
| Dynamo DB  | Azure Cosmos DB	 | | |
| Cloud virtual networking  | Virtual Private Cloud (VPC) | Virtual Network| Provides an isolated, private environment in the cloud. Users have control over their virtual networking environment, including selection of their own IP address range, creation of subnets, and configuration of route tables and network gateways.|
|  Virtual network peering |VPC Peering  |VNET Peering | VNet peering is a mechanism that connects two virtual networks (VNets) in the same region through the Azure backbone network. Once peered, the two virtual networks appear as one for all connectivity purposes.|
|   |  | | |
			
			




## Compute
![image](https://user-images.githubusercontent.com/69948118/232262362-e97a67fd-5e52-4678-96f2-49478a09ddb3.png)
### Other Compute Services Comparison
- AWS Batch and Azure Batch – provision tens, hundreds, or thousands of compute resources based on the job requirements.
- AWS Auto Scaling and Azure VM Scale Sets – increase or decrease the number of your resources as demand changes.
- AWS Lambda and Azure Functions – a serverless computing platform to run code in response to events.
- - Amazon ECS, AWS Fargate, and Azure Container Instances – run containerized applications without managing any servers.
- Amazon ECR and Azure Container Registry – a repository to store and manage container images.
- Amazon EKS and Azure Kubernetes Service – simplify the management of your containerized applications across a cluster of nodes.

## Storage
- Amazon S3 vs. Azure Blob
![image](https://user-images.githubusercontent.com/69948118/232262401-41013f76-b642-4914-a836-421be669299d.png)
### Other Storage Services Comparison
- Amazon EBS and Azure Disk – a disk storage to store your data and operating system.
- Amazon EFS  and Azure Files – create and configure file systems and share your files across multiple resources.
- AWS Storage Gateway and Azure StorSimple – simplify storage management by using a hybrid cloud storage solution.
- AWS Snow Family and Azure Data Box – transfer petabytes and exabytes of data to the cloud.

## Database
- Amazon RDS vs. Azure SQL

![image](https://user-images.githubusercontent.com/69948118/232262446-0bebb3e0-4b5e-41ff-8dec-2a204880de20.png)

### Other Database Services Comparison
- Amazon DynamoDB and Azure Cosmos DB – a database model for document and key-value stores.
- Amazon Redshift and Azure Synapse Analytics – a cloud data warehouse service used for analytics and business intelligence tools.
- Amazon ElastiCache and Azure Cache for Redis – an in-memory-based caching service to improve the performance of your existing database.
- AWS DMS and Azure DMS – automate the migration of your data from multiple databases.

## Networking
- Amazon VPC vs. Azure VNet
![image](https://user-images.githubusercontent.com/69948118/232262484-1491d60c-d931-4cac-ab17-986690d15d69.png)

### Other Networking Services Comparison
- AWS VPN Gateway and Azure VPN Gateway – secure connection from your on-premises network to your cloud private network.
- Amazon Route 53 and Azure DNS – helps you manage your DNS records.
- AWS Direct Connect and Azure ExpressRoute – dedicated private connection between the cloud provider and your data center.
- Amazon ELB: NLB and Azure Load Balancer – layer 4 load balancer for TCP and UDP protocols.
- AWS Exam Readiness Courses
- Amazon ELB: ALB and Azure Application Gateway – load balancer for layer 7 traffic (SSL termination, cookie stickiness, and round-robin routing).

## Security and Identity
- AWS Identity & Access Management (IAM) vs. Azure Active Directory & RBAC

![image](https://user-images.githubusercontent.com/69948118/232262505-7fb14f6f-8fba-4f37-962c-05e31017ff63.png)

### Other Security and Identity Services Comparison
- AWS WAF and Azure WAF on Application Gateway – protects web applications from common exploits and vulnerabilities.
- AWS Shield and Azure DDoS Protection – protect your resources from denial of service attacks.
- AWS KMS and Azure Key Vault – create and manage the keys used to encrypt your data.
- AWS Trusted Advisor and Azure Advisor – provides recommendations in operational excellence, security, performance, reliability, and cost.

