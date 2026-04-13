# Netflix-Dashboard
# 🎬 Netflix Analytics: TV Shows & Movies Insights Dashboard

A dynamic, interactive data visualization tool built to explore Netflix's content library — focusing on IMDb ratings, vote distributions, content type comparisons, release trends, runtime patterns, and age certification breakdowns.

---

## Short Description

The Netflix Analytics Dashboard is a visually engaging Power BI report designed to help users explore and compare **5,283 titles** (Movies & Shows) available on Netflix — spanning from **1953 to 2022** across multiple dimensions including IMDb scores, audience votes, runtime, release year trends, and content maturity ratings. This tool is intended for entertainment analysts, content strategists, streaming industry researchers, and data enthusiasts who want to uncover patterns in Netflix's evolving content library.

---

## Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing the dataset
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures such as Rating × Votes, dynamic KPIs, and conditional logic
- 📝 **Data Modeling** – Relationships and calculated columns established across the dataset to enable cross-filtering and aggregation
- 📁 **File Format** – `.xlsx` for the source dataset, `.pbix` for development, and `.png` for dashboard previews

---

## Data Source

**Source:** Netflix Titles Dataset (Kaggle / Public)

The dataset contains metadata for **5,283 Netflix titles** including Movies and TV Shows, covering:

| Column | Description |
|---|---|
| `title` | Name of the movie or show |
| `type` | MOVIE or SHOW |
| `release_year` | Year of original release (1953–2022) |
| `age_certification` | Content rating (R, PG, TV-MA, etc.) |
| `runtime` | Duration in minutes |
| `imdb_score` | IMDb rating (0–10 scale) |
| `imdb_votes` | Total number of IMDb user votes |

---

##  Features / Highlights

###  Business Problem

The global streaming industry is fiercely competitive, yet content analysts and decision-makers often lack an intuitive way to evaluate platform-level content quality, audience engagement, and historical trends at a glance.

Key questions that are hard to answer from raw data:
- Which titles generate the highest audience engagement by IMDb votes?
- How has Netflix's content volume and quality changed over the decades?
- Which age certifications consistently produce higher-rated content?
- What is the runtime distribution pattern across Netflix's library?

---

### Goal of the Dashboard

To deliver an interactive visual tool that:
- Enables users to explore 5,283+ Netflix titles across two content types
- Compares Movies vs. Shows on engagement (IMDb votes × scores)
- Uncovers rating and runtime trends across release years (1953–2022)
- Segments performance by age certification and content type filters

---

### Walkthrough of Key Visuals

**Page 1 — Content Overview & Ratings**

- **Key KPIs (Top Center)**
  - Total titles catalogued: **3.407K** (filtered view)
  - Maximum runtime: **235 minutes**
  - Average IMDb score: **6.27**

- **Count of ID by Type (Donut Chart)**
  Shows the share split between MOVIE (64.5%) and SHOW (35.5%), with an interactive type slicer

- **Sum of Runtime by Release Year (Area Chart)**
  Massive spike at **2020–2022** (peak: 46K) reflects Netflix's aggressive content expansion era

- **Count of IMDb Votes by Runtime (Line Chart)**
  Bell-curve peaking around **90–100 min runtime** (count: 113), confirming that standard-length films attract the most voter participation

- **Average of IMDb Votes by Release Year (Line Chart)**
  Reveals that **1970s–1990s classics** earned higher average vote counts — indicating enduring audience loyalty to older titles

---

**Page 2 — Temporal & Certification Analysis**

- **Release Year Slicer (1953–2022)** and **Type Filter** (MOVIE / SHOW)

- **Average IMDb Score by Release Year (Horizontal Bar Chart)**
  Scores peak in the **1960s–1970s** era, reflecting the classic film era's critical acclaim on the platform

- **Sum of IMDb Score by Release Year (Line Chart)**
  Volume-adjusted scores surge post-2000, driven purely by increased content count

- **Average Runtime by Release Year (Line Chart)**
  Runtime has steadily declined from ~180 min peaks in the late 1950s to ~75–90 min in recent years

- **Average IMDb Score by Age Certification (Scatter Plot)**
  **TV-MA** and **TV-14** content scores highest on average — adult-oriented content consistently outperforms family-rated titles in critical reception

---

**Page 3 — Top Titles & Rating × Votes Analysis**

- **Rating × Votes by Type (Bar Chart)**
  Movies (0.64bn) dwarf Shows (0.26bn) in total engagement weight — movies drive nearly 2.5× the audience interaction

- **Rating × Votes by Title — All Titles (Bar Chart)**
  Top performers: **Inception (20.0M)**, **Forrest Gump (17.6M)**, **Breaking Bad (16.4M)**

- **Top 10 Highest Rated Titles — IMDb Score (Clustered Bar)**
  Compares Movie vs Show scores side-by-side; notable leaders include **ERASED (16.3 - SHOW)**, **Cowboy Bebop (15.5 - SHOW)**, **The Gift (15.2 - MOVIE)**

- **Top 10 Highest Rated Titles — Votes (Bar Chart)**
  Even among top-rated titles, **Taxi Driver (6.6M votes)** leads, highlighting the gap between critical acclaim and mass audience reach

---
---

## Dashboard Snapshots

### Overview Page
![Dashboard Overview](https://github.com/analyticswithkanishk/Netflix-Dashboard/blob/main/Snapshot%20of%20the%20dashboard.png)

### Rating & Votes Analysis 
![Temporal Analysis](https://github.com/analyticswithkanishk/Netflix-Dashboard/blob/main/Snapshot%20of%20the%20dashboard2.png
)

### IMDB Analysis 
![Ratings Analysis](https://github.com/analyticswithkanishk/Netflix-Dashboard/blob/main/Snapshot%20of%20the%20dashboard3.png)

---

## Key Stats at a Glance

| Metric | Value |
|---|---|
| Total Titles | 5,283 |
| Movies | 3,407 (64.5%) |
| TV Shows | 1,876 (35.5%) |
| Year Range | 1953 – 2022 |
| Average IMDb Score | 6.53 |
| Max Runtime | 235 minutes |
| Total IMDb Votes | ~123.3 Million |
| Age Certifications | 11 categories |

---


---
