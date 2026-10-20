# Περιβάλλον (Environment)

4 datasets — 3,306 records

> Browse at [listbase.org/el/environment/](https://listbase.org/el/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Σταθμοί ηλεκτροπαραγωγής στην Ελλάδα](el-stathmoi-ilektroparagogis.json) | 2,073 | 1065 KB | [CSV](el-stathmoi-ilektroparagogis_EL.csv) | [Excel](el-stathmoi-ilektroparagogis_EL.xlsx) | [View](https://listbase.org/el/environment/el-stathmoi-ilektroparagogis/) |
| [Φυσικά καταφύγια και προστατευόμενες περιοχές στην Ελλάδα (OSM)](el-fysika-katafygia.json) | 684 | 105 KB | [CSV](el-fysika-katafygia_EL.csv) | [Excel](el-fysika-katafygia_EL.xlsx) | [View](https://listbase.org/el/environment/el-fysika-katafygia/) |
| [Σεισμοί 2.5+ στην Αττική 2006–2026](el-attikis-seismoi-2006-2026.json) | 463 | 105 KB | [CSV](el-attikis-seismoi-2006-2026_EL.csv) | [Excel](el-attikis-seismoi-2006-2026_EL.xlsx) | [View](https://listbase.org/el/environment/el-attikis-seismoi-2006-2026/) |
| [Δασικές πυρκαγιές στην Αττική 2015–2025](el-attikis-pyrkagies-2015-2025.json) | 86 | 28 KB | [CSV](el-attikis-pyrkagies-2015-2025_EL.csv) | [Excel](el-attikis-pyrkagies-2015-2025_EL.xlsx) | [View](https://listbase.org/el/environment/el-attikis-pyrkagies-2015-2025/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/environment/el-stathmoi-ilektroparagogis.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/environment/)
