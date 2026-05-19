# EPA Enforcement Check

Search environmental violation records by company name. Find out which companies have been penalized under the Clean Air Act, Clean Water Act, RCRA, and other environmental laws.

**Live:** https://GreatTombProductions.github.io/epa-enforcement/

## What This Shows

- **178,000+ companies** with environmental enforcement records
- **187,000+ facilities** with violations, penalties, or noncompliance
- **$11.5 billion** in total assessed penalties
- **78,000+ formal enforcement actions**

Covers six federal environmental programs:
- **Clean Air Act (CAA)** — air pollution controls
- **Clean Water Act (CWA)** — water discharge permits
- **RCRA** — hazardous waste handling
- **Safe Drinking Water Act (SDWA)** — public water systems
- **Toxics Release Inventory (TRI)** — chemical releases
- **Greenhouse Gas Reporting** — CO2 emissions

## Why This Exists

EPA enforcement data is technically public through the [ECHO system](https://echo.epa.gov), but the interface only supports looking up one facility at a time. There's no practical way to ask "how many facilities does this company have violations at?" or "what's their total penalty history?"

A company with 274 facilities and $1.3 billion in penalties looks the same as one with a single clean facility — unless you aggregate the data.

This tool pre-aggregates 3.1 million regulated facility records into a searchable index by company name.

## Data Source

[EPA ECHO Exporter](https://echo.epa.gov/tools/data-downloads) — updated weekly. Single bulk download containing all regulated facilities with inspection, violation, enforcement, and penalty data.

## How It Works

Static site. No server, no API, no tracking. All data is pre-processed into JSON shards that load on demand. Your search query never leaves your browser.

Built by [Great Tomb Productions](https://github.com/GreatTombProductions).
