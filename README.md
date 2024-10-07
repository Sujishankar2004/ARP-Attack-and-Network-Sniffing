# ARP-Attack-and-Network-Sniffing
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
![Screenshot 2024-10-07 085837](https://github.com/user-attachments/assets/8dbde493-bdc6-4226-aa28-ffdfc0bfa917)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-10-07 085848](https://github.com/user-attachments/assets/86630706-4367-4b4b-a890-b8e204991a5a)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2024-10-07 085907](https://github.com/user-attachments/assets/b5f3d48f-9084-4624-9f44-f41d36c167e5)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![Screenshot 2024-10-07 085926](https://github.com/user-attachments/assets/390c1eb0-4d0e-4f5e-90b7-4956677d995f)



Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2024-10-07 085936](https://github.com/user-attachments/assets/ecc8e274-75c5-4582-b9e0-f7ab0563b7dc)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
