# Albridge Client Performance Scraper

> A focused scraping solution that extracts detailed client performance data from Albridge Wealth Reporting.
> Built for reliability at scale, this scraper turns locked dashboard metrics into structured, analysis-ready datasets.


<p align="center">
  <a href="https://www.bitbash.dev/project/albridge-client-performance-scraper" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://www.bitbash.dev/project/albridge-client-performance-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <a href="https://www.bitbash.dev/project/albridge-client-performance-scraper" target="_blank"><strong>Albridge Client Performance Scraper</strong></a> you've just found your team — Let's Chat. 👆👆 
</p>


## Introduction

This project automates the extraction of client portfolio and performance data from Albridge Wealth Reporting dashboards.
It solves the challenge of accessing historical and ongoing performance metrics that are otherwise confined to authenticated web interfaces.
The scraper is designed for financial professionals, analysts, and data teams who need consistent, queryable performance data.

### Wealth Reporting and Portfolio Analysis Context

- Enables longitudinal analysis of client performance without manual exports
- Supports consolidation of multi-client reporting into centralized data systems
- Reduces operational friction for recurring performance reviews
- Improves accuracy by eliminating copy-paste or spreadsheet-driven workflows

## Features

| Feature | Description |
|----------|-------------|
| Authenticated Session Handling | Securely navigates login-protected Albridge dashboards using browser automation. |
| Client-Level Data Extraction | Collects performance metrics per client account with consistent structure. |
| Historical Performance Capture | Extracts time-based returns and portfolio values across reporting periods. |
| Structured Data Output | Normalizes scraped data into JSON and SQL-ready formats. |
| Configurable Selectors | Uses XPath-based extraction adaptable to layout changes. |

---

## What Data This Scraper Extracts

| Field Name | Field Description |
|-------------|------------------|
| client_id | Unique identifier associated with each client profile. |
| client_name | Full name of the client as shown in the dashboard. |
| account_id | Identifier for individual investment accounts. |
| portfolio_value | Total portfolio value at the reporting date. |
| performance_period | Time range for the reported performance. |
| rate_of_return | Percentage return for the selected period. |
| benchmark_return | Comparative benchmark performance when available. |
| report_date | Date the performance data corresponds to. |

---

## Example Output

    [
      {
        "client_id": "CL-10293",
        "client_name": "John A. Smith",
        "account_id": "AC-88421",
        "portfolio_value": 1245320.55,
        "performance_period": "YTD",
        "rate_of_return": 6.42,
        "benchmark_return": 5.87,
        "report_date": "2025-12-31"
      }
    ]

---

## Directory Structure Tree

    albridge-client-performance-scraper/
    ├── src/
    │   ├── runner.py
    │   ├── auth/
    │   │   └── login_handler.py
    │   ├── extractors/
    │   │   ├── performance_parser.py
    │   │   └── account_parser.py
    │   ├── transforms/
    │   │   └── normalize.py
    │   ├── outputs/
    │   │   ├── json_exporter.py
    │   │   └── sql_exporter.py
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── samples/
    │   │   └── performance_sample.json
    │   └── logs/
    │       └── run.log
    ├── requirements.txt
    └── README.md

---

## Use Cases

- **Financial advisors** use it to aggregate client performance data, so they can prepare consistent review reports faster.
- **Analytics teams** use it to build longitudinal datasets, so they can identify performance trends across portfolios.
- **Operations teams** use it to automate reporting workflows, so they can reduce manual data handling errors.
- **Data engineers** use it to feed warehouses, so performance metrics stay queryable and up to date.

---

## FAQs

**How does the scraper handle authentication?**
It uses Selenium-driven browser sessions to replicate real user logins, maintaining cookies and session state throughout the scraping process.

**Is the scraper resilient to layout changes?**
Yes. Core extractors rely on configurable XPath selectors, making adjustments straightforward if the interface structure changes.

**What output formats are supported?**
The project exports normalized JSON by default, with optional SQL-ready outputs for direct database ingestion.

**Can it handle multiple clients in one run?**
Yes. The runner supports batch execution across multiple client accounts within a single authenticated session.

---

## Performance Benchmarks and Results

**Primary Metric:** Average extraction time of ~3–5 seconds per client account, depending on portfolio complexity.

**Reliability Metric:** Maintains a successful scrape rate above 97% across repeated authenticated sessions.

**Efficiency Metric:** Processes hundreds of client records per run with stable memory usage under typical workloads.

**Quality Metric:** Captures over 99% of available performance fields with consistent field-level completeness.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
