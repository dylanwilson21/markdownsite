
# Galoy Marketing Website

A Jekyll-based marketing website for Galoy's bitcoin banking infrastructure and lending platform solutions.

## About

This website showcases Galoy's enterprise-grade bitcoin banking products:

- **Core Banking Suite**: Complete banking infrastructure with Bria payments hub, Cala accounting ledger, and Stablesats stability engine
- **Lana**: Bitcoin-backed lending platform for financial institutions
- **Additional Products**: Blink wallet, point-of-sale solutions, and hosted services

## Technology Stack

- **Jekyll**: Static site generator
- **GitHub Pages**: Hosting and deployment
- **Markdown**: Content management
- **HTML/CSS**: Custom styling and layouts

## Project Structure

```
├── _layouts/
│   └── default.html          # Main page template
├── _config.yml               # Jekyll configuration
├── Gemfile                   # Ruby dependencies
├── index.md                  # Homepage
├── core-banking.md           # Core Banking Suite page
├── lana.md                   # Lana lending platform page
├── about-us.md               # About/team page
├── security.md               # Security and compliance info
├── faq.md                    # Frequently asked questions
├── products.md               # Complete products overview
├── contact.md                # Contact information
└── README.md                 # This file
```

## Development

### Prerequisites

- Ruby (with gem command)
- Bundler gem

### Local Development

1. Install dependencies:
   ```bash
   gem install bundler
   bundle install
   ```

2. Run the development server:
   ```bash
   bundle exec jekyll serve --host 0.0.0.0 --port 5000
   ```

3. Visit http://localhost:5000 to view the site

### Content Updates

All content is written in Markdown with YAML front matter for metadata:

```yaml
---
layout: default
title: Page Title
description: "SEO description"
keywords: "seo, keywords, here"
---

# Page Content

Your markdown content here...
```

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch via GitHub Actions workflow (`.github/workflows/jekyll-gh-pages.yml`).

## Key Features

- **SEO Optimized**: Comprehensive meta tags and structured data
- **Responsive Design**: Mobile-friendly layout
- **Fast Loading**: Static site with optimized assets
- **Enterprise Focus**: Content tailored for financial institutions
- **Security Emphasis**: Highlights ISO27001 certification and compliance

## Contact Information

- **Business Inquiries**: biz@galoy.io
- **Documentation**: https://dev.galoy.io/
- **GitHub**: https://github.com/GaloyMoney

## License

This website content and code is proprietary to Galoy.
