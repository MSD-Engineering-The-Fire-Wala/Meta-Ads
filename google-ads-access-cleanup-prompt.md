# Prompt for Claude in Chrome: Google Ads access check + IQRA removal + "Presence" location setting

> Copy everything below the line into Claude in Chrome.
> Before you start, open https://ads.google.com and log in as the owner of Google Ads account **104-066-6321** (MSD ENGINEERING).

---

You are helping me, the business owner of **The Fire Wala (MSD Engineering), Raipur**, secure my Google Ads account and fix one campaign setting. Work in my logged-in Chrome tab, in Google Ads account **104-066-6321** only. Go one step at a time.

## Goals
1. Confirm that the outside agency **IQRA Digital Solutions** no longer has any access. Remove anything that is left, after my approval.
2. Give me a complete list of everyone and everything that can access this account.
3. Set the location option of my live campaign to **"Presence"**.

## Hard rules
1. **Read first, then change.** Do Steps 1–3 (read only), show me the report, and wait for me to reply **"approve"** before Step 4.
2. Before each click that removes access or saves a setting, tell me exactly what will change and wait for my **"yes"**.
3. **Never do any of the following:**
   - pause, enable, edit or remove any campaign, ad group, ad, keyword, budget, bid or schedule
   - change billing or payment methods
   - accept any recommendation, or change auto-apply
   - remove or change **my own** access
   - remove the **Windsor.ai** API connection or linked accounts, unless I say so
4. **Stop and ask me** if:
   - Google asks for a password, 2FA or a security check
   - removing someone would leave the account with fewer than 2 admins
   - a user or link looks unknown and you are not sure what it is
5. Mask emails in the chat, for example "asif…@iqradigitalsolutions…". Do not paste full emails or phone numbers.

## Step 1: Users (read only)
Open **Admin (gear icon) → Access and security → Users**.

1. List every user with the masked email, access level (Admin / Standard / Read only / Billing / Email only) and status (active / pending invitation).
2. Check specifically:
   - Is any **@iqradigitalsolutions** user still listed, active or pending? The two known users are asif…@ and muzamm…@.
   - Is there any **pending invitation**? There was an "Administrative access" invitation sent on **21 Nov 2026 at 13:26**. Tell me which email it went to (masked) and whether it is accepted or pending.
   - Are there any users I may not recognise? Mark them "Unknown, ask owner".

## Step 2: Other ways into the account (read only)
1. **Admin → Access and security → Managers.** List any manager (MCC) accounts linked to this account. Note whether any belongs to IQRA or an agency.
2. **Admin → Access and security → Security.** Note:
   - whether 2-step verification is required
   - any "allowed email domains" setting
3. **Tools → Data manager / Linked accounts.** List the linked Google Analytics, Business Profile, YouTube, Merchant Center and third-party apps. Note any that look agency-owned.
4. **Admin → API Center (if shown).** Just note whether a developer token exists. Do not change it.

## Step 3: Report (then wait)
Give me a table with these columns:

| Who / what | Type (user / manager / link / invite) | Access level | Status | Belongs to IQRA? | Recommendation (Keep / Remove / Ask owner) |
|---|---|---|---|---|---|

Then wait for my reply **"approve"**.

## Step 4: Remove IQRA access (only after "approve", one at a time with "yes")
1. **Remove users:** for each @iqradigitalsolutions user still present (active or pending), open the user and choose **Remove access**.
2. **Cancel or remove invites:** for a pending invite to anyone I mark "Remove", choose **Cancel invitation**.
3. **Unlink manager accounts:** for an IQRA manager (MCC) link, if I approve, choose **Unlink / End link**.
4. Do nothing to any user, link or invite I mark "Keep".

## Step 5: Location option "Presence" on the live campaign
1. Open **Campaigns** and click the campaign **"TFW Search – Extinguisher Refilling Raipur – Nov26"** (ID 24529130366).
2. Go to **Settings → Locations**. Expand **Location options**.
3. Report the current choices for **Target** and **Exclude**.
4. If Target is not already **"Presence: People in or regularly in your included locations"**, tell me and wait for my **"yes"**. Then select it and click **Save**.
5. Do NOT change:
   - the 40 km radius target
   - the languages
   - the budget, bidding or ad schedule
   - any other setting on this page

   If any warning appears, stop and show it to me.
6. Re-open the setting and confirm that "Presence" is saved.

## Step 6: Final check and report
1. Re-open **Users**. Confirm there is no @iqradigitalsolutions user and no unwanted pending invitation.
2. Confirm that campaign 24529130366 is still **Enabled / Eligible**, with its budget unchanged at **₹150/day**.
3. Give me a table with these columns:

| Item | Before | After | Status (Done / Not needed / Waiting for me) |
|---|---|---|---|

4. Suggest, but do not change:
   - turning on **"Require 2-step verification"** for all users
   - keeping at least 2 admins I trust
