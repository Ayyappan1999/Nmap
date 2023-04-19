## Introduction

### TCP
  Transfer protocol or TCP is connection-oriented protocol which means once a connection is stable, it is going to “setup” a connection then start transferring data.

### UDP
  UDP or User Datagram Protocol is simpler and connectionless which means it starts sending and doesn't care if it arrives or not.

  
# Nmap TCP and SYN Scan 
In the SYN scan, we can perform operations quickly.
Scanning thousands of ports in the second is the reason for becoming one of the most popular types of scan.

###Commands

  1. nmap -p22,133,139 target.com
  ![image](https://user-images.githubusercontent.com/61587800/233000836-1bae5496-809f-4879-87d6-91791d26d2fc.png)

  2. nmap -d --packet-trace -p22,133,139 target.com
  ![image](https://user-images.githubusercontent.com/61587800/233001478-644e92c8-da71-4137-abbd-1f84ce4b3949.png)
