<div align="center">

# Jean-François Lachance-Caumartin

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=560&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

**Security analyst by day · cryptographic researcher by night.**
I build high-assurance security tools and design symmetric primitives.

<br>

<a href="#-applications"><b>Applications</b></a> &nbsp;·&nbsp;
<a href="#-featured"><b>Featured</b></a> &nbsp;·&nbsp;
<a href="#-systems-security"><b>Systems Security</b></a> &nbsp;·&nbsp;
<a href="#-cryptography"><b>Cryptography</b></a> &nbsp;·&nbsp;
<a href="#-learning"><b>Learning</b></a> &nbsp;·&nbsp;
<a href="#-contact"><b>Contact</b></a>

</div>

> [!TIP]
> ⭐ **A star goes a long way** — it helps others find the work and keeps me building. Thank you.

<br>

---

## 🛠️ Applications

<sub>Production-ready security tools for Linux.</sub>

| Project | Stack | What it does |
|:---|:---|:---|
| **[Axis](https://github.com/effjy/axis/)** ⭐ | `C` · Post-Quantum + AES | Ultra-secure encrypted disk manager — AES-256-GCM, Kyber-1024/X448 hybrid KEM, plausible deniability, GTK GUI. |
| **[Calculator Vault (Axis)](https://github.com/effjy/axis-secret/)** ⭐ | `C` · Hidden PQ Vault | A working GTK3 calculator that secretly unlocks Axis with the right passcode — a post-quantum vault hiding in plain sight. |
| **[Ciphers](https://github.com/effjy/ciphers/)** ⭐ | `C` · Post-Quantum + AEAD | File encryption with Kyber-1024/X448 KEM over AES-256-GCM & XChaCha20, Argon2id, and locked non-dumpable memory. |
| **[Czip](https://github.com/effjy/czip/)** | `C` · XChaCha20-Poly1305 | First archiver to fuse multithreaded zstd with XChaCha20-Poly1305, Argon2id, file splitting and auto-reassembly. |
| **[Krakken-Disk](https://github.com/effjy/krakken-disk/)** | `C` · Post-Quantum | Encrypted disk manager driven by the custom **Krakken-2048** wide-state permutation. |
| **[Krakken-Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** ⭐ | `C` · Post-Quantum | Krakken-Disk on the **Butterfly** permutation — faster throughput, stronger margins. |
| **[Krakken-Disk Butterfly CLI](https://github.com/effjy/krakken-disk-butterfly-cli/)** | `C` · Post-Quantum | Headless build for servers and automation scripts. |
| **[Secure Wipe](https://github.com/effjy/swipe)** | `C` · NIST SP 800-88 | Lightweight CLI sanitizer for files, directories, free space and RAM. |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** ⭐ | `C` · NIST SP 800-88 | High-performance secure-erasure suite for storage and memory, with a GTK3 UI. |

<details open>
<summary><b>More utilities &amp; tools</b></summary>

<br>

| Project | Stack | What it does |
|:---|:---|:---|
| **[Chkrootkit-gui](https://github.com/effjy/chkrootkit-gui/)** | `C` · GTK3 | Color-coded GTK3 front-end for **chkrootkit** with live scan output and false-positive filtering. |
| **[Connection Monitor](https://github.com/effjy/connmon/)** | `C` · GTK3 | Real-time TCP connection monitor — reads `/proc/net/tcp`, resolves owning process per socket, cyber-themed live table. |
| **[Forensic Dump](https://github.com/effjy/fordump)** | `C` · GTK3 | Multithreaded disk acquisition with file carving (JPEG/PNG/PDF/ZIP) and key/credential search. |
| **[Memscan](https://github.com/effjy/memscan/)** | `C` · Linux | Scans a live process's memory for byte patterns or file magic via `/proc/<pid>/mem`. |
| **[Network Speed Limiter](https://github.com/effjy/limiter/)** | `C` · GTK3 | Bandwidth limiter capping combined up/down speed on any interface via Linux `tc`, with a one-click systemd service to reapply at boot. |
| **[Password Toolkit](https://github.com/effjy/entropy/)** | `C` · getrandom() | CSPRNG password generator with an entropy analyzer that penalizes repeats, sequences and dictionary words. |
| **[Password Toolkit GUI](https://github.com/effjy/entropy-gui/)** | `C` · GTK3 | Desktop edition — naive vs. realistic entropy, color-coded strength meter, one-click copy. |
| **[RAM Visualizer](https://github.com/effjy/ram/)** | `C` · GTK3 | RAM analyzer — top memory-consuming processes, live Cairo ring gauges and bar charts, verified `SIGTERM`/`SIGKILL` process kills. |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** | `C` · GTK3 | GTK3 frontend for **gocryptfs** — mount, unmount and init encrypted volumes. |
| **[Sizer](https://github.com/effjy/sizer)** | `C` · GTK3 | Threaded disk-space analyzer with live percentage bars, an interactive donut and drill-down. |
| **[Syshash](https://github.com/effjy/syshash/)** | `C` · SHA3-512 | File-integrity monitor that recursively hashes a directory and flags any change. |
| **[Usage](https://github.com/effjy/usage/)** | `C` · GTK3 | Real-time network monitor with live speeds, session stats and a Tokyo Night graph. |
| **[Viewer](https://github.com/effjy/viewer)** | `C` · X11 | RAM-only image viewer — locks pixels in physical memory, zeroes on teardown. |

</details>

<br>

---

## ⭐ Featured

<div align="center">
  <br>
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/axis_logo.png" width="170" alt="Axis Galactic Edition logo">
  </a>

  ### Axis · Galactic Edition

  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a" alt="MIT License"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Language-C11-teal?style=flat-square&labelColor=1a1a1a" alt="C11"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Linux"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Security-AES--256--GCM-teal?style=flat-square&labelColor=1a1a1a" alt="AES-256-GCM"></a>

  <br><br>
  <b>An ultra-secure encrypted disk manager for Linux.</b>
  <br>
  <sub>Kyber-1024 + X448 hybrid KEM · AES-NI/AVX2 · plausible deniability · Argon2id · FUSE 3.</sub>

  <br><br>
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/screenshot.png" width="660" alt="Axis Galactic Edition GUI">
  </a>
  <br>
  <sub><i>Dark-themed GTK dashboard for one-click volume management</i></sub>

  <br><br>
  <a href="https://github.com/effjy/axis"><b>Explore the repository →</b></a>
</div>

<br>

---

## 🔬 Systems Security

<sub>Hardware-assisted memory safety &amp; defensive systems.</sub>

| Project | Stack | What it does |
|:---|:---|:---|
| **[HoneyCrypt](https://github.com/effjy/honeycrypt)** | `C99` · [DOI](https://doi.org/10.6084/m9.figshare.32537733) | DTE vault returning valid decoys on wrong passcodes — no offline brute-force feedback. <sub>(2026)</sub> |
| **[KageAlloc](https://github.com/effjy/kagealloc)** | Intel MPK · [DOI](https://doi.org/10.6084/m9.figshare.32529792) | MPK-backed allocator with temporal safety and control-flow isolation at 3.8% overhead. <sub>(2026)</sub> |
| **[OpSec Linux](https://github.com/effjy/opsec-linux/)** | Hardening Guide · Linux | Paranoid-grade hardening playbook — LUKS2, nftables, MAC, auditd, anti-forensics, copy-paste commands. |
| **[OpSec Windows](https://github.com/effjy/opsec-windows/)** | Hardening Guide · Windows | Win 10/11 &amp; Server playbook — BitLocker, Credential Guard, ASR, AppLocker/WDAC, PowerShell. |
| **[TIDS](https://github.com/effjy/tids)** | `C99` · [DOI](https://doi.org/10.6084/m9.figshare.32536887) | Topological IDS using persistent homology on 5D flow clouds — 0.03% FPR on CIC-IDS2017. <sub>(2026)</sub> |

<br>

---

## 🧬 Cryptography

<sub>Symmetric permutations &amp; cryptanalysis.</sub>

| Project | Stack | What it does |
|:---|:---|:---|
| **[Krakken-2048 Abyssal](https://github.com/effjy/krakken)** | `C` · [DOI](https://doi.org/10.6084/m9.figshare.32527359) | 2048-bit SPN–ARX hybrid permutation for high-assurance sponge constructions. <sub>(2026)</sub> |
| **[Krakken-2048 Butterfly](https://github.com/effjy/krakken-butterfly)** | `C` · [DOI](https://doi.org/10.6084/m9.figshare.32527287) | Adds the XRBD layer — full avalanche in 8 rounds, stronger margins than the original 10. <sub>(2026)</sub> |
| **[Krakken-2048 Bounds](https://github.com/effjy/krakken-butterfly-bounds)** | `Python/MILP` · [DOI](https://doi.org/10.6084/m9.figshare.32599689) | MILP-proven bounds for XRBD — 229 active S-boxes / 8 rounds, single-char bound 2⁻¹³⁷⁴. <sub>(2026)</sub> |
| **[Krakken Harness](https://github.com/effjy/krakken-harness/)** | `C` · 18/18 tests | Regression harness for Krakken-2048 and the Disk V5 format — KAT, avalanche, tamper checks. |
| **[Krakken Cryptanalysis](https://github.com/effjy/krakken-cryptanalysis)** | `C` · SAC · NIST · Collision | The validation battery — SAC/diffusion, NIST SP 800-22, sponge-hash collision tests + MILP bounds. <sub>(2026)</sub> |

<br>

---

## 📚 Learning

| Project | Stack | What it does |
|:---|:---|:---|
| **[Learning C](https://github.com/effjy/learning-c/)** | `C` · Tutorial | From-scratch guide — compilation, pointers, structs, manual memory + 5 hands-on exercises. |
| **[Learning Python](https://github.com/effjy/learning-python/)** | `Python` · Tutorial | From-scratch guide — types, collections, functions, files + 5 hands-on exercises. |

<br>

---

## 📬 Contact

<div align="center">

<a href="https://github.com/effjy"><img src="https://img.shields.io/badge/GitHub-%40effjy-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>&nbsp;
<a href="https://orcid.org/0009-0005-6377-1675"><img src="https://img.shields.io/badge/ORCID-0009--0005--6377--1675-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>&nbsp;
<a href="https://figshare.com/authors/Jean-Francois_Lachance-Caumartin/24086388"><img src="https://img.shields.io/badge/Figshare-Publications-36454F?style=for-the-badge&logo=figshare&logoColor=white" alt="Figshare"></a>&nbsp;
<a href="https://gravatar.com/effjy"><img src="https://img.shields.io/badge/Gravatar-effjy-1F8CEB?style=for-the-badge&logo=gravatar&logoColor=white" alt="Gravatar"></a>&nbsp;
<a href="https://x.com/jfclachance"><img src="https://img.shields.io/badge/X-%40jfclachance-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>

<br><br>

<sub><b>Tech &amp; tooling</b></sub>
<br>
<img src="C.svg" width="42" alt="C" title="C">&nbsp;
<img src="CPP.svg" width="42" alt="C++" title="C++">&nbsp;
<img src="Python-Dark.svg" width="42" alt="Python" title="Python">&nbsp;
<img src="Bash-Dark.svg" width="42" alt="Bash" title="Bash">&nbsp;
<img src="JavaScript.svg" width="42" alt="JavaScript" title="JavaScript">&nbsp;
<img src="Java-Dark.svg" width="42" alt="Java" title="Java">&nbsp;
<img src="Perl.svg" width="42" alt="Perl" title="Perl">
<br>
<img src="Linux-Dark.svg" width="42" alt="Linux" title="Linux">&nbsp;
<img src="Ubuntu-Dark.svg" width="42" alt="Ubuntu" title="Ubuntu">&nbsp;
<img src="Git.svg" width="42" alt="Git" title="Git">&nbsp;
<img src="CMake-Dark.svg" width="42" alt="CMake" title="CMake">&nbsp;
<img src="HTML.svg" width="42" alt="HTML" title="HTML">&nbsp;
<img src="CSS.svg" width="42" alt="CSS" title="CSS">&nbsp;
<img src="SVG-Dark.svg" width="42" alt="SVG" title="SVG">

</div>
