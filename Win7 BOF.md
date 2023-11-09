The goal of this project was to Set up legacy software in a contained environment as well as using an advanced technique (BOF) 
in order to gain a reverse shell and then priv. esc.

|DO NOT ATTEMPT IN PRODUCTION|

-You will need a copy .iso of win7 (the seas should have a copy).
-You will need immunity debugger installed as well as mail server installed. 
-You will need kali/parrot os to attack victim machine.

+++
|ASSEMBLY|
+++

---
Configure both machine's network to interface with each other while segmented from the outside world once properly set up (immunity debugger is installed).
!!!ENSURE WIN7 CANNOT TOUCH THE INTERNET!!! win7 has been discontinued and is full of security holes.
---

+++
|STEPS|
+++

-USE NMAP to discover what the ip address is for the victim machine 
OR Netdiscover. (NMAP provides more info)

_____________________________
CMD's:
nmap -sV -sC ip/prefix

sudo netdiscover -r ip/prefix
______________________________

-USE python2 to run a script in order to figure out the limit 














[Under Construction]




