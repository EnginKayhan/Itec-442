# IoT & CYBER SECURITY
## Eportfolio by Engin Kayhan

## LECTURE 1 & 2

**SCANNING ACTIVITY**


### For the **lectures 1 & 2** we did scanning activities by using Command Prompt. The codes we used were;

**ping =** where we use this to see whether a networked device is reachable

![](/screenshots/ping.png)

ipconfig & ipconfig /all = shows all the current TCP/IP network configuration

![](/screenshots/ipconfig.png)

netstat = to retrive all active connections

![](/screenshots/tracert.png)

tracert = trace the path that an IP packet takes to its destination

![](/screenshots/netstat.png)



## LECTURE 2 & 3

### **DIGITALISATION**

**What is a 'fully digital enterprise'?**

A fully digital enterprise is where a business has adopted digital technologies to help improve and smooth-run their business

### **What are the cyber Security challenges/concerns with a fully digital enterprise?**

Phishing scams, cloud attacks, IoT attacks, etc.. Basically cyber-attacks

### **What are the cyber security challenges for a bricks and mortar SME wanting to become a digital enterprise?**

They have a negative impact on company and it will lead to loss in revenue where as recovery may not happen


## LECTURE 3 & 4
 **SOLARWINDS ARTICLE**
***WITH CYBER KILL CHAIN***

**Cyber Kill Chain steps are;**

+ **Reconnaissance;** is the first stage in the Cyber Kill Chain and involves researching potential targets before carrying out any penetration testing. The reconnaissance stage may include identifying potential targets, finding their vulnerabilities, discovering which third parties are connected to them (and what data they can access), and exploring existing entry points as well as finding new ones.

+ **Weaponization;** stage of the Cyber Kill Chain occurs after reconnaissance has taken place and the attacker has discovered all necessary information about potential targets, such as vulnerabilities. In the weaponization stage, all of the attacker’s preparatory work culminates in the creation of malware to be used against an identified target. Weaponization can include creating new types of malware or modifying existing tools to use in a cyberattack. 

+ **Delivery;** in the delivery stage, cyberweapons and other Cyber Kill Chain tools are used to infiltrate a target’s network and reach users. Delivery may involve sending phishing emails containing malware attachments with subject lines that prompt users to click through. Delivery can also take the form of hacking into an organization’s network and exploiting a hardware or software vulnerability to infiltrate it.

+ **Exploitation;** is the stage that follows delivery and weaponization. In the exploitation step of the Cyber Kill Chain, attackers take advantage of the vulnerabilities they have discovered in previous stages to further infiltrate a target’s network and achieve their objectives. In this process, cybercriminals often move laterally across a network to reach their targets. 

+ **Installation;** after cybercriminals have exploited their target’s vulnerabilities to gain access to a network, they begin the installation stage of the Cyber Kill Chain: attempting to install malware and other cyberweapons onto the target network to take control of its systems and exfiltrate valuable data. In this step, cybercriminals may install cyberweapons and malware using Trojan horses, backdoors, or command-line interfaces.

+ **Command & Controll (C2);** in the C2 stage of the Cyber Kill Chain, cybercriminals communicate with the malware they’ve installed onto a target’s network to instruct cyberweapons or tools to carry out their objectives. For example, attackers may use communication channels to direct computers infected with the Mirai botnet malware to overload a website with traffic or C2 servers to instruct computers to carry out cybercrime objectives.

+ **Action on Objectives;** after cybercriminals have developed cyberweapons, installed them onto a target’s network, and taken control of their target’s network, they begin the final stage of the Cyber Kill Chain: carrying out their cyberattack objectives. While cybercriminals’ objectives vary depending on the type of cyberattack, some examples include weaponizing a botnet to interrupt services with a Distributed Denial of Service (DDoS) attack, distributing malware to steal sensitive data from a target organization, and using ransomware as a cyber extortion tool.


## LECTURE 5 & 6

## AAA
### Authentication;
When you logged into this course. When you entered in your email address and your password, you're
making a claim that you are the student and by doing that, you're checked by the system and granted
access.

### Authorization;
When a user is given access to a certain piece of data or certain areas of the building.

### Accountung;
Ensures that tracking of data, computer usage, and network resources is maintained

## Threat Risk Assessment Matrix

| Medium | High | High |
| :---: | :---: | :---: |
| Low | Medium | High |
| Low | Low | Medium |

+ **y-axis = IMPACT & x-axis = LIKELIHOOD**

**FOR IMPACT** (read left to right)

Medium + High + High = High

Low + Medium + High = Medium

Low + Low + Medium = Low

**FOR LIKELIHOOD** (read up to down)

Medium + Low + Low = Low

High + Medium + Low = Medium

High + High + Medium = High

## To better yet "understand" this table we saw an example from 2016 PivotPoint Security where a scenario was given;

 ### What is the impact of the attack on the service and business?
 
1 A low impact could mean, for example, one client service down for half a day

2 A medium impact means service to a residential area could be down for half a day

3 A high impact means service to a business area could be down for half a day

## Kali Linux and VMware 

Due to hardware issues with my **old laptop**, i was not able to fully download and set up Kali Linux so therefore i don't have anything to reflect on other than the exercises we "tried to do" in class.

**Edit: I have received my new laptop ( Tuesday, January 10 2023) but sadly won't be able to download Kali Linux and test some stuff since there is less than an hour left to submit this e-portfolio**

[VMware installation (v15)](https://github.com/EnginKayhan/Itec-442/blob/main/VMware%20step-by-step%20setup.pdf)

## Tools and Description

+ **ipconfig;** presents the user with network configuration information

+ **whois;** is used to find out information regarding ownership, administrative, and technical responsibility

+ **nslookup;** is used in information-gathering process of the ***enumeration phase*** (extracting the names of the user and machine, also the resources of the network) of a cyber attack

+ **ping;** is used for measuring the tound trip time for packets to be sent from the originating host to the target host

+ **traceroute;** used for checking the latency issues between hosts and evaluate the connection to determine where excessive latency exists

+ **secure shell;** used in some network security schemas because it supports tunneling and port forwarding

## For our e-portfolio regarding the lectures 5 & 6 we were given activities to do which were called;

**"Setting up a Honeypot"** where Honey pot is a computer system that we as a user set up a trap for cyber attackers who try to gain unauthorised access to information systems.

**"Implementing port security"** where port security controls how many MAC (media access control) addresses can be learned on a single switch port by using PuTTY (a free open sourcse SSH/Telnet program with small-sized versions that can run on various operating systems).

## LECTURES 6 & 7

In these lectures we dove deep into types of attacks against enterprise networks, attacks being called ***active and passive attacks.*** We also watched a video about man-in-the-middle attacks and later on discussed the details about the attack itself and learned about terms used for attacks such as ***spoofing, ip poisoning, etc...***.

## LECTURES 8 & 9

### IoT and Physical Computing

At week 8 & 9 we dug deeper into IoT and talked about IoT in our day-to-day lives and where we use them. Discussed topics about how & what projects and/or gadgets are usefull to us humans.

Basically IoT Devices are becoming an essential part of our lives mainly because they save us time and pretty agile compared to other 'out of trend' ways of achieving results.

## LECUTES 10 & 11

For this week we looked more in depth explanation for IoT in many places with examples and how these processes take (steps that have to be followed in order for it to be succesfully connected to the cloud or wherever it makes connection, etc...) including Smart Parking Garage and IoT Infrastructure.

Most importantly (at least for me) we had a guest speaker, Babak Reihani. Mr Reihani gave us a presentation about **"The practical aspects/challenges of IoT Operations".**

**More about Mr Reihani:**

[Mr Rehani](https://cy.linkedin.com/in/babak-reihani) has practical experience in design and construction of microcontroller boards and developing them in IoT and smart renewable energy . He is an expert in data analytics with python and modeler software. Also he has experience in designing solar power plants and a PV solar test Lab. He is the director of Smart Rasa Group.

He helps mission-driven organizations leverage the power of IoT and data analytics to maximize their impact. He takes pride in listening to customers' needs and crafting well-architected, innovative, and scalable IoT solutions that help his customers achieve their goals.

He is dedicated to engaging with IoT communities, educating, exciting, and inspiring them to build with and contribute to Smart systems.
He wrote code samples, presented demos, articles, and tutorials that easily communicate the benefits of IoT/Smart  technologies for developers, scientists, and technical decision-makers.
He strongly believes that IoT and Smart systems will help to design a better world.

[***the company's site***](https://www.smart-rg.com/)

Mr Reihani also brought IoT devices with him so that we can examine and better understand how these devices operate. I was curious enough to ask questions about the devices regarding their prices, how they are/were made, if we can edit the codes written inside of the devices, and whether it would be cheaper to make these or buy them.

At the end of the day we gained knowledge and had/still have better knowledge about IoT devices and how they work.

### THIS IS THE END OF MY E-PORTFOLIO FOR ITEC442

#### I would like to personally give my regards to our instructor BERAN TANSELOGLU for his hard work and kindness towards us. We appreciate you and you truly care about your students, thank you!









