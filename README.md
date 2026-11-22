# Abdelrahman Abouzed

**Systems & Backend Engineer** — Network Protocols • Systems Automation • Resilient Runtimes  
Mansoura, Egypt • Open to Worldwide Remote Engineering Roles & Relocation  
[Email](mailto:abdelrahman.abuzed@gmail.com) • [GitHub](https://github.com/abdelrahmanabuzed-onepice) • [LinkedIn](https://linkedin.com/in/abdelrahmanabuzed)

---

### Engineering Focus

I engineer backend systems, low-level network diagnostic tooling, and deterministic automation daemons. My work emphasizes protocol compliance (TCP/UDP, SMTP, SOCKS5), socket resilience, process supervision, and private, air-gapped LLM runtime integration.

- **Network Systems & Protocols:** Raw socket probing, SMTP/IMAP transaction engines, multi-provider DNSBL reputation scanners, and proxy session healing with exponential backoff.
- **Runtimes & Concurrency:** Multi-threaded worker pools, asynchronous event-driven I/O (`asyncio`, `uvloop`), process lifecycle management, and SQLite performance tuning (WAL mode, memory-mapped I/O).
- **Offline Intelligence & Security:** Air-gapped threat intelligence pipelines, automated vulnerability reconnaissance, and local LLM execution via Ollama without third-party cloud data egress.

---

### Flagship Systems & Open Source Projects

#### 🌐 [Network Protocol & Intelligence Suite](https://github.com/abdelrahmanabuzed-onepice/network-protocol-suite)
High-throughput network diagnostic engine for TCP/SMTP service verification, multi-blacklist DNSBL audits, ASN routing analysis, and in-flight SOCKS5 session recovery.
- Measures sub-millisecond banner greeting latencies across SMTP/IMAP servers.
- Evaluates IP reputation in parallel across Spamhaus, Barracuda, and SpamCop.
- Built-in session healing worker with automatic proxy pool rotation upon transient socket drop.

#### 🛡️ [BugHunter AI — Local Security Workstation](https://github.com/abdelrahmanabuzed-onepice/bughunter-ai)
Air-gapped reconnaissance and threat intelligence desktop workstation powered by local LLMs (`qwen2.5`) and CustomTkinter.
- Orchestrates multi-phase target profiling: DNS mapping, HTTP security headers, CORS verification, and ExploitDB correlation.
- Runs 100% offline vulnerability triage through Ollama to prevent target telemetry leakage.
- Generates structured HTML and JSON executive audit reports.

#### ⚡ [Systems & Windows Forensics Toolkit](https://github.com/abdelrahmanabuzed-onepice/windows-forensics-toolkit)
Lightweight incident response and host telemetry engine for Windows environments.
- Inspects running process trees for suspicious argument patterns and execution policy bypasses.
- Parses Windows Security Event logs for brute-force logon bursts (Event ID 4625).
- Zero-dependency sanitization and indicator defanging for incident documentation.

#### 📦 [100 Modular Automation Arsenals](https://github.com/abdelrahmanabuzed-onepice)
A collection of 10 specialized, domain-driven engineering toolkits covering Windows systems administration, cybersecurity recon, network protocols, data pipelines, and developer productivity.

---

### Technical Arsenal

| Layer | Technologies & Disciplines |
|---|---|
| **Languages** | Python 3 (AsyncIO, Socket, Multiprocessing), Go, C, SQL, Bash, PowerShell |
| **Networking & Protocols** | TCP/IP, SOCKS5 (RFC 1928), SMTP (RFC 5321), DNS wire format, TLS/SSL, HTTP/1.1 & HTTP/2 |
| **Systems & Architecture** | Linux & Windows Internals, Process Supervision, Async Event Loops, Memory Hygiene |
| **Storage & Engines** | SQLite3 (WAL mode, busy timeout, memory mapping), Redis (caching patterns), PostgreSQL |
| **Observability & Tools** | Wireshark, Git, cProfile, py-spy, Docker, Ollama Runtime Engine |

---

### Engineering Principles

1. **Zero Cloud Lock-in:** Tools are built to operate deterministically on bare-metal or private servers without mandatory external API subscriptions.
2. **Explicit Error Handling:** Network connections fail; systems crash. Every socket operation must incorporate timeout boundaries, explicit retries, and clean resource cleanup.
3. **Protocol-Level Understanding:** Prefer inspecting raw packet frames and socket states over trusting high-level, opaque abstractions.

---

### Curated Pinned Repositories

| # | Repository | Description | Key Focus |
|---|---|---|---|
| 1 | [network-protocol-suite](https://github.com/abdelrahmanabuzed-onepice/network-protocol-suite) | High-throughput SMTP banner diagnostics, DNSBL reputation audits, and resilient SOCKS5 healing. | Network Protocols, RFC 5321, SOCKS5, AsyncIO |
| 2 | [bughunter-ai](https://github.com/abdelrahmanabuzed-onepice/bughunter-ai) | Desktop security workstation pairing automated reconnaissance with offline local LLM triage. | Security Recon, Local AI, Ollama, SQLite |
| 3 | [windows-forensics-toolkit](https://github.com/abdelrahmanabuzed-onepice/windows-forensics-toolkit) | Host defense telemetry, suspicious process inspection, and Windows event log auditing. | Incident Response, Event Logs, Process Telemetry |
| 4 | [sysadmin-automation-arsenal](https://github.com/abdelrahmanabuzed-onepice/sysadmin-automation-arsenal) | Production system supervision, crash watchdog, storage hygiene, and service healing daemons. | SysAdmin, Service Supervision, Process Health |
| 5 | [cybersecurity-recon-toolkit](https://github.com/abdelrahmanabuzed-onepice/cybersecurity-recon-toolkit) | Multi-threaded port probing, service fingerprinting, OSINT, and attack surface enumeration. | Port Scanner, OSINT, TCP Probing |
| 6 | [everyday-dev-tools](https://github.com/abdelrahmanabuzed-onepice/everyday-dev-tools) | Zero-dependency standalone Python utilities for daily system administration and developer workflows. | Developer Ergonomics, Zero Dependencies, CLI |
