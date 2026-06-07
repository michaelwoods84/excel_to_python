# Excel to Python for Finance Professionals

**Replace your spreadsheets with cleaner, faster, more powerful financial models.**

A practical, notebook-based course for mid-level finance professionals who want to move beyond Excel — without wading through generic Python tutorials that have nothing to do with their actual work.

---

## Who this is for

You're a finance professional — analyst, associate, FP&A manager, or similar — who:

- Builds financial models, P&Ls, or DCFs regularly in Excel
- Suspects there's a better way, but hasn't had time to figure it out
- Wants to automate the monthly reporting process that currently takes hours
- Is comfortable in Excel but has little or no Python experience

This course was built by a quantitative analyst at an investment bank. Every example uses real finance workflows, not toy datasets.

---

## What you'll build

Each module is a self-contained Jupyter notebook with working code you can adapt immediately.

| Module | What you build |
|--------|----------------|
| **01 — Why Python?** | Load a P&L from Excel, calculate margins, produce a chart — all in ~20 lines |
| **02 — Finance Fundamentals** | Replace VLOOKUP, SUMIF, COUNTIF, and pivot tables with pandas equivalents |
| **03 — P&L Modelling** | Full 3-year income statement with scenario analysis and sensitivity tables |
| **04 — DCF Valuation** | End-to-end discounted cash flow model with WACC and a sensitivity heatmap |
| **05 — Best Practices** | Model structure, validation functions, Git version control, reusable templates |
| **06 — Automation** | Automated monthly reporting pipeline: raw data in, formatted Excel report out |

---

## How to run the notebooks

### Option A — Google Colab (recommended, no installation required)

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Select the `.ipynb` file from your downloaded course ZIP
4. Click **Runtime → Run all**

**Even easier:** unzip all course files into your Google Drive. Double-click any `.ipynb` and it opens directly in Colab. Do this once and all six notebooks are always one click away.

All you need is a free Google account. No software installation required.

### Option B — Local (Anaconda)

```bash
# 1. Install Anaconda: https://www.anaconda.com/download
# 2. Install extra libraries
pip install openpyxl plotly

# 3. Launch Jupyter Lab
jupyter lab

# 4. Open any .ipynb file from the unzipped course folder
```

---

## Course file structure

When you unzip your download you'll find:

```
excel-to-python-finance/
├── README.md                    ← Start here
├── module_01_why_python.ipynb
├── module_02_fundamentals.ipynb
├── module_03_pl_modelling.ipynb
├── module_04_dcf.ipynb
├── module_05_best_practices.ipynb
└── module_06_automation.ipynb
```

Work through modules in order — each builds on the last.

---

## Prerequisites

- No Python experience required
- Comfortable using Excel for financial analysis
- A Google account (for Colab) or Anaconda installed locally

---

## Libraries used

| Library | Purpose |
|---------|---------|
| `pandas` | DataFrames, groupby, merge, pivot tables |
| `numpy` | Numerical operations, scenario arrays |
| `matplotlib` | Charts and visualisations |
| `openpyxl` | Reading and writing Excel files |

All included in Anaconda. All available in Google Colab.

---

## Getting started

1. Unzip your download — you'll find six `.ipynb` notebook files and this README
2. Either upload to Google Drive (recommended) or open via **File → Upload notebook** in Colab
3. Start with `module_01_why_python.ipynb` and work through in order

Questions? Contact [your-email@domain.com]

---

## License

Course content is for personal use only. Do not redistribute or resell.

© 2024. All rights reserved.
