<div align="center">

# Brent Ceulemans

### I build the systems companies actually run on

Custom CRM and operations platforms — from the first inbound lead to the settled invoice.

<br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

</div>

<br>

## What I build

Custom CRM and operations platforms for companies that outgrew their spreadsheets and then
discovered that off-the-shelf software does not fit the way they actually work. Not a dashboard
bolted onto a database — the system the entire company spends its day inside.

A platform like that tends to cover the whole chain:

| | |
| :-- | :-- |
| **Sales** | lead qualification, deals, quotes with digital signing |
| **Operations** | projects, planning, field execution, logistics and stock |
| **Finance** | invoicing, payment reconciliation, VAT, collections |
| **People** | role-based access, HR, training |
| **Outward-facing** | customer portals, partner flows, marketing attribution |

Every role gets an interface built for the work it does, rather than one screen with everything
hidden behind permissions. I own these end to end: the domain modelling, the architecture, the
database, the deploys — and the phone call when something breaks on a Saturday.

<br>

## How I work

**Correctness before cleverness wherever money is involved.**
Line-item pricing, VAT regimes and invoice totals are guarded by database-level invariant checks
that run on a schedule and alert only when the state *changes*. An alarm that repeats every
fifteen minutes gets dismissed, and is worthless from then on.

**Access control is not something you bolt on afterwards.**
A public customer portal sitting on the same database as internal finance data means every
row-level policy and every grant is load-bearing. I assume a policy is broken until I have
watched it refuse the request.

**Every incident becomes a written rule.**
Anything that cost real time gets documented in the repository — the rule, and the story behind
it. A warning in prose only works if you happen to read it right before you would have made the
mistake, so the ones that matter become automated checks instead.

**Measured, not assumed.**
Before I claim something works, I run the check and read the output. That habit is the single
biggest difference between a system you trust and one you hope about.

<br>

## Open source

**[stash](https://github.com/brentc22/stash)** — a free, open source menu bar hider for macOS 27.
The macOS 27 rewrite drew the menu bar as a single window, which broke every tool in that
category at once; some have since rebuilt on the new architecture, and Ice never did. The
repository documents what changed and what is left to build on — measured on a real machine
rather than guessed at.

<br>

## Elsewhere

Most of my work lives in private client repositories, so the contribution graph tells the story
rather better than the repository list does.

<div align="center">
<br>
<sub>Belgium · open to interesting problems</sub>
</div>
