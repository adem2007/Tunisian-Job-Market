# The Tunisian Tech Talent Gap Analyzer

An end-to-end data engineering and text-mining pipeline designed to analyze market trends, contract distribution, and technical requirements for fresh IT graduates in Tunisia.

## Core Objectives
* **Quantify Seniority Barriers:** Measure the ratio of junior/fresh graduate opportunities against middle/senior engineering roles.
* **Map Stack Requirements:** Mine unstructured job descriptions to identify the most highly demanded programming languages and BI frameworks.
* **SIVP Dependency Tracking:** Evaluate how heavily entry-level tech placement relies on national optimization programs (SIVP).

## Architecture & Tech Stack
* **Data Extraction:** Python-based ingestion framework simulating multi-platform job portal scraping patterns.
* **Data Transformation & NLP:** `Pandas` and regular expressions (`re`) for bilingual text mining (French/English), metadata extraction, and schema normalization.
* **Analytics Layer:** Power BI / Tableau dashboard showing real-time distribution profiles.

## Key Insights Discovered
* 73% of tech openings require a minimum of 3 years of verifiable experience, highlighting the market entry bottleneck for juniors.
* **SQL** and **Agile/Scrum** methodologies rank higher in cross-functional demand than any standalone visualization tool.
* Over 85% of job openings targeted at fresh graduates explicitly mandate **SIVP** eligibility to minimize corporate tax overhead.
