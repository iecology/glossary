---
title: Internet Freedom Glossary
author: Jonah Silas Sheridan
date: 11/9/2015
---    

# Internet Freedom Reference
## Glossary

**Add-ons**
See Extensions

**Algorithm**:
 An algorithm can be generally described as any series of instructions given to a computer. In this context algorithms are frequently talked about in describing certain encryption schemes and methods of generating unique fingerprints or checksums for verifying file integrity.

**Asymmetric Encryption**:
A function of Public Key Cryptography which describes a type of encryption in which two separate keys exist, one which is publicly shared and can be used for encrypting information to a recipient and one which is kept private for decryption of that information.You can think of encrypting with a public key as being like putting your information in a safe that only the owner of the private key has the combination to open.

**Backup**:
Regularly updated copies of your files, ideally stored in several different places, so that if access to or integrity of
your data is disrupted for any reason (damage to computers due to accident or natural disaster, accidental or malicious deletion of files, damage to storage devices or servers), they can be restored. Online backup services are best supplemented by backups stored on personal equipment. Depending on circumstances, distributing encrypted copies to offsite storage sites by trading with others can be a wise strategy to carefully consider for your context.

**Bridge Relay**:  
A Bridge Relay is a server in the Tor network that is not publicly announced. If you choose to use a bridge, the server can provide you with access to the Tor network even if Tor is blocked in your country or network.

**Cookies**:
Small files placed on your computer by websites that you visit to help customize your experience. They are used to manage website features such as logins and can also be used to track behavior on the web. While not all cookies are a security risk, if poorly implemented they can expose the information they contain. Read more about cookies [here](http://www.allaboutcookies.org/)

**Checksum**:
In the context of this tool, a checksum is number that acts a unique fingerprint of a file or program. Using this number you can verify that a file you are going to use is the same one you saved, received or downloaded. This number is commonly published along with software releases so you can be sure your downloads have not been changed in between you and the provider. This number can be computed using various types of hash functions, some of which have a stronger guarantee of uniqueness (and so can’t be forged). For this reason Satori uses SHA256 checksums rather than less secure MD5 or SHA1 checksums.  

**Circumvention**:
The act of bypassing Internet controls, whether filters, censorship or monitoring, to safely and reliably access monitored or blocked websites and other Internet services.

**Credentials**:
Credentials are anything you use to identify yourself to a computer system. Commonly this is a username and password combination but can also additionally or only be other items such as a one time code that comes from a program or text message, a security certificate or anything else that strongly identifies who is connecting.

**Digital Assets**:  
Any and all data you store electronically. This includes files, website, emails, social media accounts, online banking accounts, etc. Some of these items may be ones that you administer yourself (e.g., the contents of hard drives, file repositories stored on servers owned and controlled by your organization); others may be maintained by third party services on your behalf (e.g., files on Google Drive or Box). Others are services that you participate in that are owned and controlled by others (subject to terms of service), such as social media content.

**Domain Name System**:
The domain name system (DNS) is like a phone book for the Internet. It translates domain names (such as google.com or whitehouse.gov) into the numbers that identify the location of services on the Internet. It can also be used to store other information about information systems to increase security or interoperability.

**Encryption**:
A mechanism by which your data scrambled in order to protect it from being read or altered by unauthorized parties. Authorized parties use some sort of shared secret such as a passphrase or encryption key to decrypt (i.e., unscramble) it. There are many different systems and algorithms used to encrypt communications and other digital assets.

**Encryption Key**:
An encryption key, also called Key Material, is a piece of information that you share with an authorized party so they can encrypt/decrypt, sign or verify information shared from you. In most cases this information is highly sensitive and needs to be protected however modern asymmetric encryption schemes allow you to have a “public” key that you can safely share with anyone.

**Extensions**:
Also called addons, these are small pieces of software that you install as part of your web browser in order to give your browser additional capabilities. Because these are generally produced by small companies and individuals, their behavior is often unexamined and can threaten your privacy, anonymity and security. If your security needs are high, avoid these without confirming their behavior with technical advisors.

**Firewall**:
A piece of software or hardware device that analyzes and selectively blocks or alters information passing between two networks. Common places to find firewalls are between your office network and the Internet and on your computer to protect you from other computers on the network with you.

**Hexidecimal**:
Hexidecimal numbering, often shortened to hex, is a common and handy way of representing information on computers. Instead of just the numerals 0 through 9, hexidecimal also uses the letters A through F. SHA256 checksums as used in Satori are hexidecimal numbers for easy comparison.  

**Key Material**:
See Encryption Key

**Keyserver**
A keyserver is a place where many people publish the public part of their encryption key so others can access it. In addition other users can indicate (via signing) that they trust that that key belongs to the person whose name or email it is associated with and then publish that information to the keyserver as well. In this way keyservers are at the center of the Web of Trust and should be considered unsafe for highly sensitive users.

**Open Source Software**:
Open Source Software (OSS), or sometimes **F**ree and **L**ibre **O**pen **S**ource **S**oftware (FLOSS), is software for which the source code, which specifies how the software works, is made available for review, audit and alteration by the end user. Many security professionals consider such software more secure than Proprietary Software because the increased transparency means the end user does not necessarily have to trust the software provider and can verify their claims about the tools they provide.

**Password manager software**:
Software that keeps your passwords stored in an encrypted file protected by a master password. This allows you to store multiple passwords by remembering only one. Password managers are available as software that you install (e.g., KeePass) and as a web based service (e.g., LastPass). While web based password managers can be very convenient the threats against them, like all web tools, are numerous so may be best avoided for highly sensitive passwords.

**Pluggable Transport**:  
A feature of Tor software that allows you to add small modules that make your Internet traffic look like something else. There are Pluggable Transports that

**Proprietary Software**:
Software for which the source code which describes the way the software works is not made available to the end user. The security level of using such software is difficult to verify and generally rests upon a significant amount of trust in the company or people making it in addition to analysis of the running program.

**Proxy**:
An intermediary service through which you can channel some or all of your Internet communication. These can be used in all sorts of ways including to bypass Internet censorship. A proxy may be on your computer on your local network or far away. It can be public, or you may need to log in with a username and password to access it. Only some proxies are secure, which means that they use encryption to protect the privacy of the information that passes between your computer and the Internet services to which you connect through the proxy. Tor software acts as a proxy running on your computer for your Internet communications to be directed through.

**Public Key Cryptography**:
Any of a variety of activities that can be performed using a matched set of publicly shared and privately protected key material including scrambling of data, signature creation and identity verification for logins.

**Security Certificate**:
A security certificate is a specific kind of file that includes an encryption key, and often times additional
information about that key. Websites such as used for banking and other services frequently use them to allow you to establish a secure connection with their servers and for third party verification of their identity.

**Tor Network**
A global network of anonymity and privacy protecting computers and devices that allows people to connect to Internet resources regardless of restrictions, censorship and filtering that may in place. In addition the Tor network limits how trackable those connections are by securely bouncing information through multiple participating computers before it gets to its destination.

**Tor Relay**:
A Tor relay is a Tor server that is published for use by Tor users and is configured to pass on data on behalf of others. It is these relays which bounce connections through the network to provide anonymity protections. While running a computer as a relay can create legal and technical headaches and is not recommended for beginners, it can also provide significant cover traffic to users on the same network who use Tor.  

**Virtual Private Network (VPN)**:
A connection between computers or devices that allow them to exchange information in an encrypted form. This can allow you to
both protect your information as it travels through networks you don’t trust as well as provide secure access to information someplace else on the Internet such as an office or datacenter.

**Web of Trust or WoT**:
A decentralized way of tracking, managing and determining confidence in keys as used in GPG and related security software. There are concerns with using the Web of Trust as it reveals your trust relationships to others with whom you work or correspond so should be used very carefully by those whose associations need to be kept private. The Web of Trust, however, can allow you to begin communications with someone you do not know with a high level of confidence that you are actually communicating with that person.
