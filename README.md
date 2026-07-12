# CodeAlpha Cybersecurity Internship — Task 2: Phishing Awareness Training

## Project Title
Phishing Awareness Training — Presentation & Interactive Module

## What This Project Is About
This project is a phishing awareness training package built for CodeAlpha's Cybersecurity Internship. It teaches non-technical and technical audiences alike how to recognize phishing emails and fake websites, understand the social engineering tactics attackers rely on, and apply concrete best practices to avoid falling victim. The training is delivered in two formats: a 15-slide presentation and a self-contained interactive web module with a hands-on "Spot the Phish" exercise and a 10-question knowledge-check quiz.

## Why This Matters
Phishing is a form of social engineering — it targets people, not systems. Verizon's 2025 Data Breach Investigations Report found that 68% of breaches involved a human element, most often a phishing email. This training's goal is to reduce that risk by teaching recognizable, memorable patterns rather than abstract rules.

## Project Files
- `Phishing_Awareness_Training.pptx` — 15-slide presentation covering all training content
- `phishing_training.html` — self-contained interactive web module (open directly in any browser, no install needed)
- `README.md` — this file

**Live version:** [Open the interactive module](https://phredreeq.github.io/CodeAlpha_PhishingAwarenessTraining/phishing_training.html) *(hosted via GitHub Pages)*

## What's Covered

### Recognizing Phishing Emails
Seven core red flags: spoofed sender addresses, manufactured urgency, generic greetings, suspicious links, unexpected attachments, requests for sensitive data, and mismatched branding.

### Recognizing Fake Websites
How to read a URL correctly (right-to-left from the first single slash), why HTTPS/the padlock icon is not a trust guarantee, and the "verify independently" habit that defeats nearly every URL-spoofing trick.

### Social Engineering Psychology
Six psychological levers attackers exploit: authority, urgency, fear, trust, curiosity, and reciprocity/greed. Understanding *why* these tactics work builds resistance to attacks a person has never seen before.

### Real-World Case Studies (verified, in presentation)
1. **The $100M+ invoice scam (2013–2015):** Evaldas Rimasauskas impersonated a real Facebook/Google vendor using forged invoices — no malware, no hacking, just a convincing fake business relationship.
2. **The 2011 RSA breach:** A single employee opened a malicious Excel attachment, leading to a breach of RSA's SecurID authentication technology used by thousands of organizations.
3. **Uber's 2022 MFA fatigue attack:** Attackers bombarded a contractor with MFA push notifications, then impersonated IT support to get one approved — bypassing MFA without any malware.

### Best Practices Checklist
Ten actionable habits, from "pause when a message creates urgency" to "verify unusual requests through a second, separate channel."

## Interactive Features (in the HTML module)

**Spot the Phish:** An annotated, realistic phishing email mockup where the user clicks on suspicious elements (sender address, urgency language, generic greeting, credential request, suspicious link, unexpected attachment) and gets a live tracker of red flags found — reinforcing recognition through active practice rather than passive reading.

**10-Question Quiz:** Covers practical judgment calls (reading URLs, responding to unexpected MFA prompts, verifying unusual requests) rather than case-study trivia. Each answer gives immediate feedback with a short explanation, and a final score with a tailored message.

## How to Use
1. Open `phishing_training.html` directly in any modern browser — no installation or server required.
2. Or open `Phishing_Awareness_Training.pptx` in PowerPoint for a presentation format.
3. Work through the sections in order, try the Spot the Phish exercise, then take the quiz.

## MITRE ATT&CK Mapping
- **T1566 — Phishing** (Initial Access): the primary technique this training addresses, covering both email-based and website-based variants.
- **T1598 — Phishing for Information** (Reconnaissance): covered conceptually in the social engineering section, where attackers gather information to make attacks more convincing (spear phishing).

## References
- Verizon 2025 Data Breach Investigations Report
- U.S. Attorney's Office, Southern District of New York — Evaldas Rimasauskas case filings
- RSA / Threatpost / Dark Reading — 2011 RSA SecurID breach reporting
- CISA, Security Boulevard — Uber 2022 breach and MFA fatigue reporting

## Author
Fredrick Agufenwa
GitHub: [Phredreeq](https://github.com/Phredreeq)
LinkedIn: [fredrick-agufenwa-09bab9165](https://linkedin.com/in/fredrick-agufenwa-09bab9165)
