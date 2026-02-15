# Layer 4 - Transport

The Transport Layer is responsible for end-to-end communication between applications on different devices.
While Layer 3 ensures packets reach the correct device, Layer 4 ensures data reaches the correct application process.

## Role and Purposes

Layer 4 provides:

  - Process-to-process delivery

  - Segmentation and reassembly

  - Port addressing

  - Flow control

  - Error control

  - Connection management

> It ensures data is delivered reliably or efficiently, depending on the protocol used.

## Data Unit

  - Layer 4 data unit = Segment (TCP)

  - Sometimes referred to as Datagram (UDP)

> Encapsulation flow: Application → Segment → Packet → Frame → Bits

## Port Addressing
Ports identify specific applications running on a device.
