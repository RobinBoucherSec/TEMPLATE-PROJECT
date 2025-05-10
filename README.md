## 🎯 Title / Project Name


## 📝 Description
My goal was to become familiar with the fundamentals of network scanning and understand how to interpret Nmap output. I wanted to gain hands-on experience in identifying active systems and open services, which are crucial first steps in penetration testing and network security assessments.

## 🔧 Tools Used
List the tools, platforms, and software involved:

Nmap
Wireshark (optional)
Kali Linux
VirtualBox (if used)

## 💡 Skills Learned
What new skills or knowledge did you gain from this project?

Understanding of basic network scanning techniques
Familiarity with interpreting Nmap output
Improved ability to assess network security posture
Practice setting up a secure lab environment

## ⚙️ Steps Taken
Describe step-by-step how you completed the project. You can use bullet points or numbered lists.

Set up a test lab environment using VirtualBox and Kali Linux.
Identified the target IP range.
Ran an initial ping scan to detect live hosts:
bash


1
nmap -sn 192.168.1.0/24
Performed a service/version scan on active hosts:
bash


1
nmap -sV 192.168.1.10
Exported the scan results for further analysis.
📸 Screenshots
You can include screenshots like this (replace the placeholder links):

markdown


1
![Nmap Scan Output](screenshots/nmap-scan.png)
If you're using external images from Imgur or another source:

markdown


1
![Wireshark Capture](https://i.imgur.com/example-image-link.png )


## 🔙 Back to Portfolio
[⬅️ Back to my Cybersecurity Portfolio](https://github.com/RobinBoucherSec/RobinBoucherSec)
