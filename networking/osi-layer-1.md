# Layer 1: Physical Link

## Introduction

OSI Layer 1, known as the Physical Layer, is the lowest layer of the OSI model. It provides the foundation for network communication by defining how raw binary data (1s and 0s) is physically transmitted between devices. Without this layer, no higher-layer communication is possible

## Role of the Physical Layer in the OSI Model

The Physical Layer’s role is to move bits from one device to another across a physical medium. It does not interpret data, manage communication sessions, or handle addressing. Instead, it ensures that a physical connection exists and that bits can be reliably transmitted over it.

**Primary functions:**

  - Establishing and terminating physical connections

  - Defining electrical, optical, and radio characteristics

  - Ensuring synchronization between sender and receiver

## Bit Transmission and Signaling

At Layer 1, data is transmitted as signals that represent binary digits.

<!- add detailed definition / explanation ->

**Signaling types:**

<!- add why there are types ->

  - Electrical signals (voltage changes in copper cables)

  - Optical signals (light pulses in fiber optics)

  - Wireless signals (radio waves in Wi-Fi and cellular networks)

**Key concepts of Signalling:**

  - Bits: Only 0s and 1s are handled

  - Signal strength and timing affect transmission quality

  - Noise and attenuation can distort signals

> Layer 1 defines how a bit is represented, not what the bit means.

## Transmission Media

Transmission media refers to the path through which signals travel. These are classified into two main types:

**Guided Media (Wired)**

They use physical cables to direct data signals along a specific, tangible path, providing controlled and reliable communication for networks and telecommunications.

The main types of Guided media are:

  - **Twisted Pair (UTP/STP):** Common in Ethernet networks, cost-effective, limited distance

  - **Coaxial Cable:** Better shielding, used in cable broadband

  - **Fiber Optic:** Uses light, high speed, long distance, immune to electromagnetic interference

**Unguided Media (Wireless)**

This meadia transmits data as electromagnetic waves through free space (vacuum) without physical cables, offering flexibility and mobility for communication.

The main types of Unguided media are: 

  - **Radio Waves:** Used in Wi-Fi and Bluetooth

  - **Microwaves:** Used in satellite and long-distance wireless links

  - **Infrared:** Short-range, line-of-sight communication

> Each medium has trade-offs in speed, distance, cost, and resistance to interference.

### Difference between Guided and Unguided media

| **Feature** | **Guided Media**| **Unguided Media**|
|:--:|:-|:-|
