# Alleghany Corporation (alleghany)

Alleghany Corporation is a holding company engaged in property and casualty reinsurance and insurance through its subsidiaries, with additional investments in non-financial businesses held via Alleghany Capital. Founded in 1929 by railroad entrepreneurs Oris and Mantis Van Sweringen, the company transitioned over decades from rail holdings into specialty insurance and reinsurance, and is headquartered at One Rockefeller Plaza in New York City.

Its principal insurance subsidiaries are Transatlantic Reinsurance Company (TransRe), a global reinsurer founded in 1977 with roughly 600 employees across 23 offices and more than $40 billion in claims paid to date; RSUI Group, a wholesale excess and surplus (E&S) underwriter spanning Property, Casualty, Professional Liability, Management Liability, and Binding Authority lines; and CapSpecialty, a specialty casualty and surety underwriter. Alleghany Capital holds non-insurance operating companies including toy and collectibles maker Jazwares (Squishmallows, Pokémon, Roblox, and Fortnite licensed lines).

On March 21, 2022, Berkshire Hathaway announced an $11.6 billion all-cash acquisition of Alleghany at $848.02 per share, which closed in October 2022. Alleghany now operates as a wholly-owned subsidiary of Berkshire Hathaway, contributing approximately $8.8 billion in 2025 gross premiums written and roughly $14 billion in insurance float to the parent.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/alleghany/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Insurance, Reinsurance, Property And Casualty, Specialty Insurance, Excess And Surplus, Surety, Financial Services, Holding Company, Berkshire Hathaway Subsidiary, Toys And Collectibles

## Timestamps

- **Created:** 2026-04-19
- **Modified:** 2026-05-23

## APIs

No public APIs are documented. Alleghany Corporation is a holding company; its operating subsidiaries distribute exclusively through reinsurance intermediaries, wholesale brokers, and independent agents, and none of them publish a developer portal, OpenAPI specifications, SDKs, webhook catalogs, or any other machine-readable API artifacts.

The only digital surfaces exposed publicly are gated broker and agent login portals (for example, the RSUI broker portal). The legacy RSUIOnline platform is being retired without a documented public replacement. TransRe maintains a GitHub organization at [`github.com/TransRe`](https://github.com/TransRe) (created February 2014) but it contains zero public repositories.

Contributions welcome if any subsidiary publishes machine-readable API documentation in the future.

## Subsidiaries

| Subsidiary | Business | Acquired | Status |
|---|---|---|---|
| TransRe (Transatlantic Reinsurance Company) | Global treaty & facultative reinsurance | 2012 | Operating |
| RSUI Group | Wholesale E&S specialty insurance | 2003 | Operating |
| CapSpecialty | Specialty casualty & surety insurance | 2002 | Operating |
| Jazwares | Toys, action figures, collectibles (Squishmallows) | Alleghany Capital portfolio | Operating |
| Roundtable Re | Reinsurance | — | Historical / restructured |
| Alleghany Capital | Middle-market non-insurance holdings | — | Operating |

## Berkshire Hathaway Acquisition

- **Announced:** March 21, 2022
- **Closed:** October 2022
- **Total value:** $11.6 billion all-cash
- **Per share:** $848.02
- **Float added to Berkshire:** ~$14 billion
- **GPW contributed (2025):** ~$8.8 billion
- **Press release:** [Berkshire Hathaway news, Mar 21, 2022](https://www.berkshirehathaway.com/news/MAR2122.pdf)

## Common Properties

- [Website](https://www.alleghany.com)
- [ContactUs](https://www.alleghany.com/contact-us/)
- [ParentCompany — Berkshire Hathaway](https://www.berkshirehathaway.com)
- [Subsidiary — TransRe](https://www.transre.com)
- [Subsidiary — RSUI Group](https://www.rsui.com)
- [Subsidiary — CapSpecialty](https://www.capspecialty.com)
- [Subsidiary — Jazwares](https://www.jazwares.com)
- [AgentLogin — RSUI Broker Portal](https://www.rsui.com/brokers/)
- [GitHubOrganization — TransRe (0 public repos)](https://github.com/TransRe)

## Pipeline Notes

This is an x-type `company` repo, but it sits at Tier 3 (`no-apis`) in the master network registry. The full 18-step pipeline was executed on 2026-05-23, with these dispositions:

- **update-apis (step 1)** — apis.yml fully written from first-wave WebFetch on alleghany.com, transre.com, rsui.com, capspecialty.com, jazwares.com, Wikipedia, plus GitHub org lookups.
- **profile-github-org (step 2)** — No `alleghany` GitHub org. Only `TransRe` exists, with 0 public repos. Recorded as a single common GitHubOrganization property.
- **discover-crds (step 3)** — N/A; no Kubernetes-native surface.
- **update-artifacts through generate-finops (steps 4–16)** — Skipped. Per the run-pipeline skill's no-placeholder rule, no `openapi/`, `asyncapi/`, `json-schema/`, `json-structure/`, `json-ld/`, `examples/`, `rules/`, `capabilities/`, `vocabulary/`, `plans/`, `rate-limits/`, or `finops/` artifacts were generated because there is no public API surface across the holding company or any subsidiary.
- **update-apis second pass (step 17)** — Re-confirmed no new artifacts to index.
- **update-readme (step 18)** — This file.

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
