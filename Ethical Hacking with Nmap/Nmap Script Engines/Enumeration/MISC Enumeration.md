## MISC Enumeration
  MISC enumeration is a broad term that encompasses the enumeration of various services and protocols that may be running on a target system. 

### Commands

  -> nmap -A -T4 scanme.nmap.org
  
<pre>
-A: Enables OS detection, version detection, script scanning, and traceroute.
-T4: Sets the timing template to "aggressive". This will increase the speed of the scan, but may also increase the chance of detection or false positives.
scanme.nmap.org: This is the target host you want to scan.
</pre>
