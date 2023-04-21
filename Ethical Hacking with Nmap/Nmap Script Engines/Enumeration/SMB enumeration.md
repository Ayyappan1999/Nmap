## SMB Enumeration
   SMB enumeration is the process of gathering information about a target system's SMB (Server Message Block) service by querying it for information. SMB is a network protocol used by Windows systems for sharing files, printers, and other resources.
  
### Commands

  -> nmap --script smb-enum-users.nse -p445 <host>
  
<pre>
--script smb-enum-users.nse: Run the smb-enum-users.nse script, which enumerates users and groups on the target system by querying the SMB service.
-p445: Specifies that Nmap should only scan the target's SMB service on port 445.
<host>: Replace this with the IP address or hostname of the target system.
</pre>

  ->  nmap --script smb-os-discovery.nse -p445 <target>
  
<pre>
--script smb-os-discovery.nse: Run the smb-os-discovery.nse script, which detects the operating system of the target system by querying the SMB service.
-p445: Specifies that Nmap should only scan the target's SMB service on port 445.
<target>: Replace this with the IP address or hostname of the target system.
</pre>
