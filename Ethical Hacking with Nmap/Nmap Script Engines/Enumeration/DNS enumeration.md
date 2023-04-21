## Dns Enumeration
  
   ◘ DNS enumeration is a technique used by attackers to gather information about a target organization's DNS infrastructure. This information can be used to identify potential vulnerabilities and attack vectors.
      
### Commands

   ◘ nmap -sSU -p 53 --script dns-nsec-enum --script-args dns example.com<target>

<pre>
-sSU: Use both TCP and UDP scanning techniques.
-p 53: Scan the DNS port (port 53).
--script dns-nsec-enum: Run the dns-nsec-enum script, which performs DNSSEC enumeration by brute forcing subdomains protected by DNSSEC.
--script-args dns: Pass the dns argument to the script, which tells it to use DNS queries to enumerate subdomains.
example.com<target>: Replace <target> with the IP address or hostname of the target domain.
</pre>
