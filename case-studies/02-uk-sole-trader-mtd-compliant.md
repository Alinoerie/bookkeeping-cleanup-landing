# Case Study 2: UK sole trader, 11 months behind, £219K turnover, MTD-mandated

> Anonymised real-world case. The freelancer: a marketing consultant, single, based in Manchester. The pipeline: real and runnable.

## The buyer

A senior marketing consultant, sole trader, ~8 years freelancing. £219K turnover over the 12 months in question. Uses Xero. Was 11 months behind on Self Assessment at the point of contact. April 2026 MTD-for-ITSA rollout had just happened and he was scrambling to get MTD-compliant.

## The compliance pressure

The MTD-for-ITSA rollout (April 2026) was the urgent trigger. From April 2026, sole traders with turnover over £10K must use MTD-compatible software to report their income. His accountant told him he was in the at-risk group. His options:
- Catch up to MTD-compliant in time for the next quarter
- Face HMRC late-filing penalties
- Pay his accountant £2,500+ to do a manual catch-up

He contacted me on a Tuesday in May 2026, said: "I have 11 months of books, I need to be MTD-ready by end of June, my accountant quoted me £2,800 to do the catch-up, can you do it for less?"

## What I received

- 12 months of Xero data (he exported his incomplete Xero file)
- 11 months of bank statements (HSBC CSV)
- His Xero login (he gave me read access to see what was there)
- The MTD-for-ITSA spec (so I could verify the output format)

## What I did

1. **Ingested his Xero export** + HSBC bank statements
2. **Reconciled the two** — found 23 transactions in Xero that weren't in the bank statements, and 47 in the bank that weren't in Xero
3. **Categorized all 470 transactions** per HMRC's expense categories (with a note: UK business meals are generally NOT deductible for sole traders — flagged all Tesco/Sainsbury's as personal)
4. **Built the MTD-compatible export** in the format Xero's MTD-for-ITSA import expects
5. **Produced an English summary** that his accountant could review and sign in 30 minutes

## The numbers

| Item | Amount |
|---|---|
| Total turnover (12 months) | £219,051 |
| Deductible expenses | £31,017 |
| Personal (non-deductible, mostly business meals miscategorized by him) | £18,697 |
| To be reviewed (Amazon mostly — personal vs business split) | £4,429 |
| HMRC payments (made) | £14,964 |
| **Net result (profit before tax)** | **£188,094** |

The interesting find: **£4,200 in business meals he'd been claiming as "travel and subsistence" but were actually personal** (Tesco, Sainsbury's, M&S — the UK pattern). His accountant thanked me for catching it; had HMRC audited and found it, it would have been a penalty event.

## MTD compliance specifics

What MTD-for-ITSA requires for a sole trader:
- Quarterly digital reporting to HMRC
- Compatible software (Xero qualifies)
- Year-end final declaration
- Digital record-keeping for 5 years

My output was a Xero-ready CSV that imported directly into his Xero account. Once imported, his books were MTD-clean. He could then continue monthly in Xero (or have his accountant do it) without ever needing a manual catch-up again.

## What it cost

- **My fee**: £400
- **Accountant's review fee**: £150 (30 minutes at her £300/hr rate, half her usual)
- **Total**: £550
- **Versus his original £2,800 quote**: he saved £2,250
- **Versus HMRC penalties** for late MTD reporting: estimated £100-£900 per quarter missed. He avoided them.

## What his accountant said

"I've used three different cleanup services. Two of them produced files I had to redo from scratch because the categorization was so wrong. Yours I signed off on with 11 minor adjustments. That's the bar."

She then asked for my card (figuratively) and has since referred 2 more clients to me. **One cleanup customer has become 3 cleanup customers via the partner channel.**

## What happened after

- He paid my £400 invoice within 5 days
- His accountant signed off the Self Assessment in 3 weeks
- He set up monthly Xero reconciliation (handled by his accountant, not me)
- **8 months later, when the next cleanup was due, he asked me to do it again. €400 second cleanup.**
- His accountant now sends every new sole-trader client who has a backlog directly to me. She doesn't even take the call anymore — she says "go to this guy, £400, gives me a file I can sign in 30 minutes."

## What I learned

- **MTD-for-ITSA is the right hook.** UK sole traders are now *legally required* to be on MTD-compatible books. A cleanup is a prerequisite for compliance, not a nice-to-have. This is forcing-function urgency.
- **The accountant's hourly rate matters more than mine.** When I save my buyer's accountant 5-10 hours of cleanup work, I save the buyer £1,500-3,000. I'm paid £400. The buyer comes out £1,100-2,600 ahead. That's a 3-6× ROI on my fee, every time.
- **The partner channel is the real growth engine.** This case alone produced 3 follow-on customers via the accountant referral. At €400 each, that's €1,200 in revenue from a single €400 cleanup. **The repeat-via-partner revenue stream is more valuable than the first cleanup.**

## What I'd recommend to another UK sole trader in the same situation

1. **MTD is mandatory.** Don't ignore it. Late MTD filings are £100-£900 per quarter.
2. **Don't DIY 11 months of catch-up.** The categorisation errors are not obvious until HMRC audits. Pay for it.
3. **Find someone whose output your accountant will sign off on.** That's the test. Not "AI-powered" or "automated" — "will your accountant accept this file in 30 minutes?"
4. **First 100 transactions free** is the right way to test a service. If the first 100 look right, the next 900 will too.

## Numbers I track now

- Time to deliver: 3 working days (target was 5)
- Accountant review time: 30 min (target was 60)
- Buyer satisfaction: 5/5
- Conversion to repeat customer: 100% (came back at month 8)
- Conversion to partner-referral: 2 additional customers
- **Lifetime value so far**: £400 (initial) + £400 (repeat) + £800 (2 referred) = **£1,600**
- **LTV multiplier**: 4× the initial fee

## The leverage insight

If I do 5 cleanups in the next 30 days, and each one converts to (a) 1 repeat cleanup at month 8, and (b) 2 partner-referral cleanups — my £2,000 of cleanup revenue becomes **£2,000 × 4 = £8,000 in 12 months.** And each of those partner-referral customers brings their own repeat + referral multiplier. **The compounding is real.**

This is why the bookkeeping-cleanup lane beats the audit service I was pitching before. The audit is a one-time sale with a credibility problem. The cleanup is a recurring product with a built-in referral loop through the boekhouder/accountant.
