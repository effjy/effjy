# 👤 About Me

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=500&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

</div>

**By day** – Network administrator & security analyst (operational security, digital forensics)  
**By night** – Independent cryptographic researcher, designing symmetric primitives and high‑assurance security tools

> My work centers on the **Krakken family** of wide‑state SPN‑ARX hybrid permutations, plus a surrounding ecosystem: post‑quantum encrypted volume managers, forensic‑grade sanitization utilities, hardware‑assisted memory allocators, topological intrusion detection, and deniable encryption vaults.

<br>

## 🧭 Navigation

- [Featured Project – Axis (Galactic Edition)](#featured)
- [Hardware‑Assisted Memory Safety & Systems Security](#hardware-memory-safety)
- [Cryptographic Permutations](#crypto-permutations)
- [Software Applications](#software-apps)
- [Research Interests](#research)
- [Background](#background)
- [Contact & Profiles](#contact)

<br>

---
<h2 id="featured">⭐ Featured Project — <a href="https://github.com/effjy/axis">Axis (Galactic Edition)</a></h2>

<div align="center">
  <br>
  <a href="https://github.com/effjy/axis"><img src="https://github.com/effjy/axis/raw/main/axis_logo.png" width="200" alt="Axis Galactic Edition GUI"></a>
  <br><br>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/language-C11-blue" alt="C11"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/platform-Linux-important" alt="Linux"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/security-AES--256--GCM-teal" alt="AES-256-GCM"></a>
  <img src="https://img.shields.io/badge/NEW-800080?style=flat-square" alt="NEW">
</div>

<br>
<div align="center">
**An ultra‑secure encrypted disk manager for Linux, powered by hardware‑accelerated AES‑256‑GCM.**  
Driven by the **AES‑256‑GCM permutation** with AES‑NI and AVX2 acceleration, it delivers high‑throughput authenticated encryption. Combines lattice‑based KEM (Kyber‑1024), elliptic‑curve key exchange (X448), and hardware acceleration – your data stays private even against future quantum adversaries.
  <br>
</div>
<div align="center">
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/screenshot.png" width="680" alt="Axis Galactic Edition GUI">
  </a>
  <br>
  <sub><i>Dark‑themed GTK dashboard for one‑click volume management</i></sub>
</div>

<br>

### 🌌 Why it stands out

- 🛡️ **Hardware‑accelerated AES‑256‑GCM** – uses AES‑NI and AVX2 for fast, secure authenticated encryption.
- 🧬 **Hybrid KEM** – Kyber‑1024 + X448: breaking either scheme alone never exposes your keys.
- ⚡ **Hardware acceleration** – AES‑NI/AVX2 instructions deliver high throughput with low CPU overhead.
- 🌑 **Plausible deniability** – IND‑RND compliant: volumes have no headers, signatures, or metadata → indistinguishable from random noise.
- 🔒 **Brute‑force hardened** – Argon2id locked to 1 GB RAM makes GPU/ASIC attacks uneconomic.
- 🐧 **FUSE 3 mounting** – encrypted containers appear as ordinary read‑write directories.

<div align="center">
  <a href="https://github.com/effjy/axis">📦 Explore the repository →</a>
</div>

<br>

---

<h2 id="hardware-memory-safety">🔬 Hardware‑Assisted Memory Safety & Systems Security</h2>

| Project | Description |
|:--------|:------------|
| **[KageAlloc](https://github.com/effjy/kagealloc)** <br> [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/kagealloc) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/kagealloc) [![MPK](https://img.shields.io/badge/Intel-MPK-orange)](https://github.com/effjy/kagealloc) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32529792-blue)](https://doi.org/10.6084/m9.figshare.32529792) | High‑performance memory allocator using **Intel MPK** for temporal safety, metadata integrity, and control‑flow isolation. Features **RICCG** (defeats PKRU hijacking), **BKR** (low‑overhead quarantine), and **TIMP** (thread‑isolated metadata). **3.8% overhead** over `ptmalloc`. <br> *Published 2026* |
| **[TIDS](https://github.com/effjy/tids)** <br> [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C99](https://img.shields.io/badge/language-C99-blue)](https://github.com/effjy/tids) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/tids) [![GTK3](https://img.shields.io/badge/GUI-GTK3-green)](https://gtk.org) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32536887-blue)](https://doi.org/10.6084/m9.figshare.32536887) | **Topological Intrusion Detection System** – real‑time NIDS using persistent homology. Transforms flow features into 5D point clouds, computes Vietoris–Rips filtrations, and visualizes *H₀*/*H₁* invariants in GTK3/Cairo. Detects DDoS, port scans, slow exfiltration – **0.03% FPR** on CIC‑IDS2017. <br> *Published 2026* |
| **[HoneyCrypt](https://github.com/effjy/honeycrypt)** <br> [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![ANSI C99](https://img.shields.io/badge/language-ANSI%20C99-blue)](https://github.com/effjy/honeycrypt) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/honeycrypt) [![GTK3](https://img.shields.io/badge/GUI-GTK3-green)](https://gtk.org) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32537733-blue)](https://doi.org/10.6084/m9.figshare.32537733) | **Distribution‑Transforming Encryption (DTE) vault** – replaces authentication errors with plausible decoys (Luhn‑valid cards, BIP39 seeds, GPS, medical records). Incorrect passcode returns a syntactically valid decoy, denying offline brute‑force feedback. Includes 21‑slot decoy grid, four high‑fidelity synthesizers, and a brute‑force simulator. <br> *Published 2026* |

<br>

---

<h2 id="crypto-permutations">🔬 Cryptographic Permutations</h2>

| Project | Description |
|:--------|:------------|
| **[Krakken-2048 Abyssal](https://github.com/effjy/krakken)** <br> [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32527359-blue)](https://doi.org/10.6084/m9.figshare.32527359) | A **2048‑bit permutation** fusing an SPN core (GF(2⁸) S‑box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed for high‑assurance sponge constructions. <br> *Published 2026* |
| **[Krakken-2048 Butterfly](https://github.com/effjy/krakken-butterfly)** <br> [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-butterfly) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-butterfly) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32527287-blue)](https://doi.org/10.6084/m9.figshare.32527287) | Evolution of Krakken‑2048 with the **XOR‑Rotation Butterfly Diffusion (XRBD)** layer – achieves full word‑level avalanche across 32 words in a single 5‑stage pass. Enables round reduction from 10 to 8 while improving security margins. <br> *Published 2026* |

<br>

---

<h2 id="software-apps">🛠️ Software Applications</h2>

| Project | Description |
|:--------|:------------|
| **[Axis (Galactic Edition)](https://github.com/effjy/axis/)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/axis) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/axis) [![Security](https://img.shields.io/badge/security-Post--Quantum--%2B--AES-teal)](https://github.com/effjy/axis) <img src="https://img.shields.io/badge/NEW-800080?style=flat-square" align="right"> | Ultra‑secure encrypted disk manager with hardware‑accelerated AES‑256‑GCM, Kyber‑1024/X448 hybrid KEM, plausible deniability, and GTK GUI. **Stable** |
| **[Krakken-Disk](https://github.com/effjy/krakken-disk/)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk) [![Post‑Quantum](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk) | Post‑quantum encrypted disk manager for Linux. Kyber‑1024/X448 hybrid KEM, AVX2‑accelerated wide‑state permutations, plausible deniability. **Stable** |
| **[Krakken-Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk-butterfly) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk-butterfly) [![Post‑Quantum](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk-butterfly) <img src="https://img.shields.io/badge/NEW-800080?style=flat-square" align="right"> | Same features as Krakken‑Disk, but with the **Krakken‑2048 Butterfly** permutation – faster 8‑round design and XRBD diffusion. **Stable** |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/secure_mount) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/secure_mount) [![GTK3](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/secure_mount) | Modern GTK3 frontend for **gocryptfs** – effortless mounting, unmounting, and initializing encrypted volumes. Desktop integration, secure password entry. **Stable** |
| **[Secure Wipe](https://github.com/effjy/swipe)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/swipe) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/swipe) [![NIST](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/swipe) | CLI data sanitization utility – NIST SP 800‑88 compliant file, directory, free‑space, and RAM wiping. Interactive text‑based interface. **Stable** |
| **[Usage](https://github.com/effjy/usage/)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/usage) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/usage) [![GTK3](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/usage) | Real‑time network traffic monitor with GTK+3 – current speeds, session statistics, live graph. Styled with **Tokyo Night** dark theme. **Stable** |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** <br> [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![C](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/vwipe) [![Linux](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/vwipe) [![NIST](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/vwipe) <img src="https://img.shields.io/badge/NEW-800080?style=flat-square" align="right"> | High‑performance secure‑erasure suite for storage and volatile memory. Multi‑threaded engine, GTK3 dark theme, secure CLI memory purger. **Stable** |

<br>

---

<h2 id="research">🎯 Research Interests</h2>

<div align="center">

| **Wide‑state permutation design** | **SPN‑ARX hybrid architectures** |
|:----------------------------------|:----------------------------------|
| Post‑quantum symmetric crypto | Invariant subspace resistance, algebraic degree propagation |
| **Topological data analysis for IDS** | **Hardware‑assisted memory safety** |
| Persistent homology, Vietoris–Rips complexes | Intel MPK, temporal safety, control‑flow isolation |
| **Side‑channel resistance** | **Automated cryptanalysis** |
| Constant‑time implementations | MILP, SAT/SMT solvers on mixed constructions |
| **Deniable encryption** | **Forensic‑grade sanitization** |
| Hidden‑volume plausibility | NIST SP 800‑88, cryptographic erasure |
| **Mode design for large‑state sponges** | – |
| Keyed duplex, AEAD | – |

</div>

<br>

---

<h2 id="background">📖 Background</h2>

Over **20 years** as a security analyst, network administrator, and technical specialist – a rare bridge between operational security and cryptographic design. For more than a decade I have independently researched symmetric primitives, focusing on how the SPN and ARX paradigms can be fused so each cancels the other's weaknesses.

The **Krakken** project embodies that philosophy: every S‑box, every rotation, every linear layer is chosen to neutralize the cryptanalytic vulnerabilities of the others.

<br>

---

<h2 id="contact">📬 Contact & Profiles</h2>

| Platform | Link |
|:---------|:-----|
| **GitHub**   | [@effjy](https://github.com/effjy) |
| **ORCID**    | [0009-0005-6377-1675](https://orcid.org/0009-0005-6377-1675) |
| **Figshare** | [Publications](https://figshare.com/authors/Jean-Francois_Lachance-Caumartin/24086388) |
| **Gravatar** | [effjy](https://gravatar.com/effjy) |
| **X**        | [@jfclachance](https://x.com/jfclachance) |

<br>

---

<div align="center">
  <img src="CSS.svg" width="50" alt="CSS">
  <img src="Java-Dark.svg" width="50" alt="Java">
  <img src="Perl.svg" width="50" alt="Perl">
  <img src="Bash-Dark.svg" width="50" alt="Bash">
  <img src="C.svg" width="50" alt="C">
  <img src="JavaScript.svg" width="50" alt="JavaScript">
  <img src="Python-Dark.svg" width="50" alt="Python">
  <br>
  <img src="CMake-Dark.svg" width="50" alt="CMake">
  <img src="Git.svg" width="50" alt="Git">
  <img src="HTML.svg" width="50" alt="HTML">
  <img src="Linux-Dark.svg" width="50" alt="Linux">
  <img src="Ubuntu-Dark.svg" width="50" alt="Ubuntu">
  <img src="CPP.svg" width="50" alt="C++">
  <img src="SVG-Dark.svg" width="50" alt="SVG">
</div>
