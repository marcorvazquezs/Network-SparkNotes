# Network Links and Concepts

### DSL

- Internet access method that uses a phone line to provide high-speed access
- Inexpensive
- **DSL Flavors**
  - **Asymmetric Digital Subscriber Line (ADSL)**
    - High data rate in only one direction (fast downloads / slow uploads)
  - **Symmetric DSL (SDSL)**
    - Offers same speeds for uploads and downloads
  - **High-rate Digital Subscriber Line (HDSL)**
    - Provides a bidirectional high-data-rate service that need high data rates (think videoconferencing)
  - **ISDN DSL**
    - Symmetric type of DSL often used when SDSL and ADSL are not available
  - **Rate-adaptive DSL (RADSL)**
    - Variation on ADSL that can change transmission speeds based on signal quality.
  - **Very high-bit-rate DSL (VHDSL)**
    - Asymmetric version of DSL
    - Can get up to 10 Mbps, fastest form of DSL
    - Uses fiber-optic cabling
  - **High-bit-rate DSL (HDSL)**
    - A symmetric technology that gives identical transmission rates in both directions.
    
    | DSL Variation | Upload Speed | Download Speed |
    | ------------- | -------------| -------------- |
    | ADSL | 1 Mbps | 3 Mbps | 
    | ADSL2 | 1.3 Mbps | 12 Mbps | 
    | ADSL2+ | 1.4 Mbps | 24 Mbps |
    | SDSL | 1.5 Mbps | 1.5 Mbps |
    | IDSL | 144 Kbps | 144 Kbps |
    | RADSL | 1 Mbps | 7 Mbps | 
    | VHDSL | 1.6 Mbps | 13 Mbps |
    |HDSL | 768 Kbps | 768 Kbps |

### Cable Broadband
- Uses a cable modem
- One big con is that you share the available bandwidth with everyone else in your cable area

### Leased Lines
- High speed digital lines that can be leased from telephone companies
- Give you an always-open, always available connection between you and who you choose to connect to
- Support both voice and data transmissions
- An expensive WAN option
- Called E-carriers in Europe and J-carriers in Japan

| Name | Transmission Speed |
|------|--------------------|
|T1    |1.544 Mbps          |
|T1C   |3.152 Mbps          |
|T2    |6.312 Mbps          |
|T3    |44.726 Mbps         |
|T4    |274.176 Mbps        |

### Metro-Optical
- Also known as MONs
- Optical networks that can cover several hundred kilometers and server metropolitan areas

## Termination Points
- **Demarc**
  - The connection point between the ISP and the customer network
  - Marks the boundary of what we are responsible for versus what the ISP is responsible for
  - The *smart jack* or *network interface device (NID)* is the hardware used at the demarcation point and performs the following functions:
    - Loopback feature (same as Ethernet loopback)
    - Signal amplification
    - Surge protection
    - Remote alarms

- **CSUs/DSUs**
  - Acts as a translator between the LAN and the WAN
  - Think of this as a digital modem that changes the signal from one digital format to another


## Questions

1) Which technology needs dial-up access?

    A. Fiber
    B. ISDN
    C. Packet Switching
    D. DMVPN

2) Which is an advantage of ISDN over a POTS network?

    A. ISDN is more reliable
    B. ISDN is cheaper
    C. ISDN is faster
    D. ISDN uses fixed length packets

3) What is the name of the gap between sending or requesting information and the time it takes to get a response?

    A. Echo
    B. Attenuation
    C. Bandwidth
    D. Latency

4) What is the usual speed of dial-up services?

    A. 1 Gbps
    B. 256 Kbps
    C. 144 Kbps
    D. 56 Kbps

5) Which is the device that acts a translator between the LAN and the WAN data format?

    A. SIP Trunk  
    B. PRI  
    C. MPLS  
    D. CSU/DSU  