# Hacking Tools
_Hello Everyone I am Harsith Priyan S, This Repo contains the list of some basic and must have tools for hackers, it also contains certain tools that I use for Bug Bounties, CTF and Pentesting, so if you are configuring Ubuntu or any other Linux for Hacking this Repo Would be useful_
## Tools

1. Msfconsole - This tool is used to probe systematic vulnerabilities on network and servers. This tool is mainly used for exploiting vulnerabilities. You can see the docs to setup this tool.

2. Burpsuite - This tool allows you to intercept browser communication and modify the content. You can visit the official website for more Information (https://portswigger.net/burp)

3. Sublist3r - This tool help you to enumerate sub domains, you can download it from official github repo (https://github.com/aboul3la/Sublist3r)

4. Nmap - It is a reconnaissance tool which helps you to get information from the target computer like the ports open and services running. You can install it with the following command:
`sudo apt-get install nmap`

5. Hashcat - It is a password / hash cracking tool it can be installed using the following command: `sudo apt-get install hashcat`

6. Wifite2 - It is a Wi-fi, i.e, a WPA hacking tool, you can install it with the following command: `sudo apt-get install wifite`

7. Hydra - Hydra is a parallelized network login cracker , it uses different method to bruteforce credentials. You can Install with the following command: `sudo apt-get install hydra`

8. Wireshark - It is network packet analyzer tool , used for network analysis and troubleshooting , It ca also be used for MITM attack. You can install it using the following command: `sudo apt-get install wireshark`

9. WafW00f - This tools helps to identify and fingerprint Web Application Firewall. It can installed by the following command :`sudo apt-get install wafw00f` or from the github repo (https://github.com/EnableSecurity/wafw00f) 

10. Smuggler - This tool helps to detect whether the web application is vulnerable for http request smuggling. It can be installed by the following git hub repo (https://github.com/defparam/smuggler)

11. Ettercap - This tool is mainly used for MITM Attacks. It can be installed by the following command: `sudo apt-get install ettercap-graphical`

12. Driftnet - This is also used for MITM attack this helps to get the images loaded in victim's browser. It can be installed by the following command: `sudo apt-get install driftnet`

13. Urlsnarf - This tools is also used for MITM attacks this is used to load url's visited by victim. This can be installed by the following command: `sudo apt-get install dsniff`

14. Exiftool - This tool is used for CTF and stuff this helps to get a file information. this can be installed with the following command: `sudo apt-get install exiftool`

15. xxd - This tools helps to analyse the hex value of the file, this also used for CTF. It comes pre-installed in most linux.

16. Java - Even though this is not directly a hackng tool it helps to use certain tools, so make sure you have the latest version installed. `sudo apt install openjdk-16-jdk`

17. Ruby - This is also not directly a hacking tool but it is used for running other tools like python and java. It can be installed from the following command: `sudo apt-get install ruby`

18. Snap - It is a software packing and deployment system developed by canonical, this helps to install all other apps easily. It can be installed from the following command : `sudo apt-get install snap`

19. Atom code Editor - This is IDE used for coding and note taking, it can installed using snap with the following command: `sudo snap install atom --classic`

20. VS Code - This also an IDE like Atom, it can be installed with the following command : `sudo snap install code --classic`

21. Sublime Text -  This to is an IDE and can be installed with the following command: `sudo snap install sublime-text --classic` 

22. Pycharm - It is a speacial text editor mainly for python, it will come handy when developing payloads or backdoors with python. It can be installed with the following command: `sudo snap install pycharm-community --classic`

_I have included 4 different Text editor's as each have their own speaciality and advantage_

23. Node Js - This is also no directly a hacking tool but  would come handy when developing exploits and hosting stuff. It can be installed with the following command: `sudo apt-get install nodejs`

24. Npm - npm is a JS package manager, it can be installed with the following command: `sudo apt-get install npm`

25. Nikto - It is an automated web app vulnerability scanner. It can be installed with the following command: `sudo apt-get install nikto`

26. Maltego - Maltego is a real-time GUI based information gathering tool it is also used for forensics, it provides a node-based graph result. For installing it make sure to check it's official website (https://www.maltego.com/)

27. Subfinder - It is also a sub domain enumeration tool like sublist3r but gives a faster result but has false positives. It can be installed using the following command: `sudo apt-get install subfinder`

28. Searchsploit (exploitdb) - This tools helps to find exploits easily, moreover it is like a browser for finding exploits. To install it visit the official github repo : (https://github.com/offensive-security/exploitdb)

29. htop - This helps to monitor the process running in your linux machine it can be installed by the following command: `sudo apt-get install htop`

30. Wappalyzer - It is a browsewr extension used to gather information about the web application, like what languages have been used to code the website the backend services and stuff. You can download it from chrome or firefox store.

31. Wpscan - It is an automated vulnerability scanner for wordpress helps enumerate plugins and themes used by the site. It does not have any direct installation candidate so first install gem using the following command : `sudo apt-get install gem` , Then use : `gem install wpscan` to instrall the tool in ubuntu.

32. LanScan - This tool is developed by me with python this helps to find out the information about who all are connected in your Wi-Fi. It can be found in my Repo. (https://github.com/Harsith-Panda/LanScan)

33. Wordpress Exploits - You can try using a lot of wordpress exploits but out here I am mentioning about the exploit for content injection on wordpress developed by me, version 4.7 and below are vulnerable for this exploit. (https://github.com/Harsith-Panda/Wordpress-4.7-ci)

34. Amass - It is a network mapping tool of Attack Surfaces and external asset dictionary, it uses active reconanaissance Techinque. For more information visit github Repo (https://github.com/OWASP/Amass)

35. XSS Hunter -  It helps to find xss vulnerabilities on website including blind xss and stuff. Github (https://github.com/mandatoryprogrammer/xsshunter)

36. Shodan.io - It is like a web browser for Hackers, it is a search-engine for internet connected devices, it show all vulnerable Devices.

37. Google.com - The reason why I have added google to the list is that google is a search engine , if used correctly it can help you find bugs and earn bounty, this method is called google dorks.

38. Dnsrecon - This tool helps helps to check all ns Records  and DNS Records of a website. It can be installed with the following command : `sudo apt-get install dnsrecon`

39. Dnsenum - As the name mention this is used for enumerating the DNS records , NS , Domain name servers and mail exchange servers. `sudo apt-get install dnsenum`

40. Sqlmap - This helps to map for sql vulnerabilities and find them, eventhough there can be false positives this tool is worth testing out and is very useful. Github (https://github.com/sqlmapproject/sqlmap)

41. Rock You.txt - Even though tere is a lot of other btuteforcing wordlist Rock You.txt has proved yo be my favorite for long time. (https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)

_This list contains most of important and famous tools used for hacking, this kind of tool list has been useful when I have been setting up ubuntu machine for hacking. Hope this would be helpful for you all. Make sure to use this tools legally_
