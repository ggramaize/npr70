# New Packet Radio

Firmware for NPR-70 modems

## Authors
Original source code has been developed by F4HDK and it includes contributions from Edouard Lafargue (SNMP Support, settings refactoring for readability, and memory usage reduction).

# Known issues

  * Improper bridging behaviour: the original source code made strange implications regarding the topology of a network, which impedes using anything beyond IPv4, and making the modems non transparent to routed trafic (fix currently in WIP).
  * Telnet requests to a modem are not handled if the request comes from the radio interface. So far the management socket is bound to the Ethernet device.

