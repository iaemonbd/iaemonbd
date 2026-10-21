<!--
  EMON | Cybersecurity & Automation Portfolio
  Replace placeholders and remove tools you have not used yet.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:001a08,50:003b16,100:00ff41&text=EMON%20%7C%20iaemonbd&fontColor=00FF41&fontSize=42&fontAlignY=38&desc=SOC%20ANALYST%20L1%20%7C%20BLUE%20TEAM%20%7C%20AUTOMATION&descAlignY=59&descSize=14" width="100%" alt="Green Matrix-style header banner"/>

<a href="https://iaemon.me"><img src="https://img.shields.io/badge/Website-iaemon.me-00ff41?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Website"/></a>
<a href="https://www.linkedin.com/in/iae"><img src="https://img.shields.io/badge/LinkedIn-Connect-00ff41?style=for-the-badge&logo=linkedin&logoColor=black" alt="LinkedIn"/></a>
<a href="https://github.com/iaemonbd"><img src="https://img.shields.io/badge/GitHub-iaemonbd-00ff41?style=for-the-badge&logo=github&logoColor=black" alt="GitHub"/></a>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2500&pause=700&color=00FF41&center=true&vCenter=true&width=720&lines=%24+whoami;EMON+%7C+Cybersecurity+Learner;SOC+Analyst+L1+%7C+Blue+Team+Focus;Security+%2B+Automation+%2B+Open+Source" alt="Animated terminal introduction"/>

`DEFEND • DETECT • INVESTIGATE • AUTOMATE`

</div>

---

## `$ whoami`

Hi, I'm **EMON** (`@iaemonbd`), a cybersecurity learner building practical skills for a **SOC Analyst L1 / Blue Team** role. I enjoy understanding how systems work, investigating security signals, automating repeatable tasks, and documenting what I learn.

- 🛡️ **Primary focus:** SOC operations, alert triage, log analysis, and defensive security
- 🌐 **Foundations:** Networking, Linux, and Windows fundamentals
- 🐳 **Infrastructure:** Docker and reproducible lab environments
- ⚙️ **Automation:** Python/Bash scripting and n8n workflows
- 🧠 **AI/LLM:** Learning LLM fine-tuning concepts and security-focused AI workflows
- 🔎 **Security testing:** Vulnerability assessment in authorized labs and systems only

> My goal is to turn learning into reproducible labs, clear investigation notes, and useful open-source projects. The projects below are works in progress unless a repository contains completed documentation and evidence.

## `$ cat focus.txt`

| Track | What I'm building toward |
|---|---|
| SOC / Blue Team | Alert triage, event logs, SIEM searches, incident notes |
| Vulnerability Assessment | Scope definition, safe scanning, validation, remediation reports |
| Linux & Scripting | Log parsing, system checks, small defensive automation tools |
| Docker | Containerized labs, secure configurations, repeatable deployments |
| n8n Automation | Workflow-based enrichment, notifications, and case hand-offs |
| LLM Fine-Tuning | Dataset preparation, evaluation, and small experimental models |

## `$ ls -la ./featured-labs`

> Create each repository, add real results, then replace these planned links with the actual URLs.

### 🛡️ SOC Home Lab & Alert Triage
A documented home lab for collecting and investigating security events.

**Planned contents**
- Lab diagram, setup instructions, and test-data sources
- Windows/Linux event examples and alert-triage workflow
- Investigation timeline, evidence, findings, and recommended response
- Screenshots with sensitive details removed

**Suggested stack:** Wazuh, Windows Event Logs, Linux authentication logs, Docker (where suitable)

**Repository:** `soc-home-lab` *(planned — link this after creating it)*

### 🔎 Vulnerability Assessment Lab
A safe, authorized practice environment for learning the assessment lifecycle.

**Planned contents**
- Written scope and rules of engagement
- Lab setup and tool configuration
- Findings with severity rationale, evidence, impact, and remediation
- Retest notes showing whether fixes worked

**Suggested stack:** OWASP Juice Shop or another intentionally vulnerable local lab, OWASP ZAP, Nmap

**Safety:** Scan only systems you own or have explicit permission to test.

**Repository:** `vulnerability-assessment-lab` *(planned — link this after creating it)*

### 🐧 Linux Log Analyzer
A small command-line utility to parse sample Linux authentication logs and summarize repeated failures.

**Planned contents**
- Python or Bash source code with comments
- Sample, sanitized input and sample output
- Usage examples, edge cases, and tests
- Clear limitations: repeated failures are a signal to investigate, not proof of compromise

**Repository:** `linux-log-analyzer` *(planned — link this after creating it)*

### 🐳 Dockerized Security Lab
A reproducible local environment for running selected learning services safely.

**Planned contents**
- `compose.yaml`, `.env.example`, and setup/cleanup steps
- Non-root containers where practical, minimal exposed ports, and health checks
- Secret-handling guidance and dependency notes
- Screenshots and troubleshooting notes

**Repository:** `docker-security-lab` *(planned — link this after creating it)*

### ⚙️ n8n Security Alert Workflow
An automation demo that routes **synthetic or approved lab alerts** through enrichment and notification steps.

**Planned contents**
- Exported workflow JSON with credentials removed
- Example input/output payloads and failure handling
- Deduplication, human review, and audit trail
- Setup guide and a short demo

**Suggested workflow:** Sample alert → validate fields → enrich with approved data sources → route for analyst review → create a notification.

**Repository:** `n8n-security-workflows` *(planned — link this after creating it)*

### 🧠 LLM Fine-Tuning Experiment
A small, documented experiment exploring how to adapt an open model to a narrow, safe task such as classifying synthetic security-ticket summaries.

**Planned contents**
- Dataset provenance, licensing, redaction, and train/validation split
- Baseline vs. fine-tuned evaluation with a reproducible metric
- Model card, limitations, and examples of failure cases
- Compute requirements and reproducibility notes

**Repository:** `llm-security-experiment` *(planned — link this after creating it)*

## `$ cat toolkit.txt`

**Core foundations**
- Networking: TCP/IP, DNS, HTTP/HTTPS
- Operating systems: Linux and Windows fundamentals
- Scripting: Python and Bash *(show only what you can demonstrate)*

**Tools I'm exploring / using in labs**
- Defensive security: Wazuh, Windows Event Viewer, Sysmon
- Network analysis: Wireshark, Nmap
- Vulnerability assessment: OWASP ZAP, intentionally vulnerable lab targets
- Containers: Docker, Docker Compose
- Workflow automation: n8n
- AI/LLM: Python-based experiments and model evaluation

> **Accuracy note:** “Exploring” does not mean professional proficiency. Move a tool into your skills section only when you can explain what you used it for and demonstrate a project.

## `$ cat learning-roadmap.md`

- [ ] Collect and explain Windows and Linux security events
- [ ] Write a concise alert-triage and escalation report
- [ ] Build a documented SIEM/home-lab workflow
- [ ] Create a tested log-analysis script
- [ ] Containerize a small lab with safe defaults
- [ ] Build an n8n workflow with error handling and human review
- [ ] Document an authorized vulnerability assessment and remediation
- [ ] Run a reproducible LLM experiment and report evaluation results

## `$ cat responsible-disclosure.txt`

I practice security testing only in environments I own or have explicit authorization to assess. I do not publish credentials, private logs, personal data, or exploit instructions targeting real systems. My aim is to improve detection, remediation, and secure operations.

## `$ connect --with emon`

- 🌐 Website: [iaemon.me](https://iaemon.me)
- 💼 LinkedIn: [linkedin.com/in/iae](https://www.linkedin.com/in/iae)
- 🧑‍💻 GitHub: [github.com/iaemonbd](https://github.com/iaemonbd)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:00ff41,50:003b16,100:001a08" width="100%" alt="Green footer banner"/>

`Stay curious. Verify evidence. Document everything.`

</div>
