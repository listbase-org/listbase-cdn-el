# Εκπαίδευση (Education)

5 datasets — 8,702 records

> Browse at [listbase.org/el/education/](https://listbase.org/el/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Σχολεία Ελλάδας](el-scholeia.json) | 3,885 | 517 KB | [CSV](el-scholeia_EL.csv) | [Excel](el-scholeia_EL.xlsx) | [View](https://listbase.org/el/education/el-scholeia/) |
| [Σχολικές μονάδες — Περιφέρεια Αττικής](el-attikis-scholeia.json) | 3,753 | 1445 KB | [CSV](el-attikis-scholeia_EL.csv) | [Excel](el-attikis-scholeia_EL.xlsx) | [View](https://listbase.org/el/education/el-attikis-scholeia/) |
| [Νηπιαγωγεία Ελλάδας](el-nipiagogeia.json) | 977 | 129 KB | [CSV](el-nipiagogeia_EL.csv) | [Excel](el-nipiagogeia_EL.xlsx) | [View](https://listbase.org/el/education/el-nipiagogeia/) |
| [Πανεπιστημιακές εγκαταστάσεις — Περιφέρεια Αττικής](el-attikis-panepistimia.json) | 54 | 14 KB | [CSV](el-attikis-panepistimia_EL.csv) | [Excel](el-attikis-panepistimia_EL.xlsx) | [View](https://listbase.org/el/education/el-attikis-panepistimia/) |
| [Greece — Universities (πανεπιστήμια)](el-panepistimia.json) | 33 | 11 KB | [CSV](el-panepistimia_EL.csv) | [Excel](el-panepistimia_EL.xlsx) | [View](https://listbase.org/el/education/el-panepistimia/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/education/el-scholeia.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/education/)
