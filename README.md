<div align="center">
  <h1>Quantok Shield</h1>
  <p><strong>Post-Quantum TLS Gateway (ML-KEM-768)</strong></p>
  <p>Drop-in protection against harvest-now-decrypt-later attacks</p>
  <a href="https://quantok.com">quantok.com</a> • 
  <a href="https://github.com/med46ai/quantok-shield/pkgs/container/quantok-shield">ghcr.io/med46ai/quantok-shield</a>
</div>

---

## Overview

Quantok Shield is a production-grade **Post-Quantum TLS Gateway** that upgrades any existing application, API gateway, or edge service to **quantum-safe encryption** using the ML-KEM-768 (Kyber-768) algorithm suite.

It is designed as a **drop-in component**, integrating with modern cloud and on-premise environments while maintaining compatibility with classical TLS clients.

Key features include:

- Hybrid TLS 1.3 with **ML-KEM-768** key exchange  
- OpenSSL 3 + oqs-provider integration  
- x86_64 + ARM64 support  
- Hardened Docker builds for Kubernetes, ECS, and edge deployments  
- Optional QUIC and HTTP/3 support  
- Harvest-now-decrypt-later (HNDL) mitigation out-of-the-box  

---

## Why Post-Quantum TLS Matters

Adversaries are actively capturing encrypted traffic today for future decryption once quantum computers mature.  
Quantok Shield eliminates this risk by providing **quantum-safe key agreement** immediately, without requiring changes to downstream infrastructure.

---

## Architecture

