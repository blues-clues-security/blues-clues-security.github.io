---
layout: single
title: "Projects"
permalink: /projects/
toc: true
---

## Class Instruction

Classes should alternate between fun and cybersecurity concepts in order for students to feel more like a club than a class. The fun courses will still be focused on developing skills using the core concepts taught, but with the focus on developing something the students can use in everyday life (i.e. Minecraft server, deploying websites, etc.).

### Cyber Patriot Units (Cyber Unit)

#### Cyber Unit 1

- Unit 1 - Introduction to CyberPatriot and Cybersecurity 2021.pptx
- Unit 2 - Introduction to Online Safety 2021.pptx
- Unit 3 - Cyber Ethics - with Instructor Notes 2021.pptx

#### Cyber Unit 2

- Unit 4 - Principles of Cybersecurity Edited 2021.pptx
- Unit 5 - Computer Basics and Virtualization 2021.pptx

#### Cyber Unit 3

- Unit 6 - Microsoft Windows Basics 2021.pptx

#### Cyber Unit 4

- Unit 7 - Microsoft Windows Security Tools 2021.pptx

#### Cyber Unit 5

- Unit 8 - Microsoft Windows Security Configuration 2021.pptx
- Unit 9 - Introduction to Linux and Ubuntu 2021.pptx

### Fun Topics

- Minecraft Calculator/Computer
- Minecraft LLM (Long)
  - [ChatGPT in MineCraft](https://www.youtube.com/watch?v=VaeI9YgE1o8)
  - [CraftGPT Github](https://github.com/sammyuri/craftgpt)
  - [Minecraft High-Performance Redstone Server](https://github.com/MCHPR/MCHPRS)
- Build and Host a Website
- Host a Minecraft Server

1) Spin-up a Secure Minecraft Server

    Skills: Linux basics, users/groups, ports, backups, updates, basic threat model
    Materials: 1 spare PC or cloud VM; or local host + LAN
    Tech: Paper/Spigot, ufw, systemd
    2-Hour Plan:

    20m: Threat model (“What could go wrong?” DDoS, griefing, OP abuse).

    30m: Install Paper, create non-root user, run as systemd service.

    20m: Configure server.properties, EULA, whitelist, backups.

    20m: Lock down with ufw, strong RCON/ops discipline.

    30m: Mini-incident drill (bad plugin or rogue OP—how to recover from backup).
    Homework: Add scheduled backups + integrity hash; write a short admin SOP.

2) Redstone Crypto: Build a 4-bit ALU (Minecraft Calculator/Computer)

    Skills: Logic gates, truth tables, documentation discipline
    Materials: Minecraft Java (single player is fine)
    Tech: Redstone, signs for documentation
    2-Hour Plan:

    20m: AND/OR/NOT refresher, half-adder design.

    60m: Build 4-bit adder with carry; test with known inputs.

    20m: Add subtraction via two’s complement lever.

    20m: “Posture review” (signal leaks, timing).
    Homework: Add a 4-bit comparator; short write-up with screenshots.

3) “Shipyard CTF”: Hardening a Mini-Game Server

    Skills: Service enumeration, patching, log review
    Materials: Two laptops (attacker/defender) or two VMs
    Tech: Nmap, fail2ban, auditd
    2-Hour Plan:

    20m: Baseline VM with an intentionally weak service.

    40m: Attackers probe with nmap; defenders monitor logs.

    30m: Defenders harden (update, firewall, disable guest).

    30m: Rematch + debrief.
    Homework: Create a hardening checklist and submit PRs to class repo.

4) “Alien Ciphers”: Break & Make Classic Crypto

    Skills: Frequency analysis, keys/secrets handling ethics
    Materials: Paper pencils + laptop
    Tech: Caesar/Vigenère worksheet + tiny Python helper script
    2-Hour Plan:

    20m: Story hook (distress message intercepted).

    45m: Break Caesar → Vigenère with frequency hints + helper tool.

    25m: Discuss why this fails today; show salted hashing in one script.

    30m: Students encode their own “mission orders” & trade to decode.
    Homework: Implement a substitution solver or write up frequency method.

5) “Holodeck Logs”: Intro to DFIR with Game-Style Artifacts

    Skills: Timeline building, log parsing, IOC thinking
    Materials: Pre-made log bundle (web, auth, app)
    Tech: grep, jq, timesketch-style worksheet
    2-Hour Plan:

    15m: Incident story (compromised holodeck).

    45m: Students answer who/when/how from logs (guided questions).

    30m: Build a basic timeline (timestamps → table).

    30m: Draft a 1-page “exec summary.”
    Homework: Write 3 detections (grep/jq one-liners) for the IOCs found.

6) “Starship Beacon”: Build & Break a Tiny Web App

    Skills: Web basics, input validation, auth/roles
    Materials: Any laptop
    Tech: Flask/FastAPI (Python) or Node/Express, SQLite
    2-Hour Plan:

    20m: Present the “beacon registry” app (list + add beacons).

    40m: Students find issues (no auth on POST, bad input).

    40m: Implement fixes: simple login, CSRF token, server-side validation.

    20m: Write one unit test and a README.
    Homework: Add role-based access (pilot vs. captain).

7) “Base Perimeter”: Wi-Fi Scanner & Simple IDS Light

    Skills: Wireless scanning ethics, basic pattern detection
    Materials: ESP32 or laptop with monitor mode capable NIC
    Tech: MicroPython (ESP32) or Linux airodump-ng dataset
    2-Hour Plan:

    20m: Safety/ethics; only scan your lab/permitted bands.

    50m: Collect beacon/probe frames (or parse provided pcap).

    20m: Heuristics: flag open APs or sudden SSID changes.

    30m: Output a small HTML dashboard.
    Homework: Add an “allowlist” and alert for rogue SSIDs.

8) “Arcade Cabinet” Personal Site (Your idea: Build & Host a Website)

    Skills: Static hosting, HTTPS, change control
    Materials: Student laptop
    Tech: GitHub Pages/Netlify, Hugo or plain HTML/CSS
    2-Hour Plan:

    20m: Clone a minimal template.

    40m: Customize content & nav; add a “Security Tips” section.

    30m: Deploy with HTTPS; add a custom subdomain if available.

    30m: Add a change log page (what changed, why).
    Homework: Add a contact form via serverless function (rate-limited).

9) “Scoreboard API”: Build a Tiny JSON API + Client

    Skills: REST basics, auth, input validation
    Materials: Laptop only
    Tech: FastAPI/Flask + SQLite; or Cloudflare Workers/Denoflare
    2-Hour Plan:

    30m: Create /scores GET/POST; return JSON.

    40m: Add an API key header + server-side input validation.

    20m: Postman or curl tests; log to file with timestamps.

    30m: Create a minimal HTML client page.
    Homework: Add pagination + “admin reset” route guarded by a secret.

10) “Stream Safe”: Privacy & OPSEC for Gamers (Bring your personal PC and let's secure it day)

    Skills: Password managers, MFA, device hardening, Discord safety
    Materials: Laptop + personal accounts (optional)
    Tech: Browser security settings, authenticator app
    2-Hour Plan:

    25m: Threat model for a student gamer.

    40m: Configure strong auth, passkeys/MFA, privacy settings.

    25m: Phishing simulation (identify red flags).

    30m: Create a personal “safety checklist.”
    Homework: Enable auto-updates & audit extensions at home.
