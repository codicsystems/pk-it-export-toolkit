# Pakistan IT Export Toolkit

Templates and checklists for Pakistani software companies and freelancers who
invoice clients abroad — the paperwork that decides whether your export income
is taxed at the concessional rate or at ordinary rates.

Everything here is a document you can fill in and use today. No dependencies,
nothing to install.

> **This is not tax or legal advice.** Rates, thresholds and banking rules in
> Pakistan change with each Finance Act and each State Bank circular. Verify
> anything you are about to file or pay against the relevant official source at
> the time you act on it, and take advice from a qualified practitioner where a
> decision has legal or financial consequence. See [DISCLAIMER.md](DISCLAIMER.md).

---

## Why this exists

Most guides for Pakistani IT exporters stop at "register with PSEB". The
problems that actually cost people money happen afterwards, in banking:

- An inbound payment gets coded as a **home remittance** instead of an IT
  services export, so no withholding happens, the income is never documented as
  export income, and the entitlement to final-tax treatment becomes arguable.
- Nobody asks the bank for a **Proceeds Realisation Certificate**, so there is
  no proof of export income when it is needed for a tax assessment, a PSEB
  renewal or a visa application.
- Money accumulates in a **Payoneer balance** rather than being repatriated,
  putting the concessional treatment at risk.
- An **invoice** says "consulting services" and triggers questions from a
  remittance desk that a specific service description would not have raised.

Each of those is preventable with a piece of paper. This repository holds the
pieces of paper.

---

## What's in here

| File | What it does |
|---|---|
| [`templates/invoice-template.html`](templates/invoice-template.html) | A print-ready export invoice that satisfies the client's finance team, your bank's remittance desk and FBR at the same time. Open in a browser, edit, print to PDF. |
| [`templates/purpose-code-declaration.md`](templates/purpose-code-declaration.md) | The one-time letter to your bank declaring the nature of your export services, so inbound payments are coded correctly from the start. |
| [`templates/board-resolution-account-opening.md`](templates/board-resolution-account-opening.md) | Board resolution for opening and operating a company bank account, naming the authorised signatory. |
| [`templates/software-development-agreement-heads.md`](templates/software-development-agreement-heads.md) | Heads of terms for a development and support agreement — the points to hand a lawyer rather than starting from a blank page. |
| [`checklists/first-90-days.md`](checklists/first-90-days.md) | Every registration step in dependency order, because doing them out of order is the most common reason this takes three months instead of three weeks. |
| [`checklists/per-payment.md`](checklists/per-payment.md) | The four things to do every time money arrives from abroad. |
| [`checklists/compliance-calendar.md`](checklists/compliance-calendar.md) | Recurring obligations with their deadlines. |
| [`reference/purpose-codes.md`](reference/purpose-codes.md) | Why the purpose code on an inbound remittance matters more than almost anything else, and what to do when it is wrong. |
| [`reference/payment-rails.md`](reference/payment-rails.md) | What actually works for receiving money in Pakistan, with the fee crossover point. |
| [`reference/glossary.md`](reference/glossary.md) | PSEB, PRC, ESFCA, ATL, NTN, CUIN — the acronyms, explained once. |

---

## Start here

If you are setting up a company:

1. Read [`checklists/first-90-days.md`](checklists/first-90-days.md) and do the
   steps in the order given. Each one produces a document the next one needs.
2. When you open the bank account, take
   [`templates/purpose-code-declaration.md`](templates/purpose-code-declaration.md)
   on your letterhead. **Do this before your first client payment arrives, not
   after** — a wrong code is easy to correct within days and hard within months.
3. Use [`templates/invoice-template.html`](templates/invoice-template.html) for
   your first invoice. Fill in the placeholders marked `[LIKE THIS]`.
4. When the money lands, work through
   [`checklists/per-payment.md`](checklists/per-payment.md).

If you are already trading and something is going wrong, the two most likely
causes are in [`reference/purpose-codes.md`](reference/purpose-codes.md).

---

## The two things people get wrong most often

**One — the purpose code.** IT and IT-enabled services exports are coded
differently from personal or family remittances. Banks have been widely reported
to default to the wrong one. The correction is administrative within days and a
negotiation within months, so check the credit advice for *every single payment*
rather than assuming. [Details](reference/purpose-codes.md).

**Two — not repatriating.** Concessional treatment of export income is
conditional on bringing the proceeds into Pakistan through banking channels.
Letting balances accumulate in a foreign payment platform puts that treatment at
risk across your whole export book, not just the part left abroad. Withdraw
monthly as a discipline, whether or not you need the money.

---

## Contributing

Corrections are very welcome, especially from practising accountants and people
who have recently been through a specific process. Two rules:

- **Cite a source.** Link the SBP circular, the FBR page, the Act, or say
  plainly "this is what happened to me at [bank] in [month]" — first-hand
  experience is valuable, it just needs labelling as experience rather than rule.
- **No advice.** This repository holds templates and checklists. It does not
  tell anyone what their tax position is.

Open an issue before a large pull request so we can agree the shape.

---

## Licence

[MIT](LICENSE) for the templates and code. Use them commercially, modify them,
no attribution required — though a star is appreciated if this saved you a
morning.

Maintained by [Codic Systems](https://codicsystems.com), a software company in
Islamabad. We built these for ourselves and there was no reason to keep them.
