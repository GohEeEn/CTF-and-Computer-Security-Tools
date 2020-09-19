# CTF-and-Computer-Security-Tools

List of tools & libraries that I have learn and use for [Capture-The-Flags (CTFs)](https://dev.to/atan/what-is-ctf-and-how-to-get-started-3f04) & Computer Security Learning

## DISCLAIMER : Some of the tools below could damage personal and public properties, which may leads to illegal activities (especially in Network & Web sections). Thus, only educational and legally-permitted use

> **The difference of white-hat and black-hat is only their ethicity and legality** <br/>
> **&#45; Unknown**

Educational & permitted platforms I have been practising on :

- [TryHackMe](https://tryhackme.com/)
- [HackTheBox](https://www.hackthebox.eu/)
- [VulnHub](https://www.vulnhub.com/)
- [Hacker101](https://www.hacker101.com/)
- And Capture-The-Flag competitions (Checkout their **rules** before using)

## Cryptography

| No. | Tool       | Homepage                                 | Description                                                                                           |
| --- | ---------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| 1.  | Cyberchef  | <https://gchq.github.io/CyberChef/>      | The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis        |
| 2.  | Dcode      | <https://www.dcode.fr/>                  | For decrypting various kind of uncommon encoding  methods                                             |
| 3.  | xortool    | <https://github.com/hellman/xortool>     |                                                                                                       |
| 4.  | Esolang    | <https://esolangs.org/wiki/Main_Page>    | Information about Esoteric programming language, like brainfuck                                       |
| 5.  | Cryptii    | <https://cryptii.com/>                   |                                                                                                       |
| 6.  | RsaCTFTool | <https://github.com/Ganapati/RsaCtfTool> | Instant RSA Encryption Decryptor, work better with basic knowledge of RSA, Sage Math package required |
| 7.  | Cryptool   | <https://www.cryptool.org/en/>           |                                                                                                       |

## Password Cracking

| No. | Tool            | Homepage                                     | Description                                                                          |
| --- | --------------- | -------------------------------------------- | ------------------------------------------------------------------------------------ |
| 1.  | Hashcat         | <https://hashcat.net/hashcat/>               |                                                                                      | A local password cracker with support on tons of encryption methods, and both CPU & GPU-powered to enhance the cracking speed |
| 2.  | John The Ripper | <https://www.openwall.com/john/>             |                                                                                      | An Open Source password security auditing and password recovery tool available for many operating systems                     |
| 3.  | md5hashing      | <https://md5hashing.net/>                    | Hash cracking based on database record                                               |
| 4.  | Hydra           | <https://github.com/vanhauser-thc/thc-hydra> | An online login password cracker that supports on multiple protocols, eg. HTTP & SSH |

## Forensics

| No. | Tool           | Homepage                                | Description                                                                                       |
| --- | -------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 1.  | Binwalk        | <https://github.com/ReFirmLabs/binwalk> | Used for analyzing, reverse engineering, and extracting firmware imagestool                       |
| 2.  | Foremost       | <https://github.com/korczis/foremost>   | A console program to recover files based on their headers, footers, and internal data structures. |
| 3.  | Exiftool       | <https://exiftool.org/>                 | Perl library & CLI to read, write and edit meta information in a wide variety of file formats     |
| 4.  | Volatility     | <https://www.volatilityfoundation.org/> | An Open Source Memory Forensics Framework                                                         |
| 5.  | Strings        |                                         |                                                                                                   |
| 6.  | The Sleuth Kit | <https://sleuthkit.org/sleuthkit/>      | A library and collection of command line tools that allow you to investigate disk images          |
| 7.  | HexEditor      |                                         |                                                                                                   |
| 8.  | Autopsy        | <https://www.autopsy.com/download/>     | An Open Source forensics platform for analyzing all types of mobile devices and digital media     |

## Reverse Engineering

| No. | Tool      | Homepage                                                       | Description                                           |
| --- | --------- | -------------------------------------------------------------- | ----------------------------------------------------- |
| 1.  | Ghidra    | <https://ghidra-sre.org/>                                      | Written in Java & C++, JDK v11+ required              |
| 2.  | GDB       | <http://www.gnu.org/software/gdb/download/>                    |                                                       |
| 3.  | IDA Pro   | <https://www.hex-rays.com/products/ida/support/download.shtml> | Multi-purpose, payment required                       |
| 4.  | radare2   | <http://www.radare.org/y/?p=download>                          | Unix-like RE framework * CLI                          |
| 5.  | Apktool   | <https://ibotpeaches.github.io/Apktool/>                       | Andriod RE apk files                                  |
| 6.  | Cutter    | <https://cutter.re/>                                           | GUI version of radare2, written in Python             |
| 7.  | Hopper    | <https://www.hopperapp.com/>                                   | Analyse IPA files, ie. iOS application files          |
| 8.  | plistutil | <https://github.com/libimobiledevice/libplist>                 | C library to handle Apple .plist files in XML format. |
| 9.  | dex2jar   | <https://github.com/pxb1988/dex2jar>                           | Tools to work with android .dex and java .class files |
| 10. | jd-gui    | <https://java-decompiler.github.io/>                           | A Java decompiler with GUI, worked with JAR files     |

## Web

| No. | Tool       | Homepage                       | Description                                                                     |
| --- | ---------- | ------------------------------ | ------------------------------------------------------------------------------- |
| 1.  | Burp Suite | <https://portswigger.net/burp> | Community Edition should be enough                                              |
| 2.  | OWASP ZAP  | <https://www.zaproxy.org/>     | Same use as Burp while maintained by OWASP, while different in certain features |

## Networking

| No. | Tool        | Homepage                            | Description                                                                                                                                                                                                   |
| --- | ----------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.  | Wireshark   | <https://www.wireshark.org/>        | An Open Source network & packet analyzer                                                                                                                                                                      |
| 2.  | tcpdump     | <https://www.tcpdump.org/>          | Command-line packet analyzer                                                                                                                                                                                  |
| 3.  | netcat      | <https://sectools.org/tool/netcat/> | A computer networking utility for reading from and writing to network connections using TCP or UDP, features includes port scanning, transferring files, and port listening, and it can be used as a backdoor |
| 4.  | Nmap        | <https://nmap.org/>                 | A free and open source (license) utility for network discovery and security auditing                                                                                                                          |
| 5.  | aircrack-ng | <https://www.aircrack-ng.org/>      | Tool for WiFi network security                                                                                                                                                                                |
| 6.  | OWASP Amass | <https://github.com/OWASP/Amass>    | A network mapping tool by attacking surfaces and external asset discovery using open source information gathering and active reconnaissance techniques                                                        |

## Steganography

### Images

| No. | Tool         | Homepage                                           | Description                                                                                       |
| --- | ------------ | -------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 1.  | Steghide     | <https://github.com/StefanoDeVuono/steghide>       |                                                                                                   |
| 2.  | Stegoveritas | <https://github.com/bannsec/stegoVeritas>          |                                                                                                   |
| 3.  | Exiftool     | <https://exiftool.org/>                            | Perl library & CLI to read, write and edit meta information in a wide variety of file formats     |
| 4.  | Stegosuite   | <https://stegosuite.org/>                          |                                                                                                   |
| 5.  | Pngcheck     | <http://www.libpng.org/pub/png/apps/pngcheck.html> |                                                                                                   |
| 6.  | Foremost     | <https://github.com/korczis/foremost>              | A console program to recover files based on their headers, footers, and internal data structures. |

### Audio

| No. | Tool             | Homepage                           | Description |
| --- | ---------------- | ---------------------------------- | ----------- |
| 1.  | Audacity         | <https://www.audacityteam.org/>    |             |
| 2.  | Sonic Visualizer | <https://www.sonicvisualiser.org/> |             |

## OSINT (Open Source INTelligence)

| No. | Tool            | Homepage                                  | Description                                                          |
| --- | --------------- | ----------------------------------------- | -------------------------------------------------------------------- |
| 1.  | OSINT Framework | <https://osintframework.com/>             | Online framework for information gathering from free tools/resources |
| 2.  | WayBack Machine | <https://web.archive.org/>                | Search for website snapshot version                                  |
| 3.  | Shodan          | <https://www.shodan.io/>                  | Search for internet connected devices info                           |
| 4.  | Social Media    |                                           | eg. GitHub, Facebook, Instagram, Twitter, etc                        |
| 5.  | Recon-ng        | <https://github.com/lanmaster53/recon-ng> | Open Source Intelligence gathering tool                              |
| 6.  | Pastebin        | <https://pastebin.com/>                   | Search for raw data                                                  |
| 7.  | Yandex          | <https://yandex.com/>                     | Search engine for reverse image search, powered by machine learning  |

## Recon

| No. | Tool      | Homepage                                       | Description                                                  |
| --- | --------- | ---------------------------------------------- | ------------------------------------------------------------ |
| 1.  | Nmap      | <https://nmap.org/>                            | Used to get website information by sending designated packet |
| 2.  | sublist3r | <https://github.com/aboul3la/Sublist3r>        | Finding subdirectories of a website                          |
| 3.  | Gobuster  | <https://github.com/OJ/gobuster>               | Directory bruteforcing (Recommended)                         |
| 4.  | dirb      | <https://tools.kali.org/web-applications/dirb> | Directory bruteforcing                                       |
