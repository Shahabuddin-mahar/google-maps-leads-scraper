# 📍 Google Maps Leads & B2B Business Scraper (No API Key Required)

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Get PRO Version](https://img.shields.io/badge/Get%20PRO%20Version-%2419%20Only-orange.svg)](https://gumroad.com/)

> **Extract unlimited high-quality B2B business leads, phone numbers, websites, ratings, and physical addresses directly from Google Maps without paying hundreds of dollars for expensive Google Cloud API keys!**

---

## ⚡ Why Use This Scraper?

- ✅ **Zero Cost / No API Key Needed:** Works directly without registering Google Cloud billing or paying \$200+/month.
- ✅ **High-Value Lead Data:** Extracts Business Name, Phone Number, Website, Category, Rating, Review Count, and Full Address.
- ✅ **Multi-Format Export:** Instantly exports clean data to **CSV (Excel)** and **JSON**.
- ✅ **Lightning Fast:** Lightweight and built with clean Python architecture.
- ✅ **Safe & Rate-Limit Resilient:** Uses rotating standard headers and graceful request handling.

---

## 🚀 Quick Start (in 60 Seconds)

### 1. Clone the Repository
```bash
git clone https://github.com/Shahabuddin-mahar/google-maps-leads-scraper.git
cd google-maps-leads-scraper
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Your First Search
```bash
python scraper.py --query "Dentists in New York" --limit 10
```

Or run interactively:
```bash
python scraper.py
```

---

## 📊 Extracted Data Fields

The exported `.csv` and `.json` files include:

| Field Name | Description | Example |
| :--- | :--- | :--- |
| `name` | Registered Business Name | Apex Dental Clinic |
| `category` | Business Category | Dentist / Dental Clinic |
| `rating` | Average Star Rating | 4.9 ★ |
| `reviews_count` | Total Customer Reviews | 340 |
| `phone` | Direct Business Phone | +1 212-555-0199 |
| `website` | Official Website URL | https://apexdentalcare.com |
| `address` | Full Street Address | 450 Lexington Ave, New York, NY |
| `maps_url` | Google Maps Link | https://maps.google.com/?q=... |

---

## 💼 Free vs. PRO Version Comparison

| Feature | Free Open-Source Version | PRO Commercial Version ($19) |
| :--- | :---: | :---: |
| Results per query | 10 Leads / run | **Unlimited Leads** |
| Export to CSV / JSON | ✅ Yes | ✅ Yes |
| Email Extraction from Website | ❌ No | ✅ **Built-in Email Finder** |
| Social Media Links (Instagram, LinkedIn, FB) | ❌ No | ✅ **Auto-Extracted** |
| Batch Multi-City Scraping | ❌ Manual | ✅ **Automated CSV queue** |
| Proxy Rotation & Headless Mode | ❌ No | ✅ **Included** |
| Commercial Resell Rights | ❌ Personal | ✅ **Full Commercial License** |

👉 **[Unlock the PRO Version on Gumroad for just $19 (One-Time Payment)](https://gumroad.com/)**

---

## 🛠️ Command-Line Arguments

```bash
usage: scraper.py [-h] [--query QUERY] [--limit LIMIT] [--format {csv,json,both}] [--output OUTPUT] [--pro-key PRO_KEY]

Options:
  -q, --query TEXT        Search query (e.g. "Real Estate in Dubai" or "Plumbers in London")
  -l, --limit INT         Max leads to extract (Free max: 10)
  -f, --format FORMAT     Export format: csv, json, or both (default: both)
  -o, --output NAME       Custom output file name (default: leads_output)
  --pro-key KEY           License key to unlock unlimited mode
```

---

## 🤝 Need Custom Scrapers or Lead Gen for Your Business?
If you need custom data pipelines, high-volume automated scrapers, or ready-made B2B leads for your agency:
- 📩 Contact via GitHub Issues or email: `Shahabuddin-mahar@users.noreply.github.com`
- 💼 Available for freelance and contract work on Upwork & Fiverr.

---

## ⚖️ License
Distributed under the MIT License. See `LICENSE` for details.
