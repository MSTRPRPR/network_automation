# network_automation

A set of simple tools to speed up certain tasks on Cisco devices.

**ping.yml**

Pings a target IP address from a list of specified hosts.
Takes an IP address as an input and pings it from hosts specified in the playbook.

**mac.yml**

Searches for a target IP/MAC address inside the arp table on the specified hosts.
Takes a MAC or IP address as an input, searches for that in the hosts specified in the playbook and returns the result if the address was found.
