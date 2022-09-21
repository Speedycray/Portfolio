# Michael Kuo
*Cybersecurity Engineer | Aspiring Pentester*

# Education
* Cyber Defense Professional Certificate, *University of Central Florida*, 2021-2022
* Bachelors of Science (Computer Science), *University of Central Florida*, 2019-2021
* Minor (Secure Computing and Networking), *University of Central Florida*, 2019-2021
* Associates (Computer Science), *Valencia College*, 2017-2019

# Certifications
* <a href="https://raw.githubusercontent.com/Speedycray/portfolio/main//CompTIA%20Network%2B%20ce%20certificate-1.png" target="_blank">CompTIA Network+ 2022-2025</a>
* <a href="https://badgr.com/public/assertions/W6z9tAapSb2JPo61Nl0NIQ" target="_blank">Cyber Security Professional</a>
* <a href="https://raw.githubusercontent.com/Speedycray/portfolio/main/Security%2B.png" target="_blank">CompTIA Security+ 2021-2024</a>
* <a href="https://badgr.com/public/assertions/wYLDfk1PQUSxuRVRaUuFBA" target="_blank">Basic Computer Skills 2021</a>

<!---
* [CompTIA Network+ 2022-2025](https://raw.githubusercontent.com/Speedycray/portfolio/main//CompTIA%20Network%2B%20ce%20certificate-1.png)
* [Cyber Security Professional](https://badgr.com/public/assertions/W6z9tAapSb2JPo61Nl0NIQ)
* [CompTIA Security+ 2021-2024](https://raw.githubusercontent.com/Speedycray/portfolio/main/Security%2B.png)
* [Basic Computer Skills 2021](https://badgr.com/public/assertions/wYLDfk1PQUSxuRVRaUuFBA)
-->






# [Log4Shell - Java's Log4J](https://nvd.nist.gov/vuln/detail/CVE-2021-44228)
![alt text](pexels-pranjall-kumar-8464466.jpg)


Photo by 
 <a href="https://www.pexels.com/@pranjall-kumar-150768">
   Photo by Pranjall Kumar
 </a> on 
 <a href="https://www.pexels.com/photo/coffee-beans-in-white-ceramic-mug-8464466/">
   Pexels
 </a>
 
Log4Shell is a vulnerability in the Java's Log4j. I hosted an exploit through a webserver with python3, Set up an LDAP listener to point to that server/exploit, and exploited Log4J's JNDI feature within Apache Solr to obtain a reverse powershell from the victim.

### **Reources:**
*  [TryHackMe](https://tryhackme.com/room/solar)
*  [Installing Apache Solr](https://www.youtube.com/watch?v=Km81Zsd7Dx8)
*  [John Hammond Log4J video](https://www.youtube.com/watch?v=7qoPDq41xhQ&t=967s)

### **Skills:** 
*  Set up attacker (Kali) and (Windows) victim virtual machines
*  Installed older version of Java
*  Obfuscated and utilized reverse powershell one-liner
*  Installed Java builder Maven
*  Set up Netcat listener for reverse shell session

### **Results:**
*  Able to open any application through victim's command prompt
*  Opened reverse powershell in attacker machine
*  Implemented [Threatlocker](https://www.threatlocker.com/) security software to stop the reverse shell

# [WiFi Pineapple](https://shop.hak5.org/products/wifi-pineapple)
![alt text](phoenix-han-ZS_RypKo9sk-unsplash.jpg)

Photo by 
  <a href="https://unsplash.com/@phienix_han?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Phoenix Han</a> 
  on 
  <a href="https://unsplash.com/photos/ZS_RypKo9sk">Unsplash</a>
 
Hak5 sells hacker tools and creates content for pentesters and those in cyber security. One of their producs is the WiFi Pineapple. This tool allows a penetration tester to audit the wireless network. It also can be used to perform offensive attacks such as deauthentication and dissassocations, man-in-the-middle, evil twin, and more. In this project I was able to use the WiFi Pineapple to set up an evil twin and captive portal. I would perform dissasociation attack on an access point and having clients associate to the evil twin.

### **Resources:**
* [WiFi Pineapple Documentation](https://docs.hak5.org/wifi-pineapple/)

### **Skills:**
* Set up a WiFi Pineapple
* Learned about deauthentication and dissassociation
* Learned about associating a client using PineAP

### **Result:**
* Kicked off everyone from the network and reassociated them to the WiFi Pineapple to be able to capture credentials in the captive portal.


# Instagram Bot
![alt text](instagram.jpeg)

Photo by <a href="https://unsplash.com/@alexbemore?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Alexander Shatov</a> on <a href="https://unsplash.com/s/photos/instagram?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

From an Instagram page, a user can see a list of "Followers" and "Followings". From the "Followers" list, the user can also see who they do not follow back. However, there is not a way for the user to know who does not follow the user back. I created a bot using Python and Selenium to fix this problem. Selenium is used for automated web-based application testing which was used to open and navigate through instagram. It would create a list of usernames from the "Followers" listing and another list from the "Following" listing. To get the list of usernames that do not follow the user back, both lists are compared to each other. Whatever is in the "Following" listing but not the "Followers" listing, would be the users that do not follow the user back.

### **Reources:**
*  <a href="https://www.youtube.com/watch?v=d2GBO_QjRlo" target="_blank">Building a simple Instagram bot with Python tutorial</a>

### **Skills:** 
*  Python
*  Selenium
*  Automated web-application testing

### **Results:**
*  Successfully created a bot that retrieves the usernames of those who do not follow the user back.

# Sudoku Solver
![alt text](sudoku.jpeg)

Photo by 
  <a href="https://pixabay.com/users/ben_kerckx-69781/">Ben_Kerckx</a> 
  on 
  <a href="https://pixabay.com/images/id-2040676/">Pixabay</a>
 
As a big fan of sudoku, I spent hours solving these puzzles in my free time. This project caught my attention and I enjoyed working on it. Following the tutorial, I used Python to write some functions that checks which cells on the sudoku board are empty, another to check which numbers are valid in the empty cell, and another for backtracking if the board becomes invalid.

### **Resources:**
* <a href="https://www.techwithtim.net/tutorials/python-programming/sudoku-solver-backtracking/">Python Sudoku Solver Tutorial with Backtracking</a>

### **Skills:**
* Python
* Backtracking

### **Result:**
* successfully created a python script that solves a sudoku board using backtracking.

<!---

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
 
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

-->
