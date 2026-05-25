# Search Agent

This agent searches the web to find business leads.

## What It Does
Uses DuckDuckGo to search for companies based on
industry and location.

## How It Works
1. Takes industry + location as input
2. Searches DuckDuckGo for results
3. Extracts company names and websites
4. Passes results to Website Scraper

## Example Search Queries

| Industry | Location | Query Used |
|----------|----------|------------|
| SaaS | Mumbai | "SaaS companies Mumbai" |
| Agency | Delhi | "marketing agency Delhi" |
| Ecommerce | Bangalore | "ecommerce store Bangalore" |

## Code

```python