---
name: weekly-invoice-totals
description: "Weekly invoice totals. Every Monday, Margot adds up what the company owes each supplier and flags any supplier more than 10% above last month."
---

# Weekly invoice totals

Use this skill to run the "Weekly invoice totals" job.

- Reads: the Invoices folder.
- Writes: invoice-totals.xlsx, and a short note.

## Steps

1. Open the Invoices folder you named and list every invoice added since last Monday.
2. For each supplier, add up the amounts owed and write the totals to invoice-totals.xlsx, one row per supplier.
3. Compare each supplier with last month in the same file and flag any total more than 10% higher.
4. List any invoice you could not read, with its file name.

## Before you finish

- Write the note for the office manager.
- Check the red lines in AGENTS.md: nothing sent, nothing deleted, no passwords or account numbers.
