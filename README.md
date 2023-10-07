# Personal Project: goose.SSL - A Custom OpenSSL Implementation of TLS 1.3

## Overview

"goose.SSL" is my personal endeavor to create a custom implementation of the TLS 1.3 protocol as defined in [RFC 8446](https://tools.ietf.org/html/rfc8446). This project aims to provide a robust, yet streamlined, SSL/TLS library that ensures secure internet communication. While the functionality will be similar to OpenSSL, goose.SSL targets greater performance and a simplified codebase for easier understanding and modification.

## Objectives

- To deepen my understanding of SSL/TLS protocols, specifically TLS 1.3.
- To challenge myself by implementing advanced cryptographic algorithms.
- To produce a functioning SSL/TLS library that could potentially be used in real-world applications, albeit with thorough testing and vetting.

## Core Features

- Full implementation of the TLS 1.3 handshake, encryption, and authentication mechanisms.
- Support for prevalent cryptographic algorithms including AES-GCM, ChaCha20-Poly1305, and multiple Elliptic Curve-based algorithms.
- A simplified API that provides the core functionalities of OpenSSL, designed for ease of understanding and modification.

## Technical Stack

- Written primarily in C++ for performance benefits and advanced language features.
- Utilizes open-source cryptographic libraries for the underlying cryptographic operations.
- Built on a modular architecture, making it extensible and maintainable.

## Learning Goals

- Gain hands-on experience in cryptographic protocols and algorithms.
- Understand the intricacies involved in secure data transmission over the internet.
- Experiment with optimizations for better performance and lower resource consumption.

## Security Safeguards

- Constant-time cryptographic operations to defend against timing attacks.
- A focus on writing clean, understandable code to minimize the risk of security vulnerabilities.
- Testing against known attack vectors and vulnerabilities to ensure robustness.

## Documentation and Knowledge Sharing

In the spirit of making this a learning project, extensive comments and documentation will be incorporated to explain the design choices, mathematical background, and the code structure. This will also serve as a guide for anyone who wishes to learn about SSL/TLS or consider contributing to the project.

## Status and Future Work

As a personal project, goose.SSL is a continual work-in-progress. Future plans include refining the code, adding more features, and conducting rigorous security audits.

By embarking on this challenging project, I hope to acquire a deep and thorough understanding of secure network communications, while also adding a significant project to my portfolio. Although it starts as a personal venture, the hope is that goose.SSL may evolve into a community-supported, open-source project.

