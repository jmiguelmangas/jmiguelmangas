# Hi, I'm Jose Miguel Mangas

[![AutoPulse](https://img.shields.io/badge/Featured-AutoPulse-0F766E)](https://github.com/jmiguelmangas/AutoPulse)
[![AeroRoute MLX](https://img.shields.io/badge/Featured-AeroRoute%20MLX-1D4ED8)](https://github.com/jmiguelmangas/aeroroute-platform)
![Python](https://img.shields.io/badge/Python-FastAPI-3776AB?logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-TypeScript-61DAFB?logo=react&logoColor=111111)
![MongoDB](https://img.shields.io/badge/MongoDB-geospatial-47A248?logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-CI%2FCD-2496ED?logo=docker&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-contracts-6BA539?logo=openapiinitiative&logoColor=white)

I'm a product-minded Python / full-stack developer based in Madrid, working at
the intersection of business analysis, operational tooling, automation and data
products.

My work is focused on understanding business workflows, turning messy
operational needs into usable tools, and building systems that make decisions,
reporting and daily execution easier. Outside work, I build portfolio projects
that combine backend engineering, data ingestion, geospatial search, analytics,
automation, synthetic trajectory modeling and polished frontend experiences.

## What I Build

- Internal tools for operations, planning, reporting and workflow automation.
- Data products with APIs, ingestion pipelines, dashboards and quality checks.
- Full-stack applications that connect business context with clean technical
  execution.
- AI-assisted and automation-first developer workflows.

## Featured Projects

### AutoPulse

Automotive intelligence platform for EV charging infrastructure.

- FastAPI backend with station search, route planning, analytics and admin data
  quality APIs.
- MongoDB geospatial data model with Open Charge Map ingestion.
- React + TypeScript frontend with MapLibre, bento-style UI, station cards,
  modeled availability and route recommendations.
- Shared OpenAPI/TypeScript contracts, CI, metrics and structured logging.

Repos:

- [AutoPulse base](https://github.com/jmiguelmangas/AutoPulse)
- [autopulse-api](https://github.com/jmiguelmangas/autopulse-api)
- [autopulse-frontend](https://github.com/jmiguelmangas/autopulse-frontend)
- [autopulse-worker](https://github.com/jmiguelmangas/autopulse-worker)
- [autopulse-contracts](https://github.com/jmiguelmangas/autopulse-contracts)

### AeroRoute MLX

Educational flight-trajectory efficiency simulator: a deterministic 4D route
optimizer, a PostGIS-backed FastAPI service, a React/MapLibre frontend, and a
locally-run Apple Silicon LLM (MLX, Gemma 3) that explains — but is
contractually forbidden from computing — the result.

![AeroRoute MLX: route comparison, deterministic AI explanation and operational-safety gates](https://raw.githubusercontent.com/jmiguelmangas/aeroroute-platform/main/assets/screenshots/results-comparison.png)

- **Deterministic core, probabilistic explanation, strictly separated.** A
  custom layered label-setting solver computes routes, fuel and scoring; the
  local LLM only narrates an already-computed result, with output validators
  (not just prompting) that reject any invented or mismatched number.
- **A measured model bake-off, not a preference call.** Chose the base model
  by running a 24-case evaluation corpus against 3 candidates and recording
  pass rate, latency and memory — including a case where a challenger failed
  most cases, and documenting why rather than discarding the result.
- **Fail-closed safety, visible at runtime.** Filing/dispatch/operator-
  approval gates are real API fields with automated regression tests that
  fail if a future endpoint quietly weakens the non-operational boundary.
- **Eight independently versioned repositories** (web, API, optimizer,
  native MLX service, offline training, data curation, cross-language
  contracts, platform) with a pinned release manifest and a guardrail that
  fails the build if a component's pinned version drifts from what's
  actually checked out.

Repos:

- [aeroroute-platform](https://github.com/jmiguelmangas/aeroroute-platform)
- [aeroroute-api](https://github.com/jmiguelmangas/aeroroute-api)
- [aeroroute-web](https://github.com/jmiguelmangas/aeroroute-web)
- [aeroroute-optimizer](https://github.com/jmiguelmangas/aeroroute-optimizer)
- [aeroroute-data](https://github.com/jmiguelmangas/aeroroute-data)
- [aeroroute-contracts](https://github.com/jmiguelmangas/aeroroute-contracts)
- [aeroroute-mlx](https://github.com/jmiguelmangas/aeroroute-mlx)
- [aeroroute-mlx-training](https://github.com/jmiguelmangas/aeroroute-mlx-training)

### Operations and Productivity Tools

Personal projects around crew/operations workflows, internal productivity,
automation, dashboards and business process support.

Examples from my workspace include Crewfinder, Crewcast, BambooHR time tracking
automation and operational pathfinder tools.

## Tech I Use

**Backend and data:** Python, FastAPI, Django, Pydantic, SQL, MongoDB, PyMongo,
HTTPX, data validation, API integrations.

**Frontend:** React, TypeScript, Vite, TanStack Query, MapLibre, HTML, CSS,
design tokens and reusable component systems.

**Automation and operations:** CLI tools, scheduled jobs, ingestion workers,
business process automation, reporting workflows.

**Quality and delivery:** Pytest, Ruff, Vitest, ESLint, OpenAPI, generated
contracts, GitHub Actions, Docker, observability and structured logging.

**AI workflow:** Codex, prompt-driven development, rapid prototyping and
AI-assisted architecture exploration.

## Current Focus

- Building portfolio-grade products that show both engineering depth and
  business understanding.
- Turning operational workflows into reliable software.
- Improving frontend/product design so tools feel clear, useful and polished.
- Connecting APIs, geospatial data, analytics and automation into cohesive
  applications.

## Contact

- Email: [jmmangas@gmail.com](mailto:jmmangas@gmail.com)
- Phone: [+34 667 475 165](tel:+34667475165)
- LinkedIn: [Jose Mangas](https://www.linkedin.com/in/josemmangasdeveloper/)
- GitHub: [jmiguelmangas](https://github.com/jmiguelmangas)
- HackerRank: [jmmangas](https://www.hackerrank.com/profile/jmmangas)
