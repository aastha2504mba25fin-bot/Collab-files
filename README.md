# Nanonets Invoice Data Extraction Labs

This repository contains a series of Google Colab notebooks demonstrating hands-on invoice data extraction using Nanonets no-code AI platform. These labs teach converting unstructured PDFs into structured financial data for finance automation. [nanonets](https://nanonets.com)

## Overview

The notebooks guide users through AI-powered Intelligent Document Processing (IDP) for invoices, covering upload, extraction, validation, and export to Excel/CSV. They mirror real-world accounts payable automation, reducing manual entry from hours to minutes. [github](https://github.com/robocorp/example-idp-nanonets-ui)

## Objective

- Extract key fields (invoice number, date, vendor, total, line items) from PDF invoices automatically.
- Understand OCR + AI for unstructured to structured data conversion.
- Apply to finance: AP automation, audits, ERP integration.
- No coding required—pure Nanonets platform usage. [nanonets](https://nanonets.com)

## Problem Statement

Manual invoice processing causes delays, errors (5-10% typical), and high costs (₹50k+/month for 1000 invoices). PDFs can't feed directly into Excel/ERP. AI solves this with 95%+ accuracy post-training. [nanonets](https://nanonets.com/ap-automation)

## Lab Notebooks

| Notebook ID | Focus Area | Link |
|-------------|------------|------|
| 1 | Nanonets Basics & Setup | [Colab 1](https://colab.research.google.com/drive/1KNLv9Pc2PQg18d2Q-H6pzMiewiGr5AcY?usp=sharing) |
| 2 | Invoice Upload & OCR | [Colab 2](https://colab.research.google.com/drive/1vrxjtl7iC9glzYIDrII12asscDA5e3yy?usp=sharing) |
| 3 | Field Extraction Demo | [Colab 3](https://colab.research.google.com/drive/1RghWaT7eGiw07PUJfgglRdRXvs4m30G1?usp=sharing) |
| 4 | Table & Line Items | [Colab 4](https://colab.research.google.com/drive/1QkKWxxGUl_0xzXs8sXJ6iWlaQCUpVbQv?usp=sharing) |
| 5 | Validation & Corrections | [Colab 5](https://colab.research.google.com/drive/1gFF0PAzchlReG1wrKWNEfLZ6SowKS-NR?usp=sharing) |
| 6 | Export to Excel/CSV | [Colab 6](https://colab.research.google.com/drive/1asGcuQ15TG8Y6mjYMN3ys1SouBSWVYlX?usp=sharing) |
| 7 | Q&A on Extracted Data | [Colab 7](https://colab.research.google.com/drive/1MI56bD_qze2F7l50GhTzD1gqm-XBO377?usp=sharing) |
| 8 | Batch Processing | [Colab 8](https://colab.research.google.com/drive/1YBpydRoBBv7zmXCq2GVokNOz5doVqq2W?usp=sharing) |
| 9 | Finance Analytics | [Colab 9](https://colab.research.google.com/drive/1h86HyZIbF3Bd6dXGX6UKdTw4aFoVfC9t?usp=sharing) |  [youtube](https://www.youtube.com/watch?v=Kc5aCNIuD-Q)

## Architecture

```
Invoice PDF/Image → Nanonets Platform → OCR + AI Extraction → Structured Data (JSON/Excel) → Analysis/ERP
```

- **OCR**: Text detection (Tesseract-like).
- **AI**: LayoutLM/BERT for fields/tables.
- **Validation**: Confidence scores, manual review.
- **Output**: Export-ready datasets. [docstrange.nanonets](https://docstrange.nanonets.com/docs/examples)

## Tools & Technologies

- **Nanonets**: Core no-code IDP platform. [nanonets](https://nanonets.com)
- **Google Colab**: Free runtime for demos (no local setup).
- **Sample Invoices**: Hypothetical finance docs with GST/TDS.
- **Exports**: CSV/Excel for Power BI/Tableau. [n8n](https://n8n.io/workflows/6194-parse-and-extract-invoice-data-with-nanonets-ocr-and-export-to-excel/)

## Key Features

- Auto-detects invoice number, dates, vendor, totals, line items.
- Handles tables (Qty, Price, Amount).
- Tax validation (GST 18%, TDS 10%).
- Q&A interface for analytics (e.g., "Highest revenue item?").
- Improves with feedback/training. [zephyrnet](https://zephyrnet.com/improve-invoice-processing-accuracy-with-nanonets-and-chatgpt/)

## Setup Instructions

1. Open any notebook link (requires Google account).
2. Sign into [nanonets.com](https://nanonets.com/) via Google.
3. Follow cell-by-cell: Upload sample PDF → Extract → Export.
4. Use provided hypothetical invoice for testing. [nanonets](https://nanonets.com)

## Sample Invoice Analysis

**Hypothetical Example** (Used in labs):
- Vendor: Global Finance Consulting
- Total: ₹70,800 (Subtotal ₹60,000 + GST ₹10,800)
- Services: Financial Modeling (₹20k), Risk Analysis (₹25k), etc.

**Questions Covered**:
- Total value? ₹70,800
- GST rate? 18%
- Highest service? Risk Analysis (35% of subtotal). [vskumar](https://vskumar.blog/2025/06/26/9-workflows-%F0%9F%93%84-from-paper-to-productive-automating-document-workflows-with-nanonets-and-ai/)

## Business Value

| Manual | AI with Nanonets |
|--------|------------------|
| 5-10 min/invoice | <30 sec/invoice |
| 5% error rate | <1% with validation |
| ₹20-50/hr labor | Near-zero marginal |
| Slow audits | Real-time compliance |  [nanonets](https://nanonets.com/ap-automation)

**Use Cases**: AP automation, fraud detection, ERP feeds (SAP), SME finance. [robocorp](https://robocorp.com/portal/robot/robocorp/example-idp-nanonets-ui)

## Future Enhancements

- API integration for production.
- Multi-language/currency.
- Workflow automation (n8n/Zapier).
- Custom model training. [n8n](https://n8n.io/workflows/6194-parse-and-extract-invoice-data-with-nanonets-ocr-and-export-to-excel/)

## Conclusion

These labs showcase Nanonets transforming finance docs into actionable data, enabling digital transformation without code. Run them in Colab for instant results! [github](https://github.com/robocorp/example-idp-nanonets-ui)
