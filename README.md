# 💿 Discogs Price Checker

A Python automation script that checks current market prices on [Discogs.com](https://www.discogs.com) for a list of records, CDs, or other music items based on SKU, EAN, or title.  
Designed for sellers, collectors, and price analysts.

---

## ✅ What It Does

- Reads a CSV file with item identifiers (e.g. SKU, EAN, or titles)
- Searches Discogs.com and scrapes current lowest prices
- Handles "Not Found" cases and records results as "N/C"
- Exports a new CSV with pricing filled into the correct column

---

## 📦 Input Format

Expected CSV format:

| Product Name | SKU     | EAN     | New Price |
|--------------|---------|---------|-----------|
| Example Item | 12345AB | 0123456 |           |

---

## 🧠 Use Cases

- Store inventory valuation  
- Collection price updates  
- Competitive price tracking for resale

---

## 🛠 Technologies

- Python 3  
- Playwright (for headless browser scraping)  
- Pandas  
- CSV/Excel processing  
- Optional: Proxy rotation

---

## 📁 Output

- Updated CSV with new prices inserted  
- Items not found are marked as `N/C`

---

## 🔐 Access

🔒 Source code is private.  
This repo documents its pricing automation features and CSV integration.

---

## 🧑‍💻 Author

**TrkElnIt** – Automation for digital collectors and eCommerce tools  

