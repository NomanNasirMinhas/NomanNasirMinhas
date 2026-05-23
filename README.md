<div align="center">

```
███████╗██╗  ██╗███████╗██╗     ██████╗  ██████╗ ███╗   ██╗
██╔════╝██║  ██║██╔════╝██║     ██╔══██╗██╔═══██╗████╗  ██║
███████╗███████║█████╗  ██║     ██║  ██║██║   ██║██╔██╗ ██║
╚════██║██╔══██║██╔══╝  ██║     ██║  ██║██║   ██║██║╚██╗██║
███████║██║  ██║███████╗███████╗██████╔╝╚██████╔╝██║ ╚████║
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═════╝  ╚═════╝ ╚═╝  ╚═══╝
```

### `whoami`

```bash
[noman@psiberus-lab ~]$ id && uname -a && cat /etc/operator
uid=0(root) gid=0(root) groups=0(root),1337(red-team),31337(elite)
Linux psiberus-lab 6.x.x-hardened #1 SMP PREEMPT x86_64 GNU/Linux
OPERATOR  : Noman Nasir Minhas   ALIAS: Sheldon / malicious_dll
ROLE      : Security Engineer — Offensive Ops & Adversary Emulation
ORG       : Cytomate Solutions & Services — Doha, Qatar 🇶🇦
EDUCATION : MS Cybersecurity — Air University | IEEE Published Researcher
CLEARANCE : [REDACTED] — Need to know only
STATUS    : ACTIVE — CRTO ██████████░░░░ 78%
```

<img src="https://img.shields.io/badge/RED_TEAM-ACTIVE-ff0000?style=for-the-badge&logo=target&logoColor=white"/>
<img src="https://img.shields.io/badge/ADVERSARY_EMULATION-Cytomate-ff4500?style=for-the-badge"/>
<img src="https://img.shields.io/badge/CRTO-IN_PROGRESS-yellow?style=for-the-badge&logo=cobalt&logoColor=black"/>
<img src="https://img.shields.io/badge/IEEE_PUBLISHED-Research-00aaff?style=for-the-badge&logo=ieee&logoColor=white"/>
<br/>
<img src="https://tryhackme-badges.s3.amazonaws.com/scorpion.tar.png" alt="TryHackMe" width="160"/>
<br/>
<a href="https://twitter.com/malicious_dll"><img src="https://img.shields.io/twitter/follow/malicious_dll?logo=twitter&style=for-the-badge&color=ff4500&labelColor=0d0d0d"/></a>
<a href="https://www.cytomate.net"><img src="https://img.shields.io/badge/Research_Base-Cytomate.net-0d0d0d?style=for-the-badge&logo=githubactions&logoColor=ff4500"/></a>
<a href="https://github.com/NomanNasirMinhas"><img src="https://komarev.com/ghpvc/?username=nomannasirminhas&label=RECON+HITS&color=ff4500&style=for-the-badge"/></a>

</div>

---

## ☠️ THREAT ACTOR PROFILE

```
╔══════════════════════════════════════════════════════════════════╗
║  CLASSIFICATION: [TOP SECRET // OFFSEC // RED CELL]             ║
╠══════════════════════════════════════════════════════════════════╣
║  OPERATOR  : Noman Nasir Minhas                                  ║
║  HANDLE    : Sheldon / malicious_dll                             ║
║  MISSION   : Break. Emulate. Detect. Harden. Repeat.            ║
║  THEATER   : Windows Internals · AD · EDR · Post-Exploitation   ║
║  WEAPONS   : Rust · Go · C/C++ · C# · Python · ASM             ║
║  LAB ENV   : VMware/Hyper-V · AD Forest · ELK · MDE · Sysmon   ║
║  INTEL ORG : Cytomate Solutions — Adversary Emulation Division  ║
║  FOUNDER   : Psiberus LLC — Autonomous Adversary Sim Platform   ║
║  RESEARCH  : USPTO Patent 18/530,422 — Cytomate Threat Intel    ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## 🎯 CURRENT OPS

```bash
[noman@psiberus-lab ~]$ cat /var/log/active_ops.log

[+] CRTO EXAM         — Multi-domain AD lab. Child→Parent trust attacks,
                        Kerberos golden ticket forgery (ExtraSids/EA SID),
                        forest trust pivoting via Cobalt Strike beacons
[+] EDR EVASION R&D   — AMSI heap corruption (HAMSICONTEXT), patchless bypass,
                        ETW patching, DLL call tracing via Frida
[+] PSIBERUS PLATFORM — Rust+Go+Tauri adversary sim suite. MQTT/RabbitMQ C2
                        backend, ELK/MDE telemetry, Cobalt Strike integration
[+] PATENT INTEL      — USPTO App #18/530,422 CIP — algorithms, claims,
                        prior art analysis for Cytomate threat intel platform
[+] PQC RESEARCH      — Kyber/Dilithium protocol study, post-quantum
                        crypto migration tooling for enterprise environments
```

---

## 🛠️ ARSENAL — TOOLING & TRADECRAFT

<details>
<summary><b>⚙️ Offensive Tooling (click to expand)</b></summary>

### Windows Evasion & Injection
- **AMSI Bypass**: Heap corruption via `HAMSICONTEXT`, patchless ntdll-level techniques, ETW patching
- **DLL Unhooking**: Section remapping, fresh ntdll load, manual syscall resolution
- **Process Injection**: Fork-chain injection (Go), APC injection, thread hijack, shellcode fluctuation (Rust)
- **Module Stomping**: `dinvoke_rs`-powered stomping with in-memory PE manipulation
- **Loaders**: AES-256-CBC/CTR shellcode encryption/decryption; Zig-based loader with runtime decryption
- **Frida Tracing**: Cross-DLL call chain visibility with full forwarding chain resolution

### Active Directory Tradecraft
- **Kerberoasting / ASREPRoasting** via Impacket / Rubeus
- **Golden Ticket Forgery**: `ExtraSids` field manipulation for cross-domain trust attacks (child → parent)
- **DCSync / SecretsDump**: Credential harvesting from domain controllers
- **BloodHound**: Graph-based attack path enumeration
- **Forest Trust Pivoting**: Inter-forest lateral movement (CONTOSO ↔ ENCLAVE)
- **Constrained Delegation Abuse**: S4U2self / S4U2proxy exploitation

### Network & Protocol Attacks
- **ARP Poisoning (ARP-Puker)**: Gratuitous ARP MITM at Layer 2
- **NTLMv1/v2 Capture**: Inveigh / Responder relay chains
- **WPAD / Proxy Abuse**: Transparent traffic interception
- **TLS Fingerprinting**: JA3/JA3S analysis via Zeek

</details>

<details>
<summary><b>🦀 Languages & Runtimes</b></summary>

```
Language     | Proficiency  | Primary Use
─────────────────────────────────────────────────────────────
Rust         | ████████████ | Implants, drivers, ARP tooling, C2 agents
Go           | ████████████ | Microservices, C2 runners, network tools, loaders
C / C++      | ███████████░ | Malware internals, WinAPI, kernel research
C#           | █████████░░░ | .NET post-exploitation, Cobalt Strike BOFs
Python       | ████████████ | Automation, Impacket, tooling scripts
x86/x64 ASM | ████████░░░░ | Shellcode, syscall stubs, manual trampolines
PowerShell   | █████████░░░ | AD recon, living-off-the-land
Zig          | ███████░░░░░ | Shellcode loaders, cross-compilation experiments
```

</details>

<details>
<summary><b>🔧 Tools & Frameworks</b></summary>

| Category | Tools |
|---|---|
| **C2 Frameworks** | Cobalt Strike, custom MQTT/RabbitMQ C2 (Psiberus) |
| **RE / Analysis** | IDA Pro, Ghidra, x64dbg, Frida, Volatility |
| **Network** | Wireshark, Zeek, Suricata, Nmap, Inveigh, Responder |
| **AD Attacks** | BloodHound, Impacket, CrackMapExec, Mimikatz, Rubeus |
| **Web** | Burp Suite, sqlmap, ffuf |
| **Vuln Scanning** | OpenSCAP, Lynis, CVE Binary Tool (air-gapped) |
| **EDR/SIEM** | MDE, Sysmon, ELK Stack, custom ETW consumers |
| **Crypto** | Kyber/Dilithium (PQC), AES-256 CTR/CBC, C2PA |

</details>

---

## 📦 REPOSITORY INDEX

| Repo | Lang | TTP / Purpose |
|------|------|---------------|
| [**Offensive-Rust**](https://github.com/NomanNasirMinhas/Offensive-Rust) | 🦀 Rust | C2 server · local/remote shellcode injection · WinAPI bindings |
| [**Offensive-Go**](https://github.com/NomanNasirMinhas/Offensive-Go) | 🐹 Go | GoShark (packet capture UI) · NetworkMonitor passive listener |
| [**Rust-Driver-Clone**](https://github.com/NomanNasirMinhas/Rust-Driver-Clone) | 🦀 Rust | Windows kernel driver (WDK) — EDR/AV internals research |
| [**ARP-Puker**](https://github.com/NomanNasirMinhas/ARP-Puker) | 🦀 Rust | Gratuitous ARP poisoning · Layer-2 MITM packet interception |
| [**binary-to-shellcode**](https://github.com/NomanNasirMinhas/binary-to-shellcode) | 🔧 Multi | PE → PIC shellcode conversion with encryption support |
| [**CPP-Utils**](https://github.com/NomanNasirMinhas/CPP-Utils) | ⚙️ C++ | Utility library for malware/offensive tooling (MSVC) |
| [**Pentesting-Notes**](https://github.com/NomanNasirMinhas/Pentesting-Notes) | 📝 — | AD attack mindmaps · pentest cheatsheets · CherryTree notes |
| [**Qiskit-Quantum**](https://github.com/NomanNasirMinhas/Qisikit-Basic-Of-Quantum-Information) | 🐍 Python | Qiskit notebooks — single/multi-qubit quantum information |

> **Private / WIP**: Psiberus agent (Rust) · Zig shellcode loader · Go fork-chain injector · Rust fluctuation implant · ASL JSON generator · sandbox/VM detection toolkit

---

## 🔬 RESEARCH DOMAINS

```
┌─────────────────────────────────────────────────────────────────┐
│  DOMAIN                  CURRENT FOCUS                          │
├─────────────────────────────────────────────────────────────────┤
│  Windows Evasion         AMSI/ETW internals, heap corruption,  │
│                          patchless bypasses, call stack spoof   │
│  Active Directory        Cross-domain/forest trust attacks,     │
│                          ExtraSids golden ticket, Kerberos      │
│  EDR Research            Telemetry blind spots, hook evasion,   │
│                          MDE signal analysis, DLL tracing       │
│  Post-Quantum Crypto     Kyber-768, Dilithium3, secure channel  │
│                          design, PQC migration tooling          │
│  Adversary Emulation     MITRE ATT&CK mapping, ASL framework,  │
│                          automated purple team pipelines        │
│  Malware Analysis        PE internals, memory forensics,        │
│                          behavioral signatures, sandbox escape  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🏗️ PSIBERUS — AUTONOMOUS ADVERSARY SIM PLATFORM

```
[psiberus@lab ~]$ cat /opt/psiberus/README

PSIBERUS — Autonomous AI-Driven Penetration Testing Platform
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

STACK:
  Agent       → Rust (evasion-first, modular payload)
  Operator UI → Tauri + Svelte (desktop)
  C2 Backend  → Go microservices, MQTT/RabbitMQ transport
  Telemetry   → ELK + MDE + Sysmon correlation engine
  Emulation   → MITRE ATT&CK mapped, ASL-native scenario engine

STATUS: [PRIVATE ALPHA] — Founder: Psiberus LLC, Doha QA
```

---

## 📊 OPERATIONAL STATS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=nomannasirminhas&show_icons=true&theme=chartreuse-dark&count_private=true&hide_border=true&bg_color=0d0d0d&title_color=ff4500&icon_color=00ffcc&text_color=c9d1d9" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nomannasirminhas&hide=cmake&langs_count=6&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=ff4500&text_color=c9d1d9&layout=compact" alt="Top Languages" width="49%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=nomannasirminhas&theme=dark&hide_border=true&background=0d0d0d&ring=ff4500&fire=ff4500&currStreakLabel=00ffcc&sideLabels=00ffcc&dates=888888" alt="Streak" width="60%"/>

[![trophy](https://github-profile-trophy.vercel.app/?username=nomannasirminhas&theme=darkhub&no-frame=true&row=1&column=6&margin-w=4)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## ✍️ INTEL DUMP — WRITING & TALKS

- 📡 [Medium @malicious-dll](http://malicious-dll.medium.com/) — Loader design, ETW/AMSI internals, token manipulation, memory forensics, AD attack/defense
- 🔬 **IEEE Research** — Published peer-reviewed offensive security research
- 🧠 **Instagram @science_with_noman** — Physics, quantum computing, space, mathematics science communication

---

## 🧪 CERTIFICATIONS & LABS

<div align="center">

<a href="https://www.hackthebox.com/"><img src="https://img.shields.io/badge/Hack_The_Box-Active-9fef00?style=for-the-badge&logo=hackthebox&logoColor=9fef00&labelColor=0d0d0d"/></a>
<a href="https://tryhackme.com/"><img src="https://img.shields.io/badge/TryHackMe-scorpion.tar-red?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://www.credly.com/"><img src="https://img.shields.io/badge/Credly-Certified-ff6b00?style=for-the-badge&logo=credly&logoColor=white&labelColor=0d0d0d"/></a>
<img src="https://img.shields.io/badge/CRTO-RTO_(In_Progress)-yellow?style=for-the-badge&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/MS_CyberSecurity-Air_University-00aaff?style=for-the-badge&labelColor=0d0d0d"/>

</div>

---

## 📡 ESTABLISH CONNECTION

```bash
[noman@psiberus-lab ~]$ netstat -contact

PROTOCOL   ENDPOINT                              STATUS
─────────────────────────────────────────────────────────────
EMAIL    → contact.nomanminhas@gmail.com         OPEN
TWITTER  → @malicious_dll                        LISTENING
LINKEDIN → /in/noman-nasir-minhas               AUTHENTICATED
MEDIUM   → @malicious-dll                        PUBLISHING
HUB      → beacons.ai/malicious.dll             ACTIVE
GITHUB   → /NomanNasirMinhas                     PUBLIC

TOPICS: GoLang · Rust · C2 Dev · EDR Evasion · AD Attacks
        Quantum Computing · Exploit Dev · Red/Purple Ops
```

<div align="center">
<a href="https://twitter.com/malicious_dll"><img src="https://img.shields.io/badge/X_(Twitter)-@malicious__dll-ff4500?style=for-the-badge&logo=x&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://linkedin.com/in/noman-nasir-minhas"><img src="https://img.shields.io/badge/LinkedIn-noman--nasir--minhas-0077b5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d0d"/></a>
<a href="http://malicious-dll.medium.com/"><img src="https://img.shields.io/badge/Medium-@malicious--dll-00ab6c?style=for-the-badge&logo=medium&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://beacons.ai/malicious.dll"><img src="https://img.shields.io/badge/Links_Hub-beacons.ai-ff4500?style=for-the-badge&labelColor=0d0d0d"/></a>
</div>

---

<div align="center">

```
██████╗ ███████╗███████╗██████╗     ██╗███╗   ██╗    ███████╗██╗██╗     ███████╗███╗   ██╗ ██████╗███████╗
██╔══██╗██╔════╝██╔════╝██╔══██╗    ██║████╗  ██║    ██╔════╝██║██║     ██╔════╝████╗  ██║██╔════╝██╔════╝
██║  ██║█████╗  █████╗  ██████╔╝    ██║██╔██╗ ██║    ███████╗██║██║     █████╗  ██╔██╗ ██║██║     █████╗
██║  ██║██╔══╝  ██╔══╝  ██╔═══╝     ██║██║╚██╗██║    ╚════██║██║██║     ██╔══╝  ██║╚██╗██║██║     ██╔══╝
██████╔╝███████╗███████╗██║         ██║██║ ╚████║    ███████║██║███████╗███████╗██║ ╚████║╚██████╗███████╗
╚═════╝ ╚══════╝╚══════╝╚═╝         ╚═╝╚═╝  ╚═══╝    ╚══════╝╚═╝╚══════╝╚══════╝╚═╝  ╚═══╝ ╚═════╝╚══════╝
```

> *"The best defense is understanding how the offense thinks."*

**🦂 Malware Researcher · Exploit Developer · Red/Purple Team Operator · Science Communicator**

```
All research conducted in controlled lab environments for ethical R&D and defense purposes.
```

</div>
