# Frontier AI Risk Governance Lab

**From safety evaluations to European policy decisions**

An independent, one-page [Quarto](https://quarto.org/) **policy concept** asking how European decision-makers should interpret frontier AI safety evaluations when considering appropriate oversight or safeguards.

The working policy-brief title is **“Making Frontier AI Safety Evaluations Decision-Useful for European Policymakers.”** The hypothetical example concerns a frontier model evaluated for potentially dangerous cyber capabilities. The proposed approach connects **evaluation evidence → risk interpretation → policy response**.

## Status and limits

This is a **proposal**, not an operational software tool, actual model evaluation, completed empirical study, legal opinion, or institutional project. No testing, audit, interviews, or empirical validation has been performed. The hypothetical case does not describe a real safety evaluation. Existing legal obligations and prospective policy suggestions are intentionally distinguished.

This independent concept is relevant to European frontier AI policy discussions, including themes addressed by the [Talos Fellowship](https://www.talosnetwork.org/talos-fellowship), but **no affiliation, endorsement, selection, or collaboration is implied**.

## Proposed deliverable

A short policy brief that: (1) defines a specific gap between publicly documented evaluation findings and policy decisions; (2) reviews a small number of publicly available materials and the relevant EU governance context; and (3) proposes feasible improvements to how evaluation information informs oversight, noting uncertainty and institutional constraints. A compact evidence matrix could serve as supporting material.

## Key references

- [EU AI Act, Article 55: obligations for providers of GPAI models with systemic risk](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-55)
- [European Commission: classification of GPAI models with systemic risk](https://ai-act-service-desk.ec.europa.eu/en/ai-act/faq/when-general-purpose-ai-model-one-systemic-risk)
- [EU AI Act consolidated text (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2024/1689)
- [Talos Fellowship](https://www.talosnetwork.org/talos-fellowship)

These references are starting points, not an exhaustive review.

## Files

- `index.qmd` — main one-page concept.
- `styles.css` — responsive visual design adapted from the author's existing Evidence Lab concept.
- `_quarto.yml` — website configuration.
- `.gitignore` — excluded local/build files.

## Run locally

Install [Quarto](https://quarto.org/docs/get-started/) and run:

```bash
quarto preview
```

Build the site with:

```bash
quarto render
```

Publish **from this repository**, not the original GovAI-oriented repository:

```bash
quarto publish gh-pages
```

If using this publishing approach, configure GitHub Pages for the `gh-pages` branch. No additional images are required for the page to render; the profile area uses a text placeholder by design.

© 2026 Caio Velasco.
