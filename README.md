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

Pure-Python signature & IOC malware scanner (YARA-inspired rules)

---

## ✨ Features

- Pure-Python rule engine with its own compact, YARA-inspired rule format (.oyx) — NOT libyara
- Strings: text (nocase/wide/ascii/fullword), hex with ?? / nibble wildcards, jumps [n-m] and alternatives (AA|BB), regex /.../is
- Conditions: any/all/none/N of them, sets ($a*), #count, @offset, $a at N, $a in (a..b), filesize, entropy, magic, uint8/16/32(be), and/or/not, math
- ~30 built-in DEMO rules (webshells, reverse shells, PowerShell abuse, PE/ELF magic, UPX, miners, ...)
- Recursive scanner — include/exclude globs, max filesize, symlink-loop guard, chunked binary-safe reads, ThreadPoolExecutor concurrency
- MD5 / SHA1 / SHA256 + hash IOC list + string IOCs
- Shannon entropy (whole file + sliding block max)
- Magic-byte file type identification (40+ types)
- Quarantine REPORT — optional copy of matches to a folder (originals are NEVER moved or deleted)
- Save report (TXT / CSV / JSON) with location chooser
- Full CLI mode (--path, --rules, --json, --fail-on)

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OYaraX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
