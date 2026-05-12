Executive Summary:
This project showcases the architecture and logic used to monitor high-volume transaction streams. In a professional production setting, this framework was deployed to audit over thousands of transactions per period, successfully flagging suspicious activities with a high recall rate to ensure financial security and operational integrity.

Key Features & Capabilities:
- Granular Risk Scoring: Implements a multi-level classification system: Normal, Suspicious, High Risk, and Very High Risk.
- Multi-Channel Logic: Specialized detection patterns for different payment methods, including QRIS anomaly detection and digital wallet velocity checks.
- Optimized Data Pipeline: Re-engineered legacy monthly analysis into daily batch processing, enabling faster response times to emerging fraud patterns.
- Stakeholder Reporting: Automated generation of transaction summaries that prioritize critical threats for manual investigation.

Technical Architecture
The framework is built upon a robust data engineering foundation:
- Data Ingestion: Aggregating raw logs from fragmented sources into a centralized database environment.
- Schema Design: Implementation of aggregated summary tables to improve query performance by 75% during deep-dive audits.
- Behavioral Analysis: Using Jupyter Notebooks to perform temporal analysis and identify outliers in transaction amounts and frequencies.

Performance Metrics (Production Benchmarks)
The following metrics reflect the impact of the logic implemented within this framework:
- Detection Ratio: Consistently identified 35% to 49% of total transaction volume as high-priority for investigation.
- Scalability: Capable of processing and auditing 30,000 - 50,000+ records per automated cycle.
- Operational Speed: Transitioning to daily processing improved data freshness by 30x compared to legacy monthly workflows.

Disclaimer
Note: This repository contains the architectural design, generic schemas, and conceptual logic. To comply with Non-Disclosure Agreements (NDA) and data privacy regulations, all sensitive business rules, private company data, and proprietary source codes have been removed or anonymized.
