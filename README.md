<img width="847" height="692" alt="592203591-83454e09-7379-4548-9f21-f37b42b20032" src="https://github.com/user-attachments/assets/04226558-5743-438f-a8ad-68ae805e41f2" /># ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

<img width="750" height="603" alt="592202512-b3afe3ae-91af-4739-adcd-99ec40a42898" src="https://github.com/user-attachments/assets/0ea02232-bed6-4361-893b-eebd74a1627e" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="847" height="692" alt="592203591-83454e09-7379-4548-9f21-f37b42b20032" src="https://github.com/user-attachments/assets/64b23c3e-de08-4042-a392-215eb3ed729f" />

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="1027" height="616" alt="592241189-408469b5-11fd-480a-a32f-1f319a85fe2d" src="https://github.com/user-attachments/assets/30daa9b0-80a4-4f5c-89ea-3e3902f55037" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="322" height="122" alt="592240461-a90d8c63-8205-441e-9a7e-ab08da87e268" src="https://github.com/user-attachments/assets/0b372e27-200f-471a-ba2e-8f0a45d0588f" />

Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1917" height="996" alt="592239886-75789902-8baf-4f27-bba1-8745a179bf8c" src="https://github.com/user-attachments/assets/ff0d8647-fb5b-4d67-93ca-28e33244bb8a" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
