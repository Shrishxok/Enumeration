# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
### OUTPUT:
![1](https://github.com/Shrishxok/Enumeration/assets/120294863/c5489ad4-1b70-4f4e-9f8f-6b7969331906)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
### OUTPUT:
![2](https://github.com/Shrishxok/Enumeration/assets/120294863/bdee21a2-1640-4a0e-978e-45c3139215ea)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
### OUTPUT:
![3](https://github.com/Shrishxok/Enumeration/assets/120294863/fbef21c8-e9cd-4a6f-b677-8a48600a5056)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
### OUTPUT:
![4](https://github.com/Shrishxok/Enumeration/assets/120294863/267c08d8-a834-4ad5-8482-b076476de29c)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
### OUTPUT:
![5](https://github.com/Shrishxok/Enumeration/assets/120294863/9c0ef6c1-c62f-46dc-9984-c49e4379d104)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
### OUTPUT:
![6](https://github.com/Shrishxok/Enumeration/assets/120294863/8849198b-0078-4f1d-9cb9-b2a080199635)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
### OUTPUT:
![7](https://github.com/Shrishxok/Enumeration/assets/120294863/e866be0a-5a15-444f-865b-f1c21d58550c)

 
#DNS Enumeration

##DNS Recon provides the ability to perform: Check all NS records for zone transfers Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration Top level domain expansion
## OUTPUT:
![8](https://github.com/Shrishxok/Enumeration/assets/120294863/dc27d5f0-3ff8-4c3a-a2dc-fb402a0c84e4)

##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
![9](https://github.com/Shrishxok/Enumeration/assets/120294863/83e4f679-8cc9-468e-b0f8-3465689bd8b8)

##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
![10](https://github.com/Shrishxok/Enumeration/assets/120294863/b7697cef-d806-4be5-9457-5f54b1098b21)

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
![11](https://github.com/Shrishxok/Enumeration/assets/120294863/b3f15900-cefc-457f-8cb7-f7e0e4bf866b)

select any username in the first column of the above file and check the same
![12](https://github.com/Shrishxok/Enumeration/assets/120294863/6285a474-adb1-4f83-b2ea-21e8bd6048fd)


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet <host address> 25 to connect
and issue appropriate commands

### OUTPUT:
![13](https://github.com/Shrishxok/Enumeration/assets/120294863/76be2435-f8d2-4278-a978-8f6682c1dddd)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
### OUTPUT:
![14](https://github.com/Shrishxok/Enumeration/assets/120294863/91f67547-fb06-47ee-9fdf-f991487d44ce)
### RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

