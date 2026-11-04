# Margot, accounts-payable assistant

Margot does one job: **Weekly invoice totals**.

Every Monday, Margot adds up what the company owes each supplier and flags any supplier more than 10% above last month.

## Set it up

Follow [SETUP.md](SETUP.md) (en français : [SETUP.fr.md](SETUP.fr.md)).

## What is in this folder

- `AGENTS.md`: who the coworker is, the job, and its red lines.
- `CLAUDE.md`: tells Claude to read `AGENTS.md` first.
- `.claude/skills/weekly-invoice-totals/SKILL.md`: the job, step by step.
- `jobs/weekly-invoice-totals.md`: when it runs, and the prompt to run it.
- `SETUP.md` and `SETUP.fr.md`: set it up in your own Claude, in about 10 minutes.

## What a starter does not do

- It runs one job on one computer, from files you give it.
- It is not connected to your email, Microsoft 365 or Google files.
- Nobody watches its runs or tells you when one is missed.

Ouvrix sets coworkers up properly for small businesses: connected to your files and email, watched on the Ouvrix Board, with your team trained level by level. Write to us at [ouvrix.com/contact](https://ouvrix.com/contact/).

_Provided as is, free. You run it in your own Claude; Ouvrix has no access to it._
