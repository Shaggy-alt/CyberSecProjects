The goal of this project was to get familiar with setting up a Vulnerability scanner in home/personal environments and to properly set up said software to ensure no misconfiguration(s) has left you exposed.
-- 
|NOTE: This installation will be done on a kali machine.|


Step 1: Search for nessus
--

- Visit https://www.tenable.com/products/nessus/nessus-essentials \ search "nessus essentials" in your prefered search engine. You will need an valid email account to recieve an activation code. 
- Once the activation code has been recieved you will be able to install the most current version. Make sure you are installing the debian kali linux version. 
 
Step 2: Installing and running
--

- Hop onto your cmd line within kali and type:
~~~
sudo dpkg -i current-version.deb  
~~~
- Wait for install
- Run the nessus service to access via web.

~~~
sudo systemctl start nessusd.service
~~~

Step 3: Creating account
--

- Access the website with local host:

~~~
http://localhost:8834
~~~

- Accept the risk and continue. 
- Click on nessus essentials. 
- Input info into field or skip to just activation code.( Either works) 

Step 4: Scanning your network
--

- Create user account & psswrd. (please dont make it simple) And submit. Download & setup may take a while.
- Once inside click new scan from the top right corner of the website.(You will be shown many different vulnerabilities that can be used to scan your net) 
- Select basic scan, Give it a name you can remember.
- For selecting the amount of targets, you can only do 16. That should be fine for smaller subnets.
- You can also put a slash Ex:/24 to do entire ranges.
- You can also select a shecdule for how often you scan targets.
- Within credentials you can put a username and passoword to access certain machines remotely if preffered. 
- Plugins allow for additional options to be done along with the scan. 
- Within discovery you can select what ports are scanned.
- Click save when ready to scan.

Step 5: Run the scan
--

- Click the triangle to run the scan if its not scheduled. 

Said instructions found here:
--
https://www.youtube.com/watch?v=_RA69m_45qg&ab_channel=TheJoyofHacking

