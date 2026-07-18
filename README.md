### Melik Şah Tokur

**Veterinarian and systems designer.**
*Full-stack: PostgreSQL · JavaScript · Python · Supabase · Playwright · n8n*

I design the data model for domains that have real rules, and then I build it — schemas
that enforce their own constraints, workflows that run unattended, and data pipelines that
survive the source changing shape.

Based in Antalya, Türkiye (GMT+3). Working with clients across Europe and the US.

---

#### What I'm best at

**Modelling a domain correctly the first time.** Most systems that model a specialist field
are built by developers interviewing experts, and the gap shows up in the schema — the field
that should have been a foreign key, the state machine missing the transition that happens
twice a year. I come at it from the other side: I've spent my career inside one of those
domains, and I write the database myself.

**Business logic that lives in the database.** Not a frontend developer who picked up
Postgres. I write the RPC functions, the triggers, the state machines, and the migrations
— so the rules hold for every caller, not just the client I happened to write.

**Automation that doesn't need babysitting.** n8n, Playwright, and LLM APIs, with real
Python and JavaScript inside the nodes. Most automation freelancers come from the no-code
world and stall at the first edge case. I don't have that ceiling.

**Data extraction that survives contact with reality.** Playwright against JavaScript-heavy
and anti-bot protected sites, cleaned with an LLM pass, structured into Postgres, exposed
as an API. Not a scraper — a pipeline.

---

#### Live work

**[EgeSüt ERP](https://github.com/Meliksahtokur/egesut-erp1)** — a farm management system in
daily production use by a 157-head dairy operation. Not a portfolio piece: 48 tables, 180
server-side functions, 221 versioned migrations, an immutable stock ledger, Playwright E2E
across 3 shards, and an in-app AI assistant that runs read-only SQL with human-in-the-loop
confirmation before any write. Real people depend on it, every day.

[Live app](https://meliksahtokur.github.io/egesut-erp1/) ·
[Design notes](https://github.com/Meliksahtokur/egesut-erp1/blob/main/DESIGN.md) — why each
architectural decision was made, and what it cost

---

#### Stack

`PostgreSQL` `Supabase` `Python` `JavaScript` `Go` `Playwright` `n8n` `MCP` `LLM APIs`
`GitHub Actions`

---

#### Open to contract work

Business process automation · internal tools · PostgreSQL-backed applications · MCP servers

📫 [Reach me here](https://github.com/Meliksahtokur) · Antalya, GMT+3 — overlapping European
hours in full
