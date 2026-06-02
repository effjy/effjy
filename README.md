# 👤 About Me

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=500&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

</div>

By day, I work as a **network administrator and security analyst** specializing in operational security and digital forensics. By night, I am an **independent cryptographic researcher** focused on symmetric primitive design and cryptanalysis.

My work centers on the **Krakken** family of wide-state SPN-ARX hybrid permutations and a surrounding ecosystem of high-assurance security tools: post-quantum encrypted volume managers, forensic-grade sanitization utilities, hardware-assisted memory allocators, topological intrusion detection, and deniable-encryption vaults.

### 🛠️ Core Arsenal & Tech Stack

![](https://img.shields.io/badge/Language-C%20%2F%20C%2B%2B-00599C?style=flat-square&logo=c%2B%2B)
![](https://img.shields.io/badge/OS-Linux%20Kernel%20%2F%20Hardening-FCC624?style=flat-square&logo=linux)
![](https://img.shields.io/badge/Crypto-Kyber%20%2F%20X448%20%2F%20SPN--ARX-00FFCC?style=flat-square)
![](https://img.shields.io/badge/GUI-GTK3%20%2F%20Cairo-7E57C2?style=flat-square&logo=gnome)
![](https://img.shields.io/badge/Compliance-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue?style=flat-square)

---

## ⭐ Featured Project — Krakken-Disk Butterfly Edition

<div align="center">

<img src="https://github.com/effjy/krakken-disk-butterfly/raw/main/krakken_logo.png" width="180" alt="Krakken-Disk Butterfly Logo">

### 🐙 Krakken-Disk v4.6.0 — Butterfly Edition

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/effjy/krakken-disk-butterfly/blob/main/LICENSE)
[![Language](https://img.shields.io/badge/language-C11-blue)](https://github.com/effjy/krakken-disk-butterfly)
[![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk-butterfly)
[![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk-butterfly)
![NEW](https://img.shields.io/badge/NEW-800080?style=flat-square)

**An ultra-secure, post-quantum encrypted disk manager for Linux.**

</div>

Krakken-Disk Butterfly Edition is an encrypted disk manager built for the post-quantum era. Driven by the **2048-bit Krakken-2048 Butterfly** permutation, it delivers a uniform **256-bit post-Grover security margin** across every volume layer, combining lattice-based cryptography, elliptic-curve key exchange, and hardware-accelerated AVX2 SIMD so your data stays private even against future quantum adversaries.

<div align="center">

<a href="https://github.com/effjy/krakken-disk-butterfly">
  <img src="https://github.com/effjy/krakken-disk-butterfly/raw/main/screenshot.png" width="720" alt="Krakken-Disk Butterfly graphical interface — dark-themed GTK volume manager">
</a>

<sub><i>The Krakken-Disk dashboard — a dark-themed GTK interface for one-click volume management.</i></sub>

</div>

#### 🌌 Why it stands out

- 🛡️ **Post-quantum by design** — a native 2048-bit wide-state permutation provides a uniform 256-bit post-Grover security margin across header and data layers.
- 🧬 **Hybrid key encapsulation** — pairs post-quantum **Kyber-1024** with classical **X448** so a break of either scheme alone never exposes your keys.
- 🦋 **Novel XRBD diffusion** — the XOR-Rotation Butterfly Diffusion layer mixes all 32 state words in a single 5-stage pass, enabling a leaner **8-round** design with stronger security margins.
- 🌑 **Plausible deniability** — fully **IND-RND** compliant: volumes carry no headers, signatures, or metadata, making them mathematically indistinguishable from random noise.
- 🔒 **Brute-force hardened** — **Argon2id** key derivation locked to 1 GB of RAM renders GPU- and ASIC-based attacks economically infeasible.
- ⚡ **Fast where it counts** — hand-tuned AVX2 vectorization with a multi-threaded, segment-parallel AEAD stream engine.
- 🐧 **Transparent mounting** — **FUSE 3** exposes encrypted containers as ordinary read-write directories.

<div align="center">

**[📦 Explore the repository →](https://github.com/effjy/krakken-disk-butterfly)**

</div>

---

## 🧭 Navigation

- [Featured Project — Krakken-Disk Butterfly](#-featured-project--krakken-disk-butterfly-edition)
- [Hardware-Assisted Memory Safety & Systems Security](#-hardwareassisted-memory-safety--systems-security)
- [Cryptographic Permutations](#-cryptographic-permutations)
- [Software Applications](#️-software-applications)
- [Research Interests](#-research-interests)
- [Background](#-background)
- [Contact & Profiles](#-contact--profiles)

---

## 🔬 Hardware-Assisted Memory Safety & Systems Security

| Project | Description | Status |
|:--------|:------------|:------:|
| **[KageAlloc](https://github.com/effjy/kagealloc)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/kagealloc) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/kagealloc) [![MPK](https://img.shields.io/badge/Intel-MPK-orange)](https://github.com/effjy/kagealloc) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32529792-blue)](https://doi.org/10.6084/m9.figshare.32529792)<br><br>High-performance memory allocator using **Intel Memory Protection Keys (MPK)** to enforce temporal safety, metadata integrity, and control-flow isolation. Introduces **RICCG** (defeats PKRU hijacking), **BKR** (near-zero-overhead quarantine), and **TIMP** (thread-isolated metadata) — at just **3.8% overhead** over `ptmalloc`. | ✅ Published<br>*(2026)* |
| **[TIDS](https://github.com/effjy/tids)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C99-blue)](https://github.com/effjy/tids) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/tids) [![GUI](https://img.shields.io/badge/GUI-GTK3-green)](https://gtk.org) [![Topic](https://img.shields.io/badge/topic-Persistent%20Homology-orange)](https://en.wikipedia.org/wiki/Persistent_homology) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32536887-blue)](https://doi.org/10.6084/m9.figshare.32536887)<br><br>**Topological Intrusion Detection System** — real-time network intrusion detection via persistent homology. Transforms flow features into 5D point clouds, computes Vietoris–Rips filtrations, and visualizes *H₀*/*H₁* invariants in GTK3/Cairo. Detects DDoS (persistent loops), port scans (parallel *H₀* bands), and slow exfiltration (bridging components). **0.03% FPR** on CIC-IDS2017. | ✅ Published<br>*(2026)* |
| **[HoneyCrypt](https://github.com/effjy/honeycrypt)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-ANSI%20C99-blue)](https://github.com/effjy/honeycrypt) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/honeycrypt) [![GUI](https://img.shields.io/badge/GUI-GTK3-green)](https://gtk.org) [![Crypto](https://img.shields.io/badge/crypto-DTE-orange)](https://github.com/effjy/honeycrypt) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32537733-blue)](https://doi.org/10.6084/m9.figshare.32537733)<br><br>**Distribution-Transforming Encryption (DTE) Vault** — a pure ANSI C desktop application that replaces authentication errors with plausible decoys (Luhn-valid cards, BIP39 seeds, GPS coordinates, medical records). An incorrect passcode returns a syntactically valid decoy rather than an integrity failure, denying attackers the mathematical feedback offline brute-force attacks rely on. Includes a 21-slot decoy grid, four high-fidelity synthesizers, and a built-in brute-force simulator. | ✅ Published<br>*(2026)* |

---

## 🔬 Cryptographic Permutations

| Project | Description | Status |
|:--------|:------------|:------:|
| **[Krakken-2048 Abyssal](https://github.com/effjy/krakken)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32527359-blue)](https://doi.org/10.6084/m9.figshare.32527359)<br><br>A **2048-bit permutation** fusing an SPN core (GF(2⁸) S-box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed for high-assurance sponge constructions. | ✅ Published<br>*(2026)* |
| **[Krakken-2048 Butterfly](https://github.com/effjy/krakken-butterfly)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-butterfly) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-butterfly) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32527287-blue)](https://doi.org/10.6084/m9.figshare.32527287)<br><br>An evolution of Krakken-2048 featuring a novel **XOR-Rotation Butterfly Diffusion (XRBD)** layer that achieves full word-level avalanche across 32 words in a single 5-stage pass. This enables a round-count reduction from 10 to 8 while improving security margins. | ✅ Published<br>*(2026)* |

---

## 🛠️ Software Applications

| Project | Description | Status |
|:--------|:------------|:------:|
| **[Krakken-Disk](https://github.com/effjy/krakken-disk/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk) [![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk)<br><br>A post-quantum encrypted disk manager for Linux combining **Kyber-1024/X448 hybrid KEM** with AVX2-accelerated wide-state permutations and strong plausible deniability. | 🟢 Stable |
| **[Krakken-Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk-butterfly) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk-butterfly) [![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk-butterfly) ![NEW](https://img.shields.io/badge/NEW-800080?style=flat-square)<br><br>An evolution of Krakken-Disk that swaps in the **Krakken-2048 Butterfly** permutation. Inherits every feature (Kyber-1024/X448 KEM, plausible deniability, AVX2 acceleration) while gaining the faster 8-round design and the XRBD diffusion layer. | 🟢 Stable |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/secure_mount) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/secure_mount) [![GTK](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/secure_mount)<br><br>A modern GTK3 frontend for **gocryptfs** that makes mounting, unmounting, and initializing encrypted volumes effortless. Features desktop integration, secure terminal password entry, and one-click volume management. | 🟢 Stable |
| **[Secure Wipe](https://github.com/effjy/swipe)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/swipe) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/swipe) [![Standards](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/swipe)<br><br>A command-line data sanitization utility for secure environments — **NIST SP 800-88 compliant** file, directory, free-space, and RAM wiping. The interactive, text-based counterpart to Virtual Wipe Turbo. | 🟢 Stable |
| **[Usage](https://github.com/effjy/usage/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/usage) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/usage) [![GTK](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/usage) [![UI Theme](https://img.shields.io/badge/UI%20Theme-Tokyo%20Night-purple)](https://github.com/effjy/usage)<br><br>A real-time network traffic and bandwidth monitor written in C with GTK+ 3. Displays current speeds, records session statistics, and draws a live graph of incoming and outgoing traffic — styled with a premium **Tokyo Night** dark theme. | 🟢 Stable |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/vwipe) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/vwipe) [![Standards](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/vwipe) [![Turbo Engine](https://img.shields.io/badge/engine-8--core%20Turbo-00FFCC)](https://github.com/effjy/vwipe)<br><br>A high-performance, forensic-grade secure-erasure suite for storage and volatile memory, aligned with **NIST SP 800-88 Rev. 1**. Features a multi-threaded engine, GTK3 dark-theme UI, and a secure CLI memory purger. | 🟢 Stable |

---

## 🎯 Research Interests

- **Wide-state permutation design** for post-quantum symmetric cryptography
- **SPN-ARX hybrid architectures** — invariant subspace resistance, algebraic degree propagation
- **Topological data analysis for intrusion detection** — persistent homology, Vietoris–Rips complexes
- **Hardware-assisted memory safety** — Intel MPK, temporal safety, control-flow isolation
- **Side-channel-resistant & constant-time implementations**
- **Automated cryptanalysis** — MILP, SAT/SMT solvers on mixed constructions
- **Deniable encryption & hidden-volume plausibility**
- **Forensic-grade sanitization & cryptographic erasure** — NIST SP 800-88
- **Mode design for large-state sponges** — keyed duplex, AEAD

---

## 📖 Background

Over **20 years** as a security analyst, network administrator, and technical specialist have given me a rare bridge between operational security and cryptographic design. For more than a decade, I have independently researched symmetric primitives, focusing on how the SPN and ARX paradigms can be fused so each cancels the other's weaknesses.

The **Krakken** project is the embodiment of that philosophy: every S-box, every rotation, and every linear layer is chosen to neutralize the cryptanalytic vulnerabilities of the others.

---

## 📬 Contact & Profiles

| Platform | Link |
|:---------|:-----|
| **GitHub**   | [@effjy](https://github.com/effjy) |
| **ORCID**    | [0009-0005-6377-1675](https://orcid.org/0009-0005-6377-1675) |
| **Figshare** | [Publications](https://figshare.com/authors/Jean-Francois_Lachance-Caumartin/24086388) |
| **Gravatar** | [effjy](https://gravatar.com/effjy) |
| **X**        | [@jfclachance](https://x.com/jfclachance) |

---

<div align="center">

  <!-- Row 1 -->
  <img src="CSS.svg" width="60" alt="CSS">
  <img src="Java-Dark.svg" width="60" alt="Java">
  <img src="Perl.svg" width="60" alt="Perl">
  <img src="Bash-Dark.svg" width="60" alt="Bash">
  <img src="C.svg" width="60" alt="C">
  <img src="JavaScript.svg" width="60" alt="JavaScript">
  <img src="Python-Dark.svg" width="60" alt="Python">

  <br>

  <!-- Row 2 -->
  <img src="CMake-Dark.svg" width="60" alt="CMake">
  <img src="Git.svg" width="60" alt="Git">
  <img src="HTML.svg" width="60" alt="HTML">
  <img src="Linux-Dark.svg" width="60" alt="Linux">
  <img src="Ubuntu-Dark.svg" width="60" alt="Ubuntu">
  <img src="CPP.svg" width="60" alt="C++">
  <img src="SVG-Dark.svg" width="60" alt="SVG">

</div>

<div align="center">

  <img src="cybersecurity_logo.svg" width="250" alt="Cybersecurity Logo">

</div>
