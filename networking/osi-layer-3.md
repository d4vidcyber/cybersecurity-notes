# Layer 3: Network

The Network Layer is responsible for moving data across different networks. Unlike Layer 2, which handles local delivery, Layer 3 enables end-to-end communication between devices on separate networks by using logical addressing and routing.

> It decides where data should go next, not how it is physically transmitted.

## Role and Purpose of Layer 3

The primary role of Layer 3 is to ensure successful delivery of data from source to destination across multiple networks.

**Key purposes include:**

  - Providing logical addressing independent of hardware

  - Determining the best path for data to travel

  - Forwarding packets between networks

  - Managing network-to-network communication

  - Supporting scalability of large networks (e.g., the internet)

> Layer 3 focuses on path selection and forwarding, not local delivery

## Logical Addressing `IP` Addressing

Logical addressing allows devices to be identified across different networks using IP addresses.

**Key points:**

  - IP addresses are software-assigned, unlike MAC addresses

  - They identify both the network and the host

  - Two main versions:

    - IPv4 – 32-bit address (e.g., 192.168.1.1)

    - IPv6 – 128-bit address (e.g., 2001:db8::1)

## IPv4 and IPv6

IP exists in two main versions to support logical addressing at Layer 3.
<!-- Add context from thm notes -->
**IPv4:**

  - 32-bit address space

  - Written in dotted-decimal format (e.g., 192.168.1.1)

  - Limited address availability

  - Commonly used with NAT

**IPv6:**

  - 128-bit address space

  - Written in hexadecimal (e.g., 2001:db8::1)

  - Vast address capacity

  - Designed to replace IPv4

  - Supports simpler header structure and better scalability

> Both versions serve the same role: identifying devices and  networks for routing.

## Packets and Data Units

At Layer 3, data is handled as packets.

**Data units by layer:**

  - Layer 2 → Frames

  - Layer 3 → Packets

  - Layer 4 → Segments

**Packet characteristics:**

  - Contains source and destination IP addresses

  - Encapsulates Layer 4 data

  - Can be fragmented to fit different network sizes

  - Independent of the physical transmission medium

> Packets allow data to move across multiple networks.

## Routing Concepts

Routing is the process of selecting the best path for packets to travel from source to destination

**Key concepts:**

  - Routers make forwarding decisions based on destination IP address

  - Multiple paths may exist between networks

  - Path selection is influenced by metrics such as:

    - Hop count

    - Bandwidth

    - Delay

> Routing enables scalable communication beyond local networks.

## Routing Tables and Metrics

Routers use routing tables to decide where to forward packets.

Routing table contains:

  - Destination network

  - Next-hop address

  - Exit interface

  - Metric (cost)

Common routing metrics:

  - Hop count

  - Bandwidth

  - Delay

  - Reliability

> Lower metric values typically indicate preferred paths.

## Routers and Layer 3 Devices

Layer 3 devices forward packets between different networks using IP addresses.

**Router**

  - Core Layer 3 device

  - Connects multiple networks

  - Maintains routing tables

  - Performs packet forwarding

**Layer 3 Switch**

  - Combines switching and routing

  - Faster routing within LANs

  - Common in enterprise networks

> These devices enable inter-network communication.

## Common Layer 3 Protocols
Layer 3 relies on protocols to support addressing and routing.

Key protocols include:

