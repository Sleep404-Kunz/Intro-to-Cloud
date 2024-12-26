# Intro-to-Cloud
## Objectives:
- Define cloud computing and describe its benefits.
- Compare and contrast cloud computing service and deployment models.
- Identify the AWS Global Infrastructure.
- Discuss the shared responsibility model.
- Describe the Well-Architected Framework and its role in building flexible and reliable architectures.
- Identify the use, features, and benefits of Amazon Web Services (AWS) core services.
- Practice using AWS core services in a lab environment.
- Describe four entry-level cloud computing careers.


# Intro to Cloud Computing
*Cloud Computing is the on-demand delivery of IT resources over the internet with pay as you go pricing.* This allows companies to focus on product innovation and development while AWS handles the infrastructure. 

## Why Cloud Computing?
- IT assets as programmatic resources to quickly set up and tear down resources/
- Dynamic access to resources for agility and flexibility in meeting customer needs.
- Pay as you go pricing model.

Modern computing is based on the client-server model.
**Client**: Web browser or desktop application that a user interacts with to make requests to servers.
**Servers**: Services such as Amazon Elastic Compute Cloud (EC2). 

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/1.png" alt = "Output" width = "300" />

## Benefits of Cloud computing

- **Trade upfront expense for variable expense**: Pay only for the computing resources consumed instead of maintaining data centers.
- **No infrastructure managment and expenses**: No need to spend money or time managing physical infrastructure allowing for undivided focus on the product and customers. 
- **Stop guessing capacity**: No need to estimate how much infrastructure is needed before deployment.
- **Scalability with savings**: Using the services with many others allows for AWS to provide lower cost to each service users.
- **Speed, agility and flexibility**: Faster development and deployment of products, saving time and money.
- **Global in minutes**: AWS services availble world-wide allows for deployment globally within minutes.

## Deployment models

1. **Infrastructure as a service (IaaS)**
Provides access to networking features, computers and data storage. Provides the highest level of flexibility and managment control over your IT resources.
<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/2.png" alt = "Output" width = "200" />

2. **Platform as a service (PaaS)**
Removes the managment of underlying infrastructure (Hardware and OS). Allows focus on deployment and managment of applications.
No need to worry about procurment, capacity planning, software maintenance and patching.
<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/3.png" alt = "Output" width = "200" />

4. **Software as a service (SaaS)**
Completed software product run bu the service provider. No need to think about how the service is maintained or how the underlying infrastructure is mangaged.
<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/4.png" alt = "Output" width = "200" />

## Deployment strategies:
Choice of deplyment depends on unique business needs such as infrastructure, data storage, access requirements. 
1. **Cloud**:
Build new or migrate existing applications to the cloud. Build applications on low-level infrastructure that requires managment or build using higher level services to reduce the manamgnet, architecting and scaling requirements.
<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/5.png" alt = "Output" width = "200" />

3. **Hybrid**:
Cloud based resources are connected to on-premises infrastructure. Integrates cloud resources with legacy IT applications. Used when legacy application are maintained on-premise of required by regulations.
<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/6.png" alt = "Output" width = "200" />

5. **On-premises**:
Private cloud deployment using virtualization and resource managment tools. Deployed on premise.
<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/7.png" alt = "Output" width = "200" />


# Intro to AWS
On demand access to over 175 global services which includes the following.

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/8.png" alt = "Output" width = "600" />

AWS provides the ability to try and experiment without having to deal wiht the collateral damage of failed experiments.
It also provides access to high-end services that would otherwise be expensive like ML, IoT, analytics, and security services.

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/9.png" alt = "Output" width = "300" />

## AWS Global Infrastructure

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/10.png" alt = "Output" width = "300" />

*Region:* Physical location around the world where data centers are clustered together. Consists of multiple isolated and physically separate Availability Zones within a geographic area. 
*Availability zones:* Area within a Region that can harbour one or more data centers. Houses the hardware devices that AWS offers. Interconnected with high-bandwidth, low-latency networking. 
*Edge Location:* Cache copies of your content for faster delivery to users at any location. Connected to AWS regions throug the AWS network across the globe. Over 200 locations across 47 coutries. 

When building architecture in cloud, plan for failure to resolve any issues that might occur. 
- Storage failures: Files stored in Amazon S3 have redundant copies in all availability zones in the region.

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/11.png" alt = "Output" width = "300" />

- Compute failures: It is best practice to spread the computing resources across multiple Availability zones so that issues in one zone does not affect the availability of your computing resources.

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/12.png" alt = "Output" width = "300" />

- Database failures: Multi-AZ deployment for Databases so that there always is a primary database in the Availability zone.

<img src= "https://github.com/Sleep404-Kunz/Intro-to-Cloud/blob/main/13.png" alt = "Output" width = "300" />

# AWS Core Services
# Cloud Careers
