# SNMP  / Syslog

### SNMP : 
###### Simple Network Management Protocol 

---

### Advandage (SNMP) : 
##### [1] Monitoring
##### [2] Management
##### [3] Open Standered
##### [4] Work on Layer 7

---

##### ==> On Real World you want to install program to using SNMP lik ( [PRTG](https://www.paessler.com/prtg/download) , [SOLARWinds](https://www.solarwinds.com/downloads)) , keep in mind it's paid Program .

---


##### There are 3 version of SNMP The Best is Version 3 beacause it using authintication but version 3 of SNMP not many devices support it , most supported is version 2 .

---


##### SNMP Enable : 

```
SNMP-Server Community cisco ro
```

###### cisco is a shared key you can use any word , ro is (Read only prefared) you can use rw (read and write) .

---

##### Syslog : 
+ like black box in plane .
+ Save all actions happen in device .
+ numbered actions from 0 to 8.
+ By Default debugging doesnot save , number (7).
+ By Default Syslog save in ram (not Recommendded).


###### Save in RAM : 
```
logging on
```

##### Save in outside device :
```
logging on 192.168.1.200
```


---
##### unfortionatly Packet tracer doesnot support most configuration of (SNMP) and (Syslog).

---

###### youtube learn :
###### [SNMP/Syslog](https://youtu.be/Qx88TOSvmBI?si=TOwGHfCeF6hPd8RU)- ENG: Walid Saad El-din


---