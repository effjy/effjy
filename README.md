<div align="center">

  <a href="https://github.com/effjy/effjy/"><img src="titles/jean-francois-title.svg" height="100%" alt="Jean-Francois Lachance-Caumartin"></a>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=560&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

**Security analyst by day · cryptographic researcher by night.**

I build high-assurance security tools and design symmetric primitives.

<sub>I work almost entirely in **C**, by choice — original cryptographic design & cryptanalysis, **post-quantum** applications on NIST standards (Kyber/ML-KEM, ML-DSA, SLH-DSA), digital forensics, and clean GTK3 front-ends. Original research, post-quantum by default, no dependencies, close to the metal.</sub>

---

<a href="https://github.com/effjy/effjy/"><img src="titles/recent-additions-title.svg" height="52" alt="Recent Additions"></a>

<a href="https://github.com/effjy/diskmon/"><b>Disk Monitor v1.0.2</b></a>
<br><br>
<a href="https://github.com/effjy/nwu/"><b>nwu — Novel Wiping Utility v1.5.0</b></a>
<br><br>
<a href="https://github.com/effjy/envision/"><b>Envision v1.0.1</b></a>
<br><br>
<a href="https://github.com/effjy/pq-sealed"><b>PQ-Sealed v1.0.1</b></a>

---

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

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/axis/"><img src="titles/axis-title.svg" height="52" alt="Axis"></a></div> | **GTK3 encrypted disk manager** — AES-256-GCM volumes behind a **Kyber-1024/X448 hybrid KEM**, with FUSE mounting and **IND-RND plausible deniability**. ⭐ |
| <div align="center"><a href="https://github.com/effjy/axis-secret/"><img src="titles/calc-title.svg" height="52" alt="Calculator Vault"></a></div> | **Working GTK3 calculator** that secretly launches **Axis** on a passcode — hiding that an encrypted disk manager is even installed. ⭐ |
| <div align="center"><a href="https://github.com/effjy/ciphers/"><img src="titles/ciphers-title.svg" height="52" alt="Ciphers"></a></div> | **GTK3 file encryptor** — **AEAD** ciphers (AES-256-GCM, XChaCha20-Poly1305) with an optional **Kyber-1024/X448 hybrid KEM** and Argon2id. |
| <div align="center"><a href="https://github.com/effjy/pq-audit/"><img src="titles/pq-audit-title.svg" height="52" alt="PQ-AUDIT"></a></div> | **Tamper-evident audit log** — append-only, hash-chained and forward-secure, sealed with post-quantum **ML-DSA/SLH-DSA** and Merkle proofs. |
| <div align="center"><a href="https://github.com/effjy/pq-note/"><img src="titles/pq-note-title.svg" height="52" alt="PQ-Note"></a></div> | **GTK3 encrypted notes app** — free-form notes sealed as one AEAD blob (AES-256-GCM / XChaCha20-Poly1305) behind a **Kyber-1024/X448 hybrid KEM** and Argon2id, unlocked by one master password. |
| <div align="center"><a href="https://github.com/effjy/pq-sealed/"><img src="titles/pq-sealed-title.svg" height="52" alt="PQ-Sealed"></a></div> | **Incremental encrypted backups** — deduplicating, content-addressed snapshots under a **Kyber-1024/X448 hybrid KEM**, manifests signed with **ML-DSA-65**. ⭐ |
| <div align="center"><a href="https://github.com/effjy/pq-sign/"><img src="titles/pq-sign-title.svg" height="52" alt="PQ-SIGN"></a></div> | **Post-quantum file signing** — detached **ML-DSA (FIPS 204)** & **SLH-DSA (FIPS 205)** signatures; secret keys sealed with Argon2id + AES-256-GCM. |
| <div align="center"><a href="https://github.com/effjy/pqotp/"><img src="titles/pqotp-title.svg" height="52" alt="PQOTP"></a></div> | **2FA authenticator** (GTK3 + CLI) — **TOTP/HOTP** seeds in a post-quantum hybrid-KEM vault behind one master password. |
| <div align="center"><a href="https://github.com/effjy/pqpman/"><img src="titles/pqpman-title.svg" height="52" alt="PQPMan"></a></div> | **GTK3 password manager** — vault sealed with AEAD and a **Kyber-1024/X448 hybrid KEM** behind one master password. |
| <div align="center"><a href="https://github.com/effjy/pqtransfer/"><img src="titles/pqtransfer-title.svg" height="52" alt="PQ Transfer"></a></div> | **Peer-to-peer file transfer** — serverless, end-to-end encrypted over a **Kyber-1024/X448 hybrid KEM**, with an optional passphrase to defeat MITM. |

<details open>
<summary><b>More utilities &amp; tools</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/chkrootkit-gui/"><img src="titles/chkrootkit-title.svg" height="65" alt="Chkrootkit GUI"></a></div> | **GTK3 front-end for chkrootkit** — live, color-coded rootkit scans with one-click false-positive filtering. |
| <div align="center"><a href="https://github.com/effjy/connmon/"><img src="titles/connmon-title.svg" height="52" alt="Connection Monitor"></a></div> | **Real-time TCP monitor** (GTK3) — reads `/proc/net/tcp` and maps every live connection to its owning process. |
| <div align="center"><a href="https://github.com/effjy/czip/"><img src="titles/czip-title.svg" height="52" alt="Czip"></a></div> | **Compress-and-encrypt archiver** — multithreaded **zstd** streamed through **XChaCha20-Poly1305**, with Argon2id keys and file splitting. |
| <div align="center"><a href="https://github.com/effjy/diskmon/"><img src="titles/diskmon-title.svg" height="52" alt="Disk Monitor"></a></div> | **Real-time disk I/O monitor** (C++/GTK4) — live read/write throughput from `/proc/diskstats` with a **Tokyo Night** Cairo graph and session peaks/averages. |
| <div align="center"><a href="https://github.com/effjy/entropy/"><img src="titles/entropy-title.svg" height="52" alt="Entropy"></a></div> | **CLI password generator** — `getrandom()` CSPRNG with an entropy analyzer that penalizes repeats, sequences and dictionary words. |
| <div align="center"><a href="https://github.com/effjy/entropy-gui/"><img src="titles/ent-gui-title.svg" height="52" alt="Entropy GUI"></a></div> | **GTK3 edition of Entropy** — naive vs. realistic password entropy with a color-coded strength meter and one-click copy. |
| <div align="center"><a href="https://github.com/effjy/envision/"><img src="titles/envision-title.svg" height="52" alt="Envision"></a></div> | **GTK3 system-security scanner** — audits your Linux box's posture (firewall, exposed ports, SSH, sudo, accounts, kernel hardening) and produces a severity-ranked report with copy-paste fixes, exportable to PDF. |
| <div align="center"><a href="https://github.com/effjy/fordump"><img src="titles/fordump-title.svg" height="52" alt="Forensic Dump"></a></div> | **GTK3 forensics tool** — multithreaded block-level disk imaging with file carving (JPEG/PNG/PDF/ZIP) and credential/key search. |
| <div align="center"><a href="https://github.com/effjy/limiter/"><img src="titles/limiter-title.svg" height="52" alt="Network Speed Limiter"></a></div> | **Bandwidth limiter** (GTK3 + CLI) — caps combined up/down speed on any interface via Linux `tc`, optionally as a boot-time service. |
| <div align="center"><a href="https://github.com/effjy/lynis-gui/"><img src="titles/lynis-title.svg" height="52" alt="Lynis GUI"></a></div> | **GTK3 front-end for Lynis** — live, color-coded security audits with a one-click pentest mode. |
| <div align="center"><a href="https://github.com/effjy/memscan/"><img src="titles/memscan-title.svg" height="52" alt="Memscan"></a></div> | **Live-memory scanner** (CLI) — searches a running process's `/proc/<pid>/mem` for byte patterns or file-magic headers. |
| <div align="center"><a href="https://github.com/effjy/mole/"><img src="titles/mole-title.svg" height="52" alt="Mole"></a></div> | **Secret scanner** — recursively greps a tree for leaked credentials via **regex + Shannon entropy**, with a CLI and a GTK3 triage UI. |
| <div align="center"><a href="https://github.com/effjy/multi-ciphers/"><img src="titles/mciphers-title.svg" height="52" alt="Multi Ciphers"></a></div> | **Dependency-free encryption CLI** — four **AEAD ciphers** (AES-256-GCM, XChaCha20, Serpent, Twofish) over an Argon2id KDF. ⭐ |
| <div align="center"><a href="https://github.com/effjy/nwu/"><img src="titles/nwu-title.svg" height="52" alt="Novel Wiping Utility"></a></div> | **SSD-aware secure-delete tool** (interactive + CLI) — combines a fast non-compressible **ChaCha20 overwrite** with per-file punch-hole and filesystem **TRIM** to wipe files, directories and free space. Also **wipes free RAM** to **clear leftover secrets from memory**. ⭐|
| <div align="center"><a href="https://github.com/effjy/ram/"><img src="titles/ram-title.svg" height="52" alt="RAM Vizualizer"></a></div> | **GTK3 + Cairo RAM analyzer** — top memory hogs, live ring gauges and bar charts, and verified-kill process termination. |
| <div align="center"><a href="https://github.com/effjy/rkhunter-gui/"><img src="titles/rkhunter-title.svg" height="52" alt="rkhunter GUI"></a></div> | **GTK3 front-end for rkhunter** — live, color-coded rootkit scans with a problems-only filter. |
| <div align="center"><a href="https://github.com/effjy/scrub/"><img src="titles/scrub-title.svg" height="52" alt="Scrub"></a></div> | **Dependency-free metadata scrubber** — natively strips Exif/XMP/IPTC (and C2PA) from JPEGs and PNGs before you share them. |
| <div align="center"><a href="https://github.com/effjy/secure_mount/"><img src="titles/smount-title.svg" height="52" alt="Secure Mount"></a></div> | **GTK3 front-end for gocryptfs** — initialize, mount and unmount encrypted volumes without touching the command line. |
| <div align="center"><a href="https://github.com/effjy/swipe"><img src="titles/swipe-title.svg" height="52" alt="Secure Wipe"></a></div> | **CLI data sanitizer** — irrecoverably wipes files, directories, free space and RAM to **NIST SP 800-88 / FIPS 140-3**, with SSD TRIM. |
| <div align="center"><a href="https://github.com/effjy/sizer"><img src="titles/sizer-title.svg" height="52" alt="Sizer"></a></div> | **GTK3 disk-space analyzer** — threaded scan from `/` with live percentage bars, an interactive donut and folder drill-down. |
| <div align="center"><a href="https://github.com/effjy/syshash/"><img src="titles/syshash-title.svg" height="52" alt="Syshash"></a></div> | **File-integrity monitor** (CLI + GTK3) — recursively hashes a tree with **SHA3-512**, baselines it, and flags any changed file on re-scan. ⭐ |
| <div align="center"><a href="https://github.com/effjy/usage/"><img src="titles/usage-title.svg" height="52" alt="Usage"></a></div> | **Real-time network monitor** (GTK3) — live up/down speeds and a **Tokyo Night** Cairo graph, with a settable usage limit that counts down and turns red when exceeded. |
| <div align="center"><a href="https://github.com/effjy/viewer"><img src="titles/viewer-title.svg" height="52" alt="Viewer"></a></div> | **RAM-only image viewer** (X11) — `mlock`s pixels in physical memory and zeroes them on teardown; JPEG/PNG, no swap leaks. |
| <div align="center"><a href="https://github.com/effjy/vwipe"><img src="titles/vwipe-title.svg" height="52" alt="Virtual Wipe Turbo"></a></div> | **Multi-core secure-erase suite** (GTK3) — saturates NVMe/SSD throughput wiping disks, free space and RAM to **NIST/FIPS** standards. |

</details>

---

## ⭐ Featured

<div align="center">
  <br>

  <a href="https://github.com/effjy/axis"><img src="titles/axis-title.svg" height="56" alt="Axis"></a>

<br>

  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/License-MIT-teal?style=flat-square&labelColor=1a1a1a" alt="MIT License"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Language-C-teal?style=flat-square&labelColor=1a1a1a" alt="C"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Platform-Linux-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Linux"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/Security-AES--256--GCM-teal?style=flat-square&labelColor=1a1a1a" alt="AES-256-GCM"></a>
  <a href="https://github.com/effjy/axis"><img src="https://img.shields.io/badge/PQC-Kyber--1024%20%2B%20X448-8a2be2?style=flat-square&labelColor=1a1a1a" alt="Kyber-1024 + X448"></a>

  <br><br>
  <b>Ultra-secure encrypted disk manager — hybrid post-quantum key encapsulation with plausible deniability.</b>
  <br>
  <sub>Kyber-1024 + X448 hybrid KEM · AES-256-GCM · Argon2id (1 GB) · FUSE 3 mounting · IND-RND plausible deniability · locked non-dumpable memory.</sub>

  <br><br>
  <a href="https://github.com/effjy/axis">
    <img src="https://github.com/effjy/axis/raw/main/screenshot.png" width="700px" alt="Axis main window">
  </a>
  <br>
  <sub><i>The Axis dashboard — create or open an encrypted volume, then mount it as a transparent FUSE filesystem with a single password</i></sub>

  <br><br>
  <a href="https://github.com/effjy/axis"><b>Explore the repository →</b></a>
</div>

---

## 🔬 Systems Security

<sub>Hardware-assisted memory safety &amp; defensive systems.</sub>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/honeycrypt"><img src="titles/honeycrypt-title.svg" height="52" alt="HoneyCrypt"></a></div> | **GTK3 decoy-encryption vault** — **DTE** turns every wrong passcode into a plausible fake plaintext, neutralizing offline brute force. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/kagealloc"><img src="titles/kagealloc-title.svg" height="52" alt="KageAlloc"></a></div> | **Hardware-assisted memory allocator** — Intel **MPK/PKU** for temporal safety and metadata integrity at just **3.8%** overhead over ptmalloc. ⭐ <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/opsec-linux/"><img src="titles/opsec-linux-title.svg" height="52" alt="OpSec Linux"></a></div> | **Paranoid-grade Linux hardening guide** — disk encryption, SSH, firewall, MAC, auditing and anti-forensics, with defense-in-depth and real commands. |
| <div align="center"><a href="https://github.com/effjy/opsec-windows/"><img src="titles/opsec-windows-title.svg" height="52" alt="OpSec Windows"></a></div> | **Paranoid-grade Windows 10/11 &amp; Server hardening guide** — BitLocker, Defender ASR, AppLocker/WDAC and firewall lockdown in PowerShell, on CIS baselines. |
| <div align="center"><a href="https://github.com/effjy/tids"><img src="titles/tids-title.svg" height="52" alt="TIDS"></a></div> | **Topological intrusion detector** — flags DDoS, port scans and exfiltration by their **persistent-homology** shape, not signatures; **0.03% FPR** on CIC-IDS2017. ⭐ <sub>(2026)</sub> |

---

## 🧬 Cryptography

<sub>Symmetric permutations, cryptanalysis &amp; permutation-driven tools.</sub>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/krakken"><img src="titles/krakken-abyssal-title.svg" height="52" alt="Krakken-2048 Abyssal"></a></div> | **2048-bit SPN-ARX permutation** — the wide-trail Krakken-2048 Abyssal core for sponge AEAD and hashing. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-butterfly"><img src="titles/krakken-butterfly-title.svg" height="52" alt="Krakken-2048 Butterfly"></a></div> | **Krakken-2048 + XRBD** — an XOR-rotation butterfly-diffusion layer reaching full word-level avalanche in **8 rounds**. ⭐ <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-butterfly-bounds"><img src="titles/krakken-bounds-title.svg" height="52" alt="Krakken-2048 Bounds"></a></div> | **MILP-proven bounds for XRBD** — ≥**229 active S-boxes** over 8 rounds, bounding every differential/linear characteristic below **2⁻¹³⁷⁴**. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-harness/"><img src="titles/krakken-harness-title.svg" height="52" alt="Krakken Harness"></a></div> | **Engineering-correctness harness** — KAT-pinned regression, invertibility, avalanche and tamper checks for Krakken-2048 and Krakken-Disk V5. |
| <div align="center"><a href="https://github.com/effjy/krakken-cryptanalysis"><img src="titles/krakken-cryptanalysis-title.svg" height="52" alt="Krakken Cryptanalysis"></a></div> | **Cryptanalysis & verification suite** — SAC/diffusion, NIST SP 800-22, division-property MILP and collision tests. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-disk/"><img src="titles/krakken-disk-title.svg" height="52" alt="Krakken-Disk"></a></div> | **GTK3 encrypted disk manager** driven by the **Krakken-2048 Abyssal** permutation — 256-bit post-Grover margin with a Kyber-1024/X448 hybrid KEM. |
| <div align="center"><a href="https://github.com/effjy/krakken-disk-butterfly/"><img src="titles/krakken-disk-butterfly-title.svg" height="52" alt="Krakken-Disk Butterfly"></a></div> | **Krakken-Disk on the Butterfly permutation** — a faster 8-round XRBD core with stronger security margins. ⭐ |
| <div align="center"><a href="https://github.com/effjy/krakken-disk-butterfly-cli/"><img src="titles/krakken-disk-butterfly-title.svg" height="52" alt="Krakken-Disk Butterfly CLI"></a></div> | **Command-line Krakken-Disk Butterfly** — the same post-quantum core, GUI-free for servers and automation. |

---

## 📚 Learning

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/learning-c/"><img src="titles/learning-c-title.svg" height="52" alt="Learning C"></a></div> | **Complete beginner's guide to C** — assumes zero prior code and builds up from compilation and variables through control flow, functions, arrays, **pointers, structs, and stack/heap memory**, closing with **5 graded exercises** and where to go next. |
| <div align="center"><a href="https://github.com/effjy/learning-python/"><img src="titles/learning-python-title.svg" height="52" alt="Learning Python"></a></div> | **Complete beginner's guide to Python** — from your first line through data types, control flow, functions, **lists/dicts/sets, strings, exceptions, and files & modules**, with PEP 8 style and **5 graded exercises**; a natural follow-on to the C guide. |

---

<div align="center">

<a href="mailto:effjy@protonmail.com"><img src="titles/email.svg" height="52" alt="Email me suggestions"></a>
<br><br>
I'm offering to develop security software at no cost. If there's a specific security-related tool you need, email me your idea and I'll get to work on it.
<br>

</div>

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
<img src="titles/C.svg" width="42" alt="C" title="C">&nbsp;
<img src="titles/CPP.svg" width="42" alt="C++" title="C++">&nbsp;
<img src="titles/Python-Dark.svg" width="42" alt="Python" title="Python">&nbsp;
<img src="titles/Bash-Dark.svg" width="42" alt="Bash" title="Bash">&nbsp;
<img src="titles/JavaScript.svg" width="42" alt="JavaScript" title="JavaScript">&nbsp;
<img src="titles/Java-Dark.svg" width="42" alt="Java" title="Java">&nbsp;
<img src="titles/Perl.svg" width="42" alt="Perl" title="Perl">
<br>
<img src="titles/Linux-Dark.svg" width="42" alt="Linux" title="Linux">&nbsp;
<img src="titles/Ubuntu-Dark.svg" width="42" alt="Ubuntu" title="Ubuntu">&nbsp;
<img src="titles/Git.svg" width="42" alt="Git" title="Git">&nbsp;
<img src="titles/CMake-Dark.svg" width="42" alt="CMake" title="CMake">&nbsp;
<img src="titles/HTML.svg" width="42" alt="HTML" title="HTML">&nbsp;
<img src="titles/CSS.svg" width="42" alt="CSS" title="CSS">&nbsp;
<img src="titles/SVG-Dark.svg" width="42" alt="SVG" title="SVG">

</div>
