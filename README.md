# Bank Asset-Liability Management (ALM) Risk Analysis

## Overview
This project simulates a commercial bank balance sheet to analyze interest rate risk, liquidity risk, and repricing mismatches under normal and stress scenarios.

The goal is to replicate core ALM functions used in banking institutions for risk monitoring and decision-making.

---

## Key Objectives
- Measure Net Interest Income (NII) and Net Interest Margin (NIM)
- Analyze duration gap between assets and liabilities
- Perform repricing gap analysis using time buckets
- Evaluate liquidity risk exposure
- Conduct interest rate stress testing

---

## Dataset
Simulated banking dataset including:
- Retail, SME, and Corporate loans
- Government and corporate bonds
- Customer deposits and borrowings

---

## Methods Used
- Python (Pandas, NumPy)
- Time bucket analysis (0–1Y, 1–3Y, 3–5Y, etc.)
- Stress testing scenarios (+100bps / +200bps rate shock)
- Gap analysis (asset vs liability mismatches)

---

## Key Insights
- The bank shows a **positive duration gap**, indicating exposure to rising interest rates.
- Short-term repricing mismatches suggest liquidity risk in early buckets.
- Stress testing shows **margin compression under rising rate environments**.
- The funding structure relies heavily on short-term liabilities.

---

## Business Recommendations
- Extend liability maturity profile
- Increase fixed-rate asset allocation
- Strengthen liquidity buffers
- Implement active ALM monitoring framework

---

## Files
- `/notebook` → Full ALM analysis (Jupyter notebook)
- `/data` → Simulated balance sheet data
- `/report` → Professional PDF risk report

---

## Author
Financial Analyst | Risk Analytics | Quant Finance Enthusiast
