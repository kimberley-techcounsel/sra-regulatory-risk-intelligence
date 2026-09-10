# SRA Regulatory Risk Intelligence

A legal data analytics project exploring regulatory enforcement decisions published by the **Solicitors Regulation Authority (SRA)** and demonstrating how public regulatory data can be transformed into structured risk intelligence.

## Project Overview

Using Python and pandas, this project cleans and analyses SRA regulatory-decision data and develops a transparent prototype regulatory risk model.

**Dataset:** 450 records across multiple snapshots, consolidated into **126 unique regulatory decisions**.

### Key Findings

* **Condition** was the most represented decision category, with 31 decisions.
* **18 regulated names** appeared in more than one unique decision.
* Duplicate publication across snapshots demonstrated the importance of data cleaning before regulatory analysis.
* Historical decision severity, repeat decisions and recency can be combined into an explainable regulatory-risk framework.

## Project Workflow

**01 — Data Cleaning**
Standardises dates, identifiers and decision categories and removes duplicate records.

**02 — Exploratory Analysis**
Examines enforcement categories, trends over time and repeat appearances.

**03 — Regulatory Risk Model**
Creates an explainable prototype score using decision severity, repeat history and recency, with sensitivity testing.

## Tools

Python · pandas · Jupyter Notebook · Matplotlib

## Why This Project

The project demonstrates the intersection of **legal analysis, regulatory compliance, data analytics and responsible risk modelling** — showing how legal data can support compliance and regulatory-intelligence workflows.

> **Disclaimer:** The risk model is an analytical prototype only. It is not an official SRA rating and does not establish the current or future regulatory risk of any individual or firm.
