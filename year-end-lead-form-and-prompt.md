# Year-End Refilling – Instant Form (text) + Claude in Chrome prompt

## Part A: Form content (founder-approved facts only)

**Form name (internal):** TFW Year-End Refilling – Dec26
**Form type:** Higher intent (adds a review screen before submit, which filters casual taps)
**Page:** MSD Engineering - The Firewala (Page ID 110106411446896)
**Language:** English

### 1. Intro screen
- **Background image:** use the ad's image (default).
- **Headline:** Fire extinguisher refilling from ₹100/kg + GST
- **Description (paragraph):**
  Year-End Offer, valid till 31 Jan 2027. ABC, CO2, Foam and Water extinguishers. 24–48 hours turnaround (depends on type). Refilling certificate and next-due-date sticker on every cylinder. ISO 9001:2015 certified, serving Raipur since 2016.

### 2. Questions
**Prefilled (from Facebook):**
- Full name
- Phone number

**Custom questions:**
| # | Question | Type | Options |
|---|---|---|---|
| 1 | Company / organisation name | Short answer | — |
| 2 | How many extinguishers need refilling? | Multiple choice | 1–3 · 4–10 · 11–25 · More than 25 |
| 3 | Which type? | Multiple choice | ABC powder · CO2 · Foam · Water · Mixed / not sure |
| 4 | Where is your site? | Multiple choice | Raipur city · Raipur industrial area (Siltara, Urla, Bhanpuri, Birgaon) · Bhilai · Durg · Other |
| 5 | Your role | Multiple choice | Owner / Director · Safety officer · Admin / Facility manager · Purchase · Other |

All questions are required.

### 3. Privacy policy
- **Link text:** Privacy Policy
- **URL:** https://www.thefirewala.in/privacy-policy/ (goes live after founder approval)

### 4. Review screen (higher intent)
Keep Meta's default review text.

### 5. Completion screen
- **Headline:** Thank you! We have received your request.
- **Description:** Our team will call you within 1 hour (Mon–Sat, 10 am – 7 pm). Outside these hours, we will call you as soon as possible. For a faster quote, WhatsApp us your cylinder quantity and type.
- **Button:** Call business → +91 77720 78610

### Not to include anywhere in the form
- Spare-part charges, trolley / 50 L units, or pickup km limits.
- A Foam / Water discount.
- "Free" claims other than free pickup-drop on 4+ cylinders. If that is mentioned, say "conditions apply".
- Any phone number other than 77720 78610.

---

## Part B: Prompt for Claude in Chrome

> Copy everything below this line into Claude in Chrome. First log in to Facebook / Meta Business Suite as the owner (aamanamsd123@…).

---

You are helping me (the business owner) create ONE Meta Instant Form (lead form) for my Facebook Page. Work in my logged-in Chrome tab. Do not create, edit, publish or pause any ad, ad set or campaign. Do not change billing or Page settings. Only create this form.

### Where
- **Business portfolio:** "MSD Engineering" (business ID 110109888113215).
- **Page:** "MSD Engineering - The Firewala" (Page ID 110106411446896).
- **Path:** Meta Business Suite → All tools → **Instant forms**, or open https://business.facebook.com/latest/instant_forms?asset_id=110106411446896
- If that path is not available, use: Page → Publishing tools / Forms library → Create form.

### Before creating
1. Check that the Page has accepted the **Lead Ads Terms** (https://www.facebook.com/legal/leadgen/tos). If it has not, stop and tell me. I will accept them myself.
2. Check whether a form named "TFW Year-End Refilling – Dec26" already exists. If yes, stop and tell me.

### Create the form with exactly these settings
- **Form name:** TFW Year-End Refilling – Dec26
- **Form type:** Higher intent
- **Language:** English

**Intro**
- Image: use image from ad (default).
- Headline: `Fire extinguisher refilling from ₹100/kg + GST`
- Description, paragraph style: `Year-End Offer, valid till 31 Jan 2027. ABC, CO2, Foam and Water extinguishers. 24–48 hours turnaround (depends on type). Refilling certificate and next-due-date sticker on every cylinder. ISO 9001:2015 certified, serving Raipur since 2016.`

**Questions**
- Prefill questions: **Full name**, **Phone number**. Remove email if it is added by default.
- Custom questions, all required, in this order:
  1. Short answer: `Company / organisation name`
  2. Multiple choice: `How many extinguishers need refilling?`
     - Options: `1–3`, `4–10`, `11–25`, `More than 25`
  3. Multiple choice: `Which type?`
     - Options: `ABC powder`, `CO2`, `Foam`, `Water`, `Mixed / not sure`
  4. Multiple choice: `Where is your site?`
     - Options: `Raipur city`, `Raipur industrial area (Siltara, Urla, Bhanpuri, Birgaon)`, `Bhilai`, `Durg`, `Other`
  5. Multiple choice: `Your role`
     - Options: `Owner / Director`, `Safety officer`, `Admin / Facility manager`, `Purchase`, `Other`

**Privacy policy**
- Link text: `Privacy Policy`
- URL: `https://www.thefirewala.in/privacy-policy/`
- Before saving, open this URL in a new tab. If it does not load or is not a privacy policy page, stop and tell me.

**Review screen:** keep Meta's default text.

**Completion / ending screen**
- Headline: `Thank you! We have received your request.`
- Description: `Our team will call you within 1 hour (Mon–Sat, 10 am – 7 pm). Outside these hours, we will call you as soon as possible. For a faster quote, WhatsApp us your cylinder quantity and type.`
- Button / call to action: **Call business**, phone `+91 7772078610`.

### Before publishing
- Show me the full preview of every screen (intro, questions, privacy, review, ending), and list any field you could not set exactly.
- Wait for me to type **"publish form"**.
- Remember: a published form cannot be edited, only duplicated. So check all text carefully against this prompt.

### After publishing
1. Tell me the **Form ID** (shown in the forms list or form details).
2. **Optional, only if I reply "download old leads":**
   - In the same Forms / Instant forms list, find the older forms used by "New Leads campaign" (June–July 2026).
   - Download their leads as CSV to my computer.
   - Tell me the file name, the number of rows, and the date range.
   - Do not paste names or phone numbers into the chat.

### Rules
- Never create or publish any ad.
- Never delete or archive any existing form.
- Never change Page, billing or business settings.
- If anything asks for a password, 2FA or verification, stop. I will do it.
