## HTTP Enumeration
  HTTP enumeration is the process of gathering information about a web server and its configuration by querying the server using the HTTP protocol. This can include identifying the web server software, its version, and the technologies used to build the website. The goal of HTTP enumeration is to gain a better understanding of the target web server and to identify potential vulnerabilities that can be exploited. 

### Command

  -> nmap -sV --script==http=enum <target>
  
<pre>
-sV: Enable version detection. This option instructs Nmap to attempt to determine the version and service of any open ports it finds.
--script http-enum: Run the http-enum script, which performs HTTP enumeration by querying various HTTP headers and directories to gather information about the target web server.
<target>: Replace this with the IP address or hostname of the target.
</pre>
