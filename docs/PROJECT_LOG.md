
# Project Log — Inventory & Supply Chain Analytics

## 1. Project Overview

**Project name:** supply chain analytics  
**Repository:** supply-chain-analysis  
**Primary tools:** Git, GitHub, Python, Pandas, MySQL, Power BI

### Business Problem

An e-commerce distributor experiences stockouts of fast-moving products while overstocking slow-moving items. This can result in lost revenue and unnecessary inventory holding costs.

### Project Objectives

- Analyze inventory movement and stock levels.
- Identify fast-moving and slow-moving products.
- Calculate inventory turnover and reorder points where the required data is available.
- Evaluate supplier lead times and delivery performance where the required dates are available.
- Segment products by stockout risk.
- Present actionable findings in a Power BI dashboard.

## 2. Development Log

### Milestone 1 — Repository Setup

**Status:** Completed

- Opened the local project in VS Code.
- Verified the Git repository and `origin` remote.
- Confirmed the active branch is `main`.
- Confirmed the repository initially had no commits.

### Milestone 2 — Python Environment

**Status:** Completed — reported by the developer

- Created a project-specific virtual environment named `.venv`.
- Activated the environment.
- Environment isolation was verified by the developer.

**Purpose:** Keep Python dependencies separate from other projects.

### Milestone 3 — Repository Hygiene and Documentation

**Status:** In progress

- Create `.gitignore` to exclude virtual environments, secrets, caches, and local datasets.
- Create this project log.
- Verify the files and Git status.
- Create the first commit and push it to GitHub.    

## 3. Data Survey

**Status:** Pending

The dataset has not yet been downloaded or inspected.

The following details remain unverified:

- Dataset source and exact filename
- Row count and column names
- Data types and date coverage
- Missing values and duplicate records
- Availability of inventory, cost, demand, and delivery fields

No data-quality findings or KPI results have been claimed at this stage.

## 4. Technical Decisions

- Use Git for version control and GitHub for remote repository hosting.
- Use Python with Pandas for data preparation and analysis.
- Use MySQL for relational storage and SQL-based analysis.
- Use Power BI for interactive reporting.
- Exclude local virtual environments and raw datasets from Git by default.
- Validate source fields before implementing KPI calculations.

## 5. Next Steps

1. Finalize `.gitignore` and commit this documentation.
2. Create and verify `requirements.txt`.
3. Establish the full project directory structure.
4. Design the backend and orchestrator.
5. Download and inspect the dataset.
6. Document data-quality findings before cleaning.

