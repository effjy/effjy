<div align="center">

  <a href="https://github.com/effjy/effjy/"><img src="titles/jean-francois-title.svg" height="100%" alt="Jean-Francois Lachance-Caumartin"></a>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFCC&center=true&vCenter=true&width=560&lines=Symmetric+Primitive+Design;Advanced+Cryptanalysis;Post-Quantum+Secured+Systems;Forensic-Grade+Sanitization)](https://git.io/typing-svg)

**Security analyst by day · cryptographic researcher by night.**

I build high-assurance security tools and design symmetric primitives.

<sub>I work almost entirely in **C**, by choice — original cryptographic design & cryptanalysis, **post-quantum** applications on NIST standards (Kyber/ML-KEM, ML-DSA, SLH-DSA), digital forensics, and clean GTK front-ends. Original research, post-quantum by default, no dependencies, close to the metal.</sub>

<br>

<a href="#-post-quantum"><b>Post-Quantum</b></a> &nbsp;·&nbsp;
<a href="#-encryption--privacy"><b>Encryption &amp; Privacy</b></a> &nbsp;·&nbsp;
<a href="#-forensics--secure-erase"><b>Forensics</b></a> &nbsp;·&nbsp;
<a href="#-monitoring--auditing"><b>Monitoring</b></a> &nbsp;·&nbsp;
<a href="#-systems-security"><b>Systems Security</b></a> &nbsp;·&nbsp;
<a href="#-cryptography"><b>Cryptography</b></a> &nbsp;·&nbsp;
<a href="#-learning"><b>Learning</b></a> &nbsp;·&nbsp;
<a href="#-contact"><b>Contact</b></a>

</div>

> [!TIP]
> ⭐ **A star goes a long way** — it helps others find the work and keeps me building. Thank you.

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
  <sub><i>Create or open an encrypted volume, then mount it as a transparent FUSE filesystem with a single password.</i></sub>

  <br><br>

  <b>More flagship work</b>
  <br>
  <a href="https://github.com/effjy/krakken-butterfly"><b>Krakken-2048 Butterfly</b></a> — 2048-bit permutation, full avalanche in 8 rounds &nbsp;·&nbsp;
  <a href="https://github.com/effjy/pq-sealed"><b>PQ-Sealed</b></a> — signed post-quantum backups
  <br>
  <a href="https://github.com/effjy/kagealloc"><b>KageAlloc</b></a> — MPK-hardened allocator, 3.8% overhead &nbsp;·&nbsp;
  <a href="https://github.com/effjy/tids"><b>TIDS</b></a> — topological intrusion detection, 0.03% FPR

</div>

---

## 🔐 Post-Quantum

<sub>NIST-standard post-quantum applications — hybrid KEM &amp; signatures by default.</sub>

<details>
<summary><b>Show 13 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/axis/">AXIS</a></div> | **Encrypted disk manager** — AES-256-GCM volumes behind a PQ hybrid KEM, FUSE mounting and plausible deniability. ⭐ |
| <div align="center"><a href="https://github.com/effjy/axis-cli/">AXIS CLI</a></div> | **Headless Axis** — the same encrypted volumes for servers and automation; reads the same containers. |
| <div align="center"><a href="https://github.com/effjy/axis-secret/">CALCULATOR VAULT</a></div> | **A working calculator** that secretly launches Axis on a passcode — hiding that it's even installed. ⭐ |
| <div align="center"><a href="https://github.com/effjy/pq-audit/">PQ-AUDIT</a></div> | **Tamper-evident audit log** — append-only and hash-chained, sealed with ML-DSA/SLH-DSA and Merkle proofs. |
| <div align="center"><a href="https://github.com/effjy/pq-chat/">PQ-CHAT</a></div> | **Serverless encrypted messenger** — a PQ KEM handshake seeds a Signal Double Ratchet for per-message forward secrecy. |
| <div align="center"><a href="https://github.com/effjy/pq-note/">PQ-NOTE</a></div> | **Encrypted notes app** — sealed as one AEAD blob behind a PQ hybrid KEM and a single master password. |
| <div align="center"><a href="https://github.com/effjy/pq-sealed/">PQ-SEALED</a></div> | **Incremental encrypted backups** — deduplicating content-addressed snapshots, manifests signed with ML-DSA-65. ⭐ |
| <div align="center"><a href="https://github.com/effjy/pq-shard/">PQ-SHARD</a></div> | **Post-quantum secret sharing** — split a secret into N shares so any K reconstruct it (Shamir over GF(2⁸)). |
| <div align="center"><a href="https://github.com/effjy/pq-sign/">PQ-SIGN</a></div> | **Post-quantum file signing** — detached ML-DSA (FIPS 204) and SLH-DSA (FIPS 205) signatures. |
| <div align="center"><a href="https://github.com/effjy/pq-transfer/">PQ-TRANSFER</a></div> | **Peer-to-peer file transfer** — serverless and end-to-end encrypted over a PQ hybrid KEM. |
| <div align="center"><a href="https://github.com/effjy/pq-zip/">PQ-ZIP</a></div> | **Post-quantum archiver** — DEFLATE then AEAD into one password-protected `.pqz`. |
| <div align="center"><a href="https://github.com/effjy/pqotp/">PQOTP</a></div> | **2FA authenticator** — TOTP/HOTP seeds in a post-quantum hybrid-KEM vault. |
| <div align="center"><a href="https://github.com/effjy/pqpman/">PQPMAN</a></div> | **Password manager** — vault sealed with AEAD and a PQ hybrid KEM behind one master password. |

</details>

---

## 🔒 Encryption & Privacy

<sub>AEAD file encryption, encrypted-cloud clients and privacy hygiene.</sub>

<details>
<summary><b>Show 8 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/ciphers/">CIPHERS</a></div> | **File encryptor** — AEAD ciphers (AES-256-GCM, XChaCha20-Poly1305) with an optional PQ hybrid KEM. |
| <div align="center"><a href="https://github.com/effjy/multi-ciphers/">MULTI CIPHERS</a></div> | **Dependency-free encryption CLI** — four AEAD ciphers (AES-256-GCM, XChaCha20, Serpent, Twofish). ⭐ |
| <div align="center"><a href="https://github.com/effjy/czip/">CZIP</a></div> | **Compress-and-encrypt archiver** — multithreaded zstd through XChaCha20-Poly1305, with file splitting. |
| <div align="center"><a href="https://github.com/effjy/secure_mount/">SECURE MOUNT</a></div> | **GTK front-end for gocryptfs** — init, mount and unmount encrypted volumes without the command line. |
| <div align="center"><a href="https://github.com/effjy/scrub/">SCRUB</a></div> | **Metadata scrubber** — natively strips Exif/XMP/IPTC (and C2PA) from JPEGs and PNGs before you share them. |
| <div align="center"><a href="https://github.com/effjy/viewer">VIEWER</a></div> | **RAM-only image viewer** — `mlock`s pixels in physical memory and zeroes them on close; no swap leaks. |
| <div align="center"><a href="https://github.com/effjy/filen-gui/">FILEN GUI</a></div> | **Desktop client for Filen.io** (C++/GTK4) — browse and sync your end-to-end encrypted cloud, all crypto local. |
| <div align="center"><a href="https://github.com/effjy/protondrive-gui/">PROTON DRIVE GUI</a></div> | **Desktop client for Proton Drive** (C++/GTK4) — Proton SRP login, then browse end-to-end encrypted files locally. |

</details>

---

## 🧹 Forensics & Secure Erase

<sub>Disk imaging, file recovery and forensic-grade sanitization.</sub>

<details>
<summary><b>Show 6 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/fordump">FORENSIC DUMP</a></div> | **Forensics imager** — multithreaded block-level disk imaging with file carving and credential/key search. |
| <div align="center"><a href="https://github.com/effjy/frecover/">FORENSIC RECOVERY</a></div> | **Read-only ext2/3/4 recovery** (C++) — undeletes inodes and carves raw free blocks, with SHA-256 and a CSV manifest. |
| <div align="center"><a href="https://github.com/effjy/memscan/">MEMSCAN</a></div> | **Live-memory scanner** — searches a running process's `/proc/<pid>/mem` for byte patterns or file magic. |
| <div align="center"><a href="https://github.com/effjy/nwu/">NOVEL WIPING UTILITY</a></div> | **SSD-aware secure delete** — ChaCha20 overwrite + punch-hole + TRIM for files, free space and RAM. ⭐ |
| <div align="center"><a href="https://github.com/effjy/swipe">SECURE WIPE</a></div> | **CLI data sanitizer** — wipes files, free space and RAM to NIST SP 800-88 / FIPS 140-3, with SSD TRIM. |
| <div align="center"><a href="https://github.com/effjy/vwipe">VIRTUAL WIPE TURBO</a></div> | **Multi-core secure-erase suite** — saturates NVMe/SSD throughput wiping disks, free space and RAM. |

</details>

---

## 🛡️ Monitoring & Auditing

<sub>Security scanners, live system monitors, integrity checks and firewalls.</sub>

<details>
<summary><b>Show 17 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/chkrootkit-gui/">CHKROOTKIT GUI</a></div> | **Front-end for chkrootkit** — live, color-coded rootkit scans with one-click false-positive filtering. |
| <div align="center"><a href="https://github.com/effjy/connmon/">CONNECTION MONITOR</a></div> | **Real-time TCP monitor** — reads `/proc/net/tcp` and maps every live connection to its owning process. |
| <div align="center"><a href="https://github.com/effjy/diskmon/">DISK MONITOR</a></div> | **Real-time disk I/O monitor** (C++/GTK4) — live throughput from `/proc/diskstats` with a Cairo graph. |
| <div align="center"><a href="https://github.com/effjy/entropy/">ENTROPY</a></div> | **CLI password generator** — CSPRNG with an analyzer that penalizes repeats, sequences and dictionary words. |
| <div align="center"><a href="https://github.com/effjy/entropy-gui/">ENTROPY GUI</a></div> | **GTK Entropy** — naive vs. realistic password entropy with a color-coded strength meter. |
| <div align="center"><a href="https://github.com/effjy/envision/">ENVISION</a></div> | **System-security scanner** — audits firewall, ports, SSH, sudo, accounts and kernel hardening; PDF report. |
| <div align="center"><a href="https://github.com/effjy/fail2ban-gui/">FAIL2BAN GUI</a></div> | **Front-end for fail2ban** — browse jails, ban/unban IPs, tune timings and start/stop jails from one window. |
| <div align="center"><a href="https://github.com/effjy/lynis-gui/">LYNIS GUI</a></div> | **Front-end for Lynis** — live, color-coded security audits with a one-click pentest mode. |
| <div align="center"><a href="https://github.com/effjy/mole/">MOLE</a></div> | **Secret scanner** — greps a tree for leaked credentials via regex + Shannon entropy; CLI and GTK triage UI. |
| <div align="center"><a href="https://github.com/effjy/limiter/">NETWORK SPEED LIMITER</a></div> | **Bandwidth limiter** — caps up/down speed on any interface via Linux `tc`, optionally as a boot service. |
| <div align="center"><a href="https://github.com/effjy/ram/">RAM VISUALIZER</a></div> | **RAM analyzer** — top memory hogs, live ring gauges and bar charts, and verified-kill termination. |
| <div align="center"><a href="https://github.com/effjy/rkhunter-gui/">RKHUNTER GUI</a></div> | **Front-end for rkhunter** — live, color-coded rootkit scans with a problems-only filter. |
| <div align="center"><a href="https://github.com/effjy/sinfo/">SERVICES INFORMATION</a></div> | **systemd service manager** (C++) — start/stop, enable/disable and mask/unmask every service, elevated per-op. |
| <div align="center"><a href="https://github.com/effjy/sizer">SIZER</a></div> | **Disk-space analyzer** — threaded scan from `/` with live bars, an interactive donut and folder drill-down. |
| <div align="center"><a href="https://github.com/effjy/syshash/">SYSHASH</a></div> | **File-integrity monitor** — SHA3-512 baselines a tree and flags any changed file on re-scan. ⭐ |
| <div align="center"><a href="https://github.com/effjy/usage/">USAGE</a></div> | **Real-time network monitor** — live up/down speeds, a Cairo graph and a settable usage limit. |
| <div align="center"><a href="https://github.com/effjy/warden/">WARDEN</a></div> | **Outbound firewall** — diverts new connections to NFQUEUE and prompts allow/deny, keyed on the binary's SHA-256. |

</details>

---

## 🔬 Systems Security

<sub>Hardware-assisted memory safety &amp; defensive systems.</sub>

<details>
<summary><b>Show 5 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/honeycrypt">HONEYCRYPT</a></div> | **Decoy-encryption vault** — DTE turns every wrong passcode into a plausible fake plaintext. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/kagealloc">KAGEALLOC</a></div> | **Hardware-assisted allocator** — Intel MPK/PKU for temporal safety at just 3.8% overhead over ptmalloc. ⭐ <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/opsec-linux/">OPSEC LINUX</a></div> | **Paranoid-grade Linux hardening guide** — encryption, SSH, firewall, MAC, auditing and anti-forensics. |
| <div align="center"><a href="https://github.com/effjy/opsec-windows/">OPSEC WINDOWS</a></div> | **Paranoid-grade Windows hardening guide** — BitLocker, Defender ASR, AppLocker/WDAC, on CIS baselines. |
| <div align="center"><a href="https://github.com/effjy/tids">TIDS</a></div> | **Topological intrusion detector** — flags attacks by their persistent-homology shape; 0.03% FPR on CIC-IDS2017. ⭐ <sub>(2026)</sub> |

</details>

---

## 🧬 Cryptography

<sub>Symmetric permutations, cryptanalysis &amp; permutation-driven tools.</sub>

<details>
<summary><b>Show 8 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/krakken">KRAKKEN-2048 ABYSSAL</a></div> | **2048-bit SPN-ARX permutation** — the wide-trail Abyssal core for sponge AEAD and hashing. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-butterfly">KRAKKEN-2048 BUTTERFLY</a></div> | **Krakken-2048 + XRBD** — an XOR-rotation butterfly-diffusion layer reaching full avalanche in 8 rounds. ⭐ <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-butterfly-bounds">KRAKKEN-2048 BOUNDS</a></div> | **MILP-proven bounds for XRBD** — ≥229 active S-boxes over 8 rounds, every characteristic below 2⁻¹³⁷⁴. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-harness/">KRAKKEN HARNESS</a></div> | **Correctness harness** — KAT-pinned regression, invertibility, avalanche and tamper checks. |
| <div align="center"><a href="https://github.com/effjy/krakken-cryptanalysis">KRAKKEN CRYPTANALYSIS</a></div> | **Cryptanalysis suite** — SAC/diffusion, NIST SP 800-22, division-property MILP and collision tests. <sub>(2026)</sub> |
| <div align="center"><a href="https://github.com/effjy/krakken-disk/">KRAKKEN-DISK</a></div> | **Encrypted disk manager** on the Abyssal permutation — 256-bit post-Grover margin, PQ hybrid KEM. |
| <div align="center"><a href="https://github.com/effjy/krakken-disk-butterfly/">KRAKKEN-DISK BUTTERFLY</a></div> | **Krakken-Disk on the Butterfly permutation** — a faster 8-round core with stronger margins. ⭐ |
| <div align="center"><a href="https://github.com/effjy/krakken-disk-butterfly-cli/">KRAKKEN-DISK BUTTERFLY CLI</a></div> | **Headless Krakken-Disk Butterfly** — the same post-quantum core for servers and automation. |

</details>

---

## 📚 Learning

<sub>Zero-to-fundamentals programming guides.</sub>

<details>
<summary><b>Show 2 projects</b></summary>

<br>

| Project | What it does |
|:---|:---|
| <div align="center"><a href="https://github.com/effjy/learning-c/">LEARNING C</a></div> | **Complete beginner's guide to C** — compilation through pointers, structs and memory, with 5 graded exercises. |
| <div align="center"><a href="https://github.com/effjy/learning-python/">LEARNING PYTHON</a></div> | **Complete beginner's guide to Python** — types through files & modules, PEP 8 style, with 5 graded exercises. |

</details>

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

![](https://komarev.com/ghpvc/?username=effjy&color=blueviolet)

</div>
