<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=300&color=gradient&customColorList=0,2,3&text=Kartikeya%20Hazela&reversal=false&section=header&animation=fadeIn" width="100%"/>

<br/>

<img src="https://img.shields.io/badge/B.Tech-Computer%20Science%20(Cybersecurity)-047857?style=flat-square&labelColor=0d1117" />
<img src="https://img.shields.io/badge/SRM%20Institute%20of%20Science%20%26%20Technology-Class%20of%202027-059669?style=flat-square&labelColor=0d1117" />
<img src="https://img.shields.io/badge/📍-Chennai,%20India-065F46?style=flat-square&labelColor=0d1117" />

<br/><br/>

<a href="https://kartikeyahazela.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-10B981?style=for-the-badge&logo=vercel&logoColor=0d1117&labelColor=0d1117" /></a>
<a href="https://linkedin.com/in/kartikeya-hazela/"><img src="https://img.shields.io/badge/LinkedIn-059669?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" /></a>
<a href="mailto:kartikeya104hazela@gmail.com"><img src="https://img.shields.io/badge/Email-047857?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=KH104&style=flat-square&color=10b981&label=Profile+Views" />
<img src="https://img.shields.io/github/followers/KH104?style=flat-square&color=059669&labelColor=0d1117&label=Followers" />
<img src="https://img.shields.io/github/stars/KH104?style=flat-square&color=047857&labelColor=0d1117&label=Stars" />

</div>

<br/>

---

## ABOUT ME

<img align="right" width="38%" src="https://raw.githubusercontent.com/aritraroy/aritraroy/master/gif3.gif" />

I’m a final-year Cybersecurity Engineering student interested in building secure, scalable software systems at the intersection of cybersecurity, AI, and cloud technologies. I enjoy working on projects ranging from threat intelligence platforms and federated learning for DDoS detection to multi-cloud data pipelines.

I like approaching projects with an engineering mindset focusing on clean architecture, security, performance, and practical usability. I’m always looking for opportunities to learn, build, and solve real-world problems through software.


---

## TECH STACK

**Languages**

<img src="https://skillicons.dev/icons?i=python,java,c,cpp,js,bash&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,js,html,css,streamlit&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,flask,postgres,mysql,sqlite&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,git,github,linux,vscode,postman&theme=dark" />

---

## FEATURED PROJECTS

<details>
<summary><strong> ThreatGuard — Threat Intelligence & IOC Analysis Dashboard</strong></summary>
<br/>

A full-stack threat-intelligence platform that aggregates and correlates Indicators of Compromise (IOCs) from multiple live feeds into a single analyst-facing dashboard.

| Attribute | Detail |
|---|---|
| **Stack** | Streamlit · FastAPI · PostgreSQL · VirusTotal API · AbuseIPDB API · OpenAI API |
| **Scale** | Multi-source IOC ingestion with real-time enrichment |
| **Performance** | Asynchronous API calls for concurrent threat-feed lookups |
| **Security** | API-key isolation, input sanitization, IOC validation before persistence |
| **Impact** | Reduced manual IOC triage effort via automated enrichment and scoring |
| **Repository** | [github.com/KH104](https://github.com/KH104) |

ThreatGuard was built to mirror how a SOC analyst actually works — pulling reputation data from VirusTotal and AbuseIPDB, layering in LLM-assisted summarization via the OpenAI API, and persisting structured threat records in PostgreSQL for historical correlation and reporting.

</details>

<details>
<summary><strong> Agent-Based Portfolio Optimization & Monitoring System</strong></summary>
<br/>
A financial decision-support dashboard that analyzes market data, generates optimal investment allocations based on user risk profiles, and continuously monitors portfolio performance to surface actionable rebalancing recommendations.
  
| Attribute | Detail |
|---|---|
| **Stack** | Python · Streamlit · PyPortfolioOpt · Pandas · yfinance |
| **Scale** | Multi-asset portfolio analysis with live market data ingestion |
| **Performance** | Real-time allocation recalculation as market data and risk inputs change |
| **Security** | Read-only market data access, no external trade execution |
| **Impact** | Automated risk-adjusted portfolio allocation and rebalancing guidance for end users |
| **Repository** | [github.com/KH104](https://github.com/KH104) |

Built as a decision-support tool that pulls live market data via yfinance, runs risk-profile-based allocation optimization through PyPortfolioOpt, and surfaces the results in an interactive Streamlit dashboard that continuously monitors portfolio drift and recommends rebalancing actions.
</details>

<details>
<summary><strong> Multi-Cloud Fraud Detection Pipeline</strong></summary>
<br/>

A cloud-agnostic fraud-detection system with adapters for AWS, GCP, and Azure, ingesting transactional events through a unified FastAPI layer.

| Attribute | Detail |
|---|---|
| **Stack** | FastAPI · AWS SDK · GCP SDK · Azure SDK · Streamlit |
| **Scale** | Unified ingestion across 3 independent cloud providers |
| **Performance** | Rule-based real-time scoring engine with sub-second event evaluation |
| **Security** | Cloud-adapter isolation, least-privilege credential scoping |
| **Impact** | Demonstrated cross-cloud portability for fraud-detection logic without vendor lock-in |
| **Repository** | [github.com/KH104](https://github.com/KH104) |

Built to solve a real enterprise problem — fraud-detection logic that shouldn't be tied to a single cloud vendor. Each cloud adapter normalizes incoming events into a common schema before they hit the shared scoring engine, visualized through a live Streamlit dashboard.

</details>

<details>
<summary><strong> 4-DOF Robotic Arm — ESP32 Controlled</strong></summary>
<br/>

An academic robotics project featuring a 4 degree-of-freedom robotic arm controlled through a WiFi-based web interface.

| Attribute | Detail |
|---|---|
| **Stack** | ESP32 · SG90 Servos · Embedded C · WiFi Web Server |
| **Scale** | 4-axis real-time servo control |
| **Performance** | Low-latency WiFi command dispatch to servo controller |
| **Security** | Local network-scoped control interface |
| **Impact** | Delivered as an academic review project demonstrating embedded systems + IoT control |
| **Repository** | [github.com/KH104](https://github.com/KH104) |

A hands-on embedded-systems build pairing an ESP32 microcontroller with SG90 servos, exposing a lightweight web server so the arm can be operated directly from a browser over WiFi.

</details>

---

## EXPERIENCE

**Intern — Python Automation & Enterprise API Integrations**
**Renault Nissan Technology Business Center**
*Internship*

Worked on backend automation and enterprise-scale API integration within a large automotive technology organization, contributing to internal tooling reliability and process efficiency.

- Built Python automation scripts to streamline internal enterprise workflows
- Integrated and consumed enterprise-grade APIs across internal systems
- Collaborated within a structured enterprise engineering environment on production-adjacent tooling

`Python` `API Integration` `Automation` `Enterprise Systems`

---

## RESEARCH PUBLICATIONS

### EDDoSFL-TGXAI: An Explainable Federated Learning Framework with Deep Reinforcement Learning for Distributed DDoS Detection

<div align="center">

| Attribute | Detail |
|---|---|
| **Type** | Co-authored research paper |
| **Domain** | Federated Learning · Deep Reinforcement Learning · Explainable AI (XAI) · Network Security |
| **Dataset** | CICDDoS2019 |
| **Model Architecture** | Random Forest + PyTorch Multi-Layer Perceptron (MLP) ensemble |
| **Result** | **99.98% detection accuracy** on the CICDDoS2019 benchmark |
| **Privacy Model** | Federated training — raw traffic data never leaves client nodes |
| **Interpretability** | Explainability layer (TGXAI) surfaces feature-level reasoning behind each detection decision |

</div>

**Problem.** Centralized DDoS-detection models require pooling raw network traffic from every client, which creates both a privacy liability and a single point of failure. Most high-accuracy intrusion-detection models are also black boxes, which limits analyst trust and makes post-incident review difficult.

**Approach.** EDDoSFL-TGXAI addresses this with a federated learning architecture where detection models are trained locally on distributed client nodes and only model updates — never raw traffic — are aggregated centrally. A deep reinforcement learning layer adaptively tunes detection thresholds as traffic patterns shift, while an ensemble of a Random Forest classifier and a PyTorch-based MLP jointly score incoming traffic for anomalous DDoS signatures. An explainable AI (XAI) layer sits on top of the ensemble, translating model decisions into feature-level justifications an analyst can audit.

**Result.** Evaluated on the CICDDoS2019 benchmark dataset, the framework achieved 99.98% detection accuracy while preserving data locality across federated nodes and producing interpretable, per-decision explanations — directly addressing the privacy and transparency gaps in conventional centralized DDoS-detection systems.

**Contribution.** Co-designed the federated training pipeline and the Random Forest + MLP ensemble, and contributed to dataset preprocessing, experimental evaluation, and the explainability layer integration.

---

## CERTIFICATIONS


**Microsoft**

![DP-900](https://img.shields.io/badge/Microsoft-DP--900%20Azure%20Data%20Fundamentals-059669?style=for-the-badge&logo=microsoftazure&logoColor=white&labelColor=0d1117)

**GitHub**

![GH-300](https://img.shields.io/badge/GitHub-Copilot%20GH--300%20Certified-047857?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)

**ISC2**

![ISC2 CC](https://img.shields.io/badge/ISC2-Certified%20in%20Cybersecurity%20(CC)-065F46?style=for-the-badge&logo=isc2&logoColor=white&labelColor=0d1117)
**(On-Going)**


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:111827,100:0d1117&height=150&section=footer" width="100%"/>

</div>
