# RTI-PC
Real Time Inventory - PC

![rtipc](https://user-images.githubusercontent.com/49924401/119489651-2fb58c00-bd5c-11eb-9d94-fa852aada862.gif)

# About :

RTI-PC is a free opensource management tool, which allows you to administer and identify your Windows 10 and server, without dependency or installation.
RTI-PC gives you a control over necessary aspects of your Windows infrastructure to identify and fix problems also inventory you machines. 
It is particularly useful for troubleshooting servers, workstations on private networks that are not connected to the Internet.

RTI-PC can help to :
- get the software information on remote computer
- check memeory usage, proc, free ram
- get information like (current user, Bios version, OS version, total ram size, IP, @mac, Serialnumber)
- Avaible and Free hard disk drive 
- get remontely logs to check errors and warning

Pls use the exe version for best reactivity

# PREREQUISITE :

* Win10 on workgroup or domain
* if you want to manage a remote computer pls enable Winrm (by Gpo or with cmd.Exe : winrmqc ) 
link how to enable Winrm by GPO : https://www.mehdi-dakhama.com/post/enable-winrm-by-gpo

# How to use :

- just enter the name of computer then click Ok

# Versions : 

- The tools exist on exe for two version basic or with proc pourcent
- Exist also on Ps1 script (you can edit and add what you want to get as informations on line : 
- recommended to use the Microsoft Store Version 

![rti-1](https://user-images.githubusercontent.com/49924401/119490542-3e507300-bd5d-11eb-9c0c-930c35e973e6.PNG)
![rti-3](https://user-images.githubusercontent.com/49924401/119490550-401a3680-bd5d-11eb-8ab9-e55e4821040b.PNG)


# Troubleshoting :

-if you can connect to the remote machine, pls try on Powershell winrm connection with this command : enter-pssession "yourcomputername" 
if dont work, enable winrm, then retry with the tool, because it is based on Winrm service

