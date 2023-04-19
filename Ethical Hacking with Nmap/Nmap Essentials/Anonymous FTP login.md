### Introduction

   -> Anonymous users log in to the FTP server by using other FTP or anonymous as a username.
   
### Commands

    1. nmap -sV -sC ip address
<pre>    
┌──(unknown㉿anon)-[~]
└─$ sudo nmap -sV -sC 192.168.1.4      
[sudo] password for unknown: 
Starting Nmap 7.93 ( https://nmap.org ) at 2023-04-19 15:07 IST
Nmap scan report for 192.168.1.4
Host is up (0.0011s latency).
Not shown: 993 filtered tcp ports (no-response)
PORT      STATE SERVICE      VERSION
135/tcp   open  msrpc        Microsoft Windows RPC
139/tcp   open  netbios-ssn  Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds Windows 7 Ultimate 7601 Service Pack 1 microsoft-ds (workgroup: WORKGROUP)
554/tcp   open  rtsp?
2869/tcp  open  http         Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
5357/tcp  open  http         Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Service Unavailable
10243/tcp open  http         Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
MAC Address: 08:00:27:42:5E:2F (Oracle VirtualBox virtual NIC)
Service Info: Host: ADMIN-PC; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
|_clock-skew: mean: -1h50m00s, deviation: 3h10m30s, median: -1s
| smb-security-mode: 
|   account_used: guest
|   authentication_level: user
|   challenge_response: supported
|_  message_signing: disabled (dangerous, but default)
|_nbstat: NetBIOS name: ADMIN-PC, NetBIOS user: <unknown>, NetBIOS MAC: 080027425e2f (Oracle VirtualBox virtual NIC)
| smb2-time: 
|   date: 2023-04-19T09:39:12
|_  start_date: 2023-04-19T09:32:55
| smb2-security-mode: 
|   210: 
|_    Message signing enabled but not required
| smb-os-discovery: 
|   OS: Windows 7 Ultimate 7601 Service Pack 1 (Windows 7 Ultimate 6.1)
|   OS CPE: cpe:/o:microsoft:windows_7::sp1
|   Computer name: admin-PC
|   NetBIOS computer name: ADMIN-PC\x00
|   Workgroup: WORKGROUP\x00
|_  System time: 2023-04-19T15:09:13+05:30

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 200.06 seconds
</pre>
