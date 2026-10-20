# Κοινωνία (Society)

2 datasets — 414 records

> Browse at [listbase.org/el/society/](https://listbase.org/el/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Αστυνομικά Τμήματα Ελλάδας](el-astynomika-tmimata.json) | 315 | 42 KB | [CSV](el-astynomika-tmimata_EL.csv) | [Excel](el-astynomika-tmimata_EL.xlsx) | [View](https://listbase.org/el/society/el-astynomika-tmimata/) |
| [Αστυνομικά τμήματα — Περιφέρεια Αττικής](el-attikis-astynomika-tmimata.json) | 99 | 20 KB | [CSV](el-attikis-astynomika-tmimata_EL.csv) | [Excel](el-attikis-astynomika-tmimata_EL.xlsx) | [View](https://listbase.org/el/society/el-attikis-astynomika-tmimata/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/society/el-astynomika-tmimata.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/society/)
