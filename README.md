<!--
  ElliotSop Security — GitHub Profile README
  Repo: github.com/00ElliotSop/00ElliotSop  (special profile repo — must match your username exactly)
  This file renders as your GitHub profile page.
-->

```
 ███████╗██╗     ██╗     ██╗ ██████╗ ████████╗███████╗ ██████╗ ██████╗ 
 ██╔════╝██║     ██║     ██║██╔═══██╗╚══██╔══╝██╔════╝██╔═══██╗██╔══██╗
 █████╗  ██║     ██║     ██║██║   ██║   ██║   ███████╗██║   ██║██████╔╝
 ██╔══╝  ██║     ██║     ██║██║   ██║   ██║   ╚════██║██║   ██║██╔═══╝ 
 ███████╗███████╗███████╗██║╚██████╔╝   ██║   ███████║╚██████╔╝██║     
 ╚══════╝╚══════╝╚══════╝╚═╝ ╚═════╝   ╚═╝   ╚══════╝ ╚═════╝ ╚═╝     
```

<div align="center">

**`Offensive Security · Red Team Operations · Applied Adversary Simulation`**

[![OSCP](https://img.shields.io/badge/OSCP-Certified-red?style=flat-square)](https://elliotsop.com)
[![CRTP](https://img.shields.io/badge/CRTP-Certified-red?style=flat-square)](https://elliotsop.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%202%25-black?style=flat-square&logo=tryhackme)](https://tryhackme.com)
[![Website](https://img.shields.io/badge/elliotsop.com-live-darkred?style=flat-square)](https://elliotsop.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-padeshina-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/padeshina)

</div>

---

```bash
┌──(elliotsop㉿kali)-[~]
└─$ cat profile.json
```

```json
{
  "name"         : "Prince Adeshina",
  "alias"        : "ElliotSop",
  "role"         : "Offensive Security Specialist",
  "company"      : "ElliotSop Security LLC",
  "location"     : "Toronto, Ontario 🇨🇦",
  "certifications": ["OSCP", "CRTP"],
  "thm_rank"     : "Top 2%",
  "focus"        : [
                     "Active Directory Exploitation",
                     "Custom Tooling & Exploit Development",
                     "AV/EDR Evasion",
                     "Red Team Operations",
                     "Adversary Simulation"
                   ],
  "website"      : "https://elliotsop.com",
  "contact"      : "contact@elliotsop.com"
}
```

---

```bash
┌──(elliotsop㉿kali)-[~]
└─$ cat skills.txt
```

```
[ Active Directory ]      ████████████████████░  95%
[ AV/EDR Evasion   ]      ██████████████████░░░  90%
[ Network Recon    ]      ███████████████████░░  92%
[ Exploit Dev      ]      █████████████████░░░░  85%
[ Python / Tooling ]      ██████████████████░░░  88%
[ PowerShell       ]      █████████████████░░░░  85%
[ C# / .NET        ]      ████████████████░░░░░  80%
[ Web App Testing  ]      █████████████████░░░░  83%
[ OSINT            ]      ████████████████░░░░░  82%
```

---

```bash
┌──(elliotsop㉿kali)-[~]
└─$ ls -la projects/
```

| Repo | Description | Stack |
|------|-------------|-------|
| [**PassForge**](https://github.com/00ElliotSop/PassForge) | Personalized wordlist generator + HIBP breach intelligence | `Python` |
| [**NetRecon**](https://github.com/00ElliotSop/NetRecon) | Network recon & service fingerprinting engine | `Python` |
| [**ADReaper**](https://github.com/00ElliotSop/ADReaper) | AD enumeration & attack path mapper | `Python` `LDAP` |
| [**PE Injector Framework**](https://github.com/00ElliotSop) | Process hollowing, thread hijacking, APC injection + EDR evasion | `C#` |
| [**Custom C2 Framework**](https://github.com/00ElliotSop) | Encrypted comms, modular payloads, anti-forensics | `Python` |
| [**Shellcode Crypter**](https://github.com/00ElliotSop) | AES/XOR multi-stage crypter + syscall-evading loader | `C` `ASM` |
| [**AD Attack Toolkit**](https://github.com/00ElliotSop) | Kerberoasting, AS-REP, DCSync, Golden Ticket w/ OPSEC | `PowerShell` |
| [**WiFi Handshake Tool**](https://github.com/00ElliotSop) | WPA/WPA2 capture, deauth, hash cracking integration | `Python` |

---

```bash
┌──(elliotsop㉿kali)-[~]
└─$ cat attack_lifecycle.txt
```

```
  RECON ──► INITIAL ACCESS ──► PRIV ESC ──► LATERAL MOVE ──► EXFIL
    │              │               │              │              │
  OSINT        Phishing        Windows/       PtH / PtT      DNS
  Nmap         App Exploits    Linux PE       WMI / DCOM     Tunnel
  DNS Enum     Pass Spray      Token Abuse    Kerb Abuse     Covert
  Subdomain    Drive-by        Kernel Expls   DCOM Lateral   Channel
```

---

```bash
┌──(elliotsop㉿kali)-[~]
└─$ cat toolkit.sh | head -20
```

```bash
TOOLKIT=(
  "BloodHound"     # AD attack path mapping
  "Cobalt Strike"  # adversary simulation C2
  "Mimikatz"       # credential harvesting
  "Rubeus"         # Kerberos abuse
  "Impacket"       # SMB / Kerberos / DCSync
  "Burp Suite Pro" # web application testing
  "Metasploit"     # exploitation framework
  "aircrack-ng"    # wireless security
  "Ghidra"         # reverse engineering
  "x64dbg"         # dynamic analysis
  "Custom tooling" # C# · Python · PowerShell
)
```

---

```bash
┌──(elliotsop㉿kali)-[~]
└─$ cat contact.gpg
```

```
  ┌─────────────────────────────────────────────────────────┐
  │  Consulting · Red Team Assessments · Custom Tooling     │
  │                                                         │
  │  web     →  elliotsop.com                              │
  │  email   →  contact@elliotsop.com                      │
  │  github  →  github.com/00ElliotSop                     │
  │  linkedin→  linkedin.com/in/padeshina                  │
  └─────────────────────────────────────────────────────────┘
```

<div align="center">

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=00ElliotSop&show_icons=true&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=e84242&icon_color=e84242&text_color=ffffff)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=00ElliotSop&layout=compact&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=e84242&text_color=ffffff)

---

*All tools and techniques demonstrated here are used exclusively in authorised penetration testing engagements and controlled lab environments.*

**ElliotSop Security LLC** · Toronto, Ontario · [elliotsop.com](https://elliotsop.com)

</div>
