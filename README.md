# Cryptography and Security Principles Demonstration

This project demonstrates key concepts in cryptography and cybersecurity using Python. It provides practical implementations, visualizations, and explanations of fundamental algorithms and processes used in secure communication and data protection.

## Overview

This Python script demonstrates the following concepts:

1. RSA (Rivest, Shamir, Adleman) cryptography
2. Basic idea of public key crypto - encryption
3. Basic idea of public key crypto - signatures
4. Diffie-Hellman Key exchange
5. One-way functions
6. Modular Math
7. Discrete Logarithms
8. Finding a key (in the context of RSA)
9. Example of RSA
10. PKCS (Public Key Cryptography Standards) example
11. Signatures – message recovery
12. Signatures - Appendix
13. HTTP -> HTTPS upgrade (simulating the process)
14. Mixed content: http and https (demonstrating the difference)

## Concepts, Explanations, and Importance

| Concept | Explanation | Importance in Cybersecurity | Domain |
|---------|-------------|---------------------------|--------|
| RSA Cryptography | Public-key crypto system for secure data transmission | Enables secure communication over insecure channels | Cryptography |
| Public Key Crypto - Encryption | Use of public key for message encryption | Allows secure message sending without prior key exchange | Cryptography |
| Public Key Crypto - Signatures | Use of private key for message signing | Provides authentication and non-repudiation | Cryptography |
| Diffie-Hellman Key Exchange | Method of securely exchanging cryptographic keys over a public channel | Allows two parties to jointly establish a shared secret over an insecure channel | Key Exchange |
| One-way Functions | Functions that are easy to compute but difficult to reverse | Fundamental to many cryptographic protocols, including password hashing | Cryptography |
| Modular Math | Arithmetic system with finite set of integers | Forms the basis for many cryptographic algorithms | Mathematics |
| Discrete Logarithms | The inverse operation of modular exponentiation | The difficulty of this problem is the basis for several cryptographic systems | Cryptography |
| PKCS Padding | Padding schemes used in public-key cryptosystems | Ensures security properties in encryption and signing operations | Cryptography |
| HTTP -> HTTPS Upgrade | Process of redirecting HTTP requests to HTTPS | Ensures secure communication by default | Network Security |
| Mixed Content | Web pages containing both HTTP and HTTPS resources | Can lead to security vulnerabilities if not handled properly | Web Security |

## Usage

To run the script:

1. Install the required packages:
   ```
   pip install matplotlib networkx prettytable cryptography sympy
   ```

2. Run the script:
   ```
   python cryptography_demo.py
   ```

The script will demonstrate each concept, display visualizations, and provide explanations for each plot.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Disclosure

This code is for educational purposes only. The implementations are simplified and not suitable for production use. For real-world applications, use well-tested and audited cryptographic libraries.
