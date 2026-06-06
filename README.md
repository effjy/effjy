# 👤 About Me

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=500&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

<p align="center">
  <b>By day</b> — Network administrator & security analyst (operational security, digital forensics) <br>
  <b>By night</b> — Independent cryptographic researcher, designing symmetric primitives and high‑assurance security tools
</p>

</div>

> [!NOTE]
> My work centers on the **Krakken family** of wide‑state SPN‑ARX hybrid permutations, plus a surrounding ecosystem: post‑quantum encrypted volume managers, forensic‑grade sanitization utilities, hardware‑assisted memory allocators, topological intrusion detection, and deniable encryption vaults.

> [!TIP]
> **⭐ If you find my work valuable, please consider starring the [Axis (Galactic Edition)](https://github.com/effjy/axis) repository (or any other project you like)!**  
> Stars help others discover these projects and motivate continued development.  
> *Even one star makes a huge difference – thank you! 🙏*

<br>

<p align="center">
  <a href="#featured"><b>⭐ Featured Project</b></a> • 
  <a href="#hardware-memory-safety"><b>🔬 Systems Security</b></a> • 
  <a href="#crypto-permutations"><b>🧬 Cryptography</b></a> • 
  <a href="#software-apps"><b>🛠️ Applications</b></a> • 
  <a href="#research"><b>🎯 Research</b></a> • 
  <a href="#background"><b>📖 Background</b></a> • 
  <a href="#contact"><b>📬 Contact</b></a>
</p>

<br>

---

<h2 id="featured" align="center">⭐ Featured Project — <a href="https://github.com/effjy/axis">Axis (Galactic Edition)</a></h2>

<div align="center">
  <br>
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/axis_logo.png" width="180" alt="Axis Galactic Edition GUI">
  </a>
  <br><br>

  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a" alt="MIT License"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Language-C11-teal?style=flat-square&labelColor=1a1a1a" alt="C11"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Linux"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Security-AES--256--GCM-teal?style=flat-square&labelColor=1a1a1a" alt="AES-256-GCM"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Release-New-800080?style=flat-square&labelColor=1a1a1a" alt="NEW"></a>
  
  <br><br>
  <b>An ultra‑secure encrypted disk manager for Linux, powered by hardware‑accelerated AES‑256‑GCM.</b>
  <br>
  Driven by the <b>AES‑256‑GCM permutation</b> with AES‑NI and AVX2 acceleration, it delivers high‑throughput authenticated encryption. Combines lattice‑based KEM (Kyber‑1024), elliptic‑curve key exchange (X448), and hardware acceleration – your data stays private even against future quantum adversaries.
  <br><br>
  
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/screenshot.png" width="680" alt="Axis Galactic Edition GUI" style="border-radius: 8px; box-shadow: 0 4px 20px rgba(0,0,0,0.5);">
  </a>
  <br>
  <sub><i>Dark‑themed GTK dashboard for one‑click volume management</i></sub>
</div>

<br>

### 🌌 Why it stands out

- 🛡️ **Hardware‑accelerated AES‑256‑GCM** — uses AES‑NI and AVX2 for fast, secure authenticated encryption.
- 🧬 **Hybrid KEM** — Kyber‑1024 + X448: breaking either scheme alone never exposes your keys.
- ⚡ **Zero-Overhead Processing** — AES-NI/AVX2 instructions deliver high throughput with minimal CPU load.
- 🌑 **Plausible deniability** — IND‑RND compliant: volumes have no headers, signatures, or metadata → indistinguishable from random noise.
- 🔒 **Brute‑force hardened** — Argon2id locked to 1 GB RAM makes GPU/ASIC attacks uneconomic.
- 🐧 **FUSE 3 mounting** — encrypted containers appear as ordinary read‑write directories.

<div align="center">
  <a href="https://github.com/effjy/axis"><b>📦 Explore the repository →</b></a>
</div>

<br>

---

<h2 id="hardware-memory-safety">🔬 Hardware‑Assisted Memory Safety & Systems Security</h2>

| Project | Technology Stack & Identifiers | Description & Benchmarks |
|:---|:---|:---|
| **[KageAlloc](https://github.com/effjy/kagealloc)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/kagealloc) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/kagealloc) <br> [![Hardware: Intel MPK](https://img.shields.io/badge/Hardware-Intel%20MPK-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/kagealloc) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32529792-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32529792) | High‑performance memory allocator using **Intel MPK** for temporal safety, metadata integrity, and control‑flow isolation. <br> • **RICCG**: Defeats PKRU hijacking. <br> • **BKR**: Low‑overhead quarantine. <br> • **TIMP**: Thread‑isolated metadata. <br> 📊 **3.8% overhead** over standard `ptmalloc`. *(Published 2026)* |
| **[TIDS](https://github.com/effjy/tids)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C99](https://img.shields.io/badge/Language-C99-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/tids) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/tids) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3-8a2be2?style=flat-square&labelColor=1a1a1a)](https://gtk.org) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32536887-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32536887) | **Topological Intrusion Detection System** — real‑time NIDS using persistent homology. <br> • Transforms flow features into 5D point clouds. <br> • Computes Vietoris–Rips filtrations. <br> • Visualizes *H₀*/*H₁* invariants in GTK3/Cairo. <br> 📊 **0.03% FPR** on CIC‑IDS2017. *(Published 2026)* |
| **[HoneyCrypt](https://github.com/effjy/honeycrypt)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: ANSI C99](https://img.shields.io/badge/Language-ANSI%20C99-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/honeycrypt) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/honeycrypt) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3-8a2be2?style=flat-square&labelColor=1a1a1a)](https://gtk.org) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32537733-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32537733) | **Distribution‑Transforming Encryption (DTE) vault** — replaces authentication errors with plausible decoys (Luhn‑valid cards, BIP39 seeds, GPS, medical records). <br> • Incorrect passcode returns a syntactically valid decoy, denying offline brute‑force feedback. <br> • Includes a 21‑slot decoy grid, four high‑fidelity synthesizers, and a brute‑force simulator. *(Published 2026)* |

<br>

---

<h2 id="crypto-permutations">🔬 Cryptographic Permutations</h2>

| Project | Mathematical Stack & Identifiers | Description & Architectural Features |
|:---|:---|:---|
| **[Krakken-2048 Abyssal](https://github.com/effjy/krakken)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32527359-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32527359) | A **2048‑bit permutation** fusing an SPN core (GF(2⁸) S‑box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed specifically for high‑assurance sponge constructions. *(Published 2026)* |
| **[Krakken-2048 Butterfly](https://github.com/effjy/krakken-butterfly)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-butterfly) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-butterfly) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32527287-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32527287) | Evolution of Krakken‑2048 with the **XOR‑Rotation Butterfly Diffusion (XRBD)** layer. <br> • Achieves full word‑level avalanche across 32 words in a single 5‑stage pass. <br> • Enables round reduction from 10 to 8 while improving security margins. *(Published 2026)* |

<br>

---

<h2 id="software-apps">🛠️ Software Applications</h2>

| Project | Security & Tech Stack | Description & Status |
|:---|:---|:---|
| **[Axis (Galactic Edition)](https://github.com/effjy/axis/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/axis) <br> [![Security: Post-Quantum + AES](https://img.shields.io/badge/Security-Post--Quantum--%2B--AES-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/axis) | Ultra‑secure encrypted disk manager with hardware‑accelerated AES‑256‑GCM, Kyber‑1024/X448 hybrid KEM, plausible deniability, and GTK GUI. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/axis/) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/axis/) |
| **[Krakken-Disk](https://github.com/effjy/krakken-disk/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk) <br> [![Security: Post-Quantum](https://img.shields.io/badge/Security-Post--Quantum-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk) | Post‑quantum encrypted disk manager for Linux. Kyber‑1024/X448 hybrid KEM, AVX2‑accelerated wide‑state permutations, plausible deniability. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk/) |
| **[Krakken-Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly) <br> [![Security: Post-Quantum](https://img.shields.io/badge/Security-Post--Quantum-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly) | Same features as Krakken‑Disk, but with the **Krakken‑2048 Butterfly** permutation — highly secure, faster 8‑round design and XRBD diffusion. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly/) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/krakken-disk-butterfly/) |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/secure_mount) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3.0-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/secure_mount) | Modern GTK3 frontend for **gocryptfs** — effortless mounting, unmounting, and initializing encrypted volumes. Desktop integration, secure password entry. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/secure_mount/) |
| **[Secure Wipe](https://github.com/effjy/swipe)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/swipe) <br> [![Standards: NIST SP 800-88](https://img.shields.io/badge/Standards-NIST%20SP%20800--88-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/swipe) | CLI data sanitization utility — NIST SP 800‑88 compliant file, directory, free‑space, and RAM wiping. Interactive text‑based interface. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/swipe) |
| **[Usage](https://github.com/effjy/usage/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/usage) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3.0-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/usage) | Real‑time network traffic monitor with GTK+3 — current speeds, session statistics, live graph. Styled with **Tokyo Night** dark theme. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/usage/) |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/vwipe) <br> [![Standards: NIST SP 800-88](https://img.shields.io/badge/Standards-NIST%20SP%20800--88-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/vwipe) | High‑performance secure‑erasure suite for storage and volatile memory. Multi‑threaded engine, GTK3 dark theme, secure CLI memory purger. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/vwipe) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/vwipe) |
| **[Viewer](https://github.com/effjy/viewer)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/viewer) <br> [![Platform: X11](https://img.shields.io/badge/Platform-X11-8a2be2?style=flat-square&labelColor=1a1a1a)]() <br> [![Security: mlock & secure zero](https://img.shields.io/badge/Security-mlock%20%26%20secure%20zero-red?style=flat-square&labelColor=1a1a1a)]() | RAM‑only image viewer for X11 — locks pixel data in physical RAM, prevents swap leaks, securely zeros memory on teardown. Supports JPEG/PNG with dynamic scaling. <br> 🏷️ [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/viewer) |

<br>

---

<h2 id="research">🎯 Research Interests</h2>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🧬 Cryptographic Primitives & Design
- **Wide‑state permutation design** for high-assurance sponge functions
- **SPN‑ARX hybrid architectures** (canceling reciprocal vulnerabilities)
- **Post‑quantum symmetric cryptography** and hybrid key encapsulation
- **Invariant subspace resistance** and algebraic degree propagation analysis
- **Mode design for large‑state sponges** (Keyed duplex, robust AEAD schemes)
- **Automated cryptanalysis** (applying MILP, SAT/SMT solvers on mixed constructions)

</td>
<td width="50%" valign="top">

#### 🛡️ Hardware, Forensics & Systems Security
- **Hardware‑assisted memory safety** (leveraging Intel MPK, control‑flow isolation)
- **Topological intrusion detection systems (TIDS)** (persistent homology, Vietoris–Rips complexes)
- **Side‑channel attack resistance** (designing strict constant‑time software implementations)
- **Forensic‑grade data sanitization** (alignment with NIST SP 800‑88 and FIPS 140‑3 standards)
- **Plausibly deniable encryption** (multi-slot decoy structures & hidden-volume engineering)

</td>
</tr>
</table>

<br>

---

<h2 id="background">📖 Background</h2>

Over **20 years** as a security analyst, network administrator, and technical specialist — representing a rare, crucial bridge between operational security and cryptographic design. For more than a decade, I have independently researched symmetric primitives, focusing on how the SPN and ARX paradigms can be fused so each cancels the other's weaknesses.

> [!TIP]
> The **Krakken** project embodies this philosophy: every S‑box, every rotation, and every linear layer is systematically chosen to neutralize the cryptanalytic vulnerabilities of the others.

<br>

---

<h2 id="contact">📬 Contact & Profiles</h2>

<p align="center">
  <a href="https://github.com/effjy"><img src="https://img.shields.io/badge/GitHub-%40effjy-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>&nbsp;
  <a href="https://orcid.org/0009-0005-6377-1675"><img src="https://img.shields.io/badge/ORCID-0009--0005--6377--1675-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>&nbsp;
  <a href="https://figshare.com/authors/Jean-Francois_Lachance-Caumartin/24086388"><img src="https://img.shields.io/badge/Figshare-Publications-36454F?style=for-the-badge&logo=figshare&logoColor=white" alt="Figshare"></a>&nbsp;
  <a href="https://gravatar.com/effjy"><img src="https://img.shields.io/badge/Gravatar-effjy-1F8CEB?style=for-the-badge&logo=gravatar&logoColor=white" alt="Gravatar"></a>&nbsp;
  <a href="https://x.com/jfclachance"><img src="https://img.shields.io/badge/X-%40jfclachance-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
</p>

<br>

---

<h3 align="center">🛠️ Tech Stack & Tooling</h3>
<div align="center">
  <!-- Languages -->
  <img src="C.svg" width="45" alt="C" title="C">&nbsp;
  <img src="CPP.svg" width="45" alt="C++" title="C++">&nbsp;
  <img src="Python-Dark.svg" width="45" alt="Python" title="Python">&nbsp;
  <img src="Bash-Dark.svg" width="45" alt="Bash" title="Bash">&nbsp;
  <img src="JavaScript.svg" width="45" alt="JavaScript" title="JavaScript">&nbsp;
  <img src="Java-Dark.svg" width="45" alt="Java" title="Java">&nbsp;
  <img src="Perl.svg" width="45" alt="Perl" title="Perl">&nbsp;
  <br><br>
  <!-- Frameworks, Markup & DevTools -->
  <img src="Linux-Dark.svg" width="45" alt="Linux" title="Linux">&nbsp;
  <img src="Ubuntu-Dark.svg" width="45" alt="Ubuntu" title="Ubuntu">&nbsp;
  <img src="Git.svg" width="45" alt="Git" title="Git">&nbsp;
  <img src="CMake-Dark.svg" width="45" alt="CMake" title="CMake">&nbsp;
  <img src="HTML.svg" width="45" alt="HTML" title="HTML">&nbsp;
  <img src="CSS.svg" width="45" alt="CSS" title="CSS">&nbsp;
  <img src="SVG-Dark.svg" width="45" alt="SVG" title="SVG">
</div>
