[ <-- Back to Firewall Interfaces](https://github.com/schlangens/knowledge-base/blob/main/Palo%20Alto%20Essentials/firewall-interfaces.md)
# Virtual Router
- Enables Routing functions
    - Interfaces
    - RIB
        - Control Plane
    - FIB
        - Data Plane
- Supported Routing Technologies
    - Static Routes
    - OSPF, OSPFv3, BGP, RIP
    - PIM-SM, PIM-ASM, PIM-SSM, IGMP version 1/2/3

# Security Zone
- A group of interfaces representing a segment controlled by the firewall
    - LAN1, Internet
- A firewall interface can belong to only one zone
    - Interface Type & Zone Type must match
    - Zone- unassigned interface does not process traffic
- Zones affects the data traffic
    - Intra-zone
    - Inter-zone

[Next Step --> Palo Alto Firewall Policies](#)
