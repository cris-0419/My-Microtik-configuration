# My-Microtik-configuration
![image](https://github.com/user-attachments/assets/03864394-f9f2-4391-8720-9a97ccbfbd17)

In this network we configured IPv4, VRRP, dhcp, VLAN, scripts in Mikrotik for redundancy in the entire network so that if only one router were to work the infrastructure would still remain functional, and a strong Firewall security:

1. disable unecesary ip service and package
2. chnage ssh port and set ssh strong crypto
3. configure port knocking
4. give access from your user just from your pc using your ip address and mac address
5. disable mac address discovery from all interfaces and block bandwith test packets
6. drop all the invalid packets
7. prevent brute force attack on ssh
8. protect from ping flood
9. block bogons ip address
10. block nmap scaning
11. prevent ICMP smurf attack
12. Block syn flood and DDOS (slow down the attack)
13. Preventing UDP flood attack
14. MNDP Attack prevention
15. hide your ip address from traceroute
