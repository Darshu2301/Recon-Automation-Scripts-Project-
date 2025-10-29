Automated Recon is a modular collection of scripts and wrappers for performing safe, repeatable reconnaissance during authorized network and web security assessments.
It focuses on subdomain discovery, DNS mapping, and passive intelligence gathering with machine-readable outputs (CSV/JSON) for easy reporting.

Why use this repo

Rapid, repeatable recon workflows to find attack surface (subdomains, hosts, historical endpoints).

Combines passive OSINT with safe, polite active checks (with rate limits).

Outputs standardized JSON/CSV for reporting or pipeline automation.

Docker-ready for isolated execution.

Key features

Subdomain enumeration (amass, subfinder, crt.sh scraping fallback).

DNS mapping & resolution (massdns / dnsx style pipeline).

Passive intelligence: crt.sh, Wayback, archive sites, CNAME/A record history (API optional).

HTTP probing & basic fingerprinting (httpx-like checks + screenshot option).

Output formats: consolidated JSON, CSV, and simple HTML atlas.

Rate-limit and polite-scan options + logging.

Dockerfile + quickstart script for reproducible runs.

Modular: use Bash wrappers or Python modules independently.
