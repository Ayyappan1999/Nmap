## Nmap Brute-Forec

  -> Nmap has simple built-in scripts that brute-force almost all service including HTTP, TELNET, SSH, MySQL, Samba, ete.

###Commands

  -> nmap --script ssh-brute -p22 <target>
  
  -> nmap --script ftp-brute -p21 <target> --script-args userdb=users.txt, passdb=passwords.txt
  
  -> nmapp --script mysql-brute -p3306 <target> --script-args userdb=users.txt, passdb=passwords.txt
  
