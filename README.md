# TenderIQ - A Bid Compliance & Evaluation System

**An intelligent platform for bid qualification, tender compliance verification, requirement traceability, and evaluation reporting.**

[![Interactive Demo](https://img.shields.io/badge/Interactive-3D_Demo-84BD00?style=for-the-badge)](https://saral2810.github.io/Bid-Compliance-System/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Saral2810/Bid-Compliance-System)

---

## 🌐 Interactive 3D Workflow

Explore the conceptual bid evaluation pipeline through an interactive 3D visualization.

### [▶ Launch Interactive 3D Demo](https://saral2810.github.io/Bid-Compliance-System/3d_bid_compliance_system.html)


---

## 📌 Project Overview

TenderIQ is a bid compliance and evaluation system designed to organize bidder submissions, evaluate requirement-level compliance, identify documentation gaps, and present qualification results through analytical dashboards.

### ✨ Key Features

- 📄 **Bid Evaluation:** Organizes tender requirements and bidder submissions.
- ✅ **Compliance Verification:** Presents exact, partial, non-matching, and non-applicable requirement matches.
- 🏆 **Bidder Qualification:** Summarizes qualified, at-risk, and disqualified bidders.
- 🔍 **Requirement Traceability:** Tracks compliance findings across bidders and individual requirements.
- ⚠️ **Gap Identification:** Highlights missing documents and potential compliance issues.
- 📊 **Evaluation Dashboards:** Visualizes compliance results, qualification summaries, and evaluation metrics.
- 🧊 **Interactive 3D Visualization:** Demonstrates the conceptual workflow through an interactive HTML experience.

---

## 📸 Dashboard Showcase

### 1. Overview

The main dashboard presents an overview of the bid evaluation results.

![Project Overview](Screenshots/Overview.png)

### 2. Bid Qualification Summary

Visualizes bidder qualification status, compliance percentages, and requirement-level findings.

![Bid Qualification Summary](Screenshots/Bid%20Qualification%20Summary.png)

### 3. Compliance Grid

Displays bidder-level compliance against tender requirements, helping identify missing or incomplete submissions.

![Compliance Grid](Screenshots/Compliance%20Grid.png)

### 4. Evaluation Methodology

Presents evaluation test results, requirement-match accuracy, and validation summaries.

![Evaluation Methodology](Screenshots/Evaluation%20Methodology.png)

### 5. Requirement Tracebility

Checks for Requirements of each bidder against the given tender and marks the percentage of completition.

![Evaluation Methodology](Screenshots/Requirement%20Tracebility.png)
---

## 🔄 System Workflow

The following diagram illustrates the conceptual flow of bid compliance evaluation, from document submission to evaluation reporting.

```mermaid
flowchart TD
    A["Tender / RFP Documents"] --> B["Requirement Extraction"]
    C["Bidder Submissions"] --> D["Document Processing"]

    B --> E["Requirement Mapping"]
    D --> E

    E --> F["Compliance Verification"]
    F --> G{"Requirement Match"}

    G --> H["Exact Match"]
    G --> I["Partial Match"]
    G --> J["Missing / Non-Compliant"]
    G --> K["Not Applicable"]

    H --> L["Compliance Analysis"]
    I --> L
    J --> L
    K --> L

    L --> M["Bidder Qualification Review"]
    M --> N["Risk & Gap Identification"]
    N --> O["Dashboard & Evaluation Report"]

    classDef input fill:#172554,stroke:#60a5fa,color:#ffffff
    classDef process fill:#164e63,stroke:#22d3ee,color:#ffffff
    classDef decision fill:#78350f,stroke:#fbbf24,color:#ffffff
    classDef output fill:#14532d,stroke:#4ade80,color:#ffffff

    class A,C input
    class B,D,E,F,L,M,N process
    class G,H,I,J,K decision
    class O output
```

---

## 📈 Dashboard Insights

The dashboards provide several views of the evaluation process:

| Dashboard | Purpose |
|---|---|
| Overview | Summarizes the evaluation results |
| Bid Qualification Summary | Presents bidder qualification categories |
| Compliance Grid | Compares bidders against individual requirements |
| Evaluation Methodology | Displays validation results and match metrics |
| Requirement Traceability | Examines requirement matches across bidders |

---

## 📂 Repository Structure

```text
Bid-Compliance-System/
├── README.md
├── LICENSE
├── 3D-visualization.HTML
├── Screenshots/
│   ├── Overview.png
│   ├── Compliance Grid.png
│   ├── Evaluation Methodology.png
│   └── Bid Qualification Summary.png
└── BidCompliance_Master-Copy.xlsx
```

---

## 🎯 Project Objective

To make bid evaluation easier to understand and review by consolidating bidder information, requirement-level compliance findings, documentation gaps, and qualification results into a structured analytical interface.

The project demonstrates how dashboards and interactive workflow visualization can support a more transparent and organized evaluation process.

---

## 👨‍💻 Author

**Saral Singhal**

---

<p align="center">
  <b>TenderIQ</b><br>
  Making bid compliance easier to understand, evaluate, and track.
</p>
