# Wireshark
Wireshark notes.
# Filters
##### As a cyber security professional what filter can I use in wireshark to see all traffic going and coming from a particular IP address?
```
Use the following filter in Wireshark to see all traffic going to and coming from a particular IP address:
ip.addr == x.x.x.x
This filter will display all packets that have either the source or the destination IP address equal to the specified address.
If you only want to see packets that have the specified IP address as the source or the destination, you can use the following filters:
To see all packets with the specified IP address as the source:
ip.src == x.x.x.x
To see all packets with the specified IP address as the destination:
ip.dst == x.x.x.x
```
##### Port
```
ip.dst == IP && tcp.port == 12345
```
