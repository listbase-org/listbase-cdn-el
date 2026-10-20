# Τεχνολογία (Technology)

1 datasets — 101 records

> Browse at [listbase.org/el/tech/](https://listbase.org/el/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Βιβλιοθήκες Ελλάδας](el-vivliothikes.json) | 101 | 137 KB | [CSV](el-vivliothikes_EL.csv) | [Excel](el-vivliothikes_EL.xlsx) | [View](https://listbase.org/el/tech/el-vivliothikes/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/tech/el-vivliothikes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/tech/)
