# Upptime - Agent Configuration

## Root Configuration

Inherits all behavior from `/AGENTS.md` at the monorepo root. Local rules extend or override the root file for this repository.

## Project Context

This repository contains the open-source uptime monitor and status page for HagiCode, powered by [Upptime](https://github.com/upptime/upptime). Status page is served at [status.hagicode.com](https://status.hagicode.com).

## Working Directory

Run commands from `repos/upptime/`.

## Key Paths

- `.github/workflows/`: Uptime CI, Response Time CI, Graphs CI, Static Site CI, Summary CI
- `history/`: historical uptime and response-time data
- `api/`: generated API endpoints for status data

## Agent Guidelines

- This is a GitHub Actions-driven monitoring repository. Do not add application code.
- Status pages and graphs are auto-generated; do not edit generated outputs manually.
- Incident reports use GitHub Issues.
- Keep `.upptimerc.yml` configuration changes minimal and well-commented.

## References

- `README.md`
- `.upptimerc.yml`
