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