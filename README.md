## Code and exercises from the book "Black Hat Python: Python Programming for Hackers and Pentesters, 2nd Edition", refactored and ported to Python 3 
Examples, source code and exercises from the book "Black Hat Python, 2nd Edition" by Justin Seitz.

![image](https://user-images.githubusercontent.com/57464184/138901408-984413ab-2648-4dbe-b40c-37ac7b59fc63.png)


--------------------------------
### About the book
The book was a watershed publication for NoStarch Press when it came out in 2014. I came to it later than that and was faced with the problem that all the code and examples were written in Python 2.7.<br>

So I set about porting the code to Python 3.<br>

You can find the book on <a href="https://www.amazon.it/Black-Hat-Python-Programming-Pentesters-ebook/dp/B00QL616DW#customerReviews">Amazon</a>,
while the official book page is on <a href="https://nostarch.com/black-hat-python2E#updates">No Starch Press</a>'s website.<br>

You should be able to download the book's source code from here http://www.nostarch.com/download/BHP-Code.zip, as I verified it to be working (June, 2025).<br>


--------------------------------

### Improvement made from the book's code
- Refactoring to Python 3 and code testing (unless otherwise specified)
- Update to PEP8 standards
- Upgraded readability (es. comments, indentation, variable names, file names)
- Update of obsolete methods (es. print -s %)
- Better context management (es. open with, server.close())
- Disregard of unsupported libs
- Minor tweaks and bugs found while testing the code
- Search for additional files requested throughout the book and not provided, or provided at outdated links, and included in individual chapters
- Additional information and resources that I searched for and found useful as I made my way through the book

--------------------------------

### What you'll find in the repo
Chapter summaries and titles are of my own creation. The book uses different titles that aren't always clear and offers no chapter summaries.  Where needed, I have placed a README.md in a given chapter's subdirectory.

#### Chapter 1: Intro
- This is an introductory chapter and it's mostly about installing Linux VM and Python. No coding here.

#### Chapter 2: Networking Basics
- bhp_net.py
- bhp_server.py
- bhp_reverse_ssh_cmd.py
- bhp_ssh_cmd.py
- rforward.py
- tcp_server.py
- tcp_client.py
- tcp_proxy.py
- udp_client.py
- test_rsa.key

#### Chapter 3: Sniffing Tools
- scanner.py
- sniffer.py
- sniffer_ip_header_decode.py
- sniffer_with_icmp.py

#### Chapter 4: Scapy & ARP Poisoning (with an extra flavour of image reco)
- arper.py
- mail_sniffer.py
- pic_carver.py

#### Chapter 5: CMS Brute Force
- content_bruter.py
- joomla_killer.py
- web_app_mapper.py
- wordpress_killer.py

#### Chapter 6: Burp Suite Integrations 
- bhp_bing.py
- bhp_fuzzer.py
- bhp_wordlist.py

#### Chapter 7: GitHub Trojan
- folder structure
- git_trojan.py

#### Chapter 8: Trojan for Windows OS
- keylogger.py
- sandbox_detector.py
- screenshotter.py
- shell_exec.py

#### Chapter 9: Hacking thru Internet Explorer
- cred_server.py
- decryptor.py
- ie_exfil.py
- keygen.py
- mitb.py

#### Chapter 10: Windows Process Monitoring and File Injection
- file_monitor.py
- process_monitor.py

#### Chapter 11: Windows Forensics
- grab_hashes.py
- code_coverage.py
- grab_hashes.py

