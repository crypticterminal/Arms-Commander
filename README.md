# Arms-Commander-Stable
Malware Suite/Menu designed for "Speedy and No-Mistakes Penetration Testing", written in Python 2.7.13 and tested on Kali Linux 4.6, originally intended to only perform the Reconnaissance and Enumeration Stages (it's role is dramatically expanded now). Requires Python 2.7 + Pip + Termcolor Module. All code is entirely free to be used in your own projects. 

# Installation, Type the Following Commands to Easily Install in a Linux Box
1. cd /tmp/
2. git clone https://github.com/tanc7/Arms-Commander
3. cd Arms-Commander/
4. chmod 777 autoInstallLinux.sh dependencyInstall.sh
5. ./dependencyInstall.sh # Required for installation of Python 2.7, and specifically Termcolor Python Module
6. ./autoInstallLinux.sh

ArmsCommander is now able to run from the Terminal or from the Desktop Launcher

# Running Arms Commander for the first time, open a terminal and type
ArmsCommander.py

# Uninstallation Instructions (Removes Desktop Launcher, the Terminal command, and /root/ArmsCommander directory, including log files)
1. cd /root/ArmsCommander
2. chmod 777 uninstall.sh
3. ./uninstall.sh

# Current Capabilities (From the Main Menu)
	#1. Battery One: URL RECON, Recon a webpage, Dig + Nslookup + Fierce DNS + Whois Lookup
	#2. Battery Two: LOCATE WEBAPP WEAKNESSES, Pop a smoke screen by flooding their Intrusion Detection System while simultaneously running a SQLMap and OWASP scanner attack
	#3. Battery Three: IP RECON via Port Scan using NMap and other tools
	#4. Battery Four: STANDARD DEFENSIVE MEASURES, activate Tor and Proxychains, all required monitoring tools
	#5. Battery Five: ANDROID APK MALWARE INJECTION, Inject a Metasploit Meterpreter Payload into a Android APK Installer File.
	#6. Battery Six: ACTVE NETWORK DEFENSES, terminate connections with NGrep and TCPKill, change your MAC address
	#7. Battery Seven: BOOTERS
	#8. Battery Eight: REMOTE EXPLOITATION, Metasploit, MSFVenom, Armitage, Veil-Evasion, Social Engineer Tookit
	#9. Battery Nine: BAD USB ATTACKS, Use the BadUSB Vulnerability to deliver undetectable attacks by thumbdrive
	#10. Battery Ten: Violent Python (From the Book) Working Proof of Concepts (POCs)

# Current Capabilities (Violent Python Menu)
	#1. SSH Server/Client Brute Forcer
	#2. Zip File Password Cracker (Better, Kali APT-Repo Alternative)
	#3. Wireless Network Credit Card Info Sniffer
	#4. Local FTP-Server Credential Sniffer
	#5. Exif Data Fetcher
	#6. Mitnick Attack Reenactment 

# Update History

# Alpha Version 0.0.5

1. Added a portion of still-working exploits as described by the author of Violent Python T.J. O'Connor, including but not limited to, a SSH Bruteforcer and a Credit Card Information Sniffer
2. Added /logs/ folder to save captured credentials

# Alpha Version 0.0.4

1. Added Keystroke Injection/BadUSB Attack Interface
2. Easy inject.bin generator for USB Rubber Duckies from Hak5 Shops
3. Forked in copies of ducky-flasher

# Alpha Version 0.0.3
1. Added the Ruby-based Android APK Malware Injection Module
2. Also forked over the required Java Signing Apps and required keys and certificates
