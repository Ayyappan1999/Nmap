### Introduction

  Nmap is one the must popular tools for get enumeration of the victim's host. There is a
lot of tools for scanning firewalls, operating systems, versions, IP ranges, etc.

  According to pervious sessions, we are using this tool for information gathering.

### Commands

  1. nmap -iL <ip list>
  2. nmap -iL <ip list> -sV
  3. nmap =sV -sC -T4 -n -Pn -oA fastscan <target>
