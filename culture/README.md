# Πολιτισμός και Θρησκεία (Culture & Religion)

18 datasets — 7,078 records

> Browse at [listbase.org/el/culture/](https://listbase.org/el/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Αρχαιολογικοί χώροι της Ελλάδας](el-archaiologikoi-xoroi.json) | 3,283 | 2808 KB | [CSV](el-archaiologikoi-xoroi_EL.csv) | [Excel](el-archaiologikoi-xoroi_EL.xlsx) | [View](https://listbase.org/el/culture/el-archaiologikoi-xoroi/) |
| [Μουσεία της Ελλάδας](el-mouseia.json) | 880 | 884 KB | [CSV](el-mouseia_EL.csv) | [Excel](el-mouseia_EL.xlsx) | [View](https://listbase.org/el/culture/el-mouseia/) |
| [Μοναστήρια της Ελλάδας (Monasteries of Greece)](el-monastiria.json) | 852 | 1114 KB | [CSV](el-monastiria_EL.csv) | [Excel](el-monastiria_EL.xlsx) | [View](https://listbase.org/el/culture/el-monastiria/) |
| [Θέατρα Ελλάδας](el-theatra.json) | 497 | 62 KB | [CSV](el-theatra_EL.csv) | [Excel](el-theatra_EL.xlsx) | [View](https://listbase.org/el/culture/el-theatra/) |
| [Κάστρα της Ελλάδας](el-kastra.json) | 472 | 490 KB | [CSV](el-kastra_EL.csv) | [Excel](el-kastra_EL.xlsx) | [View](https://listbase.org/el/culture/el-kastra/) |
| [Εκκλησίες στην Ελλάδα — Christian churches in Greece](el-ekklisies.json) | 396 | 2507 KB | [CSV](el-ekklisies_EL.csv) | [Excel](el-ekklisies_EL.xlsx) | [View](https://listbase.org/el/culture/el-ekklisies/) |
| [Θέατρα — Περιφέρεια Αττικής](el-attikis-theatra.json) | 143 | 25 KB | [CSV](el-attikis-theatra_EL.csv) | [Excel](el-attikis-theatra_EL.xlsx) | [View](https://listbase.org/el/culture/el-attikis-theatra/) |
| [Φάροι της Ελλάδας](el-fanos.json) | 113 | 134 KB | [CSV](el-fanos_EL.csv) | [Excel](el-fanos_EL.xlsx) | [View](https://listbase.org/el/culture/el-fanos/) |
| [Τζαμιά της Ελλάδας](el-tzamia.json) | 92 | 35 KB | [CSV](el-tzamia_EL.csv) | [Excel](el-tzamia_EL.xlsx) | [View](https://listbase.org/el/culture/el-tzamia/) |
| [Κινηματογράφοι — Περιφέρεια Αττικής](el-attikis-kinimatografoi.json) | 68 | 12 KB | [CSV](el-attikis-kinimatografoi_EL.csv) | [Excel](el-attikis-kinimatografoi_EL.xlsx) | [View](https://listbase.org/el/culture/el-attikis-kinimatografoi/) |
| [Αγάλματα της Ελλάδας](el-agalmata.json) | 65 | 26 KB | [CSV](el-agalmata_EL.csv) | [Excel](el-agalmata_EL.xlsx) | [View](https://listbase.org/el/culture/el-agalmata/) |
| [Βυζαντινές εκκλησίες στην Ελλάδα — Byzantine churches in Greece](el-vyzantines-ekklisies.json) | 50 | 360 KB | [CSV](el-vyzantines-ekklisies_EL.csv) | [Excel](el-vyzantines-ekklisies_EL.xlsx) | [View](https://listbase.org/el/culture/el-vyzantines-ekklisies/) |
| [Ανεμόμυλοι της Ελλάδας](el-anemomyloi.json) | 40 | 18 KB | [CSV](el-anemomyloi_EL.csv) | [Excel](el-anemomyloi_EL.xlsx) | [View](https://listbase.org/el/culture/el-anemomyloi/) |
| [Γέφυρες της Ελλάδας (Bridges of Greece)](el-gefyres.json) | 38 | 58 KB | [CSV](el-gefyres_EL.csv) | [Excel](el-gefyres_EL.xlsx) | [View](https://listbase.org/el/culture/el-gefyres/) |
| [Πύργοι της Ελλάδας — Towers in Greece](el-pyrgoi.json) | 32 | 212 KB | [CSV](el-pyrgoi_EL.csv) | [Excel](el-pyrgoi_EL.xlsx) | [View](https://listbase.org/el/culture/el-pyrgoi/) |
| [Ανάκτορα και Βασιλικές Κατοικίες της Ελλάδας](el-anaktora.json) | 23 | 20 KB | [CSV](el-anaktora_EL.csv) | [Excel](el-anaktora_EL.xlsx) | [View](https://listbase.org/el/culture/el-anaktora/) |
| [Μνημεία Παγκόσμιας Κληρονομιάς της UNESCO στην Ελλάδα](el-mnimeia-pagkosmias-klironomias-unesco.json) | 18 | 19 KB | [CSV](el-mnimeia-pagkosmias-klironomias-unesco_EL.csv) | [Excel](el-mnimeia-pagkosmias-klironomias-unesco_EL.xlsx) | [View](https://listbase.org/el/culture/el-mnimeia-pagkosmias-klironomias-unesco/) |
| [Συναγωγές της Ελλάδας](el-synagoges.json) | 16 | 8 KB | [CSV](el-synagoges_EL.csv) | [Excel](el-synagoges_EL.xlsx) | [View](https://listbase.org/el/culture/el-synagoges/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.el.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.el.listbase.org/culture/el-archaiologikoi-xoroi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/el/culture/)
