# HackTheBox-Meow

### **Introduction:** It is a CTF-based machine on the HackTheBox platform. The machine is powered by Linux. This machine focuses on Telnet, protocols, reconnaissance, weak credentials, and misconfiguration.


![ss](https://github.com/sayan-125/HackTheBox-Meow/assets/158836588/989ecc30-6267-4bd8-91c4-7ac1f1678b14)

## **Step 1:** Spawn the target machine

	Q1> What does the acronym VM stand for?
	Ans: Virtual Machine
	
	Q2> What tool do we use to interact with the operating system in order to issue commands via the command line, such as the one to start our VPN connection? It's also known as a console or shell.
	Ans: terminal
	
	Q3> What service do we use to form our VPN connection into HTB labs?
	Ans: openvpn
	
	Q4> What tool do we use to test our connection to the target with an ICMP echo request?
	Ans: ping

## **Step 2:** Scan Nmap.

	sudo nmap -sS -sV -sC -A -p- -T4 <ip>

![ss1](https://github.com/sayan-125/HackTheBox-Meow/assets/158836588/7e6831bc-5abc-4127-8897-45ab1af29a22)

	Q5> What is the name of the most common tool for finding open ports on a target?
	Ans: Nmap
	
	Q6> What service do we identify on port 23/tcp during our scans?
	Ans: telnet

## **Step 3:** Login target Machine using telnet.

	telnet <ip>
	Meow login: root

![ss2](https://github.com/sayan-125/HackTheBox-Meow/assets/158836588/09dd3346-93e5-4dc3-8736-1d01f573f444)

	Q7> What username is able to log into the target over telnet with a blank password?
	Ans: root

## **Step 4:** Open flag.txt.

	ls
	cat flag.txt

![ss3](https://github.com/sayan-125/HackTheBox-Meow/assets/158836588/3771c4a4-1e9a-4a9a-b6e2-a2d74d729bbf)

	Q8> Submit root flag
	Ans: b40abdfe23665f766f9c61ecba8a4c19

