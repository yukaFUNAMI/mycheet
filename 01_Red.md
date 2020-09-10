# Tools
 ## Wordlist
 ### Fuzz
 Seclist
 https://github.com/danielmiessler/SecLists
 
 Fuzzdb
 https://github.com/fuzzdb-project/fuzzdb
 
 ### Password
 rockyou.txt
 
 ## NW
 ## WEB
 wfuzz -u http://target/dir/FUZZ.FUZ2Z -w /usr/share/seclists/Discovery/Web-Content/big.txt -z list,php-html-txt-log --hc 404 -p 127.0.0.1:8081
 
 fuff -w wordlist.txt -u http://target.com/api/FUZZ:80 -o output.txt -replay-proxy http://127.0.0.1:8081 -p 3 -t 3

-p wait(second)
-t number of thread

fuff -w wordlist.txt:FUZZ -w mylist.txt:FUZZ2 -u http://target.com/api/FUZZ/target.php?prm=FUZZ2

->clustorbomb+pitchfork

ffuf -w  wordlist.txt -X "PUT" -u http://target.com -H "Content Type:application/json" -d "{'FUZZ':'value'}" -o output.txt -replay-proxy http://127.0.0.1:8081

->test json(change request method)

curl
http://cheat.sh/curl

 ### CMS
 ## PrivEsc
  ### Linux
  ### Windows
  ### AD
  
# Basics
 ## Linux
 ## Networking
 ## Scripting

# Wireless

# Printer

# Clowd
 ## Azure
 ## AWS
 ## GCP
 
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
