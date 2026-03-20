# Welcome and enjoy your stay 🥷
 💬 Short summary about me in tech:

## The Journey
I started IT interest around 14 years old, always wanted to create something while at age to create own computer game but didn't know how or where to start.

I did sign up for programming classes outside of formal school education but was very much bored with playing with Scratch, yet Unity3D was too complicated to handle.

Looking for clues where to start I have bought a book "C++ programming fundamentals" by Alex Allain. 

I gave up in this book on "Loops" chapter. I had the knowledge, I had Codeblocks ready but didn't know what to do next. What am I going to loop trough? It was hard to memorize variable types, since I didn't see clear goal of what would we build with that. While book explained those topics great there was huge lack of direction of where you can use them outside of boring console application.

Memorizing how to make a number random made me forget about how to do it next day, while knowledge like unix time was kept in mind.

I then looked for another way to create fun things, I made my first multiplayer online game server and the journey began.

In extremely fast way I looked back at C++ and seen now how data structures, algoritms and basic for, while, do_while loops for what they were useful - I finished the book hungry for more knowledge ending learning Binary Tree alghoritms, what I loved about C++ was the complete control over memory, it depended on YOU if you made your software running well so was easy to understand Linked List or create your own solutions as data structures, etc. Possibilities opened, while we have memory safe-lanaguage Rust now a C++ is complete basics for software engineering and knowledge about computers in general, I would recommend this book after all those years if already build something it is easy to understand a book.

[So I built +18k lines of codes in over +2 years, a multiplayer game online server for me and my friends online to play with](https://github.com/sklawik/szkodnik-rp)
I mastered Pawn scripting language to its limits, while having a +18k lines in one file seems overhelming, it was excellent playground that made me a better developer now.
I learned strong fundamentals of software security, backend validation, network packets, databases (I started from storing all data in files because I wanted to know why would I need a database in first place!) and caching options like Redis. 

It was a matter of time till problems with deployment will happen so they did - it was time to learn Docker, architecture type of OS (x86,x64, ARM) and so much more.

Connecting the script to a website using MariaDB (as MySQL wasn't working well) I could achieve all of that. Learning how to store passwords safely, the salt, the hashes, to treat system memory like a danger zone - exploits were everywhere.

I then went to web dev, completed qualifications in polish education system (INF 03 - mostly web dev, INF04 - mostly software dev like Android Studio).

I always learn something new, I touch new technologies and I'm in constant never learning curve, I found out the best way to keep up good skills is to self host your own infrastructure, as your own Cloud.


Managed to run Cloudflare tunnels from my home Raspberry Pi, setting up WireGuard to VPS I got and while having possibility at a time I could port forward internet traffic from the public to it, every 
solution has their downsides and usually needs each other to work properly, so I did stick with VPS solution for now while looking for better internet provider.


🔭 While setting up RaspberryPi I learned about:
1. RAM management. CGroups, swaps. It was absolutely needed to keep every service and work stable.
2. CertBot, SSL certificates how SSL works, why it is needed and how secure it is, how it encrypts and decrypts traffic and the difference on why we need to use public one instead of self-signed one.
3. SD Cards are... much less durable than I thought - so setting up system to run from USB SSD and use SD Card only as bootloader.
4. RaspberryPI5 has pcie express that handles SSD in more mature, durable way. It has software to download and flash images, even custom ones ( I tried some of those, but drivers for mouse couldn't push me futher)
5. Power Delivery using powerbank so when power outage happens I still have the connection - I used USB internet so it always works 24/7 unless mobile data towers (especialy 5G ones) get blown up by conspiracy theorists).
6. Differences between x64, x86 and arm, amrf, etc. Tools like FEX (translator x64/x86 -> arm), Wine to run Windows apps aswell.
7. Docker for services, for one Raspberry Pi Kubernetes wasn't needed but I see its potential for multiple bare metal machines in a home network.
8. RaspberryPI Hardware - support for transcoding media at basic level, not powerful but enough to play high quality videos and music in VLC player.
9. Browser support - I was suprised that due to Raspberry Pi nature not every feature worked correctly no matter Firefox or Chromium.
10. SSH security. Passwordless, ssh keys. Just like Github does it.
11. Fail2Ban - setting it up so it bans an IP address by reading logs from choosen applications. Excellent tool.
12. Firewall. The simple UFW one.
13. E-mail servers. SMTP, self hosting, problems, reverse DNS and cloud ready solutions. IP reputation and domain name systems.
14. Ollama - simple AI models could run on PI and installation was simple.
15. Dokploy - ready all in one solution so I don't have to manage it all by myself.

As it goes on and on the knowledge followed by experience goes beyond RaspberryPI itself. 

It goes into Cloud direction, so I do understand that Cloud ready solutions, are just like a simple VPS but it has API to use server's resources, like a framework, a library so there is no need to re-invent the wheel. Currently learning AWS. 


I could go so much more but it would be too long for simple summary readme - thank you for your time and maybe tell me what you think  by hitting me up on my website:
https://sklawik.pl

### Currently focused on:

![Cloud](https://img.shields.io/badge/Cloud-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-blue)
![Podman](https://img.shields.io/badge/Podman-blue)
![AWS](https://img.shields.io/badge/AWS-orange)


![Selfhosting](https://img.shields.io/badge/SelfHosting-red) ![Homelab](https://img.shields.io/badge/Homelab-olive) ![Linux](https://img.shields.io/badge/Linux-purple)![Debian](https://img.shields.io/badge/Debian-white) ![PersonalWebsite](https://img.shields.io/badge/sklawik.pl-darkred)


Software & Technologies I know well and some I use on daily basis.

![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)

![Cloudflare](https://img.shields.io/badge/CloudFlare-orange) ![SystemD](https://img.shields.io/badge/SystemD-gray) ![SystemD](https://img.shields.io/badge/SystemD-darkgreen) ![ReverseProxy](https://img.shields.io/badge/ReverseProxy-gray) ![VSCode](https://img.shields.io/badge/VSCode-gray) ![Ubuntu](https://img.shields.io/badge/Ubuntu-darkorange) ![RaspberryPi4](https://img.shields.io/badge/RaspberryPi4-darkgreen)




### 🛡️ Security Highlight: Responsible Disclosure (2025)
In 2025 I found low level vulnerability in Tradler.io website that exposed users personal info in their API while injecting specific attribute values.
I was awarded by the company points I could exchange later in an online shop for rewards. 

The website was used by a company I worked for - Just Eat Takeaway as third party service to collect virtual points and exchange them for physical or digital rewards.
The vulnerability itself exposed data including e-mail addresses, those could be fetched by every single user registered (employee of my company) and then because most users do not change their passwords, I could log in to 2 or more services connected to the company used by mentioned e-mails.

It is not hard to say it was relatively easy for a malicious actor to take a damage using automated scripts - phishing, scamming or data stealing.

What is interesting, the Tradler.io exposed deleted account e-mails of users with special permissions - for example managers that left the company.
By those e-mail addresses, I could log in with default passwords to all other services with special permissions. 

ASAP I did notify my company about the incident, which resulted in extremely fast actions that prevented malicious actors from logging in to any of mentioned special permissions leftovers.
This shows how 1 simple data leak could end up in access to much more services.

This bug was found because I was just curious how API looks in a website my company uses.



