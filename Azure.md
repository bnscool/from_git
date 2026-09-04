# Basics of Cloud Computing

## What is Cloud ?

In simpler terms, imagine the cloud as a vast, virtual space where you can store files, run software, and access various services over the internet. 

It's like having a powerful computer somewhere out there on the web that you can use for tasks without needing to own or physically manage the hardware. This allows users to access data and applications from anywhere with an internet connection.

## What is Cloud Computing ?

Cloud computing is a technology model that involves the delivery of computing services over the internet. Instead of owning and maintaining physical servers and infrastructure, users can access and use computing resources, applications, and storage provided by either third-party service providers (public cloud) or their own organization (private cloud) through the internet. These services are hosted in data centers located around the world.

In essence, cloud computing can involve both third-party providers (public cloud) and an organization's internal resources (private cloud). The distinction lies in whether the computing resources are shared among multiple customers (public cloud) or dedicated to a single organization (private cloud). The flexibility of cloud computing allows organizations to choose the deployment model that best aligns with their needs and requirements.

## Public Cloud:

**Who Uses It:** Everyone, like individuals, businesses, and organizations.

**What It's Like:** Imagine a giant, shared computer space on the internet. It's like using apps, storing files, or doing tasks on the internet that anyone can access.

**Example:** Think of Google Drive or Amazon Web Services (AWS).

## Private Cloud:

**Who Uses It:** One specific organization or business.

**What It's Like:** Picture having your own personal, private computer space. It's like a digital clubhouse where only you and your team have access. Others can't just drop in.

**Example:** A company using its own server for all its digital needs.

## Hybrid Cloud:

**Who Uses It:** A mix of everyone, depending on needs.

**What It's Like:** It's like having your private computer space, but sometimes you use the shared internet space too. 

**Example:** A business storing sensitive data in its private space but using the public cloud for extra storage or specific tasks.

### In a Nutshell:

**Public Cloud:** Shared digital space for everyone.

**Private Cloud:** Your own exclusive digital space.

**Hybrid Cloud:** Using both your private space and the shared online space when needed.

============================================================================

# Vocabulary in Cloud Computing

## Virtualization

Virtualization is the process of creating a virtual version of something, such as an operating system, server, storage, or network resources.

## Virtual Machine

A Virtual Machine (VM) is a software-based emulation of a physical computer. It allows running multiple operating systems on a single physical machine.

## API (Application Programming Interface)

API is a set of rules and protocols that allows different software applications to communicate with each other. It defines how software components should interact.

## Regions

Regions in cloud computing refer to geographic locations where cloud providers have data centers. Each region contains multiple data centers.

## Availability Zones

Availability Zones are isolated locations within a region that have their own power, cooling, and networking. They are designed to provide high availability and fault tolerance.

## Scalability

Scalability is the ability of a system to handle an increasing amount of work or its potential to be enlarged to accommodate that growth.

## Elasticity

Elasticity in cloud computing refers to the ability to dynamically scale resources up or down based on demand.

## Agility

Agility is the capability of quickly and easily adapting to changes. In the context of cloud computing, it involves the rapid deployment of resources and applications.

## High Availability

High Availability (HA) ensures that a system or application is operational and accessible for a high percentage of time, typically 99.9% or higher.

## Fault Tolerance

Fault Tolerance is the ability of a system to continue operating without interruption in the presence of hardware or software failures.

## Disaster Recovery

Disaster Recovery involves the planning and processes for restoring and recovering data and systems after a natural or human-induced disaster.

## Load Balancing

Load Balancing is the distribution of network traffic or computing workload across multiple servers to ensure no single server is overwhelmed.

=============================================================================

# Exploring Regions and Availability Zones in Azure

## Regions in Azure

Azure is a cloud computing platform provided by Microsoft, and it is globally distributed across multiple geographic locations known as regions. Each Azure region is a set of data centers deployed within a defined geographic area, and it is designed to provide low-latency access to Azure services for users and applications in that region.

### Key Points about Azure Regions:

- **Global Presence:** Azure has a vast global presence with data centers strategically located around the world.
  
- **Region Pairing:** Azure regions are often paired for data redundancy and resiliency. In the event of a regional failure, paired regions can help ensure continuity.

- **Compliance and Data Residency:** Organizations can choose specific regions to comply with data residency requirements and regulations.

## Availability Zones in Azure

Azure Availability Zones are part of Azure's high-availability architecture, providing redundancy and resiliency for applications and data. Each Azure region is divided into multiple Availability Zones, which are essentially unique physical locations with independent power, cooling, and networking.

### Key Points about Azure Availability Zones:

- **High Availability:** By distributing resources across Availability Zones, Azure ensures that applications remain available even in the face of localized failures, such as hardware or network failures.

- **Fault Isolation:** Availability Zones are designed to be isolated from one another, meaning a failure in one zone does not impact the availability of resources in other zones.

- **Multi-Data Center Architectures:** Availability Zones are essential for designing and deploying multi-data center architectures in Azure.

## How to Choose Regions and Availability Zones

When deploying resources in Azure, it's crucial to consider factors such as:

- **Proximity to Users:** Choose a region that is geographically close to your users to minimize latency.

- **Compliance Requirements:** Ensure that the chosen region complies with regulatory and data residency requirements.

- **High Availability Needs:** If high availability is a priority, distribute resources across multiple Availability Zones within a region.

- **Disaster Recovery Planning:** Leverage region pairing for effective disaster recovery planning.

============================================================================

# IaaS vs PaaS vs SaaS models in Azure

## Infrastructure as a Service (IaaS)

IaaS is a cloud computing model that provides virtualized computing resources over the internet. In Azure, IaaS offerings include virtual machines, storage, and networking components. Users have more control over the infrastructure but are responsible for managing and maintaining the operating system, middleware, and applications.

### Key Characteristics of Azure IaaS:

- **Scalability:** Easily scale resources up or down based on demand.
  
- **Full Control:** Users have control over the underlying infrastructure, including operating systems and applications.

- **Flexibility:** IaaS is suitable for a wide range of applications, offering flexibility in terms of technology stack.

## Platform as a Service (PaaS)

PaaS is a cloud computing model that provides a platform allowing customers to develop, run, and manage applications without dealing with the complexity of underlying infrastructure. In Azure, PaaS offerings include Azure App Service, Azure SQL Database, and Azure Functions.

### Key Characteristics of Azure PaaS:

- **Simplified Development:** Developers can focus on coding and application logic, while Azure manages the underlying infrastructure.

- **Automatic Scaling:** PaaS offerings often include built-in scaling capabilities, automatically adjusting resources based on demand.

- **Reduced Maintenance:** Azure handles tasks like patching, updates, and maintenance, freeing up resources for innovation.

## Software as a Service (SaaS)

SaaS is a cloud computing model that delivers software applications over the internet. Users can access the software through a web browser without the need for installation or maintenance. In Azure, SaaS offerings include Microsoft 365, Dynamics 365, and many third-party applications.

### Key Characteristics of Azure SaaS:

- **Accessibility:** Access software applications from any device with an internet connection.

- **Managed by Providers:** SaaS providers handle maintenance, updates, and security, reducing the burden on end-users.

- **Subscription-Based:** SaaS applications are typically offered on a subscription basis, allowing users to pay for what they use.

## Choosing the Right Model in Azure

When deciding between IaaS, PaaS, and SaaS in Azure, consider factors such as:

- **Development Needs:** Choose PaaS for streamlined development, IaaS for more control, and SaaS for off-the-shelf solutions.

- **Maintenance Preferences:** If you want to minimize maintenance tasks, opt for PaaS or SaaS.

- **Resource Control:** Choose IaaS if you need more control over the underlying infrastructure.

- **Cost Considerations:** Evaluate pricing models for each service and choose based on your budget and usage patterns.

- ============================================================================

# Azure Resources

Azure resources are the building blocks of your cloud infrastructure in Microsoft Azure. These resources can be virtual machines, databases, storage accounts, or any other service offered by Azure. Each resource is a manageable item in Azure, and they are provisioned and managed individually.

## Resource Groups in Azure

A **Resource Group** in Azure is a logical container for resources that share the same lifecycle, permissions, and policies. It helps you organize and manage related Azure resources efficiently. Resources within a group can be deployed, updated, and deleted together as a single management unit.

### Key Points about Resource Groups:

- **Lifecycle Management:** Resources within a group can be managed collectively, making it easy to handle deployments, updates, and deletions.

- **Resource Organization:** Grouping resources based on projects, environments, or applications helps keep your Azure environment well-organized.

- **Role-Based Access Control (RBAC):** Permissions and access control are applied at the resource group level, allowing you to manage who can access and modify resources within a group.

## Azure Resource Manager (ARM) Overview

**Azure Resource Manager (ARM)** is the deployment and management service for Azure. It provides a consistent management layer that enables you to deploy resources with declarative templates. ARM templates describe the resources you need and their configurations, allowing you to deploy and update resources in a predictable manner.

### Key Features of Azure Resource Manager:

- **Template-Based Deployment:** ARM uses JSON templates to define the infrastructure and configuration of your Azure resources. This enables repeatable and consistent deployments.

- **Dependency Management:** ARM automatically handles dependencies between resources, ensuring they are deployed in the correct order.

- **Rollback and Roll-forward:** In case of deployment failures, ARM can automatically roll back changes to maintain the desired state, or roll forward to the last known good state.

- **Tagging and Categorization:** You can use tags to label and categorize resources, making it easier to manage and organize your Azure environment.

**Note:** Understanding Azure resources, resource groups, and Azure Resource Manager is fundamental to effectively utilize and manage your resources in the Azure cloud.

- ============================================================================

# Virtualization: An In-Depth Explanation

## Background

In traditional computing, a single physical server runs a single operating system, and applications are installed directly on that OS. This approach has limitations, such as underutilization of hardware resources, difficulty in managing multiple servers, and lack of flexibility in scaling.

**Virtualization** addresses these challenges by introducing a layer of abstraction between the hardware and the operating system. It enables the creation of multiple virtual instances, each running its own operating system and applications, on a single physical server. This technology has become fundamental in modern data centers and cloud computing environments.

## Components of Virtualization

1. **Hypervisor (Virtual Machine Monitor):**
   - The hypervisor is a crucial component of virtualization. It sits between the hardware and the operating systems, managing and allocating resources to virtual machines (VMs).
   - There are two types of hypervisors: Type 1 (bare-metal) runs directly on the hardware, while Type 2 (hosted) runs on top of an existing operating system.

2. **Virtual Machines (VMs):**
   - VMs are the instances created by the hypervisor. Each VM operates as an independent computer with its own virtualized hardware, including CPU, memory, storage, and network interfaces.
   - Multiple VMs can run on a single physical server, allowing for efficient resource utilization.

## Key Concepts in Virtualization

1. **Server Virtualization:**
   - In server virtualization, a physical server is divided into multiple VMs, each running its own OS. This allows for better utilization of hardware resources and easier management of servers.

2. **Resource Pooling:**
   - Virtualization enables the pooling of physical resources, such as CPU, memory, and storage. These resources can be dynamically allocated to VMs based on demand.

3. **Isolation:**
   - VMs operate independently of each other. This isolation ensures that issues in one VM do not affect others, providing a more secure and stable environment.

4. **Snapshotting and Cloning:**
   - Virtualization allows the creation of snapshots, which capture the state of a VM at a specific point in time. This facilitates easy backup and recovery. Cloning enables the rapid duplication of VMs for scalability.

## Benefits of Virtualization

1. **Server Consolidation:**
   - Multiple VMs can run on a single physical server, reducing the need for a large number of physical machines. This leads to cost savings and energy efficiency.

2. **Flexibility and Scalability:**
   - Virtualization allows for the easy creation, modification, and scaling of VMs. This flexibility is essential in dynamic computing environments.

3. **Disaster Recovery:**
   - Virtualization simplifies disaster recovery by enabling the quick restoration of VMs from snapshots or backups.

4. **Resource Optimization:**
   - Resources can be allocated and deallocated dynamically based on workload, optimizing resource utilization.

5. **Testing and Development:**
   - Virtualization provides a sandbox for testing and development. VMs can be easily created, modified, and discarded without affecting the production environment.

- ============================================================================

# Types of Virtual Machines on Azure

Azure provides a variety of virtual machine (VM) offerings to cater to different workload requirements. Each VM type is designed with specific hardware configurations to meet diverse performance and scalability needs.

## General Purpose VMs

**Example: Standard_D2s_v3**

- **Description:** General-purpose VMs are well-balanced machines suitable for a variety of workloads. They offer a good balance of CPU-to-memory ratio and are suitable for development, testing, and small to medium-sized databases.

- **Use Case:** Hosting websites, lightweight applications, or development and testing environments.

## Compute Optimized VMs

**Example: Standard_F2s_v2**

- **Description:** Compute optimized VMs are designed for compute-intensive workloads that require high CPU power. They provide a high CPU-to-memory ratio, making them suitable for data analytics and computational tasks.

- **Use Case:** Batch processing, gaming applications, and other CPU-intensive workloads.

## Memory Optimized VMs

**Example: Standard_E16s_v3**

- **Description:** Memory optimized VMs are tailored for memory-intensive applications. They provide a high memory-to-CPU ratio, making them suitable for databases, in-memory caching, and analytics.

- **Use Case:** Running large databases, in-memory caching, and analytics applications.

## Storage Optimized VMs

**Example: Standard_L8s_v2**

- **Description:** Storage optimized VMs are designed for workloads that require high storage throughput and I/O performance. They provide high local disk throughput, making them suitable for big data and large databases.

- **Use Case:** Big data applications, data warehousing, and large-scale databases.

## GPU VMs

**Example: Standard_NC6s_v3**

- **Description:** GPU (Graphics Processing Unit) VMs are equipped with powerful graphics processors, suitable for graphics-intensive applications and parallel processing tasks.

- **Use Case:** Machine learning, graphics rendering, and simulations that require GPU acceleration.

## High-Performance Compute VMs

**Example: Standard_H16r**

- **Description:** High-Performance Compute VMs are designed for demanding, parallel processing and high-performance computing (HPC) applications.

- **Use Case:** Simulations, modeling, and scenarios that require massive parallel processing.

## Burstable VMs

**Example: B1s**

- **Description:** Burstable VMs provide a baseline level of CPU performance with the ability to burst above the baseline for a certain period. They are cost-effective for workloads with varying CPU usage.

- **Use Case:** Development and testing environments, small websites, and applications with variable workloads.

- ============================================================================

# Azure Networking

## Virtual Network

A Virtual Network (VNet) in Azure is a logically isolated network that securely connects Azure resources and extends on-premises networks. Key features include:

- **Isolation**: VNets provide isolation at the network level for segmenting resources and controlling traffic.

- **Subnetting**: Divide a VNet into subnets for resource organization and traffic control.

- **Address Space**: VNets have an address space defined using CIDR notation, determining the IP address range.

## Subnets, CIDR

### Subnets

Subnets are subdivisions of a Virtual Network, allowing for better organization and traffic management.

### CIDR (Classless Inter-Domain Routing)

CIDR notation represents IP addresses and their routing prefix, specifying the range of IP addresses for a network.

## Routes and Route Tables

### Routes

Routes dictate how network traffic is directed, specifying the destination and next hop.

### Route Tables

Route Tables are collections of routes associated with subnets, enabling custom routing rules.

## Network Security Groups (NSGs)

NSGs are fundamental for Azure's network security, allowing filtering of inbound and outbound traffic. Key aspects include:

- **Rules**: NSGs define allowed or denied traffic based on source, destination, port, and protocol.

- **Default Rules**: NSGs have default rules for controlling traffic within the Virtual Network and between subnets.

- **Association**: NSGs can be associated with subnets or individual network interfaces.

## Application Security Groups (ASGs)

ASGs group Azure virtual machines based on application requirements, simplifying network security:

- **Simplification**: ASGs allow defining rules based on application roles instead of individual IP addresses.

- **Dynamic Membership**: ASGs support dynamic membership based on tags or other attributes.

- **Rule Association**: Security rules can be associated with ASGs for intuitive and scalable network security management.

- ============================================================================

# Azure Networking Advanced

## Azure App Gateway & WAF

Azure Application Gateway is a web traffic load balancer that enables you to manage and route traffic to your web applications. Web Application Firewall (WAF) provides protection against web vulnerabilities. Key features include:

- **Load Balancing**: Distributes incoming traffic across multiple servers to ensure no single server is overwhelmed.

- **SSL Termination**: Offloads SSL processing, improving the efficiency of web servers.

- **Web Application Firewall (WAF)**: Protects web applications from common web vulnerabilities and exploits.

## Azure Load Balancer

Azure Load Balancer distributes incoming network traffic across multiple servers to ensure no single server is overwhelmed. Key features include:

- **Load Balancing Algorithms**: Supports different algorithms for distributing traffic, such as round-robin and least connections.

- **Availability Sets**: Works seamlessly with availability sets to ensure high availability.

- **Inbound and Outbound Traffic**: Balances both inbound and outbound traffic.

## Azure DNS

Azure DNS is a scalable and secure domain hosting service. It provides name resolution using the Microsoft Azure infrastructure. Key features include:

- **Domain Hosting**: Hosts domain names and provides name resolution within Azure.

- **Integration with Azure Services**: Easily integrates with other Azure services like App Service and Traffic Manager.

- **Global Availability**: Provides low-latency responses globally.

## Azure Firewall

Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources. Key features include:

- **Stateful Firewall**: Allows or denies traffic based on rules and supports stateful inspection.

- **Application FQDN Filtering**: Filters traffic based on fully qualified domain names.

- **Threat Intelligence Integration**: Integrates with threat intelligence feeds for enhanced security.

## Virtual Network Peering and VNet Gateway

### Virtual Network Peering

Virtual Network Peering allows connecting Azure Virtual Networks directly, enabling resources in one VNet to communicate with resources in another. Key features include:

- **Global VNet Peering**: Peering can be established across regions.

- **Transitive Routing**: Traffic between peered VNets flows directly, improving performance.

### VNet Gateway

VNet Gateway enables secure communication between on-premises networks and Azure Virtual Networks. Key features include:

- **Site-to-Site VPN**: Connects on-premises networks to Azure over an encrypted VPN tunnel.

- **Point-to-Site VPN**: Enables secure remote access to Azure resources.

## VPN Gateway

Azure VPN Gateway provides secure, site-to-site connectivity between your on-premises network and Azure. Key features include:

- **IPsec/IKE VPN Protocols**: Ensures secure communication over the Internet.

- **High Availability**: Supports active-active and active-passive configurations for high availability.

- **BGP Support**: Allows dynamic routing between your on-premises network and Azure.

- ============================================================================

# Install and Configure Nginx on Ubuntu

## Step 1: Update Package Lists

Before installing any new software, it's a good practice to update the package lists to ensure you get the latest version.

```bash
sudo apt update
sudo apt upgrade
```

## Step 2: Install Nginx

Install Nginx using the following command:

```
sudo apt install nginx
```

## Step 3: Start Nginx Service

```
sudo systemctl start nginx
```

## Step 4: Create HTML File

```
sudo vim /var/www/html/index.html
```

Add the HTML content, for example.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo Page</title>
</head>
<body>
    <h1> I Learnt how networking works in Azure today</h1>
</body>
</html>
```

Save the file.

### Restart Nginx

```
sudo systemctl restart nginx
```

- ============================================================================

# Azure Networking Interview Q&A

### What is the difference between NSG and ASG ?
ASGs are applied to VMs and are used in conjunction with NSGs. By associating an ASG tag with a network security rule, you can define rules that apply to a group of VMs sharing the same tag.
ASGs simplify the management of security rules in a multi-tier application by grouping VMs that belong to the same application tier. This makes it easier to apply and manage security policies for a specific application.

### How can you block the access to a your vm from a subnet ?
By default traffic is allowed between subnets with in the VNet in Azure. This is because of a default NSG rule “AllowVnetInBound”. 

The priority of this rule is 65000, so we need to create a Deny rule with less than 65000 priority number.

### Are Azure NSGs stateful or stateless ?
They are stateful in nature. That means if you allow a port for inbound traffic traffic to receive the request. You don’t have to open the port in outbound rules to send response back.

Example: If you host a host an application on port 80 in azure vm and allow inbound traffic for customers to access it. You don’t need to open port 80 in outbound traffic to send response back to the customer.

### What is the difference between Azure Firewall and NSG ?
Firewall:
Designed for controlling both outbound and inbound traffic to and from resources within a Virtual Network (VNet).

NSG:
Typically associated with subnets or individual network interfaces to control traffic within a VNet and between VNets.

### What are the advantages of resource groups in azure ?
- Logical Organization
- Lifecycle Management
- Resource Group Tagging
- Role-Based Access Control (RBAC)
- Cost Management
- Resource Group Templates (Azure Resource Manager Templates)
- Resource Locks

### What is the difference between Azure User Data and Custom Data ?
User data is a new version of custom data and it offers added benefits. User data persists and lives in the cloud, accessible and updatable anytime. Custom data vanishes after first boot, accessible only during VM creation.

### What is the difference between Azure App Gateway and Azure LB ?

#### Azure Application Gateway:
Operates at Layer 7 (Application layer) of the OSI model.
Provides advanced application-level routing, SSL termination, and web application firewall (WAF) capabilities.
Suited for distributing traffic based on application awareness.

#### Azure Load Balancer:
Operates at Layer 4 (Transport layer) of the OSI model.
Distributes network traffic based on IP address and port.
Suitable for generic TCP/UDP load balancing without application-specific features.

### Assume your company is using all the ideal Azure Networking setup and your application is deployed in the web subnet , Explain the traffic flow to your app ?

#### User Access:
- External users access the application over the internet.
- DNS resolves the application's domain name to the associated public IP address.

#### Internet Traffic to Azure:
-Incoming internet traffic reaches Azure through Azure Front Door, Azure Application Gateway, or Azure Load Balancer, depending on the specific requirements of the application.
- These services provide load balancing, SSL termination, and other application-level features.

#### Traffic Routing Within Azure:
- Traffic is directed to the public IP address associated with the Azure Application Gateway or Load Balancer.
- The gateway or load balancer routes traffic to the backend pool of the web servers in the web subnet.

#### Network Security Group (NSG) Enforcement:
- Network Security Groups associated with the web subnet control inbound and outbound traffic.
- NSG rules ensure that only required traffic is allowed, providing security at the network layer.
- Azure Virtual Network (VNet) Components:
- The web subnet is part of an Azure Virtual Network, which acts as an isolated network environment.
- Subnets within the VNet communicate with each other through the VNet's internal routing.

#### Application Servers:
- Web servers within the web subnet process incoming requests

#### Describe the purpose of Azure Bastion and when it is used for secure remote access to virtual machines.
- Secure Remote Access:
- Elimination of Public Internet Exposure:
- Reduced Attack Surface:
- Azure Bastion Integration:
- Simplified Connectivity:
- Azure Portal-Based Access:
- Role-Based Access Control (RBAC):
- Multi-Factor Authentication (MFA):
- Audit and Monitoring:

- ============================================================================

# Azure Blob Storage

1. What is it?

    Azure Blob Storage is a cloud-based object storage solution provided by Microsoft Azure.
    It is designed to store and manage large amounts of unstructured data, such as documents, images, videos, and other types of binary and text data.
    Blobs are organized into containers, and each blob is assigned a unique URL for access.

2. When to use it?

    Use Azure Blob Storage when you need to store and retrieve large amounts of unstructured data.
    It is suitable for scenarios like serving images or videos to a website, storing backups, and handling data for analytics and big data processing.

3. Example from DevOps Engineer point of view?

    A DevOps engineer may use Azure Blob Storage to store artifacts and binaries produced during the build process, ensuring a centralized and scalable storage solution.
    Azure Storage Explorer or Azure CLI can be used to automate the uploading and retrieval of artifacts during deployment pipelines.

4. Equivalent service in AWS:

    The equivalent service in AWS is Amazon Simple Storage Service (S3). S3 is also an object storage service designed for scalable and secure storage of objects, such as files and data.

- ============================================================================

# Azure File Storage

1. What is it?

    Azure File Storage is a fully managed file share service in the cloud.
    It provides the Server Message Block (SMB) protocol for sharing files across applications and VMs in the Azure cloud.
    Azure File Storage is useful for applications that require shared file access, such as configuration files or data files.

2. When to use it?

    Use Azure File Storage when you need a shared file system that can be accessed from multiple VMs or applications.
    It is suitable for scenarios like storing configuration files, sharing data between applications, and serving as a common storage location for applications in a cloud environment.

3. Example from DevOps Engineer point of view?

    A DevOps engineer may leverage Azure File Storage to store configuration files that are shared among multiple application instances.
    In a deployment pipeline, scripts or configuration files stored in Azure File Storage can be mounted to VMs or containers during the deployment process.

4. Equivalent service in AWS:

    The equivalent service in AWS is Amazon Elastic File System (EFS). EFS provides scalable file storage for use with Amazon EC2 instances, supporting the Network File System (NFS) protocol.

- ============================================================================

# Azure Tables

1. What is it?

    Azure Tables is a NoSQL data store service provided by Azure.
    It stores large amounts of semi-structured data and allows for fast and efficient querying using a key-based access model.
    Data is organized into tables, and each table can store billions of entities.

2. When to use it?

    Use Azure Tables when you need a highly scalable NoSQL data store for semi-structured data with simple key-based access.
    It is suitable for scenarios like storing configuration data, user profiles, and other data where a key-value or key-attribute data model is appropriate.

3. Example from DevOps Engineer point of view?

    A DevOps engineer may use Azure Tables to store configuration settings for applications or services.
    During the deployment process, scripts can retrieve configuration data from Azure Tables to customize the behavior of deployed applications.

4. Equivalent service in AWS:

    While AWS does not have a direct equivalent service for Azure Tables, Amazon DynamoDB is a similar NoSQL database service that provides key-value and document storage. DynamoDB can be used for similar use cases.

- ============================================================================

# Azure Queue Storage

1. What is it?

    Azure Queue Storage is a message queue service that allows decoupling of components in a distributed application.
    It provides a reliable way to store and retrieve messages between application components, ensuring asynchronous communication.

2. When to use it?

    Use Azure Queue Storage when you need to enable communication and coordination between different parts of a distributed application.
    It is suitable for scenarios like handling background jobs, managing tasks asynchronously, and facilitating communication between loosely coupled components.

3. Example from DevOps Engineer point of view?

    A DevOps engineer may use Azure Queue Storage to implement a message queue for processing background tasks or managing communication between microservices.
    During deployment, scripts can enqueue messages to trigger specific actions or coordinate tasks between different components.

4. Equivalent service in AWS:

    The equivalent service in AWS is Amazon Simple Queue Service (SQS). SQS provides a fully managed message queue service for decoupling components in a distributed system.

- ============================================================================

# Install Azure CLI

### Installation Overview
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli

### Install on Windows
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli

### Install on Linux
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt

### Install on Mac
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-macos 


- ============================================================================

# Create VM using Azure CLI

### Start with creating a Resource Group

```
az group create --name learn-azure-cli --location eastus
```

### Set the Resource Group as default (Optional)

```
az config set defaults.group=learn-azure-cli
```

### Create VM with Vnet

```
az vm create \
  --resource-group learn-azure-cli \
  --name vmName \ 
  --image Ubuntu2204 \
  --vnet-name default \  
  --subnet default \    
  --generate-ssh-keys \
  --output json \
  --verbose
```

### Delete the Resource Group to delete all the resources

```
az group delete --name learn-azure-cli
```

- ============================================================================

{
    "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
    "contentVersion": "1.0.0.0",
    "parameters": {},
    "functions": [],
    "variables": {},
    "resources": [
        {
            "name": "abhioshekveeramalla11232",
            "type": "Microsoft.Storage/storageAccounts",
            "apiVersion": "2023-01-01",
            "tags": {
                "displayName": "abhioshekveeramalla11232"
            },
            "location": "[resourceGroup().location]",
            "kind": "StorageV2",
            "sku": {
                "name": "Premium_LRS",
                "tier": "Premium"
            }
        }
    ],
    "outputs": {}
}

- ============================================================================

# Commands to access Blob from the Virtual Machine

### Fetch the access token 

```
access_token=$(curl 'http://169.254.169.254/metadata/identity/oauth2/token?api-version=2018-02-01&resource=https%3A%2F%2Fstorage.azure.com%2F' -H Metadata:true | jq -r '.access_token')
```


### Access the blob from Virtual Machine

storage_account_name=""
container_name=""
blob_name=""

```
curl "https://$storage_account_name.blob.core.windows.net/$container_name/$blob_name" -H "x-ms-version: 2017-11-09" -H "Authorization: Bearer $access_token"
```

- ============================================================================

# Command to create ACR ImagePullSecret

```
kubectl create secret docker-registry <secret-name> \
    --namespace <namespace> \
    --docker-server=<container-registry-name>.azurecr.io \
    --docker-username=<service-principal-ID> \
    --docker-password=<service-principal-password>
```

- ============================================================================

# Azure DevOps Interview Questions

### Complete CI/CD Pipeline process:

Scenario: How does the Azure DevOps CI/CD Pipeline look in your organization ?

Continuous Integration (CI):

    Triggers on code changes.
    Clones code from repository.
    Runs unit tests and static code analysis.
    Builds artifacts (e.g., compiled code, container images).
    Stores artifacts in Azure Pipelines artifacts for deployment.

Continuous Delivery (CD):

    Triggers on successful CI completion or manually.
    Deploys artifacts to designated environments (staging, production).
    Runs environment-specific tests (e.g., integration, acceptance).
    Approvals or gates can be implemented before deployment.
    Optionally, rolls back deployments if issues arise.

### Securing Sensitive Information in Pipelines:

Scenario: You need to securely store API keys and other secrets used in your pipeline tasks. How would you ensure their protection while maintaining pipeline functionality?

Answer: Explain using Azure Key Vault to store secrets and access them using managed identities or service connections with minimal privileges. Emphasize avoiding hardcoding secrets in the pipeline script.

### Integrating Azure Container Registry (ACR) with Pipelines:

Scenario: Your application uses Docker containers. How would you integrate ACR with Azure Pipelines for building, pushing, and deploying container images?

Answer: Describe the process of configuring Docker tasks in the pipeline to build images, authenticate with ACR using service connections, push images to the registry, and deploy them to specific environments.

### Debugging Pipeline Failures:

Scenario: Your pipeline consistently fails at a specific stage. How would you approach troubleshooting and identifying the root cause of the issue?

Answer: Highlight utilizing built-in debugging tools like logs, pipeline diagnostics, and Azure Monitor, alongside manual code review and environment checks. Mention potential causes like resource constraints, task configuration errors, or infrastructure issues.

### Handling Code Merges and Rollbacks in Pipelines:

Scenario: You discover a critical bug in the recently deployed production environment. How would you leverage Azure Pipelines for a rollback and ensure safe merging of a fix?

Answer: Explain using deployment environments and conditional triggers to target specific environments. Discuss leveraging branching strategies and continuous deployment practices to revert changes and integrate a fix seamlessly.

### Utilizing Azure Runners for Self-Hosted Environments:

Scenario: Your company has specific infrastructure requirements and needs to run pipelines on self-hosted machines. How would you leverage Azure Runners for this purpose?

Answer: Discuss configuring and managing self-hosted runners, ensuring security considerations like network isolation and access control. Mention using the appropriate runner OS and tools based on your project needs.

### Implementing Role-Based Access Control (RBAC) in Pipelines:

Scenario: Your team has various roles with different access needs. How would you configure RBAC within Azure Pipelines to ensure users have appropriate permissions?

Answer: Explain leveraging built-in roles and custom definitions to grant access to pipelines, repositories, and resources. Highlight the importance of least privilege and separation of duties principles.

### Automating Infrastructure Provisioning with Pipelines:

Scenario: You want to automate infrastructure provisioning and deployment alongside your application code. How would you integrate infrastructure as code (IaC) tools like Terraform with Azure Pipelines?

Answer: Discuss using tasks like Azure Resource Manager or Terraform tasks to manage infrastructure creation and deletion within the pipeline workflow. Mention benefits like faster deployments and improved consistency.

### Maintaining Pipeline Security Throughout the CI/CD Process:

Scenario: How would you ensure overall security within your Azure Pipelines throughout the CI/CD process, from code building to deployment?

Answer: Discuss a holistic approach, including secure code practices, vulnerability scanning, container image scanning, service principal usage with least privilege, and regular pipeline audits.

- ============================================================================

# AKS setup using CLI

## Create Azure Resource Group

```
az group create --name keyvault-demo --location eastus
```

## AKS Creation and Configuration

### Create an AKS cluster with Azure Key Vault provider for Secrets Store CSI Driver support

```
az aks create --name keyvault-demo-cluster -g keyvault-demo --node-count 1 --enable-addons azure-keyvault-secrets-provider --enable-oidc-issuer --enable-workload-identity
```

### Get the Kubernetes cluster credentials (Update kubeconfig)

```
az aks get-credentials --resource-group keyvault-demo --name keyvault-demo-cluster
```

#### Verify that each node in your cluster's node pool has a Secrets Store CSI Driver pod and a Secrets Store Provider Azure pod running

```
kubectl get pods -n kube-system -l 'app in (secrets-store-csi-driver,secrets-store-provider-azure)' -o wide
```

## Keyvault creation and configuration

- Create a key vault with Azure role-based access control (Azure RBAC).

```
az keyvault create -n aks-demo-abhi -g keyvault-demo -l eastus --enable-rbac-authorization
```

- ============================================================================

# Connect your Azure ID to the Azure Key Vault Secrets Store CSI Driver 

### Configure workload identity

```
export SUBSCRIPTION_ID=fe4a1fdb-6a1c-4a6d-a6b0-dbb12f6a00f8
export RESOURCE_GROUP=keyvault-demo
export UAMI=azurekeyvaultsecretsprovider-keyvault-demo-cluster
export KEYVAULT_NAME=aks-demo-abhi
export CLUSTER_NAME=keyvault-demo-cluster

az account set --subscription $SUBSCRIPTION_ID
```

### Create a managed identity

```
az identity create --name $UAMI --resource-group $RESOURCE_GROUP

export USER_ASSIGNED_CLIENT_ID="$(az identity show -g $RESOURCE_GROUP --name $UAMI --query 'clientId' -o tsv)"
export IDENTITY_TENANT=$(az aks show --name $CLUSTER_NAME --resource-group $RESOURCE_GROUP --query identity.tenantId -o tsv)
```

### Create a role assignment that grants the workload ID access the key vault

```
export KEYVAULT_SCOPE=$(az keyvault show --name $KEYVAULT_NAME --query id -o tsv)

az role assignment create --role "Key Vault Administrator" --assignee $USER_ASSIGNED_CLIENT_ID --scope $KEYVAULT_SCOPE
```

### Get the AKS cluster OIDC Issuer URL 

```
export AKS_OIDC_ISSUER="$(az aks show --resource-group $RESOURCE_GROUP --name $CLUSTER_NAME --query "oidcIssuerProfile.issuerUrl" -o tsv)"
echo $AKS_OIDC_ISSUER
```

### Create the service account for the pod

```
export SERVICE_ACCOUNT_NAME="workload-identity-sa"
export SERVICE_ACCOUNT_NAMESPACE="default" 
```

```
cat <<EOF | kubectl apply -f -
apiVersion: v1
kind: ServiceAccount
metadata:
  annotations:
    azure.workload.identity/client-id: ${USER_ASSIGNED_CLIENT_ID}
  name: ${SERVICE_ACCOUNT_NAME}
  namespace: ${SERVICE_ACCOUNT_NAMESPACE}
EOF
```

### Setup Federation

```
export FEDERATED_IDENTITY_NAME="aksfederatedidentity" 

az identity federated-credential create --name $FEDERATED_IDENTITY_NAME --identity-name $UAMI --resource-group $RESOURCE_GROUP --issuer ${AKS_OIDC_ISSUER} --subject system:serviceaccount:${SERVICE_ACCOUNT_NAMESPACE}:${SERVICE_ACCOUNT_NAME}
```

### Create the Secret Provider Class

```
cat <<EOF | kubectl apply -f -
# This is a SecretProviderClass example using workload identity to access your key vault
apiVersion: secrets-store.csi.x-k8s.io/v1
kind: SecretProviderClass
metadata:
  name: azure-kvname-wi # needs to be unique per namespace
spec:
  provider: azure
  parameters:
    usePodIdentity: "false"
    clientID: "${USER_ASSIGNED_CLIENT_ID}" # Setting this to use workload identity
    keyvaultName: ${KEYVAULT_NAME}       # Set to the name of your key vault
    cloudName: ""                         # [OPTIONAL for Azure] if not provided, the Azure environment defaults to AzurePublicCloud
    objects:  |
      array:
        - |
          objectName: secret1             # Set to the name of your secret
          objectType: secret              # object types: secret, key, or cert
          objectVersion: ""               # [OPTIONAL] object versions, default to latest if empty
        - |
          objectName: key1                # Set to the name of your key
          objectType: key
          objectVersion: ""
    tenantId: "${IDENTITY_TENANT}"        # The tenant ID of the key vault
EOF
```

- ============================================================================

# Verify Keyvault AKS Integration

### Create a sample pod to mount the secrets

```
cat <<EOF | kubectl apply -f -
# This is a sample pod definition for using SecretProviderClass and workload identity to access your key vault
kind: Pod
apiVersion: v1
metadata:
  name: busybox-secrets-store-inline-wi
  labels:
    azure.workload.identity/use: "true"
spec:
  serviceAccountName: "workload-identity-sa"
  containers:
    - name: busybox
      image: registry.k8s.io/e2e-test-images/busybox:1.29-4
      command:
        - "/bin/sleep"
        - "10000"
      volumeMounts:
      - name: secrets-store01-inline
        mountPath: "/mnt/secrets-store"
        readOnly: true
  volumes:
    - name: secrets-store01-inline
      csi:
        driver: secrets-store.csi.k8s.io
        readOnly: true
        volumeAttributes:
          secretProviderClass: "azure-kvname-wi"
EOF
```

### List the contents of the volume

```
kubectl exec busybox-secrets-store-inline-wi -- ls /mnt/secrets-store/
```

### Verify the contents in the file

```
kubectl exec busybox-secrets-store-inline -- cat /mnt/secrets-store/foo-secret
```

- ============================================================================

# Delete Everything

```
az group delete --name keyvault-demo
```

============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



============================================================================



- ============================================================================
