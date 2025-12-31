# Meta Ads Troubleshooting Guide

> When ads aren't performing, use this diagnostic framework.

---

## Quick Diagnostic Framework

```
Ads not delivering?
├── Check: Budget & bidding issues
├── Check: Audience too narrow
├── Check: Ad in review/rejected
└── Check: Account/payment issues

Ads delivering but no results?
├── Check: Wrong optimization goal
├── Check: Creative fatigue
├── Check: Landing page mismatch
└── Check: Tracking broken

Results declining over time?
├── Check: Ad fatigue
├── Check: Audience saturation
├── Check: Seasonal factors
└── Check: Competitor activity
```

---

## Problem 1: Ads Not Delivering

### Symptoms
- Impressions at zero or very low
- "Learning Limited" status
- No spend despite active campaign

### Causes & Fixes

**Budget Too Low**
> Set ad budget at least 10x your target CPA. If target CPA is $50, daily budget should be $500+.

- [ ] Remove spending limits and bid caps temporarily
- [ ] Start with Lowest Cost bid strategy
- [ ] Increase daily budget to exit learning phase faster

**Audience Too Narrow**
> Facebook requires at least 1,000 users in target audience.

- [ ] Expand geographic targeting
- [ ] Remove interest targeting layers
- [ ] Use Lookalike audiences to expand reach
- [ ] Test broad targeting (Andromeda works better with broad)

**Ad Stuck in Review**
> Reviews typically take <24 hours but can take longer during peak periods.

- [ ] Wait 24 hours before escalating
- [ ] Check for policy violations in copy/creative
- [ ] Submit for manual review if needed
- [ ] Create backup ads in case of rejection

**Bid Too Low**
> If using bid caps, your bid may not be competitive.

- [ ] Switch to Lowest Cost (automatic) bidding
- [ ] Remove bid caps temporarily
- [ ] Increase bid cap by 20-30%

---

## Problem 2: Low Click-Through Rate (CTR)

### Benchmarks
| CTR | Status |
|-----|--------|
| <0.5% | Poor - needs work |
| 0.5-0.9% | Below average |
| 0.9-1.6% | Good |
| >1.6% | Excellent |

### Fixes

**Hook Not Working**
- [ ] Test 5-10 different hooks
- [ ] Lead with benefit, not feature
- [ ] Use pattern interrupts
- [ ] Add movement in first 2 seconds (video)

**Wrong Audience**
- [ ] Review audience demographics in breakdown
- [ ] Test broader audiences
- [ ] Exclude past purchasers if not retargeting
- [ ] Check audience overlap between ad sets

**Ad Looks Like an Ad**
- [ ] Use UGC-style creative
- [ ] Remove heavy branding from visuals
- [ ] Make it feel native to the platform
- [ ] Test creator-style content

**Weak Value Proposition**
- [ ] Clarify the key benefit
- [ ] Add social proof
- [ ] Include specific results/numbers
- [ ] Test different angles

---

## Problem 3: High CPC / Low Conversions

### Symptoms
- Clicks but no conversions
- CPA way above target
- Money spent with no results

### Fixes

**Landing Page Issues**
> 53% of mobile users abandon sites that take >3 seconds to load.

- [ ] Check page load speed (aim for <3 seconds)
- [ ] Ensure message match between ad and page
- [ ] Mobile-optimize (90% of Meta traffic is mobile)
- [ ] Simplify the conversion path
- [ ] Add trust signals and social proof

**Wrong Optimization Goal**
> Optimizing for traffic when you want conversions attracts low-intent users.

- [ ] Switch to "Conversions" optimization
- [ ] If low volume, try "Add to Cart" instead of "Purchase"
- [ ] Ensure pixel is firing correctly
- [ ] Check conversion event is correct

**Tracking Problems**
- [ ] Verify pixel is installed correctly
- [ ] Set up Conversions API (server-side tracking)
- [ ] Check for iOS tracking limitations
- [ ] Test with Meta Pixel Helper extension

**Offer Not Compelling**
- [ ] Test different offers (discount, free shipping, bonus)
- [ ] Add urgency (limited time)
- [ ] Reduce friction (buy now pay later, free trial)
- [ ] Address objections in ad copy

---

## Problem 4: Ad Fatigue

### Symptoms
- Performance declining over time
- Frequency above 3-4
- CTR dropping week over week

### Fixes

**Refresh Creative**
- [ ] Introduce new creative every 2-4 weeks
- [ ] Test 5-10 new ads per month minimum
- [ ] Keep top performers running but add fresh creative
- [ ] Vary formats (video, static, carousel)

**Expand Audience**
- [ ] Broaden targeting
- [ ] Create new Lookalike audiences
- [ ] Target new geographic regions
- [ ] Test new interest categories

**Rotate Messaging**
- [ ] Test new angles/hooks
- [ ] Refresh offers
- [ ] Update social proof
- [ ] Seasonal messaging

---

## Problem 5: Cannibalization

### Symptoms
- One ad getting 90%+ of impressions
- Other ads in set barely delivering
- Good ads getting no chance

### Fixes

- [ ] Use separate ad sets for testing
- [ ] Limit to 2-3 ads per ad set (unless using Dynamic Creative)
- [ ] Pause the dominant ad temporarily
- [ ] Use Meta's Creative Testing feature for fair distribution

---

## Problem 6: Learning Phase Issues

### Understanding Learning Phase
- 50 conversions needed to exit learning
- Changes reset the learning phase
- "Learning Limited" means not enough data

### Fixes

**Stuck in Learning**
- [ ] Increase budget to get 50 conversions faster
- [ ] Consolidate ad sets (fewer, larger audiences)
- [ ] Avoid making changes for 7 days
- [ ] Use a higher-funnel optimization event

**Constant Resets**
- [ ] Make significant changes only (not small tweaks)
- [ ] Batch your edits instead of making one at a time
- [ ] Let campaigns run without interference
- [ ] Plan changes strategically

---

## Problem 7: Advantage+ Not Working

### Symptoms
- ASC performance worse than manual
- High CPAs in automated campaigns
- No improvement from AI optimization

### Fixes

**Not Enough Data**
- [ ] Need 50+ weekly conversions for ASC to work well
- [ ] Consider manual campaigns for new products
- [ ] Feed more creative variety

**Poor Creative**
> Creative accounts for 56% of ASC outcomes.

- [ ] Add 8-15 genuinely different concepts
- [ ] Test various formats and angles
- [ ] Refresh creative regularly
- [ ] Don't just rely on variations

**Tracking Issues**
- [ ] Verify pixel + CAPI setup
- [ ] Check attribution settings
- [ ] Ensure all conversion events fire correctly

---

## Weekly Audit Checklist

Run this every week to catch issues early:

**Performance Check**
- [ ] Review key metrics (CTR, CPC, CPA, ROAS)
- [ ] Compare to previous week
- [ ] Check frequency levels
- [ ] Review breakdown by placement, device, age

**Creative Health**
- [ ] Note any ads with declining performance
- [ ] Check ad fatigue indicators
- [ ] Plan new creative if needed
- [ ] Review competitor activity

**Technical Check**
- [ ] Verify tracking is working
- [ ] Check for policy notifications
- [ ] Confirm payment method is current
- [ ] Review any Meta notifications

**Budget & Bidding**
- [ ] Check for underspending
- [ ] Review bid strategy performance
- [ ] Reallocate budget to winners
- [ ] Pause underperformers

---

## Diagnostic Tools

### Meta Native Tools
- **Delivery Insights:** Understand why ads aren't delivering
- **Audience Overlap Tool:** Find ad set conflicts
- **Breakdown Reports:** Analyze by placement, device, demo
- **Account Quality:** Check for policy issues

### Third-Party Tools
- **Meta Pixel Helper:** Chrome extension for pixel debugging
- **Facebook Ads Debugger:** Verify tracking
- **GTM Preview Mode:** Debug tag implementations

---

## When to Escalate

Contact Meta Support if:
- Ad stuck in review >48 hours
- Account disabled without clear reason
- Technical bugs affecting delivery
- Payment issues despite valid method

Contact via:
- Meta Business Help Center
- Live chat (if available)
- Meta Business Partner (if working with agency)

---

## Emergency Playbook

### Campaign Suddenly Stopped Working

1. **Don't panic, don't make lots of changes**
2. Check for any Meta platform issues (Twitter/X: @MetaforBusiness)
3. Review recent changes you made
4. Check pixel/tracking first
5. Look at creative fatigue metrics
6. Review competitor landscape
7. Give it 24-48 hours before major changes
8. Test new creative while diagnosing

---

*Last updated: December 31, 2025*
