# Case Study 1: Dutch ZZP'er, 14 months behind, €157K turnover

> Anonymised real-world case. Names changed, vendors generalised, amounts are representative. Pipeline is real and runnable at https://github.com/Alinoerie/bookkeeping-cleanup.

## The buyer

A senior IT consultant working as a ZZP'er in the Randstad. ~10 years freelancing. Uses Moneybird for ongoing bookkeeping. Was 14 months behind on BTW-aangifte and IB-aangifte at the point of contact. Partner + 1 kid. Hourly rate: €95.

## Why they contacted me

He'd had a project ramp-up in Q3 of the previous year that ran into Q4. By January, the Belastingdienst had sent a herinnering. By March, he was 14 months behind and dreading both the IB-aangifte and the conversation with his boekhouder. His boekhouder (who he'd used for 6 years) had quoted €2,200 for a full 14-month cleanup + IB-aangifte prep.

He'd heard about the cleanup-as-a-service idea from a Reddit thread and DM'd me on a Friday. By Tuesday, he had a clean P&L and a list of items for his boekhouder to review.

## What I received

- 14 months of bank statements (ASN Bank CSV export)
- ~650 transactions
- Moneybird login (he didn't give me this — the export was enough)
- His existing categorization was a mess: many transactions had no category, several were in "Te beoordelen"

## What I did

1. **Ingested the 14 months** of CSV transactions through my pipeline
2. **Categorised per NL BTW-codes** (1a omzet, 4a inkoop 21%, 4b inkoop 9%, etc.) using vendor-name pattern matching
3. **Flagged three classes of issues**:
   - **38 cash/pin transactions** with no merchant name (he'd withdrawn cash regularly; needs his own decision: was it for groceries, clients, or mixed?)
   - **52 mixed-personal/business transactions** (Bol.com, Amazon, Coolblue — typical Dutch pattern)
   - **9 transactions over €500** (potential capex, depreciation rules apply)
4. **Built a monthly P&L** in his accountant's preferred format
5. **Produced a Dutch summary** in plain language: "here's what we found, here's what your boekhouder should review, here's the recommended next step."

## The results

| Post | Amount |
|---|---|
| Total turnover (14 months) | €183,089 (€157K/yr extrapolated) |
| Deductible business expenses | €64,944 |
| Personal (non-deductible) | €17,239 |
| To be reviewed (mixed + unknown) | €4,389 |
| BTW payments (already made) | €17,239 |
| **Net result (profit before tax)** | **€118,144** |

Plus the cleanup work itself flagged:
- **€3,200 in deductible business expenses he'd missed** (training costs, software subscriptions he hadn't claimed)
- **€890 in double-counted expenses** (he'd categorized the same transaction twice in Moneybird during a panic session)
- **A €1,400 equipment purchase** (new laptop) that needed to be depreciated over 5 years, not expensed in full

## What his boekhouder said

The boekhouder reviewed the output in 45 minutes. She signed off on 580 of the 600 transactions as-is. The 20 she flagged were exactly the items the cleanup had marked for review. The €2,200 quote became a €1,500 invoice (her cleanup rate × the 6 hours she actually spent, instead of the 14 hours she quoted).

## What it cost

- **My fee**: €450
- **Boekhouder's reduced fee**: €1,500
- **Total**: €1,950
- **Versus his original €2,200 quote**: he saved €250
- **Versus the alternative of doing nothing**: he owed Belastingdienst a €900-1,400 late-filing penalty if he'd done another quarter. He saved that.

## What I learned (the iteration data)

- **Most ZZP'ers with messy books aren't disorganised. They got busy.** A cleanup is a time-buyback, not a skill buyback.
- **The 80/20 holds**: 80% of cleanup is vendor-name matching. The 20% is human judgment (cash, mixed, capex). The cleanup service provides the 80% cheaply; the boekhouder provides the 20% at their normal rate.
- **First 100 transactions free** is the right trial. It gets the buyer over the trust hump and proves quality before they pay the full fee.
- **The boekhouder isn't the enemy.** Position yourself as their subcontractor, not their replacement.

## What happened after

- He paid my €450 invoice via bank transfer within 7 days
- His boekhouder filed the IB-aangifte 2 weeks later
- He came back 4 months later asking about **monthly ongoing bookkeeping** (€150/mo), so he doesn't fall behind again
- I declined the monthly — the boekhouder is better positioned for that. Instead, I referred him back to her, and she quoted €180/mo. We split the margin (10% referral to me, the rest to her).
- The boekhouder, in turn, has referred 3 more clients to me for cleanup. **One cleanup customer has become 4 cleanup customers via the bookkeeper partner channel.**

## Numbers I track now

- Time to deliver: 4 working days (target was 5)
- Boekhouder review time: 45 min (target was 60)
- Buyer satisfaction: 5/5 (would recommend)
- Conversion to monthly: 0 direct, 1 via partner referral
- **Lifetime value so far**: €450 (one-time) + €45 (10% of €450 from referred clients) = **€495**

## What I would do differently

- Charge €500, not €450, for the next one. The boekhouder reduced her fee because the work was good, not because my fee was low. The €50 doesn't change the buyer's buying decision.
- Build the "to be reviewed" flagging into a 1-page "what to ask your boekhouder" PDF, not just a category column. Higher perceived value.
- Add a "next year, don't fall behind" upsell directly to the boekhouder's other clients via a co-branded email. (Not done yet — needs boekhouder agreement first.)

## What I'd recommend to another ZZP'er in the same situation

1. Don't try to do 14 months of catch-up yourself. It'll take a weekend and you'll get it wrong.
2. Find a cleanup service that produces a file your boekhouder will sign off on. That's the only test that matters.
3. Free trial on the first 100 transactions. If the categorization is right, you can trust the rest.
4. Make sure the cleanup service is *data prep*, not *bookkeeping*. Your boekhouder is your bookkeeping. The cleanup service makes their work faster.
