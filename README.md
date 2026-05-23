# Retry backoff + jitter checklist (production defaults)

Production-focused companion repository for a MatrixTrak resource.

## What This Repository Is

This repository is the public distribution surface for the linked MatrixTrak resource.
It is designed for quick implementation support, community sharing, and stable versioned references.

## Canonical MatrixTrak Links

- Resource page (canonical): https://matrixtrak.com/resources/retry-backoff-jitter-checklist
- Primary blog posts:
  - https://matrixtrak.com/blog/backoff-and-jitter-safe-retries

## Resource Summary

Download includes 2 copy/paste files: retry-backoff-jitter-recipes.md (safe defaults, stop rules, 429 handling, caps/budgets) and retry-telemetry-fields.md (log/metric fields + example line for incident debugging).

## Repository Contents

- `resources/` contains shipped files copied from MatrixTrak public ship assets when available
- `docs/post-mapping.md` maps this resource to related blog posts
- `docs/resource-files.md` lists included files and source mapping
- Included shipped files:
  - resources/backoff-and-jitter-safe-retries.zip

## Who This Is For

- Engineers handling production incidents and reliability gaps
- Teams implementing or validating practical safeguards
- Readers coming from community channels who need canonical references

## Included Mapping

Primary mapping (post frontmatter resources):
- backoff-and-jitter-safe-retries - Retries amplify failures: why exponential backoff without jitter creates storms

## Usage Notes

- Treat MatrixTrak pages as the canonical long-form guidance.
- Use this repo for practical implementation support and sharing.
- For updates, always check the canonical resource page first.

## Attribution
Use MatrixTrak canonical links above for the full context and updates.
