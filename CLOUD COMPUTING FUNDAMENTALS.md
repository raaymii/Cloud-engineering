CLOUD COMPUTING FUNDAMENTALS: CLOUD CONCEPTS

Introduction to cloud computing
Cloud services include gmail/office 365, salesforce, netflix.

      -------- CLOUD PRINCIPLES ---------

Cloud vs On-premise
On-premise computing is also known as traditional computing. Traditional computing is made up of hardware which consists of processor, memory, harddrive and other components, operating system which interfaces with the hardware - the OS is a software layer that makes the hardware work and coordinates those resources, the applications layer which make users complete tasks such as working with documents or spreadsheets.
The issue with traditional computing is the pace of keeping up with innovation becomes staggering and overwhelming, this is where cloud computing comes in.

Cloud computing provides computing services, renting of computing resources, more flexibility and allows for scalability of the systems, allows users to access the latest technologies, enterprise-level data protection, reduced IT staff and less admin costs. With these, if the cloud is set up the right way, the user won't even know that a failure happened.

Technology Pillars of Cloud Computing
-Virtualization - this means that there's not a one-to-one relationship between a physical server and a logical server.
-Hypervisor - it allows multiple operating softwares to share the same host, and also manage the resource allocation to virtual operating softwares.

Cloud service models
Cloud providers sell everything as a service - virtual machines, databases, content delivery networks, anything that runs in the cloud can be sold as a service.

Fundamental cloud service/computing models
-Infrastructure as a service(IaaS) which is virtual hardware that replaces physical on-premise IT infrastructure. It can scale up and down based on the needs. As a user, you will pay for what you use. It is what powers the internet of things. It provides the necessary resources that enable high-performance computing. It is also facilities data storage, backup, and recovery options and services to users
-Platform as a service(PaaS) which adds features to infrastructure as a service. That includes operating systems and software development tools such as runtime environments. cloudware This layer adds the operating systems and software to the hardware or infrastructure as a service layer. It provides runtime environments. It allows developers to focus on apps. It provides provisioning and deployment as well as load balancing and autoscaling. This is great for APIs, devops, integration and machine learning activities.
-Software as a Service(SaaS) which is a software licensing and delivery model where apps are subscribed to and accessed over the internet. It has the largest market size of the three standard services

IaaS
This covers three fundamental aspects. These are compute - which is used for providing computing resources on demand, block-storage - which is used for providing blocks that can be used for storing information, network - which are all the resources required for providing users networking capabilities.

PaaS
This covers these fundamental aspects. Object storage which has to do with providing resources on how objects are stored. Identity which provides a layer for dealing with user authentication. Runtime layer for applications to run on. Queue which is used for batch and messaging operations. Database layer.

SaaS
With this, apps are accessed over the internet. It is the largest of the three models. It works based on a monthly fee or yearly subscription fee. An internet connection is required when accessing any SaaS application. The biggest concern is data security as the data is not stored on customer premises.
Aspects SaaS covers are application monitoring, content, collaboration technologies and services, communication tools and apps as well as finance applications

Other possible models that cloud computing can offer
Business processes(BPaaS) - processes such as payroll, IT helpdesk or other services
Communications(CaaS) - which provides things like voiceover IP, instant messaging, and video collaboration
Machine learning(MLaaS) - which provides services that allows users to easily implement machine learning solutions
Databases (DBaaS) - which provides out-of-the-box hosted SQL and NoSQL databases for users to work with without requiring any setup
Functions(FaaS) - which is a relatively new way of developing and architecting cloud applications

-------- Cloud deployment models---------
Its based on the fact that these clouds offer the best in scalability, reliability, flexibility, geographical independence and cost effectiveness.

Public clouds- they are the most popular and most common cloud deployment model. With this, whatever the client wants the client gets. If the client needs more resources, it can simply scale up and use those extra resources as needed. If more resources are used, the client pays more because that's part of the deal. They are operated by third-party companies which are also known as cloud providers such as Amazon Web Services, Microsoft Azure and Google cloud.

Private Cloud aka on-premise cloud - this cloud deployment model is achieved by purchasing virtualization software. By doing this, it is possible to set up individual clouds into which can operate within their own network and by doing this it has limited scalability. One great advantage of it is the company is in control of all its own security.

Hybrid cloud - combines the best features of public and private clouds. With hybrid cloud, we can store sensitive information privately and with confidence. Due to that, there's a tight control over the data that we process and store and the benefit and features of public cloud are enjoyed.

Community clouds - Its used for organizations that have common interests. Schools and companies that are merging might find this community cloud deployment model useful and by using it, clients know who the other clients are. A downside of it is that scalability and flexibility lesser than those found in public clouds.

With the exception of private clouds, all cloud types use the concept of shared resources
IN-DEPTH INFORMATION ON CLOUD COMPUTING TYPES CAN BE FOUND ON aws.amazon.com

Characteristics of cloud computing
They need be elastic meaning that should be able to grow or shrink if the client's needs change. This can be done via virtualization
They employ resource pooling. The provider's resources are seen as one large pool that can be divided among the client as needed
Clouds should be able to easily allocate resources and be able to do it fast. This is known as rapid elasticity.
Clouds must be self-service. this allows users to access additional resources such as storage, network or compute automatically 24/7/365 without requiring intervention from the service provider.
Cloud must be able to scale- ability to use more or fewer resources
Broad network access which means resources need to be accessible over the network by different types of clients such as workstations, laptops, and mobile phones using common access software such as web browsers. It still applies to users using OS like windows, macOS, iOS or android.
Clouds must be pay as you go which that cloud providers track a client's usage and then charge them for the services used.
Availability - means that Cloud resources are accessible and responsive when a client needs them.

Shared responsibility models
A server is perfectly secure until you install a network card. If the server is not connected to anything, there's no risk it can be compromised. The shared responsibility model is about who is responsible for the server security.
There are two actors that have a shared role and responsibility for the wellbeing of the server and its security.
The first participant is the customer - who is responsible for the security in the cloud.
RESPONSIBILITIES OF THE CUSTOMER

- In charge of the customer data and now the cloud provider.
- In charge of how the platform provided by the cloud provider is used, as well as applications, identity and access management to application resources.
- Responsible for the configuration and setup of the operating system and network firewall configuration.
- Responsible for the network traffic, the file system, and its structure and organization as well as data encryption and data intergrity.

The second participant is the provider - who takes responsibility for what it can realistically control such as the security of the cloud infrastructure and services.
RESPONSIBILITIES OF THE CLOUD PROVIDER

- Responsible for the necessary computing resources required for the client to be able to execute its operations.
- Must ensure that the customer has the necessary storage and database resources available to be able to successfully execute its operations.
- Extends to being able to provide the necessary networking resources.
- Needs to ensure that the cloud services being provided are available in different regions, as well as different availability zones and edge locations.

        -------- CLOUD NETWORKING CONCEPTS ---------

  Network Fundamentals
  A network is two or more computers or devices that can communicate with each other.
  Those devices need to have software that enables them talk to each other. These are called network client, which is built into every operating system.

From the networking side, there are three things required.

- Built-in network adapter aka network interface card. Its job is to enable the device to communicate on the network. Each NIC has the ability to communicate using one type of networking eg bluetooth, wifi, ethernet. It is important that for the two devices to talk to each other, they need to use NICs using the same technology. In other words, an ethernet-only device cannot communicate on a bluetooth network.
- Transmission method - which is how data travels from device to device. In the old days, this meant copper or fiberoptic cables.
- Networking protocols - this is the language that computers speak to facilitate communication. Protocols are analagous to human languages in many ways in that they provide the rules for common understanding.

Protocols
TCP/IP - Transmission Control Protocol/ Internet Protocol is the protocol of the internet. It is actually a modular suite of protocols working together to enable communication.

TCP/IP Protocol Suite Levels

- Process application protocols such as Telnet, RDP, SSH, FTP, DHCP, SMTP and HTTP(S).
- Host-to-host application protocols such as TCP and UDP.
- Internet protocols such as IP and network access protocols, such as Ethernet, ICMP, ARP and RARP
- Network access such as ethernet, fast, gigabit and wifi(802.11).
  Protocols at each layer within the model are responsible for different tasks. eg IP is responsible for is logical addressing. Any device on a TCP/IP network with an IP address, including computers, printers and router interfaces is called a host. Most of the protocols are at the process application layer such as RDP, SSH and HTTPS.

Common access types
Depending on how many users need cloud services, connecting to the cloud can take many forms. They include:

- HTTPS: Hyper Text Transfer Protocol Secure
- RDP: Remote Desk Protocol(mostly used on windows servers)
- SSH: Secure Shell (mostly used on linux). It allows clients to remotely connect to a virtual Linux machine securely and act as if the user were sitting at a virtual computer.
- VPN: Virtual Private Network
- Direct connect: It is used to provide a physical connection between your company's onsite network and the cloud provider's network.

HTTPS
It is mostly used to connect a single client or dozens of hundreds of clients to the cloud resources.
It is a secure TCP/IP application protocol designed to fetch web pages and encrypt data that is transmitted between a webserver and its client.
The alternative web protocol to HTTPS is HTTP. It does not encrypt transmissions. If the website starts with HTTP, do not put any information that you don't want to be transmitted in plaintext without encryption.
Key Features

- HTTPS can be used with any commercial web browser which is just specialized piece of software designed to request web pages from web servers.
- It encrypts data transmission through a Secure Socket Layer or SSL, not the data on the client or server. SSL is a standard security technology for establishing an encrypted link between a server and a client, typically a web server, website, and a browser or an email server or an email client. In other words, HTTPS encrypts data in transit but not data at rest.

RDP
Remote Desktop Protocol is a protocol used to log into an online Windows server. Once a user is logged in, they can use it just as they would use a computer sitting in front of them.
An awesome feature of the cloud is the abiility to create virtual instances of computers eg using the amazon web services (aws), elastic compute cloud (ec2), a cloud administrator or anyone with appropriate permission can create a virtual windows server.
This means that the server will act like any other windows server and can host and run applications, provide storage, and do anything else users need a server to do.
Once users are done with the virtual computer, can shut it off and no physical resources are wasted.

VIRTUAL SERVER USES
-providing extra server capacity almost instantaneously, allowing developers to test software on multiple operating systems and platforms, creating a staging environment for network administrators to install and configure changes before rolling them out to a production environment.

HOW CAN THE RDP BE USED?
-First you must install an RDP client onto the device that will be logging into the virtual instance.
-Windows includes an RDP client called Remote Desktop Connection.
-There are RDP clients for other systems. Linux users can use the rdesktop command, macOS - Microsoft Remote Desktop app,
android and ios users will find RDP clients in their respective app stores.
-RDP requires the use of a public/private key pair to authenticate users seeking to log in to remote instances.

SSH
Secure Shell is to Linux as RDP is to windows server instances.
SSH allows clients to remotely connect to a virtual Linux machine securely and act as if the user were sitting at the virtual computer.
In its most basic form, SSH is run as a text command from a command prompt.
If your OS does not have SSH clients, you can log in to putty to access it.

VPN
Virtual Private Network is a secure and private network connection that occurs through a public network. It can be used to connect individual users to a coporate network or server or to connect company networks or clouds together across the internet or public networks.
A VPN is a point-to-point secure tunnel through the internet. The tunnel private network connection provides security over the otherwise insecure connection.

Direct Connect
It is used to provide a physical connection between your company's on-site network and the cloud provider's network.

WHEN DO WE NEED TO USE A DIRECT CONNECT TYPE OF ACCESS?
-If a large number of users needs persistent access to cloud services.
-There is a large amount of data transferred between the cloud and the on-site network.

DIRECT CONNECT FEATURES
-Most cloud providers offer connections that support 100gb data transfers
-Lower bandwidth plans can be as cheap as about $50 per month.
-Faster plans with unlimited data transfers can cost more than $50k per month.
-They often come with exceptional uptime guarantees.

Software-defined Networking
The goal of SDN is to make networks more agile and flexible by separating the forwarding of network packets, the infrastructure layer, from the logical decision making process- the control layer.
Routers play a critical role in intra-network communications.
A router's job is to take incoming data packets, read the destination address, and send the packet on to the next network that gets the data closer to delivery.
Applications that needs a network actually interface with the SDN controller, thinking that they are directly working with the networking hardware.
The SDN controller also known as the control layer, consists of one or more devices that makes the decisin on where to send the packets. They are the brains of the operation. The physical devices just forward the packets based on what the control layer tells them.
The network packet is also known as the infrasture layer. Therefore, the job of the SDN controller is to understand how the application can talk to the infrastructure.

Load balancing
Load balancing technology predates its usage in the cloud. The way it works is that hardware devices conveniently named load balancers would essentially act like the web server to the outside world. Then when a user visits the website like amazon.com, the load balancer would send the request to one of the many real web servers to fulfil the request.

Load balancing configuration setup
-Cross-region configuration: all servers likely provide access to the same types of content. The big feature with this setup is that there are severs local to each region. Proximity to the users will help speed up network performance.
-Content-based configuration: It consists of splitting up the servers to handle specific types of requests.
Cloud-based load balancing has performance has performance benefits for high traffic networks and heavily used applications.

Benefits
-Performance: Servers that are specialized to handle a specific content type are often more efficient than the multipurpose ones.
-Scalability: With cloud-based load balancing, traffic spikes can be handled quite quickly. By provisioning additional virtual servers to handle the traffic when the capacity is no longer required, the servers are turned off.
-Reliability: With cloud-based load balancing, different servers can host the applicatin, even in different regions.

Domain Name System
DNS has one function on the network, and that is to resolve hostnames or URLs to IP addresses.
HOW DOES DNS WORK?
-Each DNS server has a database where it stores hostname-to-IP address pairs.
-If the DNS server does not have the IP address of the host you are seeking, it has the ability to query other DNS servers to help answer the request.

The port number is combined with the IP address to form a socket.
DNS - port 53
HTTP - port 80
HTTPS - port 443
RDP - port 3389
SSH - port 22

Firewalls
A firewall is a hardware or a software solution that serves a network security guard. At basic level, firewalls filter network traffic based on rules defined by the network administrator.
Firewalls can protect network resources from hackers lurking in the dark corners of the internet and they can simultaneously prevent computers on your network from accessing undesirable content on the internet.
So in essence, anti-malware examines files for threats whereas firewalls protect you from streams and network traffic that could be harmful to your computer.
Firewalls can be standalone black boxes, which can be software installed on a server or router or a combination of hardware or software.
Types of firewalls
-Network-based firewalls: designed to protect the whole network of computers and almost always is a hardware solution with the software on it. Most network-based firewalls have at least two network connections, one to theinternet and one to the internal network, or a private side. Some firewalls have a third network port for a second semi-internal network. This port is used to connect servers that can be considered both public and private, such as web and email servers. The intermediated network is known as demilitarized zone or DMZ.
-Host-based firewall: which protect only one computer and are almost always software solutions.
A DMZ can be configured as a space between two firewalls.
A firewall is configured to allow only packets, network data that passes specific security restrictions to get through.

Firewall Configurations
By default, firewalls are configured as default deny, which means that all traffic is blocked unless specifically authorized by the administrator.
A basic method of configuring firewalls is to use an access control list or ACL. The ACL is a set of rules that determines which traffic gets through the firewall and which traffic is blocked.
There will be different ACLs for inbound and outbound network traffic. ACLs are configured to block traffic by IP address, protocol or domain name or some combination of these. Packets that meet the criteria in the ACL are passed through the firewall to their destination.

        -------- CLOUD STORAGE CONCEPTS ---------

What the cloud really provides is compute, network and storage services without the need to invest in underlying hardware. Of these three service types, storage is the most tangible and understandable. The reason for this is that storage is the most widely used and the one that catapulted the cloud to popularity.

Benefits
-Among the benefits are convenient and easy file access so users can access files from anywhere in the world nearly instantaneously.
-It also allows for easy sharing and collaboration. Those same users can collaborate on a document or project, which wouldn't be nearly as easy or even possible if the files had to be stored on someone else's hard drive.
-It has a built-in automated redundancy.
The cloud has systems to back up all those files without users needing to intervene.
Cloud storage is very cheap. It's the cheapest of all cloud services solutions by far.

How cloud storage works
Storage in the cloud looks and acts a lot like storage on a local device, but massively scaled.
Cloud storage runs on a technology called software-defined storage which is like SDN that we explored in the previous module, but applied to storage.
There's a cloud-defined storage controller, which coordinates storage among various servers.
Using SDS on the server, one logical unit of storage can be composed of an innumerable number of physical hard drives, enabling virtually unlimited storage.
The same applies for another server in which a physical hard drive can be separated into a large number of logical storage units.
And for another server, every combination in between logical and physical storage is possible.

A good SDS solution will have the following features:
-Scalability and transparency: which means that both the amount of storage offered to clients and the underlying hardware should be scalable without any performing issues or downtime. Scalability for clients should be automated.
-Standard user reference: which means that the management and maintenance of the SDS solution should be as easy for administrators and clients.
-Storage type support: which means that the SDS solution should support applications written for object, file or block storage.

Cloud Storage Providers
There are no shortage of cloud providers in the world today. They come in different sizes from the big cloud service providers that deliver a full range of services, such as AWS, Azure and Google Cloud, to niche players that offer storage solutions only eg dropbox, box, apple iCloud, microsoft onedrive and google drive. Most of them will offer limited storage for free and premium services for more data-heavy users.
Most cloud storage providers offer synchronization to the desktop, which makes it so that you have a folder on your computer available and importantly, that folder will always have the most current edition of the folder stored in the cloud.

Storage Characteristics
Storage Performance types
-Hot storage: data that is available at all times and is instanly accessible. With hot cloud storage, we find that the access frequency to files is frequent, the access speed is fast, the media type used are solid state drives and the cost per gb is higher than with cold storage.
-Cold storage: data is not available immediately and it can take time to access such as archived data. It might take several minutes to several days to make cold data available to access. With cold storage, the access frequency to files is infrequent, the access speed is slow, and the media type used are usually hard disk drives, tape drives and could even be offline and the cost per gb is much lower than that with hot storage.
For both hot and cold storage types, cloud providers offer a wide range of storage solutions with varying performance and costs. eg
-microsoft azure offers premium, hot, cold and archived tiers
-google has two hot options, multiregional storage and regional storage, along with the nearline and coldline options.
-aws has two primary designations, which are its simple storage service s3, for hot data and s3 glacier for archives. Within s3 and s3 glacier, there are multiple options to choose from.

Storage containers
When clients uploads data to the cloud, that data is placed into a storage container.
Cloud providers call their containers by different names. eg aws and google cloud use the term bucket, whereas azure uses blob.
Providers allow clients to have multiple storage containers to meet their storage needs. eg many companies will have several hot containers for different offices or departments and more cold containers to archive data.
The end result is a flexible infrastructure that can be customized to meet any client's needs.

Key Performance Parameters
Regardless of what a cloud provider chooses to call its storage offering, focusing on the performance characteristics and costs is essential. The hotter the service and the more features it has, the more you will pay per gigabyte.
-cost per gigbyte
-storage capacity limits
-maximum numbers of containers allowed
-data encryption
-storage compression/deduplication
-intelligent analysis of storage usage / automated optimization.
-dynamic container resizing
-data read and write speed
-number of data reads/writes allowed or cost per 1000 reads/writes
-data latency for read/write
-data retrieval time for archives
-archive data retrieval costs.
Its possibly cheaper to pay for less capacity and then pay for overcharges than it is to pay for more capacity all the time.

Storage types and features
At the hardware level, data is storage as long strings of 1s and 0s on a storage media.
Its up to device operating system or software to interpret the data and know where a relevant piece of information begins and ends.
There are multiple ways in which data can be stored in the cloud and be retrieved by a computer.

3 cloud storage types
-file storage: its based on a concept of a filing cabinet. Each file has a unique name when you include the folder and subfolder its stored in. Its common in windows and mac-based computers
-block storage: files are split into chunks of data of equal size assigned to a unique identifier and then stored on the hard drive. A file structure is not needed because each piece of data has a unique address. Block storage allows files to be broken into more manageable chunks than being stored as one entity. This allows the operating system to modify one portion of a file without needing to open the entire file. Latency within a block storage is lower than with other types of storage and the data transfer is faster. Block storage is great for large structured datasets that need to be accessed and updated frequently.
-Object storage: this contains objects which can be literally anything wants to store. Each object contains the
/-data: this is the data of the object itself, literally the bits that make up the file or image or whatever is being stored.
/-metadata: thsi describes optional information about the object. It can be used for anything else that will be relevant for people trying to find the object.
/-attribures: these are classification of metadata such as color, person or other relevant characteristics. There are optional, but can make it easier to compare different unstructured datasets.

Storage Features
-compression: the purpose of compression is to make files smaller so they take up less storage space. Compression works by looking for repeated information within a file and then replacing that information with a shorter string; therefore fewer bytes are required to store the same amount of information.
-deduplication: compression and deduplication might seem like the same thing but they're not. Data deduplication works at the file level or block level to eliminate duplicate data.
-capacity on demand: it can be added anytime. If you need extra storage capacity, it is instantaneously available. So, you just pay for extra capacity that you use. Capacity on demand can be great, but it poses some risks as well. Storage capacity is like a balloon, it can go up and up but you need to ensure you don't go too high.

Content Delivery Network
It is a special type of storage load balancing used with web servers. It is primarily used to speed up access to web resources for users in geographically distributed locations.
CDNs allow users in remote locations to access web data on servers that are closer to them than the original web server is.

How does a CDN work?
The server is known as the origin because it's the primary content server. If users across the globe need to access this one server, there could be some potential issues. Latency or delay could be a problem. This is because users in Asia or Africa are quite some distance away. The number of users can also be a problem because the more users equates to slower response times.
The CDN creates a point of presence, PoP, in each remote location. Within each PoP will be one or more edge servers.
The job of the edge server is to cache the content of the origin and serve it to the users who are located nearby. If everything is configured properly, the edge server will have the same information that the origin does.
The cached content is typically a website, but it can include data such as plaintext, images, videos, audio, PDFs or even scripting files for programmers.
From the end-users standpoint, the location of the server is transparent.

Benefits of using a CDN
-Increased website performance via faster load times
-Increased website reliablity thanks to greater availability and redundancy
-Decreased bandwidth costs
-Greater scalability for web resources
-Increased website security.

        -------- CLOUD DESIGN ---------

A well designed cloud solution can save a company money in several ways.

Key design principles
-It can eliminate the sum cost of buying new hardware and software every few years just to have it go obsolete.
-It can enable users have faster and better access to data.
-A good cloud solution can help a company quickly recover from what would be otherwise a catastrophic data loss.

Redundancy in computer space means that there is some of device, system or process that can take over in an event of a failure and keep the system running.
Data redundancy can mean that critical data is accessible at any time from any location.
Network redundancy can mean that a key server or the internet is always available.
Redundancy plans enable another key features of cloud, which is high availability. This means that users have uninterrupted service and good responsiveness from cloud resources from their cloud provider.

Redundancy Plans
In cloud architecture, redundancy refers to backing up of data to ensure business continuity for organizations. Redundancy, if built into an organization’s cloud architecture, can ensure that companies have something to fall back on, in case of technical or physical failure.
When putting together your cloud needs, building a redundancy plan can help eliminate issues caused by a single point of failure, then work with your cloud provider to ensure that proper redundancy is built into the SLA. A cloud SLA (cloud service-level agreement) is an agreement between a cloud service provider and a customer that ensures a minimum level of service is maintained.
In most cases, you will need to balance the risk tolerance for a specific failure with the cost of implementing a redundant system.

Aspects Redundancy Plans Should Cover
-Hardware: Hardware redundancy usually refers to fault tolerance. Hardware redundancy solutions from a cloud provider should come in with uptime guarantees. Furthermore, hardware redundancy can refer to things such as storage, processors, memory or network devices.
-Network: Network redundancy typically refers specifically to network infrastructure such as switches and routers. It can also involve guaranteeing a certain amount of bandwidth.
-Geography (Georedundancy): Geography redundancy means that two or more physical locations have replicas of the same data. Those physical locations should be far enough apart that if one were to suffer a catastrophic natural disaster or failure, the others will be spared.
-Process: Business processed are frequently overlooked when it comes to redundancy, but they shouldn't be ignored. If a process fails, it could mean catastrophic results for a business; therefore, it is important to map out critical business processes and understand which ones are required for high availability. Then it is important to figure out what are the single points of failure.
-Software: Software redundancy can take one or two forms, redundancy of the program or redundancy within the program. Placing some sort of failsafe mechanism within software is a great way to achieve this.
-Data: Data redundancy takes the form of data backups. Data loss can come in different forms. Implementing some sort of data backup as part of the redundancy plan or disaster recovery plan may be legally required for a company, depending on its industry. Even if it's not, its the most important thing a company can do. If a company experiences data loss without having a backup, it might even go out of business. With cloud computing, backups and redundancy are incredibly easy to implement and generally not very expensive.

High Availabililty
Service availability is measured in terms of nines, or how many nines of uptime the provider guarantees. The level of uptime guaranteed by the cloud service provider will be specified in the software level agreement (SLA).

Availability Downtime
-Three nines means that the service will be available 99.9% of the time. This means a downtime of maximum 8.77 hours per year.
-Four nines means that the service will be available 99.99% of the time which means a downtime of maximum 52.6 minutes per year.
-Five nines means that the service will be available 99.999% of the time, which means a downtime for maximum 5.26 minutes per year.
-Six nines means that the service will be available 99.9999% of the time, which means a downtime for maximum of 31.56 seconds per year.
The level of services SLA you should get depends on how much risk your company is willing to take and the tradeoff with costs. Guaranteeing that services will be available with a possible exception of less than 1 second per day seems pretty impressive as it is the case with five nines.

Disaster Recovery
Disaster recovery is defined as the ability to become operational after a disaster.
The disaster can be catastrophic hardware or software failures, hackers or other cybercriminals, human error or forces of nature that cripple one or more computer systems.
Therefore, every organisation should have a disaster recovery plan which outlines the steps to take to regain operational status in the event of a disaster.
Disaster recovery plans need to account for all aspects of corporate network, infrastructure, including hardware, software, network, power and of course data. The plan should also specify what employees should do in an event of a disaster.

Disaster Recovery Planning
If you are buying cloud services from a cloud provider, they can help with disaster recovery planning and depending on how you set up your SLA, the disaster recovery could fall on them and not you.
Nevertheless, if that would be the case, assumin they're going to take care of everything, could be a tragic mistake.

Recovery Objectives
-Recovery Point Objective(RPO): This defines the maximum age of filse that must be recovered from backups to restore normal operations. In other words, how old can restored data be and still be useful to run the business? The client defines the RPO, which gets added to the SLA.
-Recovery Time Objective(RTO): This is the maximum amount of time a system can be offline in an event of a disaster. RTOs defines how long the provider has to get everything operational including network access and data restoration.

RPOs
-Different applications and datasets can and should have different RPOs. These depends on how critical they are how often they change.
-For example, operating system core files don't change often, and most likely you have the ability to restore an OS and necessary patches from installation media or online repositories, whereas if something like a medical data or financial transaction database would be lost, the RPO needs to be close to 0. So, catalog the different types of data your company has and then decide what the maximum age for good enough data is.

RTOs
They can and should vary by system. For instance, if your compaby has a website that does not handle any ecommerce transactions, then a failure might be annoying, but not essential to business operations. And beside all disaster recovery planning, high availability and cloud design you might have in place, there's one thing to remember. Don't assume anything. Don't make assumptions about what the cloud provider is going to provide in those areas.
Cloud providers do have redundancy and data recovery services available, but they must be agreed to in the SLA.
