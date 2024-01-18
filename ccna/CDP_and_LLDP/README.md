# CDP / LLDP 
---
### CDP  ==> Cisco Discovery Protocol
### LLDP ==> Link Layer Dicscovery Protocol 


---

#### CDP and LLDP :
###### use to now neibours connected to switch , like Routers , Switches , IP phone ,   (not computers ).


## CDP  : 
###### is Cisco Proprietary , Enable by Deafult on Cisco Switches 
## LLDP : 
###### is Open Statndered desabled by Deafualt .

---
##### Important Command  :

###### Enable LLDP : 

```
config t

lldp run
```

###### show neibours (Devices connected to switch) :

```
show lldp ne

show cdp ne
```

###### Disabled : 

```
no cdp run

no lldp run
```


###### Enable CDP : 

```
config t

cdp run


int range f0/1-24
cdp enable
```

---

<div>
<img src="https://github.com/Mohamed-Abdelwahed/Networking_Start/assets/86673523/09ef9115-62e7-4517-b901-8d4dce291dbe"  alt="CISCO Discovery Protocol and Link Layer Discovery Protocoal"/>
</div>

---



#### [CDP/LLDP](https://youtu.be/p5Z0xcJQArY?si=iap_PdeILWdqGVKJ) - Eng: Waleed Saad El-Din
