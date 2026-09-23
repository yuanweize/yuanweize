<div align="center">

# Weize Yuan

**Systems Engineer · Open-Source Maintainer**

Managing Director @ **HKTSE s.r.o.** · Maintainer @ **EUR-UN**  
Prague, Czech Republic · **ČVUT FEL alumnus**

[HKTSE](https://hktse.eu.org) · [EUR-UN](https://eurun.eu.org) · [Technical Blog](https://yuanweize.github.io/) · [Email](mailto:info@eurun.eu.org)

<br>

<p>
  I build and maintain systems around network observability, macOS storage automation,<br>
  assistive technology, local AI, IoT infrastructure, and developer tooling.
</p>

</div>

---

## 🛠️ Selected Engineering Work

| System | Focus & Capabilities | Evidence & Artifacts |
|---|---|---|
| **[RouteLens](https://github.com/yuanweize/RouteLens)** | Go-powered agentless network observability platform pinpointing multi-hop latency and packet loss (Local vs Backbone vs DC) via restricted SSH telemetry. | [Release](https://github.com/yuanweize/RouteLens/releases) · [Docs](https://github.com/yuanweize/RouteLens/tree/master/docs) · [Docker GHCR](https://github.com/yuanweize/RouteLens/pkgs/container/routelens) |
| **[LazyMount-Mac](https://github.com/yuanweize/LazyMount-Mac)** | Automated macOS storage mount manager (SMB/Rclone) with APFS sparsebundle self-healing and launchd supervision for NAS gaming and cloud drives. | [Release](https://github.com/yuanweize/LazyMount-Mac/releases) · [Docs](https://github.com/yuanweize/LazyMount-Mac/tree/main/docs) · [ShellCheck CI](https://github.com/yuanweize/LazyMount-Mac/actions) |
| **[OptiKey-ET5-Plugin](https://github.com/yuanweize/OptiKey-ET5-Plugin)** | Open-source Tobii Eye Tracker 5 assistive communication (AAC) plugin for OptiKey, enabling gaze-based access for people with ALS/MND. | [Release](https://github.com/yuanweize/OptiKey-ET5-Plugin/releases) · [Windows CI](https://github.com/yuanweize/OptiKey-ET5-Plugin/actions) · [CodeQL](https://github.com/yuanweize/OptiKey-ET5-Plugin/security/code-scanning) |
| **[Uni-OCR](https://github.com/yuanweize/Uni-OCR)** | Unified multilingual OCR service with Apple Silicon MLX hardware acceleration, PaddleOCR, and local API inference backends. | [Release](https://github.com/yuanweize/Uni-OCR/releases) · [Docker GHCR](https://github.com/yuanweize/Uni-OCR/pkgs/container/uni-ocr) · [CI Pipeline](https://github.com/yuanweize/Uni-OCR/actions) |
| **[SmartHome_Server](https://github.com/yuanweize/SmartHome_Server)** | Smart home IoT telemetry gateway with dual-broker mTLS (Mosquitto/EMQX), sensor fleet simulation, and Home Assistant integration. | [Architecture](https://github.com/yuanweize/SmartHome_Server#architecture) · [Docker Stacks](https://github.com/yuanweize/SmartHome_Server/tree/main/broker) |
| **[ERPNext-Czech-COA](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter)** | Czech Chart of Accounts (Účtová osnova Decree 500/2002 Sb.) importer and AI-assisted translation engine for ERPNext v14/v15. | [Release](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter/releases) · [FastAPI Engine](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter#web-ui) |

---

## 🤝 Open-Source Maintenance & Upstream Contributions

### Upstream Contributions
- **[emqx/hocon](https://github.com/emqx/hocon)**  
  Contributor — [PR #318 (Merged)](https://github.com/emqx/hocon/pull/318)  
  *Fix CLI two-phase staging and rollback on `ENOSPC` disk exhaustion*: Implemented atomic temporary staging, reverse-order rollback, permission-bit preservation, and real 1 MiB tmpfs ENOSPC fault-injection tests across 580+ Erlang/OTP regression suites.
- **[gh-metrics/metrics](https://github.com/gh-metrics/metrics)**  
  Contributor — Open [PR #113](https://github.com/gh-metrics/metrics/pull/113) (*Steam plugin recently played games & time cutoff filter*), Open [PR #114](https://github.com/gh-metrics/metrics/pull/114) (*Lines plugin null-author template error rendering guard*).
- **[RayLabsHQ/gitea-mirror](https://github.com/RayLabsHQ/gitea-mirror)**  
  Contributor — [PR #305 (Merged)](https://github.com/RayLabsHQ/gitea-mirror/pull/305)  
  *Fix Docker container configuration template and environment variables in `.env.example`.*
- **[nezhahq/agent](https://github.com/nezhahq/agent)**  
  Contributor — [PR #233](https://github.com/nezhahq/agent/pull/233)  
  *Fix variable shadowing anomaly during runtime configuration hot-reload.*

### Collaborative & Community Maintenance
- **[EUR-UN/metrics-community](https://github.com/EUR-UN/metrics-community)**  
  Independent community-maintained fork of [lowlighter/metrics](https://github.com/lowlighter/metrics), maintained collaboratively under [EUR-UN](https://github.com/EUR-UN) with transparent upstream attribution, compatibility fixes, and multi-source update automation.

---

## 🎯 Technical Competencies

- **Systems & Networking**: Go, Linux network stack, multi-hop latency telemetry, agentless probing, launchd, rclone, SMB, APFS.
- **Assistive Technology & Accessibility**: C#, .NET runtime interop, Tobii Eye Tracking Core SDK, gaze coordinate smoothing, AAC systems.
- **Local AI & Edge Computing**: Apple Silicon MLX-VLM, Python FastAPI, Home Assistant, MQTT mTLS architecture, Docker Compose.

---

## 📊 Overview

<div align="center">
  <img src="https://raw.githubusercontent.com/yuanweize/yuanweize/main/github-metrics.svg" alt="GitHub Metrics" width="70%">
</div>

---

## 📬 Connect

- **Commercial / Company**: [HKTSE s.r.o.](https://hktse.eu.org)
- **Open-Source Organization**: [EUR-UN](https://eurun.eu.org)
- **Technical Blog**: [yuanweize.github.io](https://yuanweize.github.io/)
- **Email**: [info@eurun.eu.org](mailto:info@eurun.eu.org)
