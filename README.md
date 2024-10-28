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

![Screenshot 2024-10-23 091842](https://github.com/user-attachments/assets/17b57b4c-fb6c-4fd5-95be-46f08eaaca81)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/user-attachments/assets/71fd6c01-9d8c-4efc-a26a-392004516f13)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![Screenshot 2024-10-23 091121](https://github.com/user-attachments/assets/17b17a76-7b69-4591-94b9-370c7c0a596f)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![Screenshot 2024-10-23 091110](https://github.com/user-attachments/assets/26b41635-6230-4ee5-a9d0-588683da5c41)



Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/d6a0702a-8cb7-4e4f-953b-78fc8e395eb5)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
