# CryptoForDummies

### Table of Contents

1. The Basics

  1.1 Symmetric vs. Asymmetric Encryption
     
  1.2 DH Exchange
     
  1.3 Stream Ciphers vs. Block Ciphers
     
  1.4 PKI Certificates
     
  1.5 Signature vs. Encryption

2. Anatomy of A Cipher Suite

3. TLS Handshake Breakdown

4. What's secure nowadays?

5. Perfect Forward Secrecy

6. Elliptic Curve Cryptography

7. References
***
####1. The Basics
The purpose of this document is to give a somewhat in-depth explanation of SSL/TLS and the encryption and math backing it. The math will stay at around a high school level, mostly because I'm not capable of explaining it any further. :laughing:

  #####1.1 Symmetric vs. Asymmetric Encryption
  Symmetric encryption, or secret key encryption, uses the same key for both encrypting and decrypting.
  
  Asymmetric encryption, or public key encryption, uses a key pair. The public key is used for encryption, while the private key is used for decryption.
