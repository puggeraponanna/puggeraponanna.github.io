---
layout: page
title: About
---


## About Me
I am a Backend Software Engineer with over 7 years of experience in building scalable systems, microservices, and cloud-native applications. My core expertise lies in **Golang**, **Python**, **Haskell**, and **C#**.

Throughout my career, I have worked on diverse domains ranging from fintech to construction management. I have a proven track record of designing and implementing complex event-driven architectures, optimizing performance for high-throughput systems, and building secure, reliable APIs. I am passionate about writing clean, maintainable code and leveraging modern cloud technologies to solve real-world problems.

## Experience

<div class="card" markdown="1">
### ANZx - Software Engineer (Backend - Golang)
*Feb 2024 – Present*
- Designed and implemented an event broker system using temporal workflows, that runs on a schedule to fetch data from AWS Kinesis, process it and store it in bigquery to be used for analytics and other dependent systems.
- Built a validation system that runs on Cloudrun to execute jupyter notebooks to validate the loan outcomes after credit decisioning is complete.
- Built a loan simulation tool to submit different types of loans to the credit decision system in order to run validations on the credit decision rulesets and also generate data for analytics.
- Setup GHA workflows to automate different tasks like dependency management using renovate, automated releases to GCP, running automated pre-deployment tests etc.
- Worked on building new APIs using gRPC and enhancing the existing features of the credit decision system.
</div>

<div class="card" markdown="1">
### Sequoia - Software Development Engineer (Backend - Golang)
*Dec 2021 – Feb 2024*
- Built the client side encryption framework for storing files on Amazon S3 and a mechanism to access them using one time links, and also built a tool to handle migration of existing files.
- Developed a common logging library which improved traceability of requests across different services using opensearch.
- Built a caching library using redis that works with mongodb to make data reads faster.
- Built a custom worker pool mechanism using goroutines to process parallel jobs which improved the speed of document generation.
- Built a reverse proxy service equipped with a rate limiter that can be configured based on custom rules to manage the security of publicly accessible APIs.
</div>

<div class="card" markdown="1">
### Juspay - Software Development Engineer (Backend - Haskell)
*Jun 2021 - Dec 2021*
- Worked on building a loan service provider product based on the OCEN(Open Credit Enablement Network) standards.
- Designed and built the lending service that integrates with loan service provider, account aggregators and credit bureaus to fetch the details of the borrower.
- Built the business rule engine that makes credit decisions on the borrower data based on rules set by the lenders.
- Worked on revamping the user onboarding experience for the loan application which increased the onboarding rate of customers.
</div>

<div class="card" markdown="1">
### Aurigo Software Technologies - Senior Software Engineer (Backend - C#)
*Jun 2017 - May 2021*
- Built the Bid Management module for Aurigo Masterworks to automate the online bidding process.
- Integrated Masterworks with the Oracle finance management system to enable seamless flow of financial transaction data between the two systems.
- Built a windows service based scheduling system to automate the sending and retrieval of data for integration.
- Improved the performance of existing SSRS reports and dashboards in Masterworks by optimizing SQL queries.
</div>

## Education

<div class="card" markdown="1">
### Sri Jayachamarajendra College of Engineering
**B.E. in Electronics and Communication**
*Aug 2013 – May 2017*
CGPA: 8.59/10
</div>

## Skills
<ul class="skills-list">
<li class="skill-languages"><strong>Languages:</strong> Golang, Python, Haskell, C#, Javascript, SQL, Bash</li>
<li class="skill-technologies"><strong>Technologies:</strong> Docker, MongoDB, gRPC, REST, GCP, AWS, Bigquery, Spanner, PostgreSQL, Temporal, Redis, Kubernetes</li>
</ul>

## Contact
<div class="contact-section">
  <p class="contact-intro">I am currently based in <strong>Bengaluru, India</strong>. Feel free to reach out!</p>
  
  <div class="contact-buttons">
    <a href="mailto:ponannapuggera@gmail.com" class="contact-btn">
      <span class="material-symbols-outlined">mail</span>
      <span class="contact-btn-text">
        <span class="contact-btn-label">Email</span>
        <span class="contact-btn-value">ponannapuggera@gmail.com</span>
      </span>
    </a>
    
    <a href="https://www.linkedin.com/in/puggeraponanna/" target="_blank" rel="noopener noreferrer" class="contact-btn">
      <span class="material-symbols-outlined">work</span>
      <span class="contact-btn-text">
        <span class="contact-btn-label">LinkedIn</span>
        <span class="contact-btn-value">puggeraponanna</span>
      </span>
    </a>
    
    <a href="https://github.com/puggeraponanna" target="_blank" rel="noopener noreferrer" class="contact-btn">
      <span class="material-symbols-outlined">code</span>
      <span class="contact-btn-text">
        <span class="contact-btn-label">GitHub</span>
        <span class="contact-btn-value">puggeraponanna</span>
      </span>
    </a>
  </div>
</div>