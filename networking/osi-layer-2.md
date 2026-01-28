# Layer 2: Data Link

The Data Link Layer is responsible for reliable communication between devices on the same local network. It takes raw bits from the Physical Layer and organizes them into frames, using MAC addresses to identify source and destination devices.

Layer 2 also controls how devices access the network medium and detects transmission errors. Its local, trust-based operation makes it critical for both network performance and internal network security.

## Role and Purpose of Layer 2

The Data Link Layer ensures reliable data transfer between directly connected devices on the same network segment. Its main purpose is to provide a structured and controlled way for devices to exchange data over a shared physical medium.

**Key roles include:**

  - Converting raw bits from Layer 1 into organized frames

  - Using MAC addresses to identify source and destination devices

  - Managing access to the transmission medium to avoid collisions

  - Detecting transmission errors before data moves to higher layers

  - Acting as a bridge between physical transmission (Layer 1) and logical networking (Layer 3)

> Layer 2 focuses strictly on local delivery, not end-to-end communication.

## Framing and Data Units
Framing is the process of encapsulating network-layer data into frames for transmission across a local network.

Data Units by Layer:

  - Layer 1 → Bits

  - Layer 2 → Frames

  - Layer 3 → Packets

**Why framing is important:**

  - Defines clear start and end points for data transmission

  - Enables error detection using checksums (e.g., CRC)

  - Allows switches to process and forward data efficiently

  - Ensures synchronization between sending and receiving devices

**A typical Layer 2 frame contains:**

  - Header (source and destination MAC addresses)

  - Payload (encapsulated Layer 3 packet)

  - Trailer (error-checking information)

> Framing makes raw transmission structured, reliable, and manageable at the local network level.

## Media Access Control (`MAC`) Addressing Basics
<!-- include what was learnt from THM about the mac address format (12 4bits digits, having two parts: 6 digits for the production company and 6 digits for the user) -->
`MAC` addressing provides unique identification for devices on a local network. Each network interface is assigned a 48-bit hardware address, typically written in hexadecimal.

**Key points:**

  - Operates only within the local network segment

  - Used by switches to forward frames to the correct device

  - Types of MAC addresses:

    - Unicast – one-to-one communication

    - Broadcast – one-to-all communication

    - Multicast – one-to-many communication

> MAC addressing enables precise local delivery, unlike IP addressing which handles network-to-network communication.

## Unicast, Broadcast, and Multicast
Layer 2 supports different communication patterns based on destination MAC addresses.

  - **Unicast:** Data is sent from one device to a single specific device.

  - **Broadcast:** Data is sent to all devices on the local network.

  - **Multicast:** Data is sent to a selected group of devices that have joined a multicast group.

> These modes determine how frames are distributed across a network and directly impact network efficiency.
