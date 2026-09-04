# Awesome Bug Bounty Tools with stars

> A curated list of various bug bounty tools

## Contents

* [Recon](#Recon)
  * [Subdomain Enumeration](#Subdomain-Enumeration)
  * [Port Scanning](#Port-Scanning)
  * [Screenshots](#Screenshots)
  * [Technologies](#Technologies)
  * [Content Discovery](#Content-Discovery)
  * [Content Filtering](#Content-Filtering)
  * [Links](#Links)
  * [Parameters](#Parameters)
  * [Fuzzing](#Fuzzing)
  * [Monitoring](#Monitoring)
  * [Waf Evasion](#Waf-Evasion)

* [Exploitation](#Exploitation)
  * [Command Injection](#Command-Injection)
  * [CORS Misconfiguration](#CORS-Misconfiguration)
  * [CRLF Injection](#CRLF-Injection)
  * [CSRF Injection](#CSRF-Injection)
  * [Directory Traversal](#Directory-Traversal)
  * [File Inclusion](#File-Inclusion)
  * [GraphQL Injection](#GraphQL-Injection)
  * [Header Injection](#Header-Injection)
  * [Insecure Deserialization](#Insecure-Deserialization)
  * [Insecure Direct Object References](#Insecure-Direct-Object-References)
  * [Open Redirect](#Open-Redirect)
  * [Race Condition](#Race-Condition)
  * [Request Smuggling](#Request-Smuggling)
  * [Server Side Request Forgery](#Server-Side-Request-Forgery)
  * [SQL Injection](#SQL-Injection)
  * [XSS Injection](#XSS-Injection)
  * [XXE Injection](#XXE-Injection)
  * [Cache Poisoning](#Web-Cache-Poisoning)

* [Miscellaneous](#Miscellaneous)
  * [Passwords](#Passwords)
  * [Secrets](#Secrets)
  * [Git](#Git)
  * [Buckets](#Buckets)
  * [CMS](#CMS)
  * [JSON Web Token](#JSON-Web-Token)
  * [postMessage](#postMessage)
  * [Subdomain Takeover](#Subdomain-Takeover)
  * [Vulnerability Scanners](#Vulnerability-Scanners)
  * [Forbidden Bypass](#Forbidden-Bypass)
  * [Permutation](#Permutation)
  * [Web Proxy and Traffic Interception](#Web-Proxy-and-Traffic-Interception)
  * [Origin IP](#Origin-IP)
  * [Useful](#Useful)
  * [AI Agents](#AI-Agents)
  * [Uncategorized](#Uncategorized)

***

## Recon

### Subdomain Enumeration

* [Amass](https://github.com/OWASP/Amass) ⭐ 15,097 | 🐛 242 | 🌐 Go | 📅 2026-07-19 - In-depth Attack Surface Mapping and Asset Discovery
* [subfinder](https://github.com/projectdiscovery/subfinder) ⭐ 14,374 | 🐛 7 | 🌐 Go | 📅 2026-09-02 - Subfinder is a subdomain discovery tool that discovers valid subdomains for websites.
* [Sublist3r](https://github.com/aboul3la/Sublist3r) ⭐ 11,032 | 🐛 254 | 🌐 Python | 📅 2024-08-02 - Fast subdomains enumeration tool for penetration testers
* [bbot](https://github.com/blacklanternsecurity/bbot) ⭐ 10,531 | 🐛 39 | 🌐 Python | 📅 2026-09-04 - A recursive internet scanner for hackers
* [knock](https://github.com/guelfoweb/knock) ⭐ 4,185 | 🐛 71 | 🌐 Python | 📅 2026-02-19 - Knockpy is a python tool designed to enumerate subdomains on a target domain through a wordlist.
* [Findomain](https://github.com/Findomain/Findomain) ⭐ 3,789 | 🐛 24 | 🌐 Rust | 📅 2026-08-27 - The fastest and cross-platform subdomain enumerator, do not waste your time.
* [assetfinder](https://github.com/tomnomnom/assetfinder) ⭐ 3,669 | 🐛 43 | 🌐 Go | 📅 2024-06-07 - Find domains and subdomains related to a given domain
* [massdns](https://github.com/blechschmidt/massdns) ⭐ 3,642 | 🐛 14 | 🌐 C | 📅 2026-04-15 - A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration)
* [dnsx](https://github.com/projectdiscovery/dnsx) ⭐ 2,858 | 🐛 6 | 🌐 Go | 📅 2026-08-31 - Dnsx is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers.
* [altdns](https://github.com/infosec-au/altdns) ⭐ 2,505 | 🐛 18 | 🌐 Python | 📅 2025-01-09 - Generates permutations, alterations and mutations of subdomains and then resolves them
* [Sudomy](https://github.com/Screetsec/Sudomy) ⭐ 2,430 | 🐛 41 | 🌐 Shell | 📅 2024-06-27 - Sudomy is a subdomain enumeration tool to collect subdomains and analyzing domains performing automated reconnaissance (recon) for bug hunting / pentesting
* [puredns](https://github.com/d3mondev/puredns) ⭐ 2,239 | 🐛 16 | 🌐 Go | 📅 2026-02-23 - Fast domain resolver and subdomain bruteforcing with accurate wildcard filtering with wildcard(\*)
* [shuffledns](https://github.com/projectdiscovery/shuffledns) ⭐ 1,670 | 🐛 4 | 🌐 Go | 📅 2026-08-31 - shuffleDNS is a wrapper around massdns written in go that allows you to enumerate valid subdomains using active bruteforce as well as resolve subdomains with wildcard handling and easy input-output…
* [hakrevdns](https://github.com/hakluke/hakrevdns) ⭐ 1,573 | 🐛 9 | 🌐 Go | 📅 2026-08-05 - Small, fast tool for performing reverse DNS lookups en masse.
* [VHostScan](https://github.com/codingo/VHostScan) ⭐ 1,310 | 🐛 1 | 🌐 Python | 📅 2025-08-18 - A virtual host scanner that performs reverse lookups
* [dnscan](https://github.com/rbsec/dnscan) ⭐ 1,278 | 🐛 6 | 🌐 Python | 📅 2024-12-17 - dnscan is a python wordlist-based DNS subdomain scanner.
* [scilla](https://github.com/edoardottt/scilla) ⭐ 1,265 | 🐛 8 | 🌐 Go | 📅 2026-08-31 - Information Gathering tool - DNS / Subdomains / Ports / Directories enumeration
* [domain](https://github.com/jhaddix/domain/) ⭐ 941 | 🐛 21 | 🌐 Python | 📅 2020-11-17 - enumall.py Setup script for Regon-ng
* [chaos-client](https://github.com/projectdiscovery/chaos-client) ⭐ 881 | 🐛 7 | 🌐 Go | 📅 2026-08-31 - Go client to communicate with Chaos DNS API.
* [github-subdomains](https://github.com/gwen001/github-subdomains) ⭐ 868 | 🐛 10 | 🌐 Go | 📅 2023-03-28 - This Go tool performs searches on GitHub and parses the results to find subdomains of a given domain.
* [censys-subdomain-finder](https://github.com/christophetd/censys-subdomain-finder) ⭐ 843 | 🐛 4 | 🌐 Python | 📅 2025-05-01 - Perform subdomain enumeration using the certificate transparency logs from Censys.
* [subdominator](https://github.com/RevoltSecurities/Subdominator) ⭐ 808 | 🐛 6 | 🌐 Python | 📅 2026-06-21 - Fast and powerfull to enumerate subdomains (50+ passive results ).
* [domained](https://github.com/TypeError/domained) ⚠️ Archived - Multi Tool Subdomain Enumeration
* [cero](https://github.com/glebarez/cero) ⭐ 693 | 🐛 4 | 🌐 Go | 📅 2024-03-31 - Scrape domain names from SSL certificates of arbitrary hosts
* [bugcrowd-levelup-subdomain-enumeration](https://github.com/appsecco/bugcrowd-levelup-subdomain-enumeration) ⭐ 632 | 🐛 2 | 🌐 Python | 📅 2019-02-05 - This repository contains all the material from the talk "Esoteric sub-domain enumeration techniques" given at Bugcrowd LevelUp 2017 virtual conference
* [haktrails](https://github.com/hakluke/haktrails) ⭐ 603 | 🐛 1 | 🌐 Go | 📅 2026-01-21 - Golang client for querying SecurityTrails API data
* [sub3suite](https://github.com/3nock/sub3suite) ⚠️ Archived - A research-grade suite of tools for subdomain enumeration, intelligence gathering and attack surface mapping.
* [shosubgo](https://github.com/incogbyte/shosubgo) ⭐ 579 | 🐛 1 | 🌐 Go | 📅 2025-09-01 - Small tool to Grab subdomains using Shodan api
* [csprecon](https://github.com/edoardottt/csprecon) ⭐ 526 | 🐛 0 | 🌐 Go | 📅 2026-09-02 - Discover new target domains using Content Security Policy
* [hakip2host](https://github.com/hakluke/hakip2host) ⭐ 467 | 🐛 1 | 🌐 Go | 📅 2022-04-27 - hakip2host takes a list of IP addresses via stdin, then does a series of checks to return associated domain names.
* [Turbolist3r](https://github.com/fleetcaptain/Turbolist3r) ⭐ 398 | 🐛 3 | 🌐 Python | 📅 2025-11-16 - Subdomain enumeration tool with analysis features for discovered domains
* [brutesubs](https://github.com/anshumanbh/brutesubs) ⭐ 260 | 🐛 7 | 🌐 Shell | 📅 2021-08-22 - An automation framework for running multiple open sourced subdomain bruteforcing tools (in parallel) using your own wordlists via Docker Compose
* [tugarecon](https://github.com/LordNeoStark/tugarecon) ⭐ 220 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - Fast subdomains enumeration tool for penetration testers.
* [crtndstry](https://github.com/nahamsec/crtndstry) ⭐ 214 | 🐛 3 | 🌐 Shell | 📅 2020-01-20 - Yet another subdomain finder
* [censys-enumeration](https://github.com/0xbharath/censys-enumeration) ⭐ 156 | 🐛 5 | 🌐 Python | 📅 2022-12-07 - A script to extract subdomains/emails for a given domain using SSL/TLS certificate dataset on Censys
* [dns-parallel-prober](https://github.com/lorenzog/dns-parallel-prober) ⭐ 109 | 🐛 0 | 🌐 Python | 📅 2022-10-04 - his is a parallelised domain name prober to find as many subdomains of a given domain as fast as possible.
* [related-domains](https://github.com/gwen001/related-domains) ⭐ 107 | 🐛 1 | 🌐 Python | 📅 2026-06-05 - Find related domains of a given domain. this tool search for domains that have been registered by the same peoples/companies.
* [gitlab-subdomains](https://github.com/gwen001/gitlab-subdomains) ⭐ 106 | 🐛 2 | 🌐 Go | 📅 2024-04-28 - This Go tool performs searches on GitLab and parses the results to find subdomains of a given domain.
* [Substr3am](https://github.com/nexxai/Substr3am) ⭐ 68 | 🐛 0 | 🌐 Python | 📅 2022-10-11 - Passive reconnaissance/enumeration of interesting targets by watching for SSL certificates being issued
* [Subra](https://github.com/si9int/Subra) ⭐ 55 | 🐛 0 | 🌐 HTML | 📅 2020-06-05 - A Web-UI for subdomain enumeration (subfinder)
* [crt.go](https://github.com/TaurusOmar/crt.sh) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2024-04-23 - This Go script simplifies the process of efficiently saving and analyzing subdomain output from the crt.sh website.
* [as3nt](https://github.com/cinerieus/as3nt) - Another Subdomain ENumeration Tool

### Port Scanning

* [masscan](https://github.com/robertdavidgraham/masscan) ⭐ 25,976 | 🐛 414 | 🌐 C | 📅 2026-04-23 - TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
* [RustScan](https://github.com/RustScan/RustScan) ⭐ 20,365 | 🐛 61 | 🌐 Rust | 📅 2026-08-26 - The Modern Port Scanner
* [nmap](https://github.com/nmap/nmap) ⭐ 13,525 | 🐛 678 | 🌐 C | 📅 2026-09-02 - Nmap - the Network Mapper. Github mirror of official SVN repository.
* [naabu](https://github.com/projectdiscovery/naabu) ⭐ 6,228 | 🐛 0 | 🌐 Go | 📅 2026-08-31 - A fast port scanner written in go with focus on reliability and simplicity.
* [sandmap](https://github.com/trimstray/sandmap) ⭐ 1,862 | 🐛 13 | 🌐 Shell | 📅 2024-11-19 - Nmap on steroids. Simple CLI with the ability to run pure Nmap engine, 31 modules with 459 scan profiles.
* [ScanCannon](https://github.com/johnnyxmas/ScanCannon) ⭐ 479 | 🐛 3 | 🌐 Shell | 📅 2026-08-11 - Combines the speed of masscan with the reliability and detailed enumeration of nmap
* [NimScan](https://github.com/elddy/NimScan/) ⭐ 410 | 🐛 7 | 🌐 Nim | 📅 2022-02-10 - Fast Port Scanner 🚀
* [nrich](https://gitlab.com/shodan-public/nrich) - A command-line tool to quickly analyze all IPs in a file and see which ones have open ports/ vulnerabilities.

### Screenshots

* [aquatone](https://github.com/michenriksen/aquatone) ⚠️ Archived - Aquatone is a tool for visual inspection of websites across a large amount of hosts and is convenient for quickly gaining an overview of HTTP-based attack surface.
* [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness) ⭐ 5,836 | 🐛 29 | 🌐 Python | 📅 2026-01-05 - EyeWitness is designed to take screenshots of websites, provide some server header info, and identify default credentials if possible.
* [Depix](https://github.com/beurtschipper/Depix) ⚠️ Archived - Recovers passwords from pixelized screenshots
* [gowitness](https://github.com/sensepost/gowitness) ⭐ 4,501 | 🐛 42 | 🌐 Go | 📅 2026-04-22 - gowitness - a golang, web screenshot utility using Chrome Headless
* [invisible-playwright](https://github.com/feder-cr/invisible_playwright) ⭐ 1,975 | 🐛 5 | 🌐 Python | 📅 2026-09-04 - Playwright wrapper for a stealth-patched Firefox 150 binary, useful for screenshotting and recon against targets with anti-bot detection (reCAPTCHA v3, FingerprintPro, Cloudflare).
* [screenshoteer](https://github.com/vladocar/screenshoteer) ⭐ 1,668 | 🐛 1 | 🌐 JavaScript | 📅 2021-07-25 - Make website screenshots and mobile emulations from the command line.
* [eyeballer](https://github.com/BishopFox/eyeballer) ⭐ 1,290 | 🐛 9 | 🌐 Python | 📅 2026-03-08 - Convolutional neural network for analyzing pentest screenshots
* [WitnessMe](https://github.com/byt3bl33d3r/WitnessMe) ⭐ 759 | 🐛 24 | 🌐 Python | 📅 2024-09-23 - Web Inventory tool, takes screenshots of webpages using Pyppeteer (headless Chrome/Chromium) and provides some extra bells & whistles to make life easier.
* [httpscreenshot](https://github.com/breenmachine/httpscreenshot/) ⭐ 648 | 🐛 15 | 🌐 Python | 📅 2024-10-01 - HTTPScreenshot is a tool for grabbing screenshots and HTML of large numbers of websites.
* [scrying](https://github.com/nccgroup/scrying) ⭐ 476 | 🐛 36 | 🌐 Rust | 📅 2023-04-03 - A tool for collecting RDP, web and VNC screenshots all in one place

### Technologies

* [httpx](https://github.com/projectdiscovery/httpx) ⭐ 10,355 | 🐛 9 | 🌐 Go | 📅 2026-09-04 - httpx is a fast and multi-purpose HTTP toolkit allows to run multiple probers using retryablehttp library, it is designed to maintain the result reliability with increased threads.
* [whatweb](https://github.com/urbanadventurer/whatweb) ⭐ 6,818 | 🐛 51 | 🌐 Ruby | 📅 2026-04-02 - Next generation web scanner
* [wafw00f](https://github.com/EnableSecurity/wafw00f) ⭐ 6,534 | 🐛 0 | 🌐 Python | 📅 2026-04-19 - wafw00f allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website.
* [retire.js](https://github.com/RetireJS/retire.js) ⭐ 4,165 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-23 - scanner detecting the use of JavaScript libraries with known vulnerabilities
* [webanalyze](https://github.com/rverton/webanalyze) ⭐ 1,171 | 🐛 4 | 🌐 Go | 📅 2026-08-28 - Port of Wappalyzer (uncovers technologies used on websites) to automate mass scanning.
* [tlsx](https://github.com/projectdiscovery/tlsx) ⭐ 1,136 | 🐛 8 | 🌐 Go | 📅 2026-09-02 - A fast and configurable TLS grabber focused on TLS based data collection and analysis.
* [cdncheck](https://github.com/projectdiscovery/cdncheck) ⭐ 987 | 🐛 10 | 🌐 Go | 📅 2026-08-31 - cdncheck is a tool for identifying the technology associated with dns / ip network addresses.
* [graphw00f](https://github.com/dolevf/graphw00f) ⭐ 896 | 🐛 3 | 🌐 Python | 📅 2026-05-16 - graphw00f is GraphQL Server Engine Fingerprinting utility for software security professionals looking to learn more about what technology is behind a given GraphQL endpoint.
* [fingerprintx](https://github.com/praetorian-inc/fingerprintx) ⚠️ Archived - fingerprintx is a standalone utility for service discovery on open ports that works well with other popular bug bounty command line tools.
* [MurMurHash](https://github.com/Viralmaniar/MurMurHash) ⭐ 121 | 🐛 1 | 🌐 Python | 📅 2023-08-30 - This little tool is to calculate a MurmurHash value of a favicon. This favicon hash can be used to look for similar websites on various search engines.
* [python-builtwith](https://github.com/claymation/python-builtwith) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2020-04-12 - BuiltWith API client
* [wappalyzer](https://github.com/AliasIO/wappalyzer) - Identify technology on websites.

### Content Discovery

* [katana](https://github.com/projectdiscovery/katana) ⭐ 17,388 | 🐛 38 | 🌐 Go | 📅 2026-09-04 - A next-generation crawling and spidering framework
* [dirsearch](https://github.com/maurosoria/dirsearch) ⭐ 14,692 | 🐛 22 | 🌐 Python | 📅 2026-09-04 - Web path scanner
* [gobuster](https://github.com/OJ/gobuster) ⭐ 14,078 | 🐛 23 | 🌐 Go | 📅 2026-09-03 - Directory/File, DNS and VHost busting tool written in Go
* [feroxbuster](https://github.com/epi052/feroxbuster) ⭐ 8,053 | 🐛 40 | 🌐 Rust | 📅 2026-09-02 - A fast, simple, recursive content discovery tool written in Rust.
* [hakrawler](https://github.com/hakluke/hakrawler) ⭐ 5,118 | 🐛 9 | 🌐 Go | 📅 2026-08-05 - Simple, fast web crawler designed for easy, quick discovery of endpoints and assets within a web application
* [kiterunner](https://github.com/assetnote/kiterunner) ⭐ 3,252 | 🐛 51 | 🌐 Go | 📅 2026-07-10 - Fast API endpoint bruteforcer and content discovery tool for modern web applications.
* [uncover](https://github.com/projectdiscovery/uncover) ⭐ 3,049 | 🐛 11 | 🌐 Go | 📅 2026-08-31 - uncover is a go wrapper using APIs of well known search engines to quickly discover exposed hosts on the internet.
* [gospider](https://github.com/jaeles-project/gospider) ⭐ 2,996 | 🐛 57 | 🌐 Go | 📅 2024-04-21 - Gospider - Fast web spider written in Go
* [dirstalk](https://github.com/stefanoj3/dirstalk) ⭐ 399 | 🐛 12 | 🌐 Go | 📅 2023-12-24 - Modern alternative to dirbuster/dirb
* [dirbuster-ng](https://github.com/digination/dirbuster-ng) ⭐ 357 | 🐛 5 | 🌐 C | 📅 2020-07-19 - dirbuster-ng is C CLI implementation of the Java dirbuster tool
* [crawley](https://github.com/s0rg/crawley) ⭐ 341 | 🐛 8 | 🌐 Go | 📅 2026-08-21 - fast, feature-rich unix-way web scraper/crawler written in Golang.
* [vaf](https://github.com/andreiverse/vaf) ⭐ 319 | 🐛 5 | 🌐 Nim | 📅 2022-05-29 - Vaf is a cross-platform very advanced and fast web fuzzer written in nim .
* [dirsearch](https://github.com/evilsocket/dirsearch) ⭐ 279 | 🐛 4 | 🌐 Go | 📅 2021-09-27 - A Go implementation of dirsearch.
* [recursebuster](https://github.com/C-Sto/recursebuster) ⭐ 250 | 🐛 9 | 🌐 Go | 📅 2019-10-15 - rapid content discovery tool for recursively querying webservers, handy in pentesting and web application assessments
* [filebuster](https://github.com/henshin/filebuster) ⭐ 223 | 🐛 2 | 🌐 Perl | 📅 2023-02-25 - An extremely fast and flexible web fuzzer

### Content Filtering

* [Hacker-Scoper](https://github.com/ItsIgnacioPortal/Hacker-Scoper) ⭐ 77 | 🐛 5 | 🌐 Go | 📅 2026-07-03 - CLI tool for filtering a mixed list of targets (URLs/IPs) according to the bug-bounty program's scope. The scope can be supplied manually, or it can also be detected automatically by just giving hacker-scoper the name of the targeted company. Hacker-Scoper supports IPs, URLs, wildcards, CIDR ranges, Nmap octet ranges, and even full Regex scopes.

### Links

* [gau](https://github.com/lc/gau) ⭐ 5,081 | 🐛 35 | 🌐 Go | 📅 2026-03-20 - Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl.
* [waybackurls](https://github.com/tomnomnom/waybackurls) ⭐ 4,553 | 🐛 48 | 🌐 Go | 📅 2024-05-01 - Fetch all the URLs that the Wayback Machine knows about for a domain
* [LinkFinder](https://github.com/GerbenJavado/LinkFinder) ⭐ 4,442 | 🐛 53 | 🌐 Python | 📅 2024-04-13 - A python script that finds endpoints in JavaScript files
* [waymore](https://github.com/xnl-h4ck3r/waymore) ⭐ 2,739 | 🐛 3 | 🌐 Python | 📅 2026-06-11 -  Find way more from the Wayback Machine!
* [jsluice](https://github.com/BishopFox/jsluice) ⭐ 1,909 | 🐛 9 | 🌐 Go | 📅 2024-05-22 - This tool extracts URLs, paths, secrets, and other interesting bits from JavaScript files. Values are extracted based not just on how they look, but also based on how they are used.
* [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder) ⭐ 1,590 | 🐛 4 | 🌐 Python | 📅 2026-03-08 -  A python tool used to discover endpoints, potential parameters, and a target specific wordlist for a given target
* [URLFinder](https://github.com/projectdiscovery/urlfinder) ⭐ 908 | 🐛 1 | 🌐 Go | 📅 2026-08-31 - A high-speed tool for passively gathering URLs, optimized for efficient web asset discovery without active scanning.
* [getJS](https://github.com/003random/getJS) ⭐ 892 | 🐛 1 | 🌐 Go | 📅 2026-08-29 -  A tool to fastly get all javascript sources/files
* [BurpJSLinkFinder](https://github.com/InitRoot/BurpJSLinkFinder) ⭐ 821 | 🐛 6 | 🌐 Python | 📅 2024-03-22 - Burp Extension for a passive scanning JS files for endpoint links.
* [jsleak](https://github.com/byt3hx/jsleak) ⭐ 594 | 🐛 5 | 🌐 Go | 📅 2025-09-25 - jsleak is a tool to find secret , paths or links in JavaScript files or source code.
* [GoLinkFinder](https://github.com/0xsha/GoLinkFinder) ⭐ 391 | 🐛 1 | 🌐 Go | 📅 2024-11-10 - A fast and minimal JS endpoint extractor
* [urlgrab](https://github.com/IAmStoxe/urlgrab) ⭐ 344 | 🐛 7 | 🌐 Go | 📅 2020-11-07 - A golang utility to spider through a website searching for additional links.
* [JS-Scan](https://github.com/zseano/JS-Scan) ⭐ 228 | 🐛 0 | 🌐 CSS | 📅 2017-08-22 - a .js scanner, built in php. designed to scrape urls and other info
* [github-endpoints](https://github.com/gwen001/github-endpoints) ⭐ 223 | 🐛 5 | 🌐 Go | 📅 2023-03-28 - This Go tool performs searches on GitHub and parses the results to find endpoints of a given domain.
* [linx](https://github.com/riza/linx) ⭐ 214 | 🐛 0 | 🌐 Go | 📅 2025-05-21 - Reveals invisible links within JavaScript files
* [jsfinder](https://github.com/kacakb/jsfinder) ⭐ 138 | 🐛 2 | 🌐 Go | 📅 2023-05-08 - A tool that scans web pages to find JavaScript file URLs linked in the HTML source code.
* [LinksDumper](https://github.com/arbazkiraak/LinksDumper) ⭐ 93 | 🐛 0 | 🌐 Python | 📅 2019-08-27 - Extract (links/possible endpoints) from responses & filter them via decoding/sorting

### Parameters

* [Arjun](https://github.com/s0md3v/Arjun) ⭐ 6,394 | 🐛 23 | 🌐 Python | 📅 2025-02-20 - HTTP parameter discovery suite.
* [ParamSpider](https://github.com/devanshbatham/ParamSpider) ⭐ 3,164 | 🐛 37 | 🌐 Python | 📅 2026-03-07 - Mining parameters from dark corners of Web Archives.
* [x8](https://github.com/Sh1Yo/x8) ⭐ 2,096 | 🐛 27 | 🌐 Rust | 📅 2024-09-08 - Hidden parameters discovery suite written in Rust.
* [param-miner](https://github.com/PortSwigger/param-miner) ⭐ 1,463 | 🐛 26 | 🌐 Java | 📅 2026-08-13 - This extension identifies hidden, unlinked parameters. It's particularly useful for finding web alterx poisoning vulnerabilities.
* [parameth](https://github.com/maK-/parameth) ⚠️ Archived - This tool can be used to brute discover GET and POST parameters
* [ParamPamPam](https://github.com/Bo0oM/ParamPamPam) ⭐ 276 | 🐛 1 | 🌐 Python | 📅 2022-06-27 - This tool for brute discover GET and POST parameters.

### Fuzzing

* [ffuf](https://github.com/ffuf/ffuf) ⭐ 16,637 | 🐛 233 | 🌐 Go | 📅 2026-08-20 -  Fast web fuzzer written in Go
* [fuzzdb](https://github.com/fuzzdb-project/fuzzdb) ⭐ 8,982 | 🐛 15 | 🌐 PHP | 📅 2023-11-10 - Dictionary of attack patterns and primitives for black-box application fault injection and resource discovery.
* [wfuzz](https://github.com/xmendez/wfuzz) ⭐ 6,569 | 🐛 117 | 🌐 Python | 📅 2026-01-21 - Web application fuzzer
* [IntruderPayloads](https://github.com/1N3/IntruderPayloads) ⭐ 3,976 | 🐛 4 | 🌐 BlitzBasic | 📅 2021-09-27 - A collection of Burpsuite Intruder payloads, BurpBounty payloads, fuzz lists, malicious file uploads and web pentesting methodologies and checklists.
* [fuzz.txt](https://github.com/Bo0oM/fuzz.txt) ⭐ 3,322 | 🐛 8 | 📅 2026-07-28 - Potentially dangerous files
* [fuzzilli](https://github.com/googleprojectzero/fuzzilli) ⭐ 2,340 | 🐛 74 | 🌐 Swift | 📅 2026-09-02 - A JavaScript Engine Fuzzer
* [fuzzapi](https://github.com/Fuzzapi/fuzzapi) ⚠️ Archived - Fuzzapi is a tool used for REST API pentesting and uses API\_Fuzzer gem
* [vaf](https://github.com/d4rckh/vaf) ⭐ 319 | 🐛 5 | 🌐 Nim | 📅 2022-05-29 - very advanced (web) fuzzer written in Nim.
* [qsfuzz](https://github.com/ameenmaali/qsfuzz) ⭐ 300 | 🐛 3 | 🌐 Go | 📅 2023-02-12 - qsfuzz (Query String Fuzz) allows you to build your own rules to fuzz query strings and easily identify vulnerabilities.

### Monitoring

* [bbscope](https://github.com/sw33tLie/bbscope) ⭐ 1,435 | 🐛 17 | 🌐 Go | 📅 2026-09-02 - Scope aggregation tool for HackerOne, Bugcrowd, Intigriti, YesWeHack, Immunefi
* [jsmon](https://github.com/robre/jsmon) ⭐ 738 | 🐛 10 | 🌐 Python | 📅 2024-07-31 - A Javascript change monitoring tool for Bug Bounty.

***

## Exploitation

### Command Injection

* [commix](https://github.com/commixproject/commix) ⭐ 5,834 | 🐛 5 | 🌐 Python | 📅 2026-09-04 - Automated All-in-One OS command injection and exploitation tool.

### CORS Misconfiguration

* [Corsy](https://github.com/s0md3v/Corsy) ⭐ 1,538 | 🐛 13 | 🌐 Python | 📅 2022-09-17 - CORS Misconfiguration Scanner
* [CORStest](https://github.com/RUB-NDS/CORStest) ⭐ 424 | 🐛 7 | 🌐 Python | 📅 2020-08-14 - A simple CORS misconfiguration scanner
* [CorsMe](https://github.com/Shivangx01b/CorsMe) ⭐ 171 | 🐛 4 | 🌐 Go | 📅 2021-11-17 - Cross Origin Resource Sharing MisConfiguration Scanner
* [Corser](https://github.com/cyinnove/corser) ⭐ 61 | 🐛 1 | 🌐 Go | 📅 2024-10-26 - Corser is a Golang CLI Application for Advanced CORS Misconfiguration Detection.
* [cors-scanner](https://github.com/laconicwolf/cors-scanner) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2019-11-18 - A multi-threaded scanner that helps identify CORS flaws/misconfigurations

### CRLF Injection

* [crlfuzz](https://github.com/dwisiswant0/crlfuzz) ⭐ 1,562 | 🐛 1 | 🌐 Go | 📅 2026-08-28 - A fast tool to scan CRLF vulnerability written in Go
* [CRLFsuite](https://github.com/Nefcore/CRLFsuite) ⭐ 598 | 🐛 0 | 🌐 Python | 📅 2023-10-17 - A fast tool specially designed to scan CRLF injection
* [CRLF-Injection-Scanner](https://github.com/MichaelStott/CRLF-Injection-Scanner) ⭐ 162 | 🐛 3 | 🌐 Python | 📅 2024-04-14 - Command line tool for testing CRLF injection on a list of domains.
* [Injectus](https://github.com/BountyStrike/Injectus) ⚠️ Archived - CRLF and open redirect fuzzer

### CSRF Injection

* [XSRFProbe](https://github.com/0xInfection/XSRFProbe) ⭐ 1,304 | 🐛 0 | 🌐 Python | 📅 2026-07-12 -The Prime Cross Site Request Forgery (CSRF) Audit and Exploitation Toolkit.

### Directory Traversal

* [dotdotpwn](https://github.com/wireghoul/dotdotpwn) ⭐ 1,115 | 🐛 3 | 🌐 Perl | 📅 2022-09-28 - DotDotPwn - The Directory Traversal Fuzzer
* [FDsploit](https://github.com/chrispetrou/FDsploit) ⚠️ Archived - File Inclusion & Directory Traversal fuzzing, enumeration & exploitation tool.
* [off-by-slash](https://github.com/bayotop/off-by-slash) ⭐ 266 | 🐛 2 | 🌐 Python | 📅 2021-11-18 - Burp extension to detect alias traversal via NGINX misconfiguration at scale.
* [liffier](https://github.com/momenbasel/liffier) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2026-04-10 - tired of manually add dot-dot-slash to your possible path traversal? this short snippet will increment ../ on the URL.

### File Inclusion

* [LFISuite](https://github.com/D35m0nd142/LFISuite) ⭐ 1,964 | 🐛 28 | 🌐 Python | 📅 2022-04-13 - Totally Automatic LFI Exploiter (+ Reverse Shell) and Scanner
* [liffy](https://github.com/mzfr/liffy) ⭐ 984 | 🐛 1 | 🌐 Python | 📅 2026-05-19 - Local file inclusion exploitation tool
* [LFI-files](https://github.com/hussein98d/LFI-files) ⭐ 129 | 🐛 0 | 📅 2019-10-06 - Wordlist to bruteforce for LFI
* [LFI-Enum](https://github.com/mthbernardes/LFI-Enum) ⭐ 92 | 🐛 0 | 🌐 Shell | 📅 2019-04-08 - Scripts to execute enumeration via LFI
* [Burp-LFI-tests](https://github.com/Team-Firebugs/Burp-LFI-tests) ⭐ 70 | 🐛 0 | 📅 2016-10-04 - Fuzzing for LFI using Burpsuite

### GraphQL Injection

* [inql](https://github.com/doyensec/inql) ⭐ 1,805 | 🐛 30 | 🌐 Kotlin | 📅 2026-06-17 - InQL - A Burp Extension for GraphQL Security Testing
* [GraphQLmap](https://github.com/swisskyrepo/GraphQLmap) ⭐ 1,690 | 🐛 20 | 🌐 Python | 📅 2024-03-11 - GraphQLmap is a scripting engine to interact with a graphql endpoint for pentesting purposes.
* [clairvoyance](https://github.com/nikitastupin/clairvoyance) ⭐ 1,515 | 🐛 42 | 🌐 Python | 📅 2025-12-05 - Obtain GraphQL API schema despite disabled introspection!
* [shapeshifter](https://github.com/szski/shapeshifter) ⭐ 126 | 🐛 3 | 🌐 Python | 📅 2022-03-31 - GraphQL security testing tool
* [graphql\_beautifier](https://github.com/zidekmat/graphql_beautifier) ⭐ 29 | 🐛 2 | 🌐 Ruby | 📅 2017-12-07 - Burp Suite extension to help make Graphql request more readable

### Header Injection

* [headi](https://github.com/mlcsec/headi) ⭐ 298 | 🐛 1 | 🌐 Go | 📅 2024-06-27 - Customisable and automated HTTP header injection.

### Insecure Deserialization

* [ysoserial](https://github.com/frohoff/ysoserial) ⭐ 9,043 | 🐛 47 | 🌐 Java | 📅 2025-12-04 - A proof-of-concept tool for generating payloads that exploit unsafe Java object deserialization.
* [phpggc](https://github.com/ambionics/phpggc) ⭐ 3,882 | 🐛 22 | 🌐 PHP | 📅 2025-09-29 - PHPGGC is a library of PHP unserialize() payloads along with a tool to generate them, from command line or programmatically.
* [ysoserial.net](https://github.com/pwntester/ysoserial.net) ⭐ 3,784 | 🐛 12 | 🌐 C# | 📅 2026-06-11 - Deserialization payload generator for a variety of .NET formatters
* [GadgetProbe](https://github.com/BishopFox/GadgetProbe) ⭐ 621 | 🐛 0 | 🌐 Java | 📅 2021-03-04 - Probe endpoints consuming Java serialized objects to identify classes, libraries, and library versions on remote Java classpaths.

### Insecure Direct Object References

* [Autorize](https://github.com/Quitten/Autorize) ⭐ 1,170 | 🐛 10 | 🌐 Python | 📅 2026-03-21 - Automatic authorization enforcement detection extension for burp suite written in Jython developed by Barak Tawily

### Open Redirect

* [Oralyzer](https://github.com/r0075h3ll/Oralyzer) ⭐ 824 | 🐛 0 | 🌐 Python | 📅 2026-08-26 - Open Redirection Analyzer
* [OpenRedireX](https://github.com/devanshbatham/OpenRedireX) ⭐ 803 | 🐛 5 | 🌐 Python | 📅 2024-07-01 - A Fuzzer for OpenRedirect issues
* [Injectus](https://github.com/BountyStrike/Injectus) ⚠️ Archived - CRLF and open redirect fuzzer
* [dom-red](https://github.com/Naategh/dom-red) ⚠️ Archived - Small script to check a list of domains against open redirect vulnerability

### Race Condition

* [turbo-intruder](https://github.com/PortSwigger/turbo-intruder) ⭐ 1,803 | 🐛 19 | 🌐 Kotlin | 📅 2026-08-13 - Turbo Intruder is a Burp Suite extension for sending large numbers of HTTP requests and analyzing the results.
* [race-the-web](https://github.com/TheHackerDev/race-the-web) ⭐ 636 | 🐛 5 | 🌐 Go | 📅 2022-03-18 - Tests for race conditions in web applications. Includes a RESTful API to integrate into a continuous integration pipeline.
* [razzer](https://github.com/compsec-snu/razzer) ⭐ 377 | 🐛 9 | 🌐 C | 📅 2019-07-10 - A Kernel fuzzer focusing on race bugs
* [racepwn](https://github.com/racepwn/racepwn) ⭐ 273 | 🐛 5 | 🌐 Python | 📅 2022-12-07 - Race Condition framework
* [requests-racer](https://github.com/nccgroup/requests-racer) ⭐ 161 | 🐛 2 | 🌐 Python | 📅 2023-05-22 - Small Python library that makes it easy to exploit race conditions in web apps with Requests.

### Request Smuggling

* [smuggler](https://github.com/defparam/smuggler) ⭐ 2,100 | 🐛 19 | 🌐 Python | 📅 2024-01-02 - Smuggler - An HTTP Request Smuggling / Desync testing tool written in Python 3
* [h2csmuggler](https://github.com/BishopFox/h2csmuggler) ⭐ 815 | 🐛 15 | 🌐 Python | 📅 2022-05-10 - HTTP Request Smuggling over HTTP/2 Cleartext (h2c)
* [http-request-smuggling](https://github.com/anshumanpattnaik/http-request-smuggling) ⭐ 545 | 🐛 0 | 🌐 Python | 📅 2023-12-21 - HTTP Request Smuggling Detection Tool
* [tiscripts](https://github.com/defparam/tiscripts) ⭐ 233 | 🐛 0 | 🌐 Python | 📅 2020-06-11 - These scripts I use to create Request Smuggling Desync payloads for CLTE and TECL style attacks.
* [smugglex](github.com/hahwul/smugglex) - Rust-powered HTTP Request Smuggling Scanner.

### Server Side Request Forgery

* [SSRFmap](https://github.com/swisskyrepo/SSRFmap) ⭐ 3,617 | 🐛 1 | 🌐 Python | 📅 2026-08-10 - Automatic SSRF fuzzer and exploitation tool
* [Gopherus](https://github.com/tarunkant/Gopherus) ⭐ 3,413 | 🐛 11 | 🌐 Python | 📅 2023-04-18 - This tool generates gopher link for exploiting SSRF and gaining RCE in various servers
* [singularity](https://github.com/nccgroup/singularity) ⭐ 1,317 | 🐛 17 | 🌐 JavaScript | 📅 2026-07-21 - A DNS rebinding attack framework.
* [SSRFire](https://github.com/micha3lb3n/SSRFire) ⭐ 969 | 🐛 1 | 🌐 Shell | 📅 2021-12-08 - An automated SSRF finder. Just give the domain name and your server and chill! ;) Also has options to find XSS and open redirects
* [surf](https://github.com/assetnote/surf) ⭐ 758 | 🐛 2 | 🌐 Go | 📅 2026-07-10 - Escalate your SSRF vulnerabilities on Modern Cloud Environments. `surf` allows you to filter a list of hosts, returning a list of viable SSRF candidates.
* [rbndr](https://github.com/taviso/rbndr) ⭐ 757 | 🐛 5 | 🌐 C | 📅 2020-01-16 - Simple DNS Rebinding Service
* [whonow](https://github.com/brannondorsey/whonow) ⭐ 659 | 🐛 9 | 🌐 JavaScript | 📅 2021-12-17 - A "malicious" DNS server for executing DNS Rebinding attacks on the fly (public instance running on rebind.network:53)
* [ground-control](https://github.com/jobertabma/ground-control) ⭐ 548 | 🐛 1 | 🌐 Ruby | 📅 2017-06-12 - A collection of scripts that run on my web server. Mainly for debugging SSRF, blind XSS, and XXE vulnerabilities.
* [dns-rebind-toolkit](https://github.com/brannondorsey/dns-rebind-toolkit) ⭐ 503 | 🐛 3 | 🌐 JavaScript | 📅 2021-10-02 - A front-end JavaScript toolkit for creating DNS rebinding attacks.
* [dref](https://github.com/FSecureLABS/dref) ⭐ 494 | 🐛 2 | 🌐 JavaScript | 📅 2021-04-27 - DNS Rebinding Exploitation Framework
* [B-XSSRF](https://github.com/SpiderMate/B-XSSRF) ⭐ 345 | 🐛 1 | 🌐 PHP | 📅 2019-08-23 - Toolkit to detect and keep track on Blind XSS, XXE & SSRF
* [ssrf-sheriff](https://github.com/teknogeek/ssrf-sheriff) ⭐ 339 | 🐛 1 | 🌐 Go | 📅 2024-10-31 - A simple SSRF-testing sheriff written in Go
* [httprebind](https://github.com/daeken/httprebind) ⭐ 307 | 🐛 3 | 🌐 Python | 📅 2020-08-21 - Automatic tool for DNS rebinding-based SSRF attacks
* [httprebind](https://github.com/daeken/httprebind) ⭐ 307 | 🐛 3 | 🌐 Python | 📅 2020-08-21 - Automatic tool for DNS rebinding-based SSRF attacks
* [lorsrf](https://github.com/knassar702/lorsrf) ⭐ 297 | 🐛 0 | 🌐 Rust | 📅 2024-09-22 - Bruteforcing on Hidden parameters to find SSRF vulnerability using GET and POST Methods
* [extended-ssrf-search](https://github.com/Damian89/extended-ssrf-search) ⭐ 277 | 🐛 2 | 🌐 Python | 📅 2021-02-11 - Smart ssrf scanner using different methods like parameter brute forcing in post and get...
* [dnsFookup](https://github.com/makuga01/dnsFookup) ⭐ 256 | 🐛 17 | 🌐 JavaScript | 📅 2023-05-22 - DNS rebinding toolkit
* [gaussrf](https://github.com/KathanP19/gaussrf) ⭐ 175 | 🐛 1 | 🌐 Shell | 📅 2020-11-11 - Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl and Filter Urls With OpenRedirection or SSRF Parameters.
* [ssrfDetector](https://github.com/JacobReynolds/ssrfDetector) ⭐ 165 | 🐛 2 | 🌐 JavaScript | 📅 2017-06-26 - Server-side request forgery detector
* [grafana-ssrf](https://github.com/RandomRobbieBF/grafana-ssrf) ⭐ 83 | 🐛 0 | 🌐 Python | 📅 2024-06-24 - Authenticated SSRF in Grafana
* [sentrySSRF](https://github.com/xawdxawdx/sentrySSRF) ⭐ 72 | 🐛 1 | 🌐 Python | 📅 2024-05-28 - Tool to searching sentry config on page or in javascript files and check blind SSRF

### SQL Injection

* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,360 | 🐛 32 | 🌐 Python | 📅 2026-09-04 - Automatic SQL injection and database takeover tool
* [ghauri](https://github.com/r0oth3x49/ghauri) ⭐ 4,076 | 🐛 25 | 🌐 Python | 📅 2025-10-04 - An advanced cross-platform tool that automates the process of detecting and exploiting SQL injection security flaws
* [NoSQLMap](https://github.com/codingo/NoSQLMap) ⭐ 3,345 | 🐛 1 | 🌐 Python | 📅 2026-07-28 - Automated NoSQL database enumeration and web application exploitation tool.
* [sqliv](https://github.com/the-robot/sqliv) ⚠️ Archived - massive SQL injection vulnerability scanner
* [SQLiScanner](https://github.com/0xbug/SQLiScanner) ⚠️ Archived - Automatic SQL injection with Charles and sqlmap api
* [mssqlproxy](https://github.com/blackarrowsec/mssqlproxy) ⭐ 776 | 🐛 1 | 🌐 Python | 📅 2021-02-16 - mssqlproxy is a toolkit aimed to perform lateral movement in restricted environments through a compromised Microsoft SQL Server via socket reuse
* [sqli-hunter](https://github.com/zt2/sqli-hunter) ⭐ 433 | 🐛 8 | 🌐 Ruby | 📅 2024-04-27 - SQLi-Hunter is a simple HTTP / HTTPS proxy server and a SQLMAP API wrapper that makes digging SQLi easy.
* [nosqli](https://github.com/Charlie-belmer/nosqli) ⭐ 415 | 🐛 11 | 🌐 Go | 📅 2021-10-31 - NoSql Injection CLI tool, for finding vulnerable websites using MongoDB.
* [ESC](https://github.com/NetSPI/ESC) ⭐ 305 | 🐛 2 | 🌐 C# | 📅 2023-04-25 - Evil SQL Client (ESC) is an interactive .NET SQL console client with enhanced SQL Server discovery, access, and data exfiltration features.
* [waybackSqliScanner](https://github.com/ghostlulzhacks/waybackSqliScanner) ⭐ 202 | 🐛 2 | 🌐 Python | 📅 2019-06-06 - Gather urls from wayback machine then test each GET parameter for sql injection.
* [mssqli-duet](https://github.com/Keramas/mssqli-duet) ⭐ 91 | 🐛 1 | 🌐 Python | 📅 2020-05-10 - SQL injection script for MSSQL that extracts domain users from an Active Directory environment based on RID bruteforcing
* [andor](https://github.com/sadicann/andor) ⭐ 88 | 🐛 0 | 🌐 Go | 📅 2021-12-31 - Blind SQL Injection Tool with Golang
* [BurpSQLTruncSanner](https://github.com/InitRoot/BurpSQLTruncSanner) ⭐ 64 | 🐛 1 | 🌐 Python | 📅 2020-04-17 - Messy BurpSuite plugin for SQL Truncation vulnerabilities.
* [Blinder](https://github.com/mhaskar/Blinder) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2019-09-15 - A python library to automate time-based blind SQL injection
* [SleuthQL](https://github.com/RhinoSecurityLabs/SleuthQL) - Python3 Burp History parsing tool to discover potential SQL injection points. To be used in tandem with SQLmap.
* [burp-to-sqlmap](https://github.com/Miladkhoshdel/burp-to-sqlmap) - Performing SQLInjection test on Burp Suite Bulk Requests using SQLMap

### XSS Injection

* [XSStrike](https://github.com/s0md3v/XSStrike) ⭐ 15,169 | 🐛 94 | 🌐 Python | 📅 2025-04-26 - Most advanced XSS scanner.
* [dalfox](https://github.com/hahwul/dalfox) ⭐ 5,274 | 🐛 0 | 🌐 Rust | 📅 2026-09-03 - DalFox(Finder Of XSS) / Parameter Analysis and XSS Scanning tool based on golang
* [ezXSS](https://github.com/ssl/ezXSS) ⭐ 2,335 | 🐛 5 | 🌐 PHP | 📅 2026-07-08 - ezXSS is an easy way for penetration testers and bug bounty hunters to test (blind) Cross Site Scripting.
* [xssor2](https://github.com/evilcos/xssor2) ⭐ 2,223 | 🐛 4 | 🌐 JavaScript | 📅 2021-12-12 - XSS'OR - Hack with JavaScript.
* [xsscrapy](https://github.com/DanMcInerney/xsscrapy) ⭐ 1,747 | 🐛 38 | 🌐 Python | 📅 2024-06-13 - XSS spider - 66/66 wavsep XSS detected
* [xsshunter](https://github.com/mandatoryprogrammer/xsshunter) ⭐ 1,557 | 🐛 29 | 🌐 JavaScript | 📅 2022-12-07 - The XSS Hunter service - a portable version of XSSHunter.com
* [xsser](https://github.com/epsylon/xsser) ⭐ 1,463 | 🐛 0 | 🌐 Python | 📅 2026-08-30 - Cross Site "Scripter" (aka XSSer) is an automatic -framework- to detect, exploit and report XSS vulnerabilities in web-based applications.
* [weaponised-XSS-payloads](https://github.com/hakluke/weaponised-XSS-payloads) ⭐ 1,406 | 🐛 2 | 🌐 JavaScript | 📅 2023-09-12 - XSS payloads designed to turn alert(1) into P1
* [XSpear](https://github.com/hahwul/XSpear) ⚠️ Archived - Powerful XSS Scanning and Parameter analysis tool\&gem
* [sleepy-puppy](https://github.com/Netflix-Skunkworks/sleepy-puppy) ⭐ 1,044 | 🐛 6 | 🌐 JavaScript | 📅 2018-07-24 - Sleepy Puppy XSS Payload Management Framework
* [findom-xss](https://github.com/dwisiswant0/findom-xss) ⚠️ Archived - A fast DOM based XSS vulnerability scanner with simplicity.
* [JSONBee](https://github.com/zigoo0/JSONBee) ⭐ 767 | 🐛 7 | 🌐 PHP | 📅 2024-05-06 - A ready to use JSONP endpoints/payloads to help bypass content security policy (CSP) of different websites.
* [CSPBypass](https://github.com/renniepak/CSPBypass) ⭐ 717 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-31 - a tool designed to help bypass restrictive Content Security Policies (CSP) and exploit XSS (Cross-Site Scripting) vulnerabilities on sites where injections are blocked by CSPs that only allow certain whitelisted domains.
* [docem](https://github.com/whitel1st/docem) ⭐ 688 | 🐛 1 | 🌐 Python | 📅 2024-01-28 - Uility to embed XXE and XSS payloads in docx,odt,pptx,etc (OXML\_XEE on steroids)
* [bXSS](https://github.com/LewisArdern/bXSS) ⭐ 577 | 🐛 20 | 🌐 JavaScript | 📅 2023-03-04 - bXSS is a utility which can be used by bug hunters and organizations to identify Blind Cross-Site Scripting.
* [BruteXSS](https://github.com/rajeshmajumdar/BruteXSS) ⚠️ Archived - BruteXSS is a tool written in python simply to find XSS vulnerabilities in web application.
* [tracy](https://github.com/nccgroup/tracy) ⭐ 560 | 🐛 22 | 🌐 JavaScript | 📅 2023-03-06 - A tool designed to assist with finding all sinks and sources of a web application and display these results in a digestible manner.
* [ground-control](https://github.com/jobertabma/ground-control) ⭐ 548 | 🐛 1 | 🌐 Ruby | 📅 2017-06-12 - A collection of scripts that run on my web server. Mainly for debugging SSRF, blind XSS, and XXE vulnerabilities.
* [domdig](https://github.com/fcavallarin/domdig) ⭐ 421 | 🐛 1 | 🌐 JavaScript | 📅 2025-11-15 - DOM XSS scanner for Single Page Applications
* [xssValidator](https://github.com/nVisium/xssValidator) ⚠️ Archived - This is a burp intruder extender that is designed for automation and validation of XSS vulnerabilities.
* [JSShell](https://github.com/Den1al/JSShell) ⭐ 364 | 🐛 7 | 🌐 Python | 📅 2022-06-28 - An interactive multi-user web JS shell
* [B-XSSRF](https://github.com/SpiderMate/B-XSSRF) ⭐ 345 | 🐛 1 | 🌐 PHP | 📅 2019-08-23 - Toolkit to detect and keep track on Blind XSS, XXE & SSRF
* [XSS-Radar](https://github.com/bugbountyforum/XSS-Radar) ⭐ 331 | 🐛 9 | 🌐 JavaScript | 📅 2018-01-08 - XSS Radar is a tool that detects parameters and fuzzes them for cross-site scripting vulnerabilities.
* [femida](https://github.com/wish-i-was/femida) ⭐ 284 | 🐛 1 | 🌐 Python | 📅 2019-10-10 - Automated blind-xss search for Burp Suite
* [xssmap](https://github.com/Jewel591/xssmap) ⭐ 270 | 🐛 1 | 🌐 Python | 📅 2020-08-20 - XSSMap 是一款基于 Python3 开发用于检测 XSS 漏洞的工具
* [xsshunter\_client](https://github.com/mandatoryprogrammer/xsshunter_client) ⭐ 259 | 🐛 13 | 🌐 Python | 📅 2022-12-26 - Correlated injection proxy tool for XSS Hunter
* [XSSCon](https://github.com/menkrep1337/XSSCon) ⭐ 246 | 🐛 14 | 🌐 Python | 📅 2019-09-01 - XSSCon: Simple XSS Scanner tool
* [shadow-workers](https://github.com/shadow-workers/shadow-workers) ⭐ 246 | 🐛 1 | 🌐 JavaScript | 📅 2023-10-03 - Shadow Workers is a free and open source C2 and proxy designed for penetration testers to help in the exploitation of XSS and malicious Service Workers (SW)
* [xss2png](https://github.com/vavkamil/xss2png) ⭐ 218 | 🐛 1 | 🌐 Python | 📅 2022-10-11 - PNG IDAT chunks XSS payload generator
* [domxssscanner](https://github.com/yaph/domxssscanner) ⚠️ Archived - DOMXSS Scanner is an online tool to scan source code for DOM based XSS vulnerabilities
* [extended-xss-search](https://github.com/Damian89/extended-xss-search) ⭐ 189 | 🐛 1 | 🌐 Python | 📅 2019-08-03 - A better version of my xssfinder tool - scans for different types of xss on a list of urls.
* [BitBlinder](https://github.com/BitTheByte/BitBlinder) ⭐ 124 | 🐛 0 | 🌐 Python | 📅 2026-05-12 - BurpSuite extension to inject custom cross-site scripting payloads on every form/request submitted to detect blind XSS vulnerabilities
* [XSSOauthPersistence](https://github.com/dxa4481/XSSOauthPersistence) ⭐ 77 | 🐛 0 | 🌐 JavaScript | 📅 2019-01-07 - Maintaining account persistence via XSS and Oauth
* [rexsser](https://github.com/profmoriarity/rexsser) ⭐ 75 | 🐛 1 | 🌐 Python | 📅 2020-11-05 - This is a burp plugin that extracts keywords from response using regexes and test for reflected XSS on the target scope.
* [dom-based-xss-finder](https://github.com/AsaiKen/dom-based-xss-finder) ⭐ 75 | 🐛 19 | 🌐 JavaScript | 📅 2025-06-03 - Chrome extension that finds DOM based XSS vulnerabilities
* [Xss-Sql-Fuzz](https://github.com/jiangsir404/Xss-Sql-Fuzz) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2018-12-04 - burpsuite 插件对GP所有参数(过滤特殊参数)一键自动添加xss sql payload 进行fuzz
* [XSSwagger](https://github.com/vavkamil/XSSwagger) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2019-08-30 - A simple Swagger-ui scanner that can detect old versions vulnerable to various XSS attacks
* [vaya-ciego-nen](https://github.com/hipotermia/vaya-ciego-nen) ⭐ 39 | 🐛 0 | 🌐 JavaScript | 📅 2023-01-20 - Detect, manage and exploit Blind Cross-site scripting (XSS) vulnerabilities.
* [xss-flare](https://github.com/EgeBalci/xss-flare) - XSS hunter on cloudflare serverless workers.
* [XSSTerminal](https://github.com/machinexa2/XSSTerminal) - Develop your own XSS Payload using interactive typing

### XXE Injection

* [XXEinjector](https://github.com/enjoiz/XXEinjector) ⭐ 1,801 | 🐛 0 | 🌐 Ruby | 📅 2024-12-01 - Tool for automatic exploitation of XXE vulnerability using direct and different out of band methods.
* [oxml\_xxe](https://github.com/BuffaloWill/oxml_xxe) ⭐ 1,179 | 🐛 2 | 🌐 Ruby | 📅 2024-12-16 - A tool for embedding XXE/XML exploits into different filetypes
* [docem](https://github.com/whitel1st/docem) ⭐ 688 | 🐛 1 | 🌐 Python | 📅 2024-01-28 - Uility to embed XXE and XSS payloads in docx,odt,pptx,etc (OXML\_XEE on steroids)
* [dtd-finder](https://github.com/GoSecure/dtd-finder) ⭐ 663 | 🐛 1 | 🌐 Kotlin | 📅 2024-02-21 - List DTDs and generate XXE payloads using those local DTDs.
* [xxexploiter](https://github.com/luisfontes19/xxexploiter) ⭐ 617 | 🐛 4 | 🌐 TypeScript | 📅 2023-02-04 - Tool to help exploit XXE vulnerabilities
* [ground-control](https://github.com/jobertabma/ground-control) ⭐ 548 | 🐛 1 | 🌐 Ruby | 📅 2017-06-12 - A collection of scripts that run on my web server. Mainly for debugging SSRF, blind XSS, and XXE vulnerabilities.
* [xxeserv](https://github.com/staaldraad/xxeserv) ⭐ 346 | 🐛 0 | 🌐 Go | 📅 2024-01-03 - A mini webserver with FTP support for XXE payloads
* [B-XSSRF](https://github.com/SpiderMate/B-XSSRF) ⭐ 345 | 🐛 1 | 🌐 PHP | 📅 2019-08-23 - Toolkit to detect and keep track on Blind XSS, XXE & SSRF
* [metahttp](https://github.com/vp777/metahttp) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2020-12-02 - A bash script that automates the scanning of a target network for HTTP resources through XXE

### SSTI Injection

* [tplmap](https://github.com/epinna/tplmap) ⭐ 4,199 | 🐛 46 | 🌐 Python | 📅 2024-04-21 - Server-Side Template Injection and Code Injection Detection and Exploitation Tool
* [SSTImap](https://github.com/vladko312/SSTImap) ⭐ 1,628 | 🐛 13 | 🌐 Python | 📅 2026-08-25 - Automatic SSTI detection tool with interactive interface

### Web-Cache-Poisoning

* [toxicache](https://github.com/xhzeem/toxicache) ⭐ 150 | 🐛 1 | 🌐 Go | 📅 2024-02-21 - Go scanner to find web cache poisoning vulnerabilities in a list of URLs .

### Waf Evasion

* [nomore403](https://github.com/devploit/nomore403) ⭐ 1,872 | 🐛 4 | 🌐 Go | 📅 2026-06-21 - Advanced tool for security researchers to bypass 403/40X restrictions .
* [nowafpls](https://github.com/assetnote/nowafpls/) ⭐ 1,507 | 🐛 3 | 🌐 Python | 📅 2025-07-14 - Burp Plugin to Bypass WAFs through the insertion of Junk Data.
* [Forbidden Buster](https://github.com/Sn1r/Forbidden-Buster) ⭐ 252 | 🐛 0 | 🌐 Python | 📅 2024-08-31 - A tool designed to automate various techniques in order to bypass HTTP 401 and 403 response codes and gain access to unauthorized areas in the system.
* [XFFenum](https://github.com/vavkamil/XFFenum) ⭐ 100 | 🐛 2 | 🌐 Python | 📅 2024-05-03 - A simple tool to bypass 403 forbidden end-points behind load balancers (Cloudflare) based on X-Forwarded-For header.

***

## Miscellaneous

### Passwords

* [thc-hydra](https://github.com/vanhauser-thc/thc-hydra) ⭐ 12,229 | 🐛 49 | 🌐 C | 📅 2026-07-30 - Hydra is a parallelized login cracker which supports numerous protocols to attack.
* [DefaultCreds-cheat-sheet](https://github.com/ihebski/DefaultCreds-cheat-sheet) ⭐ 6,730 | 🐛 0 | 🌐 Python | 📅 2026-07-09 - One place for all the default credentials to assist the Blue/Red teamers activities on finding devices with default password
* [patator](https://github.com/lanjelot/patator) ⭐ 3,928 | 🐛 36 | 🌐 Python | 📅 2025-05-20 - Patator is a multi-purpose brute-forcer, with a modular design and a flexible usage.
* [BruteX](https://github.com/1N3/BruteX) ⭐ 2,300 | 🐛 10 | 🌐 Shell | 📅 2024-08-18 - Automatically brute force all services running on a target.
* [changeme](https://github.com/ztgrace/changeme) ⭐ 1,517 | 🐛 16 | 🌐 Python | 📅 2025-07-08 - A default credential scanner.

### Secrets

* [gitleaks](https://github.com/zricethezav/gitleaks) ⭐ 29,099 | 🐛 474 | 🌐 Go | 📅 2026-08-26 - Scan git repos (or files) for secrets using regex and entropy
* [truffleHog](https://github.com/dxa4481/truffleHog) ⭐ 27,685 | 🐛 539 | 🌐 Go | 📅 2026-09-04 - Searches through git repositories for high entropy strings and secrets, digging deep into commit history
* [git-secrets](https://github.com/awslabs/git-secrets) ⭐ 13,388 | 🐛 131 | 🌐 Shell | 📅 2025-09-17 - Prevents you from committing secrets and credentials into git repositories
* [keyhacks](https://github.com/streaak/keyhacks) ⭐ 6,329 | 🐛 45 | 📅 2026-08-07 - KeyHacks shows methods to validate different API keys found on a Bug Bounty Program or a pentest.
* [gitrob](https://github.com/michenriksen/gitrob) ⚠️ Archived - Reconnaissance tool for GitHub organizations
* [detect-secrets](https://github.com/Yelp/detect-secrets) ⭐ 4,631 | 🐛 178 | 🌐 Python | 📅 2026-04-02 - An enterprise friendly way of detecting and preventing secrets in code.
* [shhgit](https://github.com/eth0izzle/shhgit) ⭐ 3,978 | 🐛 33 | 🌐 JavaScript | 📅 2025-02-28 - Ah shhgit! Find GitHub secrets in real time
* [cariddi](https://github.com/edoardottt/cariddi) ⭐ 3,760 | 🐛 14 | 🌐 Go | 📅 2026-08-31 - Take a list of domains, crawl urls and scan for endpoints, secrets, api keys, file extensions, tokens and more...
* [SecretFinder](https://github.com/m4ll0k/SecretFinder) ⭐ 2,503 | 🐛 49 | 🌐 Python | 📅 2024-05-26 - A python script for finding sensitive data (apikeys, accesstoken,jwt,..) and search anything on javascript files.
* [gitGraber](https://github.com/hisxo/gitGraber) ⭐ 2,385 | 🐛 11 | 🌐 Python | 📅 2026-03-26 - gitGraber: monitor GitHub to search and find sensitive data in real time for different online services
* [noseyparker](https://github.com/praetorian-inc/noseyparker) ⚠️ Archived - Nosey Parker is a command-line program that finds secrets and sensitive information in textual data and Git history.
* [GitMiner](https://github.com/UnkL4b/GitMiner) ⭐ 2,152 | 🐛 13 | 🌐 Python | 📅 2025-11-05 - Tool for advanced mining for content on Github
* [talisman](https://github.com/thoughtworks/talisman) ⭐ 2,096 | 🐛 38 | 🌐 Go | 📅 2026-03-01 - By hooking into the pre-push hook provided by Git, Talisman validates the outgoing changeset for things that look suspicious - such as authorization tokens and private keys.
* [GitGot](https://github.com/BishopFox/GitGot) ⭐ 1,572 | 🐛 4 | 🌐 Python | 📅 2024-03-07 - Semi-automated, feedback-driven tool to rapidly search through troves of public data on GitHub for sensitive secrets.
* [github-search](https://github.com/gwen001/github-search) ⭐ 1,512 | 🐛 1 | 🌐 Python | 📅 2023-02-09 - Tools to perform basic search on GitHub.
* [GitHound](https://github.com/tillson/git-hound) ⭐ 1,455 | 🐛 4 | 🌐 Go | 📅 2026-02-10 - Recon tool leveraging Code Search API. Scans for exposed API keys across all of GitHub, not just known repos and orgs. Support for GitHub dorks.
* [git-all-secrets](https://github.com/anshumanbh/git-all-secrets) ⭐ 1,144 | 🐛 6 | 🌐 Go | 📅 2019-06-25 - A tool to capture all the git secrets by leveraging multiple open source git searching tools
* [earlybird](https://github.com/americanexpress/earlybird) ⭐ 773 | 🐛 23 | 🌐 Go | 📅 2026-05-26 - EarlyBird is a sensitive data detection tool capable of scanning source code repositories for clear text password violations, PII, outdated cryptography methods, key files and more.
* [keyFinder](https://github.com/momenbasel/keyFinder) ⭐ 705 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-19 - A Chrome extension that passively scans web pages for API keys, tokens, and secrets using 80+ regex patterns and Shannon entropy analysis across 10 attack surfaces.
* [repo-supervisor](https://github.com/auth0/repo-supervisor) ⚠️ Archived - Scan your code for security misconfiguration, search for passwords and secrets.
* [rusty-hog](https://github.com/newrelic/rusty-hog) ⭐ 556 | 🐛 18 | 🌐 Rust | 📅 2026-08-03 - A suite of secret scanners built in Rust for performance. Based on TruffleHog
* [whispers](https://github.com/Skyscanner/whispers) ⚠️ Archived - Identify hardcoded secrets and dangerous behaviours
* [git-vuln-finder](https://github.com/cve-search/git-vuln-finder) ⭐ 428 | 🐛 2 | 🌐 Python | 📅 2023-10-07 - Finding potential software vulnerabilities from git commit messages
* [Trufflehog-Chrome-Extension](https://github.com/trufflesecurity/Trufflehog-Chrome-Extension) ⭐ 426 | 🐛 12 | 🌐 JavaScript | 📅 2021-10-16 - Trufflehog-Chrome-Extension
* [dufflebag](https://github.com/BishopFox/dufflebag) ⭐ 305 | 🐛 3 | 🌐 Go | 📅 2023-04-24 - Search exposed EBS volumes for secrets
* [yar](https://github.com/nielsing/yar) ⭐ 240 | 🐛 1 | 🌐 Go | 📅 2021-01-03 - Yar is a tool for plunderin' organizations, users and/or repositories.
* [secret-bridge](https://github.com/duo-labs/secret-bridge) ⭐ 208 | 🐛 13 | 🌐 Python | 📅 2024-10-25 - Monitors Github for leaked secrets
* [js-snitch](https://github.com/vavkamil/js-snitch) ⭐ 148 | 🐛 1 | 🌐 Python | 📅 2025-01-21 - Scans remote JavaScript files with Trufflehog + Semgrep to detect leaked secrets.
* [commit-stream](https://github.com/x1sec/commit-stream) - #OSINT tool for finding Github repositories by extracting commit logs in real time from the Github event API

### Git

* [zizmor](https://github.com/zizmorcore/zizmor) ⭐ 6,442 | 🐛 161 | 🌐 Rust | 📅 2026-09-04 - Static analysis tool for GitHub Actions
* [GitTools](https://github.com/internetwache/GitTools) ⭐ 4,180 | 🐛 1 | 🌐 Shell | 📅 2026-07-15 - A repository with 3 tools for pwn'ing websites with .git repositories available
* [git-dumper](https://github.com/arthaud/git-dumper) ⭐ 2,654 | 🐛 10 | 🌐 Python | 📅 2026-08-28 - A tool to dump a git repository from a website
* [dvcs-ripper](https://github.com/kost/dvcs-ripper) ⭐ 1,785 | 🐛 11 | 🌐 Perl | 📅 2024-07-19 - Rip web accessible (distributed) version control systems: SVN/GIT/HG...
* [gitjacker](https://github.com/liamg/gitjacker) ⭐ 1,607 | 🐛 11 | 🌐 Go | 📅 2025-12-05 - Leak git repositories from misconfigured websites
* [GitHunter](https://github.com/digininja/GitHunter) ⭐ 107 | 🐛 3 | 🌐 Go | 📅 2023-12-18 - A tool for searching a Git repository for interesting content
* [Gato (Github Attack TOolkit)](https://github.com/praetorian-inc/gato) ⚠️ Archived - GitHub Self-Hosted Runner Enumeration and Attack Tool

### Buckets

* [S3Scanner](https://github.com/sa7mon/S3Scanner) ⭐ 3,170 | 🐛 41 | 🌐 Go | 📅 2026-08-03 - Scan for open AWS S3 buckets and dump the contents
* [AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump) ⭐ 1,474 | 🐛 8 | 🌐 Python | 📅 2024-04-10 - Security Tool to Look For Interesting Files in S3 Buckets
* [CloudBrute](https://github.com/0xsha/CloudBrute) ⭐ 1,146 | 🐛 0 | 🌐 Go | 📅 2025-03-09 - Awesome cloud enumerator
* [CloudScraper](https://github.com/jordanpotti/CloudScraper) ⭐ 536 | 🐛 3 | 🌐 Python | 📅 2022-03-07 - CloudScraper: Tool to enumerate targets in search of cloud resources. S3 Buckets, Azure Blobs, Digital Ocean Storage Space.
* [s3tk](https://github.com/ankane/s3tk) ⭐ 460 | 🐛 1 | 🌐 Python | 📅 2026-06-29 - A security toolkit for Amazon S3
* [s3viewer](https://github.com/SharonBrizinov/s3viewer) ⭐ 449 | 🐛 2 | 🌐 Python | 📅 2023-10-11 - Publicly Open Amazon AWS S3 Bucket Viewer
* [festin](https://github.com/cr0hn/festin) ⭐ 233 | 🐛 0 | 🌐 Python | 📅 2020-12-04 - FestIn - S3 Bucket Weakness Discovery
* [S3BucketList](https://github.com/AlecBlance/S3BucketList) ⭐ 133 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-30 - Firefox plugin that lists Amazon S3 Buckets found in requests
* [s3dns](https://github.com/olizimmermann/s3dns) ⭐ 128 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - Passive DNS-based discovery of S3 (and other cloud) buckets by resolving CNAMEs and IPs during recon—ideal for stealthy and early identification of cloud storage exposures
* [s3reverse](https://github.com/hahwul/s3reverse) ⭐ 91 | 🐛 0 | 🌐 Go | 📅 2023-05-06 - The format of various s3 buckets is convert in one format. for bugbounty and security testing.
* [s3\_objects\_check](https://github.com/nccgroup/s3_objects_check) ⭐ 77 | 🐛 2 | 🌐 Python | 📅 2022-03-04 - Whitebox evaluation of effective S3 object permissions, to identify publicly accessible files.
* [S3Cruze](https://github.com/JR0ch17/S3Cruze) ⭐ 74 | 🐛 0 | 🌐 Python | 📅 2019-02-16 - All-in-one AWS S3 bucket tool for pentesters.
* [mass-s3-bucket-tester](https://github.com/random-robbie/mass-s3-bucket-tester) ⭐ 54 | 🐛 3 | 🌐 Python | 📅 2025-12-10 - This tests a list of s3 buckets to see if they have dir listings enabled or if they are uploadable
* [dirlstr](https://github.com/cybercdh/dirlstr) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2021-12-01 - Finds Directory Listings or open S3 buckets from a list of URLs
* [Burp-AnonymousCloud](https://github.com/codewatchorg/Burp-AnonymousCloud) ⭐ 48 | 🐛 1 | 🌐 Java | 📅 2023-01-11 - Burp extension that performs a passive scan to identify cloud buckets and then test them for publicly accessible vulnerabilities
* [kicks3](https://github.com/abuvanth/kicks3) ⚠️ Archived - S3 bucket finder from html,js and bucket misconfiguration testing tool
* [s3cario](https://github.com/0xspade/s3cario) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2021-05-03 - This tool will get the CNAME first if it's a valid Amazon s3 bucket and if it's not, it will try to check if the domain is a bucket name.
* [2tearsinabucket](https://github.com/Revenant40/2tearsinabucket) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-04-22 - Enumerate s3 buckets for a specific target.

### CMS

* [wpscan](https://github.com/wpscanteam/wpscan) ⭐ 9,755 | 🐛 0 | 🌐 Ruby | 📅 2026-08-20 - WPScan is a free, for non-commercial use, black box WordPress security scanner
* [joomscan](https://github.com/OWASP/joomscan) ⭐ 1,194 | 🐛 24 | 🌐 Raku | 📅 2024-09-11 - OWASP Joomla Vulnerability Scanner Project
* [CMSmap](https://github.com/Dionach/CMSmap) ⭐ 1,177 | 🐛 31 | 🌐 Python | 📅 2021-12-01 -  CMSmap is a python open source CMS scanner that automates the process of detecting security flaws of the most popular CMSs.
* [aemhacker](https://github.com/0ang3el/aem-hacker) ⭐ 813 | 🐛 15 | 🌐 Python | 📅 2024-07-28 - Tools to identify vulnerable Adobe Experience Manager (AEM) webapps.
* [pyfiscan](https://github.com/fgeek/pyfiscan) ⭐ 575 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - Free web-application vulnerability and version scanner
* [aemscan](https://github.com/Raz0r/aemscan) ⭐ 187 | 🐛 5 | 🌐 Python | 📅 2023-05-22 - Adobe Experience Manager Vulnerability Scanner
* [WPSpider](https://github.com/cyc10n3/WPSpider) ⚠️ Archived - A centralized dashboard for running and scheduling WordPress scans powered by wpscan utility.
* [Temodar Agent](https://github.com/xeloxa/temodar-agent) ⭐ 60 | 🐛 5 | 🌐 Python | 📅 2026-07-03 - AI-powered WordPress plugin/theme security analysis platform with Semgrep-based static analysis and agent-assisted investigation workflows
* [wprecon](https://github.com/blackcrw/wprecon) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2026-06-05 - Wordpress Recon

### JSON Web Token

* [jwt\_tool](https://github.com/ticarpi/jwt_tool) ⭐ 6,761 | 🐛 74 | 🌐 Python | 📅 2025-05-01 - A toolkit for testing, tweaking and cracking JSON Web Tokens
* [c-jwt-cracker](https://github.com/brendan-rius/c-jwt-cracker) ⭐ 2,562 | 🐛 16 | 🌐 C | 📅 2023-06-02 - JWT brute force cracker written in C
* [jwt-cracker](https://github.com/lmammino/jwt-cracker) ⭐ 1,180 | 🐛 12 | 🌐 JavaScript | 📅 2024-07-13 - Simple HS256 JWT token brute force cracker
* [jwt-hack](https://github.com/hahwul/jwt-hack) ⭐ 1,077 | 🐛 0 | 🌐 Rust | 📅 2026-09-02 - jwt-hack is tool for hacking / security testing to JWT.
* [jwt-heartbreaker](https://github.com/wallarm/jwt-heartbreaker) ⭐ 144 | 🐛 2 | 🌐 Java | 📅 2020-09-21 - The Burp extension to check JWT (JSON Web Tokens) for using keys from known from public sources
* [jwtear](https://github.com/KINGSABRI/jwtear) ⭐ 104 | 🐛 2 | 🌐 Ruby | 📅 2023-03-17 - Modular command-line tool to parse, create and manipulate JWT tokens for hackers
* [jwt-key-id-injector](https://github.com/dariusztytko/jwt-key-id-injector) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2020-11-29 - Simple python script to check against hypothetical JWT vulnerability.

### postMessage

* [postMessage-tracker](https://github.com/fransr/postMessage-tracker) ⭐ 1,337 | 🐛 11 | 🌐 JavaScript | 📅 2024-01-26 - A Chrome Extension to track postMessage usage (url, domain and stack) both by logging using CORS and also visually as an extension-icon
* [PostMessage\_Fuzz\_Tool](https://github.com/kiranreddyrebel/PostMessage_Fuzz_Tool) ⭐ 38 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-17 - #BugBounty #BugBounty Tools #WebDeveloper Tool

### Subdomain Takeover

* [can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz) ⭐ 5,797 | 🐛 215 | 🌐 Python | 📅 2025-02-08 - "Can I take over XYZ?" — a list of services and how to claim (sub)domains with dangling DNS records.
* [dnsReaper](https://github.com/punk-security/dnsReaper) ⭐ 2,217 | 🐛 32 | 🌐 Python | 📅 2025-10-06 - DNS Reaper is yet another sub-domain takeover tool, but with an emphasis on accuracy, speed and the number of signatures in our arsenal!
* [subjack](https://github.com/haccer/subjack) ⭐ 2,112 | 🐛 3 | 🌐 Go | 📅 2026-07-03 - Subdomain Takeover tool written in Go
* [subzy](https://github.com/PentestPad/subzy) ⭐ 1,592 | 🐛 9 | 🌐 Go | 📅 2024-09-10 - Subdomain takeover tool which works based on matching response fingerprints from `can-i-take-over-xyz`.
* [SubOver](https://github.com/Ice3man543/SubOver) ⭐ 970 | 🐛 12 | 🌐 Go | 📅 2023-10-17 - A Powerful Subdomain Takeover Tool
* [tko-subs](https://github.com/anshumanbh/tko-subs) ⭐ 775 | 🐛 4 | 🌐 Go | 📅 2021-01-03 - A tool that can help detect and takeover subdomains with dead DNS records
* [HostileSubBruteforcer](https://github.com/nahamsec/HostileSubBruteforcer) ⭐ 482 | 🐛 6 | 🌐 Ruby | 📅 2021-01-29 - This app will bruteforce for existing subdomains and provide information if the 3rd party host has been properly setup.
* [second-order](https://github.com/mhmdiaa/second-order) ⭐ 408 | 🐛 2 | 🌐 Go | 📅 2026-03-29 - Second-order subdomain takeover scanner
* [autoSubTakeover](https://github.com/JordyZomer/autoSubTakeover) ⭐ 137 | 🐛 3 | 🌐 Python | 📅 2023-08-14 - A tool used to check if a CNAME resolves to the scope address. If the CNAME resolves to a non-scope address it might be worth checking out if subdomain takeover is possible.
* [NSBrute](https://github.com/shivsahni/NSBrute) ⭐ 86 | 🐛 3 | 🌐 Python | 📅 2023-02-02 - Python utility to takeover domains vulnerable to AWS NS Takeover
* [takeover](https://github.com/mzfr/takeover) ⭐ 50 | 🐛 2 | 🌐 Go | 📅 2021-05-23 - A tool for testing subdomain takeover possibilities at a mass scale.
* [cnames](https://github.com/cybercdh/cnames) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-01-29 - take a list of resolved subdomains and output any corresponding CNAMES en masse.
* [subHijack](https://github.com/vavkamil/old-repos-backup/tree/master/subHijack-master) ⭐ 9 | 🐛 0 | 🌐 Perl | 📅 2019-08-15 - Hijacking forgotten & misconfigured subdomains

### Vulnerability Scanners

* [metasploit-framework](https://github.com/rapid7/metasploit-framework) ⭐ 38,943 | 🐛 605 | 🌐 Ruby | 📅 2026-09-03 - Metasploit Framework
* [nuclei](https://github.com/projectdiscovery/nuclei) ⭐ 31,014 | 🐛 102 | 🌐 Go | 📅 2026-09-04 - Nuclei is a fast tool for configurable targeted scanning based on templates offering massive extensibility and ease of use.
* [OWASP ZAP](https://github.com/zaproxy/zaproxy) ⭐ 15,732 | 🐛 860 | 🌐 Java | 📅 2026-09-03 -  World’s most popular free web security tools and is actively maintained by a dedicated international team of volunteers
* [nuclei-templates](https://github.com/projectdiscovery/nuclei-templates) ⭐ 12,912 | 🐛 132 | 🌐 JavaScript | 📅 2026-09-04 - Community curated list of templates for the nuclei engine to find security vulnerabilities.
* [Sn1per](https://github.com/1N3/Sn1per) ⭐ 11,196 | 🐛 8 | 🌐 Shell | 📅 2026-07-04 - Automated pentest framework for offensive security experts
* [nikto](https://github.com/sullo/nikto) ⭐ 10,703 | 🐛 1 | 🌐 Perl | 📅 2026-08-28 - Nikto web server scanner
* [Osmedeus](https://github.com/j3ssie/Osmedeus) ⭐ 6,543 | 🐛 10 | 🌐 Go | 📅 2026-08-08 - Fully automated offensive security framework for reconnaissance and vulnerability scanning
* [retire.js](https://github.com/RetireJS/retire.js) ⭐ 4,165 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-23 - scanner detecting the use of JavaScript libraries with known vulnerabilities
* [flan](https://github.com/cloudflare/flan) ⚠️ Archived - A pretty sweet vulnerability scanner
* [arachni](https://github.com/Arachni/arachni) ⚠️ Archived - Web Application Security Scanner Framework
* [cariddi](https://github.com/edoardottt/cariddi) ⭐ 3,760 | 🐛 14 | 🌐 Go | 📅 2026-08-31 - Take a list of domains, crawl urls and scan for endpoints, secrets, api keys, file extensions, tokens and more...
* [jaeles](https://github.com/jaeles-project/jaeles) ⭐ 2,369 | 🐛 32 | 🌐 Go | 📅 2026-06-20 - The Swiss Army knife for automated Web Application Testing
* [Findsploit](https://github.com/1N3/Findsploit) ⭐ 1,848 | 🐛 1 | 🌐 Shell | 📅 2021-09-27 - Find exploits in local and online databases instantly
* [BlackWidow](https://github.com/1N3/BlackWidow) ⭐ 1,819 | 🐛 3 | 🌐 Python | 📅 2026-04-17 - A Python based web application scanner to gather OSINT and fuzz for OWASP vulnerabilities on a target website.
* [getsploit](https://github.com/vulnersCom/getsploit) ⭐ 1,815 | 🐛 5 | 🌐 Python | 📅 2026-08-31 - Command line utility for searching and downloading exploits
* [SSTImap](https://github.com/vladko312/SSTImap) ⭐ 1,628 | 🐛 13 | 🌐 Python | 📅 2026-08-25 -  SSTImap is a penetration testing software that can check websites for Code Injection and Server-Side Template Injection vulnerabilities and exploit them, giving access to the operating system itself.
* [Lonkero](https://github.com/bountyyfi/lonkero) ⭐ 1,074 | 🐛 12 | 🌐 Rust | 📅 2026-08-16 - Enterprise-grade web vulnerability scanner with 60+ attack modules, built in Rust for penetration testing and security assessments.
* [Vigolium](https://github.com/vigolium/vigolium) ⭐ 1,059 | 🐛 6 | 🌐 Go | 📅 2026-09-04 - High-fidelity vulnerability scanner fusing agentic AI with native speed, modularity, and precision
* [backslash-powered-scanner](https://github.com/PortSwigger/backslash-powered-scanner) ⭐ 717 | 🐛 2 | 🌐 Java | 📅 2025-04-30 - Finds unknown classes of injection vulnerabilities
* [OWASP PTK](https://github.com/DenisPodgurskii/pentestkit) ⭐ 236 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-31 -  Browser-based vulnerability scanner for bug bounty and pentesting workflows, combining DAST, SAST, IAST, and SCA capabilities to detect runtime, source-level, interactive, and dependency-related security issues.
* [Eagle](https://github.com/BitTheByte/Eagle) ⭐ 128 | 🐛 1 | 🌐 Python | 📅 2023-06-04 - Multithreaded Plugin based vulnerability scanner for mass detection of web-based applications vulnerabilities

### Permutation

* [altdns](https://github.com/infosec-au/altdns) ⭐ 2,505 | 🐛 18 | 🌐 Python | 📅 2025-01-09 - Generates permutations, alterations and mutations of subdomains and then resolves them.
* [dnsgen](https://github.com/AlephNullSK/dnsgen) ⭐ 1,078 | 🐛 14 | 🌐 Python | 📅 2025-01-03 - DNSGen is a powerful and flexible DNS name permutation tool designed for security researchers and penetration testers. It generates intelligent domain name variations to assist in subdomain discovery and security assessments.
* [alterx](https://github.com/projectdiscovery/alterx) ⭐ 998 | 🐛 6 | 🌐 Go | 📅 2026-08-31 - Fast and customizable subdomain wordlist generator using DSL. alterx takes patterns as input and generates subdomain permutation wordlist based on that pattern.
* [gotator](https://github.com/Josue87/gotator) ⭐ 533 | 🐛 7 | 🌐 Go | 📅 2022-07-17 - Gotator is a tool to generate DNS wordlists through permutations.
* [ripgen](https://github.com/resyncgg/ripgen) ⭐ 305 | 🐛 3 | 🌐 Rust | 📅 2023-12-02 - Rust-based high performance domain permutation generator.
* [goaltdns](https://github.com/subfinder/goaltdns) ⭐ 213 | 🐛 2 | 🌐 Go | 📅 2019-07-15 - A permutation generation tool written in golang.

### Web Proxy and Traffic Interception

* [mitmproxy](https://github.com/mitmproxy/mitmproxy) ⭐ 44,908 | 🐛 480 | 🌐 Python | 📅 2026-09-01 - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [zaproxy](https://github.com/zaproxy/zaproxy) ⭐ 15,732 | 🐛 860 | 🌐 Java | 📅 2026-09-03 - ZAP is what is known as a “manipulator-in-the-middle proxy.” It stands between the tester’s browser and the web application so that it can intercept and inspect messages sent between browser and web application, modify the contents if needed, and then forward those packets on to the destination.
* [hetty](https://github.com/dstotijn/hetty) ⭐ 12,010 | 🐛 48 | 🌐 Go | 📅 2026-07-21 - hetty is a free opensource alternative to Burpsuite pro
* [proxify](https://github.com/projectdiscovery/proxify) ⭐ 3,066 | 🐛 4 | 🌐 Go | 📅 2026-08-31 - A versatile and portable proxy for capturing, manipulating, and replaying HTTP/HTTPS traffic on the go.
* [FoxyProxy Browser Extension](https://github.com/foxyproxy/browser-extension) ⭐ 516 | 🐛 16 | 🌐 JavaScript | 📅 2026-08-26 - FoxyProxy is an open-source, advanced proxy management tool that completely replaces Chrome's limited proxying capabilities.

### Origin IP

* [hakoriginfinder](https://github.com/hakluke/hakoriginfinder) ⭐ 1,101 | 🐛 1 | 🌐 Go | 📅 2026-08-05 - Tool for discovering the origin host behind a reverse proxy. Useful for bypassing WAFs and other reverse proxies.
* [CloudRip](https://github.com/staxsum/CloudRip) ⭐ 644 | 🐛 0 | 🌐 Python | 📅 2026-07-06 - A tool that helps you find the real IP addresses hiding behind Cloudflare by checking subdomains.

### Useful

* [CyberChef](https://github.com/gchq/CyberChef) ⭐ 35,743 | 🐛 568 | 🌐 JavaScript | 📅 2026-09-04 - The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis
* [interactsh](https://github.com/projectdiscovery/interactsh) ⭐ 4,513 | 🐛 11 | 🌐 Go | 📅 2026-08-31 - Interactsh is an open-source tool for detecting out-of-band interactions. It is a tool designed to detect vulnerabilities that cause external interactions.
* [gf](https://github.com/tomnomnom/gf) ⭐ 2,139 | 🐛 55 | 🌐 Go | 📅 2024-06-08 -  A wrapper around grep, to help you grep for things
* [anew](https://github.com/tomnomnom/anew) ⭐ 1,658 | 🐛 8 | 🌐 Go | 📅 2024-01-12 -  A tool for adding new lines to files, skipping duplicates
* [notify](https://github.com/projectdiscovery/notify) ⭐ 1,611 | 🐛 8 | 🌐 Go | 📅 2026-08-31 - Notify is a Go-based assistance package that enables you to stream the output of several tools (or read from a file) and publish it to a variety of supported platforms.
* [uro](https://github.com/s0md3v/uro) ⭐ 1,590 | 🐛 3 | 🌐 Python | 📅 2025-02-23 -  declutters url lists for crawling/pentesting
* [unfurl](https://github.com/tomnomnom/unfurl) ⭐ 1,341 | 🐛 14 | 🌐 Go | 📅 2023-08-12 -  Pull out bits of URLs provided on stdin
* [qsreplace](https://github.com/tomnomnom/qsreplace) ⭐ 884 | 🐛 16 | 🌐 Go | 📅 2022-11-23 -  Accept URLs on stdin, replace all query string values with a user-supplied value

### AI Agents

* [shannon](https://github.com/KeygraphHQ/shannon) ⭐ 47,723 | 🐛 17 | 🌐 TypeScript | 📅 2026-09-03 - Fully autonomous AI hacker to find actual exploits in your web apps.
* [PentestGPT](https://github.com/GreyDGL/PentestGPT) ⭐ 15,210 | 🐛 73 | 🌐 Python | 📅 2026-07-14 - AI-powered penetration testing assistant that helps automate security testing workflows and vulnerability discovery.
* [Agentic Bug Bounty Hunter](https://github.com/Awarexone/Agentic-Bug-Hunter) ⭐ 4,698 | 🐛 1 | 🌐 Python | 📅 2026-09-04 - Claude Code plugin for autonomous bug bounty hunting across HackerOne, Bugcrowd, Intigriti and Immunefi — 15 skills, 33 commands and 9 agents covering recon-to-report, 21 web vuln classes, web3/meme-coin audits, LLM red-teaming, GraphQL/CORS/JWT/NoSQL scanners and persistent hunt memory. Works with or without a subscription.
* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 888 | 🐛 2 | 🌐 Python | 📅 2026-08-29 - Open source (GPL-3.0) autonomous AI penetration testing platform that orchestrates 80+ tools over MCP with dedicated per-technology offensive sub-agents (GraphQL, Spring Boot, ASP.NET, Node.js, Flask, PHP, Ruby) and a per-finding evidence trail.

***

## Uncategorized

* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) ⭐ 80,628 | 🐛 35 | 🌐 Python | 📅 2026-08-27 - A list of useful payloads and bypass for Web Application Security and Pentest/CTF
* [SecLists](https://github.com/danielmiessler/SecLists) ⭐ 73,271 | 🐛 13 | 🌐 PHP | 📅 2026-09-04 - It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more.
* [android-security-awesome](https://github.com/ashishb/android-security-awesome) ⭐ 9,673 | 🐛 0 | 🌐 Makefile | 📅 2026-08-21 - A collection of android security related resources
* [bounty-targets-data](https://github.com/arkadiyt/bounty-targets-data) ⭐ 3,936 | 🐛 0 | 📅 2026-09-04 - This repo contains hourly-updated data dumps of bug bounty platform scopes (like Hackerone/Bugcrowd/Intigriti/etc) that are eligible for reports
* [awesome-mobile-security](https://github.com/vaib25vicky/awesome-mobile-security) ⭐ 3,528 | 🐛 14 | 📅 2024-03-01 - An effort to build a single place for all useful android and iOS security related stuff.
* [cvemap](https://github.com/projectdiscovery/cvemap) ⭐ 2,647 | 🐛 11 | 🌐 Go | 📅 2026-08-31 - Modern CLI for exploring vulnerability data with powerful search, filtering, and analysis capabilities.
* [ds\_store\_exp](https://github.com/lijiejie/ds_store_exp) ⭐ 1,734 | 🐛 16 | 🌐 Python | 📅 2023-05-06 - A .DS\_Store file disclosure exploit. It parses .DS\_Store file and downloads files recursively.
* [BigBountyRecon](https://github.com/Viralmaniar/BigBountyRecon) ⭐ 1,567 | 🐛 9 | 🌐 C# | 📅 2021-01-29 - BigBountyRecon tool utilises 58 different techniques using various Google dorks and open source tools to expedite the process of initial reconnaissance on the target organisation.
* [awesome-vulnerable-apps](https://github.com/vavkamil/awesome-vulnerable-apps) ⭐ 1,478 | 🐛 3 | 📅 2026-06-15 - Awesome Vulnerable Applications
* [mapcidr](https://github.com/projectdiscovery/mapcidr) ⭐ 1,223 | 🐛 2 | 🌐 Go | 📅 2026-08-31 - Utility program to perform multiple operations for a given subnet/CIDR ranges.
* [asnmap](https://github.com/projectdiscovery/asnmap) ⭐ 1,126 | 🐛 5 | 🌐 Go | 📅 2026-08-31 - Go CLI and Library for quickly mapping organization network ranges using ASN information.
* [Bypass bot detection](https://github.com/portswigger/bypass-bot-detection) ⭐ 500 | 🐛 1 | 🌐 Java | 📅 2025-09-09 - Burp Suite extension that mutates ciphers to bypass TLS-fingerprint based bot detection.
* [bountyplz](https://github.com/fransr/bountyplz) ⭐ 467 | 🐛 5 | 🌐 Shell | 📅 2019-05-10 - Automated security reporting from markdown templates (HackerOne and Bugcrowd are currently the platforms supported)
* [RF Swift](https://github.com/PentHertz/RF-Swift) ⭐ 376 | 🐛 2 | 🌐 Go | 📅 2026-09-04 - A powerful multi-platform RF toolbox that deploys specialized radio tools in seconds on Linux, Windows, and macOS—supporting x86\_64, ARM64 (Raspberry Pi, Apple Silicon), and RISC-V architectures without disrupting your primary OS.
* [cut-cdn](https://github.com/ImAyrix/cut-cdn) ⭐ 352 | 🐛 3 | 🌐 Go | 📅 2026-08-16 - Removing CDN IPs from the list of IP addresses.
* [ARS3NAL](https://github.com/inflictx/Arsenal) ⭐ 172 | 🐛 4 | 🌐 CSS | 📅 2026-07-09 - Offline-first, searchable arsenal for pentest & bug bounty: \~1500 payloads, a click-to-build command generator, GTFOBins, wordlists, an embedded CyberChef, reverse shells and 70 checklists. Self-hosted web app with a live static demo.

***

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, vavkamil has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
