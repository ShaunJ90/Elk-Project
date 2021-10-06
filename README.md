# Elk-Project
![ELK Network](ELK%20Network.png)

This network allows me to access my jump box from my public IP address specified in the network rules. Port 22 is allowed from my public IP specifically so that I can SSH into my jump box. The jump box is used as an administration point so that I can access both of my web servers in addition to my ELK server. There is a peering network setup in Azure to allow the 10.1.0.0/24 and 10.3.0.0/24 to pass traffic. This allows me to access the Elk server via the jump box. I've also enabled web traffic to the ELK server from my public IP for the web interface. 
|Server Name|Server IP|Operating System|
|:----------|---------|----------------|
|Web Server1|
|Web Server2|
|Elk VM|
