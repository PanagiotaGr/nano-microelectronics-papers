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
