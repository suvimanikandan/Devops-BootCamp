Intro to networking:
A brief history of how the internet was born:   
• It all started in the 1960s. The US department of Defense Advanced Research Projects Agency (DARPA) worked on a packet-switching theory to send a message between themselves and a partner university.   
• In the 1970s, Transmission Control Protocol and Internet Protocol (IP) was developed in order to link multiple networks together.  
• In the 1980s, dial-up was introduced as a way to access the internet and allowed the revolutionary way to communicated across the world using email.  
  This was possible through a local area network (LAN).  
• In the 1990s, hypertext markup language (HTML) and uniform resource locator (URL) were created to visualize what is called the World Wide Web (www).   
  In 1995 big things were happening, such as Windows 95, and large company launches that you most likely still shop on today.
• In the 2000s, the dotcom bubble had reached its end; however, this created a new wave of opportunity for technology.   
  Networking, the internet, and the devices you use today have evolved rapidly since the start of the early 2000s. From desktops, to laptops, to tablets, technology is constantly   
  
  What is computer networking?   
  A network is like a highway system, where a car travels (like a message) from point A to point B is the grocery store (website).  
  In this example, in order to get to point A to point B, you would get in some type of transportation (send a request) to go the store to buy what you need.  
  To get in some type of transportation (send a request) to go the store to buy what you need. To get there, transportation takes a series of roads (networks) to get to point B.  
  
  
What is computer networking? • It’s a collection of computing devices that are logically connected together to communicate and share resources.
• An example is like an interstate highway system that connects cities and states together from one point to another. Like networking, it made it possible to be connected in a faster and easier way.
How does it work at a basic level? • It has a node. A node is like a computer, router, switches, modems, and printers, which are connected through links (a way for data to transmit, such as cables), that follow rules to send and receive data.
• It has a host. A host is a node that has a unique function. Other devices connect to nodes so they can access data or other services. An example of a host is a server, because a server can provide access to data, run an application, or provide a service.   
  
  Data and osimodel:  
Data: • Data can be pictures, documents, code, text, etc. • Data can be sent over a network and saved 

The OSI model is the main model used in networking today.
The diagram illustrates how data flows in an OSI-compliant network from a source computer to a target computer.
1. Data starts from the source computer. The source computer sends data to the target computer. As the data leaves the source computer, it is processed and transformed by the different functions in the OSI layers, from layer 7 down to layer 1. During transmission of data, it can also be encrypted, and additional transmission-related information, which are called headers, are added to it.
2. Next, the data travels to the application layer (layer 7). This layer provides the interface that enables applications to access the network services.
3. Next is the presentation layer (layer 6). This layer ensures that the data is in a usable format and handles encryption and decryption.
4. The data moves to the session layer (layer 5). This layer maintains the distinction between the data of separate applications.
5. Next is the transport layer (layer 4). This establishes a logical connection between the source and destination. It also specifies the transmission protocol to use, such as Transmission Control Protocol (TCP).
6. The network layer (layer 3) decides which physical path the data will take. 7. The data link layer (layer 2) defines the format of the data on the network.   
  8. Finally, the data travels to the physical layer (layer 1), which transmits the raw bitstream over the physical network.
9. After the data has been transformed through the OSI layers, it is in a package format that is ready to be transmitted over the physical network.
10.Once the target computer receives the data package, it unpacks the data through the OSI layers, but in reverse, from layer 1 (physical) through 7 (application)  
  
  ayer 2 (the data link layer) a message or data is called a frame. Frames are associated with a Media Access Control (MAC) address which is known as a physical address.
At layer 3 (network layer) a message or data is called a packet. Packets are associated with Internet Protocol (IP) addresses.   
  
  Networking components 
  This section will cover the following networking components: • Client • Server • NIC • Network cables • Switch • Router
  
  client:The client connects to the server over a network.
A client is also a computer hardware device that accesses the data or a service that is managed by another computer hardware device, which is also called a server.
A client can also refer to software on the accessing device. For example, a web browser is a client for accessing content from a web server.   
  
  server:• The server has a specific job to respond to a request. When the client sends a request, the server will respond with the appropriate content the client is requesting.
• Other examples of a server are: • Web server • Database server • File server • Mail serve , print server   

NIC: A NIC: • Connects a computer to a computer network. • Can be wired or wireless. • Is sometimes referred to as a network adapter. • Has its own MAC address, a unique physical identifier to each device. This MAC address is used to identify the sender and receiver of data. The NIC and MAC address is used in layer 2 of the OSI layer.
The image is an example of a wired NIC.  
  
  Network cables:• Fiber-Optic: Its faster since it transmits light instead of electricity. 
    This cable is a good choice for areas that have high levels of electromagnetic interference (EMI) and can transmit data over distances of several kilometers.
• Coaxial: This is being replaced by fiber-optic.This cable is mainly used to connect a cable TV modem to an ISP, and to connect TVs to cable boxes. It has a coper wire in the middle with a metal braided shield.
• Twisted-Pair: This is the most common type of computer, telephone, and network cable. It is also known as the ethernet cable. It has color coded pairs which can come shielded (STP) or unshielded (UTP). STP will prevent electromagnetic interference.    
  
  A switch: • Operates at layer 2 of the OSI which means it deals with data as frames • Transmits data to only the receiving device. It makes a direct link by using MAC addresses between the transmitting device and the receiving device.
A hub works on the same layer as the switch; however, it transmits data that it receives on one port to all other ports on the hub, while the switch transmits data to only the receiving device. While all the ports/nodes receive the data from the hub, only the recipient actually listens to it. In this case, a switch is better because it saves a lot of bandwidth because it sends the data to the intended receiver.   
  
  A router: • Operates at layer 2 and 3 of the OSI, which means it deals with data as frames and packets.
• Connects multiple switches and their respective networks to form a larger network. This creates subnets, and the router then becomes a switch itself.
• Is different then a switch because it can actually filter data and a switch cannot.
Since the router operates at layer 3, it uses Internet Protocol (IP) to filter traffic and route traffic.   
  
   modem connects your home to the internet from the ISP. A coaxial cable is used and, depending on your modem, it will then provide a wireless connection to your devices, or you can connect an additional router by connecting it to a port behind the modem   
   
   Some key takeaways from this lesson include the following: • A computer network is a collection of computing devices that are logically connected to communicate and share resources.
• The main components of a computer network include: • Client devices • Servers • Network adapters (NIC) and cables • Switches • Routers
• The OSI model is a standard of how computers share information.
  
  
