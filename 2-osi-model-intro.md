1. Introduction to Computer Networking
1.1 What is Computer Networking?
Definition: Computer networking is the process of connecting two or more computers or devices through a wired or wireless communication medium to exchange information and share resources.

Example:

Suppose Computer A is connected to Computer B through:
- An Ethernet/LAN cable (wired).
- Wi-Fi (wireless).
- Bluetooth (wireless).
Both computers can communicate and exchange information.
1.2 Why Do We Need Networking?
Initially, computers were designed to perform tasks independently. However, as computer technology developed, the need for communication between computers increased.

Networking was introduced to overcome this communication gap.

Main purposes of networking:
1. File Sharing: Sharing files between computers.
2. Resource Sharing: Sharing printers, storage devices, etc.
3. Communication: Exchanging information between computers.
4. Internet Sharing: Allowing multiple devices to access the Internet.
5. Data Exchange: Transferring information between different systems.
Example: In an office, multiple computers can access the same printer through a network.
1.3 Networking Hardware
RJ45 Ethernet Port

A commonly used Ethernet port that allows computers and other devices to connect through an Ethernet cable.

Ethernet Cable (LAN Cable)

A physical communication medium used to connect devices within a wired network.

NIC (Network Interface Card)

A hardware component that allows a computer to connect to a network through Ethernet or wireless technology.

Important: Not every computer requires an RJ45 port because wireless networking is also possible.
2. Networking Standards and Protocols
As networking developed, different manufacturers initially used different communication technologies and hardware.

This created compatibility problems when connecting computers from different manufacturers.

To solve these problems, common networking standards and protocols were introduced.
2.1 What is Standardization?
Definition: Standardization is the process of establishing common rules and specifications so that different devices and systems can communicate and work together.

Example: Computers from different manufacturers can communicate because they follow common networking standards.
2.2 What is a Network Protocol?
Definition: A network protocol is a set of predefined rules that determines how devices communicate and exchange data over a network.

Examples:
Protocol	Purpose
TCP	Reliable data transmission
IP	Logical addressing and packet delivery
HTTP	Web communication
HTTPS	Secure web communication
FTP	File transfer
DNS	Domain name resolution


2.3 ISO – International Organization for Standardization
Definition: ISO is an international organization responsible for developing and publishing standards across different industries, including information technology and networking.

One of its important contributions to networking was the development of the OSI reference model.

Full Form: International Organization for Standardization.
2.4 Interoperability
Definition: Interoperability is the ability of different computer systems, devices, or software from different manufacturers to communicate and exchange information.

Example: A Windows computer communicating with a Linux server over a network.
3. ARPANET – Beginning of Modern Networking
Full Form: Advanced Research Projects Agency Network.

ARPANET was an early packet-switching network developed in the United States with support from ARPA, an agency of the US Department of Defense.
Important Points
- ARPANET became operational in 1969.
- It connected computers at different research institutions.
- It used packet-switching technology.
- It became an important foundation for the development of the modern Internet.
What is Packet Switching?
Definition: Packet switching is a communication technique in which data is divided into smaller units called packets and transmitted across a network.

At the destination, the packets are processed and reassembled to recover the original information.

Example: When you download a large file, its data is transmitted through multiple packets rather than one continuous block.

Important correction: ARPANET was not the original name of the OSI model. They are two completely different networking concepts.
4. OSI Model (Open Systems Interconnection)
4.1 What is the OSI Model?
Definition: The OSI model is a seven-layer reference model developed by ISO to explain how data communication takes place between different computer systems over a network.

It divides network communication into seven layers, with each layer performing a specific function.

Full Form: Open Systems Interconnection.
History
- Late 1970s: Work on networking standardization developed.
- 1980s: The OSI architecture was formalized.
- 1984: The OSI reference model was published as an international standard.
Main Objectives
1. Standardize network communication.
2. Improve interoperability between different vendors.
3. Divide communication into manageable layers.
4. Simplify network troubleshooting.
5. Establish common communication guidelines.
4.2 Seven Layers of the OSI Model
Layer	Name	Main Function
7	Application	Provides network services to applications
6	Presentation	Data formatting, encryption and compression
5	Session	Establishes and manages sessions
4	Transport	End-to-end data delivery
3	Network	Routing and logical addressing
2	Data Link	Framing and MAC addressing
1	Physical	Transmission of bits


Layer 7 – Application Layer
Definition: Provides network services to applications and allows software to communicate over a network.

Functions:
- Web browsing.
- Email communication.
- File transfer.
- Network resource access.
Protocols: HTTP, HTTPS, FTP, SMTP and DNS.

Example: Opening Google Chrome and accessing a website.
Layer 6 – Presentation Layer
Definition: Responsible for translating, formatting, encrypting and compressing data so that the receiving system can understand it.

Functions:
- Data translation.
- Encryption and decryption.
- Data compression.
- Data formatting.
Examples: JPEG, PNG, ASCII and UTF-8.

Example: Encrypting information before transmitting it to protect it from unauthorized access.
Layer 5 – Session Layer
Definition: Responsible for establishing, maintaining and terminating communication sessions between applications.

Functions:
- Session establishment.
- Session maintenance.
- Session termination.
- Synchronization.
Example: Managing a communication session during an online meeting.
Layer 4 – Transport Layer
Definition: Provides end-to-end communication between applications running on different devices.

Functions:
- Segmentation and reassembly.
- Port addressing.
- Flow control.
- Error recovery.
- Reliable data delivery when using TCP.
Protocols: TCP and UDP.

Example: Downloading a file from a server.
Layer 3 – Network Layer
Definition: Responsible for delivering data packets from source to destination across different networks.

Functions:
- Logical addressing.
- Routing.
- Path determination.
- Packet forwarding.
Example: Routers forwarding packets toward a destination using IP addresses.

Protocol: IP.
Layer 2 – Data Link Layer
Definition: Responsible for transferring data between directly connected devices over a network link.

Functions:
- Framing.
- MAC addressing.
- Error detection.
- Media access control.
Example: Ethernet communication between a computer and a switch.
Layer 1 – Physical Layer
Definition: Responsible for transmitting raw binary data (0s and 1s) through a physical communication medium.

Functions:
- Transmission of bits.
- Electrical and optical signals.
- Cables and connectors.
- Physical transmission speed.
Examples: Ethernet cables, fibre-optic cables and physical network connectors.
5. TCP/IP Architecture and TCP/IP Model
5.1 What is TCP/IP?
TCP/IP stands for Transmission Control Protocol/Internet Protocol.

Definition: TCP/IP is a networking protocol architecture that defines how computers communicate and exchange information across interconnected networks.

It provides a common set of communication protocols that allows different computers, operating systems and networking devices to communicate with each other.

Example: When you open YouTube, your computer communicates with YouTube's servers using TCP/IP protocols.
5.2 History and Development of TCP/IP
TCP/IP was developed through research supported by ARPA (Advanced Research Projects Agency).

Important historical events:
Year	Development
1969	ARPANET became operational.
1974	Vint Cerf and Bob Kahn published an important paper describing internetworking protocols.
1978	TCP was divided into TCP and IP.
1981	TCP and IP specifications were published as standards.
1983	ARPANET officially transitioned to TCP/IP.


Important contributors:
- Vint Cerf.
- Bob Kahn.
Both are widely recognized as the fathers of the Internet.
5.3 Why Was TCP/IP Developed?
Before TCP/IP, different computer networks used different communication technologies and protocols.

This created difficulties when trying to connect independent networks.

TCP/IP was developed to solve this problem by providing a common communication architecture.

Main objectives:
1. Connect different networks.
2. Enable communication between different computer systems.
3. Provide logical addressing.
4. Enable routing between networks.
5. Support reliable data transmission through TCP.
Important Definition – Internetworking:

Internetworking is the process of connecting multiple independent networks so that devices across those networks can communicate with each other.
5.4 Four Layers of the TCP/IP Model
Unlike the OSI model, which contains seven layers, the commonly taught TCP/IP model contains four layers.
Layer	Name	Main Function
4	Application	Provides network services to applications
3	Transport	Manages end-to-end communication
2	Internet	Handles IP addressing and routing
1	Network Access	Handles local network communication and physical transmission


Layer 4 – Application Layer
Definition: The Application Layer provides network services to applications and allows software to exchange information over a network.

It combines the functions of the Application, Presentation and Session layers of the OSI model.

Main functions:
- Web browsing.
- Email communication.
- File transfer.
- Domain name resolution.
- Network resource access.
Important protocols:
Protocol	Purpose
HTTP	Web communication
HTTPS	Secure web communication
FTP	File transfer
SMTP	Sending emails
DNS	Domain name resolution
DHCP	Automatic IP configuration


Example: When you open Google Chrome and access YouTube, the browser uses application-layer protocols to communicate with the server.
Layer 3 – Transport Layer
Definition: The Transport Layer provides end-to-end communication between applications running on different devices.

Main functions:
- Segmentation and reassembly.
- Port addressing.
- Flow control.
- Error recovery.
- Reliable data delivery when using TCP.
Important protocols:

1. TCP (Transmission Control Protocol)

TCP is a connection-oriented protocol that provides reliable and ordered data transmission.

Features:
- Reliable delivery.
- Data sequencing.
- Acknowledgements.
- Retransmission of lost data.
Example: Downloading a document.

2. UDP (User Datagram Protocol)

UDP is a connectionless protocol that provides lightweight communication without guaranteeing delivery or ordering.

Features:
- Low overhead.
- No delivery guarantee.
- No guaranteed ordering.
- Suitable for real-time communication.
Example:
- Online gaming.
- Voice calls.
- Live video communication.
What are Port Numbers?

A port number identifies a particular application or service running on a device.
Port	Protocol	Purpose
21	FTP	File transfer
22	SSH	Secure remote access
25	SMTP	Email sending
53	DNS	Domain resolution
80	HTTP	Web communication
443	HTTPS	Secure web communication


Remember: Transport Layer = TCP + UDP + Port Numbers.
Layer 2 – Internet Layer
Definition: The Internet Layer is responsible for delivering packets from the source device to the destination device across interconnected networks.

Main functions:
- Logical addressing.
- Routing.
- Packet forwarding.
- Path determination.
Important protocols:
Protocol	Purpose
IP	Logical addressing and packet delivery
ICMP	Network error reporting and diagnostics
IGMP	IPv4 multicast group management


IPv4 and IPv6

There are two major versions of IP:
- IPv4: Uses a 32-bit address.
- IPv6: Uses a 128-bit address.
Examples:

IPv4: 192.168.1.10

IPv6: 2001:db8::1

Example: When you access a website hosted in another country, routers use IP addresses to forward packets toward the destination.

Remember: Internet Layer = IP Addressing + Routing + Packets.
Layer 1 – Network Access Layer
Also known as the Network Interface Layer or Link Layer.

Definition: The Network Access Layer handles communication over a local network and the transmission of data through the physical communication medium.

It combines the functions of the Physical and Data Link layers of the OSI model.

Main functions:
- Physical transmission.
- Framing.
- MAC addressing.
- Media access control.
- Error detection.
Examples:
- Ethernet.
- Wi-Fi.
- LAN cables.
- Network Interface Cards (NICs).
- Network switches.
Example: When your laptop sends data to a Wi-Fi router, the Network Access Layer handles the local network transmission.

Remember: Network Access Layer = Frames + MAC Addressing + Physical Transmission.
6. Difference Between OSI and TCP/IP Models
Both models explain how communication takes place between computers, but their structures are different.
OSI Model	TCP/IP Model
Contains seven layers.	Commonly contains four layers.
Developed by ISO.	Developed through ARPA-supported research and Internet standardization.
Primarily a reference model.	Practical protocol architecture.
Separates Application, Presentation and Session layers.	Combines their functions into Application Layer.
Separates Physical and Data Link layers.	Combines their functions into Network Access Layer.


Layer Mapping
OSI Model	TCP/IP Model
Application	Application
Presentation	Application
Session	Application
Transport	Transport
Network	Internet
Data Link	Network Access
Physical	Network Access


Important: The TCP/IP model is not simply another name for the OSI model. They are different networking architectures.
7. Data Transmission Through Networking Layers
Let's understand how data travels from one computer to another.

Suppose you send a message from your computer to another computer.

The data passes through different layers before reaching its destination.
At the Sender's End
1. Application Layer: Creates the data.
2. Transport Layer: Divides data into segments.
3. Internet Layer: Adds IP addressing information and creates packets.
4. Network Access Layer: Encapsulates packets into frames.
5. Physical Transmission: Transmits the information as bits.
At the receiving end, the reverse process takes place.

This is known as Encapsulation and Decapsulation.
Important Definitions
Encapsulation: The process of adding necessary protocol information, such as headers, to data as it moves down the networking layers.

Decapsulation: The process of removing and interpreting protocol information as data moves up the networking layers at the receiving end.
Data Units in Networking
Layer	Data Unit
Application	Data
Transport	Segment (TCP) / Datagram (UDP)
Internet	Packet
Network Access	Frame
Physical (OSI)	Bits


8. Important Networking Terminology – Quick Revision
Term	Definition
Networking      	Connecting devices to communicate and share resources.
Protocol	        Rules governing network communication.
Standardization 	Establishing common rules and specifications.
ISO	                International Organization for Standardization.
Interoperability	Ability of different systems to communicate.
ARPANET	            An early packet-switching network.
Packet Switching	Dividing data into packets for transmission.
OSI             	Seven-layer networking reference model.
TCP/IP         	Networking protocol architecture.
TCP	            Reliable, connection-oriented transport protocol.
IP	            Protocol responsible for logical addressing and packet delivery.
Routing	        Selecting a path for packets to reach their destination.
Encryption  	Converting readable data into an encoded format.
Decryption  	Converting encrypted data back into readable information.
Encapsulation	Adding protocol information to data.
Decapsulation	Removing protocol information from received data.


9. Quick Revision – Everything in One Sequence
This is the sequence you should follow when revising the entire lecture.
No.	Topic	What to Remember
1	Networking Basics	    Connecting computers and devices
2	Need for Networking	    Communication and resource sharing
3	Networking Hardware	    RJ45, Ethernet, NIC
4	Standardization	        Common networking rules
5	Protocols	            Rules of communication
6	ISO	                    International standards organization
7	Interoperability	    Communication between different systems
8	ARPANET	                Early packet-switching network
9	OSI Model	            Seven-layer reference model
10	OSI Layers	            Application to Physical
11	TCP/IP Architecture	    Practical networking protocol architecture
12	TCP/IP Model  	        Four layers
13	OSI vs TCP/IP	        Differences and layer mapping
14	Data Transmission	    Encapsulation and decapsulation