# 🦉 OSignal

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCipher-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OSignal** — Digital Signature Suite

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OSignal is a digital-signature suite for RSA and ECDSA key management, signing, verification and certificate inspection. It generates RSA-2048/4096, ECDSA P-256/384/521 and Ed25519 key pairs, signs text and files with PSS and SHA-256/384/512, and verifies signatures with full key and fingerprint inspection. It ships as a themed desktop application built on the cryptography library.

---

## ✨ Features


- RSA-2048/4096, ECDSA P-256/P-384/P-521 and Ed25519 key-pair generation
- Sign text and files using RSA-PSS with SHA-256/384/512
- Verify signatures for both text and files, with clear valid/invalid results
- PEM key import/export plus a key inspector (type, size, fingerprint)
- Signature hex viewer, SHA-256/MD5 fingerprints and a session signature history log
- Export signed bundles as JSON, all in a dark OWLSec theme

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OSignal
./OSignal --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
