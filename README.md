# mintlify-docs (superseded)

> [!IMPORTANT]
> **This site has moved.** The Nyuchi documentation site is now
> [`nyuchi/nyuchi-docs`](https://github.com/nyuchi/nyuchi-docs) — Astro 6 +
> Starlight, published at [docs.nyuchi.com](https://docs.nyuchi.com). Open
> issues and pull requests there. Nothing in this repository is maintained.

![Status](https://img.shields.io/badge/status-superseded-lightgrey?style=flat-square)
[![Lint](https://github.com/nyuchi/mintlify-docs/actions/workflows/lint.yml/badge.svg)](https://github.com/nyuchi/mintlify-docs/actions/workflows/lint.yml)
![Mintlify](https://img.shields.io/badge/Mintlify-retired-0D9373?style=flat-square)

**Successor:** [docs.nyuchi.com](https://docs.nyuchi.com) (engineering) and [docs.bundu.org](https://docs.bundu.org) (product) | **Superseded:** 24 May 2026

---

## What it is

The first attempt at a Nyuchi documentation site: a [Mintlify](https://mintlify.com)
project generated from the
[`mintlify/product-guide-starter`](https://github.com/mintlify/product-guide-starter)
template on 5 May 2026, filled in over four pull requests, and abandoned
nineteen days later when the docs moved to Astro Starlight.

It holds 36 MDX pages covering the platform, the `/v1` API gateway,
WorkOS sign-in, product workspaces, analytics, integrations and in-app support
chat. That content has been carried over to `nyuchi/nyuchi-docs`. Nothing is
written here any more, and nothing should be: an edit landing in this repo
reaches no reader.

The repository is kept for history — the four content pull requests are the
record of what the API surface looked like in May 2026 — not because it is
expected to come back.

## How to tell it is stale, from the inside

The clearest evidence is `docs.json`. It is still the starter template's
configuration, untouched:

- `"name": "Product Guide"` — the template's name, never changed to Nyuchi
- `"theme": "almond"` with the template's green, not the Nyuchi palette
- Global anchors pointing at **Mintlify's own** changelog and support pages
  rather than Nyuchi's

`AGENTS.md` likewise still opens with the template's own "Customize this file
for your project" instruction. A rebrand was attempted — pull request #5,
_"feat(theme): rebrand the docs site as Nyuchi Docs"_ — and closed unmerged.
That closed PR is the moment the site was given up on.

## If you are looking for the docs

| You want                                   | Go to                                                         |
| ------------------------------------------ | ------------------------------------------------------------- |
| Engineering documentation                  | [docs.nyuchi.com](https://docs.nyuchi.com)                    |
| Product documentation                      | [docs.bundu.org](https://docs.bundu.org)                      |
| The repository behind the engineering docs | [`nyuchi/nyuchi-docs`](https://github.com/nyuchi/nyuchi-docs) |

## Licence

This repository carries no `LICENSE` file. It is Nyuchi-internal documentation
source retained for history; treat it as all rights reserved unless and until
a licence is added.
