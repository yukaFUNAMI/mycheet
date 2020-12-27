# Tools
 ## Lists
 Seclist https://github.com/danielmiessler/SecLists
 
 Fuzzdb https://github.com/fuzzdb-project/fuzzdb
 
 ## Password
 Basic Auth(https://10.10.10.10:443/targetdir id:admin pass:mylist)
 
 hydra -l admin -P /usr/share/wordlists/mylist.txt 10.10.10.10 -s 443 https-get /targetdir
 
 ## Enum
 Basic Commands(Network)
 
 Nmap
 
 Masscan https://github.com/robertdavidgraham/masscan

 AutoRecon https://github.com/Tib3rius/AutoRecon
 
 Sn1per https://github.com/1N3/Sn1per
 
 ### Subdomain
 Amass https://github.com/OWASP/Amass
 
 Subfinder https://github.com/subfinder/subfinder

 ### OSINT 
 pawned https://haveibeenpwned.com/
 
 googledorks https://www.exploit-db.com/google-hacking-database
 
 Shodan https://www.shodan.io/
 
 Cessys https://censys.io/
 
 ## WEB
 OpenVas https://github.com/greenbone/openvas
 
 Nessus
 
 Burp Proxy (Extentions)
 
 Logger++ https://github.com/PortSwigger/logger-plus-plus
 
 RetireJS https://github.com/PortSwigger/retire-js
 
 Wafdetect https://github.com/PortSwigger/waf-detect
 
 Whatthewaf https://github.com/PortSwigger/what-the-waf
 
 Bypasswaf https://github.com/PortSwigger/bypass-waf
 
 UploadScanner https://github.com/PortSwigger/upload-scanner
 
 traversal https://github.com/PortSwigger/file-upload-traverser
 
 https://github.com/PortSwigger/intruder-file-payload-generator
 
 Notes https://github.com/PortSwigger/notes
 
 
 Gobuster https://github.com/OJ/gobuster
 
 wfuzz https://github.com/xmendez/wfuzz
 
 wfuzz -u http://target/dir/FUZZ.FUZ2Z -w /usr/share/seclists/Discovery/Web-Content/big.txt -z list,php-html-txt-log --hc 404 -p 127.0.0.1:8081
 
 ffuf https://github.com/ffuf/ffuf
 
 ffuf -w wordlist.txt -u http://target.com/api/FUZZ:80 -o output.html -of html -replay-proxy http://127.0.0.1:8081 -p 3 -t 3
 
 -p wait(second), -t number of thread, -of fileformat(html->you can open browser)
 
 ffuf -w wordlist.txt:FUZZ -w mylist.txt:FUZZ2 -u http://target.com/api/FUZZ/target.php?prm=FUZZ2
 ->clustorbomb+pitchfork
 
 ffuf -w  wordlist.txt -X "PUT" -u http://target.com -H "Content Type:application/json" -d "{'FUZZ':'value'}" -o output.txt -replay-proxy http://127.0.0.1:8081
->test json(change request method)

ffuf -w wordlist.txt -u http://target.com/FUZZ/ -e .php -recursion

### SQLi
sqlmap https://github.com/sqlmapproject/sqlmap

https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection

MYSQL

PostgreSQL

MSSQL

Oracle

NOSQL

### XSS
xsshunter https://github.com/mandatoryprogrammer/xsshunter

bypass https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet

Frameworks Doc(JS)
React.js
Angular.js
Node.js
Bootstrap
Nuxt.js
jQuery
Vue.js

### CMS
WhatCMS https://github.com/GONZOsint/WhatCMS
WPScan https://github.com/wpscanteam/wpscan
Droupal https://github.com/droope/droopescan 
Joomer https://github.com/OWASP/joomscan
Magento 

### API

### WAF Bypass
#### Akm
#### Cloud
#### Etc

## PrivEsc
 ### Linux  
  Training(Udemy) https://www.udemy.com/course/linux-privilege-escalation/

### Windows  
  Training(Udemy) https://www.udemy.com/course/windows-privilege-escalation/
  ### AD
  
# Basics
curl http://cheat.sh/curl

# Wireless

# Printer

# Clowd
 ## Azure
 ## AMZN
 https://digi.ninja/projects/bucket_finder.php
 ## GCP
 ## Git
 https://github.com/michenriksen/gitrob
 
# LabSetup
 ## Kali
 ## Docker
 Docker handbook(JP)
 https://shimo5.me/post/2020-09-07/
 
# Resorces
## Howto
https://www.vulnhub.com/resources/

## Guidance
 OWASP Testing guide
 https://owasp.org/www-project-web-security-testing-guide/

 PCI DSS Penetration-Testing-Guidance
 https://www.pcisecuritystandards.org/documents/Penetration-Testing-Guidance-v1_1.pdf

 PTES Technical Guidelines
 http://www.pentest-standard.org/index.php/PTES_Technical_Guidelines

## Report
Pentest Tools
https://pentest-tools.com/features/pentest-reporting-tool

Offensive Security
https://www.offensive-security.com/reports/sample-penetration-testing-report.pdf

## Leagal(JP)
