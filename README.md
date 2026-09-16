# Oleksii Yelenskyi

Junior SOC Analyst, Kraków

I studied cybersecurity and now I mostly work on detection: writing Sigma rules for Windows and checking them against real attack logs to see what they actually catch and what they miss.

Looking for my first job in a SOC or IT support team, in Kraków or remote. I have the right to work in Poland.

<a href="mailto:alekselenskiy.twink@gmail.com"><img src="https://img.shields.io/badge/Email-alekselenskiy.twink%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>

---

### soc-detection-lab

[github.com/flexeykinDev/soc-detection-lab](https://github.com/flexeykinDev/soc-detection-lab)

Three Sigma rules tested on 278 real EVTX attack captures from a public dataset. They fired 17 times across 15 captures, including mimikatz, Meterpreter and MalSeclogon.

A few things I learned along the way:

- The LSASS rule looks at process access masks instead of file names, so it still works when a tool is renamed.
- I converted the rules to Splunk SPL and to KQL for Defender XDR. One of them didn't convert to KQL, and the README explains why.
- My first PowerShell rule had false positives on the remoting host. I narrowed it down and kept the real attacks.

![Sigma](https://img.shields.io/badge/Sigma-555?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-555?style=flat-square)
![Sysmon](https://img.shields.io/badge/Sysmon-555?style=flat-square)
![KQL](https://img.shields.io/badge/KQL-555?style=flat-square)
![Splunk SPL](https://img.shields.io/badge/Splunk_SPL-555?style=flat-square)

---

### What I work with

![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-333?style=flat-square&logo=linux&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-555?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### Other stuff

Side projects I built with AI help. I made the decisions, tested and fixed them, and got them working.

| | |
|---|---|
| [QuasarMC](https://github.com/flexeykinDev/QuasarMC) | Minecraft server core written from scratch in Java |
| [dbd-perk-randomizer](https://github.com/flexeykinDev/dbd-perk-randomizer) | Perk randomizer for Dead by Daylight, data updates itself with GitHub Actions |
| [roflo-pinterest](https://github.com/flexeykinDev/roflo-pinterest) | Small Python tray app, packaged as an .exe |
| [lumen](https://github.com/flexeykinDev/lumen) | Music widget for the Windows 11 taskbar, in Rust |
| [Vortex-Hub](https://github.com/flexeykinDev/Vortex-Hub) | My personal site |

---

Ukrainian and Russian are my native languages, English is B2, and I'm learning Polish (A2).
