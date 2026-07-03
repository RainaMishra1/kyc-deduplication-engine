# KYC Deduplication & Loan Management System

FastAPI + PostgreSQL based system for KYC deduplication, mobile deduplication, and multi-loan management.

### Features

* KYC duplicate detection with confidence scoring
* Mobile number deduplication
* Support for multiple loans per customer
* Blacklist verification and audit tracking
* Unified customer profile view

### APIs

* `POST /api/v1/kyc/dedup` – Check duplicate KYC
* `POST /api/v1/loan/apply` – Apply for a loan
* `GET /api/v1/customer/{identifier}` – Get customer and loan details

### Run

```bash
git clone https://github.com/RainaMishra1/kyc-deduplication-engine.git
cd kyc-deduplication-engine
pip install -r requirements.txt
uvicorn main:app --reload
```
