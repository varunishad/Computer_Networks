## Computer Networks

A computer network is a set of devices connected through links, where devices can be computer, printer, or anything capable of sending or receiving the data and links can be wired or wireless.

The aim of computer network technology is to help people interact with each other through a network.

![Computer Network](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-tutorial.png)

* * *

### Components of computer Network

NIC, hub, switch, cable, router and modem are some of the important components which are needed to install the software.

![Computer Network Components](https://static.javatpoint.com/tutorial/computer-network/images/components-of-computer-network.png)

#### NIC (network interface card)

 NIC contains the hardware addresses, the data-link layer protocol use this address to identify the system on the network so that it can transfer the data to the correct destination.

 There are two types of NIC:

 1. **Wireless NIC:** In this, a connection is made using the **radio wave technology** which is employed by antennas.

 2. **Wired NIC:** Cables uses the **wired NIC** to transfer the data over the medium.

#### Hub

 A Hub is a central device that splits the network connection into multiple devices. When a computer requests for information from another computer, it first sends the request to the Hub. Hub then broadcasts this request to the entire network. All the other devices check whether the request belongs to them or not. If not, the request gets dropped.

#### Switch

 A Switch groups all the devices over the network to transfer the data to another device. It directly sends the data to the device for which it belongs to i.e., from source to the destination.

#### Cables and Connectors

 Cable is a transmission media used to transmit a communication signals.

 There are three types of cables:

 1. **Twisted pair cable:** Transmits data over 1Gbps or more.

 2. **Coaxial cable:** Resembles like TV installation cable but provides high data transmission speed.

 3. **Fibre optic cable:** It transmits data using light beams. Hence, provides high data transmission speed as compare to other cables.

#### Router

 Router is a device that connects the LAN to the internet. The router is mainly used to connect the distinct networks or connect the internet to multiple computers.

#### Modem

 Modem allows the computer to connect to the internet over the existing telephone line. It stands for Modulator/Demodulator as it converts the digital data into an analog signal over the telephone lines.

### Computer Network Architecture

 Two types of architecture are used in computer networks:

 #### 1. Peer-To-Peer network:

 * In this all the computers are linked together with equal privilege and responsibilities for processing the data.

 * Special permissions are assigned to each computer for sharing the resources, but this can lead to a problem if the computer with the resource is down.

 * Useful for small environments, usually up to 10 computers.

![Peer-to-peer](https://static.javatpoint.com/tutorial/computer-network/images/peer-to-peer-network.png)


 #### 2. Client/Server network:

 * It is a network model designed for the end users called clients, to access any resource from a central computer known as Server.

 * The central controller is known as a server while all other computers in the network are called clients.

 * A server performs all the major operations such as security,network management, and is responsible for managing all the resources such as files, directories, etc.

 ![lient/Server network](https://static.javatpoint.com/tutorial/computer-network/images/client-server-network.png)

### Types of Computer Networks:

 ![Computer Network Types](https://static.javatpoint.com/tutorial/computer-network/images/types-of-computer-network.png)

 **1. PAN (Personal Area Network):**
 * It is a network created within an individual person, typically within 10 meters.

 * Devices that are used to develop the personal area network are the laptop, mobile phones, media player, play stations,etc.

 ![PAN](https://static.javatpoint.com/tutorial/computer-network/images/personal-area-network.png)

 Two types of personal area network:

 1. Wired Personal Area Network
 2. Wireless Personal Area Network

 **2. LAN (Local Area Network):**

 * It is a group of computers connected to each other in a small area such as building, office.

 * It is used for connecting two or more personal computers through a communication medium such as twisted pair, coaxial cable, etc.

 * Collection of PAN is known as LAN.


 ![LAN](https://static.javatpoint.com/tutorial/computer-network/images/local-area-network.png)

 **3. MAN (Metropolitan Area Network):**

 * It is a network that covers a larger geographic area by interconnecting different LANs to form a larger network.

 * In this, different LANs are connected to each other through a telephonic exchange line.

 * Used in colleges, communication between bank in a city .

 ![MAN](https://static.javatpoint.com/tutorial/computer-network/images/metropolitan-area-network.png)

 **4. WAN (Wide Area Network):**

 * A WAN is not limited to a single location, but it spans over a large geographical area through a telephone line, fibre optic cable or satellite links.

 * Widely used in the field of Business, government, and education.

 * The internet is one of the biggest WAN in the world.

 ![WAN](https://static.javatpoint.com/tutorial/computer-network/images/wide-area-network.png)


### Network Topologies:

 Topology defines the structure of the network of how all the components are interconnected to each other.

 #### Types of Network Topology:

 * **Bus Topology:**

 * All the stations are connected through a single cable known as a backbone cable and each node is either connected to the backbone cable by drop cable or directly connected to the backbone cable.

 * When a node wants to send a message over the network, it puts a message over the network. All the stations available in the network will receive the message whether it has been addressed or not.

 ![BUS](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-topologies-bus-topology.png)

 * **Ring Topology:**

 * The node that receives the message from the previous computer will retransmit to the next node.

 * The data flow is unidirectional i.e., in clockwise direction.

 * Each node is connected to other node having no termination point. Hence, The data flows in a single loop continuously known as an endless loop.

 ![Ring](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-topologies-ring-topology.png)

 * **Star Topology:**

 * Every node is connected to the central hub, switch or a central computer known as **server** and the devices attached to the server are known as **clients**.

 * Hubs or Switches are mainly used as connection devices in a physical star topology.


 ![STAR](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-topologies-star-topology.png)

 * **Tree Topology:**

 * It is a combination of bus topology and star topology.

 * All the computers are connected with each other in hierarchical fashion.

 * The top-most node in tree topology is known as a root node, and all other nodes are the descendants of the root node.

 ![Tree](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-topologies-tree-topology.png)

 * **Mesh Toplogy:**

 * It is an arrangement of the network in which computers are interconnected with each other through various connections.

 * There are multiple paths from one computer to another computer.

 * It is mainly used for wireless networks. The Internet is an example of the mesh topology.

 ##### Types of Mesh Topology:

 * **Full Mesh Topology:** Each computer is connected to all the computers available in the network.

 * **Partial Mesh Topology:** Not all but certain computers are connected to those computers with which they communicate frequently.

 ![MESH](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-topologies-mesh-topology.png)

 * **Hybrid Topology:**

 * It is the combination of various different topologies.

 * It is a connection between different links and nodes to transfer the data.

 * Similar topologies connected with each other will not result in Hybrid topology.

 ![HYBRID](https://static.javatpoint.com/tutorial/computer-network/images/computer-network-topologies-hybrid-topology.png)

### Transmission Modes:

 - The way in which data is transmitted from one device to another is known as **transmission mode**. It is defined in the physical layer.

 - Each communication channel has a direction associated with it, and transmission media provide the direction. Therefore, the transmission mode is also known as a **directional mode**.

 Transmission mode is divided into three categories:

 **1. Simplex Mode:**

 ![Simplex](https://static.javatpoint.com/tutorial/computer-network/images/transmission-modes-simplex-mode.png)

 * In Simplex mode, the communication is unidirectional, i.e., the data flow in one direction.

 * A device can only send the data but cannot receive it or it can receive the data but cannot send the data.

 * Keyboard and Monitor are the examples of the simplex mode as a keyboard can only accept the data from the user and monitor can only be used to display the data on the screen.

 **2. Half-Duplex Mode:**

 ![Half duplex](https://static.javatpoint.com/tutorial/computer-network/images/transmission-modes-half-duplex-mode.png)

 * In this direction can be reversed, i.e., the station can transmit and receive the data but not at the same time.

 * The entire bandwidth of the communication channel is utilized in one direction at a time.

 * **Walkie-talkie** is an example of the Half-duplex mode

 **3. Full-Duplex Mode:**

 ![Full duplex](https://static.javatpoint.com/tutorial/computer-network/images/transmission-modes-full-duplex-mode.png)

 * The communication is bi-directional, i.e., the data flow in both the directions. Both the stations can send and receive the message simultaneously.

 * It is the fastest mode of communication between devices.

 * **Telephone network** is the most common example of full-duplex mode.
