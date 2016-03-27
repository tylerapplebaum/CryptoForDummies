# CryptoForDummies

### Table of Contents

1. The Basics

  1.1 Symmetric-key vs. Asymmetric-key Cryptography

  1.2 Diffie-Hellman-Merkle Exchange

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

  #####1.1 Symmetric Key vs. Asymmetric Key Cryptography
  Symmetric cryptography, or secret key cryptography, uses the same key for both encryption and decryption. Symmetric key cryptography is very fast, but it only works if both parties have the same key.

  Asymmetric cryptography, or public key encryption, uses a key pair. The public key is used for encryption, while the private key is used for decryption. This operation is slower and more resource intensive than symmetric key cryptography. However, it can be used to securely exchange data in the presence of a third party.

  Both symmetric and asymmetric cryptography are used during a TLS session. Asymmetric cryptography is used to set up the key exchange process, so that both parties can share a symmetric key for fast encryption and decryption of data.

  #####1.2 Diffie-Hellman-Merkle Exchange
  Tomes have been written on this fundemental part of cryptography. I won't attempt to replicate that depth of knowledge here.  

  #####1.3 Stream Ciphers vs. Block Ciphers

  #####1.4 PKI Certificates

  #####1.5 Signature vs. Encryption

####2. Anatomy of A Cipher Suite
Let's use this common cipher suite below as our example.

TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256

Here it is in smaller chunks:

```
* TLS
* ECDHE_RSA
* AES_128
* GCM
* SHA256
```

####3. TLS Handshake Breakdown

####4. What's secure nowadays?

####5. Perfect Forward Secrecy

####6. Elliptic Curve Cryptography

####7. References

***
