# DHCP SPOOFING AND SNOOPING

### DHCP SNOOFING is Attack the hacker make his device DHCP server using any tools , and make deafult gateway his own ip address



### To Solve DHCP Spoofing we use DHCP Snooping (all configuraion on switch) allowed only one port give DHCP IP

## DHCP SNOOPING Configuration on Switch :

```
ip dhcp snooping
ip dhcp snooping information option
ip dhcp snooping vlan 1

int f0/1
ip dhcp snooping trust

```

<div>
<img src="https://github.com/Mohamed-Abdelwahed/Networking_Start/assets/86673523/28be2723-4c34-4cf6-975f-99f0bb4fbb3c"  alt="DHCP Spoofing problem and its solve using Snooping(allowed switch port)" />
</div>


## Youtube Learn : 
### [DHCP Spoofing](https://youtu.be/DTmZkmqrUjI?si=5oe-jah--AG21mo3) - ENG: Waleed Saad El-Din