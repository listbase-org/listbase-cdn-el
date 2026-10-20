# ListBase CDN — Ελληνικά (el)

Open dataset collection for **Ελληνικά** (Greek).
419 datasets across 17 categories with 192,317 total records.

> Browse and download at [https://listbase.org/el/](https://listbase.org/el/)

## Categories

| Category | Datasets |
|----------|----------|
| [Πολιτισμός και Θρησκεία (Culture & Religion)](culture/) | 18 |
| [Εκπαίδευση (Education)](education/) | 5 |
| [Περιβάλλον (Environment)](environment/) | 4 |
| [Χρηματοοικονομικά (Finance & Trade)](finance/) | 55 |
| [Τρόφιμα (Food & Nutrition)](food/) | 4 |
| [Γεωγραφία (Geography)](geography/) | 21 |
| [Υγεία (Health)](health/) | 8 |
| [Ιστορία (History)](history/) | 1 |
| [Γλώσσα (Language)](language/) | 1 |
| [Πολιτική (Politics)](politics/) | 8 |
| [Αναφορά (Reference)](reference/) | 230 |
| [Κοινωνία (Society)](society/) | 2 |
| [Αθλητισμός (Sports)](sports/) | 3 |
| [Τεχνολογία (Technology)](tech/) | 1 |
| [Χρόνος και Ημερολόγιο (Time & Calendar)](time/) | 18 |
| [Τουρισμός (Tourism)](tourism/) | 7 |
| [Μεταφορές (Transport)](transport/) | 33 |

## Usage

### Browse on the web
Visit [listbase.org/el/](https://listbase.org/el/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.el.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.el.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.el.listbase.org/geography/th-central-provinces_EL.xlsx
curl -O https://cdn.el.listbase.org/geography/th-central-provinces_EL.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.el.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.el.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_EL.csv   # CSV download
│   └── {dataset}_EL.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
