# Nano & Microelectronics ArXiv Daily (Nanotech • Devices • Photonics • MEMS)

Daily arXiv digest for **nanotechnology, microelectronics, photonics, MEMS**, and related applied-physics materials/device research.

This repository updates automatically via **GitHub Actions** and generates:
- `digests/YYYY-MM-DD.md` (full daily archive)
- `topics/<topic>.md` (one file per topic)
- a compact **Today** section below with links to each topic page

---

## Quick start (non-experts)
1. Create a GitHub repo (e.g., `nano-microelectronics-arxiv-daily`).
2. Upload/push these files.
3. Go to **Actions** → enable workflows.
4. Run once manually: **Actions → Daily ArXiv Digest → Run workflow**.

---

## How to tune what you see
Edit `config.yml`:
- `days_back`: how many days back count as “new” (recommended: 1–2)
- `max_results_per_topic`: cap per topic
- `categories`: arXiv categories to query
- `topics`: your keyword buckets

To reduce off-topic papers, enable stricter matching:
- `match_in: title` (strict) or `title+abstract` (broader)
- `must_have_any`: a small “gate” of domain terms that must appear

---

<!-- BEGIN TODAY -->
## ✅ Today

**Last update:** 2026-02-15  
**Daily archive:** `digests/2026-02-15.md`  

_Auto-generated. Edit `config.yml` to change topics/keywords._

### Browse by topic (links)

- **[Nanomaterials & Synthesis](topics/nanomaterials-synthesis.md)**
- **[Nano/Microelectronic Devices](topics/nano-microelectronic-devices.md)**
- **[CMOS, Process & Fabrication](topics/cmos-process-fabrication.md)**
- **[Photonics, Optoelectronics & Plasmonics](topics/photonics-optoelectronics-plasmonics.md)**
- **[MEMS/NEMS & Sensors](topics/mems-nems-sensors.md)**
- **[Energy & Power Materials (Micro/Nano)](topics/energy-power-materials-micro-nano.md)**
- **[Reliability, Modeling & TCAD](topics/reliability-modeling-tcad.md)**

### Nanomaterials & Synthesis

_No matches today._


### Nano/Microelectronic Devices

_No matches today._


### CMOS, Process & Fabrication

_No matches today._


### Photonics, Optoelectronics & Plasmonics

_No matches today._


### MEMS/NEMS & Sensors

_No matches today._


### Energy & Power Materials (Micro/Nano)

_No matches today._


### Reliability, Modeling & TCAD

_No matches today._
<!-- END TODAY -->

---

## Local run (optional)
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
# or
venv\Scripts\activate     # Windows

pip install -r requirements.txt
python scripts/fetch_arxiv_daily.py
```

## License
Apache-2.0
