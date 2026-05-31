# CyberLAB â€” Cyber Attack Simulation Platform

> **ALMAAREEFA University â€” Graduation Project 2024-2025**
> Department of Computer Science and Information Systems
> Supervisor: DR. ISMAIL MOHAMMED KESHTA

---

## ðŸ›¡ï¸ About

CyberLAB is a professional **interactive cybersecurity simulation platform** designed for educational purposes. It allows students and researchers to learn about cyber attacks and defenses in a completely safe, isolated virtual environment.

## ðŸš€ Live Demo

ðŸŒ **[Open CyberLAB](https://talalf1.github.io/Cyber-attack-)**

### ðŸ” Demo Login
| Field | Value |
|-------|-------|
| Email | `admin@cyberlab.com` |
| Password | `password123` |

---

## âœ¨ Features

### ðŸ“Š Real-Time Dashboard
- Live attack feed with simulated global threats
- System status gauges (CPU, Memory, Network)
- Attack type distribution charts
- Threat intelligence panel

### ðŸŽ“ Learning Center â€” 4 Difficulty Levels
| Level | Arabic | Topics |
|-------|--------|--------|
| ðŸŸ¢ Beginner | Ù…Ø¨ØªØ¯Ø¦ | Cybersecurity basics, Malware, Social Engineering |
| ðŸ”µ Intermediate | Ù…ØªÙˆØ³Ø· | Network Scanning, SQL Injection |
| ðŸŸ  Advanced | Ù‚ÙˆÙŠ | Metasploit Framework, Exploitation |
| ðŸ”´ Expert | Ø®Ø¨ÙŠØ± | APT Lifecycle, Nation-State Tactics |

Each module includes:
- ðŸ“– **Theory** â€” Concept explanation
- ðŸ’» **Demo** â€” Live terminal simulation
- ðŸ›¡ï¸ **Defense** â€” How to protect against the attack
- ðŸ§  **Quiz** â€” Test your knowledge (+XP)

### ðŸ§ª Interactive Lab
Type **real commands** and see live attack simulations:
```
nmap -sV 192.168.1.1          # Port scan
hping3 -S --flood 192.168.1.1 # DDoS
sqlmap -u http://target/login  # SQL Injection
hydra -l admin -P rockyou.txt  # Brute Force
msfconsole                     # Metasploit
arpspoof -i eth0               # MITM
python3 ransomware.py          # Ransomware
```

Toggle 6 defense systems to block attacks:
ðŸ”¥ Firewall | ðŸ•µï¸ IDS/IPS | ðŸ§± WAF | ðŸ” MFA | ðŸ¯ Honeypot | ðŸ”’ DLP

### ðŸ“ˆ Analytics
- Weekly attack volume charts
- Attack vs Defense radar chart
- Severity distribution
- Attack frequency heatmap
- Top attack origins by country
- Top exploited CVEs

---

## ðŸ› ï¸ Tech Stack

- **HTML5** â€” Semantic structure
- **CSS3** â€” Custom design system, animations, glassmorphism
- **Vanilla JavaScript** â€” No frameworks, pure JS modules
- **Chart.js** â€” Data visualization
- **Canvas API** â€” Attack visualization animations

---

## ðŸ“ Project Structure

```
CyberLAB/
â”œâ”€â”€ index.html          # Login / Register
â”œâ”€â”€ dashboard.html      # Live threat dashboard
â”œâ”€â”€ learn.html          # Learning center
â”œâ”€â”€ lab.html            # Interactive attack lab
â”œâ”€â”€ analytics.html      # Analytics & reports
â”œâ”€â”€ profile.html        # User profile & XP
â”œâ”€â”€ css/
â”‚   â”œâ”€â”€ main.css        # Global design system
â”‚   â”œâ”€â”€ auth.css        # Authentication styles
â”‚   â”œâ”€â”€ dashboard.css   # Dashboard styles
â”‚   â”œâ”€â”€ learn.css       # Learning center styles
â”‚   â””â”€â”€ lab.css         # Lab styles
â””â”€â”€ js/
    â”œâ”€â”€ utils.js          # Shared utilities
    â”œâ”€â”€ app.js            # Core auth & navigation
    â”œâ”€â”€ dashboard.js      # Live simulation engine
    â”œâ”€â”€ learn.js          # Learning modules & quiz
    â”œâ”€â”€ lab.js            # Lab visualization
    â””â”€â”€ interactive-lab.js # Interactive terminal
```

---

## ðŸŽ® How to Run Locally

```bash
# Using Node.js serve
npx serve . --listen 3000

# OR using Python
python -m http.server 3000
```

Then open: `http://localhost:3000`

---

## âš ï¸ Disclaimer

This platform is for **educational purposes only**. All attack simulations are completely virtual and no real systems are affected. The tools demonstrated are shown for cybersecurity education and awareness.

---

*Made with â¤ï¸ for ALMAAREEFA University â€” 2025*
