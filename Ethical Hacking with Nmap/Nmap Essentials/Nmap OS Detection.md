## Introduction
One of the Nmap best known command is remote OS detection using TCP/IP stack fingerprinting. Nmap sends some of TCP/UDP packets to the remote host and check every bit in the responses.

### Commands
  1. -O (run the OS detection)
  ![image](https://user-images.githubusercontent.com/61587800/233002575-70cec06b-2547-4082-8034-e1482ecfaeec.png)

  2. --osscan-guess
  ![image](https://user-images.githubusercontent.com/61587800/233003030-a70d44bf-08f6-4f8d-afd4-4a6f1dded2ea.png)

  3. nmap -sV -O -v target
<pre>  
  ┌──(unknown㉿anon)-[~]
└─$ sudo  nmap -sV -O -v 192.168.1.4
Starting Nmap 7.93 ( https://nmap.org ) at 2023-04-19 13:08 IST 
NSE: Loaded 45 scripts for scanning.
Initiating ARP Ping Scan at 13:08
Scanning 192.168.1.4 [1 port]
Completed ARP Ping Scan at 13:08, 0.06s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 13:08
Completed Parallel DNS resolution of 1 host. at 13:08, 0.05s elapsed
Initiating SYN Stealth Scan at 13:08
Scanning 192.168.1.4 [1000 ports]
Discovered open port 554/tcp on 192.168.1.4
Discovered open port 135/tcp on 192.168.1.4
Discovered open port 139/tcp on 192.168.1.4
Discovered open port 445/tcp on 192.168.1.4
Discovered open port 2869/tcp on 192.168.1.4
Discovered open port 5357/tcp on 192.168.1.4
Discovered open port 10243/tcp on 192.168.1.4
Completed SYN Stealth Scan at 13:08, 4.80s elapsed (1000 total ports)
Initiating Service scan at 13:08
Scanning 7 services on 192.168.1.4
Completed Service scan at 13:10, 112.90s elapsed (7 services on 1 host)
Initiating OS detection (try #1) against 192.168.1.4
NSE: Script scanning 192.168.1.4.
Initiating NSE at 13:10
Completed NSE at 13:10, 7.11s elapsed
Initiating NSE at 13:10
Completed NSE at 13:10, 7.02s elapsed
Nmap scan report for 192.168.1.4
Host is up (0.0012s latency).
Not shown: 993 filtered tcp ports (no-response)
PORT      STATE SERVICE      VERSION
135/tcp   open  msrpc        Microsoft Windows RPC
139/tcp   open  netbios-ssn  Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds Microsoft Windows 7 - 10 microsoft-ds (workgroup: WORKGROUP)
554/tcp   open  rtsp?
2869/tcp  open  http         Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
5357/tcp  open  http         Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
10243/tcp open  http         Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
MAC Address: 08:00:27:42:5E:2F (Oracle VirtualBox virtual NIC)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose|specialized|phone
Running: Microsoft Windows 2008|8.1|7|Phone|Vista
OS CPE: cpe:/o:microsoft:windows_server_2008:r2 cpe:/o:microsoft:windows_8.1 cpe:/o:microsoft:windows_7 cpe:/o:microsoft:windows cpe:/o:microsoft:windows_vista::- cpe:/o:microsoft:windows_vista::sp1
OS details: Microsoft Windows Server 2008 R2 or Windows 8.1, Microsoft Windows Embedded Standard 7, Microsoft Windows Phone 7.5 or 8.0, Microsoft Windows Vista SP0 or SP1, Windows Server 2008 SP1, or Windows 7, Microsoft Windows Vista SP2, Windows 7 SP1, or Windows Server 2008
Uptime guess: 0.021 days (since Wed Apr 19 12:40:57 2023)
Network Distance: 1 hop
TCP Sequence Prediction: Difficulty=263 (Good luck!)
IP ID Sequence Generation: Incremental
Service Info: Host: ADMIN-PC; OS: Windows; CPE: cpe:/o:microsoft:windows

Read data files from: /usr/bin/../share/nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 135.99 seconds
           Raw packets sent: 2031 (91.202KB) | Rcvd: 17 (1.070KB)

</pre>
