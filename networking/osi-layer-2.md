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