# Currency-Exchange
API Automation - Exchange Rate Data Collection

# Currency Exchange Rate Automation

## Project Overview

This project demonstrates an automated data pipeline that collects live currency exchange rates using an API and stores them in Google Sheets automatically.

The automation was built using Make.com and integrates with ExchangeRate API and Google Sheets to eliminate manual data collection.

---

## Automation Workflow

1. HTTP request fetches exchange rate data from ExchangeRate API
2. API authentication is handled using an API Key
3. The response contains real-time currency exchange rates
4. The automation extracts required fields
5. Data is automatically inserted into Google Sheets
6. The workflow runs on a scheduled interval

---

## Tools Used

- Make.com
- ExchangeRate API
- Google Sheets
- API Integration
- Workflow Automation

---

## Workflow Screenshot
![workflow](https://github.com/srinathnporange/Currency-Exchange/blob/main/Capture.PNG)
---

## Sample Output Data

| Date | USD | INR Rate | EUR Rate |
|-----|-----|-----|-----|
| 2026-02-06 | 1 | 90.335 | 0.8482 |

---

## Key Learnings

- API-based data extraction
- Automation for analytics workflows
- Building automated data pipelines
- Integrating APIs with cloud tools
- Reducing manual reporting effort

---

## Future Improvements

- Store data in a database
- Build Power BI dashboard on collected data
- Add multiple currency comparisons
