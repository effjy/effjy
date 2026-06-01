# 👤 About Me

<div align="center">
  
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=500&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

</div>

By day: Network administrator and security analyst (OpSec, digital forensics). By night: Independent cryptographic researcher specializing in symmetric primitive design and cryptanalysis.

I am the author of the Krakken-2048 family of wide-state SPN-ARX hybrid permutations, Krakken-Disk post-quantum encrypted volume managers, Virtual Wipe Turbo forensic sanitization suite, KageAlloc MPK memory allocator, and TIDS topological intrusion detection.

### 🛠️ Core Arsenal & Tech Stack
![](https://img.shields.io/badge/Language-C%20%2F%20C%2B%2B-00599C?style=flat-square&logo=c%2B%2B)
![](https://img.shields.io/badge/OS-Linux%20Kernel%20%2F%20Hardening-FCC624?style=flat-square&logo=linux)
![](https://img.shields.io/badge/Crypto-Kyber%20%2F%20X448%20%2F%20SPN--ARX-00FFCC?style=flat-square)
![](https://img.shields.io/badge/GUI-GTK3%20%2F%20Cairo-7E57C2?style=flat-square&logo=gnome)
![](https://img.shields.io/badge/Compliance-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue?style=flat-square)

---

## 🔬 Hardware‑Assisted Memory Safety & Systems Security

| Project | Description | Status |
|:--------|:------------|:-------|
| **[KageAlloc](https://github.com/effjy/kagealloc)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/kagealloc) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/kagealloc) [![MPK](https://img.shields.io/badge/Intel-MPK-orange)](https://github.com/effjy/kagealloc) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32529792-blue)](https://doi.org/10.6084/m9.figshare.32529792)<br><br>High‑performance memory allocator using Intel Memory Protection Keys (MPK) to enforce temporal safety, metadata integrity, and control‑flow isolation. Introduces **RICCG** (defeats PKRU hijacking), **BKR** (near‑zero overhead quarantine), and **TIMP** (thread‑isolated metadata). Only 3.8% overhead over `ptmalloc`. | First public release (2026) — published |
| **[TIDS](https://github.com/effjy/tids)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C99-blue)](https://github.com/effjy/tids) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/tids) [![GUI](https://img.shields.io/badge/GUI-GTK3-green)](https://gtk.org) [![Topic](https://img.shields.io/badge/topic-Persistent%20Homology-orange)](https://en.wikipedia.org/wiki/Persistent_homology) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32536887-blue)](https://doi.org/10.6084/m9.figshare.32536887)<br><br>**Topological Intrusion Detection System** – real‑time network intrusion detection using persistent homology. Transforms network flow features into 5D point clouds, computes Vietoris‑Rips filtrations, and visualizes $H_0$/$H_1$ invariants via GTK3/Cairo. Detects DDoS (persistent loops), port scans (parallel $H_0$ bands), and slow exfiltration (bridging components). 0.03% FPR on CIC‑IDS2017. | First public release (2026) — published |

---

## 🔬 Cryptographic Permutations

| Project | Description | Status |
|:--------|:------------|:-------|
| **[Krakken-2048 Abyssal](https://github.com/effjy/krakken)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32527359-blue)](https://doi.org/10.6084/m9.figshare.32527359)<br><br>A 2048-bit cryptographic permutation fusing an SPN core (GF(2⁸) S-box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed for high-assurance sponge constructions. | First public release (2026) — published |
| **[Krakken-2048 Butterfly](https://github.com/effjy/krakken-butterfly)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-butterfly) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-butterfly) [![DOI](https://img.shields.io/badge/DOI-10.6084/m9.figshare.32527287-blue)](https://doi.org/10.6084/m9.figshare.32527287)<br><br>An evolution of the Krakken-2048 design featuring a novel XOR-Rotation Butterfly Diffusion (XRBD) layer that achieves full word-level avalanche across 32 words in a single 5-stage pass. This additional mixing stage enables a round count reduction from 10 to 8 while improving security margins. | First public release (2026) — published |

---

## 🛠️ Software Applications

| Project | Description | Status |
|:--------|:------------|:-------|
| **[Krakken-Disk](https://github.com/effjy/krakken-disk/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk) [![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk)<br><br>A post-quantum encrypted disk manager for Linux combining Kyber-1024/X448 hybrid KEM with AVX2-accelerated wide-state permutations and strong plausible deniability. | Stable release available |
| **[Krakken-Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk-butterfly) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk-butterfly) [![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk-butterfly) ![NEW](https://img.shields.io/badge/NEW-800080?style=flat-square)<br><br>An evolution of Krakken-Disk that replaces the original permutation with the **Krakken-2048 Butterfly** permutation. Inherits all features (Kyber‑1024/X448 KEM, plausible deniability, AVX2 acceleration) while benefiting from the faster 8‑round design and the novel XRBD diffusion layer. | Stable release available |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/secure_mount) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/secure_mount) [![GTK](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/secure_mount)<br><br>A modern GTK3 graphical frontend for gocryptfs that makes mounting, unmounting, and initializing encrypted volumes effortless. Features desktop integration, secure terminal password entry, and one-click volume management. | Stable release available |
| **[Secure Wipe](https://github.com/effjy/swipe)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/swipe) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/swipe) [![Standards](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/swipe)<br><br>Command-line data sanitization utility for secure environments — NIST SP 800-88 compliant file, directory, free space, and RAM wiping. The interactive, text-based counterpart to Virtual Wipe Turbo. | Stable release available |
| **[Usage](https://github.com/effjy/usage/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/usage) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/usage) [![GTK](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/usage) [![UI Theme](https://img.shields.io/badge/UI%20Theme-Tokyo%20Night-purple)](https://github.com/effjy/usage)<br><br>A real-time network traffic and bandwidth monitoring tool written in C and built with GTK+ 3. Displays current speeds, records session statistics, and draws a live graph of incoming and outgoing traffic. Styled with a premium Tokyo Night dark theme. | Stable release available |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/vwipe) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/vwipe) [![Standards](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/vwipe) [![Turbo Engine](https://img.shields.io/badge/engine-8--core%20Turbo-00FFCC)](https://github.com/effjy/vwipe)<br><br>High-performance, forensic-grade secure erasure suite for storage and volatile memory (RAM), aligned with NIST SP 800-88 Rev. 1. Features a multi-threaded engine, GTK3 dark theme UI, and secure CLI memory purger. | Stable release available |

---

## 🎯 Research Interests

- **Wide‑state permutation design for post‑quantum symmetric cryptography**  
- **SPN‑ARX hybrid architectures** (invariant subspace resistance, algebraic degree propagation)  
- **Topological data analysis for intrusion detection** (persistent homology, Vietoris‑Rips complexes)  
- **Hardware‑assisted memory safety** (Intel MPK, temporal safety, control‑flow isolation)  
- **Side‑channel resistant & constant‑time implementations**  
- **Automated cryptanalysis** (MILP, SAT/SMT solvers) of mixed constructions  
- **Deniable encryption & hidden volume plausibility**  
- **Forensic‑grade sanitization and cryptographic erasure** (NIST SP 800‑88)  
- **Mode design for large‑state sponges** (keyed duplex, AEAD)

---

## 📖 Background

Over 20 years as a Level 3 security analyst, network administrator, and technical specialist have given me a rare bridge between operational security and cryptographic design. For more than a decade, I have independently researched symmetric primitives, focusing specifically on how SPN and ARX paradigms can be fused to cancel each other’s weaknesses. The Krakken project is the embodiment of that philosophy: every S‑box, every rotation, every linear layer is chosen to neutralize the cryptanalytic vulnerabilities of the others.

---

## 📬 Contact & Profiles

| Platform     | Link |
|--------------|------|
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
