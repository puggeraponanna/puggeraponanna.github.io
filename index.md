---
layout: page
title: About
---

<section class="hero-section">
  <span class="hero-cursor">$ <span class="hero-cursor-text"></span><span class="cursor-blink"></span></span>
  <h1>Crafting Scalable <span class="highlight">Backend</span> Systems</h1>
  <p class="hero-subtitle">9+ years of experience, architecting highly concurrent, event-driven distributed systems, high-throughput data pipelines, and cloud-native architectures.</p>
  <div class="hero-meta">
    <span class="hero-badge">
      <span class="material-symbols-outlined">location_on</span>
      Bengaluru, India
    </span>
    <span class="hero-badge">
      <span class="material-symbols-outlined">code</span>
      Senior Backend Engineer
    </span>
  </div>
</section>

<section id="experience">
  <h2>Experience</h2>

  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-header">
        <h3>Oolio — Senior Software Engineer (Backend — Golang)</h3>
        <span class="timeline-date">Mar 2026 – Present</span>
      </div>
      <ul>
        <li><strong>Architected event-driven inventory depletion engine</strong> in Go (PostgreSQL, NATS JetStream) that auto-deducts stock from POS orders and production runs via a recipe/container cascade, with an idempotent Reserve - Commit - Reverse lifecycle safe against event replay and duplicate ingestion.</li>
        <li><strong>Built organization-level authorization</strong> for the Products API using Open Policy Agent (OPA) and ReBAC, extracting policies into a standalone Kubernetes sidecar and enforcing granular, location-scoped access control behind a feature flag with zero impact to existing tenants.</li>
        <li><strong>Delivered both systems on a domain-driven, hexagonal Go architecture</strong> with 600+ tests, including a testcontainer-backed integration suite (real PostgreSQL + NATS) for end-to-end correctness.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3>ANZ — Software Engineer (Backend — Golang, Python)</h3>
        <span class="timeline-date">Feb 2024 – Feb 2026</span>
      </div>
      <ul>
        <li><strong>Architected event-driven data pipeline</strong> in Go on Cloud Run (Terraform IaC) that decouples systems via Pub/Sub events, parsing and loading into BigQuery to enable async processing, analytics, and data product consumption across teams.</li>
        <li><strong>Built scalable data products</strong> using dbt transformations on BigQuery, delivering standardized datasets that accelerated reporting and experimentation for multiple consumption teams.</li>
        <li><strong>Engineered CI/CD pipelines</strong> with GitHub Actions, automating deployments and proof-gathering to cut release turnaround time and boost deployment reliability.</li>
        <li><strong>Rewrote legacy Java loan simulation tool</strong> in Go, enhancing maintainability and enabling rapid validation of credit decision rulesets for analytics generation.</li>
        <li><strong>Implemented Cloud Run-based validation system</strong> using Jupyter Notebooks to verify post-credit-decision loan outcomes, ensuring data integrity across pipelines.</li>
        <li><strong>Developed gRPC APIs</strong> and extended credit decisioning system features, supporting new lending scenarios with improved security and performance.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3>Sequoia — Backend Engineer (Golang, Python, Node)</h3>
        <span class="timeline-date">Dec 2021 – Feb 2024</span>
      </div>
      <ul>
        <li><strong>Architected and implemented backend service</strong> for employment offer management system in Go and MongoDB, orchestrating end-to-end lifecycle from offer creation through digital acceptance.</li>
        <li><strong>Engineered Redis-MongoDB hybrid caching layer</strong>, reducing query latency and database load while maintaining data consistency across distributed microservices.</li>
        <li><strong>Designed state machine-based workflow engine</strong> with event-driven callbacks, enabling complex multi-stage offer approval processes with automated notifications.</li>
        <li><strong>Established comprehensive unit testing framework</strong> with CI integration, improving code coverage and enabling rapid feature iteration with confidence.</li>
        <li><strong>Built production-grade client-side encryption system</strong> for S3 document storage with secure one-time access links, including zero-downtime migration tooling for existing files.</li>
        <li><strong>Implemented high-performance goroutine worker pool</strong> with dynamic scaling and graceful shutdown, improving document generation throughput by 3x while preventing resource exhaustion.</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3>Juspay — Software Development Engineer (Haskell)</h3>
        <span class="timeline-date">Jun – Dec 2021</span>
      </div>
      <ul>
        <li><strong>Architected event-driven, OCEN-compliant loan origination system</strong> in Haskell utilizing Redis Streams for asynchronous processing, orchestrating complex integrations across loan service providers, account aggregators, and credit bureaus for real-time borrower assessment.</li>
        <li><strong>Built a flexible business rule engine</strong> with configurable decision trees, enabling lenders to define custom credit policies while maintaining regulatory compliance and audit trails.</li>
        <li><strong>Re-engineered loan application onboarding flow</strong> with progressive disclosure and intelligent form validation, achieving improvements in completion rate (27% to 91%).</li>
      </ul>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3>Aurigo — Senior Software Engineer (C#)</h3>
        <span class="timeline-date">Jun 2017 – May 2021</span>
      </div>
      <ul>
        <li><strong>Architected end-to-end state contract procurement platform</strong>, automating bidding workflows and ensuring seamless, real-time financial synchronization with legacy systems.</li>
        <li><strong>Optimized unit price search</strong> via advanced caching, significantly reducing search latency and enhancing bid preparation efficiency for department stakeholders.</li>
      </ul>
    </div>

  </div>
</section>

<section id="skills">
  <h2>Skills</h2>

  <div class="skills-grid">

    <div class="skill-category">
      <h3>Languages</h3>
      <div class="skill-tags">
        <span class="skill-tag">Golang</span>
        <span class="skill-tag">Python</span>
        <span class="skill-tag">Haskell</span>
        <span class="skill-tag">C#</span>
        <span class="skill-tag">JavaScript</span>
        <span class="skill-tag">SQL</span>
        <span class="skill-tag">Bash</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>Frameworks &amp; Runtimes</h3>
      <div class="skill-tags">
        <span class="skill-tag">Gin</span>
        <span class="skill-tag">Chi</span>
        <span class="skill-tag">FastAPI</span>
        <span class="skill-tag">Flask</span>
        <span class="skill-tag">Node</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>Cloud &amp; Tooling</h3>
      <div class="skill-tags">
        <span class="skill-tag">GCP</span>
        <span class="skill-tag">AWS</span>
        <span class="skill-tag">Cloud Run</span>
        <span class="skill-tag">Kubernetes</span>
        <span class="skill-tag">Docker</span>
        <span class="skill-tag">Pub/Sub</span>
        <span class="skill-tag">Kinesis</span>
        <span class="skill-tag">NATS</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>AI-Assisted Development</h3>
      <div class="skill-tags">
        <span class="skill-tag">Claude</span>
        <span class="skill-tag">Gemini</span>
        <span class="skill-tag">AI-Integrated Testing</span>
        <span class="skill-tag">Prompt Engineering</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>Databases</h3>
      <div class="skill-tags">
        <span class="skill-tag">BigQuery</span>
        <span class="skill-tag">Spanner</span>
        <span class="skill-tag">PostgreSQL</span>
        <span class="skill-tag">MySQL</span>
        <span class="skill-tag">MongoDB</span>
        <span class="skill-tag">Redis</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>Data &amp; ETL</h3>
      <div class="skill-tags">
        <span class="skill-tag">Apache Beam</span>
        <span class="skill-tag">dbt</span>
        <span class="skill-tag">Jupyter Notebooks</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>Workflows &amp; Orchestration</h3>
      <div class="skill-tags">
        <span class="skill-tag">Temporal</span>
      </div>
    </div>

    <div class="skill-category">
      <h3>APIs &amp; Messaging</h3>
      <div class="skill-tags">
        <span class="skill-tag">gRPC</span>
        <span class="skill-tag">REST</span>
        <span class="skill-tag">Protobuf</span>
        <span class="skill-tag">WebSockets</span>
        <span class="skill-tag">OAuth/JWT</span>
      </div>
    </div>

  </div>
</section>

<section id="education">
  <h2>Education</h2>

  <div class="education-card">
    <h3>Sri Jayachamarajendra College of Engineering</h3>
    <p class="edu-degree">B.E. in Electronics and Communication</p>
    <p class="edu-date">Aug 2013 – May 2017</p>
    <p class="edu-gpa">CGPA: 8.59 / 10</p>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>

  <div class="contact-section">
    <p>Currently pushing code from <strong>Bengaluru, India</strong>. Let's connect.</p>

    <div class="contact-buttons">
      <a href="mailto:ponannapuggera@gmail.com" class="contact-btn">
        <span class="material-symbols-outlined">mail</span>
        Email
      </a>

      <a href="https://www.linkedin.com/in/puggeraponanna/" target="_blank" class="contact-btn" rel="noopener">
        <span class="material-symbols-outlined">link</span>
        LinkedIn
      </a>

      <a href="https://github.com/puggeraponanna" target="_blank" class="contact-btn" rel="noopener">
        <span class="material-symbols-outlined">code</span>
        GitHub
      </a>
    </div>
  </div>
</section>
