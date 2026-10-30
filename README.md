<div align="center">

<img src="./gatecore-logo.png" width="140" alt="GateCore Logo" style="border-radius: 18px; margin-bottom: 16px;" />

# Mohamed Sameh

**Systems Architect & Infrastructure Engineer**  
Creator of [**GateCore**](https://github.com/mo7med20/gatecore) — Sovereign On-Premises ADC & Layer 7 Web Application Firewall

[![Go Version](https://img.shields.io/badge/Go-1.26.10-00ADD8?style=flat-square&logo=go)](https://go.dev/)
[![Security Audit](https://img.shields.io/badge/CVEs-0%20Known-10B981?style=flat-square)](https://github.com/mo7med20/gatecore)
[![License](https://img.shields.io/badge/Architecture-Sovereign%20%26%20Air--Gapped-090D16?style=flat-square)](https://github.com/mo7med20/gatecore)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Sameh-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/mohamed--sameh)
[![Twitter / X](https://img.shields.io/badge/X-@MohamedSam7238-000000?style=flat-square&logo=x)](https://x.com/MohamedSam7238)

<br/>

> **Mohamed Sameh builds enterprise networking and infrastructure software. Currently creating GateCore, a software-defined application delivery platform for modern infrastructure.**

</div>

---

### 🛡️ Flagship Project: [GateCore](https://github.com/mo7med20/gatecore)

GateCore is a single, zero-dependency Go binary combining a high-throughput L4/L7 reverse proxy, strict TLS 1.3 termination, an embedded Layer 7 WAF, and a local Web management control plane.

* **Sovereign & Self-Contained:** Runs in `<35MB` RAM with zero external databases, daemons, or cloud phone-home dependencies.
* **Cryptographic & Supply-Chain Integrity:** Reproducible builds, verifiable Go toolchain (`vcs.modified=false`), Syft SPDX SBOMs, keyless Cosign signatures, and OpenVEX vulnerability attestations.
* **High-Throughput Data Plane:** Peak-EWMA latency-based load balancing, active health checks, zero-downtime certificate hot reloading (`SIGHUP` / `GetCertificate`), and sub-second connection draining.
* **Enterprise Security Engine:** OWASP Layer 7 inspection (SQLi, XSS, RCE, traversal), GeoIP filtering, per-path mTLS, and tamper-evident audit logging with SIEM forwarding (CEF, LEEF, RFC 5424).
* **Air-Gapped Licensing:** Hardware-bound node fingerprinting and offline Ed25519 digital signature validation for physical appliances and secure on-premise enclaves.

---

### ⚙️ Core Engineering Competencies

```
  ┌────────────────────────────────────────────────────────────────────────┐
  │                           MOHAMED SAMEH                                │
  │                        SYSTEMS ARCHITECTURE                            │
  └────────────────────────────────────────────────────────────────────────┘
         │                                       │
         ▼                                       ▼
  [ NETWORKING & DATA PLANE ]             [ SECURITY & SUPPLY CHAIN ]
  • L4/L7 High-Throughput Proxies         • Layer 7 WAF & OWASP Engines
  • Peak-EWMA & Load Distribution         • Strict TLS 1.3 & mTLS Auth
  • HTTP/2, gRPC & TCP Splice             • OpenVEX & Syft SPDX SBOMs
  • Kernel Zero-Copy & sync.Pool          • Ed25519 Cryptographic Licensing
  • Sub-Second Graceful Connection Drain  • Immutable HMAC Audit Chaining
```

* **Data Plane & Distributed Systems:**
  - High-concurrency network servers in Go using non-blocking I/O and zero-allocation memory pools (`sync.Pool`).
  - Resilient load balancing algorithms (Peak-EWMA, Round-Robin, Least-Connections) with active health check state machines.
  - Zero-downtime process reloading and sub-second connection draining.
* **Systems & Application Security:**
  - Strict TLS 1.3 enforcement with AEAD cipher suites (AES-GCM, ChaCha20-Poly1305) and client certificate (mTLS) verification.
  - Application layer firewall engines defending against OWASP Top 10 exploits without external proxy sidecars.
  - Tamper-evident, HMAC-chained cryptographic audit logs exported to enterprise SIEM platforms.
* **Cryptographic Supply-Chain Assurance:**
  - End-to-end provenance pipelines using keyless Cosign attestations and SPDX Software Bill of Materials (SBOM).
  - OpenVEX vulnerability tracking eliminating false-positive alarms in corporate compliance scanners.
  - RFC 9116 compliant security vulnerability intake policies.

---

### 📐 Engineering Philosophy

1. **Depth Over Breadth:** Specialization in low-level networking, concurrency correctness, and data plane resilience rather than broad buzzword checklists.
2. **Fail-Closed by Design:** Security mechanisms must fail safely. Critical paths degrade gracefully without dropping customer traffic.
3. **Zero Unnecessary Dependencies:** Single static binaries over sprawling multi-container dependencies. If a feature can be solved with clean standard library Go and minimal memory allocations, it belongs in the core.
4. **Verifiable Trust:** Security claims must be backed by reproducible builds, 100% race detector cleanliness (`-race`), and public cryptographic signatures.

---

### 📬 Contact & Enterprise Inquiries

* **Enterprise & Architecture Inquiries:** [ms2323513@gmail.com](mailto:ms2323513@gmail.com)
* **LinkedIn:** [linkedin.com/in/mohamed--sameh](https://www.linkedin.com/in/mohamed--sameh)
* **Twitter / X:** [@MohamedSam7238](https://x.com/MohamedSam7238)
* **GitHub:** [@mo7med20](https://github.com/mo7med20)
* **Platform Documentation:** [GateCore Architecture & Source](https://github.com/mo7med20/gatecore)
