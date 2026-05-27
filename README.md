# Core Network Analyzer (CNA)

Core Network Analyzer (CNA) is an Open Source telecom traffic analysis platform developed and maintained by PAiCore Technology.

The platform is focused on signaling visibility, trace analysis, protocol correlation, and operational troubleshooting across multiple telecom protocols and network layers.

The CNA ecosystem provides a modular architecture composed of independent services responsible for ingestion, ETL processing, analytics, database operations, and data presentation.

---

# Features

- Telecom traffic analysis
- Modular microservice architecture
- ETL processing pipeline
- Protocol correlation and analytics
- Reporting and visualization
- Scalable data ingestion
- Open Source CNA ecosystem
- Signaling and operational troubleshooting support

---

# CNA Components

| Component | Description | Repository |
|---|---|---|
| Ingestion Service | Handles traffic ingestion and preprocessing | https://github.com/paicoretech/ingestion-service |
| Ingestor ETL | ETL and data transformation pipelines | https://github.com/paicoretech/ingestor-etl |
| Analytics Service | Analytics and correlation engine | https://github.com/paicoretech/analytics-service |
| Summary Presentation | Frontend presentation and reporting layer | https://github.com/paicoretech/summary-presentation |
| DB CNA Scripts | Database schema and maintenance scripts | https://github.com/paicoretech/db-cna-scripts |

---

# Architecture Overview

```text
Network Traffic / Signaling Data
                │
                ▼
        Ingestion Service
                │
                ▼
            ETL Pipeline
                │
                ▼
         Analytics Service
                │
                ▼
              Database
                │
                ▼
      Summary Presentation UI
```

---

# Deployment

Each CNA component is maintained independently and contains its own deployment instructions and requirements.

Please refer to each repository documentation for:
- Installation
- Build instructions
- Runtime configuration
- Deployment guidelines
- Environment setup

---

# Open Source Release

This repository acts as the umbrella project for the CNA Open Source ecosystem and centralizes access to all public CNA components.

---

# About PAiCore Technology

PAiCore Technology develops telecom signaling platforms and Open Source core network technologies focused on interoperability, scalability, telecom messaging, signaling visibility, and network analytics.

Website:
https://paicore.tech

---

# License

This project is released under the AGPL-3.0 License.

