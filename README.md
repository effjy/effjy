<!-- Header with ASCII art and tagline -->
<div align="center">
  <pre>
   ▄▄▄·  ▄▄▄· ▄▄▄▄▄ ▄ .▄ ▄▄▄ .    ▄▄▄·  ▄▄▄· ▄▄▄▄▄ ▄▄▄· ▄▄▄▄▄
  ▐█ ▀█ ▐█ ▀█ •██  ██▪▐█ ▀▄.▀·   ▐█ ▄█▐█ ▄█ •██  ▐█ ▀█ •██  
  ▄█▀▀█ ▄█▀▀█  ▐█.▪██▀▐█ ▐▀▀▪▄    ██▀· ██▀·  ▐█.▪▄█▀▀█  ▐█.▪
  ▐█ ▪▐▌▐█ ▪▐▌ ▐█▌·██▌▐▀ ▐█▄▄▌   ▐█▪·•▐█▪·• ▐█▌·▐█ ▪▐▌ ▐█▌·
   ▀  ▀  ▀  ▀  ▀▀▀ ▀▀▀ ·  ▀▀▀    .▀    .▀    ▀▀▀  ▀  ▀  ▀▀▀ 
  </pre>
  <h3>🔐 Post‑Quantum Cryptography · 🧠 Forensic Sanitization · 🐧 Linux Security</h3>
  <p>
    <img src="https://img.shields.io/badge/Security-Research-teal" />
    <img src="https://img.shields.io/badge/C-Code-blue" />
    <img src="https://img.shields.io/badge/GTK3-UI-brightgreen" />
    <img src="https://img.shields.io/badge/Linux-Kernel-critical" />
  </p>
</div>

---

# 👤 Jean‑François Lachance‑Caumartin

**Network administrator · Level 3 security analyst · Independent cryptographic researcher**

> *“Engineering the abyss — one permutation at a time.”*

With over 20 years of operational security (OpSec) and digital forensics experience, I design **post‑quantum ready primitives** and **forensically‑sterile tools** for governments, defense, and enterprises.

---

## 🎯 Mission

<table>
<tr>
<td width="70%">

The goal of my work is to keep **long‑term secrets safe** — even against nation‑state adversaries and future quantum attackers.  
My **Krakken‑2048** permutations and sanitization suites are built for organizations that cannot afford to leave anything behind.

</td>
<td width="30%" align="center">

<img src="https://img.shields.io/badge/NIST%20SP%20800--88-Compliant-blue" /><br/>
<img src="https://img.shields.io/badge/FIPS%20140--3-Ready-teal" /><br/>
<img src="https://img.shields.io/badge/Post--Quantum-Kyber%2FX448-purple" />

</td>
</tr>
</table>

---

## 🔬 Cryptographic Permutations

| Project | Description | Status |
|:--------|:------------|:-------|
| **[Krakken‑2048 Abyssal](https://github.com/effjy/krakken)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken)<br><br>A 2048‑bit SPN‑ARX hybrid permutation with MDS branch number 9 and 10 rounds. Designed for sponge‑based hashing and encryption. | `peer review` |
| **[Krakken‑2048 Butterfly](https://github.com/effjy/krakken-butterfly)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-butterfly) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-butterfly)<br><br>Adds **XRBD** – a logarithmic butterfly diffusion layer – achieving full word‑level avalanche in 5 stages, reducing rounds to 8 while strengthening security. | `peer review` |

---

## 🛠️ Software Applications

| Project | Description | Status |
|:--------|:------------|:-------|
| **[Krakken‑Disk](https://github.com/effjy/krakken-disk/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk) [![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk)<br><br>Post‑quantum encrypted volume manager with Kyber‑1024/X448 KEM and plausible deniability. | `stable` |
| **[Krakken‑Disk Butterfly](https://github.com/effjy/krakken-disk-butterfly/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/krakken-disk-butterfly) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/krakken-disk-butterfly) [![Security](https://img.shields.io/badge/security-Post--Quantum-teal)](https://github.com/effjy/krakken-disk-butterfly) ![NEW](https://img.shields.io/badge/NEW-orange?style=flat-square)<br><br>Same features as Krakken‑Disk, but powered by the faster **Butterfly** permutation (8 rounds, XRBD diffusion). | `stable` |
| **[Virtual Wipe Turbo](https://github.com/effjy/vwipe)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/vwipe) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/vwipe) [![Standards](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/vwipe) [![Turbo Engine](https://img.shields.io/badge/engine-8--core%20Turbo-00FFCC)](https://github.com/effjy/vwipe)<br><br>Forensic‑grade, multi‑threaded sanitisation with a GTK3 dark UI – saturates NVMe throughput. | `stable` |
| **[Secure Wipe](https://github.com/effjy/swipe)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/swipe) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/swipe) [![Standards](https://img.shields.io/badge/standards-NIST%20SP%20800--88%20%2F%20FIPS%20140--3-blue)](https://github.com/effjy/swipe)<br><br>Command‑line counterpart to VWT – interactive menu for file, directory, free space and RAM wiping. | `stable` |
| **[Secure Mount](https://github.com/effjy/secure_mount/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/secure_mount) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/secure_mount) [![GTK](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/secure_mount)<br><br>GTK3 frontend for `gocryptfs` – one‑click volume initialisation, mounting and unmounting. | `stable` |
| **[Usage](https://github.com/effjy/usage/)** | [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Language](https://img.shields.io/badge/language-C-blue)](https://github.com/effjy/usage) [![Platform](https://img.shields.io/badge/platform-Linux-important)](https://github.com/effjy/usage) [![GTK](https://img.shields.io/badge/GTK-3.0-brightgreen)](https://github.com/effjy/usage) [![UI Theme](https://img.shields.io/badge/UI%20Theme-Tokyo%20Night-purple)](https://github.com/effjy/usage)<br><br>Real‑time network monitor with live graphs, session totals and PDF reports – Tokyo Night themed. | `stable` |

---

## 🧠 Research & Background

<details>
<summary><b>📖 Click to expand – my story & interests</b></summary>

<br/>

> With over 20 years as a Level 3 security analyst and network administrator, I bring real‑world insight to cryptographic design.  
> For more than a decade, I’ve explored how **SPN** and **ARX** paradigms can be fused to overcome each other’s weaknesses – the Krakken project is the result.

**🎯 Research interests:**
- Wide‑state permutation design
- SPN‑ARX hybrid architectures
- Invariant subspace cryptanalysis
- Algebraic degree propagation
- Operational security (OpSec) & advanced sanitisation

</details>

---

## 📬 Connect with me

<div align="center">

| Platform | Link |
|:--------:|:-----|
| **GitHub** | [@effjy](https://github.com/effjy) |
| **ORCID** | [0009‑0005‑6377‑1675](https://orcid.org/0009‑0005‑6377‑1675) |
| **Gravatar** | [luminous0816ec2f7a](https://gravatar.com/luminous0816ec2f7a) |
| **X (Twitter)** | [@jfclachance](https://x.com/jfclachance) |

</div>

---

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=500&color=00FFCC&center=true&vCenter=true&width=500&lines=Post‑Quantum+ready;Forensically‑sterile+by+design;Krakken‑powered" alt="Typing SVG" />
  <br/>
  <i>“No headers, no signatures – only entropy.”</i>
</div>

---

*🦑 Released into the abyss – 2026*
