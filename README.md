# nmap_wireshark_scan-Task1-


First I opened the terminal in kali kinux,then wrote the command 
ifconfig => to capture the avaliable interface that 

I got the ip address with 192.xx.xx.xx (Hiding it for security purpose)

Then I performed the SCAN with the command 
nmap -sn 192.x.x.x (This is a simple “ping scan” that just finds active devices.)

Then to check the open ports 
nmap -sS 192.x.x.x/24

This gave me the data of the all the devices connected to my network like the open ports the devie name of some devices also the mac address of the devices


Then I opened the wireshark that was used to capture the network packets as the document file with the commands and the screenshots is uploaded
