[ <-- Back to Firewall Basic Settings](https://github.com/schlangens/knowledge-base/blob/main/Palo%20Alto%20Essentials/firewall-basic-settings.md)
# Data Interfaces
- PAN-OS supports several types of interfaces and can opertate in multiple deployments
    - Tap, Virtual Wire, Layer 2, Layer 3

- Tap
    - Works on a copy of the network traffic
        - Port mirroring (SPAIN)
    - Deployed for logging & visibility

- Virtual Wire
    - For inline deployments
        - Traffic control, decryption, QoS, etc
    - A logical connection of two ports
        - No L2/L3 addresses
            - No management capabilities
            - Easy to integrate
    - Allows for sub-interfaces
- Virtual wire interfaces must be attached to a Virtual Wire Object
    - Default virtual wire ports may need to be removed

- Layer 2
    - Used for L2 switching
        - Inline
    - Require a VLAN object
    - Supports sub-interfaces

- Layer 3
    - Used for L3 routing (IPv4, IPv6)
        - INline
    - Require a virtual router
    - Supports sub-interfaces & management

# Other Interfaces
- Loopback
    - Virtual L3 ports internal to the firewall
    - Used in many scenarios
        - Routing, DNS Sinkholes
- Tunnel
    - Virtual interface used for VPN representation
    
[Next Step --> Firewall Initialization](https://github.com/schlangens/knowledge-base/blob/main/Palo%20Alto%20Essentials/firewall-initialization.md)  
