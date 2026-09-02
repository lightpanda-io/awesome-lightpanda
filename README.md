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
- [tylergibbs1/feedstock](https://github.com/tylergibbs1/feedstock) - High-performance web crawler and scraper for TypeScript, powered by Bun. Supports Lightpanda, local or cloud, as a browser backend alongside Playwright and generic CDP.
- [us/crw](https://github.com/us/crw) - Open-source web scraper built for AI agents with a built-in MCP server. Single Rust binary, ~6 MB idle RAM. Uses Lightpanda for JS rendering. Firecrawl-compatible API.
- [seaavey/SBrowser](https://github.com/seaavey/SBrowser) - Web search and scraping REST API powered by Lightpanda for JavaScript rendering and Markdown extraction, with a Redis anti-DDoS shield.
- [ancs21/playpanda](https://github.com/ancs21/playpanda) - Any URL to LLM-ready markdown. Three-tier engine: HTTP → Lightpanda → CloakBrowser. Written in Zig.
- [tokimo-lab/tokimo-package-web-fetch](https://github.com/tokimo-lab/tokimo-package-web-fetch) - Unified Rust fetcher: plain HTTP, headless browser via Lightpanda, or Cloudflare bypass, with Readability denoising.
- [KakkoiDev/lightpanda-proxy](https://github.com/KakkoiDev/lightpanda-proxy) - Transparent HTTP proxy that renders JavaScript through Lightpanda before handing HTML to text browsers like w3m.
- [ba0f3/gocrawl](https://github.com/ba0f3/gocrawl) - Go crawler with chromedp/Lightpanda auto-fallback for client-rendered pages and challenge pages. Ships a docker-compose with Lightpanda on 9222.
- [cbwln/lightcrawl](https://github.com/cbwln/lightcrawl) - Lightpanda-powered alternative to Firecrawl.
- [raakkan/agents-api](https://github.com/raakkan/agents-api) - Self-hostable scraping, meta-search and screenshot REST API for agents, with Lightpanda CDP as one of the engines.
- [endurance-ai/crawler](https://github.com/endurance-ai/crawler) - Fashion SKU crawler for kiko.ai with a dedicated Lightpanda engine path and automatic engine selection for Cafe24 storefronts.
- [colophon-group/jobseek](https://github.com/colophon-group/jobseek) - Python job crawler replacing Playwright and Chromium with Go and self-hosted Lightpanda, sized for 10M boards and 100M postings.
- [aasenevan-dot/stock-scanner-dashboard](https://github.com/aasenevan-dot/stock-scanner-dashboard) - Lightpanda-powered live market and r/wallstreetbets intelligence dashboard.

## AI Agents and Automation
 
- [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) - Hermes supports Lightpanda as a local agent-browser option, with automatic Chrome fallback.
- [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) - Vercel's browser automation CLI for AI agents. Supports Lightpanda as an engine via `--engine lightpanda` as a faster, lighter alternative to Chrome. Written in Rust.
- [webcoyote/sandvault](https://github.com/webcoyote/sandvault) - Run AI agents isolated in a macOS user account and sandbox-exec, with sandboxed access to Lightpanda.
- [ulpi-io/browse](https://github.com/ulpi-io/browse) - Browsing tool by ULPI for AI agent workflows, powered by Lightpanda.
- [nextlevelbuilder/goclaw](https://github.com/nextlevelbuilder/goclaw) - OpenClaw rebuilt in Go with multi-tenant isolation and native concurrency. Ships a Lightpanda sidecar overlay for docker-compose, with Lightpanda-aware remote browser handling.
- [irookanji/playwright-lightpanda-tests](https://github.com/irookanji/playwright-lightpanda-tests) - Playwright test automation framework with Lightpanda integration.
- [elchemista/spectre_lens](https://github.com/elchemista/spectre_lens) - Agent-first Elixir browser lens for Lightpanda.
- [LocalKinAI/kinbrowser](https://github.com/LocalKinAI/kinbrowser) - Markdown-native browser for AI agents with a three-tier waterfall system, HTTP → Lightpanda → chromedp.
- [hartmantexas/tb](https://github.com/hartmantexas/tb) - Hybrid approach using Lightpanda with Satori to convert DOM HTML to SVG, falling back to Chromium for pixels.
- [open-wa/wa-automate-nodejs](https://github.com/open-wa/wa-automate-nodejs) - Node.js framework for WhatsApp chatbots. Bots can swap to Lightpanda as a lightweight headless backend without runtime changes.
- [EratoLab/web-access-mcp](https://github.com/EratoLab/web-access-mcp) - Web access MCP server aimed at chat interfaces. Local browser launch supports Lightpanda alongside Chrome, and it ships a dedicated Lightpanda Dockerfile.
- [skatkov/opencode-lightpanda](https://github.com/skatkov/opencode-lightpanda) - A Lightpanda browser plugin/tool for OpenCode.
- [hasindu-madushan/slim-atlas-ai](https://github.com/hasindu-madushan/slim-atlas-ai) - An MCP server providing lightweight browser automation using Lightpanda for LLMs.
- [prokopis3/webrain](https://github.com/prokopis3/webrain) - Rust MCP server for LLM-driven browser automation and web scraping. Runs Chrome, Lightpanda and Obscura through a single CDP backend.
- [veerupandey/kageha_agent](https://github.com/veerupandey/kageha_agent) - Thin agent kernel: plan, act, verify. `kageha setup` installs the Lightpanda nightly when the browser pack is enabled, falling back to Chromium.
- [amurru/hakase](https://github.com/amurru/hakase) - Go AI research and navigation agent. Ships a `lightpanda` MCP server in its default tool configuration.
- [agentjido/jido_browser](https://github.com/agentjido/jido_browser) - Browser automation actions for Jido AI agents, with `mix jido_browser.install lightpanda` as a first-class driver.
- [Freakboy/pandamcp](https://github.com/Freakboy/pandamcp) - MCP bridge for Lightpanda/CDP browsers with stdio, SSE and Streamable HTTP transports.
- [maxwelljens/battlecruiser](https://github.com/maxwelljens/battlecruiser) - Terminal mail reader that renders HTML email through Lightpanda.
- [Brilhante29/lightpanda-mcp-server](https://github.com/Brilhante29/lightpanda-mcp-server) - Go MCP server for Lightpanda.
- [daanrongen/lightpanda-mcp](https://github.com/daanrongen/lightpanda-mcp) - TypeScript MCP server: navigate, extract, click, fill forms, screenshot, evaluate JS over stdio.
- [codedoga/lightpanda-mcp](https://github.com/codedoga/lightpanda-mcp) - Docker image exposing Lightpanda's native MCP server over Streamable HTTP via supergateway.
- [oussamaelfig/Reynard](https://github.com/oussamaelfig/Reynard) - Autonomous CTF and authorized web security testing agent with a Kali/Lightpanda tool runtime.
- [audityourcontracts/pi-lightpanda](https://github.com/audityourcontracts/pi-lightpanda) - Lightpanda headless browser extension for the `pi` coding agent.
- [Hexpy-Games/butler](https://github.com/Hexpy-Games/butler) - Local-first AI agent runtime for personal and project work. Lightpanda is a selectable web reader backend.
- [mahirfatih/techcrunch-news-agent](https://github.com/mahirfatih/techcrunch-news-agent) - TechCrunch News Agent - AI Summarizer with Lightpanda + Ollama
- [mur-run/mur](https://github.com/mur-run/mur) - Rust agent orchestration platform. Its sandboxed deep-research gateway drives `lightpanda fetch` natively as a render engine.
- [vellum-ai/browser](https://github.com/vellum-ai/browser) - Assistant plugin that acts as a browser. Its settings panel installs Lightpanda and sets it as the default engine alongside Chromium debugging.
- [Herbertofury/Ferrum-Browser](https://github.com/Herbertofury/Ferrum-Browser) - Agent-native application tester that runs Lightpanda as its direct-CDP fast web lane, alongside Playwright, Electron and Remote WebDriver lanes.
- [fontvu/hermes-agent-template](https://github.com/fontvu/hermes-agent-template) - Hermes Agent Docker template with a Lightpanda build-arg engine.
- [veerupandey/loomable](https://github.com/veerupandey/loomable) - Python deep-agent framework with a sandboxed shell layer and a bundled browser skill that drives the Lightpanda MCP server.
- [OthmaneBlial/web-task-agent](https://github.com/OthmaneBlial/web-task-agent) - TypeScript local-first research agent that turns a question into an auditable decision package with sources and contradictions attached.
- [0x13omb3r/0xroboros-browser](https://github.com/0x13omb3r/0xroboros-browser) - Hard fork building HNS/DANE resolution and agent-verdict features on top of Lightpanda, with its own OCI image and docs.
- [suissa/PurePanda-Positron-3P](https://github.com/suissa/PurePanda-Positron-3P) - Electron alternative for memory-safe desktop apps built on Lightpanda.

## Language Bindings and Drivers
 
- [navidemad/capybara-lightpanda](https://github.com/navidemad/capybara-lightpanda) - Capybara driver for Lightpanda, enabling Ruby integration testing with the Lightpanda headless browser.
- [ferdiunal/larapanda](https://github.com/ferdiunal/larapanda) - Type-safe Lightpanda SDK for Laravel and PHP with named instances, auto CLI/Docker runtime resolution, MCP integration, and strict markdown/semantic tree outputs.
- [marcoroth/lightpanda-ruby](https://github.com/marcoroth/lightpanda-ruby) - Ruby client for Lightpanda via CDP with a high-level browser automation API and Capybara driver.
- [tclesius/lightpanda-py](https://github.com/tclesius/lightpanda-py) - Python client for Lightpanda that bundles the binary and exposes APIs to fetch pages, start a CDP server, start an MCP server, and more.
- [u2i/lightpanda](https://github.com/u2i/lightpanda) - Elixir package for installing and running the Lightpanda headless browser.
- [u2i/wallabidi](https://github.com/u2i/wallabidi) - Concurrent Elixir browser testing over WebDriver BiDi. Lightpanda is the documented fast path, at roughly 50ms per test.
- [DamageBDD/DamageBDD](https://github.com/DamageBDD/DamageBDD) - Erlang BDD behaviour-verification platform with Lightpanda in its browser layer.
- [jonathanong/darkpanda](https://github.com/jonathanong/darkpanda) - TypeScript SDK for Lightpanda.
- [lessless/light_cdp](https://github.com/lessless/light_cdp) - Elixir CDP client that connects directly to Lightpanda over WebSocket. No Node.js required.
- [crayonnova/lightpanda-nix](https://github.com/crayonnova/lightpanda-nix) - Nix flake for Lightpanda browser.
- [tonyputi/traverse](https://github.com/tonyputi/traverse) - web browsing for Laravel. Lightpanda is the first driver, with markdown and semantic-tree output for agents.

## Resources
 
- [probably-not/lightpanda-wpt-analysis](https://github.com/probably-not/lightpanda-wpt-analysis) - Are We Lightpanda Yet? External tracking of web-platform-test conformance.
- [pleasedodisturb/web-agent-comparison](https://github.com/pleasedodisturb/web-agent-comparison) - Third-party reproducible benchmark of seven browser-automation MCP servers, including Lightpanda.
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
