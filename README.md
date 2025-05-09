# 👋 Hi, I’m @snapshot-site

![Snapshot Site Banner](https://cdn.snapshot-site.fr/images/logo.png)

🚀 **Snapshot Site** is a fast, scalable API that lets you take high-resolution, full-page screenshots of any website — programmatically.

---

## 👀 I’m interested in:
- Web automation and headless browser technologies (Puppeteer, Chrome Headless)
- High-performance APIs & low-latency rendering
- Serverless and scalable infrastructure on AWS
- SaaS platforms & developer-friendly tooling
- SEO tooling and site monitoring via screenshots

## 🌱 I’m currently improving:
- Stealth mode & anti-bot fingerprinting
- Dynamic autoscaling of screenshot services in Docker/Kubernetes
- Dual-stack (IPv4/IPv6) API endpoint support
- Capture stability for highly dynamic or JS-heavy sites

## 💞️ I’m looking to collaborate on:
- Open-source tooling for automated visual regression testing
- Puppeteer plugins or alternatives in Rust/Go
- Edge-caching strategies (CloudFront, BunnyCDN, etc.)

## 📫 Reach me:
- 🌐 Website: [https://snapshot-site.com](https://snapshot-site.com)
- 📧 Email: [contact@snapshot-site.com](mailto:contact@snapshot-site.com)

## 😄 Pronouns:
He/Him

## ⚡ Fun fact:
We use real browsers in the cloud to capture what bots can't see. Your site might look different when JS is disabled — ours won't miss a pixel 😉.

## 📸 Snapshot Site – Full-Page Screenshot API

![Snapshot Site API](https://cdn.snapshot-site.fr/images/snapshot-site-api.png)

**Snapshot Site** is a powerful, developer-friendly API that captures **full-page, high-resolution screenshots** of any website — with real browser rendering and device emulation.

### 🔗 [→ View API Docs](https://snapshot-site.com/api-docs)

---

### 🚀 Features

- 🖥️ **Full-Page Capture**  
  Capture the entire webpage, including content below the fold, with pixel-perfect accuracy.

- 📱 **Device Emulation**  
  Simulate mobile, tablet, and desktop environments to test responsive designs.

- ⚡ **Dynamic Content Support**  
  Handle scroll-based animations, lazy-loaded elements, and execute custom JS before capture.

- 🧠 **Anti-Bot Detection Bypass**  
  Smart rendering engine handles pages protected by anti-bot systems.

- 🔐 **No Watermark, No Branding**  
  Clean screenshots — perfect for production workflows and reports.

- 🔄 **API-Driven Automation**  
  Automate screenshot generation for QA, SEO audits, content monitoring, and more.

---

### 🧪 Quick Example

```bash
curl --request POST
--url https://screenshot-snapshot-site2.p.rapidapi.com/api/v1/screenshot
--header 'Accept: application/json'
--header 'Content-Type: application/json'
--header 'x-rapidapi-host: screenshot-snapshot-site2.p.rapidapi.com'
--header 'x-rapidapi-key: YOUR_API_KEY'
--data '{"url":"https://wikipedia.org","format":"png","width":1280,"height":720,"delay":0,"fullSize":false,"hideCookie":false}'

