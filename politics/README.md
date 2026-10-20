# Πολιτική (Politics)

8 datasets — 3,865 records

> Browse at [listbase.org/el/politics/](https://listbase.org/el/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Δημόσιες υπηρεσίες στην Ελλάδα](el-dimosies-ypiresies.json) | 1,616 | 197 KB | [CSV](el-dimosies-ypiresies_EL.csv) | [Excel](el-dimosies-ypiresies_EL.xlsx) | [View](https://listbase.org/el/politics/el-dimosies-ypiresies/) |
| [Αυτοδιοικητικές εκλογές 2023 και 2019 ανά Δήμο](el-dimotikes-ekloges-2023-2019.json) | 977 | 609 KB | [CSV](el-dimotikes-ekloges-2023-2019_EL.csv) | [Excel](el-dimotikes-ekloges-2023-2019_EL.xlsx) | [View](https://listbase.org/el/politics/el-dimotikes-ekloges-2023-2019/) |
| [Ευρωεκλογές 2024 και 2019 ανά Δήμο](el-evropaikes-ekloges-2024-2019.json) | 664 | 512 KB | [CSV](el-evropaikes-ekloges-2024-2019_EL.csv) | [Excel](el-evropaikes-ekloges-2024-2019_EL.xlsx) | [View](https://listbase.org/el/politics/el-evropaikes-ekloges-2024-2019/) |
| [Βουλευτικές εκλογές Ιουνίου 2023 ανά Δήμο](el-voulevtikes-ekloges-iouniou-2023.json) | 332 | 258 KB | [CSV](el-voulevtikes-ekloges-iouniou-2023_EL.csv) | [Excel](el-voulevtikes-ekloges-iouniou-2023_EL.xlsx) | [View](https://listbase.org/el/politics/el-voulevtikes-ekloges-iouniou-2023/) |
| [Πρωθυπουργοί της Ελλάδας](el-prothipourgoi.json) | 105 | 77 KB | [CSV](el-prothipourgoi_EL.csv) | [Excel](el-prothipourgoi_EL.xlsx) | [View](https://listbase.org/el/politics/el-prothipourgoi/) |
| [Πρόεδροι της Βουλής των Ελλήνων](el-vouli-proedroi.json) | 98 | 63 KB | [CSV](el-vouli-proedroi_EL.csv) | [Excel](el-vouli-proedroi_EL.xlsx) | [View](https://listbase.org/el/politics/el-vouli-proedroi/) |
| [Ιστορικά στοιχεία βουλευτικών εκλογών της Ελλάδας](el-voulevtikes-ekloges-istorika.json) | 55 | 56 KB | [CSV](el-voulevtikes-ekloges-istorika_EL.csv) | [Excel](el-voulevtikes-ekloges-istorika_EL.xlsx) | [View](https://listbase.org/el/politics/el-voulevtikes-ekloges-istorika/) |
| [Πρόεδροι της Ελληνικής Δημοκρατίας](el-proedroi-tis-dimokratias.json) | 18 | 11 KB | [CSV](el-proedroi-tis-dimokratias_EL.csv) | [Excel](el-proedroi-tis-dimokratias_EL.xlsx) | [View](https://listbase.org/el/politics/el-proedroi-tis-dimokratias/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/politics/el-dimosies-ypiresies.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/politics/)
