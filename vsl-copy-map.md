# VSL Page — Full Copy Map
## Nexus Outbound Engine
**File:** `vsl.html`  
**Traffic source:** Cold Meta ads → direct to this page  
**Goal:** Watch video → click Apply to Get Started → submit application  
**Note:** "Founding client pricing available" micro copy is intentional. No specific dollar amounts anywhere.

---

## THE OFFER (understand this before building anything)

The Nexus Outbound Engine is a **done-for-you outbound system** with a pay-per-result model:

- Nexus builds and runs dedicated cold email infrastructure for the client's business
- 10,000+ AI-personalized emails per month (researched and written per prospect)
- When a prospect replies with interest, the AI responds in under 10 seconds — simultaneously calling them by phone, sending a personalized email with a booking link, and sending an SMS
- The AI handles booking the call directly onto the client's calendar
- The client's sales team just shows up to warm, confirmed meetings
- **No setup fee. No long-term contract. Month-to-month.**
- Client pays per confirmed call delivered — if no calls, no charge beyond the base retainer
- Specific outcome promise: **10 to 30 confirmed sales calls per month**
- Founding client pricing is available for the first 3 spots (creates legitimate scarcity)

**Who it's for:** B2B companies with a sales function in place and an inconsistent pipeline. They need a closer — Nexus fills the closer's calendar. Not for B2C.

---

## FUNNEL LOGIC

Cold Meta traffic. They don't know Nexus. They clicked an ad about pipeline or getting more sales calls. This page must:

1. **Qualify immediately** — the eyebrow tells them exactly who this is for
2. **Make a specific, outcome-focused promise** — 10–30 confirmed calls, pay per call
3. **Get them to watch the video** — the video handles all objections and does the full sell
4. **Give them one action after the video** — Apply to Get Started, right below the player
5. **Handle remaining doubt below the fold** — for scanners who skip or skim

No nav links. One exit: apply.

---

## PAGE STRUCTURE

```
[NAV — logo + wordmark only, no links]

[HERO]
  Eyebrow
  Headline (H1)
  Subheadline
  Proof pills

[VSL VIDEO]
  CTA button — directly below player
  Micro copy — directly below button

[ARROW NUDGE]

[APPLICATION FORM]
  Form header
  GHL/form embed
  Form footer note

[HOW IT WORKS — condensed, for scanners]

[PROOF CARDS — testimonials]

[FAQ — 5 questions]

[BOTTOM CTA]

[FOOTER]
```

---

## SECTION 1 — NAV

Same sticky blurred nav as main page. **No links, no menu.** Logo + wordmark only.

```
[Nexus Acquisition logo]  NEXUS ACQUISITION
```

---

## SECTION 2 — HERO

**Purpose:** Qualify the visitor (eyebrow), make a bold specific promise (headline), explain the mechanism in one breath (subheadline). Get them to press play.

### Eyebrow
```
For B2B Companies With a Sales Team and an Inconsistent Pipeline
```
*(Gold, small caps, uppercase, centered. Same eyebrow component as main page but longer text — no flanking dashes on this one, just the text. It's an ICP qualifier, not a brand label.)*

### Headline (H1)
```
We Book 10 to 30 Confirmed Sales Calls
onto Your Calendar Every Month.
You Only Pay for the Calls We Deliver.
```
*(Cormorant Garamond, bold, large — clamp 38px to 66px. The words "10 to 30 Confirmed Sales Calls" or the second line "You Only Pay for the Calls We Deliver." could be in italic gold to break up the weight. Suggested: "You Only Pay for the Calls We Deliver." in italic gold.)*

### Subheadline
```
Done-for-you outbound infrastructure. AI-personalized at scale.
Every positive reply gets a call back in under 10 seconds — automatically.
```
*(Figtree, 15–17px, muted text color `var(--text2)`, max-width 520px, centered. Same `.hero-sub` class as main page.)*

### Proof Pills (4 pills, same style as main page)
```
[10K+ emails / month]  [AI books the call]  [Pay per call only]  [Month-to-month]
```
*(These reinforce the mechanism and business model at a glance. They answer "how" and "what's the risk" without any copy.)*

---

## SECTION 3 — VSL VIDEO

**Purpose:** The primary selling mechanism. Everything above gets them to press play. Everything below handles the people who don't finish.

### Above-video label (very small, muted — optional)
```
NEXUS OUTBOUND ENGINE — OVERVIEW
```
*(10px, letter-spaced, `var(--text3)`, centered above the video frame)*

### Video frame
- Same browser-chrome wrapper as main page (traffic light dots + top bar)
- Top bar label: `nexusacquisitionai.com`
- 16:9 aspect ratio
- Gold pulsing play button (glow animation)
- Grid background overlay on placeholder state
- Bottom bar: green live dot + text

### Video bottom bar text
```
[● LIVE]  Watch now — this presentation may be taken down without notice
```

### CTA Button — sits DIRECTLY below the video frame, no gap
```
Apply to Get Started  →
```
*(Full-width gold button, same `.submit-btn` styling as main page. This is the primary CTA. It anchors to `#apply` further down the page. No bridge section between video and button — the button is immediate.)*

### Micro copy — sits directly below the CTA button
```
No setup fee. No long-term contract. Month-to-month.
Founding client pricing available — first 3 spots only.
```
*(Two lines, small, centered, `var(--text3)` for the first line. "first 3 spots only." in `var(--gold)` or `var(--text2)` to create mild visual emphasis on the scarcity element. 12px, same `.form-footer-note` styling.)*

---

## SECTION 4 — ARROW NUDGE

Same animated bouncing arrow as main page. Connects video block to the form.

---

## SECTION 5 — APPLICATION FORM

**ID:** `#apply` — the anchor for all CTA buttons on the page.

### Form card header

**Title:**
```
Apply to Get Started
```

**Sub:**
```
We review every application within 24 hours — no pitch, no pressure
```

*(Same `.form-header` treatment: gold bottom-border bar, Cormorant Garamond title, muted sub.)*

### Form embed
*GHL / Typeform / Calendly embed goes here. Replace the placeholder div.*

### Form footer note (inside the card, below the embed)
```
Founding client pricing available — first 3 spots only.
Price increases after spots are filled.
```
*(Same `.form-footer-note` class as main page. "first 3 spots only." in `var(--gold)`.)*

---

## SECTION 6 — HOW IT WORKS (condensed)

**Purpose:** For scanners and skeptics who skipped the video. This section explains the mechanism so they understand what they're applying for.

### Section divider label
```
How It Works
```

### Section title
```
Cold Prospect to Booked Call.
```

### Section sub
```
Five steps. Zero humans in the loop.
```

### Steps (condensed — shorter body text than main page version)

**Step 01 — Prospect Targeting & List Building**
```
We identify and pull targeted prospects matched to your ideal customer profile. 
Every contact is verified before anything sends — invalid addresses removed 
automatically so your deliverability stays clean from day one.
```

**Step 02 — AI-Written Personalization at Scale**
```
Our system researches every prospect individually and writes a unique 
personalized opening for each email. 10,000+ emails per month — every 
single one reads like it was written specifically for that person.
```

**Step 03 — Private Sending Infrastructure**
```
Emails deploy through dedicated infrastructure built exclusively for your 
business. Business-hours only, time-zone optimized, deliverability monitored daily.
```

**Step 04 — Instant Reply Intelligence**
```
The moment a reply arrives, the system reads and categorizes it in real time. 
Unsubscribes handled in seconds. Only genuine interest triggers what happens next.
```

**Step 05 — AI Books the Call in Under 10 Seconds** *(Badge: The Core Differentiator)*
```
Interest detected → our AI calls the prospect, sends a booking email, and fires 
an SMS — all simultaneously. The call lands on your calendar as a confirmed, 
warm meeting. Your team just shows up.
```

---

## SECTION 7 — PROOF CARDS

### Section divider label
```
Client Results
```

### Section title
```
What Clients Say.
```

*(No section sub — let the quotes speak)*

### Proof Card 1
```
Quote: "Real testimonial — specific result, specific timeframe, specific business type."
Name: [Client Name]
Role: [Title, Company]
```

### Proof Card 2
```
Quote: "Second testimonial — outcome-focused, honest, sounds like a real person."
Name: [Client Name]
Role: [Title, Company]
```

*Replace with real testimonials as they come in. The more specific the number and timeframe, the more credible.*

---

## SECTION 8 — FAQ

**Purpose:** Kill the final objections. Five questions, VSL-page focused. Shorter and more direct than the main page FAQ.

### Section divider label
```
Common Questions
```

### Section title
```
Straight Answers.
```

---

**Q1: How is this different from a cold email agency?**
```
Most agencies use shared infrastructure and have humans reviewing replies 
manually — which means slow follow-up, shared reputation pools, and no real 
accountability for results. We build dedicated infrastructure for your business 
specifically. The bigger difference is what happens when a prospect shows 
interest: our AI is on the phone with them, in their inbox, and in their texts 
within 10 seconds — simultaneously. No human involved at any step. No agency 
does this.
```

**Q2: What kind of businesses is this built for?**
```
B2B companies with a sales function in place and a need for consistent pipeline. 
SaaS, consulting, marketing services, financial services, recruiting, insurance, 
logistics, and professional services all work well. You need someone to close 
the calls — we fill their calendar. This is not configured for consumer businesses.
```

**Q3: How does the AI actually book the call?**
```
The instant our system detects a positive reply, three things happen with zero 
human involvement: our AI calls the prospect directly, sends them a personalized 
email with a booking link, and sends an SMS — all at the same time. Most people 
book within minutes. The call lands on your sales team's calendar as a confirmed, 
warm appointment. Your rep shows up ready to close.
```

**Q4: How long until we're live?**
```
There's a brief warmup period before any real prospects are contacted — 
non-negotiable, and critical for long-term deliverability. During that window 
we build and configure everything. Most clients are sending to real prospects 
within 2–3 weeks of onboarding.
```

**Q5: We already run cold email internally. Why would we need this?**
```
Most internal setups rely on a human catching replies and following up 
hours later — by which point the prospect has mentally moved on. The 
difference here is the response speed. The moment someone raises their hand, 
the system is already moving across three channels simultaneously. That speed 
is what converts interest into booked meetings before intent fades.
```

---

## SECTION 9 — BOTTOM CTA

**Purpose:** Final push for scrollers who didn't apply yet. Direct and confident.

### Headline
```
Your Competitors Are Already
Automating This.
```

### Sub-copy
```
If you have a sales team and need consistent pipeline, apply below. 
We'll confirm fit in 20 minutes.
```

### CTA Button
```
Apply to Get Started  →
```
*(Same gold button, links to `#apply`)*

### Below-button micro copy
```
No setup fee. No long-term contract. Month-to-month.
```
*(Same micro copy as below the VSL, reinforces the low-commitment nature of the offer)*

---

## SECTION 10 — FOOTER

Same as main page:
```
[Nexus Acquisition logo]  NEXUS ACQUISITION

Contact  |  Privacy Policy  |  Terms

© 2026 Nexus Acquisition — nexusacquisitionai.com
```

---

## COPY DECISIONS & RATIONALE

### Why "Apply to Get Started" instead of "Book a Call"?
"Book a call" positions the next step as a sales call. "Apply to Get Started" positions it as the beginning of the engagement — they're applying to work with you, not booking a sales pitch. This creates selectivity and perceived value. It also filters for more committed leads.

### Why the CTA button goes directly under the video, not in a bridge section?
Your micro copy does the bridging work. "No setup fee. No long-term contract. Month-to-month." answers the final hesitation (risk) in two seconds. A full bridge section would slow the momentum. After the video, energy is high — convert it immediately.

### Why proof pills below the headline (not after the sub)?
The eyebrow qualifies WHO this is for. The headline makes the promise. The pills validate the HOW before the sub-copy explains it. They do a lot of work in a tiny footprint and reduce cognitive load before someone reads the full sub.

### Why "Founding client pricing available — first 3 spots only"?
This is legitimate scarcity tied to an onboarding constraint (limited capacity to build systems properly). It creates urgency without manufactured fakeness, and it rewards early movers — which is the audience you actually want. Keep this line exactly as written.

### Why no dollar amounts?
Cold traffic doesn't have enough context to evaluate a price correctly. Show them the number before they understand the value and they'll anchor wrong. Price is discussed on the strategy call after fit is confirmed on both sides.

### Why 5 FAQ questions instead of 7?
Cold Meta traffic has a shorter patience window than someone who found you organically. Five focused questions covering the core objections is the right density. The full 7-question FAQ is appropriate on the main page for due-diligence browsers.

---

## IMPLEMENTATION NOTES FOR CLAUDE CODE

When building `vsl.html`:

1. **Copy all CSS from `mainpage`** exactly — same `:root` tokens, same font imports, same base styles. No new design tokens needed.
2. **Nav:** Same as mainpage nav. Logo image + wordmark. No links.
3. **Hero:** Same `.hero`, `.eyebrow`, `h1`, `.hero-sub`, `.proof-pills` structure. The eyebrow here is longer text — no flanking dashes/lines (remove the `::before` / `::after` pseudo-elements on `.eyebrow` for this page, or use a modified class).
4. **Headline treatment:** "You Only Pay for the Calls We Deliver." should be wrapped in `<em>` for italic gold styling (same as `<em>On Autopilot.</em>` on the main page).
5. **VSL Section:** Copy `.vsl-section` block from mainpage exactly — same browser chrome, top bar, play button, bottom bar. Update bottom bar text to match this doc.
6. **CTA button under video:** Sits outside the `.vsl-section` wrapper, immediately after it. Use the same `.submit-btn` class but make it an `<a href="#apply">` tag. Full width, gold, "Apply to Get Started →" with arrow SVG.
7. **Micro copy under button:** Use `.form-footer-note` class or a simple centered `<p>` with `font-size:12px; color:var(--text3)`. "first 3 spots only." in a `<span>` with `color:var(--gold)`.
8. **Arrow nudge:** Same `.arrow-nudge` section as mainpage.
9. **Form section:** Same `.form-section` block. Update header title to "Apply to Get Started" and sub to match this doc. Update footer note to match this doc.
10. **How It Works:** Same `.hiw-section` structure. Use the condensed step copy from this doc (shorter than mainpage).
11. **Proof cards:** Same `.proof-section` / `.proof-cards` structure. Two cards, placeholder content.
12. **FAQ:** Same `.faq-section` structure with JS accordion. 5 questions from this doc, not 7.
13. **Bottom CTA:** Same `.bottom-cta` structure. Update headline, sub, and button text to match this doc. Add micro copy line below button.
14. **Footer:** Exact copy from mainpage footer.
15. **Page `<title>`:** `Nexus Outbound Engine — 10–30 Confirmed Sales Calls Per Month`
16. **Page `<meta description>`:** `Done-for-you outbound system that books 10–30 confirmed B2B sales calls onto your calendar every month. You only pay for the calls we deliver.`
