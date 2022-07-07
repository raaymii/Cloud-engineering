Course Instructor - David Davis

----CLOUD COMPUTING: THE BASICS----
Cloud computing is on demand computing resources delivered to you over the internet.
Cloud computing is a computing service that you traditionally did local or on-premises as it's called, now performed remotely, across the internet (off-premises).
Basically, it's the computing that you need, but it is done by someone else and it's done somewhere else.

According to VMware, cloud computing is an approach to computing that leverages the efficient pooling of an on-demand, self-managed, virtual infrastructure.

TRAITS OF A CLOUD
-Elastic: it can scale up and down.
-Metered: you can pay for what you use. You can pay by the minute or by the computing resource, just like your electric bill.
-Self-service: there's no need or there's reduced need for IT experts

To understand cloud computing you must be able to answer these questions
-where are my applications running?
-where is my data stored?

BENEFITS OF CLOUD COMPUTING
-fast access to resources or applications you or your company needs.
-you only pay for what you use.
-there's no capital expenditure to get started.
-the potential to liminate the need for local IT staff to maintain infrastructure and applications.
-the potential to lower costs
-you deploy what you need, yourself, with self-service.
-allows IT staff to instead focus on the business

RISKS OF CLOUD COMPUTING
-placing your trust in the cloud provider i.e if you store all your data in aws or microsoft azure and one those platforms go down, you no longer have access to your data or applications.
-there's potential for data loss
-potential for slow access to your data
-potential questions related to legality/regulatory
-potential for loss of customization
-potential for unknown costs

FORMS OF CLOUD COMPUTING
SAAS: you're accessing applications directly in the cloud. These applications are already running in the cloud and you're just simply paying to use them. e.g gmail, office 365, salesforce.com, dropbox.
IAAS: with IAAS, you're accessing a virtual machine. The virtual machine is an instance of a physical computer virtualized and running in the cloud. It has an operating system, virtual hardware like virtual CPU, virtual memory, virtual storage, virtual networking.
PAAS: with PAAS, developers who need access to a platform or development platform i.e SQL to deploy a database or it could be a web server that's already running and deploy new web application can get their application and database up and running very quickly.

HISTORY OF CLOUD COMPUTING
"The more things change, the more they stay the same"
Cloud computing has been called several names in the past and they include:
-centralized computing
-grid computing
-distributed computing
-on-demand computing
-hosting
-Application Service Provider (ASPs)

----INFRASTRUCTURE AS A SERVICE (IAAS)----
WHAT IS VIRTUALIZATION?
It is the logical division of physical computing resources. Virtualization makes a physical server into a virtual host machine so that virtual host can then run guest virtual machines.
There are many resources that can be virtualized - server(compute), storage and network.
There are many forms of virtualization - including server and desktop virtualization.
Virtualization became popular with VMware's ESX server launched in 2001.
Virtualization hypervisor is a piece of software that makes virtualization possible.

WHAT IS A VIRTUAL MACHINE?
The hypervisor is the core piece of a virtualization solution.
A virtual machine is a software-based instance of a physical server where a guest operating system has access to emulated virtual hardware.
A virtual machine runs on top of a hypervisor that's loaded on a physical server. Those virtual guest machines or virtual guests as they're known, runs on top that physical server with the hypervisor and that becomes the virtual host. It provides all of the physical resources to the virtual machines to actually run the operating systems and applications.
The operating systems and applications loaded on the guest virtual machines don't know the difference. They don't know that they're running on virtual hardware and there's other virtual machines. They think they have full access to the physical hardware, to the physical server. So they're provided virtual resources from the hypervisor.
Virtualization is not cloud computing unless you're running the virtual desktop over in the cloud.

WHAT IS A CONTAINER?
A software container is an operating system-level virtualization where the operating system kernel provides isolated user spaces to run specific applications.
With containers, the operating system is sliced up into isolated secure areas to run specific applications. It's just one operating system and not multiple ones like with virtualization.
Containers can actually be run inside a virtual machine on a virtualization hypervisor.
Containers have much less overhead than virtualization and virtual machines, and they have much faster startup times than virtual machines.
Containers have been popularized with excitement around Docker containers.
Cloud uses both virtualizations and containers.

PRIVATE CLOUD, HYBRID CLOUD AND PUBLIC CLOUD
Private clouds are run on-premise meaning they're run in your own building, at your own datacenter. These types of clouds are for your company to leverage. They're run on your own infrastructure.
Public clouds are also referred to as IaaS eg amazon web services ec2 and microsoft azure virtual machines.
There is no real hybrid cloud. It's not a real place that you can run your application or a real place you can go to. What the hybrid cloud means is that you've connected your private cloud to your public cloud to create this hybrid cloud.
Hybrid cloud is the private cloud and public cloud working together. For example, you could run a database in the private cloud and web server in the public cloud and they could be communicating with themselves across this hybrid cloud.

VIRTUALIZATION VS PRIVATE CLOUD
Virtualiztion:
-required for cloud computing
-provides scalability and elastic computing
-provides that pooling and sharing capability of resources
-provides load balancing for the compute so that if one host runs out of resources, a virtual machine can be moved or started on a new host.
-provides high availability at the infrastructure level
-portability of the virtual machine so they can be moved around from host to host even from the private infrastructure into the public cloud across the hybrid cloud.
-provides the ability to clone an existing application or virtual machine, essentially duplicating that entire virtual guest operating system, applications and data into a new instance.

Private cloud on top of virtualization:
-provides abstraction of underlying infrastructure layer
-provides secure multi-tenancy
-self service portal
-catalog of applications essentially a catalog of virtual machines that I want to deploy.
-I get chargeback/showback meaning I can report on my usage and I can bill actually internally to the company or let's say I'm running a public cloud like amazon, I can bill my customers for the usage of the private or public cloud.
-potential to burst to a hybrid cloud

Virtualization is not the same as private cloud. Private cloud requires virtualization, public cloud requires virtualization.
But just because you have virtualization doesn't mean that you have cloud.

IAAS PRICING MODEL
The great thing about IAAS pricing is, ideally it is based on utility, consumption or subscription-based pricing i.e you pay for only what you use.
IaaS pricing models can get complex:
-On-demand: with this, you pay for the compute capacity by the hour with no long-term commitments or upfront payments. Its kind of the classic utility-based, consumption-based pricing model.
-Spot Instances: this is when you can bid on spare computing capacity for up to 90% off of the on-demand price. So if they extra capacity they're not using, you can bid on it and get it cheap. The downside of this is that the computing capacity could go away at any point.
-Reserved Instances: they cost less than on-demand pricing, but you also have to commit to a 1 to 3-year term. This is what you want to do if you're going to be running some production applications in the cloud for the long-term.
-Dedicated Hosts: this might be for your most critical production applications that you're going to be running in the cloud for the long term.
Amazon EC2 is the leader in infrastructure-as-a-service cloud computing.

SERVICE LEVEL AGREEMENT (SLA)
Having an SLA with your cloud provider is very important.
SLA defines what level of performance and availability the IaaS provider will provide you. It also tells you what would happen if the provider are unable to provide the level of service agreed upon
They're just not for IaaS, they're for any cloud computing provider whether it's a SaaS, PaaS or IaaS.
You should always be beware of the SLA that's being offered by your cloud provider.

MIGRATING TO THE CLOUD
Some companies have "greenfield deployments" but it's not common.
These are things you need to consider before you migrate to the cloud:
-costs associated with using the cloud
-what you require from the cloud in terms of security, availability and performance and what it would cost you
-migration vs rebuilding
-enterprise-grade functionality
-tools that can help in migration

----INFRASTRUCTURE AS A SERVICE NETWORKING----
IAAS NETWORKING OPTIONS
-Public networking: with this, IaaS virtual machines or containers, they have public IP network addresses. These virtual machines running in the IaaS cloud, they're on the internet using public IP addresses.
-Private Networking: here, you use VPNs which are software-based virtual tunnels through the internet to connect to these virtual machines running in the public cloud or in some cases, large enterprises will have dedicated connections meaning connections they have purchased through a telecom carrier that are private and allow them to connect directly to their virtual machines running in an IaaS public cloud.

VIRTUAL PRIVATE CLOUD (VPC) NETWORKING
VPC is not a private cloud.
VPC network is a private network that can be connected to your network.
With VPC in place, you have control over private IP addressing in the public cloud, routing, network access list basically security- who can get in and can't, and VPN connectivity back to your on-premises infrastructure.
So with VPC, you essentially have a private network in the public cloud that your virtual machines are running in. They may or may not have access to the public internet.

----STORAGE IN THE CLOUD----
UNDERSTANDING IAAS STORAGE
-You store your data or your files inside the virtual machine. Each virtual machine has storage of its own. In the case of IaaS cloud computing, each virtual machine in the cloud has its own virtual storage and it's stored with the virtual machine that's running in the cloud.
-You store your data outside the virtual machine. Each virtual machine can access external storage of some kind and it could be block storage in the cloud or object storage in the cloud. EBS = Elastic Block Storage.
Object storage is perfect for unstructured data. ie data that's not in the traditional file system structure.

CLOUD FILE STORAGE
-Dropbox
-Microsoft OneDrive
-Google Drive

OBJECT STORAGE
Object storage is storage for unstructured data. eg pictures, archival data, video files, graphics files, files you might offer for download from a website.
The most popular object storage in the world is amazon s3 or simple storage service and microsoft azure blob storage.
You can also run object storage on-premises. i.e ceph, swift, and others.
In aws storage, you can create a bucket.
A bucket is a name that represents a storage container. In that storage bucket, you'll store your objects, things like graphics and videos.

DATA PROTECTION IN THE CLOUD
Data protection solutions:
-crash plan
-carbonite
-aws storage gateway
-microsoft azure backup
These are great options for replicating your files only up to the public cloud

If you have to replicate your entire virtual machines including the operating system applications and data to the cloud, and also want them to be copied in many cases at intervals, then disaster recovery is introduced.
Disaster recovery solutions include:
-zerto
-veeam
-infrascale
They provide the ability to bring the machines up in the public cloud should your company have a disaster.

----INFRASTRUCTURE AS A SERVICE: SECURITY----
Cloud Security Concerns
-is my data safe?
-who can see my data?
-can my data be modified?
-who is responsible for securing my data?
The answer to these questions lies in the shared responsibility model between the cloud provider and the client.

ENCRYPTION
Encryption is the process of converting information or data into ciphertext, which cannot be easily understood by anyone except those who have the key.
Many cloud providers give you the option to encrypt your data whether it's in your virtual machine or if it's in some block or object storage, it can all be encrypted and then only you can have the key to decrypt that data.

COMPLIANCE
Examples of compliance you need to follow are
-laws or regulatory compliance, depending on the type of business that you run.
-you might have company requirements or policies or rules that require you to protect that data or treat it in a specific way.
-you might have standards for your industry or governace from your industry
-maybe even regulations from let's say the IRS that require you to treat that data and report it, again in a specific way.

VULNERABILITIES AND MITIGATION
Vulnerability is basically a hole that a malicious attacker could find in your infrastructure. It could be a database, virtual machine, web server.
With mitigation, you're monitoring the breaches as they come in and you're there to fend off the malicious attacker who is exploring some vulnerability.

Questions to likely ask your cloud provider concerning this.
-who keeps my operating systems and applications up to date?
-who performs backups of the data, and should something happen? have they been tested?
-who performs security scans of my virtual machines?

----COMPARING IAAS AND PAAS----
