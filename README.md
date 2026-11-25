# Automatic Recon Tool

An automated reconnaissance tool built in Python for security analysis and reporting. Provides a GUI-based interface (Tkinter) that automates information gathering tasks including WHOIS lookup, DNS records, SSL certificate analysis, Shodan queries, technology detection, metadata extraction, and admin panel discovery. Can export reports to PDF, capture screenshots, and send results via email.

---

## Problem Statement

Manual reconnaissance is time-consuming and error-prone. Security analysts need an automated, repeatable tool that gathers comprehensive target information and produces structured reports.

## Objectives

- Automate common reconnaissance tasks (WHOIS, DNS, SSL, headers, technology detection)
- Provide a GUI for non-technical users
- Support optional Shodan API integration
- Export results to PDF and email
- Capture screenshots of target pages

## Key Features

- **WHOIS & DNS Record Lookup** — domain registration and DNS record enumeration
- **HTTP Header Inspection** — analyze response headers
- **SSL Certificate Details** — certificate chain and validity
- **Shodan API Integration** — optional, requires API key
- **robots.txt & Sitemap Discovery** — crawl discovery files
- **Technology Detection** — BuiltWith integration
- **HTML Metadata Extraction** — parse page metadata
- **Admin Panel Brute Force Finder** — common admin path discovery
- **Screenshot Capture** — Selenium-based page screenshots
- **PDF Report Export** — structured report generation
- **Email Report Support** — send results via email
- **Tkinter GUI** — desktop interface

## Technologies Used

| Component | Technology |
|-----------|-----------|
| Language | Python 3 |
| GUI | Tkinter |
| Web Scraping | Selenium, requests |
| PDF Export | ReportLab / FPDF |
| Email | smtplib |
| Optional APIs | Shodan, BuiltWith |

## Project Structure

```
Automatic-Recon-Tool/
├── 2.py              # Main application (GUI + recon logic)
├── 2.spec            # PyInstaller spec file
├── LICENSE           # MIT License
└── README.md
```

## Installation and Setup

### Prerequisites
- Python 3.8+
- pip

### Setup
```bash
pip install -r requirements.txt
python 2.py
```

**Note:** Shodan integration requires a valid Shodan API key set via environment variable.

## Limitations

- Shodan and BuiltWith features require API keys
- Admin panel finder uses common path lists (not comprehensive)
- Screenshot capture requires Selenium WebDriver

## Author and Contact Information

**SAMALA RAKSHITH BABU**

- Email: samalarakshithbabu7@gmail.com
- LinkedIn: https://www.linkedin.com/in/samala-rakshith-babu-9374ab281/
- GitHub: https://github.com/samalarakshithbabu

## License

MIT License — Copyright (c) 2025 SAMALA RAKSHITH BABU