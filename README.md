<div align="center">

```ansi
[38;2;199;125;255m███████╗██╗  ██╗███████╗██╗     ██████╗  ██████╗ ███╗   ██╗[0m
[38;2;157;78;221m██╔════╝██║  ██║██╔════╝██║     ██╔══██╗██╔═══██╗████╗  ██║[0m
[38;2;123;44;191m███████╗███████║█████╗  ██║     ██║  ██║██║   ██║██╔██╗ ██║[0m
[38;2;72;149;239m╚════██║██╔══██║██╔══╝  ██║     ██║  ██║██║   ██║██║╚██╗██║[0m
[38;2;0;180;216m███████║██║  ██║███████╗███████╗██████╔╝╚██████╔╝██║ ╚████║[0m
[38;2;72;202;228m╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═════╝  ╚═════╝ ╚═╝  ╚═══╝[0m
```

`Break the abstraction. Emulate the adversary. Harden what's left.`
`Kernel-space when it has to be · forests when they let me in.`

</div>

---

### `boot sequence`

```ansi
[38;5;46mnoman@psiberus-lab[0m:[38;5;44m~[0m$ ./whoami --verbose
[38;5;244m[*] resolving operator identity ................[0m [38;5;46mOK[0m
[38;5;244m[*] loading evasion + injection modules ........[0m [38;5;46mOK[0m
[38;5;244m[*] mounting AD attack + kernel toolkits .......[0m [38;5;46mOK[0m

[38;5;44muid[0m=0([38;5;202mroot[0m) [38;5;44mgid[0m=0([38;5;202mroot[0m) groups=0(root),1337([38;5;202mred-team[0m),31337([38;5;220melite[0m)
[38;5;244mLinux psiberus-lab 6.x.x-hardened #1 SMP PREEMPT x86_64 GNU/Linux[0m

[38;5;44mOPERATOR [0m : [1mNoman Nasir Minhas[0m          [38;5;44mALIAS[0m : Sheldon / malicious_dll
[38;5;44mROLE     [0m : Security Engineer — Offensive Ops & Adversary Emulation
[38;5;44mORG      [0m : Cytomate Solutions & Services — Doha, Qatar 🇶🇦
[38;5;44mFOUNDER  [0m : Psiberus LLC — Autonomous Adversary Simulation Platform
[38;5;44mEDUCATION[0m : MS Cybersecurity — Air University · IEEE Published
[38;5;44mSTATUS   [0m : [38;5;46mACTIVE[0m — CRTO [38;5;46m✔[0m  CRTL [38;5;46m✔[0m  [Red Team Operator + Lead]
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
╔═══════════════════════════════════════════════════════════════╗
║ CLASSIFICATION: [TOP SECRET // OFFSEC // RED CELL]            ║
╠═══════════════════════════════════════════════════════════════╣
║ OPERATOR  : Noman Nasir Minhas                                ║
║ HANDLE    : Sheldon / malicious_dll                           ║
║ MISSION   : Break. Emulate. Detect. Harden. Repeat.           ║
║ THEATER   : Windows Internals · AD · EDR · Post-Exploitation  ║
║ WEAPONS   : Rust · Go · C/C++ · C# · Python · ASM             ║
║ LAB ENV   : VMware/Hyper-V · AD Forest · ELK · MDE · Sysmon   ║
║ INTEL ORG : Cytomate Solutions — Adversary Emulation Division ║
║ FOUNDER   : Psiberus LLC — Autonomous Adversary Sim Platform  ║
║ CERTS     : CRTO (Operator) + CRTL (Lead) — Zero-Point Sec    ║
║ OFF-HOURS : quantum computing + physics — self-study, for fun ║
╚═══════════════════════════════════════════════════════════════╝
```

> Most operators stop at the exploit. I keep going — down into kernel objects,
> callback tables, and the telemetry that's supposed to catch me. Break it,
> emulate it, then help the blue side see it coming.

---

## 🎯 CURRENT OPS

```ansi
[38;5;46mnoman@psiberus-lab[0m:~$ cat /var/log/active_ops.log
[38;5;202m[+][0m [38;5;44mADVERSARY SIMULATION  [0m— Full-scope red team engagements @ Cytomate.
                            MITRE ATT&CK-mapped campaigns, purple team
                            pipelines, ASL-driven scenario automation
[38;5;202m[+][0m [38;5;44mKERNEL DRIVERS DEV    [0m— Windows kernel driver research in Rust (WDK).
                            EDR/AV internals, DKOM, callback manipulation
                            minifilter drivers, object/handle hooking
[38;5;202m[+][0m [38;5;44mAD SECURITY RESEARCH  [0m— Cross-domain / forest trust attack chains,
                            Kerberos delegation abuse, ExtraSids golden
                            ticket forgery, DCSync, BloodHound pathing
[38;5;202m[+][0m [38;5;44mPOST-QUANTUM CRYPTO   [0m— Kyber-768 / Dilithium3 protocol integration,
                            quantum-safe secure channel design + PQC
                            migration tooling for offensive/defensive use
[38;5;202m[+][0m [38;5;44mEDR EVASION R&D       [0m— AMSI heap corruption (HAMSICONTEXT), ETW
                            patching, patchless syscall techniques, DLL
                            call tracing via Frida, hook evasion research
[38;5;202m[+][0m [38;5;44mPSIBERUS PLATFORM     [0m— Rust+Go+Tauri autonomous adversary sim suite.
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

</details>

---

## 🔬 RESEARCH DOMAINS

```
┌───────────────────────────────────────────────────────────────┐
│ DOMAIN                  CURRENT FOCUS                         │
├───────────────────────────────────────────────────────────────┤
│ Windows Evasion         AMSI/ETW internals, heap corruption,  │
│                         patchless bypasses, call-stack spoof  │
│ Active Directory        Cross-domain / forest trust attacks,  │
│                         ExtraSids golden ticket, Kerberos     │
│ EDR Research            Telemetry blind spots, hook evasion,  │
│                         MDE signal analysis, DLL tracing      │
│ Post-Quantum Crypto     Kyber-768, Dilithium3, secure-channel │
│                         design, PQC migration tooling         │
│ Adversary Emulation     MITRE ATT&CK mapping, ASL framework,  │
│                         automated purple-team pipelines       │
└───────────────────────────────────────────────────────────────┘
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
| [**Qiskit-Quantum**](https://github.com/NomanNasirMinhas/Qisikit-Basic-Of-Quantum-Information) | 🐍 Python | Qiskit notebooks — quantum computing (personal study) |

> **Private / WIP**: Psiberus agent (Rust) · Zig shellcode loader · Go fork-chain injector · Rust fluctuation implant · ASL JSON generator · sandbox/VM detection toolkit

---

## 🏗️ PSIBERUS — AUTONOMOUS ADVERSARY SIM PLATFORM

```ansi
[38;5;46mpsiberus@lab[0m:~$ cat /opt/psiberus/README
[38;5;202mPSIBERUS[0m — Autonomous AI-Driven Penetration Testing Platform
[38;5;244m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m
[38;5;44mSTACK:[0m
  [38;5;44mAgent      [0m → Rust (evasion-first, modular payload)
  [38;5;44mOperator UI[0m → Tauri + Svelte (desktop)
  [38;5;44mC2 Backend [0m → Go microservices, MQTT/RabbitMQ transport
  [38;5;44mTelemetry  [0m → ELK + MDE + Sysmon correlation engine
  [38;5;44mEmulation  [0m → MITRE ATT&CK mapped, ASL-native scenario engine
[38;5;44mSTATUS:[0m [38;5;202m[PRIVATE ALPHA][0m — Founder: Psiberus LLC, Doha QA
```

---

## 📊 OPERATIONAL STATS

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=nomannasirminhas&show_icons=true&count_private=true&include_all_commits=true&rank_icon=github&show=reviews,prs_merged_percentage&custom_title=Sheldon+//+OFFSEC+Stats&number_format=short&title_color=c77dff&icon_color=48cae4&text_color=d7c6ff&ring_color=48cae4&border_color=9d4edd&border_radius=10&bg_color=135,17082e,0a1826&cache_seconds=21600" alt="GitHub Stats" width="49%"/>
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=nomannasirminhas&langs_count=8&layout=compact&hide=cmake&custom_title=Weapons+of+Choice&title_color=48cae4&text_color=d7c6ff&border_color=00b4d8&border_radius=10&bg_color=135,0a1826,17082e&cache_seconds=21600" alt="Top Languages" width="49%"/>
<img src="https://streak-stats.demolab.com/?user=nomannasirminhas&theme=dark&hide_border=true&background=0a1826&ring=9d4edd&fire=c77dff&currStreakLabel=48cae4&sideLabels=48cae4&dates=8a7bb0&stroke=9d4edd" alt="Streak" width="60%"/>

[![trophy](https://trophy.benkou.dev/?username=nomannasirminhas&theme=darkhub&no-frame=true&row=1&column=6&margin-w=4)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## ✍️ INTEL DUMP — WRITING & TALKS

- 📡 [Medium @malicious-dll](http://malicious-dll.medium.com/) — Loader design, ETW/AMSI internals, token manipulation, memory forensics, AD attack/defense
- 🔬 **IEEE Research** — Published peer-reviewed offensive security research
- 🧠 **Instagram** — Casual science communication on the side (physics, quantum, space) — a hobby, not a day job

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

```ansi
[38;5;46mnoman@psiberus-lab[0m:~$ netstat --contact
[38;5;244mPROTOCOL   ENDPOINT                               STATUS[0m
[38;5;44mEMAIL    [0m→ contact.nomanminhas@gmail.com         [38;5;46mOPEN[0m
[38;5;44mTWITTER  [0m→ @malicious_dll                        [38;5;44mLISTENING[0m
[38;5;44mLINKEDIN [0m→ /in/noman-nasir-minhas                [38;5;44mAUTHENTICATED[0m
[38;5;44mMEDIUM   [0m→ @malicious-dll                        [38;5;202mPUBLISHING[0m
[38;5;44mGITHUB   [0m→ /NomanNasirMinhas                     [38;5;46mPUBLIC[0m
[38;5;244mTOPICS: GoLang · Rust · C2 Dev · EDR Evasion · AD Attacks
        Post-Quantum Crypto · Exploit Dev · Red/Purple Ops[0m
```

<div align="center">

<a href="https://twitter.com/malicious_dll"><img src="https://img.shields.io/badge/X_(Twitter)-@malicious__dll-ff4500?style=for-the-badge&logo=x&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://linkedin.com/in/noman-nasir-minhas"><img src="https://img.shields.io/badge/LinkedIn-noman--nasir--minhas-0077b5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d0d"/></a>
<a href="http://malicious-dll.medium.com/"><img src="https://img.shields.io/badge/Medium-@malicious--dll-00ab6c?style=for-the-badge&logo=medium&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://beacons.ai/malicious.dll"><img src="https://img.shields.io/badge/Links_Hub-beacons.ai-ff4500?style=for-the-badge&labelColor=0d0d0d"/></a>

</div>

---

<div align="center">

```ansi
[38;2;72;202;228m██████╗ ███████╗███████╗██████╗     ██╗███╗   ██╗    ███████╗██╗██╗     ███████╗███╗   ██╗ ██████╗███████╗[0m
[38;2;0;180;216m██╔══██╗██╔════╝██╔════╝██╔══██╗    ██║████╗  ██║    ██╔════╝██║██║     ██╔════╝████╗  ██║██╔════╝██╔════╝[0m
[38;2;72;149;239m██║  ██║█████╗  █████╗  ██████╔╝    ██║██╔██╗ ██║    ███████╗██║██║     █████╗  ██╔██╗ ██║██║     █████╗[0m
[38;2;123;44;191m██║  ██║██╔══╝  ██╔══╝  ██╔═══╝     ██║██║╚██╗██║    ╚════██║██║██║     ██╔══╝  ██║╚██╗██║██║     ██╔══╝[0m
[38;2;157;78;221m██████╔╝███████╗███████╗██║         ██║██║ ╚████║    ███████║██║███████╗███████╗██║ ╚████║╚██████╗███████╗[0m
[38;2;199;125;255m╚═════╝ ╚══════╝╚══════╝╚═╝         ╚═╝╚═╝  ╚═══╝    ╚══════╝╚═╝╚══════╝╚══════╝╚═╝  ╚═══╝ ╚═════╝╚══════╝[0m
```

> *"The best defense is understanding how the offense thinks."*

**🦂 Malware Researcher · Exploit Developer · Kernel Tinkerer · Red/Purple Team Lead**

```
All offensive research conducted in controlled lab environments for ethical R&D and defense purposes.
```

</div>
