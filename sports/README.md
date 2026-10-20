# Αθλητισμός (Sports)

3 datasets — 1,891 records

> Browse at [listbase.org/el/sports/](https://listbase.org/el/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Γήπεδα στην Ελλάδα](el-gipeda.json) | 1,280 | 158 KB | [CSV](el-gipeda_EL.csv) | [Excel](el-gipeda_EL.xlsx) | [View](https://listbase.org/el/sports/el-gipeda/) |
| [Αθλητικά κέντρα Ελλάδας](el-athlitika-kentra.json) | 603 | 79 KB | [CSV](el-athlitika-kentra_EL.csv) | [Excel](el-athlitika-kentra_EL.xlsx) | [View](https://listbase.org/el/sports/el-athlitika-kentra/) |
| [Χιονοδρομικά κέντρα της Ελλάδας](el-chionodromika-kentra.json) | 8 | 5 KB | [CSV](el-chionodromika-kentra_EL.csv) | [Excel](el-chionodromika-kentra_EL.xlsx) | [View](https://listbase.org/el/sports/el-chionodromika-kentra/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/sports/el-gipeda.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/sports/)
