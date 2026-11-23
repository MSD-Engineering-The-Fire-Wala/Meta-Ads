# Prompt for Claude in Chrome: read-only audit of the IQRA-era Google Ads campaigns

> Copy everything below the line into Claude in Chrome.
> Before you start, open https://ads.google.com and log in as the owner of Google Ads account **104-066-6321**.

---

You are a senior Google Ads auditor working for me, the business owner of **The Fire Wala (MSD Engineering), Raipur**. Work in my logged-in Chrome tab, in Google Ads account **104-066-6321**.

This is a **READ-ONLY audit**. Its goal is to learn what worked and what wasted money in the campaigns an outside agency (IQRA) ran, so that my current campaigns can be improved.

## Hard rules
1. **Never change anything.** Do NOT:
   - enable, pause, remove or edit any campaign, ad group, ad, keyword, asset, budget, bid, audience, conversion action, billing or account setting
   - accept recommendations or "Apply" anything
   - change auto-apply settings
   - invite or remove users
2. **Keep the current campaign running.** "TFW Search – Extinguisher Refilling Raipur" (ID 24529130366) is live. Do not open its settings in edit mode.
3. **Stop and ask me** if a page asks for a password, 2FA, payment or a confirmation.
4. **Personal data.** Do not copy customer names, phone numbers or emails into the chat. Lead counts are fine; personal details are not.
5. Use date range **"All time"** (or 1 Jan 2024 – today) unless a step says otherwise.

## Campaigns to audit
- IQRA | Leads | B2C | Raipur (ID 24251655279)
- IQRA | Leads | YT | Chattisgarh (ID 24422843476)
- Leads-Display-1
- TFW-AMC-Refilling-Search
- TFW Refilling Raipur (ID 24533871340)
- Any other paused or removed campaign. Use the filter Campaign status = All, including removed.

## Step 1: Account overview
For every campaign, give me one table with these columns:
- Campaign
- Type (Search / Display / Video / PMax)
- Status
- Start date and end date
- Total spend (₹)
- Impressions, clicks, CTR, avg. CPC
- Conversions, cost per conversion, conversion rate
- Bidding strategy and daily budget

## Step 2: Conversion tracking (most important)
Go to **Goals → Conversions → Summary** and list every conversion action with:
- name, source (website / call / import / GA4)
- status (Active / Inactive / No recent conversions / Unverified)
- count setting (One / Every) and "Primary / Secondary"
- the number of conversions in All time

Then tell me:
- Were IQRA's "conversions" real leads (form submit / call / WhatsApp click), or only page views or "engagement"?
- Is anything counting twice?

## Step 3: Per-campaign details (for each campaign with spend > ₹0)
1. **Locations**
   - Targeted and excluded locations.
   - Location option: "Presence" or "Presence or interest".
   - **Report → Locations / "Where your ads showed"**: the top 10 cities by spend, with clicks and conversions. Flag spend outside Raipur, Bhilai, Durg and their industrial areas.
2. **Keywords** (Search campaigns)
   - All keywords with match type, status, spend, clicks, conversions and Quality Score (with its 3 components).
   - The top 10 by spend and the top 10 by conversions.
3. **Search terms** (Insights & reports → Search terms)
   - The top 50 search terms by spend, with clicks and conversions.
   - Mark each one: ✅ relevant buyer (refilling / AMC / new extinguisher / fire safety for business), ⚠️ unclear, or ❌ waste (jobs, training course, DIY, other cities, competitor names, home or car use).
4. **Negative keywords:** list them.
5. **Ads and assets**
   - Every ad's headlines and descriptions, final URL, status and policy status (note the reason for any disapproval).
   - CTR and conversions per ad.
   - Asset report: which headlines or descriptions are rated "Best / Good / Low".
6. **Audiences and demographics:** age, gender and device split by spend and conversions; any audience segments added.
7. **Ad schedule / time:** spend and conversions by day of week and hour, if available.
8. **Display / YouTube campaigns only**
   - Placements (where the ads showed): the top 20 by spend.
   - Flag mobile apps, games and kids' channels.
   - The video ad used and its view rate.

## Step 4: Landing pages
In **Insights & reports → Landing pages**, list each URL with clicks, conversions and mobile speed score. Note whether it was thefirewala.com, thefirewala.in or another site.

## Step 5: Change history
Open **Tools → Change history** (All time). Summarise in a short timeline:
- who made the big changes (budget, bidding, campaign created, paused)
- when they made them

Use email masking, for example "iqra…@…".

## Step 6: Billing summary (read only)
**Billing → Summary / Transactions**: give me total spend per month for the IQRA period. Do not open or change payment methods.

## Step 7: Export the data for my consultant
Download these reports as **CSV** (All time). If a report has a "Download" icon, use it; do not create scheduled reports.
1. Campaigns
2. Keywords
3. Search terms
4. Locations ("Where your ads showed" / user locations)
5. Ads
6. Conversions summary
7. Change history

Then:
- Tell me each file name and its number of rows.
- Ask me to upload them to my Google Drive folder "TFW Ads Data / IQRA Google".

## Step 8: Final audit report (in the chat)
1. **Scorecard table**, with one row per campaign. Columns:
   - Spend
   - Real leads (only if conversion tracking was real)
   - Cost per real lead
   - Verdict: Winner / Average / Waste
2. **Top 5 money leaks**, with ₹ amounts, for example wrong locations, junk search terms, Display placements in apps, or no conversion tracking.
3. **Top 5 things that worked**, for example keywords, search terms, headlines, areas or times with real leads.
4. **Recommendations** for my current campaign "TFW Search – Extinguisher Refilling Raipur":
   - keywords to add
   - negatives to add
   - headlines that worked
   - areas
   - schedule
   - Do NOT apply them; only list them.
5. **Questions for the owner:** anything you could not verify.

Write the report in simple English. Keep numbers exact, copied from the screens. Write "not available" when data is missing; never guess.
