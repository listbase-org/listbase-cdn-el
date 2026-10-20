# Τρόφιμα (Food & Nutrition)

4 datasets — 5,919 records

> Browse at [listbase.org/el/food/](https://listbase.org/el/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Ταχυφαγεία (Fast Food) στην Ελλάδα](el-fast-food.json) | 3,251 | 331 KB | [CSV](el-fast-food_EL.csv) | [Excel](el-fast-food_EL.xlsx) | [View](https://listbase.org/el/food/el-fast-food/) |
| [Αρτοποιεία Ελλάδας](el-artopoieia.json) | 2,302 | 245 KB | [CSV](el-artopoieia_EL.csv) | [Excel](el-artopoieia_EL.xlsx) | [View](https://listbase.org/el/food/el-artopoieia/) |
| [Ζαχαροπλαστεία στην Ελλάδα (OSM)](el-zacharoplasteia.json) | 332 | 37 KB | [CSV](el-zacharoplasteia_EL.csv) | [Excel](el-zacharoplasteia_EL.xlsx) | [View](https://listbase.org/el/food/el-zacharoplasteia/) |
| [Εστιατόρια Michelin στην Ελλάδα](el-estiatoria-michelin.json) | 34 | 46 KB | [CSV](el-estiatoria-michelin_EL.csv) | [Excel](el-estiatoria-michelin_EL.xlsx) | [View](https://listbase.org/el/food/el-estiatoria-michelin/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/food/el-fast-food.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/food/)
