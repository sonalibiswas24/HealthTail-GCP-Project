# HealthTail-GCP-Project

---

## 🔍 Project Overview

ClinIPet is a data analytics case study exploring clinical and commercial performance of their client Healthtail across a veterinary practice network. The goal was to answer key business questions around supplier distribution, patient visit patterns, and the most common conditions treated — turning raw clinic data into clear, actionable insights.

## 🗄️ SQL Queries

The `sql/` folder contains business-focused queries written to extract insights directly from the clinic database. Key queries cover:

- **Top patients by visit count** — identifying the most frequent visitors across the network
- **Supplier market share** — understanding how medication suppliers like Pets Pharma, Animal Meds Ltd., Vet Pharma Inc., and Vet Supplies Co. are distributed across prescriptions
- **Most common diagnoses** — ranking conditions by visit volume to understand clinical demand (e.g., Hyperthyroidism, Hip Dysplasia, Arthritis)
- Supporting queries for filtering, grouping, and aggregating visit records

## 📊 Data Studio Dashboard

The dashboard was built in Google Data Studio and visualises the outputs of the SQL queries in an interactive format.

**Key visuals included:**
- 🥧 **Supplier Distribution (Pie Chart)** — Pets Pharma leads at 30.1%, followed closely by Animal Meds Ltd. at 29.7%
- 📋 **High-Frequency Patients (Table)** — Top 10 patients ranked by visit count, with dog_8071 topping the list at 41 visits
- 📊 **Top Diagnoses by Visit Volume (Bar Chart)** — Hyperthyroidism is the most visited condition at 10.8K visits

> 🔗 [View Live Dashboard](#) *((https://datastudio.google.com/reporting/5e53bd78-a5df-4f04-b69f-676c424c2da6))*

## 📽️ Presentation

The `presentation/` folder contains a PowerPoint deck summarising the project findings, designed for a non-technical stakeholder audience. It walks through:

1. Project background and objectives
2. Data methodology
3. Supplier performance breakdown
4. High-frequency patient analysis
5. Clinical diagnosis trends
6. Key recommendations

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| SQL | Data extraction and business logic |
| Google Looker Studio | Dashboard and data visualisation |
| PowerPoint | Stakeholder presentation |
| GitHub | Version control and project sharing |
| BigQuery | Cleaning and querying the data |

---

## 💡 Key Findings

- **Pets Pharma** is the leading supplier by prescription share (30.1%), but **Animal Meds Ltd.** is a near-equal competitor at 29.7% — a margin worth monitoring
- **dog_8071** recorded the highest visit count (41 visits), suggesting either a complex chronic case or a data anomaly worth investigating
- **Hyperthyroidism** accounts for significantly more visits than any other condition (10.8K),
