# Curation Guidelines

This document records inclusion/exclusion criteria and editorial decisions for Awesome S-100.

## Scope

**In scope:** IHO S-100 Universal Hydrographic Data Model and the product specifications built on it, plus the governance structures, tools, registries, and learning resources that make up the S-100 ecosystem.

**Out of scope:**
- IHO S-57 and pre-S-100 standards (except as migration context)
- General hydrographic or marine GIS tools not implementing S-100
- IALA standards that do not reference S-100 directly

## Product specification table schema

Each row in a product specification table uses these columns:

| Column | Content |
|---|---|
| **ID** | Official IHO or IALA identifier (e.g. S-101, S-201) |
| **Title** | Official English title |
| **Body** | Responsible body or working group |
| **Edition** | Current published edition (e.g. 2.0.0). Use `—` if not yet published. |
| **Status** | One of the status codes below |
| **Links** | One or more stable links (see link policy) |

## Status codes

| Symbol | Status | Meaning |
|---|---|---|
| 🟢 | Operational | Formally adopted and in active operational use |
| 🟡 | Testing | Published for testing; not yet operational |
| 🔵 | Under Development | Work in progress; no published edition |
| ⚪ | Proposed | Scope agreed but development not yet started |
| ⚫ | Withdrawn | Deprecated or superseded |

## Link policy

1. **Primary:** IHO GI Registry entry or official product page — these change less often than PDF URLs.
2. **Secondary:** Direct PDF link labelled `[PDF]`, added only when a stable page also exists.
3. **Tertiary:** GitHub repository for open schemas or catalogues.

Direct PDF links as the sole link are not accepted because IHO PDF URLs change on every new edition.

## Freshness

The `Last verified` date in the Product Specifications section header must be updated whenever any row changes. The authoritative current version is always the [IHO GI Registry](https://registry.iho.int/).

## Copyright

IHO and IALA documents are protected. This list links to them but does not reproduce, rehost, or paraphrase their substantive content. Do not commit spec PDFs or FC/PC XML files to this repository.
