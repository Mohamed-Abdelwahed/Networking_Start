#ETHER CHANNEL


###[1] Solve the Problem of slowing STP (Spanning Tree Protocol Cause)
###[2] Make a group of Cables  Like only (One Cable)
###[3] Redundancy


##Ether channel has two protocols :
####[1] ==> PAGP (Cisco Proprietary) has two modes (Desirable, Auto)

####[2] ==> LACP (Multi vendor) has two modes (Active , Passive)

Commands to switch on Ether Channel are like the below command :

```
int range f0/1-4
switchport mode trunk
channel-group 1 mode active
```

Troubleshooting Ether channel :

```
do show eth
do show eth sum
```

<div>
<img src="https://github.com/Mohamed-Abdelwahed/Networking_Start/assets/86673523/b036b055-4266-4691-b9e2-70c917391ad9"  alt="Ether channel image"/>
</div>




###Yotube Learnning : 
####[Ether Channel](https://youtu.be/z5qdEtY9paQ?si=lJQ-F5iEz-i_0gA2)- Eng:Waleed Saad El-Din








