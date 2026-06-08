# 👤 About Me

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=560&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

<p align="center">
  <b>By day</b> — Network administrator & security analyst, focused on operational security and digital forensics. <br>
  <b>By night</b> — Independent cryptographic researcher designing symmetric primitives and high-assurance security tools.
</p>

</div>

> [!NOTE]
> I build practical, high-assurance security software backed by original cryptographic research. My work spans the **Krakken family** of wide-state SPN–ARX hybrid permutations and a surrounding ecosystem of post-quantum encrypted volume managers, forensic-grade sanitization utilities, hardware-assisted memory allocators, topological intrusion detection, and deniable encryption vaults.

> [!TIP]
> **⭐ If you find any of these projects useful, a star goes a long way.**  
> Stars help others discover the work and keep me motivated to maintain and extend it. Even one is genuinely appreciated — thank you! 🙏

<br>

<p align="center">
  <a href="#apps"><b>🛠️ Applications</b></a> • 
  <a href="#featured"><b>⭐ Featured Project</b></a> • 
  <a href="#hardware-memory-safety"><b>🔬 Systems Security</b></a> • 
  <a href="#crypto-permutations"><b>🧬 Cryptography</b></a> • 
  <a href="#research"><b>🎯 Research</b></a> • 
  <a href="#background"><b>📖 Background</b></a> • 
  <a href="#contact"><b>📬 Contact</b></a>
</p>

<br>

---

<h2 id="apps" align="center">🛠️ Flagship Applications</h2>

<p align="center"><i>Production-ready security tools for Linux. Stars on any of these are hugely appreciated. ⭐</i></p>

<br>

| Project | Security & Tech Stack | Description |
|:---|:---|:---|
| **[Axis (Galactic Edition)](https://github.com/effjy/axis/)** ⭐ | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/axis) <br> [![Security: Post-Quantum + AES](https://img.shields.io/badge/Security-Post--Quantum--%2B--AES-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/axis) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/axis/) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/axis/) | Ultra-secure encrypted disk manager with hardware-accelerated **AES-256-GCM** (AES-NI + AVX2), a **Kyber-1024 / X448** hybrid KEM, plausible deniability, and a clean GTK GUI. The flagship of the ecosystem. |
| **[Krakken-Disk](https://github.com/effjy/krakken-disk/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk) <br> [![Security: Post-Quantum](https://img.shields.io/badge/Security-Post--Quantum-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk/) | Post-quantum encrypted disk manager driven by the custom **Krakken-2048** wide-state permutation. Kyber-1024 / X448 hybrid KEM, AVX2 acceleration, and full plausible deniability. |
| **[Krakken-Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly) <br> [![Security: Post-Quantum](https://img.shields.io/badge/Security-Post--Quantum-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly/) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/krakken-disk-butterfly/) | Same feature set as Krakken-Disk, upgraded with the **Krakken-2048 Butterfly** permutation — a faster 8-round design using XOR-Rotation Butterfly Diffusion (XRBD) for stronger security margins. |
| **[Krakken-Disk Butterfly CLI](https://github.com/effjy/krakken-disk-butterfly-cli/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly-cli) <br> [![Security: Post-Quantum](https://img.shields.io/badge/Security-Post--Quantum-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly-cli) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-disk-butterfly-cli/) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/krakken-disk-butterfly-cli/) | Command-line version of Krakken-Disk Butterfly — same post-quantum encryption with the XRBD permutation, but without GUI dependencies, ideal for headless servers and automated scripts. |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/vwipe) <br> [![Standards: NIST SP 800-88](https://img.shields.io/badge/Standards-NIST%20SP%20800--88-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/vwipe) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/vwipe) [![Release: New](https://img.shields.io/badge/Release-New-9933ff?style=flat-square&labelColor=070807)](https://github.com/effjy/vwipe) | High-performance secure-erasure suite for storage and volatile memory. Multi-threaded wiping engine, GTK3 dark theme, and a secure CLI memory purger — NIST SP 800-88 aligned. |
| **[Secure Wipe](https://github.com/effjy/swipe)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/swipe) <br> [![Standards: NIST SP 800-88](https://img.shields.io/badge/Standards-NIST%20SP%20800--88-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/swipe) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/swipe) | NIST SP 800-88 compliant CLI sanitization utility for files, directories, free space, and RAM. Lightweight, scriptable, with an interactive text-based interface. |

<details open>
<summary><b>More utilities & tools</b></summary>

<br>

| Project | Security & Tech Stack | Description |
|:---|:---|:---|
| **[Password Toolkit](https://github.com/effjy/entropy/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/entropy) <br> [![CSPRNG: getrandom()](https://img.shields.io/badge/CSPRNG-getrandom()-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/entropy) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/entropy/) | A CSPRNG-backed password generator with a brutally honest entropy analyzer. Generates cryptographically secure passwords via `getrandom()` with rejection sampling, and estimates real-world password strength by penalizing repeated chars, sequences, and dictionary coverage. |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/secure_mount) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3.0-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/secure_mount) | Modern GTK3 frontend for **gocryptfs** — effortless mounting, unmounting, and initializing of encrypted volumes, with desktop integration and secure password entry. |
| **[Usage](https://github.com/effjy/usage/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/usage) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3.0-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/usage) | Real-time network traffic monitor in GTK+3 — live speeds, session statistics, and a live graph styled with the **Tokyo Night** dark theme. |
| **[Viewer](https://github.com/effjy/viewer)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/viewer) <br> [![Platform: X11](https://img.shields.io/badge/Platform-X11-8a2be2?style=flat-square&labelColor=1a1a1a)]() <br> | RAM-only image viewer for X11 — locks pixel data in physical RAM, prevents swap leaks, and securely zeros memory on teardown. Supports JPEG/PNG with dynamic scaling. |
| **[Forensic Dump](https://github.com/effjy/fordump)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)]() <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3-8a2be2?style=flat-square&labelColor=1a1a1a)]() <br> [![Features: Carving/Credentials](https://img.shields.io/badge/Features-Carving%2FCredentials-teal?style=flat-square&labelColor=1a1a1a)]() | Multi‑threaded forensic disk acquisition, file carving (JPEG/PNG/PDF/ZIP), and credential/key signature search with a GTK3 interface. |
| **[memscan](https://github.com/effjy/memscan/)** | [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/memscan) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/memscan) <br> [![Status: Stable](https://img.shields.io/badge/Status-Stable-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/memscan/) | Linux CLI tool that scans a live process's memory for byte patterns or file magic headers and dumps matching data. Reads `/proc/<pid>/maps` and `/proc/<pid>/mem` directly; supports custom hex/text patterns, ASCII and hex+ASCII output, writable-only filtering, address range restriction, and result capping. |
</details>

<br>

---

<h2 id="featured" align="center">⭐ Featured Project — <a href="https://github.com/effjy/axis">Axis (Galactic Edition)</a></h2>

<div align="center">
  <br>
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/axis_logo.png" width="180" alt="Axis Galactic Edition logo">
  </a>
  <br><br>

  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a" alt="MIT License"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Language-C11-teal?style=flat-square&labelColor=1a1a1a" alt="C11"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Linux"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Security-AES--256--GCM-teal?style=flat-square&labelColor=1a1a1a" alt="AES-256-GCM"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Release-New-800080?style=flat-square&labelColor=1a1a1a" alt="NEW"></a>
  
  <br><br>
  <b>An ultra-secure encrypted disk manager for Linux, powered by hardware-accelerated AES-256-GCM.</b>
  <br>
  Combining lattice-based KEM (<b>Kyber-1024</b>), elliptic-curve key exchange (<b>X448</b>), and AES-NI / AVX2 acceleration, Axis delivers high-throughput authenticated encryption that keeps your data private — even against future quantum adversaries.
  <br><br>
  
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/screenshot.png" width="680" alt="Axis Galactic Edition GUI" style="border-radius: 8px; box-shadow: 0 4px 20px rgba(0,0,0,0.5);">
  </a>
  <br>
  <sub><i>Dark-themed GTK dashboard for one-click volume management</i></sub>
</div>

<br>

### 🌌 Why it stands out

- 🛡️ **Hardware-accelerated AES-256-GCM** — AES-NI and AVX2 deliver fast, authenticated encryption.
- 🧬 **Hybrid KEM** — Kyber-1024 + X448: breaking either scheme alone never exposes your keys.
- ⚡ **Low-overhead processing** — AES-NI / AVX2 instructions maximize throughput at minimal CPU load.
- 🌑 **Plausible deniability** — IND-RND compliant: volumes carry no headers, signatures, or metadata, so they are indistinguishable from random noise.
- 🔒 **Brute-force hardened** — Argon2id locked to 1 GB RAM makes GPU/ASIC attacks uneconomical.
- 🐧 **FUSE 3 mounting** — encrypted containers appear as ordinary read-write directories.

<div align="center">
  <a href="https://github.com/effjy/axis"><b>📦 Explore the repository →</b></a>
</div>

<br>

---

<h2 id="hardware-memory-safety">🔬 Hardware-Assisted Memory Safety & Systems Security</h2>

| Project | Technology Stack & Identifiers | Description & Benchmarks |
|:---|:---|:---|
| **[KageAlloc](https://github.com/effjy/kagealloc)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/kagealloc) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/kagealloc) <br> [![Hardware: Intel MPK](https://img.shields.io/badge/Hardware-Intel%20MPK-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/kagealloc) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32529792-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32529792) | High-performance memory allocator using **Intel MPK** for temporal safety, metadata integrity, and control-flow isolation. <br> • **RICCG**: defeats PKRU hijacking. <br> • **BKR**: low-overhead quarantine. <br> • **TIMP**: thread-isolated metadata. <br> 📊 **3.8% overhead** over standard `ptmalloc`. *(Published 2026)* |
| **[TIDS](https://github.com/effjy/tids)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C99](https://img.shields.io/badge/Language-C99-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/tids) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/tids) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3-8a2be2?style=flat-square&labelColor=1a1a1a)](https://gtk.org) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32536887-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32536887) | **Topological Intrusion Detection System** — real-time NIDS using persistent homology. <br> • Transforms flow features into 5D point clouds. <br> • Computes Vietoris–Rips filtrations. <br> • Visualizes *H₀* / *H₁* invariants in GTK3/Cairo. <br> 📊 **0.03% FPR** on CIC-IDS2017. *(Published 2026)* |
| **[HoneyCrypt](https://github.com/effjy/honeycrypt)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: ANSI C99](https://img.shields.io/badge/Language-ANSI%20C99-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/honeycrypt) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/honeycrypt) <br> [![GUI: GTK3](https://img.shields.io/badge/GUI-GTK3-8a2be2?style=flat-square&labelColor=1a1a1a)](https://gtk.org) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32537733-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32537733) | **Distribution-Transforming Encryption (DTE) vault** — replaces authentication errors with plausible decoys (Luhn-valid cards, BIP39 seeds, GPS, medical records). <br> • An incorrect passcode returns a syntactically valid decoy, denying offline brute-force feedback. <br> • Includes a 21-slot decoy grid, four high-fidelity synthesizers, and a brute-force simulator. *(Published 2026)* |

<br>

---

<h2 id="crypto-permutations">🧬 Cryptographic Permutations</h2>

| Project | Mathematical Stack & Identifiers | Description & Architectural Features |
|:---|:---|:---|
| **[Krakken-2048 Abyssal](https://github.com/effjy/krakken)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32527359-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32527359) | A **2048-bit permutation** fusing an SPN core (GF(2⁸) S-box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed specifically for high-assurance sponge constructions. *(Published 2026)* |
| **[Krakken-2048 Butterfly](https://github.com/effjy/krakken-butterfly)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-butterfly) <br> [![Platform: Linux](https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-butterfly) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32527287-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32527287) | Evolution of Krakken-2048 with the **XOR-Rotation Butterfly Diffusion (XRBD)** layer. <br> • Achieves full word-level avalanche across 32 words in a single 5-stage pass. <br> • Reduces rounds from 10 to 8 while improving security margins. *(Published 2026)* |
| **[Krakken-2048 Bounds (XRBD Layer)](https://github.com/effjy/krakken-butterfly-bounds)** | [![License: MIT](https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a)](LICENSE) <br> [![Language: Python/MILP](https://img.shields.io/badge/Language-Python%20%7C%20MILP-teal?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-butterfly-bounds) <br> [![Solver: SCIP](https://img.shields.io/badge/Solver-SCIP-8a2be2?style=flat-square&labelColor=1a1a1a)](https://www.scipopt.org) <br> [![Paper](https://img.shields.io/badge/Paper-PDF-red?style=flat-square&labelColor=1a1a1a)](https://github.com/effjy/krakken-butterfly-bounds/blob/main/paper.pdf) <br> [![DOI](https://img.shields.io/badge/DOI-10.6084%2Ffigshare.32599689-teal?style=flat-square&labelColor=1a1a1a)](https://doi.org/10.6084/m9.figshare.32599689) | **Provable differential & linear bounds** for the XRBD permutation. <br> • Exact MILP model proves **229 active S‑boxes** over 8 rounds. <br> • Single‑characteristic bound: **2⁻¹³⁷⁴** (differential & linear). <br> • XRBD contribution isolated: SPN core alone admits 27 active S‑boxes at 2 rounds; with XRBD it rises to 37, then grows per round. <br> • All constants (MDS, S‑box, permutations) exhaustively verified. *(Paper, 2026)* |

<br>

---

<h2 id="research">🎯 Research Interests</h2>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🧬 Cryptographic Primitives & Design
- **Wide-state permutation design** for high-assurance sponge functions
- **SPN-ARX hybrid architectures** that cancel reciprocal vulnerabilities
- **Post-quantum symmetric cryptography** and hybrid key encapsulation
- **Invariant subspace resistance** and algebraic degree propagation analysis
- **Mode design for large-state sponges** (keyed duplex, robust AEAD schemes)
- **Automated cryptanalysis** (MILP, SAT/SMT solvers on mixed constructions)

</td>
<td width="50%" valign="top">

#### 🛡️ Hardware, Forensics & Systems Security
- **Hardware-assisted memory safety** (Intel MPK, control-flow isolation)
- **Topological intrusion detection** (persistent homology, Vietoris–Rips complexes)
- **Side-channel resistance** (strict constant-time implementations)
- **Forensic-grade data sanitization** (NIST SP 800-88, FIPS 140-3)
- **Plausibly deniable encryption** (multi-slot decoy structures, hidden-volume engineering)

</td>
</tr>
</table>

<br>

---

<h2 id="background">📖 Background</h2>

With over **20 years** as a security analyst, network administrator, and technical specialist, I sit at a rare intersection of operational security and cryptographic design. For more than a decade I have independently researched symmetric primitives, with a particular focus on how the SPN and ARX paradigms can be fused so that each cancels the other's weaknesses.

> [!TIP]
> The **Krakken** project embodies this philosophy: every S-box, every rotation, and every linear layer is deliberately chosen to neutralize the cryptanalytic vulnerabilities of the others.

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
