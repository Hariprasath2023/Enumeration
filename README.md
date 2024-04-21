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

site:   This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![Screenshot 2024-04-21 090926](https://github.com/Hariprasath2023/Enumeration/assets/145207783/97ce1236-87e7-4142-89e9-9da065cc4c5a)


filetype:  This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![Screenshot 2024-04-21 090935](https://github.com/Hariprasath2023/Enumeration/assets/145207783/e56660b9-dfb3-48d7-b2f5-d52733d55bbb)



intext:   This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![Screenshot 2024-04-21 090944](https://github.com/Hariprasath2023/Enumeration/assets/145207783/f722f099-fc03-4b28-b133-28746183a18d)


inurl:   This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![Screenshot 2024-04-21 090953](https://github.com/Hariprasath2023/Enumeration/assets/145207783/3bf64f01-f9f9-417e-bf7c-4c438139c98b)

intitle:   This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![Screenshot 2024-04-21 091001](https://github.com/Hariprasath2023/Enumeration/assets/145207783/6f0dfa22-6247-480d-a129-e569b307a9ea)


link:   This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![Screenshot 2024-04-21 091009](https://github.com/Hariprasath2023/Enumeration/assets/145207783/5ee3c8db-d99d-44a5-8cc6-4a1499b5625d)

cache:   This operator allows you to view t he cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 ![Screenshot 2024-04-21 091018](https://github.com/Hariprasath2023/Enumeration/assets/145207783/01820184-8431-4754-b384-2d717f6e9bca)

#DNS Enumeration


##DNS Recon
provides the ability to perform: Check all NS records for zone transfers Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT) Perform common SRV Record Enumeration Top level domain expansion
output:
![Screenshot 2024-04-21 091034](https://github.com/Hariprasath2023/Enumeration/assets/145207783/fba08d94-4129-4b2a-a425-38d8cd886b12)
Denesum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record). Get the namservers (threaded). Get the MX record (threaded). Perform axfr queries on nameservers and get BIND versions(threaded). Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”). Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded). Calculate C class domain network ranges and perform whois queries on them (threaded). Perform reverse lookups on netranges (C class or/and whois netranges) (threaded). Write to domain_ips.txt file ip-blocks. This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
![Screenshot 2024-04-21 091040](https://github.com/Hariprasath2023/Enumeration/assets/145207783/f9731be0-ee7f-46ec-8a27-a61a28ed0291)

smtp-user-enum

Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

![Screenshot 2024-04-21 091048](https://github.com/Hariprasath2023/Enumeration/assets/145207783/70b096ff-ace9-4b26-9000-c2e1780bd3bc)
select any username in the first column of the above file and check the same
![Screenshot 2024-04-21 091057](https://github.com/Hariprasath2023/Enumeration/assets/145207783/f7864a67-ab16-4d48-80cc-7a9a1f627c15)
Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet 25 to connect and issue appropriate commands

Output
![Screenshot 2024-04-21 091108](https://github.com/Hariprasath2023/Enumeration/assets/145207783/c2947732-a462-4da2-99bb-b5e568dc0fbd)
nmap –script smtp-enum-users.nse
The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

OUTPUT:
![Screenshot 2024-04-21 091118](https://github.com/Hariprasath2023/Enumeration/assets/145207783/ad41cbbf-4ea8-4f09-9423-9aa9ab3ffef8)







## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

