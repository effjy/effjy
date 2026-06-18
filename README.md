<div align="center">

<a href="https://github.com/effjy/effjy/"><img src="titles/jean-francois-title.svg" height="100%" alt="Jean-Francois Lachance-Caumartin"></a>

### 🛡️ Systems & Cryptography Engineer · Post-Quantum Security · Low-Level C

*I build security tools in C — from original cryptographic permutations and post-quantum
vaults to forensic utilities and hardened Linux desktop apps. Close to the metal, paranoid by design.*

![C](https://img.shields.io/badge/C-555555?style=for-the-badge&logo=c&logoColor=white)
![GTK3](https://img.shields.io/badge/GTK3-4A90D9?style=for-the-badge&logo=gnome&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1793D1?style=for-the-badge&logo=linux&logoColor=white)
![Post-Quantum](https://img.shields.io/badge/Post--Quantum-8A2BE2?style=for-the-badge)
![Cryptanalysis](https://img.shields.io/badge/Cryptanalysis-teal?style=for-the-badge)

</div>

---

## 👋 About

I'm a security-focused engineer who works almost entirely in **C** — by choice. My projects
span original **cryptographic design and cryptanalysis**, **post-quantum** applications built
on NIST standards (Kyber/ML-KEM, ML-DSA, SLH-DSA), **digital forensics**, and clean **GTK3**
desktop front-ends that make serious security tooling actually pleasant to use.

A few themes run through everything I build:

- 🔬 **Original research** — I designed *Krakken-2048*, a 2048-bit SPN-ARX permutation, and
  wrote the papers, the MILP proofs, and the cryptanalysis suites behind it.
- 🧬 **Post-quantum by default** — hybrid Kyber-1024 + X448 KEMs, AES-256-GCM / XChaCha20-Poly1305
  AEADs, and Argon2id hardening across a whole family of tools.
- ⚙️ **No dependencies, close to the metal** — primitives implemented from scratch, AVX2/AES-NI
  hand-tuning, `/proc` parsing, `mlock()`'d secrets, and `ioctl()` block-level I/O.

---

## 🔐 Cryptographic Research — The *Krakken* Project

My flagship work: an original wide-state cryptographic permutation, its evolution, and the full
provable-security apparatus around it.

| Project | What it is |
|---|---|
| <div align="center"><a href="https://github.com/effjy/krakken"><img src="titles/krakken-abyssal-title.svg" height="52" alt="Krakken-2048 Abyssal"></a></div> | **Krakken-2048 Abyssal** — a 2048-bit SPN-ARX hybrid permutation for sponge hashing & AEAD. Full paper: spec, differential/linear/rebound/invariant-subspace analysis, MILP bounds, AVX2 benchmarks. |
| **[krakken-butterfly](https://github.com/effjy/krakken-butterfly)** | The evolution: **XOR-Rotation Butterfly Diffusion (XRBD)** — a 5-stage logarithmic butterfly network giving full avalanche in one pass, cutting 10 rounds down to 8. |
| **[krakken-butterfly-bounds](https://github.com/effjy/krakken-butterfly-bounds)** | Reproducible MILP models proving a minimum of **229 active S-boxes** over 8 rounds, bounding any characteristic to **2⁻¹³⁷⁴** — with a closed optimality gap. |
| **[krakken-cryptanalysis](https://github.com/effjy/krakken-cryptanalysis)** | The empirical + provable analysis suite for the wide-trail permutation and its sponge hash. |
| **[krakken-harness](https://github.com/effjy/krakken-harness)** | Standalone, drop-anywhere CI test package — determinism, invertibility, tamper-evidence, KAT drift-lock. |

---

## 💾 Encrypted Storage & Disk Managers

Post-quantum encrypted volumes with plausible deniability — volumes mathematically
indistinguishable from random noise (IND-RND).

| Project | What it is |
|---|---|
| **[axis](https://github.com/effjy/axis)** | Ultra-secure encrypted disk manager — AES-256-GCM + hybrid Kyber-1024/X448 KEM, AES-NI/AVX2 accelerated, Argon2id (1 GB) hardened, full plausible deniability. |
| **[axis-secret](https://github.com/effjy/axis-secret)** | A beautiful GTK3 calculator… with the entire Axis disk manager hidden behind a secret passcode. |
| **[krakken-disk](https://github.com/effjy/krakken-disk)** | Encrypted volume manager powered by the Krakken-2048 permutation — uniform 256-bit post-Grover margin. |
| **[krakken-disk-butterfly](https://github.com/effjy/krakken-disk-butterfly)** | The faster 8-round XRBD edition of Krakken-Disk. |
| **[krakken-disk-butterfly-cli](https://github.com/effjy/krakken-disk-butterfly-cli)** | CLI build with **FUSE 3** mounting — encrypted containers as transparent filesystem directories. |
| **[honeycrypt](https://github.com/effjy/honeycrypt)** | DTE-based decoy encryption vault — neutralizes offline brute-force by replacing auth errors with *plausible decoys*. |
| **[secure_mount](https://github.com/effjy/secure_mount)** | GTK3 manager for `gocryptfs` encrypted volumes — init, mount, unmount without the command line. |

---

## 🧬 Post-Quantum Application Suite

A coherent family of NIST-standard PQC tools sharing a common crypto core.

| Project | What it is |
|---|---|
| **[pqpman](https://github.com/effjy/pqpman)** | Post-quantum password manager — single-master-password vault sealed with Kyber-1024 + X448 hybrid KEM. |
| **[pqotp](https://github.com/effjy/pqotp)** | Post-quantum TOTP/HOTP authenticator (GTK3 + CLI) — the PQ answer to Google Authenticator. |
| **[pq-note](https://github.com/effjy/pq-note)** | Encrypted notes — nothing decrypted ever touches disk. |
| **[pq-sealed](https://github.com/effjy/pq-sealed)** | Incremental encrypted backups with ML-DSA-65-signed, tamper-evident snapshots. |
| **[pq-sign](https://github.com/effjy/pq-sign)** | Detached file signing with ML-DSA (FIPS 204) & SLH-DSA (FIPS 205). |
| **[pq-audit](https://github.com/effjy/pq-audit)** | Tamper-evident, hash-chained, PQ-sealed audit logging — the record you can *prove*. |
| **[pqtransfer](https://github.com/effjy/pqtransfer)** | Serverless peer-to-peer file transfer over an end-to-end PQ-encrypted channel. |

---

## 🔏 Encryption & Password Tooling

| Project | What it is |
|---|---|
| **[ciphers](https://github.com/effjy/ciphers)** | GTK3 file encryption with modern AEAD + post-quantum hybrid key encapsulation. |
| **[multi-ciphers](https://github.com/effjy/multi-ciphers)** | Dependency-free CLI authenticated encryption — four AEAD ciphers, Argon2id, every primitive bundled. |
| **[czip](https://github.com/effjy/czip)** | First archiver to fuse multithreaded **zstd** compression with **XChaCha20-Poly1305** — streaming, flat memory, terabyte-ready. |
| **[entropy](https://github.com/effjy/entropy)** | Terminal password generator + multi-factor entropy analyzer (`getrandom()`, dictionary & leet-speak penalties). |
| **[entropy-gui](https://github.com/effjy/entropy-gui)** | The sleek GTK3 edition of Entropy. |

---

## 🕵️ Forensics, Memory Safety & Detection

| Project | What it is |
|---|---|
| **[fordump](https://github.com/effjy/fordump)** | GTK3 forensic acquisition suite — multi-threaded block-level imaging, magic-byte carving, credential/signature detection. |
| **[memscan](https://github.com/effjy/memscan)** | Scans live process memory (`/proc/<pid>/mem`) for byte patterns & magic headers. |
| **[mole](https://github.com/effjy/mole)** | Recursively greps directory trees for leaked credentials — API keys, private keys, JWTs, cloud tokens. |
| **[scrub](https://github.com/effjy/scrub)** | Forensic-grade metadata scrubber — strips Exif/XMP/IPTC natively in C, no libexif. |
| **[viewer](https://github.com/effjy/viewer)** | Security-focused image viewer — pixel data `mlock()`'d into RAM and securely wiped, never swapped. |
| **[syshash](https://github.com/effjy/syshash)** | File integrity monitor — SHA3-512 (Keccak from scratch), CLI + GTK3 over one core. |
| **[tids](https://github.com/effjy/tids)** | **Topological** IDS — detects intrusions by their *shape* using persistent homology & Vietoris-Rips filtrations. |
| **[kagealloc](https://github.com/effjy/kagealloc)** | Hardware-assisted temporal memory-safety allocator using Intel MPK/PKU — ~3.8% overhead over ptmalloc. Includes a paper. |
| **[swipe](https://github.com/effjy/swipe)** | CLI secure-wipe — NIST SP 800-88 / FIPS 140-3, files, free space, RAM, SSD TRIM. |
| **[vwipe](https://github.com/effjy/vwipe)** | Virtual Wipe Turbo — multi-core forensic data sanitization saturating NVMe/SSD throughput. |

---

## 🖥️ Linux Desktop Front-Ends & Monitors

Color, live output, and a clean dark aesthetic for tools that usually scroll past in a terminal.

| Project | What it is |
|---|---|
| **[chkrootkit-gui](https://github.com/effjy/chkrootkit-gui)** | GTK3 front-end for `chkrootkit` — live, color-coded rootkit scans. |
| **[rkhunter-gui](https://github.com/effjy/rkhunter-gui)** | GTK3 front-end for Rootkit Hunter — `rkhunter --check` live, in color. |
| **[lynis-gui](https://github.com/effjy/lynis-gui)** | GTK3 front-end for Lynis — security audits with color, live. |
| **[connmon](https://github.com/effjy/connmon)** | Real-time TCP connection monitor — resolves owning process per connection via `/proc`. |
| **[usage](https://github.com/effjy/usage)** | Live bandwidth monitor with a Cairo-drawn traffic graph and Tokyo Night theme. |
| **[ram](https://github.com/effjy/ram)** | GTK3 + Cairo RAM analyzer with ring gauges and *verified* process kills. |
| **[sizer](https://github.com/effjy/sizer)** | Disk-space analyzer with live percentages and an interactive donut diagram. |
| **[limiter](https://github.com/effjy/limiter)** | Per-interface upload/download bandwidth cap — GTK3 + CLI. |

---

## 📚 Guides & Learning

| Project | What it is |
|---|---|
| **[opsec-linux](https://github.com/effjy/opsec-linux)** | Paranoid-grade Linux hardening guide — defense-in-depth, real commands. |
| **[opsec-windows](https://github.com/effjy/opsec-windows)** | The Windows 10/11/Server counterpart — PowerShell, CIS/Microsoft SCT baselines. |
| **[learning-c](https://github.com/effjy/learning-c)** | From-scratch C beginner's guide with graduated exercises. |
| **[learning-python](https://github.com/effjy/learning-python)** | From-scratch Python beginner's guide with graduated exercises. |

---

<div align="center">

### 🧰 Toolbox

**Languages** · C (C11/C99) · Python · Bash · PowerShell
**Crypto** · AES-256-GCM · XChaCha20/ChaCha20-Poly1305 · SHA3/Keccak · Argon2id · Kyber-1024 (ML-KEM) · X448 · ML-DSA · SLH-DSA
**Systems** · GTK3 · Cairo · FUSE 3 · AVX2 / AES-NI · `/proc` & `ioctl` · `mlock` · MILP / SMT proofs

*Close to the metal. Paranoid by design. Provable when it counts.*

</div>
