## Name: Barkavi B
## Reg.no:212224110011
# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system



## OUTPUT:
![alt text](image.png)

Invoke msfconsole:




## OUTPUT:

![alt text](image-2.png)

![alt text](image-3.png)

Following command is executed for scanning the systems on our local area network with a TCP scan (-sT) looking for open ports between 1 and 1000 (-p1-1000).

msf > nmap -sT 192.168.1810/24 -p1-1000
![alt text](image-4.png)
step4: use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.

scan the targets with the command db_nmap as follows.

msf > db_nmap 192.168.181.0/24

![alt text](image-5.png)
Metasploit has a multitude of scanning modules built in. If we open another terminal, we can navigate to

Metasploit's auxiliary modules and list all the scanner modules.

cd /usr/share /metasploit-framework/modules/auxiliary

kali > ls -l
![alt text](image-6.png)

Search is a powerful command in Metasploit that you can use to find what you want to locate.

msf >search name:Microsoft type:exploit

![alt text](image-7.png)

![alt text](image-8.png)
search type:auxiliary mysql

![alt text](image-9.png)
use 11

![alt text](image-10.png)

set RHOSTS

![alt text](image-11.png)

![alt text](image-12.png)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
