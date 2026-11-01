# Business App Builder — reusable prompt

Copy everything in the box, fill in the 4 blanks at the top (or just say them out loud with voice typing), and paste into a new Claude chat.

---

```
Build a complete, working, branded business app I can pitch to a real company.

COMPANY: [business name]
WEBSITE OR CITY: [website URL, or city + state if they have no site]
INDUSTRY: [e.g. dryer vent cleaning, lawn care, nonprofit, cleaning service]
RELATIONSHIP: [e.g. my brother-in-law's company / my mother and aunt run it]

Do all of this without asking me questions. Make every decision yourself.

1. RESEARCH THE COMPANY
   - Search the web and open their site. Pull their real name, services,
     service area, phone, email, hours, tagline, and who they serve.
   - Read their brand colors from the live site (text, button and background
     colors) and their fonts. Use their actual logo image in the app.
   - If they have no website, check Google Business, Facebook, and state
     business records. If still nothing, design a clean brand that fits the
     industry and tell me you did that.

2. RESEARCH THE INDUSTRY (2026)
   - Find what the leading apps in this industry offer today
     (for trades: Jobber, Housecall Pro, ServiceTitan, GorillaDesk;
     for nonprofits: Bloomerang, Givebutter, DonorPerfect, Volunteer Hub).
   - Build every feature a small company in this industry needs day to day.
     Use the industry's real terms, units and pricing methods.

3. BUILD THE APP
   - One phone-first app that runs on a Samsung Galaxy (Android) in Chrome.
   - Large text, high contrast, big buttons, works with keyboard voice typing.
   - Opens with realistic sample data clearly marked "Sample", plus a button
     to clear it.
   - Everything works: add, edit, delete, save, search, totals, reports.
   - Their logo, colors, phone and service list are built in.
   - Light and dark mode.
   - Check the code runs with no errors and take a phone-size screenshot
     to confirm it looks right before giving it to me.

4. MAKE MY PRICE SHEET IMAGE — WHAT THE COMPANY PAYS ME FOR THE APP
   (this is a business, not a favor)
   - This sheet is MY bill to the company: what they pay Transcenlutions
     LLC each month for the app. It is NOT the company's prices for their
     own customers. Do not put their service prices on it.
   - Title it "Your [App Name] Plan from Transcenlutions LLC" and show
     "Prepared for: [owner name], [company]" at the top.
   - A one-page image in their brand colors I can text or print.
   - 3 monthly plans the company can choose from, each listing exactly what
     they get from me (features, number of users, support hours).
   - A "what your monthly payment covers" table: hosting, database,
     domain/email, texting, AI usage, storage, app store fees, and my
     support labor at $40/hour. Use current real vendor prices (search them).
   - Price every plan so it covers all my costs AND makes at least 25% profit.
     Show my profit per plan, for both monthly and yearly payment.
   - Add my one-time setup fee, a yearly discount, and a free trial.
   - One line showing how my fee pays for itself for this specific business.
   - Only list features the app actually has today. Mark anything not built
     yet as "Coming soon".

5. GIVE ME
   - The app file, the price sheet image, and a 3-sentence pitch I can say
     out loud to the owner.
   - Then tell me the single next step to take, with a clickable link.
   - Back everything up to my GitHub (transcenlutions25) when I say go.
     Every company gets its OWN new repo named after the company. Public
     during the build stage; I'll switch it to private later
     (e.g. dryer-vent-tech-app). Never put it in another company's repo.
     Turn on GitHub Pages so the app has a live link for the owner's phone.
     If you can't create the repo yourself, give me a one-tap link to
     github.com/new with the name already filled in.

Free tools first, then free trials, then paid.
```

---

## Quick-start examples

**Dryer vent company (brother-in-law)**
> COMPANY: [his company name] · WEBSITE OR CITY: [site or city] · INDUSTRY: dryer vent cleaning and inspection · RELATIONSHIP: my brother-in-law's company

Expect: job tickets with before/after airflow readings, vent length and run type, lint-buildup photos, fire-safety inspection report for the customer, annual reminder scheduling, property-manager and multi-unit apartment billing.

**The Beautiful Way (mother and aunt — nonprofit)**
> COMPANY: The Beautiful Way · WEBSITE OR CITY: [site or city] · INDUSTRY: nonprofit organization · RELATIONSHIP: my mother and aunt run it

Expect: donor records and giving history, donation receipts with tax language, volunteer sign-ups and hours, events, grant deadlines, board-ready monthly report. Price sheet note: nonprofits often expect a discount — keep the 25% profit floor and show it as a "nonprofit rate" off a higher list price.

## Tips
- Say "same as PowerBlade" to reuse that app's layout with a new brand.
- If the company has a different owner than you expect, Claude will say what it found so you can confirm before pitching.
