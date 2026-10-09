### Andrija Gojaković

Software developer from Prijepolje, Serbia. I build business software for small companies
and look after it once it's live: deployment, backups, updates and support by phone.

I work with AI every day. I write skills and instruction files for Claude agents (the rules,
workflows and checks that keep an agent consistent), review what they produce and correct it
before anything ships. The result is mine: tests, deployment, and every line that goes live.

**What I've built**

- **Case management for law offices**: running with two offices since August 2026, each on
  its own isolated instance. Cases, clients, hearings, document generation, billing and
  receivables, conflict-of-interest checks. ~350 automated tests, CI, versioned releases,
  encrypted off-site backups with a rehearsed restore.
- **Membership and payments for a gym**: members, plans, barcode check-in at the door,
  payments and statistics. Still in daily use.
- **Practice management for surveying companies**: cadastral parcels (5,800+ municipalities),
  deadlines, field work with a mobile flow, quotes, invoices and per-job profitability.
- **Management system for construction contractors**: contracts, sites, crews, progress
  billing, subcontractors. In development.

The code of these systems is private because it runs for real clients.

**In progress: ClipsDex**

An open-source app that uses AI to organise the videos people save on Instagram. Speech
recognition, image models and language models sort them by topic, summarise them and
recognise songs and films. I set up and test the models on a fixed set of sample videos;
the app learns from the user's corrections and runs privately on their own computer.

<!--
**Open source**

- [safe-spreadsheet](https://github.com/andrijagojakovic/safe-spreadsheet) — read and write .xlsx/.csv without PhpSpreadsheet, treating uploaded files as hostile input
- [laravel-backup-verify](https://github.com/andrijagojakovic/laravel-backup-verify) — a backup you have never restored is not a backup
- [laravel-release-guard](https://github.com/andrijagojakovic/laravel-release-guard) — version, changelog and git tag always agree, or there is no release
-->

**How I work**

Tests before "done". One client per isolated instance. A backup counts only after a
successful restore. A runbook someone else could follow.

**Stack:** PHP · Laravel · Livewire · JavaScript · MySQL · PostgreSQL · Docker · nginx · Pest · GitHub Actions · Claude Code

Open to remote backend work, contract tasks and AI-related roles.
[LinkedIn](https://www.linkedin.com/in/andrija-gojakovi%C4%87-70a0a02a8/)
