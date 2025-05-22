---
layout: splash
title: "MITRE ATT&CK Training Module for Forensic Analysts"
permalink: /
header:
  overlay_color: "#2b2b2b"
  overlay_filter: "0.3"
  overlay_image: /assets/images/cyber-banner.png
  actions:
    - label: "Start the Modules"
      url: "/modules/"
  caption: "Structured Training for DFIR, SOC, and Cybersecurity Professionals"
excerpt: >
  A modular, hands-on training environment based on the MITRE ATT&CK Framework — developed to enhance adversary detection, forensic investigation, and security control mapping.
intro:
  - excerpt: >
      > “If you know the enemy and know yourself, you need not fear the result of a hundred battles.”
      <br>
      <small>— Sun Tzu, The Art of War</small>
---

{% include feature_row id="intro" type="center" %}

## What is MITRE ATT&CK?

MITRE ATT&CK (Adversarial Tactics, Techniques, and Common Knowledge) is a curated knowledge base that documents the behavior of real-world threat actors. It is used across the cybersecurity industry to model, analyze, and detect adversarial actions throughout the attack lifecycle.

This platform provides a structured training experience that teaches participants how to:
- Understand ATT&CK tactics, techniques, and procedures (TTPs)
- Map forensic artifacts to adversary behavior
- Apply ATT&CK in SOC operations, red teaming, and detection engineering

---

## Training Methodology

Each module in this training program follows a consistent and progressive structure:

- **Theory:** Conceptual foundations with examples
- **Hands-On Labs:** Controlled, scenario-based exercises and simulations
- **Cheatsheets:** Quick-reference terminology, IDs, and correlations
- **Playbooks & Case Studies:** Real-world mappings with procedure-level insight
- **Assessment:** Lab submissions, quizzes, and detection challenges

---

## Curriculum Overview

<section class="curriculum-section section">
  <div class="responsive-table-wrapper">
    <table class="curriculum-table">
      <thead>
        <tr>
          <th>Module</th>
          <th>Focus</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>1. Foundations of MITRE ATT&CK</td><td>Origins, structure, matrix navigation, and core terminology</td></tr>
        <tr><td>2. Core Terminology & Framework Concepts</td><td>Groups, software, data sources, STIX/TAXII, and mapping strategies</td></tr>
        <tr><td>3. Forensic Evidence Mapping</td><td>Correlating artifacts from logs, memory dumps, and registry with ATT&CK techniques</td></tr>
        <tr><td>4. Initial Access & Execution</td><td>Phishing, supply chain compromise, scripting and user execution detection</td></tr>
        <tr><td>5. Persistence & Privilege Escalation</td><td>Startup items, Run keys, token stealing, and unpatched exploit identification</td></tr>
        <tr><td>6. Defense Evasion & Credential Access</td><td>Obfuscation, Mimikatz use, Kerberoasting, memory analysis for credential theft</td></tr>
        <tr><td>7. Discovery & Lateral Movement</td><td>Network service scans, RDP events, lateral pivoting evidence</td></tr>
        <tr><td>8. Collection, Exfiltration & Impact</td><td>Keylogging, data theft, HTTP POST-based exfiltration, ransomware simulation</td></tr>
        <tr><td>9. Threat Intelligence Mapping</td><td>STIX/TAXII feeds, adversary profiles, and threat report mapping</td></tr>
        <tr><td>10. Detection Engineering & CAR</td><td>MITRE CAR pseudocode, Sigma rules, and platform-specific detections</td></tr>
        <tr><td>11. Adversary Emulation & Red Teaming</td><td>Scenario playbooks, purple teaming workflows, and ATT&CK Evaluations</td></tr>
        <tr><td>12. Security Control Mapping</td><td>Control-to-technique coverage using NIST CSF, CIS, ISO frameworks</td></tr>
        <tr><td>13. Tools & Automation</td><td>Using ATT&CK Navigator, Python scripts, STIX integrations, daily updates</td></tr>
        <tr><td>14. Advanced Topics</td><td>Cloud/ICS ATT&CK, deception via MITRE Shield, AI/ML for threat detection</td></tr>
      </tbody>
    </table>
  </div>
</section>


## Getting Started

If you're here for the first time, follow these steps to begin your training:

1. Read the [Foundations of MITRE ATT&CK](/modules/foundations-of-mitre-attack/) module
2. Set up a virtual lab (Kali Linux, REMnux, or Windows VM)
3. Explore the [ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/)
4. Download the [MITRE Basics Cheatsheet](/catoverflow.com)
5. Join the [MITRE ATT&CK Community](https://attack.mitre.org/resources/#slack)

---

## Frequently Asked Questions (FAQ)

**Q: Who is this training designed for?**  
This training is tailored for digital forensic investigators, threat hunters, incident responders, and cybersecurity students seeking structured knowledge based on real-world adversary behavior.

**Q: Do I need technical experience to begin?**  
A basic understanding of cybersecurity concepts and incident response helps, but the modules are structured from foundational to advanced, making them accessible to learners.

**Q: Are the labs safe to run on my system?**  
Labs are designed for use in isolated virtual machines or test environments. Never run live malware samples on production systems.

**Q: Will I get a certificate?**  
While this is currently a self-paced, open-source project, a final CTF-based evaluation and badge system is planned for future releases.