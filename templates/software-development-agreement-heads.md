# Software development and support agreement — heads of terms

Points to hand a lawyer, rather than starting from a blank page or signing
something you found online.

> **This is not a contract and not legal advice.** It is a list of the decisions
> a development agreement has to make. Have a qualified lawyer draft the actual
> document, especially for cross-border work. See [DISCLAIMER.md](../DISCLAIMER.md).

---

## Why bother, for a small project

Three reasons that show up later:

- **Scope disputes.** Almost every unprofitable small project became unprofitable
  through additions nobody priced.
- **IP ownership.** If it is not written down, ownership of the thing you built
  is genuinely unclear, and that becomes very expensive at exactly the moment it
  matters — when there is a product, an acquirer, or a dispute.
- **Proof of work.** For a Pakistani exporter this is also the document that
  evidences your export is real, for PSEB and for tax.

## Parties and background

- Full legal names of both entities, with company numbers and registered
  addresses. Not trading names.
- **If the parties are connected** — you are a director or shareholder of both —
  say so in a recital, state that the interest is disclosed, and state that the
  terms are agreed on an arm's length basis. Both tax authorities can adjust
  profits between connected enterprises transacting on non-commercial terms, and
  a disclosed relationship priced sensibly is a strength where a discovered one
  is a problem.

## Scope

- What is being built, described specifically enough that a third party reading
  it in two years understands what was bought.
- **What is explicitly not included.** This section is worth more than the
  inclusions.
- Deliverables, with acceptance criteria that are testable rather than
  subjective.
- Assumptions and dependencies — what you need from the client, by when, and what
  happens to the timeline if it does not arrive.

## Characterisation — services or licence

This matters more than it looks, because it can change the tax treatment of
every payment.

- **Development and support services** — the client is buying your work.
- **A licence to use software** — the client is buying the right to use
  something you own, and the payment may be a royalty.

Many jurisdictions require withholding on royalties paid abroad while requiring
none on service fees. If you are genuinely providing development and support,
say so, grant any necessary licence as part of those services, and do not price
it separately as a royalty. If you are genuinely licensing a product, treat it as
a licence. **Characterise what is actually happening** — do not label a royalty
as a service fee to avoid withholding.

Get this checked by an accountant in the *client's* jurisdiction, not only your
own.

## Intellectual property

Decide explicitly, because silence favours nobody:

- Who owns **newly written code**.
- Who owns **pre-existing code** you bring to the project — your libraries,
  frameworks, prior work. Usually you retain these and grant a licence.
- What licence the client receives: exclusive or non-exclusive, transferable or
  not, perpetual or for the term, and what happens on termination.
- Third-party and open-source components, and their licences.
- Whether you may reference the work publicly as a case study, and in what terms.

> The cheapest time to agree IP is before the first line is written. It becomes
> very hard once there is money or a third party attached.

## Charges and payment

- Fixed price against defined outcomes, or a retainer. Avoid open-ended hourly
  billing: when tooling makes you faster, hourly billing cuts your revenue for
  the same output.
- Milestones tied to deliverables, not to dates.
- Currency, and who carries the exchange risk. Quote and invoice in one currency
  and put conversion on the client.
- Payment terms, and what happens when they are missed. State plainly that work
  pauses on an invoice more than a stated number of days overdue and the timeline
  moves by the length of the pause. This is the only leverage a small vendor has,
  and stating it upfront means never having to threaten it.
- Who bears bank charges on international transfers. Say "send in full".
- For a Pakistani exporter: a line instructing the payer to remit as payment for
  information technology services.

## Change control

- Change requests in writing, priced with a timeline impact, before work starts.
- The single largest cause of unprofitable projects at small vendors is politely
  absorbing the fourth "small addition".

## Warranties, support and liability

- A **bounded** warranty period for defect fixes after handover — thirty days is
  common. Unbounded makes you a free support desk forever.
- What counts as a defect versus a change. Define it, or you will argue about it.
- Support and response commitments if there is a retainer, with hours and a
  target response time you can actually meet.
- A liability cap, usually referenced to fees paid. Have a lawyer draft this one.

## Data protection and confidentiality

- Mutual confidentiality, with a term.
- Who is the controller and who the processor, if personal data is involved, and
  which regime applies — a UK or EU client will need this to be right.
- Where data is stored and processed, and whether cross-border transfer is
  permitted.
- **If you have any interest in a business adjacent to the client's**, address it
  here: separate infrastructure, no commingling, and say so in writing rather
  than only in conversation.

## Handover and termination

- What transfers on final payment: code, documentation, credentials, repository
  access, deployment instructions, architecture notes, known limitations.
- Notice period for termination, and what happens to work in progress and to
  amounts already paid.
- What survives termination — confidentiality, IP, payment obligations.

## Governing law and disputes

- Choose a law and a forum, and state them. For cross-border work this is a real
  decision with cost consequences, not boilerplate. Take advice.
- Consider a short escalation path before formal proceedings.

## Signature

- Signed and dated by both parties before work starts and before money moves.
- Electronic signature is fine in most jurisdictions, but keep the audit trail:
  who signed, when, from where, and what they consented to.

> **Sequence matters more than wording.** An agreement signed before the first
> payment is documentation. The same agreement produced two years later after a
> question from a tax authority is a reconstruction, and both sides know the
> difference. A short agreement signed on time beats a long one signed late.
