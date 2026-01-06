# Networking Fundamentals

An introductory overview of fundamental networking concepts, explaining how data is transmitted, addressed, and routed within computer networks.

## What is a Network?
Networks are connections between entities, found in many aspects of life, e.g., friend circles or family relationships.

In computing, however, a network is the connection of technological devices that allows them to share and exchange information, data and resources.

## Types of Networks

Computer networks are categorized based on their size, scope, and intended use, and each type supports communication and resource sharing in various environments.

**1. Personal Area Network `PAN`:** A small network for connecting devices around a single person, typically within a few meters.
> Example: Connecting a smartphone to a Bluetooth headset.


**2. Local Area Network `LAN`:** A network covering a small area like a home, office, or building, allowing devices to share resources.
  - A Wireless Local Area Network `WLAN` is a type of LAN that uses wireless connections (Wi-Fi) instead of cables.
> Example: Computers in an office connected to the same router `LAN` or accessing the office Wi-Fi `WLAN`.

**3. Campus Area Network `CAN`:** A network that connects multiple LANs within a limited area like a university or corporate campus.
> Example: Network connecting all departments in a university campus.

**4. Metropolitan Area Network `MAN`:** A network that spans a city or town, connecting multiple LANs.
> Example: Network linking branch offices of a city-based bank.

**5. Wide Area Network `WAN`:** A large network that spans cities, countries, or even globally, often using leased telecommunication lines.
> Example: The internet connecting users worldwide.

![Network scope diagram](../assets/types-of-networks.png)

## Types of Network Topologies

Network topology refers to the physical or logical arrangement of devices (nodes) and connections (links) in a network. The common types include:

**1. Bus Topology:** All devices share a single communication line.
> Example: Old Ethernet networks using a coaxial cable.

**2. Star Topology:** All devices connect to a central hub or switch.
> Example: Modern office `LANs` with a central switch.

**3. Ring Topology:** Devices are connected in a circular manner, data travels in one or both directions.
> Example: Token Ring networks in some legacy systems.

**4. Mesh Topology:** Every device is connected to every other device.
> Example: Some WAN backbone networks for reliability.

**5. Tree Topology:** Hierarchical arrangement of star networks connected together.
> Example: University networks connecting departments and buildings.

**6. Hybrid Topology:** Combination of two or more topologies.
> Example: Large corporate networks combining star and mesh layouts.

![Network topologies diagram](../assets/network-topologies.png)

## Network Models

A network model is a layered framework that explains how data is transmitted and communicated between devices on a network.

Network models describe how network communication is structured and standardized using layered architectures. The two primary network models are:

**1. Open System Interconnection `OSI` Model:** A conceptual seven-layer model used to understand, design, and troubleshoot network communication. An overview of each `OSI` Layer:
  - **Layer 1 `Physical`:** Transmits raw bits over physical media.
    > Example: Network cables and electrical signals.
    
  - **Layer 2 `Data Link`:** Manages physical addressing and error detection.
    > Example: Ethernet frames using MAC addresses.
    
  - **Layer 3 `Network`:** Handles logical addressing and routing.
    > Example: `IP` routing packets across networks.
    
  - **Layer 4 `Transport`:** Ensures reliable or fast data delivery.
    > Example: `TCP` for reliable transmission, `UDP` for fast streaming.
    
  - **Layer 5 `Session`:** Manages sessions and connections between devices.
    > Example: Maintaining a login session.
    
  - **Layer 6 `Presentation`:** Handles data formatting, encryption, and compression.
    > Example: `SSL/TLS` encrypting data.
    
  - **Layer 7 `Application`:** Provides network services directly to user applications.
    > Example: Web browsers using `HTTP`.

![OSI layer model](../assets/osi-model.png)

**2. Transmission Control Protocol / Internet Protocol `TCP/IP` Model:** A practical four-layer model used in real-world networks, especially the Internet. Each `TCP/IP` layers are listed below:
  - **Network Access Layer:** Manages physical transmission and local network delivery.
    > Example: Ethernet and Wi-Fi.
    
  - **Internet Layer:** Handles logical addressing and routing across networks.
    > Example: `IP` and `ICMP`.
    
  - **Transport Layer:** Manages end-to-end communication and reliability.
    > Example: `TCP` and `UDP`.
    
  - **Application Layer:** Combines `OSI` application, presentation, and session layers; provides network services to applications.
    > Example: `HTTP`, `FTP`, `SMTP`.

## Data Transmisson
Data transmission refers to the process of sending data from one device to another over a communication medium, following defined rules (protocols) to ensure accurate and reliable delivery.

## Classification of Data Transmission
**1. Based on Direction of Data Flow:**
  - **Simplex:**
  - **Half-Duplex:**
  - **Full-Duplex:**

**2. Based on Signal Type:**
  - **Analog Transmission:**
  - **Digital Transmissionn:**

**3. Based on Data Delivery Method**
