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

## Quick stats

<!-- Replace `USERNAME` with your GitHub username in the URLs below -->

![GitHub stats](https://github-readme-stats.vercel.app/api?username=USERNAME\&show_icons=true\&count_private=true\&theme=radical)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME\&layout=compact\&theme=radical)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=USERNAME\&theme=dark\&date_format=%5BY%5D-%5Bm%5D-%5Bd%5D)

*(If you want the more advanced / prettier style like `lowlighter/metrics`, see the Setup section below.)*

---

## Areas of focus

| Domain                     | Tools / Techniques                                            |
| -------------------------- | ------------------------------------------------------------- |
| Web Application Pentesting | Burp Suite, OWASP ZAP, sqlmap, wfuzz, Burp Extender plugins   |
| Network & Infrastructure   | Nmap, Netcat, Metasploit, enum4linux, ldapsearch              |
| Linux Privilege Escalation | LinPEAS, GTFOBins, sudoers audits, kernel-exploit research    |
| Exploit Dev & Reverse      | pwntools, radare2, GDB, Binary Ninja / Ghidra                 |
| Post-Exploitation          | BloodHound, Mimikatz (lab-only), PowerShell Empire (learning) |

---

## Recent projects / writeups



*(Add links to these repos or directories once you push them.)*

---

## Resources / Learning plan

* **Daily**: At least one THM/HTB challenge or lab box for OSCP
* **Weekly**: 1 full PWK lab objective — document the process in a writeup.
* **Monthly**: One medium writeup published to README / blog.

---


## Example GitHub Actions (auto-update) — quick idea

If you're using a metrics generator that needs a GitHub Action, create `.github/workflows/update-metrics.yml` with a workflow that runs once per day and updates generated images or the README (see the metrics repo for exact Action usage). Example skeleton:

```yaml
name: GOWTHAMAN GS
on:
  schedule:
    - cron: '0 7 * * *' # every day at 07:00 UTC
  workflow_dispatch: {}

jobs:
  update:
    runs-on: Kali
    steps:
      - uses: actions/checkout@v4
      - name: Run metrics generator
        run: |
          # If using a packaged script / generator, run it here
          echo "Replace with exact command from lowlighter/metrics README"
      - name: Commit changes
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "github-actions[bot]@users.noreply.github.com"
          git add README.md
          git commit -m "chore: update metrics" || echo "No changes"
          git push
```

> ⚠️ **Important:** Replace the `Run metrics generator` step with the real command or Action from the metrics repo you choose.

---

## Contact

* Email: `your.email@example.com` *(or remove if you prefer privacy)*
* Portfolio / Blog: `https://your-site.example.com`

---


