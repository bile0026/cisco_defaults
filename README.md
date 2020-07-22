# cisco_defaults
Sets various default configuration items on cisco devices.

Sets these settings, modify for your environment:
* Creates a login banner
* Removes MOTD banner
* Sets NTP server and source interface
* Disables a list of services
    * http server
    * http secure-server
    * vtp
    * domain lookups
* Enables these services
    * SSH Version 2
    * SCP Server
