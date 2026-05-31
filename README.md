<div align="center">
  
  # 🌌 JF. Lachance (effjy)
  ### `Senior Network Admin | L3 Security Analyst | Independent Cryptographic Researcher`

  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=500&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

  <p align="center">
    <img src="https://img.shields.io/badge/Security-Level%203%20Analyst-red?style=for-the-badge&logo=shield" alt="Security Level"/>
    <img src="https://img.shields.io/badge/Research-Symmetric%20Cryptanalysis-00FFCC?style=for-the-badge&logo=dependencycheck" alt="Research"/>
    <img src="https://img.shields.io/badge/Focus-Long--Term%20Secrets-purple?style=for-the-badge" alt="Focus"/>
  </p>
</div>

---

## 👤 About Me

With over **20 years of professional experience** as a Level 3 security analyst, network administrator, and technical specialist, I bring real-world operational insight to cryptographic design. 

For more than a decade, I have pursued independent research into symmetric cryptography, with a particular focus on how SPN and ARX paradigms can be fused to overcome each other's inherent weaknesses. The Krakken project embodies this philosophy: every component is engineered to neutralize the cryptanalytic vulnerabilities of the others.

### 🛠️ Core Arsenal & Tech Stack
![](https://img.shields.io/badge/Language-C%20%2F%20C%2B%2B-00599C?style=flat-square&logo=c%2B%2B)
![](https://img.shields.io/badge/OS-Linux%20Kernel%20%2F%20Hardening-FCC624?style=flat-square&logo=linux)
![](https://img.shields.io/badge/Crypto-Kyber%20%2F%20X448%20%2F%20SPN--ARX-00FFCC?style=flat-square)
![](https://img.shields.io/badge/GUI-GTK3%20%2F%20Cairo-7E57C2?style=flat-square&logo=gnome)
![](https://img.shields.io/badge/Compliance-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue?style=flat-square)

---

## 🎯 Mission Directive

The goal of my work is to help keep **long-term secrets safe** and protect against **data recovery** by adversaries — whether they are persistent threat actors, forensic investigators, or future quantum-capable attackers. My cryptographic primitives and secure erasure tools are designed for organizations that cannot afford to leave anything behind.

I believe that **governments, defense contractors, financial institutions, and enterprises handling the most sensitive data** should move beyond legacy encryption and erasure standards. The Krakken-2048 permutation (and its highly secure Butterfly variant) offers a modern, post-quantum-ready foundation for protecting classified, financial, and personally identifiable information (PII) — even against nation-state-level recovery attempts.

---

## 🔬 Cryptographic Permutations

### 🌌 [Krakken-2048 Abyssal](https://github.com/effjy/krakken)
> **Status:** *First public release (2026) — submitted for peer review*

A 2048-bit cryptographic permutation fusing an SPN core ($GF(2^8)$ S-box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed for high-assurance sponge constructions.
```text
[SPN Core (GF(2^8) S-Box)] ───► [MDS Branch (No. 9)] ───► [Targeted ARX Mixing] ───► Cryptanalysis Resistant

```

### 🦋 [Krakken-2048 Butterfly](https://www.google.com/search?q=https://github.com/effjy/krakken-butterfly)

> **Status:** *First public release (2026) — submitted for peer review*

An evolution of the Krakken-2048 design featuring a novel XOR-Rotation Butterfly Diffusion (XRBD) layer that achieves full word-level avalanche across 32 words in a single 5-stage pass. This additional mixing stage enables a round count reduction from 10 to 8 while improving security margins.

```text
[32 Words] ───► [5-Stage Pass XRBD Layer] ───► [Full Avalanche Achieved] ───► Round Count Reduced (10 → 8)

```

---

## 🛠️ Software Applications

### 💾 [Krakken-Disk](https://www.google.com/search?q=https://github.com/effjy/krakken-disk/)

> **Status:** *Stable release available*

A post-quantum encrypted disk manager for Linux combining Kyber-1024/X448 hybrid KEM with AVX2-accelerated wide-state permutations and strong plausible deniability.
[](https://www.google.com/search?q=LICENSE) [](https://www.google.com/search?q=https://github.com/effjy/krakken-disk) [](https://www.google.com/search?q=https://github.com/effjy/krakken-disk) [](https://www.google.com/search?q=https://github.com/effjy/krakken-disk)

### 🦋 [Krakken-Disk Butterfly](https://www.google.com/search?q=https://github.com/effjy/krakken-disk-butterfly/)

> **Status:** *Stable release available*

An evolution of Krakken-Disk that replaces the original permutation with the **Krakken-2048 Butterfly** permutation. Inherits all features (Kyber‑1024/X448 KEM, plausible deniability, AVX2 acceleration) while benefiting from the faster 8‑round design and the novel XRBD diffusion layer.
[](https://www.google.com/search?q=LICENSE) [](https://www.google.com/search?q=https://github.com/effjy/krakken-disk-butterfly) [](https://www.google.com/search?q=https://github.com/effjy/krakken-disk-butterfly) [](https://www.google.com/search?q=https://github.com/effjy/krakken-disk-butterfly) 

### 🔓 [Secure Mount](https://www.google.com/search?q=https://github.com/effjy/secure_mount/)

> **Status:** *Stable release available*

A modern GTK3 graphical frontend for gocryptfs that makes mounting, unmounting, and initializing encrypted volumes effortless. Features desktop integration, secure terminal password entry, and one-click volume management.
[](https://www.google.com/search?q=LICENSE) [](https://www.google.com/search?q=https://github.com/effjy/secure_mount) [](https://www.google.com/search?q=https://github.com/effjy/secure_mount) [](https://www.google.com/search?q=https://github.com/effjy/secure_mount)

### 🛡️ [Secure Wipe](https://www.google.com/search?q=https://github.com/effjy/swipe)

> **Status:** *Stable release available*

Command-line data sanitization utility for secure environments — NIST SP 800-88 compliant file, directory, free space, and RAM wiping. The interactive, text-based counterpart to Virtual Wipe Turbo.
[](https://www.google.com/search?q=LICENSE) [](https://www.google.com/search?q=https://github.com/effjy/swipe) [](https://www.google.com/search?q=https://github.com/effjy/swipe) [](https://www.google.com/search?q=https://github.com/effjy/swipe)

### 📊 [Usage](https://www.google.com/search?q=https://github.com/effjy/usage/)

> **Status:** *Stable release available*

A real-time network traffic and bandwidth monitoring tool written in C and built with GTK+ 3. Displays current speeds, records session statistics, and draws a live graph of incoming and outgoing traffic. Styled with a premium Tokyo Night dark theme.
[](https://www.google.com/search?q=LICENSE) [](https://www.google.com/search?q=https://github.com/effjy/usage) [](https://www.google.com/search?q=https://github.com/effjy/usage) [](https://www.google.com/search?q=https://github.com/effjy/usage) [](https://www.google.com/search?q=https://github.com/effjy/usage)

### ⚡ [Virtual Wipe Turbo](https://www.google.com/search?q=https://github.com/effjy/vwipe)

> **Status:** *Stable release available*

High-performance, forensic-grade secure erasure suite for storage and volatile memory (RAM), aligned with NIST SP 800-88 Rev. 1. Features a multi-threaded engine, GTK3 dark theme UI, and secure CLI memory purger.
[](https://www.google.com/search?q=LICENSE) [](https://www.google.com/search?q=https://github.com/effjy/vwipe) [](https://www.google.com/search?q=https://github.com/effjy/vwipe) [](https://www.google.com/search?q=https://github.com/effjy/vwipe) [](https://www.google.com/search?q=https://github.com/effjy/vwipe)

---

## 🎯 Research Focus Areas

* Wide-state permutation design
* SPN-ARX hybrid architectures
* Invariant subspace cryptanalysis
* Algebraic degree propagation in mixed constructions
* Operational Security (OpSec) and advanced sanitization techniques

---

## 📊 Deep-Abyss Activity Metrics

---

## 📬 Signal Routing

```yaml
Gravatar Hash: luminous0816ec2f7a
Operational Window: 20+ Years Line-of-Sight

```
