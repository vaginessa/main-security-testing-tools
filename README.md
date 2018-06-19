## Contents

* [Penetration Testing Distributions](#penetration-testing-distributions)
* [Docker for Penetration Testing](#docker-for-penetration-testing)
* [Multi-paradigm Frameworks](#multi-paradigm-frameworks)
* [Network Vulnerability scanners](#network-vulnerability-scanners)
  * [Static Analyzers](#static-analyzers)
  * [Web Vulnerability Scanners](#web-vulnerability-scanners)
* [Network Tools](#network-tools)
  * [Exfiltration Tools](#exfiltration-tools)
  * [Network Reconnaissance Tools](#network-reconnaissance-tools)
  * [Protocol Analyzers and Sniffers](#protocol-analyzers-and-sniffers)
  * [Proxies and MITM Tools](#proxies-and-mitm-tools)
* [Wireless Network Tools](#wireless-network-tools)
* [Transport Layer Security Tools](#transport-layer-security-tools)
* [Web Exploitation](#web-exploitation)
* [Hex Editors](#hex-editors)
* [File Format Analysis Tools](#file-format-analysis-tools)
* [Anti-virus Evasion Tools](#anti-virus-evasion-tools)
* [Hash Cracking Tools](#hash-cracking-tools)
* [Windows Utilities](#windows-utilities)
* [GNU/Linux Utilities](#gnulinux-utilities)
* [macOS Utilities](#macos-utilities)
* [DDoS Tools](#ddos-tools)
* [Social Engineering Tools](#social-engineering-tools)
* [OSINT Tools](#osint-tools)
* [Anonymity Tools](#anonymity-tools)
* [Reverse Engineering Tools](#reverse-engineering-tools)
* [Side-channel Tools](#side-channel-tools)
* [CTF Tools](#ctf-tools)

## Tools

### Penetration Testing Distributions

* [Kali](https://www.kali.org/) - GNU/Linux distribution designed for digital forensics and penetration testing.
* [ArchStrike](https://archstrike.org/) - Arch GNU/Linux repository for security professionals and enthusiasts.
* [BlackArch](https://www.blackarch.org/) - Arch GNU/Linux-based distribution for penetration testers and security researchers.
* [Network Security Toolkit (NST)](http://networksecuritytoolkit.org/) - Fedora-based bootable live operating system designed to provide easy access to best-of-breed open source network security applications.
* [BackBox](https://backbox.org/) - Ubuntu-based distribution for penetration tests and security assessments.
* [Parrot](https://www.parrotsec.org/) - Distribution similar to Kali, with multiple architecture.
* [Buscador](https://inteltechniques.com/buscador/) - GNU/Linux virtual machine that is pre-configured for online investigators.
* [Fedora Security Lab](https://labs.fedoraproject.org/en/security/) - Provides a safe test environment to work on security auditing, forensics, system rescue and teaching security testing methodologies.
* [The Pentesters Framework](https://github.com/trustedsec/ptf) - Distro organized around the Penetration Testing Execution Standard (PTES), providing a curated collection of utilities that eliminates often unused toolchains.
* [AttifyOS](https://github.com/adi0x90/attifyos) - GNU/Linux distribution focused on tools useful during Internet of Things (IoT) security assessments.

### Multi-paradigm Frameworks

* [Metasploit](https://www.metasploit.com/) - Software for offensive security teams to help verify vulnerabilities and manage security assessments.
* [Armitage](http://fastandeasyhacking.com/) - Java-based GUI front-end for the Metasploit Framework.
* [Faraday](https://github.com/infobyte/faraday) - Multiuser integrated pentesting environment for red teams performing cooperative penetration tests, security audits, and risk assessments.
* [ExploitPack](https://github.com/juansacco/exploitpack) - Graphical tool for automating penetration tests that ships with many pre-packaged exploits.
* [Pupy](https://github.com/n1nj4sec/pupy) - Cross-platform (Windows, Linux, macOS, Android) remote administration and post-exploitation tool.
* [AutoSploit](https://github.com/NullArray/AutoSploit) - Automated mass exploiter, which collects target by employing the Shodan.io API and programmatically chooses Metasploit exploit modules based on the Shodan query.

### Network Vulnerability Scanners

* [Netsparker Application Security Scanner](https://www.netsparker.com/) - Application security scanner to automatically find security flaws.
* [Nexpose](https://www.rapid7.com/products/nexpose/) - Commercial vulnerability and risk management assessment engine that integrates with Metasploit, sold by Rapid7.
* [Nessus](https://www.tenable.com/products/nessus-vulnerability-scanner) - Commercial vulnerability management, configuration, and compliance assessment platform, sold by Tenable.
* [OpenVAS](http://www.openvas.org/) - Free software implementation of the popular Nessus vulnerability assessment system.
* [Vuls](https://github.com/future-architect/vuls) - Agentless vulnerability scanner for GNU/Linux and FreeBSD, written in Go.

#### Static Analyzers

* [Brakeman](https://github.com/presidentbeef/brakeman) - Static analysis security vulnerability scanner for Ruby on Rails applications.
* [cppcheck](http://cppcheck.sourceforge.net/) - Extensible C/C++ static analyzer focused on finding bugs.
* [FindBugs](http://findbugs.sourceforge.net/) - Free software static analyzer to look for bugs in Java code.
* [sobelow](https://github.com/nccgroup/sobelow) - Security-focused static analysis for the Phoenix Framework.
* [bandit](https://pypi.python.org/pypi/bandit/) - Security oriented static analyser for python code.
* [Progpilot](https://github.com/designsecurity/progpilot) - Static security analysis tool for PHP code.

#### Web Vulnerability Scanners

* [Netsparker Application Security Scanner](https://www.netsparker.com/) - Application security scanner to automatically find security flaws.
* [Nikto](https://cirt.net/nikto2) - Noisy but fast black box web server and web application vulnerability scanner.
* [Arachni](http://www.arachni-scanner.com/) - Scriptable framework for evaluating the security of web applications.
* [w3af](https://github.com/andresriancho/w3af) - Web application attack and audit framework.
* [Wapiti](http://wapiti.sourceforge.net/) - Black box web application vulnerability scanner with built-in fuzzer.
* [SecApps](https://secapps.com/) - In-browser web application security testing suite.
* [WebReaver](https://www.webreaver.com/) - Commercial, graphical web application vulnerability scanner designed for macOS.
* [WPScan](https://wpscan.org/) - Black box WordPress vulnerability scanner.
* [Zoom](https://github.com/UltimateHackers/Zoom) - Powerful wordpress username enumerator with infinite scanning.
* [cms-explorer](https://code.google.com/archive/p/cms-explorer/) - Reveal the specific modules, plugins, components and themes that various websites powered by content management systems are running.
* [joomscan](https://www.owasp.org/index.php/Category:OWASP_Joomla_Vulnerability_Scanner_Project) - Joomla vulnerability scanner.
* [ACSTIS](https://github.com/tijme/angularjs-csti-scanner) - Automated client-side template injection (sandbox escape/bypass) detection for AngularJS.
* [SQLmate](https://github.com/UltimateHackers/sqlmate) - A friend of sqlmap that identifies sqli vulnerabilities based on a given dork and website (optional).


### Network Tools

* [pig](https://github.com/rafael-santiago/pig) - GNU/Linux packet crafting tool.
* [Network-Tools.com](http://network-tools.com/) - Website offering an interface to numerous basic network utilities like `ping`, `traceroute`, `whois`, and more.
* [Intercepter-NG](http://sniff.su/) - Multifunctional network toolkit.
* [SPARTA](https://sparta.secforce.com/) - Graphical interface offering scriptable, configurable access to existing network infrastructure scanning and enumeration tools.
* [Zarp](https://github.com/hatRiot/zarp) - Network attack tool centered around the exploitation of local networks.
* [dsniff](https://www.monkey.org/~dugsong/dsniff/) - Collection of tools for network auditing and pentesting.
* [scapy](https://github.com/secdev/scapy) - Python-based interactive packet manipulation program & library.
* [Printer Exploitation Toolkit (PRET)](https://github.com/RUB-NDS/PRET) - Tool for printer security testing capable of IP and USB connectivity, fuzzing, and exploitation of PostScript, PJL, and PCL printer language features.
* [Praeda](http://h.foofus.net/?page_id=218) - Automated multi-function printer data harvester for gathering usable data during security assessments.
* [routersploit](https://github.com/reverse-shell/routersploit) - Open source exploitation framework similar to Metasploit but dedicated to embedded devices.
* [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) - Swiss army knife for pentesting networks.
* [impacket](https://github.com/CoreSecurity/impacket) - Collection of Python classes for working with network protocols.
* [dnstwist](https://github.com/elceef/dnstwist) - Domain name permutation engine for detecting typo squatting, phishing and corporate espionage.
* [THC Hydra](https://github.com/vanhauser-thc/thc-hydra) - Online password cracking tool with built-in support for many network protocols, including HTTP, SMB, FTP, telnet, ICQ, MySQL, LDAP, IMAP, VNC, and more.

#### Exfiltration Tools

* [DET](https://github.com/sensepost/DET) - Proof of concept to perform data exfiltration using either single or multiple channel(s) at the same time.
* [pwnat](https://github.com/samyk/pwnat) - Punches holes in firewalls and NATs.
* [tgcd](http://tgcd.sourceforge.net/) - Simple Unix network utility to extend the accessibility of TCP/IP based network services beyond firewalls.
* [Iodine](https://code.kryo.se/iodine/) - Tunnel IPv4 data through a DNS server; useful for exfiltration from networks where Internet access is firewalled, but DNS queries are allowed.

#### Network Reconnaissance Tools

* [zmap](https://zmap.io/) - Open source network scanner that enables researchers to easily perform Internet-wide network studies.
* [nmap](https://nmap.org/) - Free security scanner for network exploration & security audits.
* [scanless](https://github.com/vesche/scanless) - Utility for using websites to perform port scans on your behalf so as not to reveal your own IP.
* [DNSDumpster](https://dnsdumpster.com/) - Online DNS recon and search service.
* [CloudFail](https://github.com/m0rtem/CloudFail) - Unmask server IP addresses hidden behind Cloudflare by searching old database records and detecting misconfigured DNS.
* [dnsenum](https://github.com/fwaeytens/dnsenum/) - Perl script that enumerates DNS information from a domain, attempts zone transfers, performs a brute force dictionary style attack, and then performs reverse look-ups on the results.
* [dnsmap](https://github.com/makefu/dnsmap/) - Passive DNS network mapper.
* [dnsrecon](https://github.com/darkoperator/dnsrecon/) - DNS enumeration script.
* [dnstracer](http://www.mavetju.org/unix/dnstracer.php) - Determines where a given DNS server gets its information from, and follows the chain of DNS servers.
* [passivedns-client](https://github.com/chrislee35/passivedns-client) - Library and query tool for querying several passive DNS providers.
* [passivedns](https://github.com/gamelinux/passivedns) - Network sniffer that logs all DNS server replies for use in a passive DNS setup.
* [Mass Scan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
* [smbmap](https://github.com/ShawnDEvans/smbmap) - Handy SMB enumeration tool.
* [XRay](https://github.com/evilsocket/xray) - Network (sub)domain discovery and reconnaissance automation tool.
* [ACLight](https://github.com/cyberark/ACLight) - Script for advanced discovery of sensitive Privileged Accounts - includes Shadow Admins.

#### Protocol Analyzers and Sniffers

* [tcpdump/libpcap](http://www.tcpdump.org/) - Common packet analyzer that runs under the command line.
* [Wireshark](https://www.wireshark.org/) - Widely-used graphical, cross-platform network protocol analyzer.
* [netsniff-ng](https://github.com/netsniff-ng/netsniff-ng) - Swiss army knife for for network sniffing.
* [Dshell](https://github.com/USArmyResearchLab/Dshell) - Network forensic analysis framework.
* [Debookee](http://www.iwaxx.com/debookee/) - Simple and powerful network traffic analyzer for macOS.
* [Dripcap](https://github.com/dripcap/dripcap) - Caffeinated packet analyzer.
* [Netzob](https://github.com/netzob/netzob) - Reverse engineering, traffic generation and fuzzing of communication protocols.

#### Proxies and MITM Tools

* [dnschef](https://github.com/iphelix/dnschef) - Highly configurable DNS proxy for pentesters.
* [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [Morpheus](https://github.com/r00t-3xp10it/morpheus) - Automated ettercap TCP/IP Hijacking tool.
* [mallory](https://github.com/justmao945/mallory) - HTTP/HTTPS proxy over SSH.
* [SSH MITM](https://github.com/jtesta/ssh-mitm) - Intercept SSH connections with a proxy; all plaintext passwords and sessions are logged to disk.
* [evilgrade](https://github.com/infobyte/evilgrade) - Modular framework to take advantage of poor upgrade implementations by injecting fake updates.
* [Ettercap](http://www.ettercap-project.org) - Comprehensive, mature suite for machine-in-the-middle attacks.
* [BetterCAP](https://www.bettercap.org/) - Modular, portable and easily extensible MITM framework.

### Wireless Network Tools

* [Aircrack-ng](http://www.aircrack-ng.org/) - Set of tools for auditing wireless networks.
* [Kismet](https://kismetwireless.net/) - Wireless network detector, sniffer, and IDS.
* [Reaver](https://code.google.com/archive/p/reaver-wps) - Brute force attack against WiFi Protected Setup.
* [Wifite](https://github.com/derv82/wifite) - Automated wireless attack tool.
* [Fluxion](https://github.com/FluxionNetwork/fluxion) - Suite of automated social engineering based WPA attacks.

### Transport Layer Security Tools

* [SSLyze](https://github.com/nabla-c0d3/sslyze) - Fast and comprehensive TLS/SSL configuration analyzer to help identify security mis-configurations.
* [tls_prober](https://github.com/WestpointLtd/tls_prober) - Fingerprint a server's SSL/TLS implementation.
* [testssl.sh](https://github.com/drwetter/testssl.sh) - Command line tool which checks a server's service on any port for the support of TLS/SSL ciphers, protocols as well as some cryptographic flaws.
* [crackpkcs12](https://github.com/crackpkcs12/crackpkcs12) - Multithreaded program to crack PKCS#12 files (`.p12` and `.pfx` extensions), such as TLS/SSL certificates.

### Web Exploitation

* [OWASP Zed Attack Proxy (ZAP)](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - Feature-rich, scriptable HTTP intercepting proxy and fuzzer for penetration testing web applications.
* [Fiddler](https://www.telerik.com/fiddler) - Free cross-platform web debugging proxy with user-friendly companion tools.
* [Burp Suite](https://portswigger.net/burp/) - Integrated platform for performing security testing of web applications.
* [autochrome](https://www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2017/march/autochrome/) - Easy to install a test browser with all the appropriate setting needed for web application testing with native Burp support, from NCCGroup.
* [Browser Exploitation Framework (BeEF)](https://github.com/beefproject/beef) - Command and control server for delivering exploits to commandeered Web browsers.
* [Offensive Web Testing Framework (OWTF)](https://www.owasp.org/index.php/OWASP_OWTF) - Python-based framework for pentesting Web applications based on the OWASP Testing Guide.
* [Wordpress Exploit Framework](https://github.com/rastating/wordpress-exploit-framework) - Ruby framework for developing and using modules which aid in the penetration testing of WordPress powered websites and systems.
* [WPSploit](https://github.com/espreto/wpsploit) - Exploit WordPress-powered websites with Metasploit.
* [SQLmap](http://sqlmap.org/) - Automatic SQL injection and database takeover tool.
* [tplmap](https://github.com/epinna/tplmap) - Automatic server-side template injection and Web server takeover tool.
* [weevely3](https://github.com/epinna/weevely3) - Weaponized web shell.
* [Wappalyzer](https://www.wappalyzer.com/) - Wappalyzer uncovers the technologies used on websites.
* [WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Website fingerprinter.
* [BlindElephant](http://blindelephant.sourceforge.net/) - Web application fingerprinter.
* [wafw00f](https://github.com/EnableSecurity/wafw00f) - Identifies and fingerprints Web Application Firewall (WAF) products.
* [fimap](https://github.com/kurobeats/fimap) - Find, prepare, audit, exploit and even Google automatically for LFI/RFI bugs.
* [Kadabra](https://github.com/D35m0nd142/Kadabra) - Automatic LFI exploiter and scanner.
* [Kadimus](https://github.com/P0cL4bs/Kadimus) - LFI scan and exploit tool.
* [liffy](https://github.com/hvqzao/liffy) - LFI exploitation tool.
* [Commix](https://github.com/commixproject/commix) - Automated all-in-one operating system command injection and exploitation tool.
* [DVCS Ripper](https://github.com/kost/dvcs-ripper) - Rip web accessible (distributed) version control systems: SVN/GIT/HG/BZR.
* [GitTools](https://github.com/internetwache/GitTools) - Automatically find and download Web-accessible `.git` repositories.
* [sslstrip](https://www.thoughtcrime.org/software/sslstrip/) - Demonstration of the HTTPS stripping attacks.
* [sslstrip2](https://github.com/LeonardoNve/sslstrip2) - SSLStrip version to defeat HSTS.
* [NoSQLmap](http://nosqlmap.net/) - Automatic NoSQL injection and database takeover tool.
* [VHostScan](https://github.com/codingo/VHostScan) - A virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, aliases and dynamic default pages.
* [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) - Dictionary of attack patterns and primitives for black-box application fault injection and resource discovery.
* [EyeWitness](https://github.com/ChrisTruncer/EyeWitness) - Tool to take screenshots of websites, provide some server header info, and identify default credentials if possible.
* [webscreenshot](https://github.com/maaaaz/webscreenshot) - A simple script to take screenshots of list of websites.

### Hex Editors

* [HexEdit.js](https://hexed.it) - Browser-based hex editing.
* [Hexinator](https://hexinator.com/) - World's finest (proprietary, commercial) Hex Editor.
* [Frhed](http://frhed.sourceforge.net/) - Binary file editor for Windows.
* [0xED](http://www.suavetech.com/0xed/0xed.html) - Native macOS hex editor that supports plug-ins to display custom data types.
* [Hex Fiend](http://ridiculousfish.com/hexfiend/) - Fast, open source, hex editor for macOS with support for viewing  binary diffs.

### File Format Analysis Tools

* [Kaitai Struct](http://kaitai.io/) - File formats and network protocols dissection language and web IDE, generating parsers in C++, C#, Java, JavaScript, Perl, PHP, Python, Ruby.
* [Veles](https://codisec.com/veles/) - Binary data visualization and analysis tool.
* [Hachoir](http://hachoir3.readthedocs.io/) - Python library to view and edit a binary stream as tree of fields and tools for metadata extraction.

### Anti-virus Evasion Tools

* [Veil](https://www.veil-framework.com/) - Generate metasploit payloads that bypass common anti-virus solutions.
* [shellsploit](https://github.com/Exploit-install/shellsploit-framework) - Generates custom shellcode, backdoors, injectors, optionally obfuscates every byte via encoders.
* [Hyperion](http://nullsecurity.net/tools/binary.html) - Runtime encryptor for 32-bit portable executables ("PE `.exe`s").
* [AntiVirus Evasion Tool (AVET)](https://github.com/govolution/avet) - Post-process exploits containing executable files targeted for Windows machines to avoid being recognized by antivirus software.
* [peCloak.py](https://www.securitysift.com/pecloak-py-an-experiment-in-av-evasion/) - Automates the process of hiding a malicious Windows executable from antivirus (AV) detection.
* [peCloakCapstone](https://github.com/v-p-b/peCloakCapstone) - Multi-platform fork of the peCloak.py automated malware antivirus evasion tool.
* [UniByAv](https://github.com/Mr-Un1k0d3r/UniByAv) - Simple obfuscator that takes raw shellcode and generates Anti-Virus friendly executables by using a brute-forcable, 32-bit XOR key.
* [Shellter](https://www.shellterproject.com/) - Dynamic shellcode injection tool, and the first truly dynamic PE infector ever created.

### Hash Cracking Tools

* [John the Ripper](http://www.openwall.com/john/) - Fast password cracker.
* [Hashcat](http://hashcat.net/hashcat/) - The more fast hash cracker.
* [CeWL](https://digi.ninja/projects/cewl.php) - Generates custom wordlists by spidering a target's website and collecting unique words.
* [JWT Cracker](https://github.com/lmammino/jwt-cracker) - Simple HS256 JWT token brute force cracker.
* [Rar Crack](http://rarcrack.sourceforge.net) - RAR bruteforce cracker.
* [BruteForce Wallet](https://github.com/glv2/bruteforce-wallet) - Find the password of an encrypted wallet file (i.e. `wallet.dat`).

### Windows Utilities

* [Sysinternals Suite](https://technet.microsoft.com/en-us/sysinternals/bb842062) - The Sysinternals Troubleshooting Utilities.
* [Windows Credentials Editor](http://www.ampliasecurity.com/research/windows-credentials-editor/) - Inspect logon sessions and add, change, list, and delete associated credentials, including Kerberos tickets.
* [mimikatz](http://blog.gentilkiwi.com/mimikatz) - Credentials extraction tool for Windows operating system.
* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - PowerShell Post-Exploitation Framework.
* [Windows Exploit Suggester](https://github.com/GDSSecurity/Windows-Exploit-Suggester) - Detects potential missing patches on the target.
* [Responder](https://github.com/SpiderLabs/Responder) - LLMNR, NBT-NS and MDNS poisoner.
* [Bloodhound](https://github.com/adaptivethreat/Bloodhound/wiki) - Graphical Active Directory trust relationship explorer.
* [Empire](https://www.powershellempire.com/) - Pure PowerShell post-exploitation agent.
* [Fibratus](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel.
* [wePWNise](https://labs.mwrinfosecurity.com/tools/wepwnise/) - Generates architecture independent VBA code to be used in Office documents or templates and automates bypassing application control and exploit mitigation software.
* [redsnarf](https://github.com/nccgroup/redsnarf) - Post-exploitation tool for retrieving password hashes and credentials from Windows workstations, servers, and domain controllers.
* [Magic Unicorn](https://github.com/trustedsec/unicorn) - Shellcode generator for numerous attack vectors, including Microsoft Office macros, PowerShell, HTML applications (HTA), or `certutil` (using fake certificates).
* [DeathStar](https://github.com/byt3bl33d3r/DeathStar) - Python script that uses Empire's RESTful API to automate gaining Domain Admin rights in Active Directory environments.

### GNU/Linux Utilities

* [Linux Exploit Suggester](https://github.com/PenturaLabs/Linux_Exploit_Suggester) - Heuristic reporting on potentially viable exploits for a given GNU/Linux system.

### macOS Utilities

* [Bella](https://github.com/Trietptm-on-Security/Bella) - Pure Python post-exploitation data mining and remote administration tool for macOS.

### DDoS Tools

* [LOIC](https://github.com/NewEraCracker/LOIC/) - Open source network stress tool for Windows.
* [JS LOIC](http://metacortexsecurity.com/tools/anon/LOIC/LOICv1.html) - JavaScript in-browser version of LOIC.
* [SlowLoris](https://github.com/gkbrk/slowloris) - DoS tool that uses low bandwidth on the attacking side.
* [HOIC](https://sourceforge.net/projects/high-orbit-ion-cannon/) - Updated version of Low Orbit Ion Cannon, has 'boosters' to get around common counter measures.
* [T50](https://sourceforge.net/projects/t50/) - Faster network stress tool.
* [UFONet](https://github.com/epsylon/ufonet) - Abuses OSI layer 7 HTTP to create/manage 'zombies' and to conduct different attacks using; `GET`/`POST`, multithreading, proxies, origin spoofing methods, cache evasion techniques, etc.
* [Memcrashed](https://github.com/649/Memcrashed-DDoS-Exploit) - DDoS attack tool for sending forged UDP packets to vulnerable Memcached servers obtained using Shodan API.

### Social Engineering Tools

* [Social Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit) - Open source pentesting framework designed for social engineering featuring a number of custom attack vectors to make believable attacks quickly.
* [King Phisher](https://github.com/securestate/king-phisher) - Phishing campaign toolkit used for creating and managing multiple simultaneous phishing attacks with custom email and server content.
* [Evilginx](https://github.com/kgretzky/evilginx) - MITM attack framework used for phishing credentials and session cookies from any Web service.
* [wifiphisher](https://github.com/sophron/wifiphisher) - Automated phishing attacks against WiFi networks.
* [Catphish](https://github.com/ring0lab/catphish) - Tool for phishing and corporate espionage written in Ruby.
* [Beelogger](https://github.com/4w4k3/BeeLogger) - Tool for generating keylooger.

### OSINT Tools

* [Maltego](http://www.paterva.com/web7/) - Proprietary software for open source intelligence and forensics, from Paterva.
* [theHarvester](https://github.com/laramies/theHarvester) - E-mail, subdomain and people names harvester.
* [creepy](https://github.com/ilektrojohn/creepy) - Geolocation OSINT tool.
* [metagoofil](https://github.com/laramies/metagoofil) - Metadata harvester.
* [Google Hacking Database](https://www.exploit-db.com/google-hacking-database/) - Database of Google dorks; can be used for recon.
* [Google-dorks](https://github.com/JohnTroony/Google-dorks) - Common Google dorks and others you probably don't know.
* [GooDork](https://github.com/k3170makan/GooDork) - Command line Google dorking tool.
* [dork-cli](https://github.com/jgor/dork-cli) - Command line Google dork tool.
* [Censys](https://www.censys.io/) - Collects data on hosts and websites through daily ZMap and ZGrab scans.
* [Shodan](https://www.shodan.io/) - World's first search engine for Internet-connected devices.
* [recon-ng](https://bitbucket.org/LaNMaSteR53/recon-ng) - Full-featured Web Reconnaissance framework written in Python.
* [github-dorks](https://github.com/techgaun/github-dorks) - CLI tool to scan github repos/organizations for potential sensitive information leak.
* [vcsmap](https://github.com/melvinsh/vcsmap) - Plugin-based tool to scan public version control systems for sensitive information.
* [Spiderfoot](http://www.spiderfoot.net/) - Multi-source OSINT automation tool with a Web UI and report visualizations
* [BinGoo](https://github.com/Hood3dRob1n/BinGoo) - GNU/Linux bash based Bing and Google Dorking Tool.
* [fast-recon](https://github.com/DanMcInerney/fast-recon) - Perform Google dorks against a domain.
* [snitch](https://github.com/Smaash/snitch) - Information gathering via dorks.
* [Sn1per](https://github.com/1N3/Sn1per) - Automated Pentest Recon Scanner.
* [Threat Crowd](https://www.threatcrowd.org/) - Search engine for threats.
* [Virus Total](https://www.virustotal.com/) - Free service that analyzes suspicious files and URLs and facilitates the quick detection of viruses, worms, trojans, and all kinds of malware.
* [PacketTotal](https://packettotal.com/) - Simple, free, high-quality packet capture file analysis facilitating the quick detection of network-borne malware (using Bro and Suricata IDS signatures under the hood).
* [DataSploit](https://github.com/upgoingstar/datasploit) - OSINT visualizer utilizing Shodan, Censys, Clearbit, EmailHunter, FullContact, and Zoomeye behind the scenes.
* [AQUATONE](https://github.com/michenriksen/aquatone) - Subdomain discovery tool utilizing various open sources producing a report that can be used as input to other tools.
* [Intrigue](http://intrigue.io) - Automated OSINT & Attack Surface discovery framework with powerful API, UI and CLI.
* [ZoomEye](https://www.zoomeye.org/) - Search engine for cyberspace that lets the user find specific network components.
* [gOSINT](https://github.com/Nhoya/gOSINT) - OSINT tool with multiple modules and a telegram scraper.
* [Amass](https://github.com/caffix/amass) - Subdomain enumeration via scraping, web archives, brute forcing, permutations, reverse DNS sweeping, TLS certificates, passive DNS data sources, etc.

### Anonymity Tools

* [Tor](https://www.torproject.org/) - Free software and onion routed overlay network that helps you defend against traffic analysis.
* [OnionScan](https://onionscan.org/) - Tool for investigating the Dark Web by finding operational security issues introduced by Tor hidden service operators.
* [I2P](https://geti2p.net/) - The Invisible Internet Project.
* [Nipe](https://github.com/GouveaHeitor/nipe) - Script to redirect all traffic from the machine to the Tor network.
* [What Every Browser Knows About You](http://webkay.robinlinus.com/) - Comprehensive detection page to test your own Web browser's configuration for privacy and identity leaks.

### Reverse Engineering Tools

* [Interactive Disassembler (IDA Pro)](https://www.hex-rays.com/products/ida/) - Proprietary multi-processor disassembler and debugger for Windows, GNU/Linux, or macOS; also has a free version, [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware.shtml).
* [WDK/WinDbg](https://msdn.microsoft.com/en-us/windows/hardware/hh852365.aspx) - Windows Driver Kit and WinDbg.
* [OllyDbg](http://www.ollydbg.de/) - x86 debugger for Windows binaries that emphasizes binary code analysis.
* [Radare2](http://rada.re/r/index.html) - Open source, crossplatform reverse engineering framework.
* [x64dbg](http://x64dbg.com/) - Open source x64/x32 debugger for windows.
* [Immunity Debugger](http://debugger.immunityinc.com/) - Powerful way to write exploits and analyze malware.
* [Evan's Debugger](http://www.codef00.com/projects#debugger) - OllyDbg-like debugger for GNU/Linux.
* [Medusa](https://github.com/wisk/medusa) - Open source, cross-platform interactive disassembler.
* [plasma](https://github.com/joelpx/plasma) - Interactive disassembler for x86/ARM/MIPS. Generates indented pseudo-code with colored syntax code.
* [peda](https://github.com/longld/peda) - Python Exploit Development Assistance for GDB.
* [dnSpy](https://github.com/0xd4d/dnSpy) - Tool to reverse engineer .NET assemblies.
* [binwalk](https://github.com/devttys0/binwalk) - Fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images.
* [PyREBox](https://github.com/Cisco-Talos/pyrebox) - Python scriptable Reverse Engineering sandbox by Cisco-Talos.
* [Voltron](https://github.com/snare/voltron) - Extensible debugger UI toolkit written in Python.
* [Capstone](http://www.capstone-engine.org/) - Lightweight multi-platform, multi-architecture disassembly framework.
* [rVMI](https://github.com/fireeye/rVMI) - Debugger on steroids; inspect userspace processes, kernel drivers, and preboot environments in a single tool.
* [Frida](https://www.frida.re/) - Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.

### Side-channel Tools

* [ChipWhisperer](http://chipwhisperer.com) - Complete open-source toolchain for side-channel power analysis and glitching attacks.

### CTF Tools

* [ctf-tools](https://github.com/zardus/ctf-tools) - Collection of setup scripts to install various security research tools easily and quickly deployable to new machines.
* [Pwntools](https://github.com/Gallopsled/pwntools) - Rapid exploit development framework built for use in CTFs.
* [RsaCtfTool](https://github.com/sourcekris/RsaCtfTool) - Decrypt data enciphered using weak RSA keys, and recover private keys from public keys using a variety of automated attacks.


# License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).