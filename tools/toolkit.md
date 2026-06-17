# 🧰 My Offensive Security Toolkit

> Tools don't make the pentester — but knowing the right tool for the right phase makes you fast and precise.
> Here's the arsenal I rely on, organized by purpose. All are industry-standard, open or widely available, and used **only in authorized contexts.**

---

## 🐧 Foundation

| Tool | Role |
|---|---|
| **Kali Linux** | My primary offensive workstation — comes pre-loaded with most of the below |
| **A note-taking system** (e.g. Obsidian, CherryTree) | Where everything gets documented as I work — non-negotiable |
| **A lab environment** (VMware / VirtualBox / GNS3) | Safe, legal practice ground to sharpen skills |

---

## 🔍 Reconnaissance & Enumeration

| Tool | What I use it for |
|---|---|
| **Nmap** | Host discovery, port scanning, service/version detection — the backbone of recon |
| **Shodan** | Understanding exposed internet-facing assets (great for IoT/OT awareness) |
| **Whois / DNS tools** | Mapping domains, records, and ownership |
| **Enumeration scripts** | Service-specific deep-dives once Nmap reveals what's listening |

> **Tip:** I never run a single broad scan and walk away. I scan, read, then scan deeper on what's interesting. Recon is iterative.

---

## 🌐 Web Application Testing

| Tool | What I use it for |
|---|---|
| **Burp Suite** | The core of web testing — intercepting, analyzing, and manipulating requests |
| **Directory/content discovery tools** | Finding hidden endpoints and forgotten files |
| **Manual testing** | The most underrated "tool" — understanding the app's logic beats any scanner |

---

## 🪟 Active Directory & Internal Networks

A huge focus of my CPENT preparation. AD is where many real-world compromises happen.

- Understanding **authentication flows** and where they break
- **Privilege escalation** paths and how misconfigurations create them
- **Lateral movement** concepts and how to detect/prevent them

> I treat AD not as "a bunch of attacks to memorize" but as a **system to understand** — once you get how it's *supposed* to work, the weaknesses reveal themselves.

---

## ⚡ Exploitation & Post-Exploitation

| Tool | Role |
|---|---|
| **Metasploit Framework** | Validating known vulnerabilities in a controlled, documented way |
| **Manual exploitation** | When precision matters more than automation |
| **Shell stabilization techniques** | Turning a fragile foothold into a workable session |

> **Mindset:** automation finds the door; understanding walks you through it. I always know *why* something worked, not just *that* it worked.

---

## 🛠️ Practice Platforms (where the real learning happens)

The single biggest factor in my preparation wasn't reading — it was **doing**, repeatedly.

- **TryHackMe** — structured, progressive, great for building reflexes (I reached the global Top 6%)
- **Personal labs** — building and breaking my own environments (GNS3, VMs)
- **Capture The Flag (CTF)** events — pressure, creativity, and speed (3rd place, ANEMONE CTF 2025)

---

## 💡 The Honest Truth About Tools

You could memorize this entire list and still fail a real engagement. What matters is:

1. **Knowing which phase you're in** and which tool serves it.
2. **Understanding the output**, not just running the command.
3. **Documenting** what you find as you find it.

The tools are the easy part. The thinking is the job.

---

*Part of [Road to CPENT](../README.md) — Coach John, D-CORP Academy*
