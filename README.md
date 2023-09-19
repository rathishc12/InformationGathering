# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/9cffcbb9-cd72-4171-bf15-30014b866711)
## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/3e11d028-82ad-4c4b-9609-62b3f06af3fb)
## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/aac50b33-d927-4d31-a15d-73b665685c20)
## History of the wbsite:
## Output:
https://web.archive.org/        

![image](https://github.com/rathishc12/InformationGathering/assets/120539398/5767818c-a756-493b-a8f2-91abef97877f)
## Web server Fingerprint:
## Netcat:

nc 172.17.52.118 80

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/d68ddbd5-4fec-4e27-b400-0dc85e7fc4ac)
## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org

## Output:
![239422130-f8eebdf9-67ff-42c0-ae3b-b126d20576bb](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/4bb36ba7-34f4-4eea-bc87-dd922fdf1429)
## Whatweb:

whatweb infosys.com


whatweb zoho.com


whatweb -v -a 3 172.17.52.201

## Output:
![239422365-13003241-f18f-4e84-b15d-86a327e9c68c](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/c2f54de4-7829-472e-8674-4254ba7afa0f)
## httprint:InformationGathering

httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/31e9520a-b989-4d4a-a650-3a3213443794)
## Tracing the Location:
## TCP Traceroute:

sudo traceroute -T www.saveetha.ac.in

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/b3e5f1e5-7fed-46a7-9db4-c92912bf014e)
## UDP Traceroute:

sudo traceroute -U www.saveetha.ac.in

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/b66b52c3-09c8-4c99-834e-8c2204730031)
## ICMP Traceroute:

sudo traceroute  www.saveetha.ac.in

## Output:
![image](https://github.com/rathishc12/InformationGathering/assets/120539398/bcc85ca3-eed2-4dcf-b01e-dd4729a00d0d)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
