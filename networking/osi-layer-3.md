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
Layer 2 → Frames
Layer 3 → Packets
Layer 4 → Segments
