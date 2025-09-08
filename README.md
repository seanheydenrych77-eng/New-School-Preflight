# Preflight PDF Checker

A Streamlit app to let schools/teachers upload print-ready PDFs and automatically check them against printing standards.

## Features
- Page size and orientation check
- Binding type detection:
  - Saddle Stitch (no spine width)
  - Perfect Bound (spine width auto-calculated for ≥60pp on 80gsm by default)
  - Wiro Binding
- Colour vs. black-and-white detection
- Paper weight selection with "Not Sure" defaulting to 80gsm bond
- Hardened preflight:
  - Fonts embedded check
  - Overprint settings
  - Transparency flattening
  - DPI per image check

## Installation

Clone the repo and install dependencies:

```bash
pip install -r requirements.txt
```

## Run the app

```bash
streamlit run app.py
```
