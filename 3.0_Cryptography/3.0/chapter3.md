# Assymetric Encryption Algorithms


### Rivest-Shamir-Adleman(RSA)
 : Public key cryptosystem based on the difficulty of factoring large prime numbers


### Diffie-Hellman
 : A cryptographic protocol used to securely establish a shared secret key between two parties over an <u>insecure<u> network


### Elliptic Curve Cryptography(ECC)
 : Tyoe of public-key encryption that uses the mathematical properties of elliptic curves to provide strong security with <ins>shorter</ins> key lengths than other methods


### Digital Signature Alogorithm(DSA)
 : A method for creating and verifying digital signatures to ensure authenticity and integrity of data; Government standard
# Blockchain

### Blockchain
 : The measures used to protect blockchain networks, including the use of cryptography, decentralization, and consensus mechanisms like <ins>Proof-Of-Work(POW)</ins> or <ins>Proof-Of-Stake(POS)</ins> to ensure the integrity, privacy, and functionality of transactions



- ### Blockchain Uses:
    * Decentralization
    * Peer-to-Peer(P2P) Networking
    * <ins>Open Public Ledger(OPL)</ins> -> Public record of transactions in the blockchain# Caesar Cipher

### Caesar Ciper
 : Simple substitution cipher where each letter in a message is shifted a <ins>fixed</ins> number of positions down the alphabet, and it is <ins>not secure for modern use</ins>



## Example

- ### <ins>ROT13</ins> -> type of Caesar Cipher where the alphabet is shifted by <ins>13</ins> letters# Certificate Revocation List


### Certificate Revocation List(CRL)
 : A blacklist for certificates# Certificates

- ### Public Key
- ### Subjects Information
- ### Serial Number
- ### Certificate Authority Confirmation
- ### Validity Date
# Cryptographic Attacks


### Hashing Collisions
 : When <ins>two</ins> different inputs produces the <ins>same</ins> hash value


### Dictionary Attack
 : Brute force method using a list of passwords


### Birthday Attack
 : Combines collision and dictionary attacks; uses probabilities to exploit weak digital signatures


### Downgrade Attack
 : **<ins>Forcing</ins>** a system to use an <ins>older version</ins> of a network transmission/service
# Cryptography

### Cryptography
 : The process of writing/solving messages using a secret code


### Security Through Obscurity 
 : Keeping data secret through <ins>hiding</ins> it


### Encryption
 : The process of converting normal readible test into something inelligible


### Cipher
 : The <ins>method/algorithm</ins> used to encrypt/convert data


### Plaintext
 : An unencrypted message


### Ciphertext
 : An encrypted message


### Algorithm
 : The process of encrypting/decrypting a message


### Cryptoanalysis
 : The process of cracking cryptographic systems# Disk/File Encryption


## Types of Disk/File Encryption


- ### Full-Disk/Partition
- ### Volume/File Encryption
- ### Database Encryption
- ### Record-Level Encryption
- ### High-Level Encryption
- ### Low-Level Encryption


### High-Level Encryption
 : Encrypting resources available to end users


### Low-Level Encryption
 : Encrypting resources that are least accessible to the user# Encrypting File System


## Encrypting File Systems(EFS)/FileVault


### Cryptoprocessors
 : Dedicated hardware to encrypt/decrypt data
 - Keys never leave the cryptoprocessors
 - Reduces the Attack Surface
# Encryption

### Encryption Keys
 : Data strings used to encrypt/decrypt data


### Symmetric Encryption
 : Same key is used to encrypt/decrypt data

 
### Assymmetric Encryption
 : Uses two keys; public and private key. <ins>Public key</ins> **encrypts** the data and <ins>Private Key</ins> **decrypts** the data


### Hybrid Cryptosystem
 : Symmetric private key and a recipients <ins>public key</ins> to **encrypt** data while the <ins>private key</ins> **decrypts** the data# Encryption Key Management


### Encryption Key Management
 : Keys are only as secure as a file is on the system


### Key Generation
 : When a key is initially created


### Storage
 : Preventing unauthorized access to keys


### Revocation
 : The event where a key is lost/stolen

 
### Expiration/Renewal
 : Keys have a "shelf-life"
# Hardware Security Module


### Hardware Security Module(HSM)
 : Cryptoprocessors implemented in <ins>removeable</ins> hardware
- Generate/Store keys and digital signatures
- HSMs can be more powerful than TPMs# Hashing

### Hashing
 : The process of converting one value into another values


### Hash
 : Digital footprint for piece of data


### Salting
 : Adding random numbers and characters **<ins>before</ins>** the hash is created


### Key Stretching
 : Take a generated key from a password and a salt value and you continuously convert the data strings into a longer and more disordered key# Hashing Algorithms


- ### SHA1
- ### SHA2
- ### SHA3
- ### MD5 -> No Longer Secure
- ### RIPEMD# Hashing Collisions

### Hashing Collisions
 : Two different files generate the **SAME** hash values
# Invalid Certificates

- ### The organization/entity no longer exists
- ### Private key becoming compromised
- ### Issued certificates are discovered to be fake# Methods of Cryptography


### Elliptic Curve Cryptography(ECC)
 : Generates smaller keys with greater levels of security, securing connections and data transmissions


### Perfect Forward Secrecy
 : Each message is encrypted with a **unique** key. Also can be called <ins>Ephemeral Key</ins>


### Obscurity
 : Making data difficult to find
- Example:
    * Data Masking
    * Stegonography
    * Tokenization


### Data Masking 
: Taking data and replacing the characters with an alternate character
- Example:
    * Replacing the characters in the data with "x"# Mining


### Mining
: Adding blocks to a blockchain# Public Key Infrastructure


### Public Key Infrastructure(PKI)
 : A framework with dedicated components to <ins>validate a subject's identity</ins>
 - Example
    * User
    * PCs
    * Networking Devices

- ### Cryptography -> Authentication
    * Non-Repudiation


### Digital Certificates
 : A form of digital authentication with confirmation from a <ins>trusted</ins> source
* Public Key
* Subject's Information
* Third-Party Confirmation


### Certificate Authority
 : Trusted entities that diestribute digital certificates

## Step of PKI

1. ### Root Certificate -> first certificate that a certificate authority will make, self-signed, sign lower-level certificates; signed with a private key, published with a public key

2. ### Root Certificate is distributed to client; client stores the root certificate

3. ### Certificate Signing Request(CSR) -> a file a subject sends to a certificate authority to get a certificate

- Subjects Public Key

4. ### The certificate authority signs or denies the Certificate Signing Request(CSR)

5. ### Subject certificate is established and sent to the other subject

6. ### Client cross checks server certificate with the root certificate on file# Rainbow Table Attack


### Rainbow Table Attack
 : Password-cracking method that uses large, pre-computed table of plaintext passwords and their corresponding hash values to reverse-engineer password hashes that have been stolen from a compromised system



- ### Provides longer and more complex hashes

- ### Incorporate Salting# States of Data


### Data at Rest
 : Data is in storage and not being used


### Data in Transit
 : Transferring data over a network

 
### Data in Use
 : Data being present in memory# Transactions


Sender -> S
Receiver -> R
Block -> []
User -> U
Blockchain -> []->[]->[]



1. ### Request Transaction
    * S -> R


2. ### Block is Created
    * []


3. ### Block is Distributed
    * [] -> U


4. ### User Verifies Transactions
    * U (check)


5. ### Block Gets Added to Blockchain
    * [] -> []->[]->[]


6. ### Receiver User Gets Contents Of Block
    * S -> R[]# Transport Encryption


### WiFi Protected Access(WPA)
 : Secure wireless traffic


### Internet Protocol Security(IPSEC)
 : Serves network traffic over an untrusted network between two endpoints; Implmented with VPNs


### Transport Layer Security(TLS)
 : Secures application data(web/email)

 
### GNU Privacy Guard(GPG)
 : Secures emails and files # Trusted Platform Module


### Trusted Platform Module(TPM)
 : Cryptoprocessor module <ins>within</ins> the CPU
- Checks the integrity of files on start up 
- Provides full Assymetric Encryption# Type of Digital Certificates


- ### Root Certificate

- ### Subject Alternatice Name(SAN)
    * TestOut.<ins>com</ins>
    * TestOut.<ins>net</ins>
    * TestOut.<ins>org</ins>

- ### Wildcard -> Subdomain Centralization
    * quiz.<ins>testout</ins>.com
    * test.<ins>testout</ins>.com

- ### Code Signed -> Proving an application is legitimate

- ### Email -> Sending secure emails; uses S/MIME protocol

- ### User and Computer -> Validates users or computers on a network# Types of Certificate Authorities


### Single Certificate Authority(CA)
 : Direct relationship between root certificate authority and subjects on a network


### Third-Party Certificate Authority(CA)
 : A certificate authority that doesn't have any direct relations with any subjects


### Chain Of Trust
 : A hiearchal model to establish trust between different entities


### Key Archival
 : Keys are backed up by a certificate authority; private keys are backed up

 
### Key Escrow
 : Third-Party oranizations that stores keys