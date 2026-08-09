<div align="center">

```
███████╗██╗  ██╗███████╗██╗     ██████╗  ██████╗ ███╗   ██╗
██╔════╝██║  ██║██╔════╝██║     ██╔══██╗██╔═══██╗████╗  ██║
███████╗███████║█████╗  ██║     ██║  ██║██║   ██║██╔██╗ ██║
╚════██║██╔══██║██╔══╝  ██║     ██║  ██║██║   ██║██║╚██╗██║
███████║██║  ██║███████╗███████╗██████╔╝╚██████╔╝██║ ╚████║
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═════╝  ╚═════╝ ╚═╝  ╚═══╝
```

`I break Windows in kernel space, forge Kerberos tickets across forests, and`
`in the other half of my brain I do quantum mechanics and teach physics.`

</div>

---

### `boot sequence`

```bash
[noman@psiberus-lab ~]$ ./whoami --verbose
[*] resolving operator identity ......................... OK
[*] loading tradecraft modules ......................... OK
[*] mounting quantum research partition ................ OK
[*] warning: operator runs offensive R&D and physics papers in parallel

uid=0(root) gid=0(root) groups=0(root),1337(red-team),31337(elite),42(physicist)
Linux psiberus-lab 6.x.x-hardened #1 SMP PREEMPT x86_64 GNU/Linux

OPERATOR  : Noman Nasir Minhas          ALIAS : Sheldon / malicious_dll
ROLE      : Security Engineer — Offensive Ops & Adversary Emulation
ORG       : Cytomate Solutions & Services — Doha, Qatar 🇶🇦
FOUNDER   : Psiberus LLC — Autonomous Adversary Simulation Platform
EDUCATION : MS Cybersecurity — Air University · IEEE Published Researcher
DUAL-CORE : Red Team Tradecraft  ||  Foundational Physics & QIS
STATUS    : ACTIVE — CRTO ✔  CRTL ✔  [Red Team Operator + Lead]
```

<div align="center">

<img src="https://img.shields.io/badge/RED_TEAM-ACTIVE-ff0000?style=for-the-badge&logo=target&logoColor=white"/>
<img src="https://img.shields.io/badge/ADVERSARY_EMULATION-Cytomate-ff4500?style=for-the-badge"/>
<img src="https://img.shields.io/badge/CRTO-CERTIFIED-ff4500?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/CRTL-CERTIFIED-b30000?style=for-the-badge&logoColor=white"/>
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
║  CLASSIFICATION: [TOP SECRET // OFFSEC // RED CELL]              ║
╠══════════════════════════════════════════════════════════════════╣
║  OPERATOR  : Noman Nasir Minhas                                  ║
║  HANDLE    : Sheldon / malicious_dll                            ║
║  MISSION   : Break. Emulate. Detect. Harden. Repeat.           ║
║  THEATER   : Windows Internals · AD · EDR · Post-Exploitation  ║
║  WEAPONS   : Rust · Go · C/C++ · C# · Python · ASM            ║
║  LAB ENV   : VMware/Hyper-V · AD Forest · ELK · MDE · Sysmon  ║
║  INTEL ORG : Cytomate Solutions — Adversary Emulation Division ║
║  FOUNDER   : Psiberus LLC — Autonomous Adversary Sim Platform  ║
║  CERTS     : CRTO (Operator) + CRTL (Lead) — Zero-Point Sec    ║
║  SIDE-CORE : Quantum information · QED · foundational physics  ║
╚══════════════════════════════════════════════════════════════════╝
```

> Most operators stop at the exploit. I keep going — down into kernel objects
> and callback tables, and sideways into Hilbert spaces and photon localization.
> The overlap isn't an accident: both are about seeing the machine underneath
> the abstraction everyone else takes for granted.

---

## 🎯 CURRENT OPS

```bash
[noman@psiberus-lab ~]$ cat /var/log/active_ops.log
[+] ADVERSARY SIMULATION  — Full-scope red team engagements @ Cytomate.
                            MITRE ATT&CK-mapped campaigns, purple team
                            pipelines, ASL-driven scenario automation
[+] KERNEL DRIVERS DEV    — Windows kernel driver research in Rust (WDK).
                            EDR/AV internals, DKOM, callback manipulation,
                            minifilter drivers, object/handle hooking
[+] AD SECURITY RESEARCH  — Cross-domain/forest trust attack chains,
                            Kerberos delegation abuse, ExtraSids golden
                            ticket forgery, DCSync, BloodHound pathing
[+] QUANTUM CYBERSECURITY — Post-quantum cryptography migration tooling,
                            Kyber-768 / Dilithium3 protocol integration,
                            quantum-safe secure channel design research
[+] EDR EVASION R&D       — AMSI heap corruption (HAMSICONTEXT), ETW
                            patching, patchless syscall techniques, DLL
                            call tracing via Frida, hook evasion research
[+] PSIBERUS PLATFORM     — Rust+Go+Tauri autonomous adversary sim suite.
                            MQTT/RabbitMQ C2 backend, ELK/MDE telemetry
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
x86/x64 ASM  | ████████░░░░ | Shellcode, syscall stubs, manual trampolines
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
| **Quantum** | Qiskit, QuTiP, Stim — QIS + circuit simulation |

</details>

---

## 🧬 THE UNCOMMON STACK

```
[noman@psiberus-lab ~]$ ./what_makes_this_profile_different.sh

  Most red teamers ──────────────► exploit → report → repeat
  Most physicists  ──────────────► theory → paper → repeat

  This operator sits on the intersection:

     OFFENSIVE SECURITY  ◄──────────►  FOUNDATIONAL PHYSICS
     ├─ kernel drivers                 ├─ quantum information (QIS)
     ├─ EDR/AMSI/ETW internals         ├─ QED / photon localization
     ├─ AD forest attack chains        ├─ pulsars / quantum gravity
     └─ adversary emulation            └─ science communication

            └────────── converge on ──────────┘
                POST-QUANTUM SECURITY R&D
           (Kyber-768 · Dilithium3 · secure channels)
```

> I ship offensive tooling *and* author physics preprints under my own name.
> The quantum work isn't a hobby bolted onto the résumé — it's why the
> post-quantum crypto research on the security side actually holds up.

---

## 🔬 RESEARCH DOMAINS

```
┌─────────────────────────────────────────────────────────────────┐
│  DOMAIN                  CURRENT FOCUS                           │
├─────────────────────────────────────────────────────────────────┤
│  Windows Evasion         AMSI/ETW internals, heap corruption,   │
│                          patchless bypasses, call stack spoof    │
│  Active Directory        Cross-domain/forest trust attacks,      │
│                          ExtraSids golden ticket, Kerberos       │
│  EDR Research            Telemetry blind spots, hook evasion,    │
│                          MDE signal analysis, DLL tracing        │
│  Post-Quantum Crypto     Kyber-768, Dilithium3, secure channel   │
│                          design, PQC migration tooling           │
│  Adversary Emulation     MITRE ATT&CK mapping, ASL framework,    │
│                          automated purple team pipelines         │
│  Quantum Information      Qubits, Hilbert spaces, QED, photon    │
│                          localization — published preprints      │
└─────────────────────────────────────────────────────────────────┘
```

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

<img src="https://github-readme-stats.vercel.app/api?username=nomannasirminhas&show_icons=true&count_private=true&hide_border=true&bg_color=0d0d0d&title_color=ff4500&icon_color=00ffcc&text_color=c9d1d9" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nomannasirminhas&hide=cmake&langs_count=6&hide_border=true&bg_color=0d0d0d&title_color=ff4500&text_color=c9d1d9&layout=compact&cache_seconds=1800" alt="Top Languages" width="49%"/>
<img src="https://streak-stats.demolab.com/?user=nomannasirminhas&theme=dark&hide_border=true&background=0d0d0d&ring=ff4500&fire=ff4500&currStreakLabel=00ffcc&sideLabels=00ffcc&dates=888888&stroke=ff4500" alt="Streak" width="60%"/>

[![trophy](https://trophy.benkou.dev/?username=nomannasirminhas&theme=darkhub&no-frame=true&row=1&column=6&margin-w=4)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## ✍️ INTEL DUMP — WRITING & TALKS

- 📡 [Medium @malicious-dll](http://malicious-dll.medium.com/) — Loader design, ETW/AMSI internals, token manipulation, memory forensics, AD attack/defense
- 🔬 **IEEE Research** — Published peer-reviewed offensive security research
- ⚛️ **Physics Preprints** — Independent papers on quantum information, QED, and foundational physics under my own name
- 🧠 **Instagram @science_with_noman** — Physics, quantum computing, space, and mathematics science communication

---

## 🧪 CERTIFICATIONS & LABS

<div align="center">

<a href="https://www.hackthebox.com/"><img src="https://img.shields.io/badge/Hack_The_Box-Active-9fef00?style=for-the-badge&logo=hackthebox&logoColor=9fef00&labelColor=0d0d0d"/></a>
<a href="https://tryhackme.com/"><img src="https://img.shields.io/badge/TryHackMe-scorpion.tar-red?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://www.credly.com/"><img src="https://img.shields.io/badge/Credly-Certified-ff6b00?style=for-the-badge&logo=credly&logoColor=white&labelColor=0d0d0d"/></a>
<br/>
<a href="https://training.zeropointsecurity.co.uk/courses/red-team-ops"><img src="https://img.shields.io/badge/CRTO-Red_Team_Operator-ff4500?style=for-the-badge&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://training.zeropointsecurity.co.uk/courses/red-team-ops-ii"><img src="https://img.shields.io/badge/CRTL-Red_Team_Lead-b30000?style=for-the-badge&logoColor=white&labelColor=0d0d0d"/></a>
<img src="https://img.shields.io/badge/MS_CyberSecurity-Air_University-00aaff?style=for-the-badge&labelColor=0d0d0d"/>

</div>

---

## 📡 ESTABLISH CONNECTION

```bash
[noman@psiberus-lab ~]$ netstat -contact
PROTOCOL   ENDPOINT                              STATUS
─────────────────────────────────────────────────────────────
EMAIL    → contact.nomanminhas@gmail.com         OPEN
TWITTER  → @malicious_dll                         LISTENING
LINKEDIN → /in/noman-nasir-minhas                 AUTHENTICATED
MEDIUM   → @malicious-dll                          PUBLISHING
HUB      → beacons.ai/malicious.dll                ACTIVE
GITHUB   → /NomanNasirMinhas                        PUBLIC
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

> *"The best defense is understanding how the offense thinks —*
> *and the best offense is understanding the machine one layer deeper than anyone expects."*

**🦂 Malware Researcher · Exploit Developer · Kernel Tinkerer · Red/Purple Team Lead · Physicist-at-large**

```
All offensive research conducted in controlled lab environments for ethical R&D and defense purposes.
```

</div>
