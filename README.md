## Brent Ceulemans

Product owner and developer at [Vernast](https://vernast.be), a Belgian damp-proofing and
renovation company. I build the platform the company actually runs on — which means I own the
problem end to end: the domain, the architecture, the database, the deploys, and the phone call
when something breaks on a Saturday.

### What I work on

**Vernast v2.0** — a role-based platform covering the full chain from inbound lead to settled
invoice: lead qualification, sales, quotes with digital signing, projects, planning, on-site
execution, logistics and warehousing, invoicing and collection, a customer portal, a partner
flow, HR, training, marketing attribution and equipment rental. Eleven roles, each with its own
interface.

Some of what that involves day to day:

- **Correctness over cleverness in anything touching money.** Line-item pricing, VAT regimes and
  invoice totals are covered by database-level invariant checks that run on a schedule and alert
  only on state changes — an alarm that repeats every quarter of an hour gets dismissed and is
  then worthless.
- **Row-level security as a first-class concern.** A public customer portal on the same database
  as internal finance data means every policy and every grant is load-bearing.
- **Documented scar tissue.** Every incident that cost real time becomes a written rule in the
  repository, with the story behind it. A warning in prose only works if you read it right
  before you would have made the mistake.

**Stack:** TypeScript · React · Vite · Supabase (PostgreSQL) · Tailwind · Cloudflare Workers

### Public work

- **[stash](https://github.com/brentc22/stash)** — research and design for a macOS 27 menu bar
  hider. macOS 27 rewrote the menu bar as a single window, which broke Ice, Bartender and every
  tool in that category. The design documents what still works, measured rather than assumed.

Most of my work lives in private repositories, so the contribution graph tells the story better
than the repository list does.
