---
layout: page
title: About
---


## About Me
Backend Software Engineer with expertise in Golang, Python, Haskell, and C#. Experienced in building scalable systems, microservices, and cloud-native applications.
Bengaluru, India | [ponannapuggera@gmail.com](mailto:ponannapuggera@gmail.com) | +91 8861312627

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
<li><strong>Languages:</strong> Golang, Python, Haskell, C#, Javascript, SQL, Bash</li>
<li><strong>Technologies:</strong> Docker, MongoDB, gRPC, REST, GCP, AWS, Bigquery, Spanner, PostgreSQL, Temporal, Redis, Kubernetes</li>
</ul>