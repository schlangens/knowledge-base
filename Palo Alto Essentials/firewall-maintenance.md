[ <-- Back to Management Access](https://github.com/schlangens/knowledge-base/blob/main/Palo%20Alto%20Essentials/management-access.md)
# Configuration Files
- Running Configuration
    - Current Configuration enforced in the Data Plane
        - Controls the firewall's behavior
    - Saved to `running-config.xml`

- Candidate Configuration
    - Temporary configuration stored in the memory in the Control Plane
    - Saved as either default `snapshot.xml` or a custom XML file
    - Saving candidate configuration does not activate changes
        - Requires a commit
            - Turns Candidate configuration into running configuration

- Firewall configurations are managed using several options
    - Revert to last save configuration
        - Replaces current candidate configuration settings with a save candidate configuration file
    - Revert to running Configuration
        - Replaces current candidate configuration settings with the current running configuration
    - Load
        - Overwrites the current candidate configuration with a config file
    - Export
        - Exports a current/running configuration file as an XML (backups)
    - Import, Save

# Dynamic Updates
- Keep the system up-to-date with latest threats, applications & more
    - AntiVirus
        - Including WildFire signatures
    - Applications, Applications & Threats
    - GlobalProtect Data File
        - Host information profile (HIP) data
    - GlobalProtect Clientless VPN
        - Enables clientless VPN access to common web applications from the GlobalProtect portal
    - PAN-DB URL Filtering

# Software Updates
- Used for scheduled PAN-OS code updates
    - Require a system reboot
    - Software can be downloaded manually or over the Management interface

[Next Step --> Firewall Basic Settings](#)  