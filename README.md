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
- [tylergibbs1/feedstock](https://github.com/tylergibbs1/feedstock) - High-performance web crawler and scraper for TypeScript, powered by Bun. Supports Lightpanda, local or cloud, as a browser backend alongside Playwright and generic CDP.
- [SurendraTamang/scrapy-lightpanda](https://github.com/SurendraTamang/scrapy-lightpanda) - Scrapy download handler that plugs Lightpanda into scrapy-playwright for JavaScript-rendered pages.
- [us/crw](https://github.com/us/crw) - Open-source web scraper built for AI agents with a built-in MCP server. Single Rust binary, ~6 MB idle RAM. Uses Lightpanda for JS rendering. Firecrawl-compatible API.
- [ancs21/playpanda](https://github.com/ancs21/playpanda) - Any URL to LLM-ready markdown. Three-tier engine: HTTP → Lightpanda → CloakBrowser. Written in Zig.
- [tokimo-lab/tokimo-package-web-fetch](https://github.com/tokimo-lab/tokimo-package-web-fetch) - Unified Rust fetcher: plain HTTP, headless browser via Lightpanda, or Cloudflare bypass, with Readability denoising.
- [KakkoiDev/lightpanda-proxy](https://github.com/KakkoiDev/lightpanda-proxy) - Transparent HTTP proxy that renders JavaScript through Lightpanda before handing HTML to text browsers like w3m.
- [ba0f3/gocrawl](https://github.com/ba0f3/gocrawl) - Go crawler with chromedp/Lightpanda auto-fallback for client-rendered pages and challenge pages. Ships a docker-compose with Lightpanda on 9222.
- [cbwln/lightcrawl](https://github.com/cbwln/lightcrawl) - Lightpanda-powered alternative to Firecrawl.
- [raakkan/agents-api](https://github.com/raakkan/agents-api) - Self-hostable scraping, meta-search and screenshot REST API for agents, with Lightpanda CDP as one of the engines.
- [endurance-ai/crawler](https://github.com/endurance-ai/crawler) - Fashion SKU crawler for kiko.ai with a dedicated Lightpanda engine path and automatic engine selection for Cafe24 storefronts.
- [colophon-group/jobseek](https://github.com/colophon-group/jobseek) - Python job crawler replacing Playwright and Chromium with Go and self-hosted Lightpanda, sized for 10M boards and 100M postings.
- [aasenevan-dot/stock-scanner-dashboard](https://github.com/aasenevan-dot/stock-scanner-dashboard) - Lightpanda-powered live market and r/wallstreetbets intelligence dashboard.
- [Ejokey/lightjev](https://github.com/Ejokey/lightjev) - Two-layer crawler: Lightpanda renders the page, then Jev answers two typed questions instead of an LLM call per step. About $0.0001 per decision.
- [coolapso/searchbase](https://github.com/coolapso/searchbase) - Self-hosted, privacy-focused search engine for AI agents and LLMs, with a built-in MCP server and REST API. Ships a Lightpanda fetch worker.
- [PedriniCarbelini/lightpanda-headless-browser](https://github.com/PedriniCarbelini/lightpanda-headless-browser) - Hybrid crawler that renders pages locally with Lightpanda and falls back to hosted Chrome.
- [dmitkov28/aws-lambda-reddit-scraper-lightpanda](https://github.com/dmitkov28/aws-lambda-reddit-scraper-lightpanda) - Reddit scraper running Lightpanda inside AWS Lambda.
- [yulinfeng000/lightpanda-webfetch](https://github.com/yulinfeng000/lightpanda-webfetch) - Web fetch API for LLMs, powered by Lightpanda.
- [hermespromox/browserjev](https://github.com/hermespromox/browserjev) - Low-memory web page classification combining HTTPX, Lightpanda and Jev.
- [paulmeller/camopanda](https://github.com/paulmeller/camopanda) - Lightpanda behind a header-rewriting HTTPS proxy, exposed over CDP for browser agents.
- [TulipFarm/huntsman](https://github.com/TulipFarm/huntsman) - Self-hosted scraper that turns pages into clean Markdown behind a Firecrawl-compatible `/v1/scrape` API, rendering JavaScript with Lightpanda.
- [NiltonGarnica/lightpanda-link-tree](https://github.com/NiltonGarnica/lightpanda-link-tree) - Python microservice that returns a page's link tree as JSON, three levels deep. Opens pages with Lightpanda to find JavaScript-generated links.
- [faisallbhr/logammulia-scraper](https://github.com/faisallbhr/logammulia-scraper) - Node.js scraper for ANTAM gold price history, with Telegram alerts and a GitHub Pages chart. Uses Lightpanda with Puppeteer Core to read the price charts.
- [Amz34/hyper-scrape](https://github.com/Amz34/hyper-scrape) - Web extraction and RAG ingestion engine in three tiers: Scrapling, Lightpanda (Zig and V8) for JavaScript pages, and Crawl4AI as the heavy fallback.
- [bharathvbcr/vani](https://github.com/bharathvbcr/vani) - Job-listing reader in Go that fetches public employer career pages. Custom careers pages are read through one Lightpanda process per board.

## AI Agents and Automation
 
- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Open-source AI assistant running on your own computer. Its browser extension ships a Lightpanda engine, with a pinned Docker sidecar for lightweight installs.
- [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) - Hermes supports Lightpanda as a local agent-browser option, with automatic Chrome fallback.
- [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) - Vercel's browser automation CLI for AI agents. Supports Lightpanda as an engine via `--engine lightpanda` as a faster, lighter alternative to Chrome. Written in Rust.
- [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - End-to-end testing framework for Node.js. Ships a Lightpanda helper that starts `lightpanda serve` itself or attaches to a running instance.
- [tester-army/e2e](https://github.com/tester-army/e2e) - End-to-end testing framework for web and mobile apps. The `@e2e-dev/lightpanda` provider starts one `lightpanda serve` per worker.
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
- [Raknaos/lightpanda-session-bridge](https://github.com/Raknaos/lightpanda-session-bridge) - Chrome extension and Python relay that hands authenticated sessions (Google OAuth, Passkeys, SSO, 2FA) from a real browser into an isolated Lightpanda CDP runtime for AI agents.
- [Cloudgeni-ai/opengeni](https://github.com/Cloudgeni-ai/opengeni) - Self-hostable agentic service platform. Drives Lightpanda as its managed browser engine, with process recovery and input/typing validation built into the CDP driver.
- [Privasys/container-app-lightpanda](https://github.com/Privasys/container-app-lightpanda) - Container app exposing Lightpanda as an MCP `browse` tool, deployable to hardware-attested TDX enclaves.
- [saitanay/panda97](https://github.com/saitanay/panda97) - Lightpanda browser automation for the pi coding agent, installable with `pi install npm:panda97`. Launches a separate Lightpanda process per tab over CDP.
- [harikishantk/mint-webmcp](https://github.com/harikishantk/mint-webmcp) - Headless WebMCP-style MCP server that compiles HTML forms into dynamic form tools via Lightpanda `detectForms`, with safe fill-before-submit and PandaScript export.
- [miraccan00/ig-follow-tracker](https://github.com/miraccan00/ig-follow-tracker) - Small local app built on Lightpanda that tracks Instagram unfollows.
- [Guibibi/pi-lightpanda-extension](https://github.com/Guibibi/pi-lightpanda-extension) - Extension for the `pi` coding agent with Lightpanda web tools, plus Playwright for screenshots.
- [bhumitschaudhry/Meleys](https://github.com/bhumitschaudhry/Meleys) - Rust runtime giving LLM agents control of Lightpanda and Chromium over MCP and REST.
- [lurissarie/local-agent-browser](https://github.com/lurissarie/local-agent-browser) - Local personal agent browser built on Lightpanda.
- [Tariq-Anjum/ai-web-agent-stack](https://github.com/Tariq-Anjum/ai-web-agent-stack) - Local AI web agent stack combining SearXNG, Crawl4AI and agent-browser running on Lightpanda.
- [outmost9271/pi-browser-switch](https://github.com/outmost9271/pi-browser-switch) - `pi` extension that switches between local Chrome and Lightpanda containers.
- [tonyputi/pi-lightpanda](https://github.com/tonyputi/pi-lightpanda) - Extension giving the `pi` coding agent a Lightpanda browser.
- [abdulaaly/omnifast-browser](https://github.com/abdulaaly/omnifast-browser) - Web agent with pluggable browser engines, including Lightpanda.
- [BIackFIame/canvastty-plugin-lightpanda](https://github.com/BIackFIame/canvastty-plugin-lightpanda) - Optional Lightpanda engine for background browsing by CanvasTTY agents.
- [stanleyrprose/mac-browser-plane](https://github.com/stanleyrprose/mac-browser-plane) - Browser execution service for agents running on a Mac mini (exposed over MCP) with Chrome and Lightpanda engines.
- [john-walks-slow/render-browser-gateway](https://github.com/john-walks-slow/render-browser-gateway) - Lightpanda browser gateway for AI agents, sized to run on free hosting tiers.
- [AnEntrypoint/agentplug-lightpanda-bin](https://github.com/AnEntrypoint/agentplug-lightpanda-bin) - WebAssembly build of an agentplug plugin for Lightpanda, published by CI.
- [profullstack/x402-client](https://github.com/profullstack/x402-client) - Client for x402 web payments, with adapters for Lightpanda over CDP and its CLI.
- [sscode/browserlab](https://github.com/sscode/browserlab) - Correctness and regression test suite for browser automation across Chrome and Lightpanda.
- [florianilch/lightpanda-gateway](https://github.com/florianilch/lightpanda-gateway) - Gateway for running agent and scripted Lightpanda workloads on private infrastructure, with process lifecycle and concurrency control.
- [andrey-usa/navigera](https://github.com/andrey-usa/navigera) - Rust CLI and MCP server that lets agents drive a browser, with Lightpanda as an experimental engine (`--engine lightpanda`).
- [mcc0nnell/lightpanda-agent-bridge](https://github.com/mcc0nnell/lightpanda-agent-bridge) - Local MCP stdio bridge for Lightpanda over Unix-domain CDP WebSockets.
- [YekaiY/lightpanda-skill](https://github.com/YekaiY/lightpanda-skill) - Agent skill that teaches AI agents to drive Lightpanda, installable with npx.
- [aakshintala/fiber-lightpanda](https://github.com/aakshintala/fiber-lightpanda) - Fiber extension adding a `web_render` tool that renders JavaScript pages to Markdown with Lightpanda.
- [LdwS123/Instonct](https://github.com/LdwS123/Instonct) - Self-hosted personal AI agent for Telegram and WhatsApp, in Python. Uses Lightpanda over MCP as its browser for web reading and form filling.
- [kuanbandu/dsh-lightpanda-mcp](https://github.com/kuanbandu/dsh-lightpanda-mcp) - DeepSeek Harness (DSH) plugin bundle that mounts `lightpanda mcp` as an MCP tool server for agents.
- [thiagoyb11/UTNFRSF-CampusVirtual-MCP](https://github.com/thiagoyb11/UTNFRSF-CampusVirtual-MCP) - MCP server for the UTN FRSF virtual campus that reads courses, calendars and resources and submits assignments, driving the site with Lightpanda.
- [fufay/dsh-lightpanda-skill](https://github.com/fufay/dsh-lightpanda-skill) - Headless browsing skill for DSH and Whale agents: stateless fetch plus stateful cookie and session work over CDP, with the Lightpanda binary downloaded and checked by sha256.
- [operatecenter/operator-starter](https://github.com/operatecenter/operator-starter) - Starter kit for autonomous AI agents with a console. Lightpanda is one of several pluggable browser runtimes, reached over CDP, alongside Steel, Chromium and MicroVMs.

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
- [deepwatrcreatur/nix-lightpanda](https://github.com/deepwatrcreatur/nix-lightpanda) - Nix package for Lightpanda.
- [surf-ex/surf_board](https://github.com/surf-ex/surf_board) - Elixir library driving Chrome or Lightpanda over CDP and WebDriver BiDi.
- [rcgeorge23/lightpanda-java](https://github.com/rcgeorge23/lightpanda-java) - Experimental Java binding built on the draft C embedding API proposed in [lightpanda-io/browser#3096](https://github.com/lightpanda-io/browser/pull/3096).
- [Wyzix33/lightpanda-windows-native](https://github.com/Wyzix33/lightpanda-windows-native) - Windows port checkpoint with a vendored boringssl-zig and zig-v8-fork, plus CDP smoke tests and a live login test.
- [qidiai/lightpanda-windows-port](https://github.com/qidiai/lightpanda-windows-port) - Community port of Lightpanda to native Windows.
- [mattneel/lightpanda_ex](https://github.com/mattneel/lightpanda_ex) - Mix tasks to install and run Lightpanda from Elixir, modeled on the Phoenix `esbuild` package.

## Resources
 
- [probably-not/lightpanda-wpt-analysis](https://github.com/probably-not/lightpanda-wpt-analysis) - Are We Lightpanda Yet? External tracking of web-platform-test conformance.
- [pleasedodisturb/web-agent-comparison](https://github.com/pleasedodisturb/web-agent-comparison) - Third-party reproducible benchmark of seven browser-automation MCP servers, including Lightpanda.
- [api-evangelist/lightpanda](https://github.com/api-evangelist/lightpanda) - Catalogue profile of Lightpanda, treating the CDP over WebSocket endpoint as the programmable surface, with APIs.json and MCP artifacts refreshed daily.
- [KemalG-u/karincaai-lightpanda-rehberi](https://github.com/KemalG-u/karincaai-lightpanda-rehberi) - Turkish getting-started guide covering which tasks suit Lightpanda and when to keep the Chrome path, with a self-run VPS A/B benchmark against Chrome and the raw data published.
- [fisheeplife-beep/cn-deploy-lightpanda](https://github.com/fisheeplife-beep/cn-deploy-lightpanda) - Unofficial Chinese deployment companion covering China-network installs, Docker, CDP smoke scripts, and common pitfalls.
- [triposat/browser-automation-bench](https://github.com/triposat/browser-automation-bench) - Benchmark comparing Playwright, Puppeteer, Selenium, WebDriver BiDi and Lightpanda.
- [laghoule/lightpanda_browser](https://github.com/laghoule/lightpanda_browser) - Helm chart deploying Lightpanda as a CDP and WebDriver server on Kubernetes.
- [Va55/lightpanda-static](https://github.com/Va55/lightpanda-static) - Fully static musl builds of Lightpanda for x86_64 and 32-bit x86, CI-built, reproducible and attested, with the i386 port patches and build recipe.
- [sidalit/lightpanda-snap](https://github.com/sidalit/lightpanda-snap) - Snap packaging for Lightpanda.
- [handsomejackson/lightpanda-zh](https://github.com/handsomejackson/lightpanda-zh) - Unofficial Chinese tutorial covering install, a first fetch, Puppeteer over CDP, and a memory comparison between Lightpanda and Chrome.
- [Ezra-Zhao/lightpanda-cheatsheet-es-pt](https://github.com/Ezra-Zhao/lightpanda-cheatsheet-es-pt) - One-page Lightpanda cheatsheet in Chinese, English, Spanish and Portuguese: fetch, serve, agent and mcp modes, CDP quickstart and install.
- [linmoxi33/lightpanda-cdp-noop-guard](https://github.com/linmoxi33/lightpanda-cdp-noop-guard) - Offline CI tool that checks CDP traces for methods Lightpanda accepts but silently ignores, with links to the upstream source.
- [KingOfKalk/devcontainer-features](https://github.com/KingOfKalk/devcontainer-features) - Collection of devcontainer features, including one that installs Lightpanda (CDP, fetch, MCP) with telemetry off.
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
