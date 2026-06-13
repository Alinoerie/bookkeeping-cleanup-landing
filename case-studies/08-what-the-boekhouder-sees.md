# Case Study 8: "What the boekhouder sees" — the reviewer perspective

> Anonymised. The boekhouder: NL one-person practice, 12 years experience, 80+ ZZP clients. What she actually looks at when she reviews my output.

## The misconception

Most cleanup services pitch: "We do the work, your accountant just signs it." That's the wrong framing. The accountant does more than sign — they REVIEW. The review is what makes the cleanup valuable.

A 4-6 hour review, vs a 30-60 minute review, is the difference between the accountant trusting your work and the accountant redoing your work from scratch.

## What the boekhouder actually checks

When my output lands in her inbox, she opens 4 things in this order:

1. **The summary report (SAMENVATTING.md / SUMMARY.md)** — does the structure make sense? Are the right items flagged? Is the language one a boekhouder would use, or is it the language of an AI tool that doesn't understand bookkeeping?

2. **The "needs your review" list** — the transactions I flagged. The boekhouder looks at this list to estimate her own review time. If I flag 50 items, she expects a 2-hour review. If I flag 5, she expects a 30-minute review. **The quality of my flagging determines the boekhouder's review time.**

3. **The categorized CSV** — a sample of 10-20 transactions. Not the whole thing, just a sample. She checks: are the categorizations reasonable? Are the BTW codes correct? Is the formatting what her accounting software imports correctly?

4. **The P&L** — the year-at-a-glance view. Does the math add up? Are the categories sensible? Is the trend reasonable?

She does NOT check every transaction. That would take 4 hours. She checks 10-20 of them, and if they look right, she signs off on the rest. **Her trust in me is built on a sample, not a full audit.**

## What makes the boekhouder's review fast (30-60 min)

Three things, in order of importance:

1. **The flagged items are real and specific.** "Mixed personal/business, needs judgment" is bad. "Bol.com €85 on 2024-11-15: 60% likely personal (groceries), 40% possibly business (kantoorartikelen). Confirm or split." is good. The boekhouder looks at the specific transaction, makes the call in 30 seconds, moves on.

2. **The categorization is BTW-correct.** If I categorize "Kantoorartikelen" under "Kantoorkosten, 21% BTW" and the boekhouder knows that's wrong (e.g., it's actually a 9% category), the trust breaks instantly. BTW/HMRC accuracy is the single biggest trust signal.

3. **The summary is in plain Dutch/English.** Not AI-generated jargon. Real words a boekhouder would use. "Persoonlijke uitgaven" not "Personal expenditure classification." "Te beoordelen" not "Requires human review."

## What makes the boekhouder's review slow (4+ hours)

The opposite of all three:

1. **Generic flags.** "Needs review" without context. The boekhouder has to figure out what to look at.
2. **Wrong BTW codes.** The boekhouder has to re-categorize before signing.
3. **AI-generated summary.** The boekhouder doesn't trust the output because the language is "computer-y."

## What the boekhouder's "this is good" criteria looks like

After 10-20 sample transactions and the flagged items, the boekhouder's decision tree is:

- ✅ Categorization matches her style → 30-min review, sign-off
- ⚠️ A few questionable items but most are fine → 1-hour review, sign-off with notes
- ❌ More than 10% looks wrong → 2-3 hour review, request revision

**My target: 95%+ of my categorizations match what the boekhouder would do.** That's the bar for a 30-60 minute review. Below 90% and the review time doubles.

## What the boekhouder wishes the cleanup service would do

I asked this boekhouder directly. Her top 5 wishes:

1. **Pre-fill the BTW-aangifte** — the actual tax form, not just the categorized data. I should produce a draft aangifte, not just a CSV.
2. **Auto-match to existing customer records** — if a vendor (e.g., "Coolblue B.V.") is in her records, the cleanup should use her name, not re-create it.
3. **Flag duplicate transactions** — if the same transaction appears twice (bank feed error), flag it.
4. **Include the original bank statement row** — so she can verify against the source.
5. **Provide an English version** for the international ZZP'ers (UK, US, German) in her client base.

These are all small features that would 2-3× the cleanup fee. Each is 2-3 weeks of work. None of them are deal-breakers for the first 100 cleanups. But after I have 5+ boekhouders, the cumulative asks are a v2 product roadmap.

## What this means for the cleanup product

The cleanup is not "data prep" or "categorization." The cleanup is **"a boekhouder-ready file that takes 30-60 minutes to review and sign."** The difference between a 30-minute review and a 4-hour review is €1,000-2,000 in saved time for the boekhouder's client.

**The cleanup is judged by the boekhouder's review time, not the categorization accuracy.** A 100% accurate cleanup that takes 4 hours to review is worse than a 95% accurate cleanup that takes 30 minutes to review. The boekhouder's time is the scarce resource, not mine.

## What this means for the cleanup service positioning

**Sell the review-time savings, not the categorization accuracy.** The boekhouder doesn't care if I'm 95% or 99% accurate. She cares if her review takes 30 minutes or 4 hours.

The pitch becomes: "I do the cleanup so you don't have to. Your review takes 30 minutes, not 4 hours. Your client pays €400 for the cleanup, you charge €150 for the review, the client saves €1,000-1,500 vs your normal cleanup quote, and you save 3-4 hours."

That's the pitch. **The categorization accuracy is implicit, not the headline.**

## What this means for the v2 product

If I want to charge €800-1000 per cleanup instead of €400-500, I need to add the features the boekhouder wants:
- Pre-filled BTW-aangifte / Self Assessment draft
- Auto-match to existing customer records
- Duplicate detection
- Bank statement cross-reference
- English / Dutch / German output

Each of these is 1-2 weeks of work. Each is also a 2× price increase. **The boekhouder's "I wish you did X" list is the v2 product roadmap.**

## What I learned

- **The cleanup is judged by review time, not accuracy.** A 95% accurate cleanup that takes 30 minutes to review is more valuable than a 99% accurate cleanup that takes 4 hours.
- **The boekhouder's review is a quality check, not just a sign-off.** She looks at a sample, not the whole thing. Trust is built on the sample.
- **BTW/HMRC accuracy is the single biggest trust signal.** If the categorization is correct, the boekhouder trusts the rest.
- **Specific flags beat generic flags every time.** "Mixed personal/business" is bad. "Bol.com €85, 60% likely personal" is good.
- **The v2 product is the boekhouder's wish list.** Pre-filled aangifte, customer matching, duplicate detection. Each is 1-2 weeks and 2× the price.

## What this means for MRR

- **Year 1: €400-500 per cleanup, 30-60 min boekhouder review, 95% accuracy.** This is the current product.
- **Year 2: €800-1000 per cleanup, 15-30 min boekhouder review, 98% accuracy + aangifte draft.** This is the v2 product.
- **Year 3: €1500 per cleanup, 10-min boekhouder review, 99% accuracy + filed aangifte.** This is the v3 product.

Each year, the price goes up because the boekhouder's review time goes down. **The cleanup becomes more valuable to the boekhouder, not less, as the product matures.**

The 5-10 boekhouder partners produce 80-160 cleanups per year at €400-1500 each = **€32,000-240,000/year in cleanup revenue at maturity.** Plus monthly bookkeeping at €150-300/mo for the converted 10-20% = **€2,000-10,000 MRR.**

## The leverage insight

**The cleanup service is a learning loop with the boekhouders.** Every cleanup teaches me what they need next. The v2 product features come from the boekhouder's wish list, not from my own product roadmap. **The boekhouders are the product managers, I'm the engineer.**

This is a fundamentally different model from "I think this is what the buyer wants." It's "the buyer (boekhouder) tells me what they want, I build it." Lower risk, higher conversion, faster iteration.

## What I'd recommend to another cleanup service

1. **Track the boekhouder's review time per cleanup.** This is your quality metric. Target: 30-60 minutes.
2. **Be specific in your flags.** "Mixed personal/business" is bad. Specific transactions with specific questions are good.
3. **Get BTW/HMRC accuracy above 95%.** This is the trust signal.
4. **Listen to the boekhouder's wish list.** That's your v2 product.
5. **Position the cleanup as review-time savings, not categorization accuracy.** The boekhouder cares about her time, not your accuracy.

## The strategic implication

**The cleanup is not a product. The cleanup is a relationship.** The relationship is with the boekhouder, not the buyer. The buyer's transaction is one-time; the boekhouder's relationship is 5+ years. Build the relationship; the transactions follow.
