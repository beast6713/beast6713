# HITESH YADAV
**Delhi, India | +91 81681 48782 | kunjeyanhitesh13@gmail.com**  
**LinkedIn:** [linkedin.com/in/hiteshyadav6713](https://www.linkedin.com/in/hiteshyadav6713) | **GitHub:** [github.com/beast6713](https://github.com/beast6713)  
**Portfolio:** [hitesh-portfolio-beast6713s-projects.vercel.app](https://hitesh-portfolio-beast6713s-projects.vercel.app)

---

## PROFESSIONAL SUMMARY
B.Tech Computer Science Engineering student specializing in Cybersecurity with academic distinction (9.52/10 GPA). Technical foundation in secure software engineering, network diagnostics, Linux system internals, and concurrent backend routing. Experienced in building CLI vulnerability validators, low-level disk parsers, and custom multi-threaded scanners. Seeking an entry-level Cloud, Security, Support, or Systems Engineer role at Tech Mahindra.

---

## EDUCATION
**SRM Institute of Science & Technology (SRM IST)**, Chennai, TN  
*Bachelor of Technology (B.Tech) in CSE (Specialization in Cybersecurity)*  
**Expected Graduation:** May 2028 | **CGPA:** 9.52 / 10.0 (Outstanding academic track)  
*Relevant Coursework:* Network Security, Operating Systems, Relational Databases, Digital Forensics & Incident Response, Web Architecture & SSDLC, Data Structures & Algorithms.

---

## TECHNICAL SKILLS
*   **Programming:** Python 3.12+, Go (Golang), C++, TypeScript, JavaScript (ES6+), Bash/Shell
*   **Cybersecurity & Auditing:** NTFS Binary Carving, Wireshark/TShark Packet Inspection, Nmap Port Auditing, Burp Suite Web Auditing, OWASP ZAP API, JWT Rotation, RBAC
*   **Networking & Systems:** TCP/UDP Socket Programming, System Log Analysis, Troubleshooting, Linux System Administration, DNS, DHCP, HTTP/HTTPS
*   **Cloud & Infrastructure:** Docker, Docker Compose, GitHub Actions (CI/CD), AWS IAM Basics
*   **Databases:** PostgreSQL, Redis, MongoDB, MySQL, SQLite

---

## FEATURED PROJECTS

### 1. HTTP Security Assessment Framework (v2.0.0)
*Python, Playwright, OWASP ZAP, Pytest*
*   **Architecture & Quality:** Designed a unified Single Source of Truth architecture (`AssessmentResult`) achieving **92.24% line coverage** across 130 unit tests with strict `mypy` typing and zero static lint errors (`ruff`).
*   **Multi-Engine Pipeline:** Engineered a crawler engine, AST security header validator (HSTS/CSP/XFO/XCTO), passive TLS/cookie analyzer, and weighted risk scoring engine.
*   **Browser & ZAP Integration:** Programmed Playwright headless browser checks for DOM element verification and integrated the OWASP ZAP API for findings cross-validation.
*   **Active Verification & Safety:** Programmed safe Reflected XSS parameter verification with rate limiting and custom `SafetyPolicy` safeguards.

### 2. IP-Sentinel (IP Intelligence Platform)
*Go (Golang), Next.js, Redis, PostgreSQL, Docker*
*   **Clean Backend:** Architected a high-concurrency threat investigation engine in Go (Golang) using Clean Architecture to decouple core domain logic from provider adapters.
*   **Parallel Investigation Engine:** Developed concurrent workers using goroutines to query and normalize IP intelligence from multiple APIs (WHOIS, RDAP, DNS) simultaneously.
*   **Caching & Analytics:** Configured a Redis caching tier to bypass redundant external requests, achieving sub-millisecond threat audit resolution.
*   **SOC Dashboard:** Developed a Next.js (App Router) operational dashboard with dynamic threat visualizations, geolocation origins, and offending ASN metrics.

### 3. PortFootprint Scanner
*Python, Socket API, Threading, JSON/CSV Reporting*
*   **High-Concurrency Scanner:** Developed a multi-threaded TCP connect scan engine in Python using `ThreadPoolExecutor`, reducing scan latency by **60%+** across targeted ports.
*   **Service Fingerprinting:** Designed a priority-based registry pattern to match socket welcome strings and run custom ASCII protocol checks (HTTP, SSH, FTP, SMTP).
*   **Structured Reporting:** Programmed an export registry supporting structured JSON logs, flat CSV spreadsheets, and a responsive HTML/CSS report dashboard.

### 4. NTFS Forensic Artifact Carving Tool
*Python, Binary Carving, NTFS Internals*
*   **Low-Level Parsing:** Built a low-level forensic tool in Python that directly scans raw disk images by bypassing standard OS file system APIs.
*   **Metadata Extraction:** Parsed NTFS Master File Table (MFT) raw sectors, runlist data structures, and signatures to carve and rebuild deleted file records.
*   **Evidence Integrity:** Integrated SHA-256 and MD5 hashing algorithms to compute file signatures, guaranteeing forensic integrity.

---

## CERTIFICATIONS
*   **Cybersecurity Specialization Track** | SRM Institute of Science & Technology | 2026
*   **Enterprise Clean Architecture & DDD** | Independent Software Review Board | 2026
*   **DevOps & CI/CD Pipeline Engineering** | Open Source Community | 2026

---

## HONORS & ACHIEVEMENTS
*   **3rd Place:** Capture The Flag (CTF) Cyber Security Competition, SRM IST (2025)
*   **Participant:** Smart India Hackathon (SIH) 2025 (Developed secure backend prototype)
*   **Participant:** VITAP Hackathon Competition 2026
