<div align="center">

# Weize Yuan

**Systems Engineer · Open-Source Maintainer**

[![Managing Director](https://img.shields.io/badge/Managing_Director-HKTSE_s.r.o.-0f172a?style=flat-square&logo=enterprise&logoColor=white)](https://hktse.eu.org)
[![Maintainer](https://img.shields.io/badge/Maintainer-EUR--UN-1e293b?style=flat-square&logo=github&logoColor=white)](https://eurun.eu.org)
[![Alumnus](https://img.shields.io/badge/Alumnus-%C4%8CVUT_FEL-005b94?style=flat-square)](https://fel.cvut.cz)
[![Location](https://img.shields.io/badge/Location-Prague%2C_CZ-0969da?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Prague)

<br>

<p>
  I architect and maintain low-latency systems across agentless network telemetry, macOS storage automation,<br>
  assistive eye-tracking AAC technology, local AI inference, and distributed IoT infrastructure.
</p>

[![Corporate Portal](https://img.shields.io/badge/HKTSE_s.r.o.-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://hktse.eu.org)
[![Open Source Org](https://img.shields.io/badge/EUR--UN-10B981?style=flat-square&logo=github&logoColor=white)](https://eurun.eu.org)
[![Technical Blog](https://img.shields.io/badge/yuanweize.github.io-F59E0B?style=flat-square&logo=blogger&logoColor=white)](https://yuanweize.github.io/)
[![Direct Email](https://img.shields.io/badge/info%40eurun.eu.org-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:info@eurun.eu.org)

</div>

---

## 🛠️ Selected Engineering Work

| System | Stack | Architecture & Core Capabilities | Artifacts & Proof |
|:---|:---|:---|:---|
| **[RouteLens](https://github.com/yuanweize/RouteLens)** | [![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/yuanweize/RouteLens) [![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://github.com/yuanweize/RouteLens) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/yuanweize/RouteLens) | Agentless network observability platform pinpointing multi-hop latency and packet loss (Local vs Backbone vs DC) via restricted SSH telemetry. | [Release](https://github.com/yuanweize/RouteLens/releases) · [Docs](https://github.com/yuanweize/RouteLens/tree/master/docs) · [GHCR](https://github.com/yuanweize/RouteLens/pkgs/container/routelens) |
| **[LazyMount-Mac](https://github.com/yuanweize/LazyMount-Mac)** | [![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)](https://github.com/yuanweize/LazyMount-Mac) [![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://github.com/yuanweize/LazyMount-Mac) [![APFS](https://img.shields.io/badge/-APFS-555555?style=flat-square&logo=apple&logoColor=white)](https://github.com/yuanweize/LazyMount-Mac) | Automated macOS storage mount manager (SMB/Rclone) with APFS sparsebundle self-healing and launchd supervision for NAS gaming and cloud drives. | [Release](https://github.com/yuanweize/LazyMount-Mac/releases) · [Docs](https://github.com/yuanweize/LazyMount-Mac/tree/main/docs) · [CI](https://github.com/yuanweize/LazyMount-Mac/actions) |
| **[OptiKey-ET5-Plugin](https://github.com/yuanweize/OptiKey-ET5-Plugin)** | [![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white)](https://github.com/yuanweize/OptiKey-ET5-Plugin) [![.NET](https://img.shields.io/badge/-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://github.com/yuanweize/OptiKey-ET5-Plugin) [![Windows](https://img.shields.io/badge/-Windows-0078D6?style=flat-square&logo=windows&logoColor=white)](https://github.com/yuanweize/OptiKey-ET5-Plugin) | Open-source Tobii Eye Tracker 5 assistive communication (AAC) plugin for OptiKey, enabling gaze-based access for people with ALS/MND. | [Release](https://github.com/yuanweize/OptiKey-ET5-Plugin/releases) · [CI](https://github.com/yuanweize/OptiKey-ET5-Plugin/actions) · [CodeQL](https://github.com/yuanweize/OptiKey-ET5-Plugin/security/code-scanning) |
| **[Uni-OCR](https://github.com/yuanweize/Uni-OCR)** | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/yuanweize/Uni-OCR) [![Apple MLX](https://img.shields.io/badge/-Apple%20MLX-000000?style=flat-square&logo=apple&logoColor=white)](https://github.com/yuanweize/Uni-OCR) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://github.com/yuanweize/Uni-OCR) | Unified multilingual OCR service with Apple Silicon MLX hardware acceleration, PaddleOCR, and local API inference backends. | [Release](https://github.com/yuanweize/Uni-OCR/releases) · [GHCR](https://github.com/yuanweize/Uni-OCR/pkgs/container/uni-ocr) · [CI](https://github.com/yuanweize/Uni-OCR/actions) |
| **[SmartHome_Server](https://github.com/yuanweize/SmartHome_Server)** | [![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)](https://github.com/yuanweize/SmartHome_Server) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/yuanweize/SmartHome_Server) [![HA](https://img.shields.io/badge/-Home_Assistant-41BDF5?style=flat-square&logo=home-assistant&logoColor=white)](https://github.com/yuanweize/SmartHome_Server) | Smart home IoT telemetry gateway with dual-broker mTLS (Mosquitto/EMQX), sensor fleet simulation, and Home Assistant integration. | [Architecture](https://github.com/yuanweize/SmartHome_Server#architecture) · [Stacks](https://github.com/yuanweize/SmartHome_Server/tree/main/broker) |
| **[ERPNext-Czech-COA](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter)** | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter) [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter) [![ERPNext](https://img.shields.io/badge/-ERPNext-0089FF?style=flat-square&logo=erpnext&logoColor=white)](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter) | Czech Chart of Accounts (Účtová osnova Decree 500/2002 Sb.) importer and AI-assisted translation engine for ERPNext v14/v15. | [Release](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter/releases) · [Web UI](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter#web-ui) |

---

## 🤝 Open-Source Maintenance & Upstream Contributions

### Upstream Systems & Kernel-Level Engineering

- **[nezhahq/agent](https://github.com/nezhahq/agent)** (High-Performance Distributed Telemetry Agent)  
  [![Merged PR](https://img.shields.io/badge/PR_%23229-MERGED_(v1.15.0)-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/nezhahq/agent/pull/229) [![Merged PR](https://img.shields.io/badge/PR_%23233-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/nezhahq/agent/pull/233) [![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/nezhahq/agent) [![Intel iGPU](https://img.shields.io/badge/Intel-iGPU_Telemetry-0071C5?style=flat-square&logo=intel&logoColor=white)](https://github.com/nezhahq/agent/pull/229)  
  - **Linux Intel iGPU Hardware Telemetry Engine (#229 · Tagged in v1.15.0)**:  
    Architected native Linux Intel iGPU hardware monitoring via Direct Rendering Manager (`/sys/class/drm`, Vendor ID `0x8086`) and PCI topology via `ghw`. Parsed real-time hardware telemetry (`intel_gpu_top`) covering 5 independent silicon execution engines: **RCS** (Render/3D), **BCS** (Blitter), **VCS** (Video Codec), **VECS** (Video Enhancement), and **CCS** (Compute Acceleration). Engineered zero-overhead singleton detection via `sync.Once`, eliminating process polling and memory allocation overhead.
  - **Runtime Configuration Hot-Reload Concurrency (#233)**:  
    Identified and resolved a microsecond-level variable shadowing (Variable Shadowing) concurrency defect in `handleApplyConfigTask`, eliminating state desynchronization during dynamic agent configuration reloads in production fleets.

- **[emqx/hocon](https://github.com/emqx/hocon)** (Distributed Configuration Engine for EMQX Enterprise Broker)  
  [![Merged PR](https://img.shields.io/badge/PR_%23318-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/emqx/hocon/pull/318) [![Erlang/OTP](https://img.shields.io/badge/Erlang%2FOTP-A90533?style=flat-square&logo=erlang&logoColor=white)](https://github.com/emqx/hocon) [![Storage Systems](https://img.shields.io/badge/Storage-Atomic_Staging-orange?style=flat-square&logo=linux&logoColor=white)](https://github.com/emqx/hocon/pull/318)  
  - **CLI Two-Phase Staging & `ENOSPC` Rollback (#318 · Reviewed by Core Maintainer @zmstone)**:  
    Guarded mission-critical EMQX broker configuration generation against physical disk exhaustion. Built a transactional two-phase staging mechanism with reverse-order fault rollback and strict POSIX file mode preservation (`0600`/`0644`). Proved zero-corruption resilience by constructing a real **1 MiB tmpfs physical disk-full fault injection sandbox** passing 580+ Erlang/OTP regression suites.

- **[gh-metrics/metrics](https://github.com/gh-metrics/metrics)** (Ecosystem Metrics Generation Framework)  
  [![Open PR](https://img.shields.io/badge/PR_%23113-OPEN-238636?style=flat-square&logo=git&logoColor=white)](https://github.com/gh-metrics/metrics/pull/113) [![Open PR](https://img.shields.io/badge/PR_%23114-OPEN-238636?style=flat-square&logo=git&logoColor=white)](https://github.com/gh-metrics/metrics/pull/114) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/gh-metrics/metrics)  
  - **Pipeline Crash Guard & High-Scale API Thresholding**:  
    Implemented SVG rendering overflow safeguards for Steam accounts with large libraries via playtime cutoff filters (#113); built a fault-tolerant null-author guard (#114) preventing template renderer crashes when parsing commits with unmapped or ghost authors.

- **[RayLabsHQ/gitea-mirror](https://github.com/RayLabsHQ/gitea-mirror)** (Multi-Source Enterprise Git Mirror Pipeline)  
  [![Merged PR](https://img.shields.io/badge/PR_%23305-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/RayLabsHQ/gitea-mirror/pull/305) [![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/RayLabsHQ/gitea-mirror)  
  - **Container Infrastructure Alignment**:  
    Fixed Docker environment variable propagation and image repository configuration templates in `.env.example`, ensuring seamless hybrid-cloud container deployments.

### Collaborative & Community Maintenance

- **[EUR-UN/metrics-community](https://github.com/EUR-UN/metrics-community)**  
  [![Community Distribution](https://img.shields.io/badge/EUR--UN-Community_Maintained-0969da?style=flat-square&logo=github&logoColor=white)](https://github.com/EUR-UN/metrics-community) [![GHCR Container](https://img.shields.io/badge/GHCR-Docker_Image-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/EUR-UN/metrics-community/pkgs/container/metrics-community) [![Release](https://img.shields.io/badge/Release-Active-success?style=flat-square&logo=semanticrelease&logoColor=white)](https://github.com/EUR-UN/metrics-community/releases)  
  Independent community-maintained fork of [lowlighter/metrics](https://github.com/lowlighter/metrics), operated collaboratively under [EUR-UN](https://github.com/EUR-UN) with transparent upstream attribution, security updates, multi-source update flows, and automated container releases.

---

## 💻 Tech Stack & Toolchain

<div align="center">
  <img src="https://skillicons.dev/icons?i=go,python,cs,dotnet,c,cpp,bash,linux,apple,docker,githubactions,fastapi,postgres,sqlite,cloudflare&theme=dark" alt="Technical Toolchain" />
</div>

<br>

| Domain | Core Technologies & Tools |
|:---|:---|
| **Languages & Runtimes** | [![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org) [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org) [![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/) [![.NET](https://img.shields.io/badge/-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/) [![C/C++](https://img.shields.io/badge/-C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](https://isocpp.org) [![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/) [![Erlang/OTP](https://img.shields.io/badge/-Erlang%2FOTP-A90533?style=flat-square&logo=erlang&logoColor=white)](https://www.erlang.org) |
| **Operating Systems & Infrastructure** | [![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://kernel.org) [![macOS](https://img.shields.io/badge/-macOS_Darwin-000000?style=flat-square&logo=apple&logoColor=white)](https://apple.com/macos) [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com) [![WireGuard](https://img.shields.io/badge/-WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)](https://wireguard.com) [![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)](https://cloudflare.com) [![GitHub Actions](https://img.shields.io/badge/-CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions) |
| **Observability, Protocols & Services** | [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com) [![MQTT](https://img.shields.io/badge/-MQTT_mTLS-660066?style=flat-square&logo=mqtt&logoColor=white)](https://mqtt.org) [![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://postgresql.org) [![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://sqlite.org) [![SSH Telemetry](https://img.shields.io/badge/-SSH_Telemetry-24292e?style=flat-square&logo=gnubash&logoColor=white)](https://github.com/yuanweize/RouteLens) |
| **Edge AI & Assistive Technology** | [![Apple MLX](https://img.shields.io/badge/-Apple_Silicon_MLX-000000?style=flat-square&logo=apple&logoColor=white)](https://github.com/ml-explore/mlx) [![Home Assistant](https://img.shields.io/badge/-Home_Assistant-41BDF5?style=flat-square&logo=home-assistant&logoColor=white)](https://home-assistant.io) [![Tobii Eye Tracking](https://img.shields.io/badge/-Tobii_Core_SDK-FF0044?style=flat-square&logo=eye&logoColor=white)](https://developer.tobii.com) [![PaddleOCR](https://img.shields.io/badge/-PaddleOCR-0052cc?style=flat-square&logo=baidu&logoColor=white)](https://github.com/PaddlePaddle/PaddleOCR) |

---

## 📊 Overview

<div align="center">
  <img src="https://raw.githubusercontent.com/yuanweize/yuanweize/main/github-metrics.svg" alt="GitHub Metrics" width="70%">
</div>

---

## 📬 Connect

<div align="center">

[![HKTSE s.r.o.](https://img.shields.io/badge/HKTSE_s.r.o.-Corporate_Portal-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://hktse.eu.org)
&nbsp;
[![EUR-UN](https://img.shields.io/badge/EUR--UN-Open_Source_Org-10B981?style=for-the-badge&logo=github&logoColor=white)](https://eurun.eu.org)
&nbsp;
[![Technical Blog](https://img.shields.io/badge/Tech_Blog-yuanweize.github.io-F59E0B?style=for-the-badge&logo=blogger&logoColor=white)](https://yuanweize.github.io/)
&nbsp;
[![Email Contact](https://img.shields.io/badge/Direct_Email-info%40eurun.eu.org-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@eurun.eu.org)

</div>
