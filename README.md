Time spent: 4 hours

## Which Honeypot(s) you deployed

-Custom incident response 

-Wordpot 
https://github.com/gbrindisi/wordpot

-Dionaea
https://www.edgis-security.org/single-post/dionaea-malware-honeypot

（Dionaea “the Nepenthes successor” is a malware capturing honeypot initially developed under The Honeynet Project's 2009 Google Summer of Code (GSoC).）

Walkthrought: https://i.imgur.com/B5dvyNA.gif

## Any issues you encountered

-I wait half a day after set up and the attack finally shows up. I also tried other honeypot, but Dionase is the only one works.

## A summary of the data collected: number of attacks, number of malware samples, etc.

-I follow the guide of set up from Codepath. I used nmap -sV -P0 command in the terminal and saw about 900 attacks by nmap after several hours in the website.(Don`t know why it took so long, might because of set up issue) I found the attack are generally from my laptop, but some are from different areas. Pcap attack is the majority.

## Any unresolved questions raised by the data collected

-No
