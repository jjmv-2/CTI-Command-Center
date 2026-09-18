# THE WATCHER

> **Nothing hides forever.**

THE WATCHER is a threat intelligence prioritization platform designed to help
analysts identify which vulnerabilities and threats matter most to their
environment.

Rather than simply displaying threat intelligence feeds, THE WATCHER
correlates vulnerability and threat data against technologies configured
in an organization's environment to prioritize relevant intelligence.

## 🎯 Why I Built It

Security teams receive large amounts of vulnerability and threat data,
but not every threat carries the same level of risk for every organization.

I built THE WATCHER to explore a core CTI problem:

**How can threat intelligence be made more relevant and actionable for
a specific environment?**

The platform combines public threat intelligence with environment context
to help analysts quickly identify vulnerabilities that deserve investigation.

## 🔎 Key Features

### Threat Intelligence Dashboard
Provides an overview of current vulnerability and threat intelligence,
including recent activity and prioritized findings.

### CISA KEV Integration
Ingests the CISA Known Exploited Vulnerabilities catalog to identify
vulnerabilities confirmed to be exploited in the wild.

### Environment Correlation
Users configure technologies present in their environment.

THE WATCHER compares vulnerability information against those technologies
to identify relevant vendor and product matches.

### Priority Intelligence
Environment-relevant vulnerabilities are prioritized using factors such as:

- Known exploitation
- Environment match
- Vendor match
- Product match
- Known ransomware activity

### WATCHER Assessment
Each prioritized vulnerability receives an analyst-friendly explanation
showing why the vulnerability matters and which factors contributed to
its prioritization.

### Vulnerability Enrichment
Vulnerability records can be enriched with additional CVE information,
including CVSS data and technical details.

### Threat Intelligence Sources
THE WATCHER currently works with intelligence from sources including:

- CISA Known Exploited Vulnerabilities
- MITRE ATT&CK
- NVD
- ThreatFox

## 🧠 Example Analysis

A vulnerability affecting Microsoft Windows may receive increased priority
when:

1. CISA confirms active exploitation.
2. Windows exists in the configured environment.
3. The vendor matches an environment technology.
4. The affected product directly matches an environment technology.
5. CISA associates the vulnerability with ransomware activity.

THE WATCHER explains these factors rather than displaying a score without
context.

## 📸 Screenshots

### Intelligence Dashboard

[Add dashboard screenshot here]

### WATCHER Assessment

[Add vulnerability investigation screenshot here]

### Environment Correlation

[Add environment page screenshot here]

## 🛠️ Technology

**Frontend**
- React
- TypeScript
- Vite
- Tailwind CSS

**Backend**
- Node.js
- Express

**Threat Intelligence / Data**
- CISA KEV
- MITRE ATT&CK
- NVD
- ThreatFox

## 🏗️ Architecture

Threat Intelligence Sources
        ↓
Data Ingestion
        ↓
Normalization / Enrichment
        ↓
Environment Correlation
        ↓
Prioritization Engine
        ↓
WATCHER Assessment
        ↓
Analyst Investigation

## 🚧 Current Development

THE WATCHER is an ongoing cybersecurity research and development project.

Areas I'm continuing to explore include:

- Improved threat correlation
- Malware intelligence
- IOC enrichment
- ATT&CK mapping
- Asset/environment integrations
- Analyst workflows
- Explainable prioritization

## 🎓 What I'm Learning

I built this project to strengthen practical skills in:

- Cyber Threat Intelligence
- Vulnerability intelligence
- Threat data enrichment
- Environment-based prioritization
- API integration
- Intelligence analysis
- React / TypeScript development

## ⚠️ Disclaimer

THE WATCHER is an independent educational and research project.

Threat intelligence data may be incomplete, delayed, or inaccurate.
Prioritization results should support analyst investigation and should
not be treated as a replacement for professional security assessment.

## 👤 Author

**Jeffrey Vinson Jr.**

Cybersecurity | Cyber Threat Intelligence | U.S. Army Reserve Signal Officer

LinkedIn: [Your LinkedIn]
