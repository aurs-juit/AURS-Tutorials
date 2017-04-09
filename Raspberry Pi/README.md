# Raspberrry Pi3 Tutorial
### Connecting your Raspberry Pi to Linux using ssh.<br>

***

We will use Raspberry using SSH Client mainly. Raspberry Pi 3 comes with inbuilt wifi.<br>
<br>
For ease of access, we will connect R pi using anny wifi hotspot.We will initially need an ethernet cable to setup Hotspot Pi.<br>
Go to the Network Connnection -> Edit connection.<br>
Create a new network connection, select mode=Ethernet. Set the IPV4 setting to "shared to computers"<br>
<br>
Connect your Raspberry Pi to PC using ethernet cable and power it up. Go to the terminal.<br>
access your network configuration files with command: cat /var/lib/misc/dnsmasq.leases<br>
<br>
You will get a local adress of your Raspberry Pi with ip 10.XX.X.X. Use ssh to connect the device using terminal.<br>
<br>
For this use the command, `ssh pi@10.XX.X.X` //Default username is pi<br> 
You will be asked for the password, enter your password. Default password is raspberry.<br>

For accessing in GUI mode, Go to any remote desktop in case of Ubuntu use Remmina. Log in using RDP with your ip.<br>
Now in our GUI mode connect your hotspot, actually you are making your pi to remember it.<br>
Once you have set up your pi, you can ssh into it just by powering up your Hotspot and Pi. Enjoy!
![Terminal Login](/git.png)
