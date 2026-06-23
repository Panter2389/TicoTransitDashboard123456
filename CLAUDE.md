# Project Memory — Silver Zone Labs

This branch holds business documents for **Silver Zone Labs** (research-use-only peptide
e-commerce) and its corporate stack. Work is for merchant-account / underwriting prep
(BMO Harris via Blacksite Partner) and related business documents.

## 🔒 Sensitive documents — stored locally, NEVER on GitHub
Legal, financial, and identity documents live in:

    silverzonelabs/important_documents/      ← git-ignored, NOT committed

This folder holds the Articles of Organization, EIN letter, government ID, affiliate
banking record, and Stripe processing history. **It contains SSNs, a driver's license,
DOB, and bank details — never commit it.** When you need entity details, EIN, the owner's
ID/legal name/address, banking, or Stripe figures, read:

    silverzonelabs/important_documents/00_KEY_INFORMATION.md

> ⚠️ This environment is ephemeral: the `important_documents/` folder does NOT survive a
> container recycle. The user keeps the authoritative copies in their own secure storage and
> re-uploads when needed. Do not assume the folder is present in a fresh session.

## Non-sensitive context
- **Corporate stack:** TD Capital Holding(s) LLC (parent) → Sierra Integrative Holdings LLC
  (Nevada; Master Series) → Silver Zone Labs (operating brand, silverzonelabs.com).
- **Owner / sole member:** David Lee-Sang (full details in the local key-info file).
- **BMO Harris:** conditionally approved. Outstanding: 2 mo parent merchant statements,
  manufacturing agreement (signature pending). 3 mo personal statements already provided.
- **Known discrepancies to reconcile** before submissions: "Sierra Integrative Holding" (IRS)
  vs "Holdings" (NV); owner street-number mismatch; whether "Silver Zone Labs LLC" is a
  separate entity; "ETZ Bio" vs "Silver Zone Labs" branding on the scaling plan.

## Generated documents (committed, in `silverzonelabs/`)
- `SilverZoneLabs_Strategic_Blueprint_2026_Launch` / `_Scale` (.html/.pdf) — name-corrected.
- `SilverZoneLabs_Manufacturing_Agreement_TEMPLATE` (.html/.pdf).
- `BMO_Application_Package_CoverSheet`, `BMO_Transmittal_CoverLetter` (.html/.pdf).
- `SierraIntegrative_Stripe_Statement_Feb-Apr2026.pdf`.

## Conventions
- Do NOT put SSNs, IDs, EINs, bank/account numbers, or home addresses in any committed file.
- This session is locked to the `ticotransitdashboard123456` repo; a dedicated `silverzonelabs`
  repo exists but is only writable from a session attached to it.
