# MITRE ATT&CK Training Module for Forensic Analysts

A hands-on, modular training portal built for DFIR (Digital Forensics & Incident Response) professionals, law-enforcement analysts, SOC teams, and cybersecurity students. This site guides you through the MITRE ATT&CK framework—covering theory, practical labs, reporting, and final evaluations (quizzes & CTF).

> **Author:** Kopal Chaturvedi  
> M.Sc. DFIS Student @ NFSU Delhi  
> **Minor Project • All Rights Reserved © 2025**  

---

## 🔍 Live Demo  
https://kopakop68.github.io/mitre-module/
---

## 🚀 Features

- **14 In-Depth Modules**: From foundational concepts to advanced cloud, ICS/OT, AI/ML, and deception engineering.  
- **Theory → Lab → Report → Evaluation**: Each lesson combines conceptual write-ups, practical exercises in preconfigured VMs or CTF-style challenges, analyst-style report templates, and end-of-module quizzes.  
- **Navigator & SIEM Integration**: JSON layer examples, Sigma→YARA-L pipelines, Splunk & Elastic dashboards, Grafana heat-maps.  
- **Red/Blue/Purple Team Labs**: Atomic Red Team, Caldera, TPOT honeynets, Shield deception scenarios.  
- **Community & Automations**: STIX/TAXII workflows, CAR analytics, GitHub Actions to auto-update ATT&CK data.  
- **Mobile-First & Dark Mode**: Responsive design with automatic theme detection.

---

## 📚 Curriculum at a Glance

| Module | Title                                        |
|--------|----------------------------------------------|
| 1      | Foundations of MITRE ATT&CK                  |
| 2      | Core Terminology & Framework                 |
| 3      | Forensic Evidence Mapping                    |
| 4      | Initial Access & Execution                   |
| 5      | Persistence & Privilege Escalation           |
| 6      | Defense Evasion & Credential Access          |
| 7      | Discovery & Lateral Movement                 |
| 8      | Collection, Exfiltration & Impact            |
| 9      | Threat Intelligence & Adversary Profiles     |
| 10     | Detection Engineering & CAR                  |
| 11     | Adversary Emulation & Red Teaming            |
| 12     | Security Control Mapping & Risk              |
| 13     | Tools & Automation Frameworks                |
| 14     | Advanced & Emerging Topics                   |

---

## 🛠️ Tech Stack

| Technology             | Role                                                              |
|------------------------|-------------------------------------------------------------------|
| Jekyll + Minimal Mistakes | Static-site generator & theme                                   |
| GitHub Pages           | Hosting & CI/CD                                                   |
| Markdown/YAML          | Content authoring & configuration                                 |
| Mermaid, JSON          | Interactive diagrams & ATT&CK Navigator layers                    |
| Sigma, YARA-L, CAR     | Detection rule development & analytics pipelines                  |
| Splunk, Elastic, Grafana | SIEM dashboards & visualization                                |
| Atomic Red Team, Caldera, TPOT | Red/Blue/Purple team labs & honeynets                    |

---

## 📂 Repository Structure

```
/
├── 404.html                   # Custom 404 (Liquid-parsed)
├── README.md                  # Project overview & roadmap
├── _config.yml                # Site config & theme settings
├── _data/                     # Global YAML/JSON data files
├── _layouts/                  # Jekyll layouts (splash, post, single, cardpage)
├── _includes/                 # Shared header, footer, head_custom
├── _pages/                    # About, Contact, Privacy, etc.
├── _posts/                    # Module lessons & blog posts
├── assets/
│   ├── css/style.css          # Custom theme overrides
│   └── images/                # Logos, banners, icons
└── modules/                   # (Optional) pre-built module folders
```

---

## 🛫 Getting Started

1. **Clone Repo**  
   ```bash
   git clone https://kopakop68.github.io/mitre-module/.git
   cd mitre-module
   ```

2. **Install Dependencies**  
   ```bash
   bundle install
   ```

3. **Serve Locally**  
   ```bash
   bundle exec jekyll serve --livereload
   ```  
   Open `http://127.0.0.1:4000/mitre-module/`.

4. **Build**  
   ```bash
   bundle exec jekyll build
   ```  
   Generated site in `_site/`.

5. **Deploy**  
   Push to `main`; GitHub Pages auto-publishes from `gh-pages` or `main` branch.

---

## 🗺️ Project Roadmap

**Phase 1 – Setup** (✅)  
- Jekyll & Minimal Mistakes theme integration  
- GitHub Pages CI build  

**Phase 2 – Design & Layout** (⚙️ In Progress)  
- Homepage splash & module sitemap  
- Responsive navbar, logo, dark/light toggle  

**Phase 3 – Content Generation**  
- Author 14 modules: theory, labs, reports, quizzes  
- Embed diagrams, JSON layers, code samples  

**Phase 4 – Optimization & Launch**  
- SEO meta tags & sitemap.xml  
- Final QA & performance tuning  
- Documentation complete  

---

## ⚠️ Contribution

This project was developed as a Minor Project for academic purposes.  
_Contributions are not open to the public._  

If you’re an instructor or DFIR team lead interested in reusing or adapting this material, please reach out via the **Contact** page.

---

## 📜 License

All Rights Reserved © 2025  
Designed & authored by Kopal Chaturvedi, M.Sc. DFIS @ NFSU Delhi  

---