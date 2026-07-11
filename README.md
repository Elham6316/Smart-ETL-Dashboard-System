# Smart ETL & Dashboard System

A multi-agent data pipeline and analytics platform that transforms raw retail sales data into a cleaned dataset and a fully interactive, browser-based business intelligence dashboard — no backend, no build step, no dependencies beyond a web browser.

## Overview

This project takes a raw sales export (`sales.csv`), runs it through an automated ETL (Extract, Transform, Load) process to produce a clean, analysis-ready dataset (`Cleaned_Sales.csv`), and surfaces the results in an interactive dashboard for exploring revenue, orders, product performance, and category trends in real time.

## Key Features

- **AI-Powered Agentic Workflow** — The system was engineered using the Model Context Protocol (MCP) to securely bridge AI models with local datasets. It leverages advanced Prompt Engineering methodologies to orchestrate specialized agents, ensuring autonomous and secure execution across all ETL pipeline stages.
- **Multi-Agent System** — The pipeline is broken into specialized agent roles (Extractor, Transformer, Analyzer) that handle ingestion, cleaning, and KPI computation as discrete stages.
- **Data Cleaning** — Automated deduplication, encoding correction, date standardization, whitespace trimming, and rounding to produce a reliable source of truth from messy raw data.
- **Interactive Web Dashboard** — A single-file HTML dashboard with live category filtering, hover-enabled charts, a searchable transactions table, and a strategic insights panel that updates dynamically based on the selected filter.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | ETL pipeline, data cleaning, and KPI/aggregate computation |
| HTML5 | Dashboard structure and layout |
| Tailwind CSS | Styling and responsive design |
| Plotly.js | Interactive bar and donut chart visualizations |

## How to Run

No installation or server required.

1. Open the project folder.
2. Double-click `dashboard.html` (or `interactive_dashboard.html` for the full interactive version) to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Use the category filter and search bar to explore the data — charts, KPIs, and insights update automatically.

## Project Structure

```
├── sales.csv                    # Raw source data
├── Cleaned_Sales.csv            # Cleaned dataset (ETL output)
├── dashboard.html                # Static executive summary dashboard
├── interactive_dashboard.html    # Interactive dashboard with filtering & search
├── chart1.png / chart2.png       # Pre-rendered chart assets
└── README.md                     # Project documentation
```

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://elham6316.github.io/Smart-ETL-Dashboard-System/)
