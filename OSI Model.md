# The OSI Networking Model

- Each layer of the OSI model has a specific function

### Physical Layer (Layer 1)
- Think physical characteristics
- Defines things like voltage, frequency, speed and bandwidth
  - **Hardware**
    - Cables
    - Connectors
    - Cable pinouts
  - **Topology**
    - Ring
    - Mesh
    - Star
    - Bus
    - Hybrid

- **Protocols and Technologies**
  - USB
  - Ethernet
  - DSL
  - ISDN
  - Leased Lines (T1 and T3)
  - GSM
  - SONET

### Data Link Layer (Layer 2)
- Responsible for getting data to the physical layer
- Other responsibilities
  - Error detection
  - Error Correction
  - Hardware Addressing (MAC Addresses)
- Layer 2 PDU is called a *Frame*
- **Sublayers**
  - **Media Access Control (MAC) Layer**
    - MAC address defined at this layer
    - MAC address burned into each NIC
    - Controls access to network media
  - **Logical Link Control (LLC) Layer**
    - Handles error and flow control

- **Protocols and Technologies**
  - High-Level Data Link Control (HDLC)
  - Layer 2 Tunneling Protocol (L2TP)
  - Point-to-Point Tunneling Protocol (PPTP)
  - Spanning Tree Protocol (STP)
  - virtual LANs (VLANs)

### Network Layer (Layer 3)
- Main responsibility of this layer is *routing* - passing data from one network to another
- *Routing Protocols* live in this layer
  - software component that do *route selection*, think picking the best path for the data to get from one network to another
  - Routes can be set either statically or dynamically
  - Use IP addresses instead of MAC Addresses
- Layer 3 PDU is called a *packet*
- **Dynamic Routing Protocols**
  - *Routing Information Protocol (RIP)*
  - *Open Shortest Path First (OSPF)*

- **Network Layer Protocols**
  - Internet Protocol (IP)
  - Address Resolution Protocol (ARP)
  - Reverse Address Resolution Protocol (RARP)
  - Asynchronous Transfer Mode (ATM)
  - Intermediate System to Intermediate System (IS-IS)
  - IP Security (IPSec)
  - Internet Control Message Protocol (ICMP)
  - Multiprotocol Label Switching (MPLS)

### Transport Layer (Layer 4)
- Main function is to transport data between network devices
- Functions:
  - Error checking: checks data is correctly send or received
  - Service Addressing: checks data is passed to the right service at the upper layers
  - Segmentation: data is broken down into chunks of manageable sizes

- **Protocols**
  - User Datagram Protocol (UDP)
  - Transmission Control Protocol (TCP)

- **Data Flow Control**
  - Controls how the receiving device can accept data transmissions
    - Buffering: data is temporarily stored and waits for the destination device to become available. Can cause problems if the sending device transmits data faster than the receiver device can handle.
    - Windowing: Data is sent in groups of segments that only need one acknowledgment. The "size of the window" is defined when the session between two devices is established.

### Session Layer (Layer 5)
- Handles the managing and controlling of the synchronization of data between applications on two devices
- Establishes, maintains and breaks sessions
- Handles encryption - scrambling of data

- **Protocols**
  - NetBIOS
  - Network File System (NFS)
  - Server Message Block (SMB)
  - Transport Layer Security (TLS)

### Presentation Layer (Layer 6)
- Main function is to convert data received from the application layer into another format
- **Common Data Formats**
  - **Graphics files**
    - JPEG
    - TIFF
    - GIF
  - **Text and data**
    - ASCII
    - EBCDIC
  - **Sound/video**
    - MPEG
    - MP3
    - MIDI

### Application Layer (Layer 7)
- Takes requests and data from users and pass them to the lower layers of the OSI model
- Defines processes that let applications use network services.
- **Protocols**
  - Secure Shell (SSH)
  - BGP
  - DHCP
  - NTP
  - SMTP
  - HTTP
  - HTTPS
  - IMAP
  - POP3

#### Mapping Devices to the OSI Model
| Device | OSI Layer |
|--------|-----------|
|Hub     | Physical Layer (Layer 1)|
|Wireless Bridge | Data Link (Layer 2)|
|Switch | Data Link (Layer 2) or Network (Layer 3)|
|Router | Network (Layer 3) |
|NIC    | Data Link (Layer 2) |
|Access Point (AP) | Data Link (Layer 2) |


## Questions

1) At which OSI layer does an AP operate? 

    A. Network  
    B. Physical  
    C. Data Link  
    D. Session  

2) What are the sub-layers of the data link layer? 

    A. MAC  
    B. LCL  
    C. Session  
    D. LLC  

3) At which layers does a switch operate in? 

    A. Layer 1  
    B. Layer 2  
    C. Layer 3  
    D. Layer 4  

4) Which OSI layer is responsible for building connections between devices? 

    A. Network  
    B. Transport  
    C. Session  
    D. Data Link  

5) What happens when data moves from upper layers to lower layers of the OSI model on a system? 

    A. The header and trailer are stripped off (decapsulation)  
    B. Data is sent in groups of segments that need two acknowledgments  
    C. Data moves from the physical layer to application layer  
    D. Data is encapsulated with a header at the beginning and a trailer at the end