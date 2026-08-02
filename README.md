# Web Scraping Project: Scire Research

##  Project Overview

This project scrapes key information from the Scire Research website (https://scireresearch.com/) to collect structured data about the company's services, contact information, and key value propositions. The scraped data is saved in both JSON and CSV formats for easy analysis and integration.

##  Objectives

- Collect data from a website using web scraping techniques
- Identify and inspect the website's HTML structure
- Use BeautifulSoup and requests libraries to scrape data
- Store scraped data in structured formats (JSON and CSV)
- Handle common challenges such as finding specific content patterns

##  Target Website

**Scire Research** (https://scireresearch.com/)
- Foundation for Africa's Data-Driven Future
- Research services, AI innovation, and data infrastructure
- Contact information in Nairobi, Kenya

##  Tools Used

| Tool | Purpose |
|------|---------|
| Python 3.x | Programming language |
| requests | HTTP requests to fetch webpage |
| BeautifulSoup | HTML parsing and data extraction |
| pandas | Data manipulation and CSV creation |
| json | Structured data storage |
| re (regex) | Pattern matching for contact information |

##  Data Collected

| Category | Description |
|----------|-------------|
| Company Headline | Main tagline from the website |
| Key Paragraphs | Important descriptive text |
| Service Highlights | Key services offered |
| Why Choose Us | Company value propositions |
| Beyond Research Pillars | Strategic focus areas |
| Contact Information | Email, phone, location |

##  Output Files

| File | Format | Description |
|------|--------|-------------|
| `scire_research_data.json` | JSON | Structured hierarchical data |
| `scire_research_data.csv` | CSV | Flattened tabular data |

### JSON Structure Example
```json
{
  "website": "https://scireresearch.com/",
  "headline": "Building Africa's Data-Driven Future",
  "key_paragraphs": ["..."],
  "service_highlights": ["..."],
  "why_choose_us": ["..."],
  "beyond_research_pillars": ["..."],
  "contact_info": {
    "email": "info@scireresearch.com",
    "phone": "+254 704 813110",
    "location": "Nairobi, Kenya"
  }
}
