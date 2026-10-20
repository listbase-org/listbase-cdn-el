# Τουρισμός (Tourism)

7 datasets — 8,664 records

> Browse at [listbase.org/el/tourism/](https://listbase.org/el/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Παραλίες στην Ελλάδα (OSM)](el-paralies-osm.json) | 2,830 | 303 KB | [CSV](el-paralies-osm_EL.csv) | [Excel](el-paralies-osm_EL.xlsx) | [View](https://listbase.org/el/tourism/el-paralies-osm/) |
| [Ενοικιαζόμενα διαμερίσματα στην Ελλάδα](el-diamerismata-enoikiasi.json) | 1,993 | 207 KB | [CSV](el-diamerismata-enoikiasi_EL.csv) | [Excel](el-diamerismata-enoikiasi_EL.xlsx) | [View](https://listbase.org/el/tourism/el-diamerismata-enoikiasi/) |
| [Ξενώνες στην Ελλάδα](el-xenones.json) | 1,329 | 138 KB | [CSV](el-xenones_EL.csv) | [Excel](el-xenones_EL.xlsx) | [View](https://listbase.org/el/tourism/el-xenones/) |
| [Αξιοθέατα Ελλάδας](el-axiotheata.json) | 981 | 117 KB | [CSV](el-axiotheata_EL.csv) | [Excel](el-axiotheata_EL.xlsx) | [View](https://listbase.org/el/tourism/el-axiotheata/) |
| [Σημεία τουριστικής πληροφόρησης στην Ελλάδα](el-touristikes-plirofories.json) | 801 | 96 KB | [CSV](el-touristikes-plirofories_EL.csv) | [Excel](el-touristikes-plirofories_EL.xlsx) | [View](https://listbase.org/el/tourism/el-touristikes-plirofories/) |
| [Πανοραμικές θέσεις θέας στην Ελλάδα](el-panoramikes-theseis.json) | 385 | 43 KB | [CSV](el-panoramikes-theseis_EL.csv) | [Excel](el-panoramikes-theseis_EL.xlsx) | [View](https://listbase.org/el/tourism/el-panoramikes-theseis/) |
| [Κάμπινγκ Ελλάδας](el-camping.json) | 345 | 38 KB | [CSV](el-camping_EL.csv) | [Excel](el-camping_EL.xlsx) | [View](https://listbase.org/el/tourism/el-camping/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/tourism/el-paralies-osm.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/tourism/)
