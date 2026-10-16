# Encryption Fundamentals & Mailvelope PGP

## Executive Summary
A guide to symmetric/asymmetric cryptography, public key infrastructure (PKI), and end-to-end browser-based email encryption using OpenPGP via Mailvelope.

## Key Concepts
- **Symmetric vs. Asymmetric Encryption:**
  - *Symmetric (AES):* Single shared secret key; fast, used for bulk data encryption.
  - *Asymmetric (RSA/ECC):* Uses a Public Key for encryption/verification and a Private Key for decryption/signing.
- **PGP/GPG Web of Trust:** Generating keypairs, exporting public keys, and signing digital messages to guarantee authenticity and non-repudiation.
- **Mailvelope Integration:** Browser extension configuration to seamlessly decrypt PGP-encrypted messages within webmail interfaces.

## Practical Takeaway
Asymmetric keypairs solve the key distribution problem: public keys can be freely shared to allow anyone to encrypt messages, but only the holder of the private key can decrypt them.
