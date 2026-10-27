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

Platforms for companies that outgrew their spreadsheets and then found that off-the-shelf
software does not fit the way they actually work. Not a dashboard bolted onto a database — the
system the whole company spends its day inside.

| | |
| :-- | :-- |
| **Sales** | lead qualification, deals, quotes with digital signing |
| **Operations** | projects, planning, field execution, logistics and stock |
| **Finance** | invoicing, payment reconciliation, VAT, collections |
| **People** | role-based access, HR, training |
| **Outward-facing** | customer portals, partner flows, marketing attribution |

Every role gets an interface built for the work it does, instead of one screen with the rest
hidden behind permissions. I own these end to end: the domain modelling, the architecture, the
database, the deploys — and the phone call when something breaks on a Saturday.

<br>

## Things you can install

<table>
<tr>
<td width="50%" valign="top">

### [catchbox](https://github.com/brentc22/catchbox)

Disposable inboxes for developers. One mailbox per flow, with the one-time code and the action
link pulled out for you — plus a deliverability read of the headers, which is usually the answer
to *why did this land in spam*.

```sh
brew tap brentc22/tap
brew trust brentc22/tap
brew install brentc22/tap/catchbox
```

</td>
<td width="50%" valign="top">

### [Stash](https://github.com/brentc22/stash)

A free menu bar hider for macOS 27. The macOS 27 rewrite drew the menu bar as a single window
and broke every tool in that category at once. The repository documents what changed, measured
on a real machine rather than guessed at.

```sh
brew tap brentc22/stash
brew trust brentc22/stash
brew install --cask brentc22/stash/stash
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Glint](https://github.com/brentc22/glint)

A screenshot tool that blurs your secrets before you share them. On-device text recognition
finds emails, IBANs, card numbers and API keys, checks them (an IBAN has to pass its checksum),
and pixelates them in one click.

```sh
brew tap brentc22/tap
brew trust brentc22/tap
brew install --cask brentc22/tap/glint
```

</td>
<td width="50%" valign="top">

### [Portside](https://github.com/brentc22/portside)

Every dev server on your Mac in the menu bar, grouped by repo and git worktree. See which
branch started what is on `:5174`, and stop it in one click.

```sh
brew tap brentc22/tap
brew trust brentc22/tap
brew install --cask brentc22/tap/portside
```

</td>
</tr>
</table>

<br>

## How I work

**Correctness before cleverness wherever money is involved.** Pricing, VAT regimes and invoice
totals are guarded by database-level invariants that run on a schedule and alert only when the
state *changes* — an alarm that repeats every fifteen minutes gets dismissed, and is worthless
from then on.

**Access control is not something you bolt on afterwards.** A public customer portal on the same
database as internal finance data makes every row-level policy load-bearing. I assume a policy is
broken until I have watched it refuse the request.

**Every incident becomes a written rule,** and the ones that matter become automated checks —
a warning in prose only helps if you read it in the minute before you would have made the mistake.

**Measured, not assumed.** Before I claim something works, I run the check and read the output.
That habit is the single biggest difference between a system you trust and one you hope about.

<br>

<div align="center">

Most of my work lives in private client repositories, so the graph below tells the story rather
better than the repository list does.

<br>

<sub>Belgium · open to interesting problems</sub>

</div>
