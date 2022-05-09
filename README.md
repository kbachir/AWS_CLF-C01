# AWS_CLF-C01

# Intro to the Cloud

## What is Cloud Computing?
- Cloud computing is the **on-demand delivery** of compute power, db storage, applications and other IT resources
- Pay-as-you-go pricing
- You can provision **exactly the type and size** of computing resources you need
- **Instant** access

### Benefits:
- Flexible: change resource type as and when needed
- Cost-Effective: Pay-as-you-go 
- Scalable: Accomodate larger loads easily based by scaling up or out
- Elastic: Ability to scale out and in when needed
- Highly available and fault tolerant: Build across data centres
- Agiltity: Rapidly develop, test and launch software

### Problems with traditional IT:
- Pay for rent for the data centre
- Pay for power, cooling and maintenance 
- Adding and replacing hardware takes time
- Scaling is limited
- Needs a team to monitor 24/7
- No disaster recovery

## Types of Cloud Computing:

#### Infrastrcture as a Service:
- Provide building blocks for cloud IT
- Provide networking computers and data storage space
- Highest level of flexibility
- Easy parallel with traditional on prem

_i.e EC2_

#### Platform as a Service:
- Removes the need for your organization to manage the underlying infrastructure
- Focus on deployment and management of applications

_i.e Elastic Beanstalk_

#### Software as a Service: 
- Completed product run and managed by the service provider

_i.e Rekognition for ML_

![Types-of-cloud-computing](https://user-images.githubusercontent.com/98312982/167387742-879fb688-f5c4-4fcf-b3ef-cd7f6aefd453.png)

### Pricing Models:

#### Compute
- Pay for exact amount compute time

#### Storage
- Pay for exact amount of storage space used

#### Data transfer
- Pay for data that is transferred **out** out of the cloud
- Data transferred **in** is free

# AWS Regions: 
- AWS has regions all around the world
- It's a acluster of data centres
- Most services are linked and scoped to a particular region
- Some services are global and not region scoped, _i.e IAM_

## How do you choose a region? 
A few factors matter, including:

#### Compliance:
- Data governance and legal requirements mean some data needs to be stored in certain areas and can never leave without specific permission 
- This means that to operate in a particular area, the data needs to be stored only in that particular area

#### Latency:
- Proximity to users matters because of server latency and delivery times

#### Availability: 
- Not all services and features are available in every region

#### Pricing:
- Pricing varies region to region and is transparent in the service pricing page

## Availability Zones:
- Each region has at least 3 AZs, usually 3 and maximum of 6
- Discrete data centres with redundant power, networking and connectivity
- Separate from each other so that they are **isolated from disasters**
- Connected with **high bandwith, ultra low latency **networking
- Together they form a region

## Points of Presence (Edge Locations)
- AWS has 216 PoP in 84 cities and 42 countries, allowing ultra low latency delivery around the world

## Shared Responsibility Model
![shared-responsibility-model-aws](https://user-images.githubusercontent.com/98312982/167392913-ee8713dd-5bd1-4402-a875-d37fe1277ec5.png)

# IAM
