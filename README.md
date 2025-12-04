# NestJS Web Scraping (Amazon Product Scraper)

A Web Scraping service built with **NestJS** and **Puppeteer**, designed to extract public product information from Amazon, including:

- Product Title  
- Price  
- Image URL

This project demonstrates how to use **headless browser automation** inside a NestJS application to fetch dynamic content from JavaScript-rendered pages.

# 📦 Installed Modules
pnpm i --save puppeteer-core
pnpm i --save @nestjs/config

# 🔧 Environment Variables (.env)
BROWSER_WS= your-browser-ws

# Start the app:
pnpm start:dev

# 📌 Example API Usage
## Request
localhost:3000/amazon/products?product=macbookpro
## Response
{
  "title": "Apple",
  "price": "$19.99",
  "Url": "https://www.amazon.com/..."
}

