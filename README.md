# RTI-PC
Real Time Inventory - PC

# About :

RTI-PC is a free opensource management tool, which allows you to administer and identify your Windows 10 and server, without dependency or installation.
RTI-PC gives you a control over necessary aspects of your Windows infrastructure to identify and fix problems also inventory you machines. 
It is particularly useful for troubleshooting servers, workstations on private networks that are not connected to the Internet.

RTI-PC can help to :
-get the software information on remote computer
-check memeory usage, proc, free ram
-get information like (current user, Bios version, OS version, total ram size, IP, @mac, Serialnumber)
-Avaible and Free hard disk drive 
-get remontely logs to check errors and warning

Pls use the exe version for best reactivity

# PREREQUISITE :

-Win10 on workgroup or domain
-enable Winrm if you want connect to remote Win10 machine

# How to use :

-just enter the name of computer then click Ok

# Versions : 

-the tools exist on exe for two version basic or with proc pourcent, the exist also on Ps1 script
you can add what you want to get as informations on line : 
-Favor use the Microsoft Store Version 

# Troubleshoting :

-if you can connect to the remote machine, pls try on Powershell winrm connection with this command : enter-pssession "yourcomputername" 
if dont work, enable winrm, then retry with the tool, because it is based on Winrm service

