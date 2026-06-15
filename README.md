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

---

## 🛠️ Applications

<sub>Production-ready security tools for Linux.</sub>

| Project | Tech | What it does |
|:---|:---|:---|
| <a href="https://github.com/effjy/axis/"><img src="titles/axis-title.svg" height="44" alt="Axis"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![PQ](https://img.shields.io/badge/PQ-8a2be2?style=flat-square) | Ultra-secure encrypted disk manager — AES-256-GCM, Kyber-1024/X448 hybrid KEM, plausible deniability, GTK GUI. |
| <a href="https://github.com/effjy/axis-secret/"><img src="titles/calculator-vault-title.svg" height="52" alt="Calculator Vault"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![PQ](https://img.shields.io/badge/PQ-8a2be2?style=flat-square) | A working GTK3 calculator that secretly unlocks Axis with the right passcode — a post-quantum vault hiding in plain sight. |
| <a href="https://github.com/effjy/ciphers/"><img src="titles/ciphers-title.svg" height="44" alt="Ciphers"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![AEAD](https://img.shields.io/badge/AEAD-teal?style=flat-square) | File encryption with Kyber-1024/X448 KEM over AES-256-GCM & XChaCha20, Argon2id, and locked non-dumpable memory. |
| <a href="https://github.com/effjy/czip/"><img src="titles/czip-title.svg" height="44" alt="Czip"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![XChaCha20](https://img.shields.io/badge/XChaCha20-teal?style=flat-square) | First archiver to fuse multithreaded zstd with XChaCha20-Poly1305, Argon2id, file splitting and auto-reassembly. |
| <a href="https://github.com/effjy/krakken-disk/"><img src="titles/krakken-disk-title.svg" height="52" alt="Krakken-Disk"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![PQ](https://img.shields.io/badge/PQ-8a2be2?style=flat-square) | Encrypted disk manager driven by the custom **Krakken-2048** wide-state permutation. |
| <a href="https://github.com/effjy/krakken-disk-butterfly/"><img src="titles/krakken-disk-butterfly-title.svg" height="52" alt="Krakken-Disk Butterfly"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![PQ](https://img.shields.io/badge/PQ-8a2be2?style=flat-square) | Krakken-Disk on the **Butterfly** permutation — faster throughput, stronger margins. |
| <a href="https://github.com/effjy/krakken-disk-butterfly-cli/"><img src="titles/krakken-disk-butterfly-cli-title.svg" height="52" alt="Krakken-Disk Butterfly CLI"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![CLI](https://img.shields.io/badge/CLI-555?style=flat-square) | Headless build for servers and automation scripts. |
| <a href="https://github.com/effjy/pqpman/"><img src="titles/pqpman-title.svg" height="44" alt="PQPMan"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![PQ](https://img.shields.io/badge/PQ-8a2be2?style=flat-square) | **The first password manager built on post-quantum cryptography** — Kyber-1024/X448 hybrid KEM over AES-256-GCM & XChaCha20-Poly1305, behind one master password. |
| <a href="https://github.com/effjy/swipe"><img src="titles/secure-wipe-title.svg" height="52" alt="Secure Wipe"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![NIST](https://img.shields.io/badge/NIST_800--88-36454F?style=flat-square) | Lightweight CLI sanitizer for files, directories, free space and RAM. |
| <a href="https://github.com/effjy/vwipe"><img src="titles/virtual-wipe-turbo-title.svg" height="52" alt="Virtual Wipe Turbo"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![NIST](https://img.shields.io/badge/NIST_800--88-36454F?style=flat-square) | High-performance secure-erasure suite for storage and memory, with a GTK3 UI. |

<details open>
<summary><b>More utilities &amp; tools</b></summary>

<br>

| Project | Tech | What it does |
|:---|:---|:---|
| <a href="https://github.com/effjy/chkrootkit-gui/"><img src="titles/chkrootkit-gui-title.svg" height="52" alt="Chkrootkit GUI"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Color-coded GTK3 front-end for **chkrootkit** with live scan output and false-positive filtering. |
| <a href="https://github.com/effjy/connmon/"><img src="titles/connection-monitor-title.svg" height="52" alt="Connection Monitor"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Real-time TCP connection monitor — reads `/proc/net/tcp`, resolves owning process per socket, cyber-themed live table. |
| <a href="https://github.com/effjy/fordump"><img src="titles/forensic-dump-title.svg" height="52" alt="Forensic Dump"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Multithreaded disk acquisition with file carving (JPEG/PNG/PDF/ZIP) and key/credential search. |
| <a href="https://github.com/effjy/lynis-gui/"><img src="titles/lynis-gui-title.svg" height="52" alt="Lynis GUI"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Color-coded GTK3 front-end for the **Lynis** security auditor with live audit output and one-click reports. |
| <a href="https://github.com/effjy/memscan/"><img src="titles/memscan-title.svg" height="44" alt="Memscan"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![Linux](https://img.shields.io/badge/Linux-555?style=flat-square&logo=linux&logoColor=white) | Scans a live process's memory for byte patterns or file magic via `/proc/<pid>/mem`. |
| <a href="https://github.com/effjy/limiter/"><img src="titles/network-speed-limiter-title.svg" height="52" alt="Network Speed Limiter"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Bandwidth limiter capping combined up/down speed on any interface via Linux `tc`, with a systemd service to reapply at boot. |
| <a href="https://github.com/effjy/entropy/"><img src="titles/entropy-title.svg" height="44" alt="Entropy"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![CSPRNG](https://img.shields.io/badge/CSPRNG-teal?style=flat-square) | CSPRNG password generator with an entropy analyzer that penalizes repeats, sequences and dictionary words. |
| <a href="https://github.com/effjy/entropy-gui/"><img src="titles/entropy-gui-title.svg" height="52" alt="Entropy GUI"></a> ⭐ | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Desktop edition — naive vs. realistic entropy, color-coded strength meter, one-click copy. |
| <a href="https://github.com/effjy/ram/"><img src="titles/ram-visualizer-title.svg" height="44" alt="RAM Visualizer"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | RAM analyzer — top memory-consuming processes, live Cairo ring gauges and bar charts, verified process kills. |
| <a href="https://github.com/effjy/secure_mount/"><img src="titles/secure-mount-title.svg" height="52" alt="Secure Mount"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | GTK3 frontend for **gocryptfs** — mount, unmount and init encrypted volumes. |
| <a href="https://github.com/effjy/sizer"><img src="titles/sizer-title.svg" height="44" alt="Sizer"></a> ⭐ | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Threaded disk-space analyzer with live percentage bars, an interactive donut and drill-down. |
| <a href="https://github.com/effjy/syshash/"><img src="titles/syshash-title.svg" height="44" alt="Syshash"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![SHA3-512](https://img.shields.io/badge/SHA3--512-teal?style=flat-square) | File-integrity monitor that recursively hashes a directory and flags any change — CLI plus a GTK3 desktop app. |
| <a href="https://github.com/effjy/usage/"><img src="titles/usage-title.svg" height="44" alt="Usage"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![GTK3](https://img.shields.io/badge/GTK3-teal?style=flat-square) | Real-time network monitor with live speeds, session stats and a Tokyo Night graph. |
| <a href="https://github.com/effjy/viewer"><img src="titles/viewer-title.svg" height="44" alt="Viewer"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![X11](https://img.shields.io/badge/X11-555?style=flat-square) | RAM-only image viewer — locks pixels in physical memory, zeroes on teardown. |

</details>

---

## ⭐ Featured

<div align="center">
  <br>

  <a href="https://github.com/effjy/ciphers"><img src="titles/ciphers-title.svg" height="56" alt="Ciphers"></a>

  <br>
  <sub>v1.0.3</sub>

  <br><br>

  <a href="https://github.com/effjy/ciphers"><img src="https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a" alt="MIT License"></a>
  <a href="https://github.com/effjy/ciphers"><img src="https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a" alt="C"></a>
  <a href="https://github.com/effjy/ciphers"><img src="https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Linux"></a>
  <a href="https://github.com/effjy/ciphers"><img src="https://img.shields.io/badge/Security-AES--256--GCM-teal?style=flat-square&labelColor=1a1a1a" alt="AES-256-GCM"></a>
  <a href="https://github.com/effjy/ciphers"><img src="https://img.shields.io/badge/PQC-Kyber--1024%20%2B%20X448-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Kyber-1024 + X448"></a>

  <br><br>
  <b>A simple, secure GTK3 app for file encryption — now with post-quantum hybrid key encapsulation.</b>
  <br>
  <sub>Kyber-1024 + X448 hybrid KEM · AES-256-GCM / XChaCha20-Poly1305 · Argon2id · chunked authenticated streaming · locked non-dumpable memory.</sub>

  <br><br>
  <a href="https://github.com/effjy/ciphers">
    <img src="https://github.com/effjy/ciphers/raw/main/data/screenshot.png" width="500px" alt="Ciphers main window">
  </a>
  <br>
  <sub><i>The Ciphers main window — pick a cipher, key strength and the optional post-quantum hybrid layer, then encrypt or decrypt with a single password</i></sub>

  <br><br>
  <a href="https://github.com/effjy/ciphers"><b>Explore the repository →</b></a>
</div>

---

## 🔬 Systems Security

<sub>Hardware-assisted memory safety &amp; defensive systems.</sub>

| Project | Tech | What it does |
|:---|:---|:---|
| <a href="https://github.com/effjy/honeycrypt"><img src="titles/honeycrypt-title.svg" height="40" alt="HoneyCrypt"></a> | ![C99](https://img.shields.io/badge/Language-C99-teal?style=flat-square&labelColor=1a1a1a) ![DOI](https://img.shields.io/badge/DOI-8a2be2?style=flat-square) | DTE vault returning valid decoys on wrong passcodes — no offline brute-force feedback. <sub>(2026)</sub> |
| <a href="https://github.com/effjy/kagealloc"><img src="titles/kagealloc-title.svg" height="40" alt="KageAlloc"></a> | ![MPK](https://img.shields.io/badge/Intel_MPK-0071c5?style=flat-square&logo=intel&logoColor=white) ![DOI](https://img.shields.io/badge/DOI-8a2be2?style=flat-square) | MPK-backed allocator with temporal safety and control-flow isolation at 3.8% overhead. <sub>(2026)</sub> |
| <a href="https://github.com/effjy/opsec-linux/"><img src="titles/opsec-linux-title.svg" height="52" alt="OpSec Linux"></a> | ![Linux](https://img.shields.io/badge/Linux-555?style=flat-square&logo=linux&logoColor=white) ![Guide](https://img.shields.io/badge/Guide-teal?style=flat-square) | Paranoid-grade hardening playbook — LUKS2, nftables, MAC, auditd, anti-forensics, copy-paste commands. |
| <a href="https://github.com/effjy/opsec-windows/"><img src="titles/opsec-windows-title.svg" height="52" alt="OpSec Windows"></a> | ![Windows](https://img.shields.io/badge/Windows-0078d6?style=flat-square&logo=windows&logoColor=white) ![Guide](https://img.shields.io/badge/Guide-teal?style=flat-square) | Win 10/11 &amp; Server playbook — BitLocker, Credential Guard, ASR, AppLocker/WDAC, PowerShell. |
| <a href="https://github.com/effjy/tids"><img src="titles/tids-title.svg" height="44" alt="TIDS"></a> | ![C99](https://img.shields.io/badge/Language-C99-teal?style=flat-square&labelColor=1a1a1a) ![DOI](https://img.shields.io/badge/DOI-8a2be2?style=flat-square) | Topological IDS using persistent homology on 5D flow clouds — 0.03% FPR on CIC-IDS2017. <sub>(2026)</sub> |

---

## 🧬 Cryptography

<sub>Symmetric permutations &amp; cryptanalysis.</sub>

| Project | Tech | What it does |
|:---|:---|:---|
| <a href="https://github.com/effjy/krakken"><img src="titles/krakken-abyssal-title.svg" height="52" alt="Krakken-2048 Abyssal"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![DOI](https://img.shields.io/badge/DOI-8a2be2?style=flat-square) | 2048-bit SPN–ARX hybrid permutation for high-assurance sponge constructions. <sub>(2026)</sub> |
| <a href="https://github.com/effjy/krakken-butterfly"><img src="titles/krakken-butterfly-title.svg" height="52" alt="Krakken-2048 Butterfly"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![DOI](https://img.shields.io/badge/DOI-8a2be2?style=flat-square) | Adds the XRBD layer — full avalanche in 8 rounds, stronger margins than the original 10. <sub>(2026)</sub> |
| <a href="https://github.com/effjy/krakken-butterfly-bounds"><img src="titles/krakken-bounds-title.svg" height="52" alt="Krakken-2048 Bounds"></a> | ![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white) ![MILP](https://img.shields.io/badge/MILP-teal?style=flat-square) | MILP-proven bounds for XRBD — 229 active S-boxes / 8 rounds, single-char bound 2⁻¹³⁷⁴. <sub>(2026)</sub> |
| <a href="https://github.com/effjy/krakken-harness/"><img src="titles/krakken-harness-title.svg" height="52" alt="Krakken Harness"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![Tests](https://img.shields.io/badge/18%2F18-teal?style=flat-square) | Regression harness for Krakken-2048 and the Disk V5 format — KAT, avalanche, tamper checks. |
| <a href="https://github.com/effjy/krakken-cryptanalysis"><img src="titles/krakken-cryptanalysis-title.svg" height="52" alt="Krakken Cryptanalysis"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![NIST](https://img.shields.io/badge/NIST_800--22-36454F?style=flat-square) | The validation battery — SAC/diffusion, NIST SP 800-22, sponge-hash collision tests + MILP bounds. <sub>(2026)</sub> |

---

## 📚 Learning

| Project | Tech | What it does |
|:---|:---|:---|
| <a href="https://github.com/effjy/learning-c/"><img src="titles/learning-c-title.svg" height="52" alt="Learning C"></a> | ![C](https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a) ![Tutorial](https://img.shields.io/badge/Tutorial-teal?style=flat-square) | From-scratch guide — compilation, pointers, structs, manual memory + 5 hands-on exercises. |
| <a href="https://github.com/effjy/learning-python/"><img src="titles/learning-python-title.svg" height="52" alt="Learning Python"></a> | ![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white) ![Tutorial](https://img.shields.io/badge/Tutorial-teal?style=flat-square) | From-scratch guide — types, collections, functions, files + 5 hands-on exercises. |

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
