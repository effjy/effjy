# 👤 About Me

Network administrator and Level 3 security analyst with deep expertise in operational security (OpSec) and digital forensics. As an independent cryptographic researcher, I specialize in symmetric primitive design and advanced cryptanalysis. I am the creator of **Krakken-2048 Abyssal**, a novel wide-state SPN-ARX hybrid permutation, along with the **Krakken-Disk** post-quantum encrypted volume manager and **Virtual Wipe Turbo**, a forensic-grade data sanitization suite.

---

## 🎯 Mission

The goal of my work is to help keep **long-term secrets safe** and protect against **data recovery** by adversaries — whether they are persistent threat actors, forensic investigators, or future quantum-capable attackers. My cryptographic primitives and secure erasure tools are designed for organizations that cannot afford to leave anything behind.

I believe that **governments, defense contractors, financial institutions, and enterprises handling the most sensitive data** should move beyond legacy encryption and erasure standards. The Krakken-2048 permutation (and its highly secure Butterfly variant) offers a modern, post-quantum-ready foundation for protecting classified, financial, and personally identifiable information (PII) — even against nation-state-level recovery attempts.

---

## 🛠️ Current Projects

| Project | Description | Status |
|:--------|:------------|:-------|
| **Krakken-2048 Abyssal**<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/krakken-blue)](https://github.com/effjy/krakken) | A 2048-bit cryptographic permutation fusing an SPN core (GF(2⁸) S-box + MDS branch number 9) with targeted ARX mixing to eliminate algebraic invariants. Designed for high-assurance sponge constructions. | First public release (2026) — submitted for peer review |
| **Krakken-2048 Butterfly**<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/krakken--butterfly-blue)](https://github.com/effjy/krakken-butterfly) | An evolution of the Krakken-2048 design featuring a novel XOR-Rotation Butterfly Diffusion (XRBD) layer that achieves full word-level avalanche across 32 words in a single 5-stage pass. This additional mixing stage enables a round count reduction from 10 to 8 while improving security margins. | Specification complete — reference implementation and cryptanalysis scripts available |
| **Krakken-Disk**<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/krakken--disk-blue)](https://github.com/effjy/krakken-disk/) | A post-quantum encrypted disk manager for Linux combining Kyber-1024/X448 hybrid KEM with AVX2-accelerated wide-state permutations and strong plausible deniability. | Stable release available |
| **Krakken-Disk Butterfly** ![NEW](https://img.shields.io/badge/NEW-orange?style=flat-square)<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/krakken--disk--butterfly-blue)](https://github.com/effjy/krakken-disk-butterfly/) | An evolution of Krakken-Disk that replaces the original permutation with the **Krakken-2048 Butterfly** permutation. Inherits all features (Kyber‑1024/X448 KEM, plausible deniability, AVX2 acceleration) while benefiting from the faster 8‑round design and the novel XRBD diffusion layer. | Stable release available (v4.6.0) |
| **Secure Mount** ![NEW](https://img.shields.io/badge/NEW-orange?style=flat-square)<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/secure_mount-blue)](https://github.com/effjy/secure_mount/) | A modern GTK3 graphical frontend for gocryptfs that makes mounting, unmounting, and initializing encrypted volumes effortless. Features desktop integration, secure terminal password entry, and one-click volume management. | Initial release available |
| **Secure Wipe**<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/swipe-blue)](https://github.com/effjy/swipe) | Command-line data sanitization utility for secure environments — NIST SP 800-88 compliant file, directory, free space, and RAM wiping. The interactive, text-based counterpart to Virtual Wipe Turbo. | Stable release available |
| **Usage**<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/usage-blue)](https://github.com/effjy/usage/) | A real-time network traffic and bandwidth monitoring tool written in C and built with GTK+ 3. Displays current speeds, records session statistics, and draws a live graph of incoming and outgoing traffic. Styled with a premium Tokyo Night dark theme. | Stable release available |
| **Virtual Wipe Turbo**<br>[![GitHub](https://img.shields.io/badge/GitHub-effjy/vwipe-blue)](https://github.com/effjy/vwipe) | High-performance, forensic-grade secure erasure suite for storage and volatile memory (RAM), aligned with NIST SP 800-88 Rev. 1. Features a multi-threaded engine, GTK3 dark theme UI, and secure CLI memory purger. | Stable release available |

---

## 🎯 Research Interests

- Wide-state permutation design  
- SPN-ARX hybrid architectures  
- Invariant subspace cryptanalysis  
- Algebraic degree propagation in mixed constructions  
- Operational Security (OpSec) and advanced sanitization techniques  

---

## 📖 Background

With over 20 years of professional experience as a Level 3 security analyst, network administrator, and technical specialist, I bring real-world operational insight to cryptographic design. For more than a decade, I have pursued independent research into symmetric cryptography, with a particular focus on how SPN and ARX paradigms can be fused to overcome each other's inherent weaknesses. The Krakken project embodies this philosophy: every component is engineered to neutralize the cryptanalytic vulnerabilities of the others.

---

## 📬 Contact & Profiles

| Platform     | Link |
|--------------|------|
| **GitHub**   | [@effjy](https://github.com/effjy) |
| **ORCID**    | [0009-0005-6377-1675](https://orcid.org/0009-0005-6377-1675) |
| **Gravatar** | [luminous0816ec2f7a](https://gravatar.com/luminous0816ec2f7a) |
| **X**        | [@jfclachance](https://x.com/jfclachance) |

---

*🦑 Released into the abyss — 2026*
