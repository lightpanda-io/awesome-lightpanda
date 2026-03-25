```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗  
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝  
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
 
██╗     ██╗ ██████╗ ██╗  ██╗████████╗██████╗  █████╗ ███╗   ██╗██████╗  █████╗ 
██║     ██║██╔════╝ ██║  ██║╚══██╔══╝██╔══██╗██╔══██╗████╗  ██║██╔══██╗██╔══██╗
██║     ██║██║  ███╗███████║   ██║   ██████╔╝███████║██╔██╗ ██║██║  ██║███████║
██║     ██║██║   ██║██╔══██║   ██║   ██╔═══╝ ██╔══██║██║╚██╗██║██║  ██║██╔══██║
███████╗██║╚██████╔╝██║  ██║   ██║   ██║     ██║  ██║██║ ╚████║██████╔╝██║  ██║
╚══════╝╚═╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝ ╚═╝  ╚═╝
```

# awesome-lightpanda

A curated list of cool things people are building with [Lightpanda](https://github.com/lightpanda-io/browser), the headless browser designed for AI and automation, written in Zig. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

---

## Contents
 
- [Web Data Extraction](#web-data-extraction)
- [AI Agents and Automation](#ai-agents-and-automation)
- [Language Bindings and Drivers](#language-bindings-and-drivers)
- [Resources](#resources)
- [Contributing](#contributing)
 
---
 
## Web Data Extraction

- [monostate/node-scraper](https://github.com/monostate/node-scraper) - Smart Node.js scraper that automatically switches between fetch, Lightpanda headless, and full Puppeteer with intelligent fallback. Includes AI-powered Q&A, PDF parsing, and bulk scraping with progress tracking.
- [4ier/neo](https://github.com/4ier/neo) - Turn any web app into an API. Chrome extension that captures browser traffic, auto-generates schemas, and lets AI replay APIs directly. Supports Lightpanda as a fast headless backend for AI agents and scraping.

## AI Agents and Automation

- [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) - Vercel's browser automation CLI for AI agents. Supports Lightpanda as an engine via `--engine lightpanda` as a faster, lighter alternative for Chrome. Written in Rust.
- [ulpi-io/browse](https://github.com/ulpi-io/browse) - Browsing tool by ULPI for AI agent workflows, powered by Lightpanda.

## Language Bindings and Drivers

- [navidemad/capybara-lightpanda](https://github.com/navidemad/capybara-lightpanda) - Capybara driver for Lightpanda, enabling Ruby integration testing with the Lightpanda headless browser.
- [marcoroth/lightpanda-ruby](https://github.com/marcoroth/lightpanda-ruby) - Ruby client for Lightpanda via CDP with high-level browser automation API and Capybara driver.

## Resources
 
- [Lightpanda Browser](https://github.com/lightpanda-io/browser) - Lightpanda browser repo.
- [Lightpanda Docs](https://github.com/lightpanda-io/docs) - Documentation.
- [Lightpanda Demo](https://github.com/lightpanda-io/demo) - Demo repository with Puppeteer examples and benchmarks.
- [Lightpanda Cloud](https://console.lightpanda.io/) - Managed cloud service.
- [@lightpanda/browser](https://www.npmjs.com/package/@lightpanda/browser) - npm package.
- [Docker Image](https://hub.docker.com/r/lightpanda/browser) - Docker image.
- [Lightpanda Agent Skill](https://github.com/lightpanda-io/agent-skill) - Browser skill for OpenClaw AI agents.
- [Homebrew Tap](https://github.com/lightpanda-io/homebrew-browser) - Install Lightpanda via Homebrew on macOS.
 
---
 
## Contributing
 
Contributions are welcome! Please read the [contribution guidelines](contributing.md) first.
