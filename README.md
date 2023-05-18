# AWS Cloud Practitioner CLF-C01 Preparation 2023
Source Link: <a href="https://youtu.be/SOTamWNgDKc">freeCodeCamp.org</a>  

## Cloud Hosting

1. __Dedicated Server__  
One physical machine dedicated to single a business.  
_Very Expensive, High Maintenance, High Security_

2. __Virtual Private Server (VPS)__  
One physical machine is virtualized into sub machines.  
_Better Utilization and Isolation of Resources_

3. __Shared Hosting__  
One physical machine shared by hunder of businesses.  
_Very Cheap, Limited Functionality and Poor Isolation_

4. __Cloud Hosting__  
Multiple physical machines that acts as one system.  
_Felxible, Scalable, Cost Effective, High Configurability_

## Amazon Web Services (AWS)

> __Keywords__: Cloud Service Providers (CSP), Simple Queue Service (SQS), Simple Storage Service (S3), Elastic Compute Cloud (EC2)

* __SQS__ was first AWS service launched for public use in 2004
* __S3__ was launched in March of 2006
* __EC2__ was launched in August of 2006


## Cloud Service Provider

* Chains together __Cloud Services__ to create __Cloud Architectures__
* Make __Cloud Services__ accessible via __Single Unified API__ eg. AWS API
* __Cloud Services__ utilizes __metered billing__ based on usage.
* __Cloud Services__ offers __automation__ via Infrastructure as Code (IaC)  

### Landscape of CSPs

Tier-1: AWS, Azure, GCP, Alibaba Cloud  
Tier-2: IBM Cloud, Oracle Cloud, Rackspace(OpenStack)  
Tier-3: Vultr, Digital Ocean, Linode  

### Common Cloud Services

4 Core Cloud Services for Infrastructure as a Service (IaaS):

* Compute
* Networking  
* Storage  
* Databases  

AWS has over __200+__ cloud services

## Evolution of Computing

* Dedicated
* VMs
* Containers
* Functions  

### Types of Cloud Computing

* __Software as a Service__ (SaaS)  
Products run and managed by the service provider.  
Eg. Gmail, Office 365, Salesforce  
* __Platform as a Service__ (PaaS)  
Focus on deployment and management of user apps  
Eg. Elastic Beanstalk, Heroku, Google App Engine  
* __Infrastructure as a Service__ (IaaS)  
Provides access to networking features, computers and data storage space.  
Eg. Azure, AWS, GCP  

### Cloud Computing Deployment Models

* __Public Cloud__  
Everything is build on the CSP (Cloud-Native or Cloud First)  
* __Private Cloud__  
Everything is build on-premise  
* __Hybrid__  
Uses both On-Premise and CSP
* __Cross-Cloud / Multi Cloud Providers__  
Uses Multiple Cloud Providers  
Eg. __Amazon EKS__ <--> __Azure Arc__ <--> __GCP Kubernetes Engine__  

### Benefits of the Cloud

* __Agility__  
* __Pay-as-you-go pricing__  
* __Economy of scale__  
* __Global Reach__ 
* __Security__  
* __Reliability__  
* __High Availability__  
* __Scalability__  
* __Elasticity__

### Six Advantages of the Cloud

1. Trade capital expense for variable expense __(Pay On Demand)__  
2. Benefit from massive economies of scale __(Sharing the cost with other customers)__  
3. Stop guessing capacity __(Scale up or down)__  
4. Increase speed and agility __(Launch resources within a few clicks in minutes)__  
5. Stop spending money on running and maintaining data centers __(Focus on your own customers)__  
6. Go Global in minutes __(Deploy your app in multiple regions around the world with a few clicks)__  

## Global Infrastructure

### Availability Zones
Physical location made up of one or more datacenter. 
A __region__ will generally contain 3 __Availability Zones__.   

### Fault Tolerance

#### Fault Domain
Section of a network that is vulnerable to damage if a critical device system fails. The purpose of the fault domain is that if a failure occurs it will not cascade outside that domain, limiting the damage possible.  
Eg. Availability Zone

#### Fault Level
Collection of Fault domains.  
Eg. Region  

### AWS Global Network
Interconnections between AWS Global Infrastructure


### Point of Presence
Intermediate location between AWS Region and End user for content delivery or expediated upload.  
* __Amazon Cloudfront__  
* __Amazon S3 Transfer Acceleration__  
* __AWS Global Accelerator__ 

### AWS Direct Connect  
Private / Dedicated connection between datacenter, office, co-location & AWS.  

### Wavelength Zones
Allows for edge computing on 5G networks.  

### Data Residency
Payical or Geogrpahic location of an organization or cloud resouces reside.  
