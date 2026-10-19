# Ancora-Education-Ucertify-Lab69
# Part II: Command Line Tools

Command line tools are powerful utilities that allow users to interact with a computer's operating system through text-based commands. In this lab session, you will explore various command line tools and learn how to use them effectively. This lab session will cover several command line tools, namely, nslookup, arp, route, and netstat commands.

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=12]

## Lab Objective 
This lab session demonstrates the steps involved in using the commands nslookup, arp, route, and netstat in Windows PowerShell. Upon completion of this lab, you will be able to: 
* Understand the purpose of nslookup, arp, route, and netstat commands.
* Query DNS servers with the nslookup command.
* Display the local ARP table with the arp command.
* View and modify the local routing table with the route command.
* Display active connections and protocol statistics with the netstat command. Lab/Machine Environment You are provided with the Windows virtual machine.

## PART A: Analyzing Command Line Tools
Launch Windows PowerShell, execute nslookup, arp, route, and netstat commands, and then analyze their results. Windows PowerShell is a powerful command-line shell and scripting language developed by Microsoft specifically for Windows operating systems. It provides a comprehensive set of administrative tools and capabilities for managing and automating system tasks.
### STEP 1
Click the Start menu and open Windows PowerShell. 
### STEP 2
Execute the following command to use nslookup and to find name server information for a domain by querying the Domain Name System:
```bash
nslookup www.google.com
```
### STEP 3
Execute the following command to use arp and to show what media access control (MAC) addresses have been learned for the listed IP addresses:
```bash
arp -a
```
### STEP 4
Execute the following command to use route and to display the contents of a PC’s routing table:
```bash
route print
```
### STEP 5 
Execute the following command to use netset and to show the path taken by a packet on an IP network from the source to the destination:
```bash
netstat
```
### STEP 6
Execute the following command to show the name of the program that opened a session:
```bash
netstat -b
```
## Lab Summary
This lab session provides you with a straightforward and practical understanding of the commands nslookup, arp, route, and netstat in Windows PowerShell. Here's a summary of what you have learned:
* How to query DNS servers with the nslookup command.
* How to display the local ARP table with the arp command.
* How to view and modify the local routing table with the route command.
* How to display active connections and protocol statistics with the netstat command.

Now, you are equipped with the knowledge and skills to use the commands nslookup, arp, route, and netstat in Windows PowerShell effectively.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
