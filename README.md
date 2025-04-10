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
![Screenshot 2025-04-10 153729](https://github.com/user-attachments/assets/7957de2f-6b4f-49df-8161-ff39e37cd922)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:
![Screenshot 2025-04-08 232716](https://github.com/user-attachments/assets/d007e76e-f4db-4552-b778-c68f3252bbda)






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2025-04-08 225105](https://github.com/user-attachments/assets/836e7cad-38fa-483d-8cea-98c92edcceff)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-04-08 230659](https://github.com/user-attachments/assets/74ad5c2d-3c96-44cc-b9f1-0cf150e33688)

Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-04-08 231325](https://github.com/user-attachments/assets/5808df54-6613-492c-ac40-baec77281638)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
