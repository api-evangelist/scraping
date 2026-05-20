# Scraping (scraping)
An index and topic collection covering web scraping platforms, proxy networks, SERP APIs, browser-based extraction services, and data collection APIs. Scraping platforms turn the public web into structured data by combining residential and datacenter proxy networks, anti-bot circumvention, headless browser automation, and managed crawler infrastructure. This collection includes scraping APIs like ScrapingBee, Scrapfly, ScrapingAnt, ScraperAPI, and Zyte; proxy networks like Bright Data, Oxylabs, Smartproxy, SOAX, and Nimble; data extraction platforms like Apify, Diffbot, Outscraper, Octoparse, and Datafiniti; SERP APIs like SerpApi; AI-first crawlers like Firecrawl, Crawl4AI, Jina AI, Browser Use, and AgentQL; and open-source scraping toolkits like Scrapy, Crawlee, Beautiful Soup, and Cheerio.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Web Scraping, Data Extraction, Proxy Network, SERP API, Residential Proxies, Web Crawling, Anti-Bot Circumvention, Headless Browser

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Scrape Job Schema](https://raw.githubusercontent.com/api-evangelist/scraping/refs/heads/main/json-schema/scraping-scrape-job-schema.json)
- [JSONSchema - Proxy Pool Schema](https://raw.githubusercontent.com/api-evangelist/scraping/refs/heads/main/json-schema/scraping-proxy-pool-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/scraping/refs/heads/main/json-ld/scraping-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/scraping/refs/heads/main/vocabulary/scraping-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Proxy Network Access | Scraping platforms expose massive pools of residential, mobile, datacenter, and ISP proxies that rotate IP addresses to distribute requests and bypass rate limits. |
| Anti-Bot Circumvention | Managed scraping APIs handle browser fingerprinting, TLS fingerprinting, CAPTCHA solving, and JavaScript challenges so consumers do not need to maintain their own bypass logic. |
| Headless Browser Rendering | Scraping APIs run real headless browsers (Chromium, Firefox, WebKit) on demand to execute JavaScript, wait for dynamic content, and capture fully rendered HTML or screenshots. |
| Structured Data Extraction | Platforms like Diffbot and Apify convert unstructured HTML into normalized JSON for products, articles, jobs, places, and other entity types using machine learning extraction. |
| SERP and Search Engine Scraping | SERP APIs like SerpApi, Bright Data SERP, and Oxylabs SERP scrape Google, Bing, Yahoo, Baidu, DuckDuckGo, and other search engines into structured JSON results. |
| AI-Native Web Reading | New crawlers like Firecrawl, Jina Reader, and Crawl4AI convert any URL into clean Markdown or structured JSON optimized for LLM and RAG ingestion. |
| Job Scheduling and Crawl Orchestration | Platforms like Apify, Octoparse, and Zyte run scheduled scraping jobs, distribute work across thousands of workers, and persist datasets for downstream consumption. |

## Use Cases

| Name | Description |
|------|-------------|
| E-Commerce Price Intelligence | Retailers scrape competitor product pages across Amazon, Walmart, and Shopify storefronts to track pricing, availability, and assortment in near real time. |
| SEO and SERP Monitoring | SEO platforms use SerpApi, Bright Data, and Oxylabs SERP APIs to track keyword rankings, featured snippets, and competitor visibility across global Google locales. |
| Lead Generation and Sales Intelligence | Sales teams scrape LinkedIn, business directories, and review sites to enrich CRM records with contact details, firmographics, and intent signals. |
| Brand and Review Monitoring | Brand teams scrape product reviews, social posts, and forums to monitor sentiment, detect counterfeits, and respond to support issues. |
| Real Estate and Travel Aggregation | Aggregators scrape listings from Zillow, Redfin, Airbnb, Booking.com, and Kayak to build search and comparison products. |
| AI and RAG Data Ingestion | AI teams use Firecrawl, Jina Reader, and Bright Data to crawl public web content into Markdown for retrieval-augmented generation pipelines. |
| Financial and Alternative Data | Hedge funds and analysts scrape job postings, app store rankings, and pricing pages to build alternative-data signals for investment models. |

## Integrations

| Name | Description |
|------|-------------|
| Bright Data | Largest commercial proxy network with 150M+ residential IPs, plus managed Web Unlocker, SERP API, and Web Scraper IDE. |
| Oxylabs | Premium residential, datacenter, and mobile proxies with Web Scraper API, SERP Scraper API, and E-Commerce Scraper API products. |
| Apify | Marketplace of 4,000+ pre-built scrapers (Actors) plus a serverless platform for running, scheduling, and storing scraped datasets. |
| Firecrawl | AI-native crawler that converts websites into Markdown, structured JSON, or screenshots optimized for LLM and RAG workflows. |
| ScrapingBee | Managed scraping API that handles headless browsers, proxy rotation, and CAPTCHA bypass with simple HTTP requests. |
| SerpApi | Real-time SERP scraping API supporting Google, Bing, Yahoo, Baidu, YouTube, Amazon, eBay, and 30+ other search engines. |
| Diffbot | AI-powered structured extraction across articles, products, discussions, videos, and a public Knowledge Graph of 10B+ entities. |
| Zyte | End-to-end scraping platform from the creators of Scrapy, with Smart Proxy Manager, automatic unblocking, and structured data APIs. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Scrape Job Schema](json-schema/scraping-scrape-job-schema.json)
- [Proxy Pool Schema](json-schema/scraping-proxy-pool-schema.json)

### JSON Structure

- [Scrape Job Structure](json-structure/scraping-scrape-job-structure.json)
- [Proxy Pool Structure](json-structure/scraping-proxy-pool-structure.json)

### JSON-LD

- [Scraping Context](json-ld/scraping-context.jsonld)

## Vocabulary

- [Scraping Vocabulary](vocabulary/scraping-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across web scraping APIs, proxy networks, and structured extraction platforms

## Network

This index references the following web scraping, proxy, and data extraction repositories:

- [AgentQL](https://github.com/api-evangelist/agentql)
- [Apify](https://github.com/api-evangelist/apify)
- [Beautiful Soup](https://github.com/api-evangelist/beautiful-soup)
- [Bright Data](https://github.com/api-evangelist/bright-data)
- [Browser Use](https://github.com/api-evangelist/browser-use)
- [Cheerio](https://github.com/api-evangelist/cheerio)
- [Crawl4AI](https://github.com/api-evangelist/crawl4ai)
- [Crawlee](https://github.com/api-evangelist/crawlee)
- [Datafiniti](https://github.com/api-evangelist/datafiniti)
- [Diffbot](https://github.com/api-evangelist/diffbot)
- [Firecrawl](https://github.com/api-evangelist/firecrawl)
- [Foodspark](https://github.com/api-evangelist/foodspark)
- [Import.io](https://github.com/api-evangelist/import-io)
- [Jina AI](https://github.com/api-evangelist/jina-ai)
- [Nimble](https://github.com/api-evangelist/nimble)
- [Octoparse](https://github.com/api-evangelist/octoparse)
- [Outscraper](https://github.com/api-evangelist/outscraper)
- [Oxylabs](https://github.com/api-evangelist/oxylabs)
- [ParseHub](https://github.com/api-evangelist/parsehub)
- [ScraperAPI](https://github.com/api-evangelist/scraper-api)
- [Scrapfly](https://github.com/api-evangelist/scrapfly)
- [ScrapingAnt](https://github.com/api-evangelist/scrapingant)
- [ScrapingBee](https://github.com/api-evangelist/scrapingbee)
- [Scrapy](https://github.com/api-evangelist/scrapy)
- [SerpApi](https://github.com/api-evangelist/serpapi)
- [Smartproxy](https://github.com/api-evangelist/smartproxy)
- [SOAX](https://github.com/api-evangelist/soax)
- [Zyte](https://github.com/api-evangelist/zyte)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
