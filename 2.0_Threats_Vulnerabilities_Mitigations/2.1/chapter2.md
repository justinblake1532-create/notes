# Application Attacks

### Injection
 : When an attacker inserts malicious code or commands into an apps input to execute unauthorized actions, gain access to sensitive data, or compromise the system


### Buffer Overflow
 : Attacker sends more data to programs buffer than it's designed to handle


### Replay
 : Attack involves capturing a legit data transmission, such as an auth request or command, and then retransmitting it later to gain unauthorized access


### Privilege Escalation
 : Attacker exploits a vulerability in a app or OS to gain higher-level access than they were originally granted


### Forgery 
 : Refers to Cross-Site Request Forgery(CSRF) and Server-Site Request Forgery(SSRF). Tricks a user's browser into seding unwanted HTTP requests to a trusted application, exploiting authenticated sessions(CSRF). SSRF abuses an applications server functionality to make requests to internal or external resources, often to steal data or gain unauthorized access


### Directory Traversal
 : Attack where attacker(s) manipulates user input to access files and directories on the server outside the web root folder# Attack Indicators

- ### Account Lockout 
- ### Concurrent Session Usage
- ### Blocked Content
- ### Impossible Travel
- ### Resource Consumption
- ### Resource Inaccessibility
- ### Out-Of-Cycle Logging
- ### Published/Documented
- ### Missing Logs# Common Threat Vectors and Attack Surfaces

### Message-Based
* Email
* Short Message Service (SMS)
* Instant Message (IM)
### Image-Based
### File-Based
### Voice Call
### Removable Device
### Vulnerable Software
* Client-Based vs. Agentless
### Unsupported Systems and Applications
### Human Vectors/Social Engineering
* Phising
* Vishing
* Smishing
* Misinformation/Disinformation
* Impersonation
* Business Email Compromise
* Pretexting
* Watering Hole
* Brand Impersonation
* Typosquatting
### Strategies for Attacks
* Reconnaissance 
* Social Engineering
* Breaching Systems
* Backdoor
* Escalating Privileges# Cryptographic Attacks

### Downgrade
 : Forces a system to abandon a stronger security protocol for a weaker, older, or less secure one, effectively lowering its security to expose and manipulate data


### Collision
 : Exploits a weakness in hashing algorithms where two different inputs produce the exact same hash value


### Birthday
 : An exploit that uses mathematics of the birthday paradox to find a <ins>collision</ins> in a hash function
# Defense Strategies

### Layering
 : Uses multiple, overlapping security controls (physical, administrative, technical), to protect against threats by creating <ins>redudant</ins> layers of defense


### Principle of Least Privilege
 : a user, program, or system should only have the minimum permissions and access necessary to perform its required functions, <ins>nothing more</ins>


### Variety
 : A security program should use multiple, dissimilar types of security controls
- Cont.
    * What you know -> User/Password
    * What you are -> Biometrics
    * What you have -> ID Card
    * Where you are -> Geolocation
        - Example: 
            * Multi-Factor Authentication


### Randomness
 : intentionally introduces unpredictability into a system to make it more difficult for attackers to exploit vulnerabilities


### Simplicity
 : Secuirty systems should be as straight forward and uncomplicated as possible# Indicators of Malicious Activity

### Malware Attacks
* Ransomeware
* Trojan
* Worm
* Spyware
* Bloatware
* Virus
* Keylogger
* Logic Bomb
* Rootkit
### Physical Attacks
* Brute Force
* Radio Frequency Identification (RFID) Cloning
* Environmental
### Network Attacks
* Distributed Denial Of Service (DDoS)
    * Amplified
    * Reflected
* Domain Name Service (DNS)
* Wireless
* On-Path
* Credential Replay
* Malicious Code
### Application Attacks
* Injection
* Buffer Overflow
* Replay
* Privilige Escalation
* Forgery
* Directory Transversal
### Cryptographic Attacks
* Downgrade
* Collision
* Birthday
### Password Attacks
* Spraying
* Brute Force
### Indicators
* Account Lockout
* Concurrent Session Usage
* Blocked Content
* Out-Of-Cycle Logging
* Missing Logs
* Impossible Travel
* Resource Consumption
* Resource Inaccessibility 
* Published/Documented# Malware

### Malware
 : Any malicious software designed to harm computer systems, networks, or data by causing unauthorized access, disrupting operations, or stealing sensitive information# Malware Attacks

### Ransomware
 : Encrypts an organizations data, rendering it inaccessible until a ransom is paid for a decryption key


### Trojan
 :  Software that masquerades as a legitimate or harmless program to deceive users into installing it


### Worm
 : A <ins>self-propagating and self-replicating</ins> software that spreads across networks without user intervention by exploiting vulerabilites in operating system and software. **No Host Needed**


### Spyware
 : Software designed to secretly collect information about a user or organization without their knowledge or consent and transmits it to a third party for illicit purposes


### Bloatware
 : Unwanted software, often per-installed by manufacturer or downloaded thorugh web behavior, that consumes system resources and slows down devices


### Virus
 : Self-replicating type of software that inserts code inot a **HOST** program, files, or boot sector to spread to other systems


### Keylogger
 : <ins>type of software</ins> that records and logs a user's keystrokes without their knowledge


### Adware
 : Software that extracts user data and provides targeted **ADs** based on the extracted data


### Logic Bomb
 : Piece of malicious code intentionally inserted into a software system that executes its harmful payload when a <ins>specific condition is met</ins>


### Rootkit
 : Stealthy type of malicious software that hides itself and other malware from an operating system to maintain persistent and privileged level of access


### Remote Access Trojan (RAT)
 : Malware that provides an attacker(s) with unauthorized, remote administrative control over an infected system. A <ins>RAT</ins> creates a backdoor into the system, allowing the attacker to secretly perform a wide range of malicious actions


### Cryptomining
 : Malware used to hijack PCs to mine cryptocurrency# Mitre Attack Exercise

1. Find the definition of Active Scanning.

    #### <ins>Active Scanning</ins>
     : Adversary probes victim infrastructure via network traffic


2. Find how to detect Phising attacks.

    #### <ins>DS0015</ins>
     : Monitor for third-party app logging, messaging, and/or other artifacts that may send phising messages to gain access to victim systems

    #### <ins>DS0022</ins>
     : Monitor for creation of suspicious email attatchments in download directory

    #### <ins>DS0029(Network Traffic Content)</ins>
     : Monitor for clicking on malicious links leading to credential phishing

    #### <ins>DS0029(Network Traffic Flow)</ins>
     : Monitor network data for uncommon data flows


3. Find how to mitigate Email Spoofing.

    #### <ins>M1054</ins>
     : Use anti-spoofing and ;email authentication mechanisms to fileter messages based of validity checks of the sender and integrity of the messages


4. Give the definition for Tactics.

    #### <ins>Tactics</ins>
     : Represents the **"why"** of an attack technique or sub-technique


5. Give the definition for Techniques.

    #### <ins>Techniques</ins>
     : Represents the **"how"** an adversary achieves a tactical goal by performing an action# Network Attacks

### Distributed Denial of Service (DDoS)
 : A cyber attack that uses a botnet of compromised computers to overwhelm a target network or server with an overwhelming volume of traffic


### Bot
 : An automated script to perform a given task


### Botnet
 : A group of Bots


### Domain Name System (DNS)
 : Targets the domain name to disrupt its availability or manipulate the data it provides, leading to compromised services, or user redirection to malicious sites


### Wireless
 : Any malicious activity that exploits weaknesses in a wireless network to gain unauthorized access, intercept data, disrupt services, or control connected devices


### On-Path
 : Also known as Man-In-The-Middle (MITM), is a cyberattack where a malicious actor places themselves between two communicating parties to intercept, monitor, or modify the data being exchanged


### Credential Replay
 : Attack where an attacker intercepts valid authentication credentials and resends or re-transmits them to a system to gain unauthorized access to an account or system


### Malicious Code
 : Cyberattack using software or scripts, often delivered covertly, to compromise a systems Confidentiality, Integrity, or Availability (C.I.A) by exploiting vulerabilities# Password Attacks

### Spraying
 : A type of brute force attack where a threat actor attempts a small number of very common passwords against a large list of usernames


### Brute Force
 : A trial-and-error method where an attacker tries every possible combination of characters to guess a correct password and gain unauthorized access to a system or account# Physical Attacks

### Brute Force
 : A cyber attack that uses automated software to rapidly try every possible combo of usernames and passwords to gain unauthorized access to a systm or account


### RFID Cloning
 : Attack that involves creating a <ins>replica</ins> of a legitimate RFID tag's data and identity to deceive a reader and gain unauthorized access or authorization


### Environmental
 : Attack targets the <ins>physical surroundings or infrastructure</ins> of a system to disrupt its operations# Scanning

### Client-Based
 : Security activities performed on the end-user's device or "client", rather than on the network or server


### Agentless
 : Security method for inspecting systems, cloud workloads, and code for vulnerabilities or misconfigurations without installing software agents on the target systems# Section 2 Definitions

### Pharming
 : Attack used to <ins>redirect</ins> users to fraudulent websites


### Attack Surface
 : Any known points on a network/resource that can be exploited


### Phising
 : Attacker impersonates a trusted entity to trick users into revealing sensitive information via <ins>Email</ins>


### Vishing
 : Attacker(s) uses <ins>phone calls</ins> or <ins>voice messages</ins> to impersonate trusted entities into revealing sensitive information


### Smishing
 : Attacker(s) send fraudulent <ins>text messages (SMS)</ins> to trick victims into revealing sensitive information


### Pretexting
 : Attacker(s) creates a believable, <ins>false narrative or scenario</ins> to trick a victim into revealing sensitive information


### Watering Hole
 : Targeted cyber attack where attacker(s) <ins>compromise a legitimate website</ins> that frequently a group of people visit, then <ins>infect with malware</ins> to <ins>infect visitors</ins> and gain access to their systems


### Impersonation
 : Someone <ins>pretending</ins> to be <ins>someone else</ins>


### Typosquatting
 : Attacker(s) register domain names that are <ins>similar</ins> to legitimate, popular websites, <ins>often containing slight misspellings</ins> to trick users# Social Engineering Process

1) ### Research
    * Footprinting -> gathering informatino


2) ### Development
    * Select Target
    * Form Relationship -> trust


3) ### Exploitation
    * Threat actor gains access/attempt was made
    * Wrap up/Exit Strategy# Supply Chain

### Suppliers
 : Provides <ins>raw</ins> materials
- Example
    * Hardware
    * Software


### Manufacturers
 : Produces the main good from raw materials


### Vendors
 : Sell the goods to consumers# Threat Actors

- Nation-state
- Unskilled Attacker
- Hacktivist
- Insider Threat
- Organized Crime
- Shadow IT

Opportunist Attack 
: Spur of the moment, short term gain
    * Ex: Mainly for financial gain
Targeted Attack
: Main target/goal, Long term, data exfiltration

# Motivations

- Data Exfiltration
- Espionage
- Service Disruption
- Blackmail
- Disruption/Chaos
- Disinformation
- Financial Gain
- Philosophical/Political Beliefs
- Ethical 
- Revenge
- War

# Attributes of Actors

- Internal/External
- Resources/Funding
- Level of Sophistication/Capability# Various Types of Vulnerabilities

### Application
* Memory Injection 
* Buffer Overflow
* Race Conditions
    * Time-Of-Check (TOC)
    * Time-Of-Use (TOU)
* Malicious Update
### Operating System(OS)-Based
### Web-Based
* SQL Injection
* Cross-Site Scripting (XSS)
### Hardware
* Firmware
* End-Of-Life (EOL)
* Legacy
### Virtualization
* Virtual Machine(VM) Escape
* Resource Reuse
### Cloud-Specific
### Supply Chain
* Service Provider
* Hardware Provider 
* Software Provider
### Crytopgraphic 
### Misconfiguration
### Mobile Device
* Side Loading
* Jailbreaking
### Zero-Day