[ <-- Back to KB](https://schlangens.github.io/knowledge-base/)
# Management Access
+ Web Interface
    - Local
    - Centralized
        - Panorama
    = Panorama is recommended for networks with 6+ firewalls
        - Reduces complexity and administration overhead
        - Aggregates data from all managed devices
- CLI
    - Console, SSH, Telnet
- API
    - XML
    - REST
# Management Port
- Special interface designed for administration
    - Part of the Control Plane
    - Preconfigured with `192.168.1.1/24` for HTTPS
        - admin//admin
- Data Ports also support management functions
    - Management Profiles
    - Service Routes
# Service Routes
- Required to provided access to external services through data ports
    - Device > Setup > Services > Service Route Configuration > Customize

# Firewall CLI
- Palo Alto Firewalls use two CLI modes
    - Operational
        - Basic networking/system commands & verification
            - `ping` , `traceroute` , `show` , `debug`
    - Configuration
        - Accessible via `configure`       
- CLI Enhancements
    - Use `find` to figure out the command syntax
    - Use `?` to get help on the command options and parameters
    - Use the `TAB` key for command auto-completion
    Use the `|` symbol along with `match` or `except` for output filtering        