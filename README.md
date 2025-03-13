# Cryptography Algorithms & Experiments

This repository contains implementations of various cryptographic algorithms and concepts through 10 practical experiments. Each experiment demonstrates fundamental cryptographic techniques and their applications.

## 🔑 Features
- Classical ciphers (Substitution, Caesar, Transposition)
- Modern symmetric encryption (DES, AES, Feistel)
- Public-key cryptography (RSA, Diffie-Hellman)
- Number theory applications (Chinese Remainder Theorem)
- Digital signatures

## 🧪 Experiments

### 1. Classical Ciphers (Substitution/Caesar/Reverse)
- Implements basic substitution ciphers with key validation
- Key wrapping using modulo 26 arithmetic
- Includes transposition cipher with cyclic shifts

### 2. Transposition Cipher
- Pure position-based encryption method
- Implements columnar transposition technique

### 3. Affine Cipher
- Uses mathematical encryption: `E(x) = (k1*x + k2) mod n`
- Validates multiplicative inverse existence
- Implements modular arithmetic for decryption

### 4. Feistel Cipher
- Implements Feistel network structure
- Demonstrates block cipher principles
- Uses cyclic shifts and substitution boxes

### 5. DES Key Generation
- Generates 16-round DES keys
- Implements PC-1 and PC-2 permutation tables
- Handles circular shifts (1/2-bit variations)
- Reduces key from 64-bit to 48-bit

### 6. AES Key Expansion
- Generates 44-round AES keys
- Implements Rijndael key schedule
- Uses S-box substitution and Rcon constants
- Demonstrates key expansion from cipher key

### 7. Chinese Remainder Theorem
- Implements CRT for modular arithmetic optimization
- Uses extended Euclidean algorithm for inverse calculation
- Solves simultaneous congruences system

### 8. RSA Encryption
- Implements RSA using extended Euclidean algorithm
- Generates prime-based key pairs
- Includes primality checking mechanism
- Demonstrates public/private key relationship

### 9. Diffie-Hellman Key Exchange
- Demonstrates secure key exchange protocol
- Implements primitive root calculations
- Shows vulnerability to MITM attacks
- Highlights symmetric key derivation process

### 10. Digital Signatures (RSA-based)
- Implements RSA digital signatures
- Generates sender key pairs
- Verifies message integrity/authenticity
- Demonstrates signature generation/verification process

## ⚙️ Installation
1. Clone repository: git clone https://github.com/your-username/cryptography-experiments.git
cd cryptography-experiments

_Note: Some scripts may require command-line arguments for keys/inputs_

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request


## 🔍 Key Observations
- Demonstrated vulnerability of classical ciphers to cryptanalysis
- Highlighted importance of key complexity in modern algorithms
- Showcased mathematical foundations of cryptography
- Illustrated real-world security considerations (MITM attacks)



