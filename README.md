# Awesome S-100 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for the IHO S-100 Universal Hydrographic Data Model and its family of product specifications.

S-100 is the IHO's framework for next-generation digital maritime standards — the foundation for ECDIS, e-Navigation, and interoperable hydrographic data exchange.

## Contents

- [Start Here](#start-here)
- [The S-100 Standard](#the-s-100-standard)
- [Product Specifications](#product-specifications)
- [Governance & Working Groups](#governance--working-groups)
- [Meetings & Schedule](#meetings--schedule)
- [Registries & Catalogues](#registries--catalogues)
- [Tools & Software](#tools--software)
- [Test Data & Samples](#test-data--samples)
- [Related Standards](#related-standards)
- [Learning Resources](#learning-resources)

---

## Start Here

New to S-100? Read these five resources in order.

- [S-100 Edition 5.2.0](https://iho.int/en/s-100-universal-hydrographic-data-model) — The foundation document. Part 1 (General) and Part 2 (Data Model) give the conceptual framework everything else builds on.
- [IHO GI Registry](https://registry.iho.int/) — The authoritative catalogue of all S-100 product specifications, feature concepts, and portrayal items. When in doubt, start here.
- [IHO S-100 Working Group (S-100WG)](https://iho.int/en/s-100wg) — Tracks active development across the specification family. The meeting reports give the clearest current picture of what is being built.
- [IALA S-100 Resources](https://www.iala-aism.org/technical/data-modelling/) — IALA's S-100-based product specifications (S-125, S-126, S-201, S-211) and guidance for Aids to Navigation.
- [IMO e-Navigation Strategy](https://www.imo.org/en/OurWork/Safety/Pages/eNavigation.aspx) — Understanding why Phase 1 S-100 products (S-101, S-102, S-104, S-111, S-124, S-129) became operationally required in 2026 requires this background.

---

## The S-100 Standard

- [S-100 Universal Hydrographic Data Model](https://iho.int/en/s-100-universal-hydrographic-data-model) — Current edition: 5.2.0. Defines the data model, registry framework, metadata, portrayal, and encoding rules used by all S-100-based product specifications.
- [S-97 IHO Portrayal Register](https://registry.iho.int/) — Register of portrayal concepts shared across product specifications.
- [IHO Publications](https://iho.int/en/standards-and-specifications) — Complete list of IHO standards and specifications in force.

---

## Product Specifications

> Last verified: 2026-07-24. Authoritative current versions are always the [IHO GI Registry](https://registry.iho.int/).
>
> **Status legend:** 🟢 Operational · 🟡 Testing · 🔵 Under Development · ⚪ Proposed · ⚫ Withdrawn

### Navigation

| ID | Title | Body | Edition | Status | Links |
|---|---|---|---|---|---|
| S-101 | Electronic Navigational Chart | ENCWG | 2.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-101-electronic-navigational-chart) |
| S-102 | Bathymetric Surface | S-102PT | 3.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-102-bathymetric-surface) |
| S-104 | Water Level Information for Surface Navigation | NIPWG | 2.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-104) |
| S-111 | Surface Currents | NIPWG | 2.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-111) |
| S-129 | Under Keel Clearance Management (UKC) | ENCWG | 1.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-129) |

### Nautical Publications & Information

| ID | Title | Body | Edition | Status | Links |
|---|---|---|---|---|---|
| S-122 | Marine Protected Areas | S-122PT | — | 🔵 Under Development | [IHO](https://iho.int/en/s-122) |
| S-123 | Marine Radio Services | NIPWG | — | 🟡 Testing | [IHO](https://iho.int/en/s-123) |
| S-124 | Navigational Warnings | NIPWG | 1.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-124) |
| S-127 | Marine Traffic Management | NIPWG | — | 🔵 Under Development | [IHO](https://iho.int/en/s-127) |
| S-128 | Catalogue of Nautical Products | ENCWG | 1.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-128) |
| S-131 | Marine Harbour Infrastructure | ENCWG | — | 🔵 Under Development | [IHO](https://iho.int/en/s-131) |

### Aids to Navigation

| ID | Title | Body | Edition | Status | Links |
|---|---|---|---|---|---|
| S-125 | Marine Aids to Navigation (Information) | IALA/IHO | 1.0.0 | 🟢 Operational | [IALA](https://www.iala-aism.org/technical/data-modelling/) |
| S-126 | Marine Radio Aids to Navigation | IALA | — | 🔵 Under Development | [IALA](https://www.iala-aism.org/technical/data-modelling/) |
| S-201 | Aids to Navigation Information | IALA | 0.0.5 | 🟡 Testing | [IALA](https://www.iala-aism.org/technical/data-modelling/) |
| S-211 | Port Call Message Format | IALA | — | 🔵 Under Development | [IALA](https://www.iala-aism.org/technical/data-modelling/) |

### Limits & Boundaries

| ID | Title | Body | Edition | Status | Links |
|---|---|---|---|---|---|
| S-121 | Maritime Limits and Boundaries | ENCWG | 1.0.0 | 🟡 Testing | [IHO](https://iho.int/en/s-121) |
| S-130 | Work in Progress | — | — | 🔵 Under Development | — |

### Route & Voyage

| ID | Title | Body | Edition | Status | Links |
|---|---|---|---|---|---|
| S-421 | Route Plan | NIPWG | — | 🔵 Under Development | [IHO](https://iho.int/en/s-421) |

### Testing & Support

| ID | Title | Body | Edition | Status | Links |
|---|---|---|---|---|---|
| S-98 | IHO Encoding Guide for ECDIS | IHO | 2.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-98) |
| S-158 | Ports and Waterways | IHO | 1.0.0 | 🟡 Testing | [IHO](https://iho.int/en/s-158) |
| S-164 | IHO Test Data Sets for ECDIS | IHO | 4.0.0 | 🟢 Operational | [IHO](https://iho.int/en/s-164) |

---

## Governance & Working Groups

| Body | Scope | Supervises |
|---|---|---|
| [HSSC](https://iho.int/en/hssc) | IHO Hydrographic Services and Standards Committee — top-level governance | All S-100 WGs |
| [S-100WG](https://iho.int/en/s-100wg) | Maintains the S-100 framework itself; coordinates across product spec WGs | S-100 Ed. 5.x |
| [ENCWG](https://iho.int/en/enc-working-group) | ENC products | S-101, S-102, S-121, S-128, S-129, S-131 |
| [NIPWG](https://iho.int/en/nipwg) | Nautical Information Products | S-104, S-111, S-123, S-124, S-127, S-421 |
| [IALA ENAV](https://www.iala-aism.org/committees/enav/) | AtoN and e-Navigation | S-125, S-126, S-201, S-211 |
| [IMO NCSR](https://www.imo.org/en/MediaCentre/MeetingSummaries/Pages/NCSR.aspx) | Navigation, Communications and Search and Rescue — endorses Phase adoption | Phase 1 rollout |

---

## Meetings & Schedule

Rather than listing individual meeting dates (which rot quickly), this section points to each body's official schedule page and notes the typical cadence.

| Body | Cadence | Official Schedule |
|---|---|---|
| HSSC | Annual (typically Q4) | [HSSC meetings](https://iho.int/en/hssc-meetings) |
| S-100WG | 2–3 times per year | [S-100WG meetings](https://iho.int/en/s-100wg-meetings) |
| NIPWG | 2 times per year | [NIPWG meetings](https://iho.int/en/nipwg-meetings) |
| ENCWG | 2 times per year | [ENCWG meetings](https://iho.int/en/encwg-meetings) |
| IALA ENAV | 2 times per year | [ENAV meetings](https://www.iala-aism.org/committees/enav/) |

---

## Registries & Catalogues

- [IHO GI Registry](https://registry.iho.int/) — Central registry for S-100 concepts, features, attributes, and portrayal items. The canonical source for FC and PC content.
- [IHO GI Registry API](https://registry.iho.int/api) — REST API for programmatic access to register contents.
- [S-100 Feature Catalogues](https://registry.iho.int/) — Per-specification FCs are linked from each product spec's GI Registry entry.
- [S-100 Portrayal Catalogues](https://registry.iho.int/) — Per-specification PCs, also accessible via the GI Registry.

---

## Tools & Software

### Open Source

- [s100py](https://github.com/noaa-ocs-hydrography/s100py) — Python library for reading and writing S-100 HDF5-based product files (S-102, S-104, S-111).
- [GDAL](https://gdal.org/) — Geospatial Data Abstraction Library with S-100 drivers for S-101, S-102, and related formats.
- [OpenCPN](https://opencpn.org/) — Open-source chart plotter with S-63/S-101 display capability.

### Commercial

- [CARIS BATHY DataBASE](https://teledynecaris.com/) — Hydrographic data management with S-100 export support.
- [SevenCs Karta](https://www.sevencs.com/) — ENC production and S-101 toolchain.
- [Metis ECDIS](https://www.metisnavigation.com/) — ECDIS system with S-100 Phase 1 support.

### Validation & Testing

- [S-100 Validation Tool](https://iho.int/en/s-100-validation) — IHO reference validator for S-100 exchange sets.

---

## Test Data & Samples

- [S-164 IHO Test Data Sets for ECDIS](https://iho.int/en/s-164) — Official test datasets for ECDIS type approval; includes S-101 and S-57 samples.
- [IHO S-100 Exchange Set Samples](https://iho.int/en/s-100-samples) — Sample exchange sets for product specification development and testing.

---

## Related Standards

- [IEC 63173-2 (SECOM)](https://www.iec.ch/) — IEC standard for secure communication of S-100 data (encryption and authentication layer over S-100 exchange sets).
- [IALA G1143](https://www.iala-aism.org/product/guideline-g1143/) — IALA guideline for implementing S-100-based product specifications.
- [ISO 19100 series](https://www.iso.org/committee/54904.html) — ISO/TC211 geographic information standards that underpin S-100's data model.
- [IMO e-Navigation Strategy Implementation Plan](https://www.imo.org/en/OurWork/Safety/Pages/eNavigation.aspx) — Strategic framework that drove the development of Phase 1 S-100 products.
- [ITU-R M.1371](https://www.itu.int/rec/R-REC-M.1371/) — AIS technical standard, relevant for S-211 Port Call integration.

---

## Learning Resources

- [IHO S-100 Seminars](https://iho.int/en/s-100-seminars) — IHO-hosted seminars on S-100 implementation; recordings and presentations available.
- [IALA S-100 Training Materials](https://www.iala-aism.org/technical/data-modelling/) — Introductory and technical training for AtoN-related S-100 specifications.
- [IHO Hydrographic Commission on Antarctica (HCA) S-100 Guidance](https://iho.int/en/hca) — Practical implementation guidance from regional commissions.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to add entries and [CURATION.md](CURATION.md) for inclusion criteria and editorial decisions.
