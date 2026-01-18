# Hi — I’m `w01f` 👋

> Aspiring pentester | Preparing for **OSCP** | Offensive security & red-team practice

[![Website](https://img.shields.io/badge/portfolio-online-informational)](#)
[![OSCP Goal](https://img.shields.io/badge/OSCP-In%20Progress-yellow)](#)

---

## About me

* 🎯 Goal: Become a professional penetration tester and complete OSCP.
* 🛠️ Current focus: web app pentesting, networks, privilege escalation, and exploit development.
* 📚 Learning plan: PWK labs, HTB (Active), VulnHub, writeups, and daily CTF practice.
* 💬 I blog about writeups and pentest notes in the `notes/` folder of this repo.

---

<div align="center">
  <pre>
  <code style="color: #00ff00;">
   PLEASE INSERT COIN . . .
   
   SCORE: 1337      HIGH SCORE: 9999      LEVEL: ROOT
   
   ┌───────────────────────────────────────────────────────┐
   │  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●  │
   │  ●   ᗧ • • • [THM] ◄─(TryHackMe Logo Target)      ●  │
   │  ●                                                ●  │
   │  ●   GHOSTS: [ Bug ] [ Error ] [ 404 ] [ Lag ]    ●  │
   └───────────────────────────────────────────────────────┘
   
   >> SYSTEM READY.
   >> WELCOME USER: w01f
  </code>
  </pre>
</div>

---

### <div align="center"> ⚡ `w01f@kali:~$ ./whoami` </div>

<div align="center">
  <a href="https://tryhackme.com/p/w01f">
    <img src="https://img.shields.io/badge/TryHackMe-Level%20UP-red?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe">
  </a>
  <a href="https://www.hackthebox.com/">
    <img src="https://img.shields.io/badge/HackTheBox-Operative-green?style=for-the-badge&logo=hackthebox&logoColor=white" alt="HackTheBox">
  </a>
  <a href="https://www.kali.org/">
    <img src="https://img.shields.io/badge/OS-Kali%20Linux-blue?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux">
  </a>
</div>

<br />

```bash
# SYSTEM DIAGNOSTICS 
# ------------------
User        : w01f
Machine     : mad (Laptop)
Role        : Offensive Security Student / Developer
Target      : OSCP Certification & International Ops
Current_Loc : 127.0.0.1 (Chennai, IN)

```

```python
class Profile:
    def __init__(self):
        self.username = "w01f"
        self.languages = ["Python", "Flask", "Bash"]
        self.tools = ["Burp Suite", "Metasploit", "Fortinet", "Wireshark"]
        
    def current_research(self):
        return [
            "AI-Enhanced Memory Forensics",
            "IoT Intrusion Detection (Autoencoders)",
            "Queuing Theory in Mathematics"
        ]

    def status(self):
        return "Compiling knowledge... please wait."

```

---

### <div align="center"> 📡 Mission Log (Projects) </div>

| Protocol | Description | Status |
| --- | --- | --- |
| **Project_QuantifiedSelf** | A personal tracking app built with Flask. | `DEPLOYED` |
| **HMS_Core** | Hospital Management System with secure login handling. | `DEBUGGED` |
| **Forensics_AI** | Researching fileless malware detection using AI. | `IN_PROGRESS` |

---

<div align="center">
<p><i>"There is no patch for human stupidity."</i></p>

<a href="https://www.google.com/search?q=https://linkedin.com/in/mrw01f">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2%3Fstyle%3Dfor-the-badge%26logo%3Dlinkedin%26logoColor%3Dwhite" />
</a>
</div>

```

### Pro Tip: The "Snake" Animation

If you want the **animated** game that eats your contribution squares (which looks very similar to Pac-Man), you need to set up a **GitHub Action**.

1.  In your repository, create a folder structure: `.github/workflows/snake.yml`
2.  Paste this code inside `snake.yml`:

<!-- end list -->

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *" # runs every 12 hours
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          # github user name to read the contribution graph from (**Required**)
          github_user_name: ${{ github.repository_owner }}
          
          # list of files to generate.
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

```
