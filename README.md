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

- [4ier/neo](https://github.com/4ier/neo) - Turn any web app into an API. Chrome extension that captures browser traffic, auto-generates schemas, and lets AI replay APIs directly. Supports Lightpanda as a fast headless backend for AI agents and scraping.
- [monostate/node-scraper](https://github.com/monostate/node-scraper) - Smart Node.js scraper that automatically switches between fetch, Lightpanda headless, and full Puppeteer with intelligent fallback. Includes AI-powered Q&A, PDF parsing, and bulk scraping with progress tracking.
- [tylergibbs1/feedstock](https://github.com/tylergibbs1/feedstock) - High-performance web crawler and scraper for TypeScript, powered by Bun and Playwright
- [us/crw](https://github.com/us/crw) - Open-source web scraper built for AI agents with a built-in MCP server. Single Rust binary, ~6 MB idle RAM. Uses Lightpanda for JS rendering. Firecrawl-compatible API.
- [seaavey/SBrowser](https://github.com/seaavey/SBrowser) - web search and Scraping REST API with Redis Anti-DDoS shield.

## AI Agents and Automation

- [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) - Vercel's browser automation CLI for AI agents. Supports Lightpanda as an engine via `--engine lightpanda` as a faster, lighter alternative for Chrome. Written in Rust.
- [ulpi-io/browse](https://github.com/ulpi-io/browse) - Browsing tool by ULPI for AI agent workflows, powered by Lightpanda.
- [irookanji/playwright-lightpanda-tests](https://github.com/irookanji/playwright-lightpanda-tests) - Playwright test automation framework with LightPanda integration.
- [elchemista/spectre_lens](https://github.com/elchemista/spectre_lens) - Agent-first Elixir browser lens for Lightpanda.
- [LocalKinAI/kinbrowser](https://github.com/LocalKinAI/kinbrowser) - Markdown-native browser for AI agents with three tier waterfall system, HTTP → Lightpanda → chromedp.
- [hartmantexas/tb](https://github.com/hartmantexas/tb) - Hybrid approach using Lightpanda with Satori to convert DOM HTML to svg, falling back to Chromium for pixels.
- [open-wa/wa-automate-nodejs](https://github.com/open-wa/wa-automate-nodejs) - Node.js framework for WhatsApp chatbots. Bots can swap to a lightweight headless backend without runtime changes.
- [EratoLab/web-access-mcp](https://github.com/EratoLab/web-access-mcp) - a simple web access MCP server targeted towards chat interfaces.
- [statkov/opencode-lightpanda](https://github.com/skatkov/opencode-lightpanda) - a Lightpanda browser plugin/tool for OpenCode.
- [hasindu-madushan/slim-atlas-ai](https://github.com/hasindu-madushan/slim-atlas-ai) - an MCP server providing lightweight browser automation using Lightpanda for LLMs.
- [prokopis3/webrain](https://github.com/prokopis3/webrain) - Rust MCP server for LLM-driven browser automation and web scraping.
- [veerupandey/kageha_agent](https://github.com/veerupandey/kageha_agent) - thin agent kernel: plan/act/verify.
- [amurru/hakase](https://github.com/amurru/hakase) - Go AI research and navigation agent.

## Language Bindings and Drivers

- [navidemad/capybara-lightpanda](https://github.com/navidemad/capybara-lightpanda) - Capybara driver for Lightpanda, enabling Ruby integration testing with the Lightpanda headless browser.
- [ferdiunal/larapanda](https://github.com/ferdiunal/larapanda) - Type-safe Lightpanda SDK for Laravel and PHP with named instances, auto CLI/Docker runtime resolution, MCP integration, and strict markdown/semantic tree outputs.
- [marcoroth/lightpanda-ruby](https://github.com/marcoroth/lightpanda-ruby) - Ruby client for Lightpanda via CDP with high-level browser automation API and Capybara driver.
- [tclesius/lightpanda-py](https://github.com/tclesius/lightpanda-py) - Python client for Lightpanda that bundles the binary and exposes APIs to fetch pages, start a CDP server, start an MCP server, etc.
- [u2i/lightpanda](https://github.com/u2i/lightpanda) - Elixir package for installing and running the Lightpanda headless browser.
- [DamageBDD/DamageBDD](https://github.com/DamageBDD/DamageBDD) - Erlang BDD behaviour-verification platform with Lightpanda in its browser layer

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
