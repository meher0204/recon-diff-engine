# Recon Diff Engine

Attack Surface Change Detection platform for tracking new, removed and risky assets across repeated reconnaissance scans.

## Features

- Subdomain enumeration
- Technology fingerprinting
- Endpoint extraction
- Risk scoring engine
- AI-generated asset explanations
- Asset change detection
- Scan history tracking
- CSV export

## Architecture

- Target Domain
  - Subdomain Discovery
  - Technology Detection
  - Endpoint Extraction
  - Risk Analysis
  - AI Explanations
  - SQLite Storage
  - Diff Engine
  - Dashboard

## Tech Stack

- Python
- Streamlit
- SQLite
- BeautifulSoup
- Requests

## Usage

```bash
pip install -r requirements.txt
streamlit run app.py
