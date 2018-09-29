# boss-ansible-role-dhcpd
ansible role to install and configure dhcp server


# Description

`bossjones.dhcpd` role can be used to configure an [ISC DHCP
Server](https://www.isc.org/downloads/dhcp/) as standalone or in a 2-host
failover configuration. Alternatively, you can configure an DHCP relay on
a host connected to multiple networks which will relay DHCP/BOOTP messages
to your DHCP server.

`dhcp-probe` script will be used to scan the network for unauthorized DHCP
servers and notify administrators if they are found.

# Inspiration

https://github.com/debops/ansible-dhcpd
