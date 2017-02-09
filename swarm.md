![](/dockericon.png)
#Setup
To initialise swarm on the master, run `docker swarm init --advertise-addr 10.0.12.3` , where 10.0.12.3 is the <master-ip> 
The output will be like `Swarm initialized: current node (xxdo1afkprfk2cxqye6h8kh5l) is now a manager.`
Then you will get a command to add the workers to this master

