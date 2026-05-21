[Apmex Scraper](https://apify.com/parseforge/apmex-scraper?fpr=data)

![ParseForge Banner](https://images.apifyusercontent.com/RHzPvdHJ2joNXJHSWjeziGDTOTaycOsfmbNq9q8ZVRM/w:1800/cb:1/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL1BhcnNlRm9yZ2UvYXBpZnktYXNzZXRzL21haW4vYmFubmVyLmpwZw.webp)

# 🥇 APMEX Precious Metals Scraper

> 🚀 **Collect gold, silver, platinum, and palladium product listings with live pricing, weight, purity, and product details from one of the largest online precious metals retailers.**

> 🕒 Last updated: 2026-04-23

Whether you are an investor tracking bullion prices, a dealer monitoring product availability, or a researcher analyzing the precious metals market, the APMEX Scraper delivers structured product data in seconds. Browse by metal type, search by keyword, or paste any category URL to start collecting.

No coding, no manual browsing. Configure your filters, click Start, and download your data as JSON, CSV, or Excel.

| 🎯 Target | APMEX precious metals product listings |
| --- | --- |
| 🔎 Best for | Price tracking, market research, dealer intelligence, investment analysis |

---

## 📋 What it does

- Collects product names, current asking prices, "as low as" pricing tiers, and original prices for gold, silver, platinum, and palladium items
- Extracts weight, purity, metal type, product badges (Sale, Top Pick), and product IDs from listings
- Supports filtering by metal type, keyword search, or direct category URL input
- Returns product images and direct URLs for each listing

---

## 🎬 Demo

🚧 Coming soon

---

## ⚙️ Input

| Field | Type | Description |
| --- | --- | --- |
| Start URL | string | APMEX category or search page URL. Browse the site, apply filters, and paste the URL here. |
| Max Items | integer | Free users: limited to 10 items. Paid users: up to 1,000,000. |
| Metal Type | select | Filter by Gold, Silver, Platinum, or Palladium. Ignored if Start URL is provided. |
| Search Query | string | Search for specific products (e.g. "American Eagle", "1 oz Gold Bar"). Overrides Start URL and Metal Type. |

**Example 1: Filter by metal type**

```
{
    "metalType": "gold",
    "maxItems": 50
}
```

**Example 2: Search for specific products**

```
{
    "searchQuery": "American Eagle",
    "maxItems": 20
}
```

> ⚠️ **Good to Know**: The scraper uses a browser to bypass site protection, so it runs slower than API-based scrapers (approximately 10 to 20 products per minute). Free users are limited to 10 items per run.

---

## 📊 Output

### 🧾 Schema

Each product record includes up to 12+ fields covering pricing, specifications, and product metadata.

 
 
 

---

## ✨ Why choose this scraper

| Feature | Details |
| --- | --- |
| All four precious metals | Gold, silver, platinum, and palladium products |
| Live pricing data | Current asking price and "as low as" pricing tiers |
| Weight and purity parsed | Specifications extracted from product titles |
| Badge detection | Sale, Top Pick, and other product badges captured |
| Search or browse | Use keywords, metal type filters, or direct category URLs |
| Product images included | High-quality product photo URLs in every record |
| Export as JSON, CSV, or Excel | Download structured data in the format you need |

---

## ✨ Why choose this Actor

|  | Capability |
| --- | --- |
| 🎯 | **Built for the job.** Scoped specifically to this data source so you skip the parser engineering entirely. |
| 🔖 | **Structured output.** Clean, typed fields ready for analysis, dashboards, or downstream pipelines. |
| ⚡ | **Fast.** Optimized request patterns return results in seconds, not minutes. |
| 🔁 | **Always fresh.** Every run pulls live data, so the dataset reflects the source as of run time. |
| 🌐 | **No infra to manage.** Apify handles proxies, retries, scaling, scheduling, and storage. |
| 🛡️ | **Reliable.** Battle-tested across many runs and edge cases, with graceful error handling. |
| 🚫 | **No code required.** Configure in the UI, run from CLI, schedule via cron, or call from any language with the Apify SDK. |

> 📊 Production-grade structured data without the engineering overhead of building and maintaining your own scraper.

---

## 📈 How it compares

| Capability | This scraper | Manual browsing |
| --- | --- | --- |
| Batch collection | Up to 1M products in one run | Browse one page at a time |
| Price tracking | Structured data for analysis | Visual comparison only |
| Metal filtering | All four metals with one click | Navigate between sections |
| Structured output | JSON, CSV, Excel | Copy from web pages |
| Automated scheduling | Daily or weekly monitoring | Manual visits |
| Spec extraction | Weight and purity parsed | Read descriptions manually |
| Multiple export formats | Three formats supported | Not available |

---

## 🚀 How to use

1. [Create a free Apify account](https://console.apify.com/sign-up?fpr=vmoqkp) (includes $5 credit)
2. Search for **APMEX Scraper** in the Apify Store
3. Select your metal type, enter a search query, or paste a category URL
4. Click **Start** and wait for results
5. Download your data as JSON, CSV, or Excel

---

## 💼 Business cases

| Use case | How it helps |
| --- | --- |
| Investment portfolio tracking | Monitor daily price changes across gold, silver, platinum, and palladium products |
| Dealer price intelligence | Compare your product pricing against a major retailer |
| Market research | Analyze pricing spreads, premiums over spot, and product trends |
| Collection tracking | Track rare coin and collectible bullion prices over time |

---

---

## 💼 Business use cases

| ### 📊 Data & Analytics     - Build trend reports and dashboards from live source data - Feed BI tools, warehouses, and ML pipelines with structured records - Run periodic snapshots to track changes over time - Compare segments, regions, or categories with consistent fields | ### 🏢 Operations & Strategy     - Monitor competitor moves, pricing, and inventory shifts - Build internal directories and lookup tools backed by current data - Power workflows that depend on fresh source records - Cut manual data-gathering time from hours to minutes |
| --- | --- |
| ### 🎯 Marketing & Growth     - Identify market opportunities and trending topics - Research target audiences and customer personas at scale - Power lead-generation pipelines with verified records - Track sentiment, reviews, or social signals over time | ### 🛠️ Engineering & Product     - Prototype features that need real-world data without owning a crawler - Replace fragile in-house scrapers with a managed Actor - Wire datasets into your apps via the Apify API or webhooks - Skip the proxy, retry, and parsing maintenance entirely |

---

## 🌟 Beyond business use cases

Data like this powers more than commercial workflows. The same structured records support research, education, civic projects, and personal initiatives.

| ### 🎓 Research and academia     - Empirical datasets for papers, thesis work, and coursework - Longitudinal studies tracking changes across snapshots - Reproducible research with cited, versioned data pulls - Classroom exercises on data analysis and ethical scraping | ### 🎨 Personal and creative     - Side projects, portfolio demos, and indie app launches - Data visualizations, dashboards, and infographics - Content research for bloggers, YouTubers, and podcasters - Hobbyist collections and personal trackers |
| --- | --- |
| ### 🤝 Non-profit and civic     - Transparency reporting and accountability projects - Advocacy campaigns backed by public-interest data - Community-run databases for local issues - Investigative journalism on public records | ### 🧪 Experimentation     - Prototype AI and machine-learning pipelines with real data - Validate product-market hypotheses before engineering spend - Train small domain-specific models on niche corpora - Test dashboard concepts with live input |

## 🤖 Ask an AI assistant about this scraper

Open a ready-to-send prompt about this ParseForge actor in the AI of your choice:

- 💬 [**ChatGPT**](https://chat.openai.com/?q=How%20do%20I%20use%20the%20APMEX%20Precious%20Metals%20and%20Bullion%20Scraper%20by%20ParseForge%20on%20Apify%3F%20Show%20me%20input%20examples%2C%20output%20fields%2C%20common%20use%20cases%2C%20and%20how%20to%20integrate%20it%20into%20a%20workflow.)
- 🧠 [**Claude**](https://claude.ai/new?q=How%20do%20I%20use%20the%20APMEX%20Precious%20Metals%20and%20Bullion%20Scraper%20by%20ParseForge%20on%20Apify%3F%20Show%20me%20input%20examples%2C%20output%20fields%2C%20common%20use%20cases%2C%20and%20how%20to%20integrate%20it%20into%20a%20workflow.)
- 🔍 [**Perplexity**](https://perplexity.ai/search?q=How%20do%20I%20use%20the%20APMEX%20Precious%20Metals%20and%20Bullion%20Scraper%20by%20ParseForge%20on%20Apify%3F%20Show%20me%20input%20examples%2C%20output%20fields%2C%20common%20use%20cases%2C%20and%20how%20to%20integrate%20it%20into%20a%20workflow.)
- 🅒 [**Copilot**](https://copilot.microsoft.com/?q=How%20do%20I%20use%20the%20APMEX%20Precious%20Metals%20and%20Bullion%20Scraper%20by%20ParseForge%20on%20Apify%3F%20Show%20me%20input%20examples%2C%20output%20fields%2C%20common%20use%20cases%2C%20and%20how%20to%20integrate%20it%20into%20a%20workflow.)

## ❓ Frequently Asked Questions

### 💳 Do I need a paid Apify plan to run this actor?

No. You can start right now on the free Apify plan, which includes **$5 in free monthly credit**. That is enough to run this actor several times and explore the output before committing to anything. Paid plans unlock higher limits, more concurrent runs, and larger datasets. [Create a free Apify account here](https://console.apify.com/sign-up?fpr=vmoqkp) to get started.

### 🚨 What happens if my run fails or returns no results?

Failed runs are not charged. If the source site changes, proxies get rate-limited, or a specific input matches nothing, re-run the actor or open our [contact form](https://tally.so/r/BzdKgA) and we will investigate. You can also check the run log in the Apify console to see why the run stopped.

### 📏 How many items can I scrape per run?

Free users are limited to **10 items per run** so you can preview the output and confirm the actor works for your use case. Paid users can raise `maxItems` up to **1,000,000** per run. [Upgrade here](https://console.apify.com/sign-up?fpr=vmoqkp) if you need full scale.

### 🕒 How fresh is the data?

Every run fetches live data at the moment of execution. There is no cache or delay: the records you get reflect what the source returned at that moment. Schedule the actor to maintain a rolling snapshot of the data you need.

### 🧑‍💻 Can I call this actor from my own code?

Yes. Apify exposes every actor as a REST endpoint and ships first-class SDKs for [Node.js](https://docs.apify.com/sdk/js) and [Python](https://docs.apify.com/sdk/python). You can start a run, read the dataset, and handle webhooks from your own app in a few lines. All you need is your Apify API token.

### 📤 How do I export the data?

Every Apify dataset can be downloaded in one click from the console as CSV, JSON, JSONL, Excel, HTML, XML, or RSS. You can also pull results programmatically via the [Apify API](https://docs.apify.com/api/v2) or stream them into BigQuery, S3, and other destinations through built-in integrations.

### 📅 Can I schedule the actor to run automatically?

Yes. Use the Apify scheduler to run the actor on any cadence, from hourly to monthly. Results are saved to your dataset and can be delivered to webhooks, email, Slack, cloud storage, or automation tools such as Zapier and Make.

---

## 🔌 Automating runs

Schedule the APMEX Scraper to run daily for price monitoring or weekly for inventory checks. Connect with Make, Zapier, or webhooks to trigger runs automatically. Pair with Google Sheets to maintain a live pricing spreadsheet or Slack to get notified when prices drop below your target.

## 🔌 Integrate with your tools

- [Make](https://docs.apify.com/platform/integrations/make) - Automate precious metals price monitoring
- [Zapier](https://docs.apify.com/platform/integrations/zapier) - Get alerts when prices change
- [Slack](https://docs.apify.com/platform/integrations/slack) - Get notified about price movements
- [Google Sheets](https://docs.apify.com/platform/integrations/drive) - Export product data to spreadsheets
- [Airbyte](https://docs.apify.com/platform/integrations/airbyte) - Build data pipelines
- [Webhooks](https://docs.apify.com/platform/integrations/webhooks) - Trigger actions on run completion

---

## 🔌 Integrate with any app

APMEX Precious Metals Scraper connects to any cloud service via [Apify integrations](https://apify.com/integrations):

- [**Make**](https://docs.apify.com/platform/integrations/make) - Automate multi-step workflows
- [**Zapier**](https://docs.apify.com/platform/integrations/zapier) - Connect with 5,000+ apps
- [**Slack**](https://docs.apify.com/platform/integrations/slack) - Get run notifications in your channels
- [**Airbyte**](https://docs.apify.com/platform/integrations/airbyte) - Pipe results into your warehouse
- [**GitHub**](https://docs.apify.com/platform/integrations/github) - Trigger runs from commits and releases
- [**Google Drive**](https://docs.apify.com/platform/integrations/drive) - Export datasets straight to Sheets

You can also use webhooks to trigger downstream actions when a run finishes. Push fresh data into your product backend, or alert your team in Slack.

---

## 🔗 Recommended ParseForge actors

| Actor | What it does |
| --- | --- |
| [Yahoo Finance Scraper](https://apify.com/parseforge/yahoo-finance-scraper) | Collect OHLCV price data for stocks, crypto, forex, and ETFs |
| [FINRA BrokerCheck Scraper](https://apify.com/parseforge/finra-brokercheck-scraper) | Look up broker and firm registration data |
| [Flippa Scraper](https://apify.com/parseforge/flippa-scraper) | Scrape online business marketplace listings |
| [Pitchbook Funds Scraper](https://apify.com/parseforge/pitchbook-scraper-fund-data) | Collect investment fund performance data |
| [FRED Economic Data Scraper](https://apify.com/parseforge/fred-scraper) | Gather economic time series from the Federal Reserve |

---

## 🆘 Need help?

[Contact us through our support form](https://tally.so/r/BzdKgA) to request a new scraper, report an issue, or propose a custom project.

---

> **Disclaimer:** This Actor is an independent tool and is not affiliated with, endorsed by, or connected to APMEX (American Precious Metals Exchange) or any precious metals dealer. It accesses only publicly available data.

---

## 🔗 Recommended Actors

- [**🔍 Google Search Scraper**](https://apify.com/parseforge/google-search-scraper) - Multi-engine SERP results with country and language targeting
- [**🗺️ Nominatim OSM Scraper**](https://apify.com/parseforge/nominatim-osm-scraper) - Geocode addresses via OpenStreetMap
- [**📊 Indexmundi Scraper**](https://apify.com/parseforge/indexmundi-scraper) - Global demographic and economic indicators
- [**📰 RAG Web Browser**](https://apify.com/parseforge/rag-web-browser) - Crawl and extract clean text from any URL for AI retrieval
- [**🌐 Website Content Crawler**](https://apify.com/parseforge/website-content-crawler) - Crawl entire sites and export structured content

> 💡 **Pro Tip:** browse the complete [ParseForge collection](https://apify.com/parseforge) for more reference-data scrapers.