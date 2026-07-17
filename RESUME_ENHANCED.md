# HITESH YADAV
**Delhi, India** | **+91 81681 48782** | **kunjeyanhitesh13@gmail.com**  
**LinkedIn:** [linkedin.com/in/hiteshyadav6713](https://www.linkedin.com/in/hiteshyadav6713) | **GitHub:** [github.com/beast6713](https://github.com/beast6713)

---

## **PROFESSIONAL SUMMARY**
Detail-oriented and security-focused **Computer Science Engineering Student** specializing in **Cybersecurity and Full-Stack Development**. Proficient in building high-performance, modular software engines and robust full-stack applications with a security-first mindset. Experienced in implementing secure architectures, containerization, network scanning tools, and digital forensic applications. Strongly committed to the principles of Zero-Trust and the Secure Software Development Lifecycle (SSDLC).

---

## **EDUCATION**
* **SRM Institute of Science & Technology (SRM IST)**, Chennai, Tamil Nadu
  * *Bachelor of Technology (B.Tech) in Computer Science Engineering (Specialization in Cybersecurity)*
  * **Expected Graduation:** May 2028  
  * **GPA:** **9.52/10** (Outstanding)
  * **Relevant Coursework:** Network Security Fundamentals, Operating Systems & Linux Kernel Internals, Data Structures & Algorithms, Object-Oriented Programming (C++/Python), Relational Databases (PostgreSQL/MySQL), Digital Forensics & Incident Response, Web Architecture & SSDLC.

---

## **TECHNICAL SKILLS**
* **Languages:** Python, Go (Golang), C++, TypeScript, JavaScript (ES6+), HTML5, CSS3, Bash/Shell Scripting
* **Frameworks & Libraries:** React.js, Next.js (App Router & SSR), Node.js, Express.js, Flutter
* **Databases & Caching:** PostgreSQL, Redis, MongoDB, MySQL, Supabase, SQLite
* **Tools & Platforms:** Git, GitHub, Docker & Docker Compose, Linux, AWS (foundational IAM/Security), Clerk (Auth), Firebase, Postman, Cloudinary
* **Cybersecurity & Forensics:** Digital Forensics, NTFS File Systems Analysis, Packet Analysis (Wireshark/TShark), Vulnerability Assessment (Nmap, Burp Suite), Socket Programming (TCP/UDP), OWASP Top 10 Mitigation, JWT & RBAC implementations

---

## **PROJECTS & OPEN SOURCE**

### **1. IP-Sentinel (IP Intelligence Platform)**
* *Enterprise-grade, modular, Clean Architecture unified cybersecurity platform for real-time IP threat intelligence.*
  * **Backend Engineering:** Architected and implemented a high-performance backend in **Go (Golang)** using Clean Architecture principles, ensuring strict decoupling of application logic and provider adapters.
  * **Parallel Investigation Engine:** Developed concurrent querying workers to fetch and normalize intelligence from multiple source providers (WHOIS, RDAP, DNS, custom threat APIs) simultaneously, accelerating analysis.
  * **Real-time SOC Dashboard:** Built a responsive operational control center UI using **Next.js (App Router)** and **Tailwind CSS**, featuring dynamic threat visualizations, geolocation origins, and offending ASN metrics.
  * **High-Speed Caching:** Integrated a **Redis** caching layer to bypass redundant external API requests, resulting in sub-millisecond response times for cached threat audits.
  * **Infrastructure:** Deployed and orchestrated database and caching services using **Docker Compose**.
  * **Tech Stack:** Go (Golang), Next.js, TypeScript, Redis, PostgreSQL, Docker, Tailwind CSS, REST APIs.

### **2. MindEase – AI Mental Wellness Platform**
* *AI-assisted wellness web application providing personalized support, cognitive tracking, and workspace environments.*
  * **Full-Stack Architecture:** Built a modular React and Express-based application with robust backend REST APIs and a PostgreSQL database.
  * **LLM Integration:** Integrated **Google Gemini API** for context-aware chat, real-time emotion detection, and implemented strict crisis/safety input filtering.
  * **Interactive UI & Visuals:** Created a sensory relaxation workspace utilizing an **HTML5 Canvas** particle engine for custom stress-relief simulations.
  * **Productivity Engine:** Developed Pomodoro-based focus timers, session logging, and custom AI-driven task recommendations.
  * **Tech Stack:** React.js, TypeScript, Node.js, Express.js, PostgreSQL, Docker, Google Gemini API, Tailwind CSS.

### **3. PortFootprint – Multi-Threaded TCP Port Scanner & Fingerprinter**
* *Cross-platform TCP network diagnostic and service banner-grabbing CLI tool.*
  * **High-Concurrency Scanner:** Developed a multi-threaded TCP connect scan engine in **Python** using `ThreadPoolExecutor`, reducing scan latency by **60%+** across targeted ranges.
  * **Service Fingerprinting Registry:** Designed a priority-based registry pattern to match socket welcome strings and run custom ASCII protocol probes (HTTP, SSH, FTP, SMTP, databases).
  * **Advanced Reporting:** Built an export registry supporting structured JSON logs, flat CSV spreadsheets, and a responsive **HTML/CSS report dashboard** with built-in dark mode and interactive filter menus.
  * **Differential Auditing:** Implemented scan comparisons (`--compare`) to dynamically identify newly opened/closed ports or changed service versions between two scans.
  * **Tech Stack:** Python, Socket Programming, Concurrency, HTML5/CSS3, JSON/CSV Reporting.

### **4. VulnReconX – Cybersecurity Reconnaissance & Scanning Framework**
* *Modular reconnaissance and vulnerability scanning framework designed around Clean Architecture and a registry-driven plugin model.*
  * **Clean Architecture & SOLID:** Engineered the scanning framework with explicit boundary contracts separating core domain logic from external scanning plugins (e.g. port scanners, DNS resolvers).
  * **Extensible Plugin Registry:** Implemented a dynamic registry pattern using manifest specifications (`manifest.yaml`) to discover, validate, and load builtin and external plugins at runtime.
  * **Robust Schema Validation:** Enforced strict target schema checking and routing configurations to handle exceptions and run automated target preflight checks.
  * **Unified Exporters:** Formulated structured reporting models and reporter contracts (HTML, JSON, PDF) to output consistent audits across different security plugin scanners.
  * **Tech Stack:** Python, Pytest, PyYAML, SOLID Principles, CLI Routing, Clean Architecture.

### **5. NTFS Forensic Recovery Tool**
* *Digital forensics application to parse raw NTFS disk images and extract deleted artifacts.*
  * **Low-Level Parsing:** Developed a standalone tool in **Python** that bypasses standard OS APIs to directly scan raw disk images.
  * **Metadata Extraction:** Parsed the NTFS **Master File Table (MFT)** to reconstruct directory trees and fetch raw file records.
  * **Advanced Carving:** Programmed fragmented file reconstruction using NTFS runlist decoding and signature-based file carving (magic numbers).
  * **Evidence Integrity:** Incorporated SHA-256 and MD5 hashing algorithms to compute file signatures, guaranteeing forensic integrity.
  * **Tech Stack:** Python, Digital Forensics, Binary Parsing, NTFS Internals, JSON Reporting.

### **6. Velocity Builder – No-Code Website Builder**
* *Interactive drag-and-drop website assembly platform with instant hosting capabilities.*
  * **Complex State Management:** Built a robust layout engine in React with Vite, employing state history tracking (Undo/Redo) and optimizing performance for large layouts.
  * **Visual Customization:** Implemented live CMS-style collection tables, theme customizations, and interactive previews.
  * **One-Click Publishing:** Integrated the **Netlify API** to compile visual designs into static code and publish them live instantly.
  * **Tech Stack:** React.js, Vite, Tailwind CSS, Netlify API, DnD Kit, Local Storage.

### **7. Royal Stitch Market – Multi-Vendor Marketplace**
* *Bespoke apparel and custom tailoring e-commerce application.*
  * **Role-Based Access Control:** Configured secure authorization boundaries (`Customer` vs. `Tailor/Admin`) using Clerk and Supabase middleware.
  * **Dashboard Analytics:** Developed vendor-facing control panels to track sales metrics, coordinate orders, and manage inventory list prices.
  * **Security & Reliability:** Implemented stateless order verification and input sanitization via **Zod schema validations** to mitigate XSS and SQL injection.
  * **Tech Stack:** Next.js, TypeScript, Supabase, PostgreSQL, Clerk, Cloudinary, Tailwind CSS.

---

## **HONORS & ACHIEVEMENTS**
* **3rd Place:** Capture The Flag (CTF) Cyber Security Competition, SRM IST.
* **Participant:** Smart India Hackathon (SIH) 2025.
* **Participant:** VITAP Hackathon Competition 2026.
* **Open Source Contributor:** Maintain active contribution streaks on GitHub, building tools and contributing documentation.
