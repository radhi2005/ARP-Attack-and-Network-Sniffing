## Name: AMIRTHVARSHINI V
## REG NO: 212223040014
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
<img width="704" height="494" alt="436853285-df9ed816-e626-473b-b908-8e9335f6699f" src="https://github.com/user-attachments/assets/8a7834ad-6ae0-45c3-9303-359d90fd3447" />
From kali linux issue the command : sudo arpspoof -i eth0 -t

### OUTPUT
<img width="689" height="270" alt="436853313-d25772c7-f872-4a15-ba49-f52992d877f1" src="https://github.com/user-attachments/assets/806cf959-07bc-4d9f-99c9-c7a621590055" />
dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

### OUTPUT:
<img width="622" height="601" alt="436853483-46680b15-dc80-4de6-971b-1fdea5048305" src="https://github.com/user-attachments/assets/a0b2644e-cee6-49ea-bbbb-487f9e3ae99d" />
In Kali issue the following commands: sudo dsnifff

### OUTPUT:
<img width="1918" height="871" alt="436853910-5da7a394-806a-4542-90c9-a29da63b5e48" src="https://github.com/user-attachments/assets/5fed5878-0cb2-4275-9225-2a55bd63017b" />
Invoke the wireshark and examine the various menus and controls of the tool:

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
