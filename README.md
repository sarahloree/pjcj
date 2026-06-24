# pjcj

PJ&CJ — Capital Allocation Dashboard

Internal capital-allocation cockpit for PJ&CJ LLC. Answers the core question:
"Can I safely start another deal right now without a cash crunch later?"

Status: prototype


Live figures (solid teal dot): income, properties, and known mortgage/lease costs — from the PJ&CJ master data.
Placeholders (amber dashed): operating cash, credit lines (LOC/HELOC), and operating expenses — awaiting financials from Sunny. These are editable inputs; nothing typed in is stored or transmitted.
Pending (dashed): Pheasant — becomes the first pipeline entry once the offer is accepted.


This is a static preview with figures baked in. The production version reads live from Supabase (built separately via Claude Code).

Confidential

Contains PJ&CJ financial information. Protect the deployed site (e.g., Netlify password protection); do not share the URL openly.

Deploy

Single-file app — index.html at the site root is all Netlify needs.
