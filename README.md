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

![arp-a](https://github.com/user-attachments/assets/67d0f25b-dbf2-48bf-ad47-34420791dca2)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:

![Screenshot 2025-04-08 232716](https://github.com/user-attachments/assets/83588076-6110-4bfc-9696-3ab103ec4937)





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![Screenshot 2025-04-08 225105](https://github.com/user-attachments/assets/3ff72943-879f-4936-a9e5-f9e97ca0fe34)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![Screenshot 2025-04-08 230659](https://github.com/user-attachments/assets/ca54d44b-147f-4ae8-891f-baad15477606)



Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-04-08 231325](https://github.com/user-attachments/assets/238d9a74-f876-4386-bdd2-06fe37af929a)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
