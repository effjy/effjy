[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=24&duration=3000&pause=500&color=00FF00&background=000000&center=true&vCenter=true&multiline=true&width=800&height=100&lines=%24+whoami;effjy;%24+cat+profile;OpSec+researcher.+Hardened+encryption%2C;post‑quantum+KEMs%2C+file+wiping+%26;kernel‑mode+crypto+–+open+source+in+C.)](https://git.io/typing-svg)

[![Security Researcher](https://img.shields.io/badge/Security_Researcher-Dark_Grey?style=for-the-badge&logo=shield&logoColor=00FF00&color=111111)](https://github.com/effjy)
[![Cryptography](https://img.shields.io/badge/Cryptography-Quantum-00FF00?style=for-the-badge&logo=cryptography&logoColor=00FF00&color=111111)](https://github.com/effjy)
[![Post-Quantum KEM](https://img.shields.io/badge/Post_Quantum_KEM-Kyber-00FF00?style=for-the-badge&logo=quantum&logoColor=00FF00&color=111111)](https://github.com/effjy)

### Hardened encryption, post‑quantum KEMs, file wiping, and kernel‑mode cryptography – all open‑source, all in C.
### 🛡️ OpSec Toolchain

| Repository | Description | Language |
|:-----------|:------------|:---------|
| **🔒 [ase](https://github.com/effjy/ase)** | *AXIS SECURE ENCRYPTION — SHA3‑512 XOR Counter Mode.* Encrypts and decrypts files/directories with robust integrity checks (HMAC‑SHA3‑512 + content hash). Secure memory handling, atomic temp‑file writes, and original file deletion only after full verification. |

`#encryption #sha3 #stream-cipher #file-encryption #integrity`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/ase?style=flat-square&color=blue)](https://github.com/effjy/ase) [![GitHub stars](https://img.shields.io/github/stars/effjy/ase?style=flat-square)](https://github.com/effjy/ase/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/ase?style=flat-square)](https://github.com/effjy/ase) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **📊 [audit](https://github.com/effjy/audit)** | *Ubuntu MATE Hardening & OpSec Audit Report.* A comprehensive system auditor that verifies kernel hardening, filesystem permissions, network exposure, PAM policies, and privacy leaks on Ubuntu MATE. Outputs colour-coded, actionable reports for instant OpSec posture review. |

`#linux-hardening #security-audit #ubuntu #opsec #system-security`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/audit?style=flat-square&color=blue)](https://github.com/effjy/audit) [![GitHub stars](https://img.shields.io/github/stars/effjy/audit?style=flat-square)](https://github.com/effjy/audit/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/audit?style=flat-square)](https://github.com/effjy/audit) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🧹 [awu](https://github.com/effjy/awu)** | *Axis Wiping Utility — data sanitization aligned with NIST SP 800‑88 Rev. 1.* Wipes files, directories, free space, and even fills/releases RAM with configurable multi‑pass schemes. TRIM‑aware, memory‑locked (mlock), and built for forensic‑grade erasure. |

`#data-sanitization #nist-800-88 #file-wiping #forensics #opsec`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/awu?style=flat-square&color=blue)](https://github.com/effjy/awu) [![GitHub stars](https://img.shields.io/github/stars/effjy/awu?style=flat-square)](https://github.com/effjy/awu/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/awu?style=flat-square)](https://github.com/effjy/awu) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **⚡ [axis](https://github.com/effjy/axis)** | *Axis-512 — Hybrid Post‑Quantum File Encryption.* The unbreakable, streaming, post‑quantum‑ready file encryption tool. It layers Keccak‑f[1600] (NIST standard) with XChaCha20‑Poly1305 for uncompromising security. |

`#post-quantum-cryptography #kem #kyber #xchacha20 #file-encryption`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/axis?style=flat-square&color=blue)](https://github.com/effjy/axis) [![GitHub stars](https://img.shields.io/github/stars/effjy/axis?style=flat-square)](https://github.com/effjy/axis/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/axis?style=flat-square)](https://github.com/effjy/axis) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🕵️ [ccu](https://github.com/effjy/ccu)** | *Classified Concealment Utility — deniable encryption with a custom 1024‑bit block cipher.* Key‑dependent S‑Box, 16‑round SPN, Argon2id KDF, HMAC‑SHA3‑512 MAC, and constant‑time operations. Encrypted files look like random noise — no magic bytes, no headers in the clear. |

`#deniable-encryption #custom-cipher #argon2id #constant-time #opsec`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/ccu?style=flat-square&color=blue)](https://github.com/effjy/ccu) [![GitHub stars](https://img.shields.io/github/stars/effjy/ccu?style=flat-square)](https://github.com/effjy/ccu/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/ccu?style=flat-square)](https://github.com/effjy/ccu) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🔏 [cfo](https://github.com/effjy/cfo)** | *Classified File Obfuscator — AES‑256‑GCM + self‑contained decryption stub.* Encrypts any C source or binary into a compilable standalone stub. The stub holds salt, IV, tag, and ciphertext; only the correct password recovers the original file. PBKDF2‑HMAC‑SHA256 key derivation, authenticated GCM. |

`#aes-256-gcm #stub-encryption #pbkdf2 #file-obfuscation #opsec`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/cfo?style=flat-square&color=blue)](https://github.com/effjy/cfo) [![GitHub stars](https://img.shields.io/github/stars/effjy/cfo?style=flat-square)](https://github.com/effjy/cfo/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/cfo?style=flat-square)](https://github.com/effjy/cfo) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🧩 [ckeu](https://github.com/effjy/ckeu)** | *Classified Kyber Encryption Utility — hybrid post‑quantum Kyber‑1024 + X25519 KEM, AES‑256‑GCM AEAD, Argon2id secret key protection.* Deniable file encryption with random padding; memory‑locked, constant‑time operations. Aligned with FIPS 203, FIPS 202, RFC 7748, and RFC 9106. |

`#post-quantum-cryptography #kyber #x25519 #aes-256-gcm #deniable-encryption`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/ckeu?style=flat-square&color=blue)](https://github.com/effjy/ckeu) [![GitHub stars](https://img.shields.io/github/stars/effjy/ckeu?style=flat-square)](https://github.com/effjy/ckeu/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/ckeu?style=flat-square)](https://github.com/effjy/ckeu) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **⚡ [ckeux](https://github.com/effjy/ckeux)** | *Classified Kyber Encryption Utility — XChaCha20‑Poly1305 streaming edition.* Hybrid Kyber‑1024 + X25519 KEM, streaming AEAD (libsodium secretstream), self‑contained Argon2id‑encrypted header, random deniable padding. Chunk‑aligned decryption, RAM‑backed temp files, constant‑time everywhere. |

`#post-quantum-cryptography #xchacha20 #streaming-encryption #kyber #deniable`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/ckeux?style=flat-square&color=blue)](https://github.com/effjy/ckeux) [![GitHub stars](https://img.shields.io/github/stars/effjy/ckeux?style=flat-square)](https://github.com/effjy/ckeux/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/ckeux?style=flat-square)](https://github.com/effjy/ckeux) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **💀 [doomed](https://github.com/effjy/doomed)** | *DOOMED — Dystopian Obfuscation Oriented Multi‑layered Encryption Device.* A research-grade file encryption tool combining hybrid post-quantum KEM (Kyber‑1024 + X25519) with three symmetric ciphers: AES‑256‑GCM (default), XChaCha20‑Poly1305, or an experimental 8192‑bit custom sponge cipher. Features deniable output, double‑layer EME‑style construction, `mlock` memory locking, and constant‑time operations. |

`#post-quantum-cryptography #kyber #aes-256-gcm #xchacha20 #sponge-cipher #deniable-encryption`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/doomed?style=flat-square&color=blue)](https://github.com/effjy/doomed) [![GitHub stars](https://img.shields.io/github/stars/effjy/doomed?style=flat-square)](https://github.com/effjy/doomed/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/doomed?style=flat-square)](https://github.com/effjy/doomed) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🔆 [light](https://github.com/effjy/light)** | *Hybrid Post‑Quantum KEM • Streaming AEAD • Suite A‑Style Simulation.* Shines a little light… with a touch of Obscurity. This project is your go‑to for post‑quantum file encryption, employing a hybrid key encapsulation mechanism (KEM) for secure key transport. |

`#post-quantum-cryptography #hybrid-kem #streaming-aead #opsec`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/light?style=flat-square&color=blue)](https://github.com/effjy/light) [![GitHub stars](https://img.shields.io/github/stars/effjy/light?style=flat-square)](https://github.com/effjy/light/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/light?style=flat-square)](https://github.com/effjy/light) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🌀 [obscurity](https://github.com/effjy/obscurity)** | *A hardened, research‑grade implementation of a novel sponge‑based cryptographic primitive.* Simulates the engineering discipline, operational security patterns, and threat‑model assumptions of classified cryptographic systems (e.g., NSA Suite A‑style ciphers). |

`#sponge-cipher #arx #constant-time #research-cipher #opsec`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/obscurity?style=flat-square&color=blue)](https://github.com/effjy/obscurity) [![GitHub stars](https://img.shields.io/github/stars/effjy/obscurity?style=flat-square)](https://github.com/effjy/obscurity/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/obscurity?style=flat-square)](https://github.com/effjy/obscurity) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🔐 [saif](https://github.com/effjy/saif)** | *Multi-cipher Post‑Quantum Encryption Utility — AES‑256‑GCM, XChaCha20‑Poly1305 & custom Saif v4 cipher.* Hybrid Kyber‑1024 + X25519 KEM, Argon2id KDF. 24‑round ARX sponge with dual‑capacity authentication tag, quantum feed‑forward, and extra Keccak‑χ every 4 rounds. Constant‑time, 7‑pass secure deletion, output indistinguishable from random noise. |

`#post-quantum-cryptography #kyber #x25519 #aes-256-gcm #xchacha20 #custom-cipher #arx #constant-time`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/saif?style=flat-square&color=blue)](https://github.com/effjy/saif) [![GitHub stars](https://img.shields.io/github/stars/effjy/saif?style=flat-square)](https://github.com/effjy/saif/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/saif?style=flat-square)](https://github.com/effjy/saif) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🔒 [secure_mount](https://github.com/effjy/secure_mount)** | *A menu‑driven, secure wrapper for gocryptfs.* Simplifies initializing, mounting, and unmounting encrypted filesystems with zero‑effort hardening. No more memorising complex command lines. |

`#gocryptfs #filesystem-encryption #fuse #file-security`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/secure_mount?style=flat-square&color=blue)](https://github.com/effjy/secure_mount) [![GitHub stars](https://img.shields.io/github/stars/effjy/secure_mount?style=flat-square)](https://github.com/effjy/secure_mount/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/secure_mount?style=flat-square)](https://github.com/effjy/secure_mount) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |
| **🖼️ [viewer](https://github.com/effjy/viewer)** | *RAM‑only image viewer for classified/sensitive JPEG and PNG files.* Loads images directly into non‑swappable (`mlock`) memory, securely wipes all pixel data on exit, and never writes decrypted data to disk. |

`#memory-security #image-viewer #mlock #jpeg #png`

[![GitHub language](https://img.shields.io/github/languages/top/effjy/viewer?style=flat-square&color=blue)](https://github.com/effjy/viewer) [![GitHub stars](https://img.shields.io/github/stars/effjy/viewer?style=flat-square)](https://github.com/effjy/viewer/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/effjy/viewer?style=flat-square)](https://github.com/effjy/viewer) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) | `C` |

“Open‑source contributor evolving around OpSec. Most of the time around cryptography.”  
[0†View all repositories →](https://github.com/effjy?tab=repositories)
