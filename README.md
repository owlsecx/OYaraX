# 🦉 OYaraX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OYaraX** — Signature & IOC Malware Scanner

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OYaraX is a YARA-based malware scanning and rule-management tool that applies signature rules to files and directories to detect malicious or suspicious content. It compiles and runs rule sets, reports matches with rule and string context, and supports recursive scanning. It is intended for authorized malware analysis and incident response.

---

## ✨ Features


- YARA rule compilation and scanning of files and directories
- Recursive directory walking with file-type and size filtering
- Match reporting with rule name, tags and matched-string context
- Rule-set management (load, validate, organize rules)
- Structured export of scan results for reporting
- Offline operation with a --self-test mode

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OYaraX
./OYaraX --self-test
./OYaraX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
