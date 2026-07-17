---
layout: page
title: About
---


<section class="hero-section">
  <h1>Crafting Scalable <span class="highlight">Backend</span> Systems</h1>
  <p class="hero-subtitle">9+ years of experience, architecting highly concurrent, event-driven distributed systems, high-throughput data pipelines, and cloud-native architectures.</p>
</section>

<div id="experience"></div>

## Experience

<div class="card" markdown="1">
### Oolio - Senior Software Engineer (Backend - Golang)
*Mar 2026 – Present*
- **Architected event-driven inventory depletion engine** in Go (PostgreSQL, NATS JetStream) that auto-deducts stock from POS orders and production runs via a recipe/container cascade, with an idempotent Reserve - Commit - Reverse lifecycle safe against event replay and duplicate ingestion.
- **Built organization-level authorization** for the Products API using Open Policy Agent (OPA) and ReBAC, extracting policies into a standalone Kubernetes sidecar and enforcing granular, location-scoped access control behind a feature flag with zero impact to existing tenants.
- **Delivered both systems on a domain-driven, hexagonal Go architecture** with 600+ tests, including a testcontainer-backed integration suite (real PostgreSQL + NATS) for end-to-end correctness.
</div>

<div class="card" markdown="1">
### ANZ - Software Engineer (Backend - Golang, Python)
*Feb 2024 – Feb 2026*
- **Architected event-driven data pipeline** in Go on Cloud Run (Terraform IaC) that decouples systems via Pub/Sub events, parsing and loading into BigQuery to enable async processing, analytics, and data product consumption across teams.
- **Built scalable data products** using dbt transformations on BigQuery, delivering standardized datasets that accelerated reporting and experimentation for multiple consumption teams.
- **Engineered CI/CD pipelines** with GitHub Actions, automating deployments and proof-gathering to cut release turnaround time and boost deployment reliability.
- **Rewrote legacy Java loan simulation tool** in Go, enhancing maintainability and enabling rapid validation of credit decision rulesets for analytics generation.
- **Implemented Cloud Run-based validation system** using Jupyter Notebooks to verify post-credit-decision loan outcomes, ensuring data integrity across pipelines.
- **Developed gRPC APIs** and extended credit decisioning system features, supporting new lending scenarios with improved security and performance.
</div>

<div class="card" markdown="1">
### Sequoia - Backend Engineer (Backend - Golang, Python, Node)
*Dec 2021 – Feb 2024*
- **Architected and implemented backend service** for employment offer management system in Go and MongoDB, orchestrating end-to-end lifecycle from offer creation through digital acceptance.
- **Engineered Redis-MongoDB hybrid caching layer**, reducing query latency and database load while maintaining data consistency across distributed microservices.
- **Designed state machine-based workflow engine** with event-driven callbacks, enabling complex multi-stage offer approval processes with automated notifications.
- **Established comprehensive unit testing framework** with CI integration, improving code coverage and enabling rapid feature iteration with confidence.
- **Built production-grade client-side encryption system** for S3 document storage with secure one-time access links, including zero-downtime migration tooling for existing files.
- **Implemented high-performance goroutine worker pool** with dynamic scaling and graceful shutdown, improving document generation throughput by 3x while preventing resource exhaustion.
</div>

<div class="card" markdown="1">
### Juspay - Software Development Engineer (Backend - Haskell)
*Jun 2021 - Dec 2021*
- **Architected event-driven, OCEN-compliant loan origination system** in Haskell utilizing Redis Streams for asynchronous processing, orchestrating complex integrations across loan service providers, account aggregators, and credit bureaus for real-time borrower assessment.
- **Built a flexible business rule engine** with configurable decision trees, enabling lenders to define custom credit policies while maintaining regulatory compliance and audit trails.
- **Re-engineered loan application onboarding flow** with progressive disclosure and intelligent form validation, achieving improvements in completion rate (27% to 91%).
</div>

<div class="card" markdown="1">
### Aurigo - Senior Software Engineer (Backend - C#)
*Jun 2017 - May 2021*
- **Architected end-to-end state contract procurement platform**, automating bidding workflows and ensuring seamless, real-time financial synchronization with legacy systems.
- **Optimized unit price search** via advanced caching, significantly reducing search latency and enhancing bid preparation efficiency for department stakeholders.
</div>

<div id="skills"></div>

## Skills

<ul class="skills-list">
<li><strong>Languages</strong> <span>Golang, Python, Haskell, C#, Javascript, SQL, Bash</span></li>
<li><strong>Frameworks/Runtimes</strong> <span>Gin, Chi, FastAPI, Flask, Node</span></li>
<li><strong>Cloud & Tooling</strong> <span>GCP, AWS, Cloud Run, Kubernetes, Docker, Pub/Sub, Kinesis, NATS</span></li>
<li><strong>AI-Assisted Development</strong> <span>Claude, Gemini, AI-Integrated Testing, Prompt Engineering</span></li>
<li><strong>Databases</strong> <span>BigQuery, Spanner, PostgreSQL, MySQL, MongoDB, Redis</span></li>
<li><strong>Data & ETL</strong> <span>Apache Beam, dbt, Jupyter Notebooks</span></li>
<li><strong>Workflows/Orchestration</strong> <span>Temporal</span></li>
<li><strong>APIs & Messaging</strong> <span>gRPC, REST, Protobuf, WebSockets, OAuth/JWT</span></li>
</ul>

<div id="education"></div>

## Education

<div class="card" markdown="1">
### Sri Jayachamarajendra College of Engineering
**B.E. in Electronics and Communication**
*Aug 2013 – May 2017*
CGPA: 8.59/10
</div>

<div id="contact"></div>

## Contact

<div class="contact-section">
  <p>Currently pushing code from <strong>Bengaluru, India</strong>. Let's connect.</p>
  
  <div class="contact-buttons">
    <a href="mailto:ponannapuggera@gmail.com" class="contact-btn">
      <span class="material-symbols-outlined">mail</span>
      <span>Email</span>
    </a>
    
    <a href="https://www.linkedin.com/in/puggeraponanna/" target="_blank" class="contact-btn">
      <span class="material-symbols-outlined">group</span>
      <span>LinkedIn</span>
    </a>
    
    <a href="https://github.com/puggeraponanna" target="_blank" class="contact-btn">
      <span class="material-symbols-outlined">code</span>
      <span>GitHub</span>
    </a>
  </div>
</div>