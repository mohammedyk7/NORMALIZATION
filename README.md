#  DATABASE NORMALIZATION REPORT

This repository contains a comprehensive study and application of **Database Normalization** techniques from real-world business scenarios.

##  Objectives
- Understand and apply the rules of **1NF**, **2NF**, and **3NF** to unnormalized datasets.
- Solve normalization problems step-by-step using actual business data from 7 different systems.
- Provide **descriptive documentation** on normalization types with examples.
- Explain the concept of **De-normalization**, its purpose, and use cases.

---

##  Contents

| File Name                          | Description                                               |
|-----------------------------------|-----------------------------------------------------------|
| `Case1_2_3_Normalization_FIXED.pdf` | Detailed normalization for Company, University, Airline systems |
| `Normalization_Theory_Report.pdf` | Self-descriptive theory of 1NF, 2NF, 3NF + De-normalization |

---

##  Normalization Overview

| Normal Form | Description |
|-------------|-------------|
| **1NF**     | Atomic values only — no multivalued or repeating groups |
| **2NF**     | Removes partial dependencies (composite keys) |
| **3NF**     | Removes transitive dependencies (non-key depending on another non-key) |

---

##  Case Studies

1. **Company System** — normalized to 3NF due to transitive dependency on Manager  
2. **University System** — normalized to 3NF due to Advisor depending on Department  
3. **Airline System** — normalized to 2NF; no transitive dependency present

Each case includes:
- UNF (unnormalized table)
- Step-by-step conversion to 1NF, 2NF, and 3NF
- Separate entity tables with clean structure

---

##  De-Normalization

Sometimes, performance matters more than purity:
- **Why?**: Reduce joins, improve read speed in OLAP/analytics
- **When?**: In reporting databases, caching layers, or read-heavy environments

---

##  Tools Used

- Python (Pandas, FPDF) for generating tables and reports
- GitHub for version control and documentation
- Excel for structured tabulation and tracking transformations

---

##  Author
**MoHammed Yusuf Alkhusaibi**  
Data modeling | Software development | Engineering logic

---

>  You can clone this repo, study the transformations, and use the examples for your own DBMS coursework or projects.
