# MiddleBase — Central Clinical Data Middleware

**MiddleBase** is a centralized middleware platform developed by the **Research Institute for Oncology, Hematology, and Cell Therapy (RIOHCT)**, Tehran University of Medical Sciences. It acts as an integration layer for connecting various clinical data sources such as hospital registries, population-based registries, HIS, LIS, and external applications.

---

## Overview

MiddleBase enables:

- **Data Integration:** Consolidates patient data from multiple sources into one system.
- **Interoperability:** Ensures seamless communication between systems through APIs and ETL pipelines.
- **Registry Integration:** Standardizes and routes data to specific disease or treatment registries.
- **Version Control & Audit:** Tracks changes, maintains historical records, and ensures compliance.
- **Middleware Intelligence:** Routes and validates data for clinical pathway execution.

---

## Getting Started

### Prerequisites

- **Python 3.10+** (for testing scripts).
- **Database:** PostgreSQL or MariaDB (for registry integration).
- **Optional:** Docker for containerized deployment.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/RIOHCT/middlebase.git
cd middlebase
