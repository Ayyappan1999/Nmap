## nmap -p80 scanme.nmap.org

<pre>

### open

┌──(unknown㉿anon)-[~]
└─$ nmap -p80 scanme.nmap.org
Starting Nmap 7.93 ( https://nmap.org ) at 2023-04-21 13:53 IST
Nmap scan report for scanme.nmap.org (45.33.32.156)
Host is up (0.25s latency).
Other addresses for scanme.nmap.org (not scanned): 2600:3c01::f03c:91ff:fe18:bb2f

PORT   STATE SERVICE
80/tcp open  http

Nmap done: 1 IP address (1 host up) scanned in 1.48 seconds

### closed

┌──(unknown㉿anon)-[~]
└─$ nmap -p80 192.168.1.6 
Starting Nmap 7.93 ( https://nmap.org ) at 2023-04-21 13:54 IST
Nmap scan report for 192.168.1.6
Host is up (0.00010s latency).

PORT   STATE  SERVICE
80/tcp closed http

Nmap done: 1 IP address (1 host up) scanned in 0.07 seconds

</pre>
