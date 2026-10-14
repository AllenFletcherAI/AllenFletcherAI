<div align="center">

# Allen Fletcher

**Machine Learning Systems & Enterprise Logistics Data Infrastructure Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/allen-fletcher)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/AllenFletcherAI)
[![Email](https://img.shields.io/badge/Direct-allensimeonfletcher%40gmail.com-blue?style=flat&logo=gmail&logoColor=white)](mailto:allensimeonfletcher@gmail.com)
[![Status: Anabin H+](https://img.shields.io/badge/Academic%20Parity-Anabin%20H%2B%20%7C%20Consecutive%20Master-success?style=flat)]()
[![Location Target: Germany](https://img.shields.io/badge/Target%20Location-Germany%20%7C%20Immediate%20Relocation-blue?style=flat)]()

</div>

---

## ⚡ Executive Focus

Machine Learning Systems Engineer specializing in high-throughput document extraction pipelines, deterministic freight reconciliation services, and decoupled enterprise ERP/TMS integration for European logistics and global supply chain networks. Engineering production-grade pipelines bridging legacy transport infrastructure with autonomous multimodal computer vision and real-time customs compliance engines.

* **Core Competencies:** Multimodal document intelligence, deterministic mathematical validation, low-latency microservice architectures, and zero-disruption enterprise database staging.
* **Production Runtimes:** Containerized FastAPI services, C# / .NET 8 client runtimes, NVIDIA TensorRT, ONNX Runtime, and Microsoft SQL Server 2022 staging buffers.
* **Statutory Status for Germany:** Anabin-verified 5-year Integrated Master's / M.Tech in Computer Science & AI (**H+ / Consecutive Master Equivalence**), fully qualifying for the **EU Blue Card (§ 18g AufenthG)** and the **Accelerated Fast-Track Skilled Worker Procedure (§ 81a AufenthG)** with zero HR friction.

---

## 🛠️ Flagship Production System

### 🚢 [Redline-Gateway // Enterprise Shipping Document Ingestion & Customs Compliance Gateway](https://github.com/AllenFletcherAI/Redline-Gateway)

> **Repository Description:**  
> *Automated shipping document ingestion and customs compliance validation gateway for Red Line Spedition and mw1group.*

* **Live Interactive Application:** [https://redline-gateway.onrender.com](https://redline-gateway.onrender.com)
* **Target Environment:** mw1group / Red Line Intern. Spedition GmbH · C# / ASP.NET · Microsoft SQL Server 2022
* **Architecture:** Decoupled dual-engine architecture combining multimodal vision parsing with strict deterministic mathematical rules for international maritime, air, and road freight documentation.

#### Key Capabilities & Technical Highlights:
* **Automated 3-Way Dossier Reconciliation:** Sub-2-second cross-audit across the core freight triad (Ocean Bill of Lading, Commercial Invoice, and Packing List), matching container identifiers, declared gross/net weights, packages, customs values, and Incoterms.
* **Deterministic Business Rule Engine:** Algorithmic verification of ISO 6346 Modulo-11 container check digits (preventing terminal gate-in rejections), Tara weight variance checks against the German 50 kg tolerance threshold, and automatic Demurrage & Detention risk calculations (€150–€350/day per container).
* **Statutory ADSp 2017 Claim Generation:** Instantly compiles a legally formatted Speditions-Reklamationsmemo preserving carrier recourse rights under § 412 HGB within strict pre-arrival deadlines.
* **Decoupled MS-SQL Staging Pattern:** Eliminates schema migration risk on production ERP databases by streaming validated, ANSI-escaped records directly into isolated staging tables (`[dbo].[myscm_Staging_Shipments]` & `[dbo].[myscm_Reconciliation_Ledger]`).
* **Enterprise .NET 8 / C# Client Library:** Production-grade `RedLineGatewayClient.cs` providing async, zero-copy `HttpClient` streaming for immediate drop-in integration into existing C# / ASP.NET dispatch backends.
* **GoBD & German Compliance Governance:** Cryptographic SHA-256 hash chaining on all ingested records ensuring an immutable, tamper-evident audit trail satisfying German tax & trade regulations (§§ 146, 147 AO / GoBD), with 100% German/EU data sovereignty (Frankfurt am Main) and zero model retention.
* **Stack:** Python 3.11, FastAPI, Google GenAI Multimodal Vision, Microsoft SQL Server (T-SQL), C# / .NET 8, Docker, Tailwind CSS, Render (Frankfurt EU-Central).

---

## 🌐 Freight Logistics & Customs Domain Depth

```text
 ┌────────────────────────────────────────────────────────────────────────────────────────┐
 │                      ENTERPRISE FREIGHT DOMAIN COMPETENCIES                            │
 ├─────────────────────────┬──────────────────────────────────────────────────────────────┤
 │ Freight Modalities      │ Ocean (FCL/LCL, Master/House B/L) · Air (IATA AWB) · Road CMR│
 │ Customs & Regulation    │ German ATLAS 9.1 IT Procedures · HS / Zolltarif · ISO 4217  │
 │ Trade & Legal Rules     │ ICC Incoterms 2020 (CIF, FOB, DAP, DDP) · ADSp 2017 · § 412  │
 │ Compliance & Auditing   │ GoBD (§§ 146, 147 AO) SHA-256 Hash Ledgers · GDPR / DSGVO   │
 │ Target Integration      │ myscm · SAP TM · CargoWise · MS-SQL 2022 · WinSped · AS/400  │
 └─────────────────────────┴──────────────────────────────────────────────────────────────┘
```

---

## ⚙️ Technical Architecture & Core Stack

```text
 ┌────────────────────────────────────────────────────────────────────────────────────────┐
 │                              PRODUCTION SYSTEMS STACK                                  │
 ├─────────────────────────┬──────────────────────────────────────────────────────────────┤
 │ Multimodal Vision & ML  │ Google GenAI Vision · PyTorch · Hugging Face · OpenCV · PyPDF│
 │ Backend & Serving       │ FastAPI · Python 3.11 · C# / .NET 8 · Docker · Redis · Celery│
 │ Databases & Staging     │ Microsoft SQL Server 2022 (T-SQL) · PostgreSQL · SQLite      │
 │ Enterprise Protocols    │ RESTful APIs · Webhooks · Multipart Streaming · JSON Schema  │
 │ Runtime & Acceleration  │ NVIDIA TensorRT · ONNX Runtime · Triton Inference Server     │
 │ Cloud & DevOps          │ Render (Frankfurt EU-Central) · AWS (S3, Lambda) · GitHub CI │
 └─────────────────────────┴──────────────────────────────────────────────────────────────┘
```

---

## 🏛️ Statutory Status & German Work Authorization

* **Academic Degree:** 5-Year Integrated Master of Technology (M.Tech) in Computer Science & Engineering (Specialization: Artificial Intelligence & Machine Learning).
* **Anabin Database Status:** Institution rated **H+** (highest institutional recognition level in Germany); degree rated **Entspricht / Gleichwertig** to a German University Master's degree.
* **Visa Eligibility:** Directly qualifies for the **EU Blue Card (§ 18g AufenthG)** under the STEM / IT specialist shortage category, as well as the **Fast-Track Skilled Worker Procedure (§ 81a AufenthG)**.
* **Pre-Cleared Dossier:** Complete bureaucratic package (*Der Behörden-Ordner*) including verified transcripts, Anabin equivalency printouts, pre-filled § 81a application forms, and fee waiver declarations assembled for friction-free employer onboarding.
