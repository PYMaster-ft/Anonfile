# Starting in cybersecurity?

You are looking to start a technical career in infosec or cyber? You are curious about how things work and have thirst in learning new skills? Great! Let’s get started then 😉

![](https://telegra.ph/file/373a8b28415f7bab4f1e2.jpg)

## First thing first

A true computer hacker is someone able to develop its own tools in an elegant way. Unlike the script-kiddies — that by definition are just kids using other people’s scripts — a talented hacker must 1) comprehend what a script/tool is doing and how it basically works 2) able to develop its own tools when needed and first and foremost 3) understand the basics of IT: do you know how a computer is generally working? This is not that easy to be honest. Could you list what are the network stacks used in modern computing? You should definitely look it up and learn the basics, otherwise you’ll get overwhelmed looking at security specific topics.

That is why, before doing anything «security» related (pentesting, bug hunting, reverse engineering, etc.) I highly recommend knowing the basics: learn computer programming. Learn C, Python and x86 (in that order or not).

C is the mother of all native languages, with its strength and weaknesses. Linux is built in C. Windows kernel is built in C. And C is the natural introduction to its big brother C++ on which a lot of software rely on (userland Windows for example). I strongly advise you to learn C, you just cannot ignore how widespread it is.

Python is the most important scripting language in the community and one of the most rapidly growing programming language (see image below). It has a lot of interesting modules already ready for you to enjoy. It’s very handy to write quick PoCs and most people in the community will understand Python. Alternatively you can learn Ruby that is also very much used (ie. Metasploit framework): pick your poison.


![](https://telegra.ph/file/80b8cc35bc9910f205486.png)


Finally, x86/x64 Intel assembly is a must-have if you want to know the basics of reverse engineering. Nowadays very few people actually code in assembly code, but native compiled code can be reverted in assembly code… which you might want to understand to reverse and understand binary files (executables).

You don’t need to master these three languages, but at the very least be familiar with them. There are plenty of decent tutorials that you can find on Google.

## Learning resources
Here is a curated list of awesome information security resources with tons of courses and links:
- [Massive Online Open Courses](https://rentry.co/chamindux-02)

Name  |  Description
----  |  ----
[CS 642: Intro to Computer Security](http://pages.cs.wisc.edu/~ace/cs642-spring-2016.html) | academic content, full semester course, includes assigned readings, homework and github refs for exploit examples. NO VIDEO LECTURES.
[CyberSec WTF](https://cybersecurity.wtf) | CyberSec WTF Web Hacking Challenges from Bounty write-ups
[Cybrary](https://www.cybrary.it/) | coursera style website, lots of user-contributed content, account required, content can be filtered by experience level
[Free Cyber Security Training](https://www.samsclass.info/) | Academic content, 8 full courses with videos from a quirky instructor sam, links to research, defcon materials and other recommended training/learning
[Hak5](https://www.hak5.org/) | podcast-style videos covering various topics, has a forum, "metasploit-minute" video series could be useful
[Hopper's Roppers Security Training](https://hoppersroppers.org/training.html) | Four free self-paced courses on Computing Fundamentals, Security, Capture the Flags, and a Practical Skills Bootcamp that help beginners build a strong base of foundational knowledge. Designed to prepare for students for whatever they need to learn next.
[Learning Exploitation with Offensive Computer Security 2.0](http://howto.hackallthethings.com/2016/07/learning-exploitation-with-offensive.html) | blog-style instruction, includes: slides, videos, homework, discussion. No login required.
[Mind Maps](http://www.amanhardikar.com/mindmaps.html) |   Information Security related Mind Maps
[MIT OCW 6.858 Computer Systems Security](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-858-computer-systems-security-fall-2014/) | academic content, well organized, full-semester course, includes assigned readings, lectures, videos, required lab files.
[OffensiveComputerSecurity](https://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html) | academic content, full semester course including 27 lecture videos with slides and assign readings
[OWASP top 10 web security risks](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project) | free courseware, requires account
[SecurityTube](http://www.securitytube.net/) | tube-styled content, "megaprimer" videos covering various topics, no readable content on site.
[Seed Labs](http://www.cis.syr.edu/~wedu/seed/labs.html) | academic content, well organized, featuring lab videos, tasks, needed code files, and recommended readings
[TryHackMe](https://tryhackme.com/) | Designed prebuilt challenges which include virtual machines (VM) hosted in the cloud ready to be deployed


## Recommended books
So now, do you want to get into malware research and reverse engineering? Pentesting? Or web application security? Maybe the most difficult thing to do, is to choose a starting topic. You cannot master all the things — so pick the one you like the most and start with this.

If you’re more into vulnerability research (memory bugs, buffer overflows, etc.), this book is the reference and a great starter:
- [Hacking: The Art of Exploitation, 2nd Edition](https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441/)

If you’d rather reverse engineer malware and understand their inner working, Malware Analyst’s Cookbook is also a great start:
- [Malware Analyst's Cookbook and DVD: Tools and Techniques for Fighting Malicious Code](https://www.amazon.com/Malware-Analysts-Cookbook-DVD-Techniques/dp/0470613033/ref=sr_1_3?ie=UTF8&qid=1506068910&sr=8-3&keywords=malware+analysis)

If you’re more familiar with web technologies (HTML, JavaScript, CSS) and want to master the security aspects of web browsers:
- [The Tangled Web: A Guide to Securing Modern Web Applications](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886/ref=sr_1_1?s=books&ie=UTF8&qid=1506069161&sr=1-1&keywords=tangled+web+security)

## Certifications

I personally think most certifications are useless. If you need a certification to work at {Cool Company Inc.}, their hiring process is broken and they should know better.
If you really need (or want) one certification, I’m willing to endorse OSCP which is fairly advanced and well known. Also get certificate like CISSP, CISA. Forget about CEH and all other expensive EC-Council crap certifications.
