## MySQL Enumeration
  MySQL enumeration is the process of gathering information about a MySQL database server and its configuration by querying the server using the MySQL protocol. The goal of MySQL enumeration is to gain a better understanding of the target database server and to identify potential vulnerabilities that can be exploited.

### Commands

  -> nmap --script=mysql-enum <target>

<pre>
--script=mysql-enum: Run the mysql-enum script, which performs MySQL enumeration by querying the server for information about databases, tables, users, and privileges.
<target>: Replace this with the IP address or hostname of the target.
</pre>
