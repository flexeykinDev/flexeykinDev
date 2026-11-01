<img src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:0d1b2a,100:1b4965&text=Oleksii%20Yelenskyi&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=Junior%20SOC%20Analyst%20%C2%B7%20Krak%C3%B3w&descAlignY=60&descSize=16" width="100%" alt="Oleksii Yelenskyi, Junior SOC Analyst, Kraków">

<div align="center">

<a href="https://github.com/flexeykinDev/soc-detection-lab"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3500&pause=900&color=3A86FF&center=true&vCenter=true&width=520&lines=Writing+Sigma+rules+for+Windows;Testing+them+on+real+attack+logs;Looking+for+a+SOC+or+IT+support+role" alt="Writing Sigma rules for Windows. Testing them on real attack logs. Looking for a SOC or IT support role."></a>

<a href="mailto:alekselenskiy.twink@gmail.com"><img src="https://img.shields.io/badge/Email-alekselenskiy.twink%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<img src="https://img.shields.io/badge/Krak%C3%B3w%20or%20remote-1b4965?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Kraków or remote">

</div>

I studied cybersecurity and now I mostly work on detection: writing Sigma rules for Windows and checking them against real attack logs to see what they actually catch and what they miss.

Looking for my first job in a SOC or IT support team, in Kraków or remote. I have the right to work in Poland.

---

### soc-detection-lab

[github.com/flexeykinDev/soc-detection-lab](https://github.com/flexeykinDev/soc-detection-lab)

Three Sigma rules tested on 278 real EVTX attack captures from a public dataset. They fired 17 times across 15 captures, including mimikatz, Meterpreter and MalSeclogon.

A few things I learned along the way:

- The LSASS rule looks at process access masks instead of file names, so it still works when a tool is renamed.
- I converted the rules to Splunk SPL and to KQL for Defender XDR. One of them didn't convert to KQL, and the README explains why.
- My first PowerShell rule had false positives on the remoting host. I narrowed it down and kept the real attacks.

<p>
<img src="https://img.shields.io/badge/Sigma-1b4965?style=flat-square" alt="Sigma"> <img src="https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=flat-square" alt="MITRE ATT&CK"> <img src="https://img.shields.io/badge/Sysmon-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Sysmon"> <img src="https://img.shields.io/badge/KQL_(Defender_XDR)-0078D4?style=flat-square" alt="KQL"> <img src="https://img.shields.io/badge/Splunk_SPL-000000?style=flat-square&logo=splunk&logoColor=white" alt="Splunk SPL"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
</p>

---

### What I work with

**Security and IT**

<img src="https://skillicons.dev/icons?i=windows,linux,powershell,bash,py,git,githubactions&perline=7" alt="Windows, Linux, PowerShell, Bash, Python, Git, GitHub Actions">

<p>
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark"> <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=gnometerminal&logoColor=white" alt="Nmap"> <img src="https://img.shields.io/badge/Sysmon-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Sysmon"> <img src="https://img.shields.io/badge/Event_Logs-555?style=for-the-badge" alt="Windows Event Logs">
</p>

**Used in my projects**

<img src="https://skillicons.dev/icons?i=rust,tauri,svelte,ts,js,nextjs,react,tailwind,nodejs,d3,cpp,cmake,java,gradle,cs,dotnet,html,css&perline=9" alt="Rust, Tauri, Svelte, TypeScript, JavaScript, Next.js, React, Tailwind, Node.js, D3, C++, CMake, Java, Gradle, C#, .NET, HTML, CSS">

---

### Projects

Side projects I built with AI help. I made the decisions, tested and fixed them, and got them working.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/flexeykinDev/lumen"><b>lumen</b></a><br>
Now-playing capsule for the Windows 11 taskbar. Works with any player, per-app volume, synced lyrics and Discord status. One portable exe.<br><br>
<img src="https://skillicons.dev/icons?i=rust,tauri,svelte,ts" height="28" alt="Rust, Tauri, Svelte, TypeScript">
</td>
<td width="50%" valign="top">
<a href="https://github.com/flexeykinDev/ShadowPlay_Patcher"><b>ShadowPlay_Patcher</b></a><br>
Tray app that stops NVIDIA Instant Replay from turning itself off on protected content. Win32 API hooking in C++.<br><br>
<img src="https://skillicons.dev/icons?i=cpp,cmake,windows" height="28" alt="C++, CMake, Windows">
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/flexeykinDev/dbd-perk-randomizer"><b>dbd-perk-randomizer</b></a> · <a href="https://flexeykindev.github.io/dbd-perk-randomizer/">live</a><br>
Perk randomizer and OBS overlay for Dead by Daylight streams. Perk data is scraped from the wiki and updated by GitHub Actions.<br><br>
<img src="https://skillicons.dev/icons?i=nextjs,ts,tailwind,githubactions" height="28" alt="Next.js, TypeScript, Tailwind, GitHub Actions">
</td>
<td width="50%" valign="top">
<a href="https://github.com/flexeykinDev/dota-counter-web"><b>dota-counter-web</b></a> · <a href="https://flexeykindev.github.io/dota-counter-web/">live</a><br>
Interactive map of Dota 2 counter-picks: who beats who, why, and which item shuts them down. Built from 2M+ high-rank games.<br><br>
<img src="https://skillicons.dev/icons?i=js,d3,html,css" height="28" alt="JavaScript, D3, HTML, CSS">
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/flexeykinDev/steam-autolike"><b>steam-autolike</b></a><br>
Firefox extension that likes friends' posts in the Steam feed and leaves one emoticon comment. It stops by itself when Steam's anti-spam limit kicks in.<br><br>
<img src="https://skillicons.dev/icons?i=js,html,css" height="28" alt="JavaScript, HTML, CSS">
</td>
<td width="50%" valign="top">
<a href="https://github.com/flexeykinDev/thaumcraft4-1.20"><b>thaumcraft4-1.20</b></a><br>
Unofficial fan port of the Thaumcraft 4 mod to Minecraft 1.20.1, for Forge and NeoForge.<br><br>
<img src="https://skillicons.dev/icons?i=java,gradle" height="28" alt="Java, Gradle">
</td>
</tr>
</table>

---

### Open source

Merged pull requests to other people's projects.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/KnifeLemon/Filee"><b>Filee</b></a> · <a href="https://github.com/KnifeLemon/Filee/pulls?q=is%3Apr+is%3Amerged+author%3AflexeykinDev">my PRs</a><br>
Offline file converter. I added quick clip trimming and window zoom, and fixed leftover temp folders and half-written files after a failed conversion.<br><br>
<img src="https://skillicons.dev/icons?i=cs,dotnet" height="28" alt="C#, .NET">
</td>
<td width="50%" valign="top">
<a href="https://github.com/Cranch-fur/Cursed-Market"><b>Cursed-Market</b></a> · <a href="https://github.com/Cranch-fur/Cursed-Market/pulls?q=is%3Apr+is%3Amerged+author%3AflexeykinDev">my PRs</a><br>
Windows proxy tool. I made it stop wiping the user's proxy settings on exit, accept only http(s) links from update responses, and warn when traffic isn't going through the proxy.<br><br>
<img src="https://skillicons.dev/icons?i=cs,dotnet,windows" height="28" alt="C#, .NET, Windows">
</td>
</tr>
</table>

---

### GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/0-profile-details.svg">
  <img src="./profile-summary-card-output/github/0-profile-details.svg" width="100%" alt="Contributions">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/3-stats.svg">
  <img src="./profile-summary-card-output/github/3-stats.svg" width="49%" alt="Stats">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/2-most-commit-language.svg">
  <img src="./profile-summary-card-output/github/2-most-commit-language.svg" width="49%" alt="Top languages">
</picture>

---

### Languages

<img src="./assets/languages.svg" width="100%" alt="Languages: Ukrainian native, Russian native, English B2, Polish B1 conversational">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/flexeykinDev/flexeykinDev/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/flexeykinDev/flexeykinDev/output/github-snake.svg" width="100%" alt="Snake eating my contribution graph">
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:1b4965,100:0d1b2a&section=footer" width="100%" alt="">
