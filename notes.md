```
interface mgt0 vlan 18
interface mgt0 native-vlan 18
interface mgt0 ip 10.0.8.82 255.255.255.0
ip route net 0.0.0.0 0.0.0.0 gateway 10.0.8.1
no interface mgt0 dhcp client
dns server-ip 10.0.20.4
dns server-ip 10.0.20.5 second
dns domain-name palermos.local
capwap client server name ia-gcp-cws-6.extremecloudiq.com
interface eth0 native-vlan 18
interface mgt0 vlan 18
```
