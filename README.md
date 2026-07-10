# cloud-itonami-lei-353800tj98pcazrove69

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Mitsubishi Heavy Industries, Ltd.**

This repository archives the publicly published privacy policy of
**Mitsubishi Heavy Industries, Ltd.**, with source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.md)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

Note: this company (a B2B/heavy-industry manufacturer) does not publish a general
consumer-facing "Terms of Use" document at its corporate site; the only publicly
available legal document discoverable there is a privacy policy, archived here
(`:tos/doc-type :privacy-policy`) rather than fabricated as a terms-of-service document.

## Company identity

- **Legal name**: Mitsubishi Heavy Industries, Ltd.
- **LEI (ISO 17442)**: [353800TJ98PCAZROVE69](https://search.gleif.org/#/record/353800TJ98PCAZROVE69) (GLEIF-verified)
- **Jurisdiction**: JP
- **Website**: https://www.mhi.com
- **Ticker**: 7011 (TSE)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived legal documents,
  each entry carrying `:tos/full-text`, `:tos/source-url`, `:tos/retrieved-at`,
  `:tos/sha256`, `:tos/doc-type`, and a `:tos/supersedes` chain for future revisions.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`) for why this repo exists,
its LEI-keyed naming, and the git-journal/kotobase.net layering it follows.
