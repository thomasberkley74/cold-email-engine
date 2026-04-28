# Nexus Acquisition — Build Progress Log

## Session: Main Page + VSL Copy Map
**Date:** April 28, 2026  
**Branch:** claude/log-main-page-completion-WRcml

---

## COMPLETED: Main Page (`mainpage`)

The main landing page for the Nexus Outbound Engine is fully built and uploaded. This is a single-file static HTML page with all styles inline (required for GHL platform compatibility).

### Design System Locked In

| Token | Value | Use |
|---|---|---|
| `--navy` | `#0d1a30` | Page background |
| `--navy2` | `#12213c` | Card/section backgrounds |
| `--navy3` | `#182849` | Header bars, elevated surfaces |
| `--gold` | `#c9a84c` | Primary brand accent, CTAs |
| `--gold2` | `#e2c472` | Italic headlines, hover states |
| `--text` | `#f5f1e8` | Primary body text |
| `--text2` | `rgba(245,241,232,0.68)` | Secondary text |
| `--text3` | `rgba(245,241,232,0.38)` | Muted / labels |

**Fonts:** Cormorant Garamond 600/700 (serif headers) + Figtree 300/400/500/600 (body)  
**Font source:** Google Fonts CDN

### Main Page Sections (in order)

1. **Nav** — Sticky, blurred backdrop, logo + "NEXUS ACQUISITION" wordmark. No nav links.
2. **Hero** — Eyebrow "Nexus Outbound Engine" → H1 "Your Pipeline. *On Autopilot.*" → sub-copy → 4 proof pills
3. **VSL Section** — Browser-chrome wrapper (traffic-light dots), 16:9 aspect ratio, gold pulsing play button, grid overlay, live green dot. Embed placeholder comment ready for iframe/Wistia/Vimeo.
4. **Arrow Nudge** — Animated bouncing arrow directing to form
5. **Application Form** — Styled form card with header "Apply for a Strategy Call" + embed placeholder for GHL/Typeform/Calendly. Footer note about founding client pricing (to be removed or updated).
6. **Guarantee Strip** — Gold bordered strip: "You only pay for calls we actually book."
7. **How It Works** — 5-step vertical timeline: (01) Prospect Targeting, (02) AI-Written Personalization, (03) Private Infrastructure, (04) Reply Intelligence, (05) AI Books the Call in Under 10 Seconds
8. **Client Results** — 2 proof cards with placeholder testimonials (to be replaced with real ones)
9. **FAQ** — 7 questions with JS accordion. Topics: differentiation, pay-per-call model, how AI books, volume, timeline, internal teams, fit.
10. **Bottom CTA** — "Ready to Fill Your Pipeline?" → Apply Now button (anchors to #apply)
11. **Footer** — Logo, contact email, Privacy Policy, Terms links, copyright

### Hero Copy (exact)
```
NEXUS OUTBOUND ENGINE (eyebrow)

Your Pipeline.
On Autopilot.

We build and run a done-for-you outbound system that finds your ideal 
prospects, sends personalized outreach at scale, and has our AI book 
the calls directly onto your calendar — you only pay per call we deliver.

[10K+ emails / month] [AI books the call] [Pay per call only] [Month-to-month]
```

### Guarantee Strip Copy (exact)
```
You only pay for calls we actually book. If our system doesn't put confirmed 
meetings on your calendar, you don't owe us anything beyond the base retainer. 
Our incentive is completely aligned with yours.
```

### Form Header Copy (exact)
```
Apply for a Strategy Call
We review every application within 24 hours — no pitch, no pressure
```

### How It Works — Step Copy (exact)

**01 — Prospect Targeting & List Building**  
Our system identifies and pulls targeted prospects matched precisely to your ideal customer profile. Every contact is verified before anything sends — invalid and risky addresses are removed automatically so your deliverability stays clean from day one.

**02 — AI-Written Personalization at Scale**  
Our system researches every prospect individually and writes a unique personalized opening for each email — pulled from their company's own web presence. Starting at 10,000 emails per month and scaled to match your pipeline, every single email reads like it was written specifically for that person.

**03 — Private Sending Infrastructure**  
Emails deploy through dedicated private infrastructure built exclusively for your business — not shared pools that hurt deliverability. Sending is throttled intelligently, runs business hours only, and is timed to each recipient's local time zone. Deliverability is monitored daily.

**04 — Instant Reply Intelligence**  
The moment a reply comes in, our system reads and categorizes it in real time. Unsubscribes and negative replies are handled automatically within seconds. Only genuine interest triggers what happens next — no human needs to be watching.

**05 — AI Books the Call — In Under 10 Seconds** *(Badge: The Core Differentiator)*  
The instant interest is detected, our AI reaches out to the prospect by phone, sends a personalized email with a booking link, and fires an SMS — all simultaneously. The prospect books directly onto your calendar. Your sales rep shows up to a warm, confirmed meeting that the system built entirely on its own.

### FAQ Questions (exact)
1. How is this different from a cold email agency?
2. What does "pay per call" actually mean?
3. How does the AI actually book the call?
4. How many emails do you send per month?
5. How long before we're live?
6. We already do cold email internally. Why would we need this?
7. Is this right for my business?

### Other Pages Built
- `calendar.html` — Strategy call booking page with 60-min call details + GHL calendar embed placeholder
- `privacy.html` — Full privacy policy (updated April 25, 2026)
- `terms.html` — Full terms of service (updated April 25, 2026)
- `Nexus-Acquisition-4.png` — Logo file

### Key Technical Decisions
- All styles inline (no external CSS file) — required for GHL compatibility
- Fonts loaded via Google Fonts CDN link tags
- Logo referenced as relative path `Nexus-Acquisition-4.png` (also available as GitHub raw URL fallback)
- FAQ accordion is pure vanilla JS, no dependencies
- Responsive breakpoint at 520px for mobile
- `scroll-behavior: smooth` on html for anchor links

---

## NEXT: VSL Page (`vsl.html`)

Full copy map documented in `vsl-copy-map.md`. The VSL page is built for cold Meta ad traffic. All sections, headlines, sub-copy, and structural notes are mapped out and ready to implement.

**Key differences from main page:**
- Nav has no links (removes distraction for ad traffic)
- Pre-video hook copy above the VSL
- Post-video CTA bridge section between video and form
- No pricing anywhere on the page
- Shorter, punchier proof sections vs. the main page's longer educational content
- Application framing is more exclusivity-based ("we only take on clients where we're confident we can deliver")
