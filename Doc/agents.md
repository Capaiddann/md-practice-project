# Agents

This file contains details about all agents in the Lead Gen system.

## Agent 1 — Lead Hunter
Finds business leads using DuckDuckGo search.

- Input: Industry + Location
- Output: List of company names and websites
- Tool used: DuckDuckGo + Claude Haiku

## Agent 2 — Website Scraper
Visits each website and extracts contact information.

- Input: Website URL
- Output: Email, phone, company details
- Tool used: BeautifulSoup

## Agent 3 — Email Verifier
Checks if the email address is real and active.

- Input: Email address
- Output: Valid or Invalid
- Tool used: SMTP check
