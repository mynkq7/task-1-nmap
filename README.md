# Task 1 – Nmap Local Network Scan

## What Did
Ran a SYN scan using Nmap on my local network (`172.16.2.0/24`).  
Main goal was to understand how Nmap works, how ports respond, and how host discovery is done.

## Command Used
```bash
nmap -sS 172.16.2.0/24
nmap -sS 172.16.2.0/24 -oN result.txt
