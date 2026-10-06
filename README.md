<div align="center">

# Allen Fletcher

**Machine Learning Systems & High-Throughput Data Infrastructure Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/allen-fletcher)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/AllenFletcherAI)
[![Email](https://img.shields.io/badge/Direct-allensimeonfletcher%40gmail.com-blue?style=flat&logo=gmail&logoColor=white)](mailto:allensimeonfletcher@gmail.com)
[![Status: Anabin H+](https://img.shields.io/badge/Academic%20Parity-Anabin%20H%2B%20%7C%20Consecutive%20Master-success?style=flat)]()

</div>

---

## ⚡ Executive Focus

Machine Learning Systems Engineer specializing in high-throughput document extraction pipelines, deterministic reconciliation services, and low-latency inference runtimes. Engineering production pipelines across unstructured computer vision, multimodal document intake, and enterprise staging synchronization.

* **Core Focus:** Structural model quantization, low-latency microservice architectures, and deterministic data ingestion engines.
* **Production Runtimes:** NVIDIA TensorRT, Triton Inference Server, ONNX Runtime, and containerized FastAPI services.
* **Statutory Status:** Anabin-verified 5-year Integrated M.Tech (H+ / Consecutive Master Equivalence), fully qualifying for EU Blue Card (§18g AufenthG) and Accelerated Skilled Worker Procedures (§81a AufenthG).

---

## 🛠️ Flagship Systems & Deployments

### 🚢 [FreightMatch-TMS // Autonomous Logistics Intake & 3-Way Reconciliation Engine](https://github.com/AllenFletcherAI/FreightMatch-TMS)
* **Live Interactive Pipeline:** [freightmatch-tms.streamlit.app](https://freightmatch-tms.streamlit.app)
* **Architecture:** Deterministic multimodal vision parsing engine categorizing unstructured maritime and logistics streams across 4 umbrella classes (Financials, Transport/Title, Cargo Specs, Customs).
* **Core Capabilities:** Sub-second layout decomposition, automated 3-way reconciliation (rate variance, weight deltas, missing endorsements), and validated enterprise webhook dispatch (`POST /api/v1/shipments/stage`).
* **Stack:** Python, Google GenAI Multimodal Vision, PyPDF, Pydantic, Streamlit, Docker.

---

## ⚙️ Technical Architecture & Core Stack

```text
 ┌─────────────────────────────────────────────────────────────────────────┐
 │                     ENTERPRISE ML SYSTEMS STACK                         │
 ├─────────────────────────┬───────────────────────────────────────────────┤
 │ Runtime & Acceleration  │ NVIDIA TensorRT · ONNX Runtime · Triton · C++ │
 │ Machine Learning & DL   │ PyTorch · Hugging Face Hub · Transformers     │
 │ Serving & Microservices │ FastAPI · Docker · Redis · Celery · Linux     │
 │ Data & Spatial Vision   │ OpenCV · NumPy · SciPy · PostgreSQL · Vector  │
 │ Cloud & Infrastructure  │ AWS (S3, Lambda, API Gateway) · GitHub CI/CD  │
 └─────────────────────────┴───────────────────────────────────────────────┘
