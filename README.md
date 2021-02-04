# deploying-web-application-on-compute-engine-instance

Steps to deploy web application on compute engine instance using deployment manager
1)	Enable deployment manager API and Compute engine API

2)	Create compute engine instance
i)	Give name to vm instance  (Ex: tejaswi-instance)
ii)	Select region and zone where to deploy your application (Ex:                                             region – us-central1, zone- us-central1-a)
iii)	Select machine configuration  (Ex: series – f1-core , machine type – n1-standard-1(1vCPU,3.75 GB memory))
iv)	Select boot disk (Ex: Debain GNU/LINUX 10)
v)	Networking : create a VPC network and select your network here
vi)	Access Scope: Allow full access to all Cloud APIs
vii)	Firewall :  select Allow http traffic , Allow https traffic

3)	Create a firewall for your network

4)	Now  you can access your SSH window

5)	Open SSH, and install server (like nginx ) to run your application

6)	Add your code on to nginx server (nginx-debian.html)

7)	Click on external ip to view your application page on next page.
