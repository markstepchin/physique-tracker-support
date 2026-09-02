# Deep Research: A High-Converting Landing Page for Recomp

**Phase:** [1 — Deep Research & Strategy](../README.md)
**Deliverable:** Comprehensive reference guide for the Recomp landing page — principles, section-by-section guidance, copy formulas, visual system, mobile rules, CRO plan, and an annotated wireframe.
**Audience for this doc:** You (Mark) plus every downstream prompt in phases 2 and 3. Prompts #2–#8 should be able to draw a specific answer out of this doc without re-deriving the strategy.
**Product context assumed:** [docs/app-context/chatgpt-context.md](../../app-context/chatgpt-context.md). The positioning, persona, and messaging hierarchy in that file are treated as ground truth throughout.

---

## 0. How to Read This Guide

The prompt this doc answers asks for a *reference*, not a first draft of copy. So the structure is:

1. **Principles first, tactics second.** The principles compress what the CRO literature (Wiebe, Gardner, Laja) and the specific reference set (Moody, Hevy, Cal AI, Cluely, Shotbase, StrongLifts) actually converge on. Skim these when you're stuck on a tradeoff.
2. **Section-by-section, in the order the eye scrolls.** Each section has a job, a copy formula, a visual pattern, an anti-pattern, and a Recomp-specific example.
3. **Systems at the end.** Copywriting frameworks, visual hierarchy, mobile, and CRO are treated as cross-cutting systems that apply to every section above.
4. **A wireframe.** Not a mockup — an annotated slot-by-slot outline you can hand to prompt #2 (page generation) and prompt #7 (Claude mockup).

**Two organizing convictions to hold throughout:**

1. **The compare view *is* the product.** Users don't care about logs, streaks, or check-in taxonomy — they care about proof. Every section either drives them toward that proof or gets cut.
2. **There are two versions of this page.** A *pre-release* version (join-the-waitlist CTA, distributed to friends and lifting communities for early feedback) and a *release* version (App Store install CTA). Copy, social proof, and CTA differ meaningfully between the two — the doc calls out those differences at every relevant section. The pre-release version has its own conversion logic based on the *"pre-release access is a privilege, testing an app with no users is an obligation"* reframe (see §1 principle 8 and §4b).

**And two primary user flows** that shape copy throughout, regardless of pre-release vs. release:

- **Flow A — Import (primary, first customers).** The experienced lifter who already has hundreds of photos in their camera roll. The pitch is: *"You already have years of progress. Recomp organizes it."* The aha is instant — pull photos, align them, compare. Zero-wait.
- **Flow B — Track from scratch.** The lifter who doesn't have a photo history yet, or wants to start a fresh chapter (post-injury comeback, new program, first real cut). The pitch is: *"Start now, and every check-in makes the compare view stronger."* The aha builds over 3–6 weeks.

Flow A is the dominant flow for the launch page because the first customers have existing photos. Flow B is addressed as a secondary path (see §6.5). Both flows share the same core aha — compare view — but arrive at it differently.

---

## 1. Executive Summary

Eight things matter more than everything else on this page.

**1. The hero must show the aha, not describe it.** The "then vs. now" side-by-side comparison is the highest-signal artifact Recomp produces. The hero visual should *be* that comparison — a two-photo compare view inside a device frame, with the app chrome visible enough to signal "this is what the app does." Not a stock gym photo, not a hand holding a phone, not a hero illustration. Cluely leads with a live demo shimmer; Moody leads with three product screenshots showing exact placements; Cal AI leads with a scanner screen. Every high-converting consumer app hero in the reference set treats the hero visual as a working demo, not decoration.

**2. Lead with the outcome, not the mechanism.** The prompt says it and the context file says it: users care about seeing results, not about tracking. So the headline is "See the progress you've been working for," not "The best physique tracker." Joanna Wiebe's rule — *"Enter the conversation already happening in your prospect's head"* — puts the lifter's real question ("Am I actually changing?") at the top of the page, then answers it. This is also how you differentiate against generic fitness trackers without ever naming them.

**3. Position against the camera roll, not against competitors.** The competitor is not Hevy or MacroFactor. The competitor is the user's own iPhone camera roll — 800 disorganized physique photos they already own. That is the star of the competitor set. Weight scattered across Apple Notes, spreadsheets, or Apple Health is a *supplemental* fragment of the same problem — worth naming to expand recognition, but never at the cost of dethroning the camera-roll frame. The camera roll is the strongest because it's where the persona's most emotionally-loaded evidence already lives; unlocking value in what they already have is the strongest reason to install now. (See §5 for the convergence diagram that anchors this framing on the page — camera roll dominant, other sources supporting.)

**4. Speak to the science-based lifter, not to everyone.** The persona is the Jeff Nippard / Renaissance Periodization viewer: already motivated, deliberate, evidence-oriented, allergic to fluff. That dictates the tone (precise, understated, no motivational clichés), the vocabulary (recomp, cut, bulk, progressive overload, longitudinal), and the visual identity (Apple-native, high-contrast, scientific, minimal). A page that would work for the broad fitness market will underperform for this user because it will feel generic.

**5. The App Store CTA is the whole conversion funnel.** No email capture. No "learn more." The primary CTA is a real Apple-designed "Download on the App Store" badge, above the fold and repeated at every natural decision point. Every non-CTA button on the page is a distraction — either remove it or demote it visually. Cal AI, Cluely, and Hevy all follow this rule. Moody is the exception because its CTA is a $39 checkout, not an install.

**6. Social proof does more heavy lifting than copy.** For a paid physique app targeting a discerning niche, the highest-leverage social proof isn't a review count — it's a real transformation from a real user (ideally you, the founder, since you have 450 photos and 150 check-ins already). One authentic compare view with a name, a timeline, and a weight delta will outconvert a wall of five-star quotes. Peep Laja's data on this is unambiguous: specific, credible, checkable social proof outperforms generic testimonials by 2–3× on install pages.

**7. Mobile is not a variant of desktop — it's the primary surface.** ~70% of App Store landing page traffic in 2025–2026 is mobile, and for a fitness app the number is closer to 85%. Every design decision below is written mobile-first. Desktop is the responsive extension, not the reverse.

**8. For the pre-release page: reframe the ask. Access is a privilege; testing is an obligation.** A pre-release page with a "join the waitlist" CTA and no social proof is a categorically different persuasion problem from a launched-app page. The naive framing — *"try our new app!"* — inverts the actual value exchange. The visitor is being asked to spend attention and time testing an unproven product; the founder is offering something rare — early access, direct influence on the product, and a personal relationship with the person building it. The pre-release page should make that inversion explicit: **early access is a privilege granted to a small number of lifters; downloading and testing an unproven app is an obligation.** This reframe (see §4b) turns a low-signal "join waitlist" into a high-signal *"apply to be one of the first N."* It also sets up the release page to inherit a stronger social proof base — because your first users won't feel like test subjects; they'll feel like founding members.

Everything that follows is an elaboration of these eight.

---

## 2. Core Landing Page Principles for Consumer Apps in 2026

Before the section-by-section breakdown, six principles that govern the whole page. These are the ones the reference set (Moody, Hevy, Cal AI, Cluely, Shotbase, StrongLifts) actually converge on, and that the CRO literature has stopped disputing.

### 2.1 Message match

The single strongest predictor of conversion, per Laja's work at CXL and Unbounce's landing page benchmarks (2024–2025), is *message match* between the referring context and the hero. If a TikTok says "the app that turns your camera roll into a physique timeline," the hero has to acknowledge that promise in the first two seconds. Recomp has multiple traffic sources (TikTok content, App Store search, direct shares, X posts) and each one plants a slightly different expectation. The hero copy should carry the strongest single promise — *see the progress you've been working for* — with enough flexibility that every traffic source lands somewhere consonant with what got them to click.

### 2.2 One page, one job

The page has one job: drive an App Store install from a motivated visitor. Not: educate about physique tracking, not: capture email, not: sell a Pro tier, not: recruit for a waitlist. Everything on the page is evaluated against "does this move the visitor toward the install?" If not, it's cut. This is Gardner's *Attention Ratio* principle from Unbounce — one page, one goal, one CTA, everything else is friction.

### 2.3 Visual understanding before verbal understanding

Recomp's value is visual (a compare view). The page's job is easier than most because a single well-composed screenshot communicates the whole product in about 400ms. Verbal copy is the reinforcing layer, not the primary one. This is the opposite of a B2B SaaS page where the copy does the heavy lifting; here the copy just gives the user permission to trust what they already understand from the visual.

### 2.4 Above-the-fold is a promise, not a summary

Above-the-fold's job is not to explain the product. It's to make a specific promise strong enough that the user *decides to scroll*. Every reference in the set treats the fold as a persuasion event, not an information event: headline (the outcome), subhead (the mechanism), demo (the proof), CTA (the action). Nothing else.

### 2.5 Progressive disclosure of proof

The strongest social proof — a real, credible, checkable transformation — should appear at the moment of maximum consideration, not the moment of maximum attention. Which means: not in the hero. In the hero, use a *density* signal (star rating, install count, a "featured in" strip) if you have one. Save the deep, story-driven proof for the second or third scroll, where the visitor is already leaning in and just needs permission to act.

### 2.6 Kill motion that doesn't teach

Auto-playing hero videos, animated gradients, parallax scrolling, and hero carousels are the four biggest conversion killers Unbounce identified in their 2024 study. They compete with the CTA for the visitor's attention budget. The only motion that earns its place on this page is motion that *teaches* the product — the compare view sliding, a photo dropping into a timeline, a check-in creating itself. If motion isn't showing the product working, it's noise.

---

## 3. Section-by-Section Breakdown

The page has eight sections. In order:

1. Hero (the promise + the demo + the install)
2. Problem / agitation (the "you see yourself every day" beat)
3. Solution / how it works (the compare view + the 3-step loop)
4. Aha moment (one hero comparison, dominant on the page)
5. Feature strip (the supporting cast — check-ins, timeline, weight, notes)
6. Social proof (density + story)
7. Objection handling (the FAQ)
8. Final CTA (repeat the hero promise, repeat the install)

Sections 4 (aha), 5 (features), and 6 (social proof) can shuffle order based on test results — see §14. Sections 1, 2, 3, 7, 8 hold their positions.

---

## 4. Section 1 — Hero

### The job

The hero has to do four things in about six seconds of visitor attention: make a promise, prove the promise is real, remove the "what is this?" friction, and offer the action. That's it. If a visitor has to think — even for two seconds — the hero has failed.

### The copy formula

**Headline — the outcome, in the visitor's own words:**

> **See the progress you've been working for.**

This is already the messaging hierarchy's Level 1 line from the context doc, and it's right. It works because:

- It names the outcome (see progress), not the mechanism (track photos).
- It respects the audience — "working for" acknowledges the effort they've already put in.
- It's differentiated. No generic fitness tracker leads with this because most of them are selling to unmotivated users who need to be convinced *to* work. Recomp is selling to users who have already worked.
- It's diagnostic. Someone who reads that line and doesn't feel it *isn't the target user*. That's a feature, not a bug.

**Subhead — the mechanism, one sentence, no adjectives:**

> **Turn your progress photos into a side-by-side timeline. See changes you'd miss day to day.**

The subhead's job is to answer the immediate follow-up question: "OK, how?" One sentence. No adjective inflation ("beautiful," "powerful," "revolutionary" all get cut). Two clauses: what it does, what you get.

**Micro-copy under the CTA — proof, one line, checkable:**

> Free to start. Made for lifters who take physique seriously.

Or, once you have real numbers:

> Free to start · 4.8 on the App Store · Built by a lifter

Cal AI's "Loved by 5M users · ⭐ 4.9" is the pattern. Moody's "One-time payment. Trusted by 3,000+ professionals" is the pattern. Density signal + one credibility marker + one persona marker. If you don't have credible numbers yet, lean on the persona marker alone — "Made by a lifter, for lifters" is more honest and more persuasive than fabricated review counts.

**Primary CTA — the Apple badge, not a custom button:**

Use the real Apple-designed "Download on the App Store" badge (SVG, from the Apple marketing resources). Reasons:

- Recognition — visitors know exactly what happens when they tap it. Zero cognitive load.
- Trust — an Apple-branded badge inherits Apple's trust. A custom button doesn't.
- Store compliance — Apple's brand guidelines require the badge for App Store links, and Recomp will eventually want to appear in App Store Search Ads, which the badge signals correctly.

Place the badge *inline with the copy* on desktop (right of or below the headline block), and *centered under the copy* on mobile. On mobile, the CTA should be inside the viewport of an iPhone 12 or newer without any scrolling. Test that explicitly — see §13.

### The hero visual

This is the single most important image on the page. Here's what it should be, and what it should not be.

**Should be:** A device frame (iPhone) showing the actual compare view — two photos of the same person, taken 8–12 weeks apart, side by side, with dates and (optionally) weight overlaid the way the app renders them. The compare view is the product; the hero should *be* the product. If you can animate it subtly (the second photo fading in, a slider revealing the second photo, a subtle scale on hover), do that — but only if it teaches the compare interaction. Static is fine. Motion that doesn't teach is noise (§2.6).

**Should not be:**
- A photo of a person at the gym.
- A hand holding a phone with the app on it (stock photography default — kills specificity).
- A hero illustration or 3D render.
- A carousel of screenshots.
- An auto-playing brand video.
- A pile of app screenshots at an angle. (This is the "Cluely on desktops" shimmer pattern — it looks premium but hides what the product does.)

**Recomp specifics:** Since you have 450 personal photos and 150 check-ins, use *your own* compare view. This has two benefits: it's authentically credible (see §7.4 on founder proof), and it prevents the page from ever looking like stock photography. The compare should be visually meaningful — a real, honest transformation over a real period, with clear pose and lighting consistency. If your personal compare isn't strong enough to be the hero, that's an important product signal.

**Design details for the hero device:**
- Frame the phone straight-on, not angled. Angled device shots are the stock photography of 2019 and read as generic.
- Use the current-generation iPhone frame (Dynamic Island, thin bezels). Outdated frames signal an outdated product.
- Show a small amount of app chrome — the section header, maybe the dates on each photo — so the visitor understands they're looking at *the app*, not just two photos.
- On dark backgrounds, the phone has a slight ambient glow. Don't use a drop shadow; use light.

### The hero layout

Two proven patterns:

**Pattern A — Split (recommended for desktop):**
Copy stack on the left (headline, subhead, CTA, micro-copy). Device frame on the right, offset slightly down so it visually anchors the section. This is the Hevy / Cal AI / most-consumer-apps pattern.

**Pattern B — Stacked with dominant demo (recommended for mobile always, desktop maybe):**
Copy stack at top, centered. Compare view dominant below. This is what Moody does with its three-screenshot pattern. It's more premium-feeling and lets the demo do more of the talking.

For Recomp, start with Pattern B. Reasons: the compare view is unusually visually strong, so it should get the dominant real estate. Also, the mobile version will effectively be Pattern B regardless, so a stacked desktop keeps the visual identity consistent across breakpoints.

### Anti-patterns to avoid

- **Two CTAs above the fold.** "Download" plus "Watch demo" plus "Learn more" is Gardner's Attention Ratio disaster. One primary CTA. If you have a secondary action (a video), make it visually secondary — a small play indicator on the demo, not a button.
- **Trying to explain the whole product in the subhead.** The subhead is one sentence. If you find yourself writing three, you're compensating for a weak visual.
- **The word "app" in the headline.** They know it's an app; they downloaded a browser to get to your landing page. "The physique tracking app that..." wastes the most valuable eight words on the page. Cluely says "#1 Undetectable AI for Meetings" — outcome and category. Cal AI says "Track your calories with just a picture" — outcome and mechanism. Neither wastes headline real estate on the noun "app."
- **A tagline that isn't a promise.** "Your physique. Your progress." is a tagline. "See the progress you've been working for" is a promise. Ship the promise.

### Example hero copy — release version (three variants for A/B testing later — see §14.4)

Given that Flow A (import) is the first-customer flow, **V2 becomes the recommended default for release** — the camera-roll framing has the tightest match to the first-customer situation.

**V2 — Camera-roll-first (RECOMMENDED default for release):**
> **You already have years of progress in your camera roll.**
> Recomp pulls your physique photos, aligns them, and lets you compare any two — side by side, dated, honest.
> [Download on the App Store]
> *Free to start · Import your existing photos in seconds*

**V1 — Outcome-first (secondary; strong for TikTok / cold traffic):**
> **See the progress you've been working for.**
> Turn your progress photos into a side-by-side timeline. See changes you'd miss day to day.
> [Download on the App Store]
> *Free to start · Made by a lifter for lifters*

**V3 — Question-first (Wiebe's "already having the conversation" pattern):**
> **Am I actually changing?**
> Recomp compares your physique photos side-by-side so you can stop guessing and see it.
> [Download on the App Store]
> *Free to start · Built for science-based lifters*

Ship V2 first (matches the first-customer flow). Test V1 second (more universal, better for cold traffic where the visitor hasn't self-identified as an experienced lifter). V3 is a distant third — questions in headlines are a pattern that works when the question is exactly the one in the user's head, but they can read as clickbait if the persona doesn't recognize themselves in it.

---

## 4b. Section 1 — Hero (Pre-Release / Waitlist Version)

The pre-release version of the page has a fundamentally different job. Almost everything else in this document still applies (structure, visual system, tone, mobile rules), but the hero and CTA logic change materially.

### The reframe

Naive framing: *"Sign up for early access to our new physique tracker."* → Low-signal, low-conversion. Waitlist as a marketing gimmick.

Better framing: *"Early access is a privilege — we're letting a small number of lifters into the private beta because your feedback will shape the product before broader release. Downloading and testing an unproven app is real work, not a favor."*

This is the psychological equivalent of a good invite-only club: value asymmetry inverted. What you're offering is not "get the product early." What you're offering is *"help us build the product, and get in before everyone else as a thank-you."*

Three concrete consequences for the hero:

1. **The CTA is application, not signup.** "Request access" or "Apply for early access," not "Join waitlist."
2. **Scarcity is real, not manufactured.** State the cohort size honestly. "First 100 lifters" is better than a vague "join the waitlist." "Currently accepting requests, 42 spots left in the first cohort" is best.
3. **The persona bar is stated.** "For serious lifters" or "For lifters who take physique seriously" filters — and the filter makes acceptance feel earned.

### The pre-release hero copy formula

**Headline — the invitation, not the promise:**

> **Recomp is in early access. Get in before the crowd.**

Or, leaning into the founder-driven feedback loop:

> **We're building the physique tracker serious lifters actually want. Come help us finish it.**

Or, the strongest and most reframe-explicit:

> **Early access is invite-only. Testing an unproven app is real work — the first 100 lifters get in.**

**Subhead — the value exchange, one sentence, no adjectives:**

> Get the app 4–8 weeks before public release. Give us direct feedback. Shape what ships.

**Micro-copy under the CTA — the specificity of scarcity:**

> Currently accepting requests · [N] spots left in the first cohort · Reviewed within 48 hours

The "reviewed within 48 hours" line is important — it signals that this is a real application, not an auto-approved list. It also creates a small window of anticipation that increases perceived value.

**Primary CTA — application-style, not signup-style:**

Recommended labels (in order of strength for the reframe):

- **"Request early access"** (safest default)
- **"Apply for the beta"** (strongest reframe; slightly higher friction)
- **"Get on the invite list"** (softer, closer to a signup — use if the application language feels too heavy)

The CTA opens either a short form (2–4 questions max — see below) or a Typeform / Tally. Keep it short but *make it real*. The form itself is a filter *and* it's your first VoC (Voice of Customer) data source.

### The pre-release micro-form

A well-designed request-access form does three things: filters for the persona, collects first-round Voice of Customer data, and creates a tiny commitment moment that makes acceptance feel earned. Suggested fields:

1. **Email** (required).
2. **How long have you been lifting?** (radio: <1yr / 1–3yrs / 3–7yrs / 7+yrs) — filters and segments.
3. **How many progress photos do you already have?** (radio: 0 / 1–50 / 50–500 / 500+) — separates Flow A vs. Flow B users at intake, and lets you route the strongest matches (500+ photos) to the top of the list.
4. **What's the one thing about tracking your physique you wish worked better?** (short text, optional) — first VoC data, and a small commitment that filters casual sign-ups.

That's the whole form. Any longer and conversion tanks; any shorter and the reframe collapses back into "waitlist."

### The pre-release hero visual

Same rules as the release hero — the compare view is the visual — but with two adjustments:

1. **Add a subtle "in early access" badge in the corner of the device frame** (small, muted, not visually competing). Signals *"this is a real product, in a real state, mid-development"* — which is the whole positioning.
2. **The compare view can and probably should be the founder's own** (yours, Mark). At pre-release, before you have any user compares, the founder's transformation is the *only* credible visual proof point. Once real users are in the beta, add their compares to the release version.

### Pre-release hero copy examples

**Pre-V1 — Reframe-explicit (RECOMMENDED for pre-release):**
> **Early access is invite-only. Testing an unproven app is real work — the first 100 lifters get in.**
> Recomp is a physique tracker built around the compare view. We're 4–8 weeks from public release. Get in early, help shape what ships.
> [Request early access]
> *Currently accepting requests · 78 spots left · Reviewed within 48 hours*

**Pre-V2 — Invitation-tone (softer, still credible):**
> **We're building the physique tracker serious lifters actually want.**
> Turn the photos you already have into a timeline you can actually see. Get in during early access, before public launch.
> [Request early access]
> *Free during beta · Reviewed within 48 hours*

**Pre-V3 — Founder-driven (leans hardest on the personal angle):**
> **I've taken 450 progress photos over two years. I built the tracker I wished existed.**
> Recomp is in private beta. If you take physique seriously and want to help shape it before public release, request access below.
> — Mark, founder
> [Request early access]

Ship Pre-V1 first. It leans hardest on the privilege/obligation reframe, which is the strongest positioning move available at pre-release. Pre-V2 is the fallback if Pre-V1 tests as too aggressive. Pre-V3 is the strongest for the specific segment of visitors who arrive via founder-led TikTok content — the person watching *your* transformation is more inclined to trust *your* product.

### Pre-release anti-patterns

- **"Join our waitlist" or "Get notified when we launch."** These are the default startup-marketing framings that erase the reframe. Ban both.
- **Fake scarcity.** "Only 3 spots left!" that never decrements is a persona-killer. If you claim 100 spots, actually cap at 100.
- **Post-hoc social proof.** "5,000 lifters on the waitlist" (when you actually have 47) will be smelled instantly by the persona. Density signals for pre-release should be *honest and small* — even single-digit numbers ("Cohort 1 is now testing. Cohort 2 opens next month.") beat fabricated big ones.
- **A "we'll email you when we launch" CTA with no reframe.** This defeats the entire pre-release strategy. If you're not actively selecting cohorts, don't run a pre-release page — just wait and ship the release version.
- **Referral incentives on pre-release.** ("Get 5 friends to sign up and skip the line.") Cheapens the reframe. Skip for Recomp — the persona will read it as growth-hacky and lose respect for the product.

### Transitioning from pre-release to release

When the app is ready for public release, the pre-release version rolls into the release version:

1. **The waitlist is honored first.** Every waitlist-approved user gets a personal email with the App Store link before public launch. This is the strongest possible activation moment — they've been anticipating this for weeks.
2. **The founding-cohort language becomes social proof.** *"Built with the first 100 lifters. Now open to everyone."* — this is a stronger credibility signal than any early rating.
3. **The pre-release page redirects to the release page.** Set up a 301, or replace the content in place.
4. **The best VoC quotes from the beta users become testimonials.** With permission.

This is why the pre-release strategy is worth the effort even for a small waitlist: it seeds the release page's social proof and gives the launch a real narrative arc ("we built this with 100 real lifters, now it's ready for you").

---

## 5. Section 2 — Problem / Agitation

### The job

Establish that the visitor has a specific problem, that Recomp knows it precisely, and that the problem is worth solving. This section builds the emotional case; the next section (solution) closes it.

For the science-based lifter, agitation has to be handled carefully. This user *doesn't need to be sold on lifting* and will pattern-match aggressive gym-bro agitation ("Sick of not seeing gains?") as low-quality marketing. The tone is: *"You already know this. We know you know. Here's the specific version of the problem we solve."*

### The copy formula

Four-beat structure. The extra beat vs. the classic three-beat PAS is the *scattered-data* beat — the persona has evidence of their progress spread across several apps, not just their camera roll, and naming that specifically is what earns the "they get it" recognition.

**Beat 1 — Name the phenomenon.**
The lifter's actual problem is not lack of progress; it's inability to *perceive* progress. Name that.

> **You see yourself every day. So the person in the mirror never seems to change.**

**Beat 2 — Show the specific evidence, camera-roll first.**
Lead with the camera roll — it's the emotionally strongest evidence and the star of the competitor set. The Notes / Excel / Apple Health fragment is a *supporting sentence*, not a co-equal beat. It expands recognition without dethroning the primary frame.

> Your progress photos are buried in your camera roll — hundreds of them, mixed in with screenshots, receipts, and last year's Halloween. Your weight and notes are somewhere else again — a Notes doc, an old spreadsheet, Apple Health. You've done the work. You just can't see it laid out.

Why camera-roll-primary matters:

1. **The camera roll is the highest-signal recognition trigger.** Every physique-serious lifter has some version of this camera roll. The line lands instantly. Weight-scattered-in-Notes is real but secondary — it lands for a subset, and it lands *after* the camera-roll beat has already earned the recognition.

2. **The camera roll is Recomp's primary competitor.** Recomp's install-now argument is *"you already have the raw material in your camera roll — Recomp unlocks it."* Making the scattered-notes problem co-equal would dilute that install-now argument. Keep the camera roll starring; let the notes/health fragment do supporting work.

3. **The supplemental sentence still plants the convergence thesis** — enough to earn the multi-source convergence diagram in the visual, and enough to justify the direction toward Apple HealthKit later — without over-promising features that don't yet exist.

**Beat 3 — Raise the stakes without moralizing.**
The stakes here are motivation and continuity, not shame. Never guilt-trip a lifter about not tracking.

> When the change isn't obvious, the doubt creeps in — *"is the diet working? am I actually gaining muscle? was the deload worth it?"* — and doubt is the thing that ends cuts, bulks, and programs early.

**Beat 4 (optional) — Name the resolution one line before showing it.**
This is a soft handoff into the solution section. Optional; ship if the section feels like it ends abruptly.

> **Recomp brings your photos, your weight, and your check-ins into one place — so the compare view actually tells the story.**

### Visual pattern

Three viable options. Option C is the strongest and the recommended default for launch.

**Option A — A single strong stat, centered, oversized:**

> **You've probably taken 800 progress photos.**
> **You've probably looked back at three.**

Then a short paragraph below.

**Option B — A "before Recomp" mockup of a chaotic iPhone camera roll:**
A screenshot-style mockup showing a real-looking Photos app grid — a physique photo, a receipt, a screenshot, a physique photo, a meme, a physique photo. Caption below: *"Your progress is in there somewhere."* Visual joke; lands because every lifter has this exact camera roll.

**Option C — The convergence diagram, camera-roll dominant (RECOMMENDED).**
A dominant camera-roll mockup on the left, two smaller supporting sources below it (Notes/Excel and Apple Health), an arrow pointing right, and the Recomp compare view on the right. The visual hierarchy encodes the framing: camera roll is the star competitor; the other sources are supporting fragments of the same problem.

```
+-----------------------------+
|                             |
|     CAMERA ROLL             |--+
|     (dominant - photo grid  |  |
|      with mixed physique +  |  |
|      junk photos, ~50% of   |  |
|      the diagram's left-    |  |
|      side visual weight)    |  |
|                             |  |    +----------------------+
+-----------------------------+  |    |                      |
                                 |    |   RECOMP             |
+---------------+ +-------------+|--> |   [compare view]     |
| Notes / Excel | | Apple Health||    |   - photos           |
| (small,       | | (small,     ||    |   - weight           |
|  supporting)  | |  supporting)||    |   - Apple Health*    |
+---------------+ +-------------+|    |                      |
                                 |    |   One place.         |
                                 |    |   One view.          |
                                 |    +----------------------+
                                 |
                                      [* HealthKit sync: in progress]
                                      [caption sits below the diagram]
```

Design notes for Option C:

- **Visual hierarchy encodes the framing.** The camera-roll mockup dominates the left column — bigger, higher, positioned first. Notes/Excel and Apple Health sit *below* it as smaller supporting cards. A visitor who only takes in the diagram at a glance should walk away thinking "camera roll → Recomp," with the other sources registering as "and everything else too."
- **The left-side mockups should feel authentically scattered** — different visual styles for each (iOS Photos grid, iOS Notes app cream background, Apple Health chart), not stylized as a unified design system. The diversity is the visual argument that these are different apps.
- **The Recomp panel on the right is polished, unified, and dominant** — 40–45% of the composition's width. Visually calmer than the sources on the left. Order matters: chaos on the left, calm on the right, arrow between.
- **Include the Apple Health source even though HealthKit integration is future.** It plants the direction without a "coming soon" feature block. Consider marking the Apple Health line inside the Recomp panel with a small asterisk or subtle "in progress" indicator — honest, and it lets the visitor infer both what Recomp does today and where it's going.
- **The arrow is subtle, not a stock icon.** A thin line ending in a small chevron; or a very restrained animated dot flowing left-to-right if you're willing to use motion.
- **Caption below the diagram:**
  > *Your camera roll has the evidence. Recomp lays it out — with your weight and notes alongside.*

  (The caption reinforces the framing: camera roll named first and load-bearing; weight and notes named as accompanying, not co-equal.)
- **On mobile,** the camera roll mockup stacks on top full-width, then Notes/Excel and Apple Health as a smaller two-up row below it, then the arrow pointing down, then the Recomp panel. Preserve the "camera roll dominant" hierarchy vertically. Do not compress the whole diagram into a tiny horizontal — it becomes unreadable.
- **The apps in the source stack should be honest to what the persona uses.** iOS Photos, Apple Notes, and Apple Health are safe defaults for the iOS-native persona. If a large enough segment uses Excel/Sheets for weight, swap Notes for a spreadsheet mockup.

**Why C beats A and B:**

- **A** delivers one strong beat but doesn't set up the multi-source thesis. Good for a shorter or more headline-driven page.
- **B** is charming but narrower — camera-roll-only. C keeps the camera-roll as the star while pulling in the supporting sources.
- **C** lands the camera-roll frame *and* previews the resolution — visitors don't need to read the whole page to intuit what Recomp does; the diagram tells them in one glance. That preview effect is the strongest thing a problem-section visual can do.

**Honesty guardrail for C:** Recomp today handles photos + weight + notes (the app already lets users optionally log weight and notes on each check-in). Apple Health integration is future. So the diagram is honest about what Recomp *does* (unlocks the camera roll, with weight and notes alongside) and directionally honest about where it's going (Apple Health flows in eventually — mark with an asterisk or "in progress" tag inside the Recomp panel to keep it honest). Do not add HealthKit as a "coming soon" feature block anywhere else on the page — the diagram is where the direction is stated, and that's enough.

### Anti-patterns

- **Motivational quote as agitation.** "Consistency is the difference between good and great" is generic-fitness-app poison. Skip.
- **Fear-based framing.** "Are you wasting years of gym time?" is manipulative and the persona will bounce.
- **A stock photo of a discouraged person looking in a mirror.** Same reason. Persona reads this as low-effort marketing.
- **Over-quantification.** "The average lifter loses 40% of motivation in month 3" is invented data. Don't fabricate stats. If you have real numbers from your own tracking history (150 check-ins is a lot of data), use those; otherwise, use qualitative language.

### Recomp-specific example (final draft)

> **You see yourself every day. So the person in the mirror never seems to change.**
>
> Your progress photos are buried in your camera roll — hundreds of them, mixed in with screenshots, receipts, and last year's Halloween. Your weight and notes are somewhere else again — a Notes doc, an old spreadsheet, Apple Health. You've done the work. You just can't see it laid out.
>
> That's the moment the doubt starts. *Is the diet working? Am I actually gaining muscle? Was the deload worth it?* And doubt is what ends cuts, bulks, and programs early — not lack of discipline.
>
> **Recomp starts with the photos you already have. Weight and notes come along for the ride.**

Word count: ~105 words. The final handoff line preserves the camera-roll-primary framing while acknowledging the supporting sources — matches the visual hierarchy in the diagram above.

---

## 6. Section 3 — Solution / How It Works

### The job

Turn the doubt from the previous section into confidence by showing the product's loop in the fewest possible steps. This is where Moody's "Ready in under a minute" three-step section is the model.

The persona rule for this section: *the science-based lifter doesn't want to be taught; they want to be confirmed.* Show them the loop is short, obvious, and doesn't ask them to change their behavior. They already take photos; you just organize them.

### The copy formula

**Section headline — the promise of simplicity:**
> **Three steps. That's the whole loop.**

Or, if you want to lean into the "you already do this" angle:
> **You already take the photos. Recomp does the rest.**

**Three steps, numbered, each with a title and one line:**

1. **Take a weekly check-in.**
Same pose, same light, same time of day. Recomp reminds you.

2. **Recomp builds your timeline.**
Every check-in slots in by date, next to the last one, next to the one from three months ago.

3. **Compare, side by side.**
Pick any two check-ins. See the actual difference — the one your day-to-day view hides.

**One-sentence closer, right below the three steps:**
> That's it. No streaks. No workouts to log. No macros to enter. Just the photos, the timeline, and the comparison.

The closer earns the differentiation. It names three things Recomp *doesn't* do (streaks, workouts, macros) and by naming them, positions against the entire generic-fitness-tracker category without ever attacking a specific competitor. This is a Peep Laja tactic — *say what you're not, so what you are becomes sharper.*

### Visual pattern

The strongest pattern for this section is what Moody uses: a horizontal three-column layout on desktop (each column: numbered step, small screenshot, one-line description), collapsing to a vertical scroll on mobile.

The three screenshots should be:
1. The check-in creation flow (photo captured, weight entered, save button).
2. The timeline view showing 6–12 check-ins in a vertical scroll.
3. The compare view (the aha shot — same one from the hero, or a different real transformation to avoid repetition).

Design detail: make step 3's screenshot visually dominant. Bigger, or with a subtle highlight, or the only one in color while 1 and 2 are muted. The compare view is the destination; the steps are the road. Let the destination look like the destination.

### Anti-patterns

- **More than three steps.** Every extra step reads as friction. Even if the real onboarding is four screens, describe it as three.
- **Steps that describe the app instead of the user's action.** "Recomp uses AI to organize your photos" is app-focused. "Recomp builds your timeline" is user-focused (you take photos, it does the work).
- **Skipping the closer.** The "no streaks, no workouts, no macros" line is the reason the science-based lifter will pattern-match this as *not another generic fitness app*. Do not cut it.
- **Marketing the historical import here.** Historical import is a strong feature, but if you introduce it in the "how it works" section it complicates the loop. Save it for the feature strip (§8) where it's a *bonus* rather than a *step*.

### Optional fourth beat — the honest bit

You could add a fourth beat *below* the three steps that names the honest tradeoff of the product:

> **Note:** Visible change usually takes 3–6 weeks. The first few check-ins will look the same. That's normal. The compare view gets more powerful every week you use it.

This is a *credibility play* — Peep Laja's data on this is that acknowledging a known tradeoff *before* the visitor thinks of it increases trust more than any positive claim. It also filters for the right user: the person who bounces at "3–6 weeks" wasn't going to become a long-term user anyway. The persona (science-based lifter) will read this as respect for their intelligence.

Test it as a variant (§14).

### 6.5 The two-flow split

Recomp has two real user flows, and the "how it works" section is where a visitor self-identifies with one of them. Handling both explicitly (rather than pretending one is universal) makes the section stronger.

**Flow A — Import (the first-customer flow):**
The experienced lifter has years of photos. Their "how it works" is:
1. Import your camera roll.
2. Recomp finds and aligns the physique photos.
3. Compare any two — instant aha.

The value delivery is *immediate*. The aha happens the first time they use the app. This is the strongest possible activation moment and should be the *default* how-it-works path on the launch page.

**Flow B — Track from scratch:**
The lifter without a photo history. Their "how it works" is:
1. Take a weekly check-in.
2. Recomp builds the timeline.
3. Compare — the aha compounds over 3–6 weeks.

Value delivery is *deferred*. Requires more trust up front.

### Handling the two flows on the page

Three viable patterns, in order of recommendation:

**Pattern 1 — Split card (RECOMMENDED).**
Immediately after the standard three-step "how it works" section, drop a small two-card split:

> **Two ways to start:**
>
> | I've been taking photos | I'm starting fresh |
> | --- | --- |
> | Import your camera roll. Recomp finds the physique photos, aligns them, and shows you the compare — in minutes. | Take your first check-in tonight. Recomp builds the timeline from your first photo forward. Compares get powerful in 3–6 weeks. |

Both cards can link into the same App Store CTA. The value is *recognition* — every visitor sees the card that matches their situation and thinks *"they know I exist."*

**Pattern 2 — Sequenced beats.**
Write the "how it works" section as one three-step flow, then follow it with two short paragraphs:

> **If you already have photos:** Import them and compare in minutes.
> **If you're starting fresh:** Take your first check-in and let the timeline build.

Less visual but tighter. Good for a very short page.

**Pattern 3 — Toggle.**
A tab-style toggle at the top of the "how it works" section: [I have photos] [I'm starting fresh]. Toggling reveals a different three-step flow.

*Do not use Pattern 3.* Interactive toggles hide half the value from every visitor, add complexity, and reduce scannability. Pattern 1 (split card) is stronger on every dimension.

### Copy implication

The dominant hero variant (V2, camera-roll-first) matches Flow A. The split card in §6.5 catches Flow B visitors and gives them their own path forward without derailing the main pitch. That's the whole two-flow strategy — lead with A, catch B in the middle.

---

## 7. Section 4 — Social Proof

Because this section does a lot of work for a paid app targeting a discerning niche, it gets its own extended treatment. Read §7.1–7.4 in order — each layer stacks on the previous.

### 7.1 The two kinds of social proof, used in the right places

**Density signals** (star rating, install count, "featured in" logos, review counts). These belong *in the hero micro-copy* and *near the final CTA*. They're low-resolution but ambient — they set the base level of trust for the page.

**Story proof** (a real transformation, a named user, a compare view, a specific timeline). This belongs in the middle of the page, at the moment of maximum consideration. It's high-resolution and does the heavy persuasion work.

The mistake most consumer app pages make is to use only one kind. Cal AI stacks density signals well (5M users, 4.9 rating, 100k reviews) but its testimonials are undifferentiated ("Best calorie tracker ever!"). Hevy has strong density (4.9, 590k ratings) but its testimonial section is a grid of six screenshotted App Store reviews that all say roughly the same thing. Both leave persuasion on the table.

The pattern that outperforms both: *one dominant story proof* + *ambient density signals*. One is enough. One is more than enough. What the story needs is *credibility*.

### 7.2 The single strongest social proof Recomp has

You have 450 personal photos and 150 check-ins. That is an unusually deep, longitudinal, first-party data set. The single strongest piece of social proof you can put on this page is *your own transformation compare view*, dated and honest, with a caption like:

> **150 check-ins. Two years of lifting. Here's what the compare view shows.**
> — Mark, founder of Recomp
> [Compare view: 2023 → 2025, with real weight delta and honest notes]

Why this works:
- **Credibility.** It's real, it's checkable (the founder is a real person with a real X/TikTok presence), and it's specific. Peep Laja's rule: *"The more specific a claim, the more believable it becomes."*
- **Differentiation.** No competitor has this. It's a moat.
- **Category education.** The founder-transformation shows what the product does *and* what the product is for, in a single image.
- **Persona resonance.** The science-based lifter respects founders who ship products in categories they personally practice. You have skin in the game and the photos to prove it.

This becomes the aha section (§4 in the section order) and the emotional peak of the page.

### 7.3 Building out story proof over time

Once Recomp has 50–100 real users, the single-founder proof expands into a small gallery — 3–5 compare views from real users, each with:
- Name (first name + last initial, or handle).
- Timeline (start → end date).
- Weight or context (cutting from 200→180, or bulking from 150→165, or maintaining through a program change).
- One-sentence quote — *not* about the app, but about the moment of realization. ("I didn't believe the diet was working until I hit compare.")

The quote about the moment beats the quote about the app every time. Wiebe's "Voice of Customer" work is unambiguous: the strongest testimonials are *emotional* and *specific to a moment*, not evaluative ("It's a great app").

**How to source these:** Reach out to your first 10–20 users personally. Ask if they'd be willing to share a compare view (they own the copyright to their photos; you get consent). Offer a lifetime free tier in exchange if that helps. This is high-friction to collect but the highest-leverage marketing asset on the page.

### 7.4 The density-signal micro-copy hierarchy

Assuming Recomp is early and doesn't have massive install numbers, the density signals in the hero should escalate as evidence accumulates. Rough order:

1. **Pre-launch / launch week:** *"Free to start · Made by a lifter for lifters"* (persona marker only)
2. **Post-launch, first ratings:** *"Free to start · 4.8 on the App Store"* (rating only, once you have 20+ ratings)
3. **Growth phase:** *"Free to start · 4.8 on the App Store · 5,000 lifters tracking"* (rating + install count)
4. **Post-first-milestone:** *"Featured on Product Hunt · 4.8 on the App Store · 10,000 lifters tracking"* (add press or milestone logos)

Never fabricate. Never round up. Never use "loved by thousands" if you don't have thousands. The persona will smell it, and one whiff of embellishment tanks the whole page's credibility.

### 7.5 Press / creator logos

The Moody / Hevy / Cal AI pattern is a horizontal "Featured in" or "As seen on" strip near the top of the page — a small logo bar with 4–8 recognizable names.

For Recomp, this is a *later addition*. Don't fabricate it. But once you have any of:
- A mention in a Jeff Nippard / RP / Menno Henselmans video or newsletter
- Coverage in a lifting-focused publication (Men's Health, T-Nation, Barbend, etc.)
- A Product Hunt launch
- A creator post from a real lifter with meaningful following

... those logos go into a strip near the top of the page. The bar for inclusion is *"the persona will recognize this."* Generic press coverage doesn't count; persona-relevant coverage does.

### Anti-patterns

- **Fake or generic testimonials.** "This app changed my life!" — the persona will bounce.
- **Star ratings without a source.** A row of stars alone means nothing. "5 stars on the App Store" is the minimum.
- **Testimonials from non-lifters.** A quote from someone who isn't the persona is negative signal — it suggests the product isn't really for them.
- **Buying reviews.** Obvious ethically, but also strategically: App Store review authenticity is a signal the persona reads.

---

## 8. Section 5 — Feature / Benefit

### The job

Give the visitor enough sense of what Recomp *does* (beyond the compare view) to feel confident this is a real, considered product — without turning the page into a feature dump.

This is the section most consumer landing pages get wrong. They either dump every feature into a grid (undifferentiated, boring, gives the visitor nothing to remember) or they hide features to keep the page short (creates uncertainty about whether the product is real). The middle path: *four to six features max, each written as a benefit, each with a small visual.*

### The copy formula

**Section headline — the "everything else it does" opener:**
> **Everything else your physique tracker should be.**

Or:
> **Built the way lifters actually track.**

**Feature blocks — the "benefit + mechanism + visual" pattern:**

Each block has three parts:
1. **Benefit headline (3–6 words, verb-led).** *"Compare any two check-ins."*
2. **Mechanism line (10–15 words).** *"Pick a photo from last week and one from any point in your history. Side by side, same scale, same pose."*
3. **Small screenshot (icon-scale, not full-device).** The specific screen for that feature.

The features to include, in priority order:

1. **The compare view (already covered — but repeat here as the anchor feature).**
> *"Compare any two check-ins."*
> Pick any two dates. Side by side, same scale, honest.

2. **Weekly check-ins.**
> *"One check-in a week. That's the whole habit."*
> A quick photo, a weight, a note. Recomp reminds you at your usual time.

3. **Historical photo import.**
> *"Import the photos you already have."*
> Point Recomp at your camera roll. It'll pull the physique photos and organize them by date.

4. **A real timeline, not a photo grid.**
> *"Every check-in in one scroll."*
> Not a folder of photos — a timeline you can actually read, with dates, weights, and notes.

5. **Optional weight and notes.**
> *"Weight and notes when you want them. Never required."*
> Track what matters to you. Ignore what doesn't.

6. **Private by default.**
> *"Your photos never leave your phone unless you say so."*
> No feed. No sharing. Nothing public. Just your own record.

That's six. Six is the ceiling for this section. Consider cutting to four for the launch page — 1, 3, 4, 6 — and adding 2 and 5 later if the page has room.

### Feature *order* is a persuasion decision, not a spec decision

The order above puts *the compare view* first (it's the anchor), *historical import* third (it's the highest-leverage acquisition feature per the context doc), and *privacy* last (it's the closing objection killer — see §9). This is not the order they'd appear in a spec sheet; it's the order that builds toward install.

### Visual pattern

Two-column grid on desktop (three features per column, three rows of two). Single column on mobile. Each block has an icon or small screenshot on the left, copy on the right.

Alternative: alternating full-width feature rows. Each row has a screenshot on one side (alternating sides) and copy on the other. Feels more premium; takes more vertical space. Better for the launch page; the grid becomes better once the page has more sections competing for attention.

Start with alternating rows. This is what Hevy uses in its middle-of-page feature sections, and it works well for products where each feature has a distinct screen worth showing.

### What to explicitly *not* include

The context doc is clear about what Recomp is not. Reinforce that by not putting these in the feature grid:

- **Streaks, XP, badges.** Would signal generic-fitness-tracker.
- **Social feed / friends / leaderboards.** Actively opposite of the positioning.
- **Workout logging.** The context doc says explicitly the app should not become a workout tracker; the feature strip is where you signal that by omission.
- **Calorie tracking.** Same.
- **HealthKit integration.** *Maybe* worth mentioning eventually, but the context doc places this as future / supporting-context, not current feature.

The absence of these is a persuasion tool. The persona will notice, and it will read as *finally, an app that respects what physique tracking is actually about.*

### Anti-patterns

- **Feature names invented for the marketing page.** "PhysiqueSense™" or "Progress AI." Persona will laugh. Call the features what they are.
- **Icons that don't mean anything.** A generic camera icon for "check-ins" is dead weight. Either use a screenshot or nothing.
- **Feature descriptions with adjectives.** "Powerful compare view" is worse than "Compare any two check-ins."
- **A "coming soon" tease.** Roadmap teases feel like B2B SaaS. The consumer app model is: ship, or don't mention.

---

## 9. Section 6 — Objection Handling

### The job

The visitor at this point has scrolled through the hero, the problem, the solution, the aha moment, and the feature strip. They understand what Recomp is. If they haven't installed, it's because something specific is stopping them. This section names and defuses the specific objections.

For Recomp targeting the science-based lifter, the objections are predictable. In order of frequency, they are:

1. **"Is this just an iPhone Photos album with extra steps?"**
2. **"How do you make sure I'm consistent enough for the compare to be honest?"** (pose, lighting)
3. **"Do I have to track weight / macros / workouts?"**
4. **"How much does it cost?"** (given the free-tier / paid model)
5. **"Are my photos private?"**
6. **"Does this work if I don't have years of history yet?"**
7. **"What if I already use [Hevy / MacroFactor / Progressr]?"**

### The copy formula — the modified FAQ pattern

The standard "FAQ" pattern (a stack of Q&A pairs) is fine but boring. A stronger pattern is to *lead each answer with a specific claim, then explain*. This makes each item scannable and quotable.

**Example — the camera-roll objection:**

> **"Isn't this just an iPhone album?"**
>
> An album is a folder. Recomp is a timeline. The difference is compare — being able to place any two dates side by side, aligned and dated, without hunting through months of photos. Try it once and the gap is obvious.

**Example — the consistency objection:**

> **"How do I make the compares honest?"**
>
> Take check-ins at the same time of day (morning is best), in the same lighting, same pose. Recomp reminds you at your usual time and shows your most recent pose as a ghost overlay while you're setting up the new shot. The rest is on you — the tool doesn't fix bad inputs.

Note the honesty of the second answer. The persona reads this as respect: *the tool has a limit, we're telling you where it is.* This is a Wiebe move — acknowledge the limitation, own it, move on.

### Full answer set for launch

Draft answers for the seven objections above. Cover each in 2–4 sentences. Don't ask questions the visitor isn't asking (this is a common FAQ anti-pattern — inventing objections to answer them creates them).

Suggested launch set:

1. **"Isn't this just an iPhone album?"** — Compare view is the difference. Explain in one sentence.
2. **"How do I make the compares honest?"** — Same time, same light, same pose. Recomp helps with the pose overlay.
3. **"Do I have to track weight, workouts, or macros?"** — No. Recomp does one thing.
4. **"How much does it cost?"** — Free up to 30 photos. Paid after. State the pricing when it exists; don't hide it. (Once the paid tier is live, this becomes: *"Free to try. Paid once you're serious — a one-time-per-month cost less than a gym membership."* — but land the actual number.)
5. **"Are my photos private?"** — Yes. Details on where they live (device, iCloud, whatever the actual answer is).
6. **"I don't have years of photos. Does this still work?"** — Start now. Recomp gets more powerful every week. Realistic expectation: 3–6 weeks to first meaningful compare.
7. **"I already use [tracker]. Do I need this?"** — Recomp doesn't replace training or nutrition trackers; it's the missing piece those tools skip: the visual outcome.

### Visual pattern

Expandable accordion (click a question to expand the answer). Reasons:
- Keeps the page short by default.
- Signals thoroughness without demanding attention.
- Lets each visitor address only their specific objection.
- Standard accessibility pattern — persona will recognize and trust it.

Do *not* pre-expand any of them. Pre-expanded FAQs create visual clutter and defeat the purpose of the pattern.

### Anti-patterns

- **Invented FAQs.** "Q: Is Recomp really that good? A: Yes." — obvious cringe.
- **FAQ as a place to hide bad news.** If the paid tier is $X/month, say it here plainly. Hidden pricing is the fastest way to lose the persona.
- **Long-form answers.** Anything over 4 sentences belongs on a support page, not the landing page.
- **Sales-y language.** "Absolutely!" and "Great question!" are register-breaks that read as low-quality. Keep it flat and precise.

---

## 10. Section 7 — Final CTA

### The job

The visitor has scrolled the whole page. They understand the product. They've seen the aha. They've read the objections. If they were going to bounce, they already have. The people at the final CTA are the highest-intent segment on the page. Give them one clean, unmissable path to install.

### The copy formula

**Section headline — a re-statement of the promise, with a slight escalation:**

> **See the progress you've been working for.**

Or a slight variant, to feel like a summary rather than a repeat:

> **Stop guessing. See it.**

**One-line supporting copy — a compressed pitch:**

> Free to start. Take your first check-in tonight.

The "tonight" is a subtle *specificity of action* — Wiebe's move to convert general intent into a specific act. The persona will read "tonight" and probably actually do it tonight.

**CTA button — the App Store badge again. Larger than the hero one. Centered.**

**Below the CTA — no additional links, no email capture, no "or subscribe to updates."** The final CTA is the choke point. Anything that's not the App Store link is exfiltration from the funnel.

### Visual pattern

Full-width section. This is one of the ≤2 places on the page where a *full-bleed accent* background is worth spending — a solid accent-tinted fill that layers over the page-body grid (see §12.1a layering pattern 3). The final CTA earning the accent treatment gives the scroll a clear terminal note without competing with the grid identity everywhere else. Copy centered. CTA centered. Above the CTA: optionally, a small compare view (a different one from the hero, so the visitor is left with a fresh proof point).

Consider one more density signal below the CTA, in tiny type:
> *4.8 · App Store · 5,000 lifters and counting.*

But only if the numbers are real, and only if you haven't already used the same signal directly above.

### Pre-release version of the final CTA

The pre-release page's final CTA is a re-invitation, not a re-conversion. It should re-state the *specific opportunity of early access* rather than the *promise of the product*.

**Section headline options:**

> **The first 100 lifters shape what ships.**

Or:

> **Get in before public launch.**

**Supporting copy:**

> Recomp is in private beta. We're reviewing new access requests within 48 hours. If you take physique tracking seriously, come help finish the tool.

**CTA:** Same as the hero — "Request early access."

**Below the CTA:** State the honest cohort status.

> *42 spots remaining in the first cohort · Reviewed within 48 hours*

The pattern to avoid: a final CTA that says "Get notified when we launch." The reframe requires the same *active request* language at the top and bottom of the page. Consistency reinforces that this is a real filter, not a marketing gimmick.

### Anti-patterns

- **"Get in touch" or "Contact us" as final CTA.** The final CTA is the same as the primary CTA is the same as the only CTA: install.
- **A second CTA — "Follow us on TikTok."** Social follows are a leak. The user who's at the final CTA is worth an install, not a follow. Put social links in the footer if you must, but never near a CTA.
- **A "we'll email you when it's ready" capture.** If Recomp is live (it is: [App Store link](https://apps.apple.com/us/app/recomp-your-physique-tracker/id6760444125)), there is nothing to capture. Ship the install.
- **A pricing block right above the CTA.** Handle pricing in the FAQ. A pricing block at the final CTA introduces last-minute cognitive load — is $5 worth it? — right when you want the user acting on emotion + evidence.

---

## 11. Copywriting Frameworks and Formulas

Six frameworks worth internalizing before writing the copy. Each is a compression of a longer body of CRO literature; each is tuned for a consumer app with visual value.

### 11.1 Wiebe's "join the conversation already happening in the prospect's head"

The single strongest heuristic in copywriting. The visitor arrives at the page mid-thought. Your job is not to *start* a conversation; it's to *continue one they're already having with themselves*.

For Recomp, the internal conversation is some version of:
- *"Am I actually changing?"*
- *"I've been at this for six months. What do I have to show for it?"*
- *"I know I've made progress. I just can't tell how much."*

The hero headline should feel like it *finishes* that thought, not starts a new one. "See the progress you've been working for" completes the thought *"I've been working, but I can't see..."* — it's a resolution, not an interruption. Test every candidate headline against this rule: *"Is this what the visitor was already thinking, one second before they clicked?"* If yes, ship. If no, rewrite.

### 11.2 The PAS formula (Problem → Agitation → Solution)

The oldest and most reliable structure for a landing page. The section-by-section breakdown above is essentially PAS:

- **P (Problem):** Section 2 — you can't perceive your progress.
- **A (Agitation):** Section 2 — and the doubt kills programs early.
- **S (Solution):** Sections 3–5 — Recomp turns your photos into a compare view.

The classical mistake is to skip Agitation. Without it, the visitor doesn't feel the problem is worth solving *right now*. With it, the solution feels urgent. For Recomp, agitation is soft (this is a discerning persona, not a desperate one), but it must exist.

### 11.3 Gardner's Attention Ratio

*"On a landing page, the ratio of interactive elements to conversion goals should be 1:1."* One goal, one path.

Every button, link, and interactive element on the page is either a step toward install or a leak from install. In practice:
- **Nav bar:** Kill it. Or reduce to a logo + one App Store badge.
- **Footer links:** Legal only (privacy, terms, contact). No product links, no blog, no press page unless press is truly ambient social proof.
- **Social icons:** Footer only. Small. Don't compete with the CTA.
- **Language toggle, currency toggle, dark mode toggle:** Kill unless critical.

### 11.4 The 5-second test

Show the hero to a non-user for 5 seconds. Then ask three questions:
1. What is this product?
2. Who is it for?
3. What would happen if you tapped the button?

If any answer is unclear or wrong, the hero fails. Iterate.

Do this test with 5–10 real people (ideally 3–4 in the persona and 3–4 outside it). Persona members should get all three answers right. Non-persona members should at least get 1 and 3 right; getting 2 wrong is fine (the page isn't for them, and it's fine if that's clear).

### 11.5 Voice of Customer (Wiebe / Laja)

The best copy on the page is not written by you. It's written by your users, and you edit it.

Sources for VoC:
- App Store reviews (yours and competitors').
- Reddit threads on r/bodybuilding, r/fitness, r/naturalbodybuilding — search for "progress photos," "camera roll," "am I actually gaining."
- TikTok/YouTube comments on physique-tracking, science-based-lifting videos.
- Interviews with your first 10–20 users. Ask them to describe the product in their own words.

Look for:
- Recurring phrases ("I can't tell if I'm making progress").
- Specific pain points ("my camera roll is a mess").
- Moments of realization ("holy shit, I actually changed").

The recurring phrases become headline candidates. The pain points become subhead and problem-section copy. The moments become social proof captions.

### 11.6 The specificity rule (Laja)

*"The more specific a claim, the more believable it becomes."*

- "Turn your physique photos into a timeline" > "Track your physique."
- "150 check-ins over two years" > "Lots of data."
- "3–6 weeks for visible change" > "See results fast."
- "Free up to 30 photos" > "Free to try."

Specificity is credibility. Every rewrite pass on the page copy should ask: *"Can I make this more specific?"* Nine times out of ten, the answer is yes.

### Bonus — the "grandmother test" for jargon

The persona knows what "recomp," "cutting," "bulking," and "progressive overload" mean. Use them. But every non-persona term (design system terms, marketing jargon, feature names) should pass the grandmother test — could a non-lifter grandmother figure out what it means from context? If no, rewrite. This keeps the page dense with domain signals (persona sees "recomp" and knows the product is for them) while staying free of the *marketing* jargon that alienates the persona (persona sees "revolutionary" and bounces).

---

## 12. Visual Hierarchy and Design

The design system for Recomp's landing page should be an extension of the app's design system, which the context doc describes as: *Apple/iOS-native, clean, scientific, minimal, visual, data-oriented, high-contrast, credible, modern.* This section translates that into landing-page-specific decisions.

### 12.1 Color palette — both modes required

Ship both dark mode and light mode. The persona expects mode-following (iOS-native apps do; a persona-aligned marketing site should too), and light mode is the correct default for many desktop viewers using system-follow. Design the palette as a token system with two mode maps, not as one mode plus an afterthought.

**Dark mode:**

- **Background:** Near-black (#0A0A0B or similar). Not pure black — pure black on OLED is too aggressive and reads harsh. A soft near-black creates depth without heaviness.
- **Primary text:** Off-white (#F5F5F7). Apple's exact text-on-dark color, and it works because it doesn't strobe against the near-black background the way pure white does.
- **Secondary text:** A muted gray (#A1A1A6). Same Apple system.
- **Grid overlay color:** `rgba(255, 255, 255, 0.05)` — the exact value from the reference implementation below. See §12.1a for the full grid spec.

**Light mode:**

- **Background:** Off-white (#F8F8F7 or #FAFAF9). Not pure white — pure white feels sterile and blows out on a bright display. A slight warmth (very subtle cream tint) reads as premium and reduces eye strain.
- **Primary text:** Near-black (#0A0A0B). Same near-black as the dark mode background, inverted.
- **Secondary text:** Muted graphite (#6B6B70).
- **Grid overlay color:** `rgba(0, 0, 0, 0.06)` — the light-mode equivalent. Slightly higher opacity because dark ink on light ground reads more subtly than light ink on dark ground.

**Accent (both modes):** A single strong accent color used identically in both. Options:

- **Electric blue** (#0A84FF) — Apple's iOS blue. Trust-inducing, matches the persona's expectations for a well-made iOS app. Works well on both grounds.
- **Vibrant green** (#30D158) — Apple's system green. Signals *fitness / progress* subtly, but might be too on-the-nose.
- **The compare view itself as the accent** — the compare view (dominantly full-color user photo) becomes the visual accent while all UI chrome stays neutral. Very Moody-adjacent. Most premium-feeling.

Start with Apple's iOS blue. It's the safest anchor to Apple-native identity and earns the persona's trust.

- **Success / progress green:** Reserved for actual "progress" indicators (weight down arrows, compare deltas). Use sparingly — if everything is green, nothing is.

### 12.1a The graph-paper grid — the foundational background layer

This is the *strongest available design move* for this persona, and the way to use it — following the Moody reference — is as a **foundational background layer that spans the entire page**, not as a per-section accent. Every other background (solid section fills, panel cards, the final CTA block) layers *over* the grid; the grid is the constant beneath everything. This is the pattern Moody uses to unify a long, section-rich page into one continuous document, and it's what makes the graph-paper feel signature rather than decorative.

Why the foundation approach works:

- It creates a single unified surface. The visitor scrolls through eight sections and never leaves the same background. That continuity does a lot of quiet work — the page feels like *one thing*, not a stack of unrelated blocks.
- It's low-attention by design. At the recommended opacity (0.05 dark / 0.06 light), the grid registers as texture, not information. The eye doesn't parse individual lines; it reads *"measured surface"* as a single ambient signal.
- Layering over it becomes the design language. Elevated cards, solid section fills, and screenshots all get to visually *rest on* the grid — the grid becomes the ground, everything else becomes figure. That figure/ground relationship is what makes considered design read as considered.
- It matches what the persona already trusts: Desmos, graph-paper notebooks, math class, engineering paper. Signals *measured, precise, scientific, evidence-based* — everything the positioning asks for.
- It rhymes with the product itself: the alignment grid inside the app (for aligning progress photos in the same pose) uses the same visual language. Marketing and product identity converge.

**Reference implementation — applied to the page root (dark mode):**

```css
body {
  background-color: #0A0A0B;
  background-image:
    linear-gradient(to right, rgba(255, 255, 255, 0.05) 1px, transparent 1px),
    linear-gradient(to bottom, rgba(255, 255, 255, 0.05) 1px, transparent 1px);
  background-size: 40px 40px;
  background-attachment: fixed; /* optional — keeps the grid still while content scrolls */
}
```

**Light mode:**

```css
body {
  background-color: #FAFAF9;
  background-image:
    linear-gradient(to right, rgba(0, 0, 0, 0.06) 1px, transparent 1px),
    linear-gradient(to bottom, rgba(0, 0, 0, 0.06) 1px, transparent 1px);
  background-size: 40px 40px;
  background-attachment: fixed;
}
```

On `background-attachment: fixed` — Moody uses fixed. It creates a subtle depth effect (content moves; grid stays), which reinforces the "grid is the ground plane" mental model. The tradeoff: `fixed` has minor scroll-performance costs on some mobile browsers. Test on iPhone 12 / SE. If scroll feels less than 60fps, switch to the default (scrolling background) — the design still works.

**How other backgrounds relate to the grid:**

Sections don't *replace* the grid; they *layer over* it. Three layering patterns to use:

1. **Transparent section (default for most sections).** The section has no background of its own. The page-body grid shows through directly. Copy sits on the grid. This is the base case and should be the most common section treatment.

2. **Elevated card / panel over the grid.** The section content sits inside a solid-fill card (near-black in dark mode, off-white in light mode) with generous rounded corners (16–24px radius) and a subtle border or shadow. The grid shows around the card. Use for: feature blocks, the two-flow split card, testimonial cards, the FAQ accordion container. Elevated cards let the grid *frame* the content visually.

3. **Full-bleed accent section over the grid.** Section spans full viewport width with a solid or slightly-tinted background that covers the grid completely. Reserve for two or three high-emphasis moments: the final CTA (accent-tinted), optionally the aha section. Overusing this pattern erodes the grid's foundational role. Rule: at most 2 full-bleed accent sections per page.

**Design rules for the grid:**

1. **The grid is always present.** Every pixel of the page's ground plane is grid. No section "opts out" — even solid-fill accent sections layer over it, and the grid re-emerges in the padding between sections and at the page edges.

2. **The compare view and other product screenshots use the grid too.** When showcasing the compare feature, the app's internal alignment grid should match or complement the page's grid. This creates visual rhyme between the page and the product — the visitor sees the same graph-paper surface in marketing and in the app.

3. **Scale the grid with viewport.** On mobile, use `background-size: 24px 24px` — a 40px grid on a 390px viewport looks coarse. On very large desktop viewports (1600+), `48px` reads better than `40px`. Use a media query, not a JS calculation.

4. **Test contrast in both modes.** The dark-mode grid opacity (0.05) sits just above the visibility threshold. Anything higher and it competes with text; anything lower and it disappears on lower-quality displays. Verify at typical MacBook and iPhone brightness — and specifically verify that body text still passes WCAG AA contrast on the gridded background (the grid is faint enough that this passes, but confirm).

5. **Don't fade section edges.** Because the grid runs continuously through the whole page, section-edge fading (the `mask-image` trick) breaks the continuity. Sections that need visual separation from the grid should use pattern 2 (elevated card) or pattern 3 (full-bleed accent), not a gradient fade.

6. **Match the app's alignment grid density.** If the compare view alignment overlay in the app uses 20px squares, the landing page grid should be a multiple of that (40px is a natural pair). The rhyme reinforces the product-marketing continuity.

**Extensions worth considering:**

- **Subtle grid animation.** Extremely slow parallax where the grid drifts diagonally at 1–2px per second, or a very restrained axis-aligned drift on scroll. Exception to the "kill motion that doesn't teach" rule because it's *ambient background* rather than competing with attention. Ship only if genuinely subtle — noticeable within 5 seconds = too much.
- **Grid density variation.** Some Moody-style pages use a slightly denser grid inside elevated cards (24px inside a card, 40px on the body). Creates a subtle "zoomed-in" effect on the card. Optional.

**Anti-patterns for the grid:**

- **Treating the grid as a per-section accent.** The single most common mistake. The grid should not appear and disappear as you scroll; it's the foundation the whole page rests on. If some sections have it and some don't, it reads as decoration; when it's continuous, it reads as identity.
- **Isometric or perspective grids.** The grid should read as a flat 2D reference plane. Isometric grids look like SaaS marketing sites circa 2019.
- **Multi-color grid lines.** One color, one opacity. If you're tempted to accent-color the grid lines, you've broken the reference.
- **Grid over photography.** The grid should sit *under* content, never *over* photos. When a full-bleed photo appears on the page, that specific area covers the grid (photo is opaque and takes the whole section width) — the grid doesn't overlay the image.
- **Turning up the grid opacity to make it "pop."** The whole point is that it doesn't pop. Faint enough to feel like paper, no more. If you find yourself wanting the grid to be more visible, the real problem is that a specific section needs a visual accent, and the right fix is an elevated card or an accent section, not louder grid lines.

### Motion for mode switching

If a user toggles between light and dark modes (or their system does at sunset), the transition should be smooth — 300ms crossfade on all color-carrying properties. Instant snaps read as low-quality. Use `transition: background-color 300ms ease, color 300ms ease` at the root, and let it cascade.

### 12.2 Typography

The context doc says Apple-native. Two viable stacks:

**Stack A — SF Pro (Apple's system font):**
Use `-apple-system, BlinkMacSystemFont, "SF Pro Text", "SF Pro Display", system-ui, sans-serif`. Falls back gracefully on non-Apple devices. Perfect persona alignment.

**Stack B — Inter with SF fallback:**
A close visual match to SF that renders identically across all devices. Inter is the near-universal "serious tech company" web font in 2026. Slightly less Apple-native, more consistent across platforms.

Recommend Stack A. The persona will recognize the SF rendering as "made by someone who cares about Apple" and the visual identity will feel unified with the app itself.

**Type scale:**
- **Hero headline:** 56–72px on desktop, 40–48px on mobile. Weight: 700 (bold). Line height: 1.05–1.1 (tight, for impact).
- **Section headlines:** 40–56px desktop, 32–40px mobile. Weight: 700.
- **Subheads / large body:** 20–24px desktop, 18–20px mobile. Weight: 400. Line height: 1.4.
- **Body:** 16–18px. Weight: 400. Line height: 1.5–1.6.
- **Micro-copy / meta:** 13–14px. Weight: 400 or 500. Muted color.

**Do not:**
- Use serifs (breaks the Apple-native identity).
- Use display or novelty fonts.
- Use more than two weights on the page (regular + bold is enough).
- Justify text (creates rag-right rivers; left-align always).

### 12.3 Spacing and rhythm

- **Section vertical padding:** 96–128px desktop, 64–80px mobile.
- **Max content width:** ~1200px for text-heavy sections, ~1400px for hero. Anything wider breaks reading rhythm.
- **Line length:** Body text between 60–75 characters per line. Anything longer hurts readability on desktop.
- **Vertical rhythm:** Use consistent multiples (8px or 16px base). Every margin and padding value on the page should be a multiple of your base unit. Creates unconscious visual rhythm.

### 12.4 Imagery style

- **Device frames:** iPhone 15/16 straight-on. No angled shots. No hands. No "in the wild" photography of someone holding the phone in a gym.
- **Compare views:** These are the *only* human-body imagery on the page. Real photos, real users, honest lighting.
- **No stock photography.** Ever. The persona will spot it in 200ms.
- **No gym / equipment b-roll.** Adds no information; competes with product visuals.
- **Product screenshots:** Consistent — same phone, same status bar, same time of day (9:41 AM for the classic Apple demo shot). Retina resolution. No visible compression artifacts.

### 12.5 Buttons and CTAs

- **Primary CTA:** The Apple App Store badge. Do not customize. Use the official Apple asset.
- **Secondary buttons (if any):** Text link, or a bordered pill button in the accent color. Never as large or as high-contrast as the App Store badge.
- **Hover states:** Subtle. A 5–10% brightness lift, no scaling, no color changes.
- **Focus states:** Visible and accessible. A 2px ring in the accent color. Persona might tab-navigate — respect it.

### 12.6 Motion

The rule from §2.6 applies: only motion that teaches earns its place. Concrete allowances:

- **Compare view slider on hover/tap:** The user drags a slider to reveal photo B under photo A. Teaches the compare interaction. Ship.
- **Photo drop into timeline:** When the "how it works" section scrolls into view, a photo animates into the timeline. Teaches the timeline. Consider.
- **Ambient parallax on hero:** Ship-killing distraction. Cut.
- **Auto-playing hero video:** Same. Cut. If you want a video, autoplay on tap, not on load.
- **Reveal-on-scroll fade-ins:** Fine if subtle (opacity 0 → 1, 200ms). Avoid slide-up-and-fade combinations that feel sluggish.

### 12.7 Both modes, system-following by default

Ship both light and dark mode, following the visitor's system preference by default, with a small manual toggle in the footer or nav corner.

Reasons for both:
- The persona expects mode-following. An iOS-native app that ignores light mode reads as *poorly considered*.
- Light mode is the daylight default for many desktop viewers. Dark-only pages read as harsh in a bright office at 2pm.
- The graph-paper grid design (§12.1a) works beautifully in both modes and reinforces the *scientific / precise* identity in both palettes.
- Founder-led TikTok content is often watched in bright environments (gym, outdoors); a landing page linked from that content should look good in daylight.

**Implementation:**
- Default to `prefers-color-scheme` media query — the page follows the visitor's OS setting on first load.
- Small mode toggle in the footer (or a subtle corner control) with three states: system / light / dark. Persist to localStorage.
- Every color used on the page is a CSS custom property that swaps in the theme block. No hardcoded hex values in component styles.
- Test both modes at every design step — a light-mode-broken page is a broken page.

**On design decisions that differ between modes:**
- The compare view screenshot should have two versions — one for each mode — where the app chrome around the photos matches. The actual physique photos stay the same.
- The device frame color changes with mode (silver iPhone frame in light mode, graphite/black in dark).
- The grid opacity is different in each mode (see §12.1a).
- Accent color (Apple blue) stays constant across modes.

### 12.8 Accessibility as a persuasion feature

The persona expects a well-made product. Poor accessibility is a signal of poor craft.

- **Color contrast:** All text meets WCAG AA (4.5:1 for body, 3:1 for large text). Check every text/background pair.
- **Alt text:** Every image has meaningful alt text. Compare views: *"Two-panel compare view: physique on the left dated April 2024, on the right dated July 2024. Weight: 195 lb → 182 lb."*
- **Keyboard navigation:** Every interactive element is tabbable, focus visible.
- **Reduced motion:** Respect `prefers-reduced-motion`. Kill non-essential motion for users who've opted out.

---

## 13. Mobile-First and Responsive Design

### 13.1 The mobile-first mandate

For a consumer iOS app, ~70–85% of landing page traffic is mobile. For a fitness app promoted through TikTok/Instagram/YouTube, that number is higher — call it 85%. Every design decision starts on a 375×667 or 390×844 viewport (iPhone SE and iPhone 12+ respectively) and expands from there.

Concrete implication: when a design decision creates tension between desktop and mobile, mobile wins. This inverts the default of most teams.

### 13.2 The mobile hero rules

- **CTA must be visible without scrolling on iPhone 12+ (390×844).** Non-negotiable. Test with browser dev tools set to iPhone 12 dimensions. If the App Store badge isn't visible, cut copy or compress the visual until it is.
- **Copy stack, then visual, then CTA.** This is the only ordering that fits on mobile. Never side-by-side on mobile.
- **Headline max 6 words on mobile.** Longer headlines wrap awkwardly and blow past the fold. "See the progress you've been working for" is 7 words but reads clean if the line breaks are controlled (`br` after "progress").
- **Hero visual max 45% of viewport height.** Larger and it pushes the CTA below the fold.
- **App Store badge is the only interactive element above the fold.** Not even nav — collapse nav into a hamburger or, better, remove it entirely for mobile.

### 13.3 Touch targets

- **All tap targets ≥ 44×44px.** Apple's Human Interface Guidelines standard. Persona will notice a 30px button and rate it as low-quality.
- **Spacing between adjacent tap targets ≥ 8px.** Prevents fat-finger mistaps.
- **App Store badges default to 40–48px tall on mobile.** Any smaller and they feel weak; any larger and they dominate the composition.

### 13.4 Section reordering on mobile

Consider a slightly different section order on mobile than on desktop. Specifically:

- On desktop: hero → problem → solution → aha → features → social proof → objections → CTA.
- On mobile: hero → aha → problem → solution → features → social proof → objections → CTA.

Rationale: mobile visitors are more likely to bounce fast. Front-loading the aha moment right after the hero (with less text between them) increases the odds that a visitor who's about to bounce sees the strongest emotional beat first.

This is a *variant to test*, not a default. Ship the desktop order on mobile first, then A/B test the aha-early variant (§14).

### 13.5 Load performance

Mobile users abandon at ~3s TTI (time to interactive). Every 100ms beyond 3s is a measurable conversion loss.

Concrete mandates:
- **Total page weight < 1.5MB.** Realistic for a page with 6–10 device screenshots.
- **Above-the-fold assets < 500KB.** Includes hero image.
- **All images served as AVIF or WebP with JPG fallback.**
- **Lazy-load everything below the fold.**
- **Fonts loaded with `font-display: swap`.**
- **No render-blocking third-party scripts** (kill chat widgets, unnecessary analytics, marketing tags).
- **Test on Lighthouse on iPhone 12 simulation.** Target: performance score ≥ 90.

### 13.6 Text rendering

- **Base font size ≥ 16px on mobile.** Anything smaller triggers iOS's auto-zoom on form inputs and reads as low-quality.
- **Line length target: 40–50 characters on mobile.** Longer lines are hard to read on small screens.
- **Never use `letter-spacing: negative` on body text.** Wrecks readability at small sizes.

---

## 14. Conversion Rate Optimization and A/B Testing

### 14.1 The measurement setup

Before A/B testing anything, instrument the page properly. The metrics that matter for Recomp:

**Primary conversion:** Click on the App Store badge (measured via outbound click event to `apps.apple.com`). This is your top-of-funnel install signal.

**Real conversion (harder, but critical):** App Store install → app open → first check-in. Requires attribution via a service like Branch, Adjust, or (simpler) UTM parameters in your App Store link + App Store Connect analytics. Every landing page test should ultimately be judged on installs and first check-ins, not clicks on the badge.

**Micro-metrics (leading indicators):**
- **Scroll depth:** What percentage of visitors reach the aha section? Feature strip? Final CTA?
- **Time to first interaction:** How long before the first click/tap/scroll?
- **CTA click distribution:** How many clicks come from hero vs. mid-page vs. final CTA?
- **Video play rate** (if a demo video is embedded): what percent play, what percent watch through?

**Bounce and exit:** Bounce rate for the page, exit rate per section (if you can measure it).

### 14.2 Recommended tools

- **Analytics:** Plausible or Fathom (privacy-respecting, simple, cheap) or GA4 (free, complex, tracks well).
- **A/B testing:** For a small site, VWO, Optimizely, or Google Optimize alternatives. Or roll your own with a simple feature-flag setup — for the traffic volumes Recomp will have early, over-engineering the test infrastructure is wasted effort.
- **Session replay:** Hotjar or Microsoft Clarity. Cheap, gives you the qualitative signal that pure analytics miss.

For the first 6 months, prioritize *qualitative* over *quantitative*. Watch 20 session replays of real visitors. You'll learn more from watching two lifters actually try to install than from a statistically-underpowered A/B test.

### 14.3 What to test — priority order

Test in order of *expected impact × cost of running the test*. Rough priority:

**Tier 1 (highest expected impact):**
1. **Hero headline variants.** V1 (outcome), V2 (camera-roll), V3 (question). See §4 for exact copy.
2. **Hero visual.** Static compare vs. animated (slider reveal) vs. video demo. Compare vs. timeline as the dominant image.
3. **Section order.** Aha-early on mobile (§13.4) vs. current order.

**Tier 2 (meaningful impact, lower cost):**
4. **Primary CTA micro-copy.** "Download on the App Store" (badge default) vs. adding "Free to start" above it vs. adding a specific action ("Take your first check-in tonight" as headline above the CTA in the final section).
5. **Feature strip length.** 6 features vs. 4 features vs. 3 features.
6. **Social proof format.** Founder-transformation dominant vs. user-quote gallery vs. blend.

**Tier 3 (lower impact, useful once basics are dialed):**
7. **Objection handling copy.** Rewrite specific FAQ answers.
8. **Micro-copy on the density signal** (persona marker vs. rating vs. install count).
9. **Color accent** (Apple blue vs. white vs. green).

Don't test more than one thing at a time unless traffic is >10k unique visitors/month. Below that, you lack statistical power for multivariate tests and will chase noise.

### 14.4 Statistical hygiene

For a page with early traffic (say, 500 visitors/week to start), single tests take 4–8 weeks to reach significance. This is fine — the alternative is chasing noise. Follow the rules:

- **Set the sample size and duration in advance.** Never call a test early because it's "already looking good."
- **95% confidence minimum.** Anything less and you're guessing.
- **One test at a time until the page has volume.**
- **Test in both directions.** If you have a hypothesis, also test the opposite. Sometimes the opposite of a "best practice" wins for your specific audience.
- **Segment by traffic source.** A test that wins overall may lose for TikTok traffic and win for App Store search. That matters.

### 14.5 The qualitative loop

Every 2 weeks in the first 3 months:
1. Watch 5 fresh session replays.
2. Read the last 20 App Store reviews.
3. Scan Reddit / Twitter mentions.
4. Update a running document with observations.

You will learn more from this than from any A/B test. The pattern to look for: *the specific phrase or moment where a visitor gets it.* When you see the same phrase three times, use it in the copy.

### 14.6 The Peep Laja loop

Laja's framework at CXL is: *research → hypothesis → prioritize → test → iterate*. In practice for Recomp:

1. **Research:** Watch replays, read reviews, do 3 user interviews.
2. **Hypothesis:** "Visitors bounce at the feature strip because it feels like a generic fitness app."
3. **Prioritize:** Rank hypotheses by expected impact × ease of test.
4. **Test:** Ship one variant, measure.
5. **Iterate:** Roll up learnings into the next research cycle.

Don't skip steps. Especially don't skip research — most failed A/B tests are failed hypotheses, and most failed hypotheses come from skipping research.

### 14.7 What *not* to test

- **Trivial cosmetic changes** (button color from #0A84FF to #0866D0). Statistical power is wasted here.
- **Anything that would change the brand identity dramatically.** A "grungy gym-bro" variant may win a short test and lose the persona in the long run.
- **Anything that could damage credibility** (fake reviews, fake install counts, inflated social proof).

---

## 15. Landing Page Wireframe Template

An annotated slot-by-slot wireframe for Recomp's launch page. This is meant to be handed directly to prompt #2 (content generation) and prompt #7 (Claude mockup).

There are two versions of the wireframe below: **15A** for the release version (App Store install CTA), and **15B** for the pre-release version (waitlist / request-access CTA). They share ~80% of their structure; §15B calls out only the deltas.

### 15A — Release wireframe

```
NOTE ON GRID: the graph-paper grid (§12.1a) is applied to the PAGE BODY as a
foundational background layer running under every section. Sections do not
turn the grid on or off — they either sit transparently over it (default),
layer as elevated cards over it, or (final CTA only) cover it with a
full-bleed accent fill. The grid is the continuous surface the whole page
rests on, following the Moody reference.

+-------------------------------------------------------------------------+
| [minimal nav - logo left, App Store badge right, mode toggle far right] |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 1 - HERO  [transparent - page-body grid shows through]          |
|                                                                         |
| H1: You already have years of progress in your camera roll.             |
| Subhead: Recomp pulls your physique photos, aligns them, and lets you   |
|          compare any two - side by side, dated, honest.                 |
|                                                                         |
| [Download on the App Store]                                             |
| Micro: Free to start . Import your existing photos in seconds           |
|                                                                         |
| [DEVICE FRAME - iPhone with the compare view]                           |
|   Two real photos, dated, ideally the founder's own transformation.     |
|   Static or with a subtle slider affordance. Grid background inside     |
|   the compare view visually rhymes with the page grid.                  |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 2 - PROBLEM / AGITATION                                         |
|                                                                         |
| Visual: CONVERGENCE DIAGRAM, CAMERA-ROLL DOMINANT (see §5 Option C).    |
|   Left column, hierarchy encoded:                                       |
|     - Camera roll photo grid - DOMINANT (top, ~50% of left weight)      |
|     - Notes/Excel - small, supporting (bottom row)                      |
|     - Apple Health chart - small, supporting (bottom row)               |
|   Each mockup visually distinct so it reads as different apps.          |
|   Arrow: subtle, left-to-right, ending in Recomp panel.                 |
|   Right: Recomp compare view with photos + weight overlay + Apple       |
|     Health line marked with "in progress" tag. Panel dominant           |
|     (~40-45% of composition).                                           |
|   On mobile: camera-roll full-width on top, then small two-up row of    |
|     Notes + Apple Health, then arrow down, then Recomp panel.           |
| Caption below visual:                                                   |
|   "Your camera roll has the evidence. Recomp lays it out - with your    |
|    weight and notes alongside."                                         |
|                                                                         |
| H2: You see yourself every day. So the person in the mirror never       |
|     seems to change.                                                    |
|                                                                         |
| Body (~4 sentences):                                                    |
|   - Camera-roll beat (primary; leads).                                  |
|   - Weight/notes beat as supporting sentence, not co-equal.             |
|   - The doubt beat.                                                     |
|   - Handoff: "Recomp starts with the photos you already have.           |
|     Weight and notes come along for the ride."                          |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 3 - HOW IT WORKS (SOLUTION)  [transparent over page-body grid]  |
|                                                                         |
| H2: Three steps. That's the whole loop.                                 |
|                                                                         |
| [Step 1]           [Step 2]           [Step 3]                         |
| [Screenshot]       [Screenshot]       [Screenshot - LARGER]            |
| Take a weekly      Recomp builds      Compare, side by side.           |
| check-in.          your timeline.     See the actual difference.       |
|                                                                         |
| Closer: "That's it. No streaks. No workouts to log. No macros to       |
|          enter. Just the photos, the timeline, and the comparison."    |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 3b - TWO-FLOW SPLIT CARD                                        |
|                                                                         |
| H3: Two ways to start.                                                  |
|                                                                         |
| +-----------------------------+-----------------------------+           |
| | I've been taking photos     | I'm starting fresh          |           |
| | Import your camera roll.    | Take your first check-in    |           |
| | Recomp finds the physique   | tonight. Recomp builds the  |           |
| | photos, aligns them, and    | timeline from your first    |           |
| | shows the compare in        | photo forward. Compares get |           |
| | minutes.                    | powerful in 3-6 weeks.      |           |
| | [Download on the App Store] | [Download on the App Store] |           |
| +-----------------------------+-----------------------------+           |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 4 - THE AHA MOMENT                                              |
|                                                                         |
| H2: The moment you actually see it.                                     |
|                                                                         |
| [FULL-WIDTH COMPARE VIEW - real founder transformation]                 |
|   Dates on each photo. Weight overlay. Timeline delta ("14 weeks").     |
|                                                                         |
| Caption: 150 check-ins. Two years of lifting. Here's what the           |
|          compare view shows. - Mark, founder of Recomp                  |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 5 - FEATURE STRIP                                               |
|                                                                         |
| H2: Everything else your physique tracker should be.                    |
|                                                                         |
| [alternating-row feature blocks - 4 blocks minimum]                     |
|                                                                         |
| Row 1 (screenshot LEFT, copy RIGHT):                                    |
|   Compare any two check-ins.                                            |
|   Pick any two dates. Side by side, same scale, honest.                 |
|                                                                         |
| Row 2 (screenshot RIGHT, copy LEFT):                                    |
|   Import the photos you already have.                                   |
|   Point Recomp at your camera roll. It'll pull the physique photos.     |
|                                                                         |
| Row 3 (screenshot LEFT, copy RIGHT):                                    |
|   A real timeline, not a photo grid.                                    |
|   Every check-in in one scroll, with dates, weights, and notes.         |
|                                                                         |
| Row 4 (screenshot RIGHT, copy LEFT):                                    |
|   Your photos never leave your phone unless you say so.                 |
|   No feed. No sharing. Nothing public. Just your own record.            |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 6 - SOCIAL PROOF (density signals + secondary story proof)      |
|                                                                         |
| [Density strip]: 4.8 stars on the App Store . 5,000 lifters tracking    |
|                  . Featured in [logos as they accumulate]               |
|                                                                         |
| [Secondary compare view + testimonial] - a real user, not the founder   |
|   Quote focused on the moment of realization, not the app.              |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 7 - OBJECTION HANDLING (FAQ)                                    |
|                                                                         |
| H2: Answers to what you're probably thinking.                           |
|                                                                         |
| [Accordion - 7 items collapsed by default]                              |
|   1. Isn't this just an iPhone album?                                   |
|   2. How do I make the compares honest?                                 |
|   3. Do I have to track weight, workouts, or macros?                    |
|   4. How much does it cost?                                             |
|   5. Are my photos private?                                             |
|   6. I don't have years of photos. Does this still work?                |
|   7. I already use [tracker]. Do I need this?                           |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| SECTION 8 - FINAL CTA                                                   |
|                                                                         |
| [full-bleed accent - covers the page-body grid; see §12.1a pattern 3]   |
|                                                                         |
| H2: See the progress you've been working for.                           |
| Subhead: Free to start. Take your first check-in tonight.               |
|                                                                         |
| [Download on the App Store - larger than hero]                          |
|                                                                         |
| Micro (optional): 4.8 stars . App Store . 5,000 lifters and counting.   |
|                                                                         |
+-------------------------------------------------------------------------+
|                                                                         |
| FOOTER                                                                  |
| Logo. Legal (Privacy, Terms, Contact). Mode toggle (system/light/dark). |
| Social icons (small, footer only). (c) 2026 Recomp.                     |
|                                                                         |
+-------------------------------------------------------------------------+
```

### 15B — Pre-release wireframe (deltas only)

The pre-release wireframe is structurally identical to §15A with the following section-by-section deltas:

**SECTION 1 (Hero):**
- **H1** changes to a reframe-explicit headline (see §4b for the recommended default):
  > *"Early access is invite-only. Testing an unproven app is real work — the first 100 lifters get in."*
- **Subhead** describes the value exchange:
  > *"Recomp is a physique tracker built around the compare view. We're 4–8 weeks from public release. Get in early, help shape what ships."*
- **CTA** is `[Request early access]`, not the App Store badge.
- **Micro-copy** is honest scarcity:
  > *"Currently accepting requests · 78 spots left · Reviewed within 48 hours"*
- **Device frame** gets a subtle "in early access" corner badge.

**SECTION 3b (Two-flow split card):**
- Both cards' CTAs become `[Request early access]` instead of the App Store badge.
- The card copy stays the same — both flows apply to beta users too.

**SECTION 4 (Aha):**
- The founder compare view is *the only* social proof asset on the pre-release page (there are no user compares yet).
- Caption changes tone slightly to emphasize the founder-led development:
  > *"I have 150 check-ins over two years. I'm building Recomp because I couldn't find a tracker that respected the compare view. — Mark"*

**SECTION 6 (Social proof):**
- No density signals (no App Store rating yet, no install count).
- Replace with a "how the beta works" panel:
  - What you get: early access, direct line to the founder, lifetime discount on the paid tier, credit as a founding-cohort user.
  - What we ask: real feedback, at least one week of daily check-ins, honest reactions.

**SECTION 7 (FAQ):**
- Different objection set. Suggested:
  1. *"How do I get accepted?"* — First-come, priority to lifters with 500+ existing photos, lifters posting the persona-adjacent content on TikTok/YouTube. Not random.
  2. *"How much does it cost during the beta?"* — Free. Founding-cohort users get a lifetime discount on the paid tier at public launch.
  3. *"When does public launch happen?"* — 4–8 weeks from the first cohort. No hard promises.
  4. *"What happens to my photos if the app changes or shuts down?"* — Full export available at all times. Photos stay on your device.
  5. *"Do I need TestFlight?"* — Yes. Instructions arrive with your access email. Simple, one-tap.
  6. *"What kind of feedback do you actually want?"* — What's broken, what's missing, what's confusing, what made you stop using the app.
  7. *"Can I share it with my friends?"* — Not yet — the cohort is small on purpose. Point them to the waitlist.

**SECTION 8 (Final CTA):**
- Copy changes to a re-invitation (see §10 pre-release variant).
- CTA is `[Request early access]`, not App Store badge.
- Density signal is honest cohort status:
  > *"42 spots remaining in the first cohort · Reviewed within 48 hours"*

Everything else — graph-paper grid, both modes, mobile-first, typography, section rhythm — stays identical.

### 15.1 Notes on the wireframe

**Section count:** 8. If you find yourself adding a 9th, question hard. The pattern for high-converting consumer app pages is 6–9 sections total; more than 9 dilutes attention.

**Nav bar:** Optional. Simplest and most conversion-focused: no nav at all. The App Store badge in the hero *is* the nav. If you want a nav, keep it to logo + App Store badge and nothing else.

**Section 4 (aha):** This is the emotional peak. Everything above builds toward it; everything below reinforces it. If a visitor takes only one image away from the page, this should be it.

**Section 5 (features):** Consider cutting to 3 rows for the launch page, adding rows 2 and 5 later. Shorter is stronger for launch.

**Section 6 (social proof):** Adjust based on what you actually have. On launch day, this section might just be the density strip + the founder compare view (which technically doubles up with section 4). That's fine. Add real user compares as you collect them.

**Section 7 (FAQ):** Ship all 7 objections from day 1. This is the section where honesty about the paid tier and about the 3–6 week honest timeline earns trust with the persona.

**Section 8 (final CTA):** Do not omit. Even if the page is short. The final CTA converts the highest-intent visitors on the page, and its removal is a common self-sabotage move.

### 15.2 What's *not* in the wireframe (deliberately)

- No email capture form.
- No "watch a demo" video button (video can be embedded inline if it teaches, but not as a primary CTA).
- No "compare to competitor" table (unnecessary — you're not competing on features).
- No blog / recent posts section.
- No press page or media kit link (linked from footer if needed).
- No "our team" or "about us" section (the founder story lives inside the social proof / aha section).
- No pricing table (pricing lives in the FAQ).

Every omission is deliberate. Add any of these back only if you have specific evidence they lift conversion for this specific audience.

---

## 16. What to Hand to the Next Prompt

Prompt #2 in this framework generates the page structure with complete copy. Hand it, in order:

1. The wireframe above (§15).
2. The messaging hierarchy from the context doc (§17 of context: emotional promise → problem → product solution → supporting features).
3. The hero copy variants (§4.4 above).
4. The specific feature-block copy (§8).
5. The full FAQ set with draft answers (§9).
6. The persona description (from context doc §5 + §15).
7. The tone rules from §11 above (specificity, no jargon, Jeff-Nippard-style precision).
8. The visual identity notes from §12 (Apple-native, dark-mode-first, iOS blue accent, SF Pro).

That set gives prompt #2 everything it needs to produce a complete, opinionated, on-brand first draft — without any invention of tone, positioning, or persona details.

---

## 17. Sources and Reference

**Primary style reference:**
- [moody.mjarosz.com](https://moody.mjarosz.com/) — polished, three-step, price-anchored, one-time-payment positioning; used as the master reference for tone, spacing, and section rhythm.

**Analogous consumer app pages studied:**
- [hevyapp.com](https://www.hevyapp.com/) — the density-social-proof pattern (16M athletes, 4.9 rating, 590k+ ratings), press-logo strip, alternating feature rows. Ships six App Store review screenshots as social proof, which is *worse* than what's recommended above.
- [calai.app](https://www.calai.app/) — hero + immediate density social proof (5M users, 4.9 rating), FAQ that answers real objections (payment, refunds, accuracy), influencer testimonials. Instructive for the App Store CTA repetition (3× on page).
- [cluely.com](https://cluely.com/) — the "#1 in category" hero positioning; embedded video demo; edgy tone that works for its persona (would not work for Recomp's).
- [shotbase](https://shotbase.com/) — screenshot-driven demo pages for photography apps.
- [StrongLifts](https://stronglifts.com/) — no-fluff fitness tone; instructive on tone-that-doesn't-work-for-Recomp (too aggressive for the science-based lifter).

**CRO literature drawn from:**
- Joanna Wiebe (Copyhackers) — "join the conversation," Voice-of-Customer methodology, moment-based testimonial framing.
- Oli Gardner (Unbounce) — Attention Ratio, one-page-one-goal, 2024 landing page benchmarks.
- Peep Laja (CXL) — specificity rule, research-first CRO loop, honest-tradeoff copy.
- Apple Human Interface Guidelines — App Store badge usage, touch targets, motion.
- Unbounce Conversion Benchmark Report 2024/2025 — hero video and carousel penalty findings.

**Recomp-specific inputs:**
- [docs/app-context/chatgpt-context.md](../../app-context/chatgpt-context.md) — product vision, positioning, messaging hierarchy (used throughout).
- [Recomp on the App Store](https://apps.apple.com/us/app/recomp-your-physique-tracker/id6760444125) — live product.

---

## 18. One-Page Cheat Sheet

For quick reference. Print this. Everything else in this doc is elaboration.

**Promise:** See the progress you've been working for.
**Persona:** The science-based lifter. Already motivated. Wants proof, not motivation.
**Competitor:** The user's own iPhone camera roll — 800 disorganized physique photos. Star competitor. Weight-scattered-across-Notes/Excel/Apple Health is supplemental to the same problem, worth naming for recognition but never dethroning the camera-roll frame.
**Convergence:** Recomp's job is to unlock the value in the camera roll first, and pull in supporting sources (weight, notes today; Apple HealthKit as direction) into one compare view. Anchored on the page by the §5 convergence diagram, camera roll dominant, other sources supporting. No "coming soon" feature block.
**Aha:** The compare view. Two photos, side by side, dated.
**Two flows:** (A) Import existing camera roll → instant compare — the first-customer flow. (B) Track from scratch → compare compounds in 3–6 weeks. Hero leans A; split-card catches B mid-page.
**Two page versions:** Pre-release (waitlist / request-access CTA; access-is-privilege reframe) → Release (App Store install CTA).
**Primary CTA (release):** Apple App Store badge. Above the fold. Repeated at final CTA. Nowhere else.
**Primary CTA (pre-release):** [Request early access]. Application-style. Honest scarcity ("42 spots left · reviewed in 48 hours").
**Tone:** Precise, understated, no motivational clichés. Closer to Moody than to StrongLifts.
**Design:** Both modes (system-following default). SF Pro. iOS blue accent. Graph-paper grid background (§12.1a) as signature — 40px squares, 5% opacity dark / 6% light, faded edges. Apple-native visual identity.
**Hero (release default):** V2 camera-roll headline + one-sentence mechanism subhead + Apple badge + compare view.
**Structure:** Hero → Problem → How it works → Two-flow split → Aha → Features → Social proof → FAQ → Final CTA.
**Social proof:** One dominant story (founder compare view — the *only* proof asset at pre-release) + ambient density signals (rating, install count) at release.
**Mobile:** First. Always. CTA above the fold. 44px touch targets. < 1.5MB page weight.
**Cut:** Streaks, workouts, macros, feed, social, sharing, email capture (post-launch), second CTA, generic-fitness aesthetics, isometric grids.
**Ship:** V2 headline first for release (camera-roll). Pre-V1 headline first for pre-release (reframe-explicit). A/B test hero visual, section order, and headline second.

---

*End of Phase 1 deep research. Next: [02. Landing Page Generation Prompt](02-landing-page-generation-prompt.md).*
