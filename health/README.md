# Υγεία (Health)

8 datasets — 6,445 records

> Browse at [listbase.org/el/health/](https://listbase.org/el/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Φαρμακεία Ελλάδας](el-farmakeia.json) | 2,520 | 301 KB | [CSV](el-farmakeia_EL.csv) | [Excel](el-farmakeia_EL.xlsx) | [View](https://listbase.org/el/health/el-farmakeia/) |
| [Φαρμακεία — Περιφέρεια Αττικής](el-attikis-farmakeia.json) | 2,190 | 327 KB | [CSV](el-attikis-farmakeia_EL.csv) | [Excel](el-attikis-farmakeia_EL.xlsx) | [View](https://listbase.org/el/health/el-attikis-farmakeia/) |
| [Ιατρεία Ελλάδας](el-iatreia.json) | 645 | 80 KB | [CSV](el-iatreia_EL.csv) | [Excel](el-iatreia_EL.xlsx) | [View](https://listbase.org/el/health/el-iatreia/) |
| [Θάνατοι από COVID-19 ανά Δήμο, 2020–2021](el-thanatoi-covid-dimous-2020-2021.json) | 332 | 49 KB | [CSV](el-thanatoi-covid-dimous-2020-2021_EL.csv) | [Excel](el-thanatoi-covid-dimous-2020-2021_EL.xlsx) | [View](https://listbase.org/el/health/el-thanatoi-covid-dimous-2020-2021/) |
| [Κλινικές Ελλάδας](el-klinikes.json) | 279 | 35 KB | [CSV](el-klinikes_EL.csv) | [Excel](el-klinikes_EL.xlsx) | [View](https://listbase.org/el/health/el-klinikes/) |
| [Οδοντιατρεία Ελλάδας](el-odontiatreia.json) | 207 | 26 KB | [CSV](el-odontiatreia_EL.csv) | [Excel](el-odontiatreia_EL.xlsx) | [View](https://listbase.org/el/health/el-odontiatreia/) |
| [Κτηνιατρεία Ελλάδας](el-ktiniatreia.json) | 179 | 22 KB | [CSV](el-ktiniatreia_EL.csv) | [Excel](el-ktiniatreia_EL.xlsx) | [View](https://listbase.org/el/health/el-ktiniatreia/) |
| [Νοσοκομεία και κλινικές — Περιφέρεια Αττικής](el-attikis-nosokomeia.json) | 93 | 20 KB | [CSV](el-attikis-nosokomeia_EL.csv) | [Excel](el-attikis-nosokomeia_EL.xlsx) | [View](https://listbase.org/el/health/el-attikis-nosokomeia/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/health/el-farmakeia.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/health/)
