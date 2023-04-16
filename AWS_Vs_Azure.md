# AWS vs Azure services
- https://learn.microsoft.com/en-us/azure/architecture/aws-professional/services

| Use case   |      AWS      |  Azure | Description
|----------|:-------------:|------:|------:|
| Regions  |  ap-south-1 | London , Mumbai| |
| Zones |    ap-south-1-a ap-south-b   |   | |
| Fixed IP | Elastic IP |  Static IP | fixed the public IP |
| Fixed IP | Elastic IP |  Static IP | fixed the public IP |
| Monitoring | CloudWatch, X-Ray, Systems Manager | Monitor | |
| Spot instance | Spot instance | Spot instance /vm | temporary compute |
| Resevation compute | reserve instance | reservevm |  |
|   |  | | |
|   |  | | |
|   |  | | |
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

