---
layout: page
title: Initial Kali Setup
permalink: /kali-setup/
---

**content will go here**

# Udpate the Operating System 

**sudo apt update && apt upgrade -y**

# Useful Software
## mingw-64
**apt-get install mingw-w64 -y**
Program to compile Windows binaries on kali 
**Example:**
*    i686-w64-mingw32-gcc [input file: source] -o [output file: .exe] -lws2_32 
 

gcc-multilib 

apt-get install gcc-multilib -y 

For installing 32 bit linux binaries on 64-bit machine (and vice versa) 

-m32 flag for 32-bit 

-m64 flag for 64-bit 

 

Powercat 

apt install powercat -y 

 

Firefox 

Foxy Proxy - toggle proxy (burp vs none) 

https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/ 

New proxy 

HTTP 

IP 127.0.0.1 

Port 8080 

Wappalyzer - enumerates we server info 

https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/ 

 

impacket 

https://github.com/SecureAuthCorp/impacket 

 

Map share drive 

 

smtp-user-enum 

apt install smtp-user-enum -y 

 

seclists 

sudo apt-get install seclists 

(/usr/share/seclists/) 

https://tools.kali.org/password-attacks/seclists 

 

steghide 

Sudo apt-get install steghide 
