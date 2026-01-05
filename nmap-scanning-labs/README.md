# 🔍 TryHackMe – Nmap Lab Write-Up

**Date Completed:** 4 January 2026  
**Platform:** TryHackMe  
**Room:** [Nmap](https://tryhackme.com/room/nmap)  
**Focus:** Port scanning, service enumeration, TCP scan types, NSE scripts, and practical assessment

---

## 🧠 Overview

This was my first deep dive into `nmap` — one of the most widely used tools in cybersecurity for network discovery and enumeration.

The TryHackMe room covered everything from basic scans to more advanced topics like SYN vs TCP Connect scans, using NSE scripts, and handling output in different formats. It ended with a hands-on practical section that tested all the skills built up throughout the lab.

---

## 📸 Screenshots Included

- THM room introduction
- Nmap switches reference guide
- TCP Connect scan
- SYN (stealth) scan
- NSE script for anonymous FTP access
- Searching for NSE scripts
- Final practical assessment scans (Tasks 12–13)

All images are stored in the `/screenshots/` folder and referenced throughout this write-up.

---

## 💡 What I Learned

Throughout this room, I became confident with:

- Using `nmap` flags like `-sS`, `-sT`, `-sV`, `-A`, and `--script`
- The difference between TCP Connect and SYN scans
- How to use the Nmap Scripting Engine (NSE) to detect misconfigurations
- Saving scan output in multiple formats using `-oA`
- Approaching enumeration logically to uncover services and vulnerabilities

---

## 🧱 Challenges Faced

I'll be honest — I found **Tasks 12 and 13**, the practical assessment, quite tough. These tasks pushed me to actually *think* instead of just following along.

I had to rely on my understanding of everything I’d learned — not just the commands, but what output meant, how to spot unusual ports, and how to link information together. I made mistakes, misread a few results, and got stuck more than once. But I stuck with it, re-ran scans, re-read my notes, and eventually got through it.

That part alone made the whole lab worth doing — it felt like a real-world scenario, and finishing it gave me a proper confidence boost.

---

## 🔭 What’s Next

This lab was just the beginning. I plan on working through more Nmap-based rooms — especially ones that dive deeper into evasive scans, firewall bypass techniques, and NSE scripting.

Alongside that, I’ll be starting the **Wireshark rooms next** to build my skills around packet analysis, protocol dissection, and understanding traffic patterns — which is key for blue team roles.

---

## 📂 Tools Used

- Nmap v7.80  
- THM AttackBox (Kali-based environment)  
- Linux terminal  
- NSE Script library

---

## ✅ Final Thoughts

This was a solid introduction to Nmap, but more importantly, a reminder that pushing through friction is where the real learning happens. I’m proud of this one — not because it was easy, but because I finished it properly, documented it, and actually understood what I was doing.