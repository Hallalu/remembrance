# Remembrance

A worldwide, continuously-updatable memorial record of people killed for their **faith**, **race**, or **ethnicity** — grouped, charted, and honest about contested framing and counter-evidence.

- **Live:** https://remembrance.coconvo.workers.dev
- **Data:** `public/data.json` (the page fetches it at runtime, so the record updates without a rebuild)
- **Deploy:** Cloudflare Worker (static assets) — `npx wrangler deploy`

Three lenses (Faith · Race · Ethnicity), each with By-group bars, Charts (donut + per-group bars + era), a dated event Timeline with named perpetrators, By-country deaths + persecution-severity, and an About/methodology section citing the debate.

Sources: Open Doors WWL, Pew Research, USCIRF, UN/UNITAD, MSF, PLOS, ICTY, HRW, ACLED, EJI, Yad Vashem/USHMM, and genocide scholarship. Every figure is an estimate with a range and a source; totals are not additive.
