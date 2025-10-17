# Public Key Infrastructure


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

6. ### Client cross checks server certificate with the root certificate on file