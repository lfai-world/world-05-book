# QA — 2026-10-30 06:46 KST

**88 / 100** — measured by the runner itself; anything it cannot measure scores 0.

| Area | Check | Points | Score | Evidence |
|---|---|---|---|---|
| Line | Every shipped lot passed all 12 stations | 12 | 0 | 7/8 complete · 0 waiting at the gate |
| Line | Wiring — every declared line connected | 10 | 10 | 14/14 |
| Line | Yield ≥ 80 % | 8 | 8 | yield 100.0% |
| Line | Signals and runner — last runs succeeded | 10 | 10 | all green |
| Public | Public = the profile and each factory's web book (WC-05 showroom) only — every HQ stays private | 10 | 10 | public ['lfai-world', 't1-05-book', 'world-05-book'] · allowed ['lfai-world', 't1-05-book', 'world-05-book'] |
| Public | Public repositories hold zero keys | 8 | 8 | {'lfai-world': 0, 't1-05-book': 0, 'world-05-book': 0} |
| Public | Dashboard is up and shows the live feed | 6 | 6 | HTTP 200 |
| Public | Every chapter opens in three layers | 6 | 0 | 7/8 |
| Public | Every chapter ships all outputs (cards · audio · video · lesson) | 10 | 10 | 8/8 |
| Public | Search index and RSS feed published | 6 | 6 | pagefind · feed.xml |
| Public | Open-source gate scanner ran; nothing held is public | 6 | 6 | held [] |
| Public | Showroom (WC-05 web book) lists every chapter | 8 | 8 | book index 8/8 chapters · public HTTP 200 |
| Public | Personal data in published chapters = 0 | 10 | 10 | found 0 |
| Profile | Profile live numbers match the factory | 10 | 10 | profile 8 · factory 8 |
| Profile | Profile images all present | 5 | 5 | 9 images |
| Profile | Playbook linked from the profile | 5 | 5 | link |
| Fab | Every chapter meets the output spec (contract/output.schema.json) — auto inspection | 12 | 12 | 8/8 · defects {} |
| Fab | Contract pack installed (charter · FMEA · spec · defect codes · guardrails · permissions · agent card) | 6 | 6 | contract/ |
| Fab | Cost ledger written and month projection under 70 % of the free minutes | 6 | 6 | 197 min · projected 10.2% |
