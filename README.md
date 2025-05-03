# NAME: NARESH KUMAR R
# REG NO: 212224040213
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
![image](https://github.com/user-attachments/assets/25e37f87-63c4-468c-ac81-73d30353ab24)
![image](https://github.com/user-attachments/assets/49c9a24a-a553-4748-8a7b-0a4ae925844e)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
dsniff:
![image](https://github.com/user-attachments/assets/2888d36d-2cbe-4e69-af02-792e5edf80ab)

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/6d43dfaf-7c0c-4400-a9d8-bee318e73c21)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/e241399c-4af2-41b5-b638-72a7f82861f0)

Invoke the wireshark and examine the various menus  and controls of the tool:
##Output:
![image](https://github.com/user-attachments/assets/2b25d109-0382-43c5-8764-8f345e2e772b)

Ettercap:
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:
![image](https://github.com/user-attachments/assets/24e467e9-6270-4c92-9dcf-ff37596f2ac5)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
