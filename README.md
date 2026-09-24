<div align="center">

# Weize Yuan

**Software & Systems Engineer · Open-Source Maintainer**

[![Location](https://img.shields.io/badge/Location-Prague%2C_CZ-0969da?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Prague)
[![Education](https://img.shields.io/badge/Alumnus-%C4%8CVUT_FEL-005b94?style=flat-square)](https://fel.cvut.cz)
[![HKTSE](https://img.shields.io/badge/Engineering-HKTSE_s.r.o.-0f172a?style=flat-square&logo=googlechrome&logoColor=white)](https://hktse.eu.org)
[![EUR-UN](https://img.shields.io/badge/Organization-EUR--UN-10b981?style=flat-square&logo=github&logoColor=white)](https://github.com/EUR-UN)
[![Blog](https://img.shields.io/badge/Blog-yuanweize.github.io-f59e0b?style=flat-square&logo=blogger&logoColor=white)](https://yuanweize.github.io/)
[![Email](https://img.shields.io/badge/Email-info%40eurun.eu.org-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:info@eurun.eu.org)

<br>

<p>
  I build reliability-focused software and systems across backend services, infrastructure automation,<br>
  network observability, applied AI, and connected/industrial systems.
</p>

</div>

---

## 🤝 Upstream Engineering & Community Maintenance

### Upstream Systems Contributions

- **[nezhahq/agent](https://github.com/nezhahq/agent)** — High-Performance Distributed Server Telemetry Agent  
  [![Merged PR](https://img.shields.io/badge/PR_%23229-MERGED_(v1.15.0)-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/nezhahq/agent/pull/229) [![Merged PR](https://img.shields.io/badge/PR_%23233-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/nezhahq/agent/pull/233) [![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/nezhahq/agent) [![Intel iGPU](https://img.shields.io/badge/Intel-iGPU_Telemetry-0071C5?style=flat-square&logo=intel&logoColor=white)](https://github.com/nezhahq/agent/pull/229)
  - **Linux Intel iGPU Hardware Telemetry Engine (#229 · Merged & Tagged in v1.15.0)**: Architected native Linux Intel iGPU hardware telemetry via Direct Rendering Manager (`/sys/class/drm`, Vendor ID `0x8086`) and PCI topology via `ghw`. Parsed real-time hardware telemetry (`intel_gpu_top`) covering 5 independent execution engines: **RCS** (Render/3D), **BCS** (Blitter), **VCS** (Video Codec), **VECS** (Video Enhancement), and **CCS** (Compute Acceleration). Engineered zero-overhead singleton detection via `sync.Once` to eliminate process polling overhead.
  - **Runtime Configuration Hot-Reload Concurrency (#233 · Merged)**: Identified and resolved variable shadowing in `handleApplyConfigTask`, eliminating state desynchronization during dynamic configuration reloads across production fleets.

- **[emqx/hocon](https://github.com/emqx/hocon)** — Configuration Engine for EMQX Enterprise MQTT Broker  
  [![Merged PR](https://img.shields.io/badge/PR_%23318-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/emqx/hocon/pull/318) [![Erlang/OTP](https://img.shields.io/badge/Erlang%2FOTP-A90533?style=flat-square&logo=erlang&logoColor=white)](https://github.com/emqx/hocon) [![Storage Fault Injection](https://img.shields.io/badge/Fault_Injection-1MiB_tmpfs-orange?style=flat-square&logo=linux&logoColor=white)](https://github.com/emqx/hocon/pull/318)
  - **CLI Two-Phase Staging & `ENOSPC` Disk-Full Rollback (#318 · Merged · Reviewed by @zmstone)**: Guarded broker configuration generation against physical disk exhaustion. Engineered a transactional two-phase file staging mechanism with reverse-order fault rollback and strict POSIX file mode preservation (`0600`/`0644`). Proved zero-corruption resilience by constructing a 1 MiB tmpfs physical disk-full fault injection test suite passing 580+ Erlang/OTP regression tests.

- **[RayLabsHQ/gitea-mirror](https://github.com/RayLabsHQ/gitea-mirror)** — Multi-Source Enterprise Git Mirror Pipeline  
  [![Merged PR](https://img.shields.io/badge/PR_%23305-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/RayLabsHQ/gitea-mirror/pull/305) [![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/RayLabsHQ/gitea-mirror)
  - **Container Infrastructure Alignment (#305 · Merged)**: Fixed Docker environment variable propagation and image repository configuration templates in `.env.example`.

- **[gh-metrics/metrics](https://github.com/gh-metrics/metrics)** — Ecosystem Metrics Generation Framework  
  [![Open PR](https://img.shields.io/badge/PR_%23113-OPEN-238636?style=flat-square&logo=git&logoColor=white)](https://github.com/gh-metrics/metrics/pull/113) [![Open PR](https://img.shields.io/badge/PR_%23114-OPEN-238636?style=flat-square&logo=git&logoColor=white)](https://github.com/gh-metrics/metrics/pull/114) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/gh-metrics/metrics)
  - **Pipeline Overflow & Fault Tolerance Guards (#113 & #114 · Open)**: Implemented playtime cutoff filters to prevent SVG rendering overflow on large Steam libraries (#113); added null-author defensive guards preventing template crashes on unmapped commit authors (#114).

### Collaborative & Community Maintenance

- **[EUR-UN/metrics-community](https://github.com/EUR-UN/metrics-community)** — Community-Maintained Distribution  
  [![Community Maintained](https://img.shields.io/badge/EUR--UN-Community_Maintained-0969da?style=flat-square&logo=github&logoColor=white)](https://github.com/EUR-UN/metrics-community) [![GHCR](https://img.shields.io/badge/GHCR-Docker_Image-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/EUR-UN/metrics-community/pkgs/container/metrics-community) [![Releases](https://img.shields.io/badge/Releases-Active-success?style=flat-square&logo=semanticrelease&logoColor=white)](https://github.com/EUR-UN/metrics-community/releases)  
  Collaborative community fork of [lowlighter/metrics](https://github.com/lowlighter/metrics) operated under [EUR-UN](https://github.com/EUR-UN). Delivers transparent upstream attribution, security updates, reviewed PR integrations, and automated multi-arch container releases.

---

## 🛠️ Selected Systems

### 1. [Atomic Sync](https://github.com/yuanweize/Atomic-Sync) — Guarded Directory-Unit Transfer Control Plane
[![Go](https://img.shields.io/badge/Go-1.24-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/yuanweize/Atomic-Sync)
[![CI](https://img.shields.io/github/actions/workflow/status/yuanweize/Atomic-Sync/ci.yml?branch=main&label=CI&style=flat-square)](https://github.com/yuanweize/Atomic-Sync/actions)
[![CodeQL](https://img.shields.io/github/actions/workflow/status/yuanweize/Atomic-Sync/codeql.yml?branch=main&label=CodeQL&style=flat-square)](https://github.com/yuanweize/Atomic-Sync/security/code-scanning)
[![GHCR](https://img.shields.io/badge/GHCR-Multi--Arch-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/yuanweize/Atomic-Sync/pkgs/container/atomic-sync)
[![Release](https://img.shields.io/github/v/release/yuanweize/Atomic-Sync?style=flat-square)](https://github.com/yuanweize/Atomic-Sync/releases)

- **Problem**: Conventional sync tools (`rclone move --min-age`) evaluate individual files independently. If a newly written file arrives inside an older project or dataset tree, standard tools transfer the old files first, splitting coherent directory structures across storage tiers.
- **System**: A dedicated Go control plane that groups directory trees into atomic transfer units based on the newest internal modification time, verifies boundary stability, and orchestrates transfers.
- **Engineering Decision**: Decoupled control plane from data plane—delegates physical data transfer directly to rclone (`copy` or `move`) while enforcing fail-closed discovery on unclassified files, eliminating destructive destination pruning, and retaining durable SQLite execution history.
- **Proof**: Multi-arch container images on GHCR, automated CI & CodeQL pipelines, fail-closed policy tests, and documented [Architecture](https://github.com/yuanweize/Atomic-Sync/blob/main/docs/ARCHITECTURE.md) and [Operations](https://github.com/yuanweize/Atomic-Sync/blob/main/docs/OPERATIONS.md) guides.

### 2. [FormVault](https://github.com/yuanweize/FormVault) — Privacy-First Document Intake & Regulatory Application Platform
[![FastAPI](https://img.shields.io/badge/FastAPI-Python_3.11-009688?style=flat-square&logo=fastapi&logoColor=white)](https://github.com/yuanweize/FormVault)
[![React](https://img.shields.io/badge/React_18-TypeScript-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/yuanweize/FormVault)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/yuanweize/FormVault)
[![Frontend CI](https://img.shields.io/github/actions/workflow/status/yuanweize/FormVault/frontend-ci.yml?branch=main&label=Frontend%20CI&style=flat-square)](https://github.com/yuanweize/FormVault/actions)
[![Backend CI](https://img.shields.io/github/actions/workflow/status/yuanweize/FormVault/backend-ci.yml?branch=main&label=Backend%20CI&style=flat-square)](https://github.com/yuanweize/FormVault/actions)

- **Problem**: Cross-border insurance and statutory document intake requires strict data privacy, non-repudiable auditability, and dynamic regulatory mode gating without exposing sensitive applicant records.
- **System**: Production document intake portal providing multi-step validation, client-side identity inspection, authenticated AES-256-GCM encrypted storage, and dual-mode business operations.
- **Engineering Decision**: Implemented a tamper-evident SHA-256 audit hash chain with monotonically increasing sequence numbers and immutable parent hashes; designed dynamic regulatory gating (`LEAD_ONLY` default vs `ASSISTED_APPLICATION` post-broker agreement) to guarantee legal compliance.
- **Proof**: Deployed in live production ([insure.hktse.eu.org](https://insure.hktse.eu.org/)), automated backend/frontend CI pipelines, WCAG 2.1 AA zero-violation accessibility verification, and turnkey Docker Compose orchestration.

### 3. [RouteLens](https://github.com/yuanweize/RouteLens) — Agentless Multi-Hop Network Observability Platform
[![Go](https://img.shields.io/badge/Go-1.24-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/yuanweize/RouteLens)
[![React](https://img.shields.io/badge/React_18-Vite-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/yuanweize/RouteLens)
[![GHCR](https://img.shields.io/badge/GHCR-Docker_Image-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/yuanweize/RouteLens/pkgs/container/routelens)
[![Release](https://img.shields.io/github/v/release/yuanweize/RouteLens?style=flat-square)](https://github.com/yuanweize/RouteLens/releases)

- **Problem**: Isolating packet loss and latency spikes across distributed hybrid nodes typically requires intrusive background monitoring agents, complicating deployment and increasing the attack surface.
- **System**: Agentless network diagnostics platform pinpointing multi-hop latency and loss (Local vs Backbone vs Datacenter) via scheduled, restricted SSH probe execution.
- **Engineering Decision**: Distributed as a single self-contained Go binary with embedded React/ECharts static assets; adopted a pure-Go SQLite storage engine (zero CGO) for frictionless, cross-platform Linux deployments.
- **Proof**: Multi-platform release packages (.deb, .rpm, binary tarballs), GHCR container images, GoReleaser automation, and live technical documentation.

### 4. [Signal Market Bot](https://github.com/yuanweize/signal-market-bot) — Conversational Commerce & Agent Runtime for Signal
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/yuanweize/signal-market-bot)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?style=flat-square&logo=fastapi&logoColor=white)](https://github.com/yuanweize/signal-market-bot)
[![CI](https://img.shields.io/github/actions/workflow/status/yuanweize/signal-market-bot/ci.yml?branch=main&label=CI&style=flat-square)](https://github.com/yuanweize/signal-market-bot/actions)
[![Docker Ready](https://img.shields.io/badge/Docker-Ready-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/yuanweize/signal-market-bot/pkgs/container/signal-market-bot-backend)
[![Release](https://img.shields.io/github/v/release/yuanweize/signal-market-bot?style=flat-square)](https://github.com/yuanweize/signal-market-bot/releases)

- **Problem**: Deploying autonomous LLM agents into private messaging ecosystems carries risks of multi-tenant data leakage, ungrounded actions, and runaway tool invocation during customer interactions.
- **System**: Signal-native AI customer support and conversational commerce platform with a directed LangGraph workflow, scoped Qdrant vector retrieval, and Model Context Protocol (MCP) tool integration.
- **Engineering Decision**: Enforced an absolute group privacy invariant (P0: group chats cannot access private user documents or memory); integrated human-in-the-loop supervisory drafts (`draft_for_human`) for sensitive actions; constructed a 32-case deterministic evaluation suite verifying response boundaries.
- **Proof**: 100% CI pass rate on deterministic contract evaluation (`evals/run_evals.py`), GHCR container builds, and comprehensive architecture documentation.

### 5. [OptiKey ET5 Plugin](https://github.com/yuanweize/OptiKey-ET5-Plugin) — Assistive Gaze Interface for Tobii Eye Tracker 5
[![C#](https://img.shields.io/badge/C%23-.NET_Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://github.com/yuanweize/OptiKey-ET5-Plugin)
[![CI](https://img.shields.io/github/actions/workflow/status/yuanweize/OptiKey-ET5-Plugin/build.yml?branch=main&label=CI&style=flat-square)](https://github.com/yuanweize/OptiKey-ET5-Plugin/actions)
[![CodeQL](https://img.shields.io/github/actions/workflow/status/yuanweize/OptiKey-ET5-Plugin/codeql.yml?branch=main&label=CodeQL&style=flat-square)](https://github.com/yuanweize/OptiKey-ET5-Plugin/security/code-scanning)
[![Release](https://img.shields.io/github/v/release/yuanweize/OptiKey-ET5-Plugin?style=flat-square)](https://github.com/yuanweize/OptiKey-ET5-Plugin/releases)

- **Problem**: Commercial eye-tracking devices for gaming (Tobii ET5) lack open-source drivers for assistive Augmentative and Alternative Communication (AAC) software, locking out patients with ALS/MND from affordable communication aids.
- **System**: Open-source hardware abstraction plugin bridging the Tobii Eye Tracker 5 SDK to the OptiKey assistive typing keyboard.
- **Engineering Decision**: Designed an interruptible background callback pump to decouple high-frequency hardware gaze streams from UI message loops; engineered bounded shutdown guarantees to prevent unhook crashes; strictly zero telemetry for patient privacy.
- **Proof**: Tagged production releases with SHA-256 checksums, automated .NET build CI, CodeQL scanning, and active open-source adoption by AAC practitioners.

### Other Systems & Tooling

- **[LazyMount-Mac](https://github.com/yuanweize/LazyMount-Mac)** — Automated macOS storage mount manager (SMB/Rclone) featuring APFS sparsebundle self-healing and launchd daemon supervision.
- **[Uni-OCR](https://github.com/yuanweize/Uni-OCR)** — Unified multilingual OCR API service with Apple Silicon MLX hardware-accelerated VLM and PaddleOCR backends.
- **[SmartHome_Server](https://github.com/yuanweize/SmartHome_Server)** — Dual-broker MQTT (Mosquitto / EMQX) telemetry gateway with mutual TLS (mTLS), sensor simulation, and Home Assistant integration.
- **[ERPNext-Czech-COA](https://github.com/yuanweize/ERPNext-Czech-Uctova-Osnova-COA-Converter)** — Czech Chart of Accounts (Decree 500/2002 Sb.) statutory parser and localization engine for ERPNext v14/v15.

---

## 🏭 Industrial & Connected Systems

Alongside software engineering, I maintain direct hands-on experience integrating industrial automation, robotics, and connected hardware across European manufacturing sites:

- **Industrial Automation & PLC/MES Integration**: Field commissioning of Siemens S7-1200 PLCs and HMIs; integrated real-time PLC-to-MES barcode traceability and production data logging channels.
- **Robotic Workcell Integration**: On-site programming, calibration, and integration of ABB industrial robotic cells across automotive and manufacturing facilities in Central/Eastern Europe (Czechia, Slovakia, Romania, Poland).
- **Connected Field Devices & IoT**: Firmware development for ESP32 telemetry nodes, RS-485 / Modbus serial communication buses, and secure MQTT telemetry using mutual TLS (mTLS).

---

## 🎯 Engineering Focus

- **Backend & Distributed Systems**: Python · Go · FastAPI · LangGraph · PostgreSQL · SQLite · Redis · Asynchronous Workflows
- **Systems & Infrastructure Automation**: Linux (POSIX) · Docker · Bash · macOS Darwin · CI/CD (GitHub Actions) · Release Engineering
- **Observability & Network Protocols**: Network Diagnostics · SSH Telemetry · MQTT (mTLS) · WireGuard · Erlang/OTP Configuration
- **Connected & Industrial Systems**: Siemens S7-1200 · ABB Robotics · Modbus / RS-485 · ESP32 · Hardware-Interfaced Software

---

## 📊 Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/yuanweize/yuanweize/main/github-metrics.svg" alt="GitHub Metrics" width="70%">
</div>

---

## 📬 Contact & Organizations

<div align="center">

[![HKTSE s.r.o.](https://img.shields.io/badge/HKTSE_s.r.o.-Independent_Engineering-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://hktse.eu.org)
&nbsp;
[![EUR-UN](https://img.shields.io/badge/EUR--UN-Open_Source_Org-10B981?style=flat-square&logo=github&logoColor=white)](https://eurun.eu.org)
&nbsp;
[![Technical Blog](https://img.shields.io/badge/Blog-yuanweize.github.io-F59E0B?style=flat-square&logo=blogger&logoColor=white)](https://yuanweize.github.io/)
&nbsp;
[![Email](https://img.shields.io/badge/Email-info%40eurun.eu.org-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:info@eurun.eu.org)

</div>
