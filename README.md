# NPA contractor & creditor invoice portal — wireframes

Interactive click-through wireframes prepared by DMC Consultancy Ltd for the
National Ploughing Association. Contractors and creditors upload their invoices
in one portal, and NPA's finance team checks, approves and tracks them in the
other, so every invoice and cost is in one place.

It's a tracker, not a payment system: no payments are made here. Approved
invoices go to NPA's accounts package (Big Red Cloud) to be paid as now, and NPA
can mark them as paid so the costs tracker stays complete.

The landing page links to two connected desktop portals that share the same demo data:

| Portal | What it covers |
| --- | --- |
| **NPA Finance** | Overview with alerts, invoice inbox (PO and duplicate checks, coding), approvals by budget holder (a second approval over €25,000), costs tracker by category and by contractor for each event, purchase orders, contractors & creditors, settings |
| **Contractor & creditor portal** | Dashboard, upload an invoice (details auto-filled from the file, PO balance and duplicate warnings), invoice tracker with messages and queries, purchase orders |

Anything done in one portal shows up in the other. For example, upload an
invoice as a contractor, then approve it in NPA Finance. The "Viewing as" menu
switches between contractors, and "Reset demo data" puts the seed data back.

All companies, people and figures are invented. File reading, emails and the
Big Red Cloud link are mocked.

## Running it

```bash
npm start          # http://localhost:3000
```

or, without Node:

```bash
python3 -m http.server 3000 --directory public
```
