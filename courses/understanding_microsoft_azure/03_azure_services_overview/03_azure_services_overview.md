## Cloud Services Types

With Azure, it's important to distinguish between the three different cloud
services types: 
- IaaS (Infrastructure As A Service)
- PaaS (Platform As A Service)
- SaaS (Software As A Service)

Each service type has a different levels of reponsability between the cloud
provider (Microsoft Azure) and the customer.

### IaaS

IaaS is the most flexible category of services as it gives the user maximum 
control.

An example in Azure would be a virtual machine. A customer would be responsible
for installing the operating system, configuration, maintenance, etc. And 
Azure would be responsible for maintaining the hardware, network connectivity,
and physical security.

### PaaS

PaaS is the middle ground between Infrastructure As A Service and Software As
A Service. With PaaS services, Azure maintains the physical infrastructure 
similar to IaaS but also responsible for the operating system, middleware, 
development tools, etc. that comprise a cloud solution.

Azure App Service is an example of a PaaS solution for web and mobile development.

### SaaS

SaaS is the most complete solution. With SaaS, the customer pays a subscription 
fee to use and connect to applications such as email, finantial software, 
messaging apps, etc.

With this model most responsability falls with Azure and the least with the
user.

With SaaS the customer is responsible for the data, devices, and account/identities.

Microsoft 365 is an example of a SaaS solution.

## Services by cloud Service Type

Each cloud service type has different services that fall underneath it's 
umbrella from different categories.

### IaaS

- Virtual Desktop
- Virtual Machine
- Storage Accounts
- Disks
- Firewall 
- Load Balancer

### PaaS

- SQL Database
- DevTest Labs
- Maria DB 
- App Service
- Azure Functions
- API Management

### Software as a Service (SaaS)

- Azure DevOps
- Sentinel
- IoT Central
- Advisor
- Azure Migrate
- Internet Analyzer

## Availability of services

The availability of services across Azure regions is dependent upon the 
region type.

There are 2 types in Azure: recommended and alternate.

Recommended is regions that provide the broadest range of services and support
availability zones.

Alternate on the other hand is regions that extend Azure's footprint within
a data residency boundary where a recommended region exists.

These regions help optimize latency and provide a second region for recovery 
but doesn't support availability zones. 

In Azure, services are grouped into: 
- Foundational: services are available in all regions and alternate regions 
  when they become generally available.
- Mainstream: services that are accesible in all recommended regions for
  deployment.
- Strategic: are targeted services offerings aimed at a particular industry.


### Foundational Services

- Azure Application Gateway
- Azure Backup
- Azure Cosmos
- Azure Event Hubs
- Azure Virtual Machines
- Azure VPN Gateway

### Mainstream Services

- Azure API Management.
- Azure Container Registry.
- Azure Functions.
- Azure Private Link.
- Azure Virtual WAN.

### Strategic Services

- Azure Lab Services. 
- Azure VMWare Solution.
- Azure Applied AI Services. 
- Azure Machine Learning.
- Azure Red Hat OpenShift.
- Azure Kubernetes.


## Big Data and Analytics

- The Azure Data Lake acts as a vast reservoir for your data.
- HDInsight processes and sifts through this reservoir.
- Azure Synapse integrates the strengths of data warehousing with big data 
  analytics and creates a unified platform.
- Stream Analytics for real time insights

Together, these tools empower businesses to manage and leverage their data
efficiently.

## AI and Machine Learning

- Azure Machine Learning streamlines building, training, and deploying 
  machine learning models. 
- Azure Cognitive Services provides pre-built AI functions such as language 
  udnerstanding, computer vision, and speech recognition.
- Azure Databricks is an analytics platform tailored for Azure and is ideal 
  for Big Data and Machine Learning.
- Azure AI Services augment applications with features like language comprehension
and speech recognition.


## Exercise: Who is responsible?

In Azure, resources typically fall under one of the three cloud service types:
Infrastructure as a Service, Platform as a Service, and Software as a Service.

Which of the following offers the Customer the greatest amount of control?

- [ ] Platform as a Service
- [X] Infrastructure as a Service
- [ ] Software as a Service


Note: 
IaaS is the most flexible, and provides the greatest amount of control. Azure
is responsible for the hardware, network connectivity, and physical security.
The customer is responsible for everything else.



## Exercise: Analytics vs AI/ML

Azure has a vast ecosystem, including services dedicated to Big Data and 
Analytics and AI & Machine Learning.

Categorize the following Azure services based on the type of tool category that
fall into. 

- Big Data and Analytics
    - Azure Datalake
    - Synapse
    - Stream Analytics
    - HDInsight
- AI & Machine Learning
    - Azure Cognitive Service
    - Azure AI Services
