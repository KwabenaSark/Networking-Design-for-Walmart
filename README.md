# Networking-Design-for-Walmart
#### {Cisco Packet Tracer, Protocols, Topology, Cabling}

## INTRODUCTION
Walmart is a retail giant that has expanded from its humble beginnings as a small store in Rogers, Arkansas, to tens of thousands of locations across the United States and beyond. Through innovations, it has created a seamless experience for customers to shop at any time and from any location. Walmart runs over 10,500 stores in 24 countries as well as eCommerce websites. Walmart employs 2.3 million people worldwide.

### Below are some of Walmart’s network requirements;
*	Switch – it is a multiport device that improves network efficiency by limiting routing information about internal network nodes and makes connections to hubs and routers easier. To link LAN strands, switches are widely employed. In Walmart, switches may read arriving packets' hardware addresses and send them to the correct destination.
Switches are vulnerable to distributed denial of service (DDoS) assaults, because of this Walmart uses various precautions to keep malicious traffic from shutting down the switch (Netwrix, 2019). 

*	Router  - it help in packet transit by navigating it through linked networking devices using various network topologies. Routers are network management devices that monitor the networks to which they are connected. Also, routers are Walmart's first line of defense, and they should be configured to only pass traffic that network administrators have approved. 


*	Hub – it is a networking device that connect multiple computers together. A hub can also function as a repeater, amplifying signals that have degraded over long. The simplest network connection device, a hub, is used by Walmart since it links LAN components using the same protocols.
As long as the incoming data is properly prepared, it can handle both digital and analog data. Hubs are also part of the physical layer of the OSI (Open System Interconnection) model.

*	Bridge – it is a networking device that enables communication between networks. For example it can be used to connects two LANs together. Bridges can forward or block data by validating the MAC addresses of the devices connected. It operates in the data link layers of the OSI (Open System Interconnection) model.

*	Modem - Walmart's digital signals are transmitted utilizing modems over analog telephone lines. As a result of this, the modem translates digital impulses into analog signals of varying frequencies, which are passed to a receiving station modem for transmission. The receiving modem provides a digital signal to a computer or other modem-connected device when the procedure is reversed. The modem usually sends and receives digital data over a serial line using the RS-232 interface, which is industry standard. Modems operates in the Data Link layers.




##	Below are ways technology is used to communicate within Walmart

*	Email – Simple Mail Transfer Protocol (SMTP)  - Internal e-mail servers are protected via SMTP  (Simple Mail Transfer Protocol). Messages sent to or from the Internet can be forwarded. As a result, internal e-mail are not immediately exposed to the Internet (Price-Evans, 2022).”

 Simple Mail Transfer Protocol is on layer 7 of the OSI model that is the application layer protocol. 

  
*	Video Conference – SIP (Session Initiation Protocol)  - is a protocol for signaling and controlling interactive communication sessions. Voice, video, chat, and instant messaging, as well as interactive games and virtual reality, uses SIP (Session Initiation Protocol)  .

Because SIP is an application-layer protocol in the OSI model, it can be used to create, manage, and pull down SIP traffic for VoIP and other communications and media applications.

*	Phone calls – VoIP (Voice over Internet Protocol) - allows voice calls to be made over the Internet (Federal Communications Commission, 2010).
VoIP is on the OSI model's sixth layer is also known as the Presentation Layer. It's where data is represented and encrypted. Data is compressed, decompressed, and encrypted if necessary in this layer. 

*	Web portals –  Hypertext Transfer Protocol (HTTP) IT allows information to be share data over the Internet  (Extrahop.com, 2021).












## 2

A logical topology is a networking concept that describes the design of a network. The logical topology of a network can be dynamically maintained and altered using network equipment such as routers and switches.

 

Walmart is likely to use the star logical topology because it is a well optimized topology. To obtain entire traffic management functionality, the management software simply has to connect with the switch, making it simple to control from a single panel.
As seen in the diagram above, each device is connected to a central hub. In a star topology, the central hub also serves as a server, while the connected nodes serve as clients. When a packet from a connecting node arrives to the central node, it can be passed to other network nodes. Below are some of the reasons why Walmart would go for star topology;

*	A single point of failure has less of an impact Each connecting node in a star topology is separated from the other connecting nodes. If one of the network's connecting nodes fails, the network's other connected nodes will continue to function normally.

*	Allows for easy adding and removing individual components from a network. 


For Wireless Technology in a star topology


 

From the diagram above wireless technologies such a wireless router connects  devices like laptops and smartphones to the internet via a switch. 







#### Two wireless protocols for rapid networking are listed below;
* IEEE 802.11 - The original 802.11 wireless standard was divided into two sections.  Both used the same 2.4GHz radio frequency and transmitted at 1 or 2Mbps. The two have different approaches to data transmission over RF medium. In one case, FHSS was applied, whereas in the other, DSSS was applied. 
* IEEE 802.11g - it is a popular wireless technology nowadays because it allows for wireless transmission across distances up to 150 feet and speeds of up to 54Mbps. Also it operates at 2.4GHz.

























### There are many types of firewall. Below are two of them;

*	Packet filtering firewalls – They're installed  at places where routers and switches are used. Rather than routing packets, these firewalls examine each one for a set of pre-defined criteria, such as authorized IP addresses, packet type, port number, and other packet protocol headers (Larsen, 2021).

*	Circuit-level gateways - during TCP handshakes and other network protocol initiations , signals  over the network between local and remote systems to see if the connection is genuine (if the signal can be trusted).  
## Below are some of the common threats to a network and countermeasures to prevent it;

##	DOS  and DDOS attack - 
When attackers overwhelm a server with traffic is a DoS attack, or denial-of-service attack, which is a malicious traffic overload. When a website receives an unusually high volume of traffic, it is unable to provide its content to visitors.

_"A DoS attack happens when a single computer and its internet connection flood a website with packets, preventing genuine users from reading the content"  (Borges, 2018)._ 

### Prevention
*	Having multiple servers -“ Attacking all servers at the same time is tough for a hacker. If a DDoS attack on a single hosting server is successful, other servers remain unaffected and can handle increased traffic until the targeted system is restored” (phoenixNAP Blog, 2021).

*	Keep an eye out for the warning signs – By doing this, traits of an attack can easily identified. Some common signs are; poor network connection, a single page or endpoint is in high demand, crashes and unusual traffic from a single IP.

*	Using the cloud to prevent attacks – With cloud-based defense large volumetric DDoS attack can be easily scaled and handled.

##	Rootkit –
it is a collection of software technologies that allow for remote access to a network. The rootkit can do a range of criminal operations, including keyloggers, password stealers, and antivirus disablers, if remote access is achieved.
They're hidden in legitimate software, and once you give it permission, it modifies the operating system. The rootkit then installs itself on computers and waits for the hacker to activate it. Rootkits can be spread through files , phishing emails, malicious links, and downloaded software from strange websites.

### Prevention
*	Regular  system scanning – scanning is one of the most effective ways to detect rootkit.

*	Monitoring network traffic - Network monitoring can also help to mitigate risks faster by isolating the attacked network parts and preventing the attack from spreading.

*	Keeping software up to date – “It's critical to keep software up to date in order to be safe and avoid being infected with malware by hackers. Keep all of  apps and operating system up to date to avoid rootkit attacks that take advantage of security flaws” (Maayan, 2020).


##	SQL Injection attack
– Many servers today store data using SQL. These injection attacks are designed to target data-driven applications and work by exploiting software security weaknesses. They use harmful code that steal, alter, or delete personal data, as well as to cancel online transactions. It has evolved into one of the most pressing data security and privacy issues.
### Prevention
*	Using the latest technologies – Using the most recent version of the development environment and language, as well as the most recent technologies 

*	Regular scanning - This will help find vulnerabilities in the network

## VPN     
A virtual private network (VPN), establishes a secure connection through the internet by routing data traffic through an encrypted virtual tunnel. This hides the IP address, making its location anonymous. As a result, it secures a network using encryption, allowing only authorized parties access.

### Below are some advantages and disadvantages of VPN
	
#### advantages
* Ensures anonymity.

Almost all websites may see one’s true IP address. VPNs hides the IP address and encrypt data. Hackers won't be able to steal personal information.
 

* Prevent Geo-locked restrictions 

Content providers use geo-restrictions to block websites for people in specific geographic locations. This is done to ensure that particular legal procedures are followed. When you try to access a webpage, you usually send a request that includes your true IP address. The webpages can simply determine the location based on your IP address and denied access instantly if one’s location is on the blacklisted list (Roomi, 2020).

#### disadvantages
* Dropped Connections

One of the most common problems that VPN customers face is connection dropouts. If this happens, you'll have to deal with the hassle of reconnecting it. 
Apart from that, because the encrypted connection is no longer active, your real IP address may be revealed. As a result, your anonymity may be compromised.

* Decreases connection speed 

Virtual private networks encrypt user data before sending it. 
Before being transferred to its final destination, data must first be sent to the VPN server, and then data must be sent back to the user via the same channel. Because of that process, user's internet speed will suffer as a result of the data traveling a longer distance  (A, 2021).











## 4
                            

 


The most affordable and fast cabling to be used for this network connection is shield twisted pair (STP) . Shielded twisted-pair cabling reduces crosstalk and other types of electromagnetic interference (EMI). It is also cheap and affordable compared to other cables in the market. Furthermore, STP has a speed range of 10 to 100Mbps
Hardware needed to allow employees connect to the Company Network
	Wireless Router- Employees' BYOD devices can be connected to a wireless router to gain access to the company's network.

Concerns
Employees will have unlimited access to the company network, they can miss use it which will slow it down. 
By putting in place a system that allows you to create a unique security profile for each end user. You may design a tailored security solution for each user that matches their particular demands while still meeting the company's general security criteria using profiling. 

You may tailor security policies based on the type of user, where they are, and what device they are using with a system like Cisco Identity Services Engine (ISE)  (CCB Technology, 2016).”



The protocol that allows devices to receive an IP address automatically is ; 

The Dynamic Host Configuration Protocol (DHCP) can automatically assigns an IP address and other configuration information to an Internet Protocol host. (Gerend, 2021).












## 5
a.
### Proprietary OS
	Cisco Internetwork Operating System (IOS)

### Open source  OS
	Open  network linux

b.

### Features of a Network Operating system includes the following;
•	Protocol support, processor support, hardware identification, and multiprocessing support for applications are all basic operating system functions.
•	Access to the network is regulated by security features such as Authentication, restrictions and access control.
•	Routing and WAN ports are examples of internetworking functionality.
•	web services and backup

c.
## Proprietary OS
	Cisco Internetwork Operating System (IOS)
Advantages	Disadvantages
Regular updates and fixes with a strong security	Support / updates may be expensive
Almost all standard protocols are allowed	Operational problems


## Open source  OS
	Open  network linux

#### Advantages	
Free to use and source code is available and can be modified
#### Disadvantages
Requires a specialist knowledge and may not be fully tested or developed or safe



* Cisco IOS would be the most appropriate network operating system for configuring network connectivity among the company's devices. Cisco IOS also provides a slew of extra services that administrators can utilize to boost network traffic performance and security such as encryption, authentication, firewall capabilities, policy enforcement, deep packet inspection, Quality of Service (QoS), intelligent routing, and proxy. Because it is a private network, the corporation would have complete access to it (Scarpati, 2020).





















### The network type that is appropriate for Walmart
Walmart is multinational companies with several branches across the world, as a result of this, the most suitable network for then is a WAN. 
The Wide Area Network covers a large network that extends over a geographical which will enable Walmart is able to communication between its official branches, also its enables employees to operate remotely with convenience and comfort.
For WANs scalability factors such as bandwidth, additional hardware components and the number of devices that will be connected to the network are all considered, an example is by using futureproof cables.


#### The following are hardware and how it connects to a network with regards to software and cost; 
* Hardware 	Connection  	Software 	Cost 
* Servers 	Connected to a switch that provides access to all networking devices	Microsoft Internet Information Services (IIS). 	$5,123.00 
* Desktop 	It connect to a switch 	Windows  11	$520.00 
* Modem 	Connects switches to internet service provider (ISP)	Fiber bandwidth 	$200.00 
* Switch 	For Interconnecting devices  	Cisco IOS 	$160 
* Router 	Allow wireless devices to connect to the network.	Cisco IOS 	$180 
* Printer 	Connected to a network through the switch 	HP LaserJet Software 	$150 

 

### Below are key aspects that will protect the network from threats
*	Firewalls – it manages traffic by blocking unwanted or unsolicited traffic 

*	Antivirus -  it identifies real-time threats to maintain the security of the network


*	Virtual private network (VPN) - All of the data traffic is routed through a virtual tunnel that is encrypted hence, masking IP address.

*	Network access control (NAC) – it blocks suspicious activities on a network and isolates devices 

### VPN solutions for Remote working
By establishing a secure link between the network and the devices used by remote workers, VPNs can be utilized to facilitate remote working. Once connected, employees will be able to access network resources .
A dedicated network access server or a software application operating on a shared server can both be used as a network access server. Using a remote access VPN, the user connects to the NAS via the internet (Spadafora, 2020).

### How VOIP impacts a network and why VOIP uses UDP
VoIP stands for voice over internet protocol, which is used to make and receive calls over the Internet, which could affect a network’s performance. VoIP codecs (codec and decoder) compress packets to maximize network efficiency, resulting in jitters and delay when using the Internet. 
UDP gives VoIP users a better experience by allowing them to have a continuous, real-time call with no delays. Unlike TCP, where faults are more visible, packet losses on UDP. have a minor impact on audio output  (VIP VoIP, 2018)





















#### References
A, Z., 2021. Online Security News, Reviews, How To and Hacks. [Online] 
Available at: https://securitygladiators.com/vpn/advantages-disadvantages/
[Accessed 30 3 2022].
Borges, E., 2018. Securitytrails. [Online] 
Available at: https://securitytrails.com/blog/top-10-common-network-security-threats-explained
[Accessed 30 3 2022].
CCB Technology, 2016. CCB Technology. [Online] 
Available at: https://ccbtechnology.com/byod-5-biggest-security-risks/
[Accessed 4 4 2022].
Extrahop.com, 2021. Extrahop.com. [Online] 
Available at: https://www.extrahop.com/resources/protocols/http/
[Accessed 29 3 2022].
Federal Communications Commission, 2010. Federal Communications Commission. [Online] 
Available at: https://www.fcc.gov/general/voice-over-internet-protocol-voip
[Accessed 29 3 2022].
Gerend, J., 2021. Dynamic Host Configuration Protocol (DHCP). [Online] 
Available at: https://docs.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top#:~:text=Dynamic%20Host%20Configuration%20Protocol%20(DHCP)%20is%20a%20client%2Fserver,subnet%20mask%20and%20default%20gateway.
[Accessed 4 4 2022].
Larsen, A., 2021. SearchSecurity. [Online] 
Available at: https://www.techtarget.com/searchsecurity/feature/The-five-different-types-of-firewalls
[Accessed 30 3 2022].
Maayan, G., 2020. Malwarebytes Labs. [Online] 
Available at: https://blog.malwarebytes.com/how-tos-2/2020/01/how-to-prevent-a-rootkit-attack/#:~:text=To%20fully%20protect%20yourself%20against,then%20reinstall%20the%20entire%20system.&text=Phishing%20is%20a%20type%20of,or%20downloading%20an%20infected%20attachment.
[Accessed 30 3 2022].
Netwrix, 2019. Netwrix.com. [Online] 
Available at: https://blog.netwrix.com/2019/01/08/network-devices-explained/
[Accessed 28 3 2022].
phoenixNAP Blog, 2021. phoenixNAP Blog. [Online] 
Available at: https://phoenixnap.com/blog/prevent-ddos-attacks
[Accessed 30 03 2022].
Price-Evans, I., 2022. What is Session Initiation Protocol (SIP)?. [Online] 
Available at: https://www.metaswitch.com/knowledge-center/reference/what-is-session-initiation-protocol-sip
[Accessed 29 3 2022].
Roomi, M., 2020. HitechWhizz - The Ultimate Tech Experience. [Online] 
Available at: https://www.hitechwhizz.com/2020/02/7-advantages-and-disadvantages-risks-benefits-of-vpn.html
[Accessed 30 3 2022].
Scarpati, J., 2020. SearchNetworking. [Online] 
Available at: https://www.techtarget.com/searchnetworking/definition/Cisco-IOS-Cisco-Internetwork-Operating-System
[Accessed 4 4 2022].
Spadafora, A., 2020. TechRadar. [Online] 
Available at: https://www.techradar.com/vpn/remote-access-vpn
[Accessed 5 4 2022].
VIP VoIP, 2018. VIP VoIP. [Online] 
Available at: https://www.vipvoip.co.uk/tcp-vs-udp/#:~:text=Why%20UDP%20is%20used%20with,audio%20and%20usually%20goes%20unnoticed.
[Accessed 5 4 2022].


