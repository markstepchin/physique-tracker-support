# Recomp Landing Page — Generated Structure & Copy (Track variant)

**Phase:** [1 — Deep Research & Strategy](../README.md)
**Source prompt:** [02-landing-page-generation-prompt.md](02-landing-page-generation-prompt.md)
**Variant:** Track-focused, release

This is the **forward-tracking, release** variant of the Recomp landing page. The thesis: the visitor either hasn't started yet or has started twice and stopped; a small weekly ritual (~30 seconds, one prompt on their phone) becomes, over months, the visual record of their training — and the **weekly reminder** is the first-class feature that turns intention into a habit. The app is on the App Store; the Apple "Download on the App Store" badge is the CTA everywhere. Every section provides purpose, full ship-ready copy, visual guidance, CTA placement, and implementation notes citing the deep research doc.

Global design constants (apply to every section unless otherwise noted):

- Graph-paper grid runs continuously beneath the whole page as a foundational background layer (40px squares, `rgba(255,255,255,0.05)` on `#0A0A0B` in dark mode; `rgba(0,0,0,0.06)` on `#FAFAF9` in light mode; 24px squares on mobile). Sections either sit transparently over the grid, layer as elevated cards over it, or (final CTA only) cover it with a full-bleed accent.
- Both modes ship, system-following by default. SF Pro type stack. Apple iOS blue (`#0A84FF`) as accent.
- Primary CTA is the official Apple "Download on the App Store" badge — never a custom button.
- Mobile-first: CTA visible above the fold on iPhone 12 (390×844), 44px touch targets, page weight under 1.5MB.

---

## Section 1 — Hero (Above the Fold)

**Purpose.** In roughly six seconds, land the ritual promise — *one photo a week, and in six months you'll see the difference* — and show the reminder that makes the ritual actually happen. The badge lets them install now.

**Full copy.**

- **H1 (headline):**
  > One check-in a week. In six months, you'll see the difference.
- **Subhead:**
  > Recomp reminds you at the same time each week, saves the photo, and shows you the compare that day-to-day view hides.
- **Primary CTA:** the Apple "Download on the App Store" badge.
- **Micro-copy under the CTA:**
  > Free to start · One photo, one prompt, one tap
- **Persona-marker fallback** (use in place of the density signal until real App Store ratings accumulate):
  > Free to start · Made by a lifter, for lifters

**Visual guidance.**

- Pattern B (stacked with dominant demo). Copy stack top-centered; a single iPhone device frame directly below, straight-on, current-generation hardware (thin bezels, Dynamic Island).
- Inside the device: the **compare view** — two real photos of the founder taken 8–12 weeks apart, dated, with weight overlays as the app renders them. A hint of app chrome so the visitor recognises this is *the app*, not just two photos.
- **Layer a notification chip on the phone frame** — an iOS-style banner near the top: **Recomp · Time for your check-in · Sunday 9:00 AM** — so the reminder feature is visible from second one and the visitor understands the loop before scrolling.
- Optional motion: a subtle slider affordance that reveals photo B beneath photo A. Static is fine; motion earns its place only if it teaches the compare interaction.
- On dark backgrounds, ambient light glow behind the phone rather than a drop shadow.
- The app's internal alignment grid on the compare view should visually rhyme with the page grid.

**CTA placement.** One CTA. Centered under the copy stack on mobile; centered above the device on desktop. The badge is the only interactive element above the fold — no secondary "Watch demo" or "Learn more."

**Implementation notes.**

- H1 was drafted from three candidates: (a) *"The weekly check-in that turns training into a visible record."* (b) *"One check-in a week. In six months, you'll see the difference."* (c) *"Take one photo a week. Recomp does the rest."* Ship (b) — the specificity of *"six months"* + *"see the difference"* is the payoff the persona is quietly running the math on. Queue (c) as the first A/B test for cold TikTok traffic; queue (a) for warmer paid channels.
- Subhead names the ritual + the reminder in one sentence. Two clauses: what it does / what you get. No adjective inflation — per research: "beautiful / powerful / revolutionary" all get cut.
- Never say the word "app" in H1 — per research: they know it's an app.
- The notification chip is a shipping requirement, not a nice-to-have — per the variant spec: the reminder is the *reason the loop works*, so it earns visibility in the hero visual.
- On mobile, the App Store badge must sit inside the iPhone 12 viewport without scroll — verify explicitly.
- Compare view must be the founder's own — per research: it's the only credible visual proof at launch and it doubles as authentic anti-stock-photo signal.
- Attention Ratio 1:1 — no nav, or nav reduced to logo + App Store badge + mode toggle only.

---

## Section 2 — Problem / Agitation

**Purpose.** Recognition — but the specific pain here is not "my camera roll is chaos" (that's the import variant's problem). It's *the day-to-day-perception problem*: you see yourself every day so change is invisible; without a system, you'll never see the change you're working for.

**Full copy.**

- **Section H2:**
  > You see yourself every day. So the person in the mirror never seems to change.
- **Body (four beats, ~115 words):**
  > Progress at your training age is measured in millimetres a week. You can't see that in the mirror at 7am. You can't feel it in a T-shirt. So the diet feels like it isn't working, and the bulk feels like it's all fat, and the training block feels like nothing is happening — even when everything is.
  >
  > Meanwhile the record of your progress doesn't exist anywhere. Not because you're lazy — because there's no system. You mean to take a photo. You forget. You take one, and it goes into the camera roll with the rest, and you never see it again.
  >
  > Doubt is what ends cuts, bulks, and programs early. Not lack of discipline. Not lack of effort.
- **Handoff line into Section 3:**
  > **Recomp is the system: one prompt a week, one photo, one tap. Six months of that, and the change is undeniable.**
- **Diagram caption (below the visual):**
  > Without a system, the record doesn't exist. Recomp is the system — the reminder, the timeline, the compare.

**Visual guidance.** A tuned version of the **convergence diagram** (Option C from the research), reframed as *"without a system, the record scatters"*:

- Left column: a photo-grid mockup styled as iOS Photos — the camera-roll fragment stays, because it's still true, but it's not weighted as heavily as in the import variant. Sized to hold ~40–45% of the left-column visual weight.
- Below it: two smaller supporting cards — an Apple Notes cream card with weight scribbles that stops abruptly mid-month, and an Apple Health weight chart with a visible gap where the tracking stopped.
- A subtle thin left-to-right arrow ending in a small chevron.
- Right: the Recomp compare view panel — the largest single element on the right, roughly 40–45% of the composition's width. Shows photos, dates, weight overlays, and — small but visible — the same **Recomp · Time for your check-in** banner from the hero, anchoring the reminder-is-the-mechanism story.
- The three source mockups on the left should feel *abandoned* — the diversity is still the argument, but the specific detail is that each one trails off, un-updated.
- Mobile: stack vertically. Camera-roll fragment first, then Notes + Apple Health row, then a downward arrow, then the Recomp panel with the reminder banner. Never compress the whole diagram horizontally.

**CTA placement.** No CTA in this section. Momentum carries the visitor into Section 3.

**Implementation notes.**

- The dominant beat is *perception + habit*, not *chaos*. The camera-roll fragment stays in the diagram because it's honest — but it's one fragment of three, not the star. Per the variant spec: don't accidentally write the import variant's problem section.
- The Apple Health "in progress" tag stays on the compare-view panel in the diagram — per research: it's the only place the future HealthKit direction is stated on the page.
- Tone is respect, not fear. No "Are you wasting years of gym time?" — per research: the persona bounces on fear-based framing.
- No stock photo of a discouraged person in a mirror. No motivational quote. No fabricated stats.

---

## Section 3 — Solution / Benefits

**Purpose.** Confirm — not teach — the visitor that the ritual is short, obvious, and doesn't ask them to change what they already do. Emphasise the weekly reminder as the mechanism. Then show the aha visually and hand them a single starting flow oriented at tonight. Then show the supporting feature set with the reminder promoted to #1.

This section runs in four sub-blocks: **3a How it works** → **3b Take your first check-in tonight** → **3c The aha moment** → **3d Everything else it does**.

### 3a — How it works

**Full copy.**

- **H2:**
  > Three steps. That's the whole loop.
- **Three steps:**
  1. **Take a weekly check-in.**
     Same pose, same light, same time of day. Recomp reminds you at your usual time — silent by default, easy to reschedule.
  2. **Recomp builds your timeline.**
     Every check-in slots in by date, next to the last one, next to the one from three months ago.
  3. **Compare, side by side.**
     Pick any two check-ins. See the actual difference — the one your day-to-day view hides.
- **Closer (right below the three steps):**
  > That's it. No streaks. No workouts to log. No macros to enter. Just the prompt, the photo, and the compare.

**Visual guidance.** Horizontal three-column layout on desktop; each column shows a numbered step, a small screenshot, and the one-line description. Step 1's screenshot shows the notification banner and the check-in capture flow (this is the differentiator vs. the release version, which weighted step 3 alone). Step 3's screenshot still gets the largest visual weight — the compare is the payoff — but step 1 gets a real supporting screenshot, not a placeholder. Collapses to a vertical scroll on mobile.

**Implementation notes.** Never describe the app's mechanics ("Recomp uses AI to…") — per research: steps describe the user's action, not the app's. The reminder detail in step 1 is load-bearing — per the variant spec: the reminder is *the* first-class feature; naming its behaviour ("silent by default, easy to reschedule") pre-answers the biggest FAQ objection right in the loop. The closer is not optional — it does the entire "we're not another generic fitness tracker" work of the page in one sentence, and adds the anti-streak reassurance ("no streaks") that this persona specifically wants to hear.

### 3b — Take your first check-in tonight (single card)

**Full copy.**

- **H3:**
  > Take your first check-in tonight.
- **Single card:**
  - **Title:** I'm starting fresh.
  - **Body:** Recomp builds the timeline from your first photo forward. Set the reminder for the same time next week. Compares get real in 3–6 weeks; they get undeniable by month three.
  - **CTA:** Apple "Download on the App Store" badge.
- **Small muted link below the card:**
  > Already have a library of photos? [Import them in one shot →](../import/)

**Visual guidance.** One elevated card centered on the section (layered over the grid; 16–24px corner radius; subtle border in dark mode, subtle shadow in light mode). On mobile, the card is full-width with generous internal padding. The muted "already have a library" link sits under the card in body-small type, secondary text colour — visible to the fit-but-wrong-flow visitor, quiet enough not to compete with the primary card's badge.

**Implementation notes.**

- The release version's two-card split is collapsed to one — per the variant spec: this page is for the forward-tracking flow. The muted link is the escape hatch for the visitor who happens to have a library and would be better served by the import page.
- The card's CTA feeds the same App Store link as the hero — per research: the value is recognition, not routing.
- Do not implement the muted link as a toggle/tab — per research: toggles hide half the value and the point here is to send a small minority elsewhere, not to negotiate the choice inline.

### 3c — The aha moment

**Full copy.**

- **H2:**
  > The moment you actually see it.
- **Caption below the compare:**
  > 150 check-ins. Two years of showing up. Started with one photo, one Sunday morning.
  > — Mark, founder of Recomp

**Visual guidance.** One full-width compare view — the founder's own transformation, real weight delta, real timeline (e.g. "14 weeks"), dated. Photos land on the page as photos, not inside a device frame — this is the emotional peak; the phone chrome is a distraction here.

**Implementation notes.** This is the emotional peak of the page — per research: if a visitor takes only one image away, this should be it. The caption is rewritten to link the compare back to a *first* check-in — per the variant spec: the founder's 150 didn't start as 150; it started as 1, and that's the visitor's next step. Full-bleed accent treatment is allowed here as one of the ≤2 accent moments on the page (final CTA gets the other), but a transparent grid treatment also works and is safer.

### 3d — Everything else it does (feature strip)

**Full copy.**

- **H2:**
  > Everything else your physique tracker should be.
- **Feature blocks** (alternating rows; ship four for launch — 1, 2, 3, 4 below — add 5 later if the page has room):
  1. **Weekly reminders that respect your time.**
     One prompt, at a time you pick. Silent by default. Change it, reschedule it, or turn it off entirely — the system still works, you'll just take fewer check-ins.
  2. **Compare any two check-ins.**
     Pick any two dates. Side by side, same scale, honest.
  3. **A real timeline, not a photo grid.**
     Every check-in in one scroll — with dates, weights, and notes.
  4. **Your photos never leave your phone unless you say so.**
     No feed. No sharing. Nothing public. Just your own record.
  5. **Import the photos you already have.**
     Group your progress shots into an iOS Photos album and import the whole album in one tap. Optional, and covered in more detail on the [import version of this page](../import/).
  6. *(hold for later)* **Weight and notes when you want them. Never required.**
     Track what matters to you. Ignore what doesn't.

**Visual guidance.** Alternating full-width feature rows. Each row: real screenshot on one side (alternating sides between rows), copy on the other. Screenshots are actual product captures at retina resolution — same phone frame, consistent status bar. The feature #1 (reminders) screenshot shows the notification permission prompt + a settings pane for cadence — the mechanism is the message. Two-column grid is the fallback if vertical space is tight.

**Implementation notes.** Order is reworked for the variant — per the spec: **reminders promoted to #1** (the track variant's headline feature), compare stays #2, timeline #3, privacy #4. Import is retained but demoted to #5 with a link to the import variant, so the fit-but-wrong-flow visitor has a second escape hatch without derailing this page's thesis. Absence is a persuasion tool — per research: nothing here mentions streaks, workouts, calories, macros, social feeds, or friends; the persona notices what isn't there. No trademarked feature names ("PhysiqueSense™") — per research: persona will laugh.

---

## Section 4 — Social Proof & Trust

**Purpose.** Convert the mid-page moment of maximum consideration into permission to act, using one dominant, checkable story proof plus ambient density signals. On this variant, frame the founder proof around *consistency* — showing up once a week for two years — because that's what the ritual sells.

**Full copy.**

- **Density strip (top of section, one line, small type):**
  - **Launch week (persona-marker only):**
    > Made by a lifter, for lifters · Built on 150+ real check-ins · Free to start
  - **Once real ratings accumulate (swap in when honest):**
    > ★ 4.8 on the App Store · 5,000 lifters showing up weekly · Free to start
- **Section H2 (above the story proof block):**
  > Real check-ins. Real timelines. Real weeks of showing up.
- **Founder story proof (uses the same visual asset as Section 3c, but framed as proof rather than aha):**
  > **Two years of showing up. 150 check-ins. Started with one photo on a Sunday.**
  > I built Recomp because I couldn't find a tracker that respected the compare view — and because I needed the prompt as much as anyone. This is what mine looks like when the ritual actually holds.
  > — Mark, founder
- **User story proof slot (populate when you have consenting users — leave as a "coming from the beta" placeholder in the meantime; each user card holds):**
  - Name (first name + last initial, or handle).
  - Timeline (start → end date).
  - Weight or context ("cutting 200 → 180", "bulking 150 → 165", "post-injury comeback").
  - One-sentence quote about the *moment* of realisation, not the app itself, ideally referencing the ritual. E.g.:
    > "I didn't believe the diet was working until I hit compare at week eight."
  - The user's compare view, with consent, matched to the moment.

**Visual guidance.** The density strip is small, single-row, muted — it's ambient. Below it, one dominant story block: the founder compare view (full-bleed or elevated card) with the caption to its side on desktop, below on mobile. Any real user cards come in as an elevated-card row underneath (3 cards on desktop; single-column carousel on mobile).

**CTA placement.** No CTA in this section. Social proof is a permission event, not a conversion event — the visitor keeps scrolling to the differentiation section, then the FAQ, then the final CTA.

**Implementation notes.**

- One dominant story + ambient density — per research: this pattern outperforms the "wall of five-star screenshots" every consumer app defaults to.
- The founder caption is reframed around consistency ("showing up") rather than archive ("two years") — per the variant spec: this variant sells the ritual, not the retrospective.
- The user quote is about a moment of realisation, not an evaluation of the app — per research (Wiebe VoC): "I didn't believe the diet was working until I hit compare" outperforms "Best physique app ever."
- Never fabricate. Never round up. Never use "loved by thousands" — per research: the persona will smell it and the whole page loses credibility. Ship the star rating only when the real number lands and is defensible.
- Every founder / user photo has meaningful alt text ("Two-panel compare view: physique on the left dated April 2024, on the right dated July 2024. Weight: 195 lb → 182 lb.").

---

## Section 5 — Differentiation

**Purpose.** Give the persona the one-glance reason Recomp is not another generic fitness tracker, in the register they respect: understated, precise, and stated by omission as much as by claim. On this variant, add one explicit row about the ritual so the differentiation reinforces the page's thesis.

**Full copy.**

- **H2:**
  > Not a fitness tracker. A tracker for what fitness is for.
- **Lead paragraph:**
  > Recomp exists for one thing: to make the visual outcome of your training visible. Everything the app does builds toward the compare view. The weekly check-in is the mechanism. Everything the app *doesn't* do is a decision.
- **Two-column list — "What Recomp does / What Recomp doesn't do":**

  | What Recomp does | What Recomp doesn't do |
  | --- | --- |
  | A weekly ritual — one photo, one prompt | Demand daily engagement |
  | Compare any two dates, side by side, aligned | Log workouts, sets, reps |
  | Weekly check-ins with photo, weight, notes | Track macros or calories |
  | Remind you at your usual time, silently | Guilt you when you miss a week |
  | Keep everything on your phone by default | Award streaks, XP, or badges |
  | Rhyme with your training — precise, quiet, honest | Publish a feed, or sell you motivation |

- **Closing line (under the table):**
  > If you already track training, nutrition, and lifts elsewhere, Recomp is the piece those tools skip. The visible outcome, one week at a time.

**Visual guidance.** Two clean columns on desktop, stacked on mobile. The "does" column sits on the left in the accent colour's tint (very restrained — a 6% wash, no more); the "doesn't do" column sits neutral. Row separators are single hairline lines in the grid's opacity. Optional: a small alignment-grid device screenshot at the section head, echoing the app's internal grid and the page grid.

**CTA placement.** No CTA here. This section is a positioning statement; the visitor is being cleared to install, not pushed.

**Implementation notes.**

- The new top rows — "A weekly ritual, one photo, one prompt / Demand daily engagement" and "Remind you at your usual time, silently / Guilt you when you miss a week" — are the ritual thesis rendered as differentiation. Per the variant spec.
- Position against the persona's *category exhaustion*, not against named competitors — per research: naming Hevy / MacroFactor is beside the point; the real competitor is the "generic fitness app" category as a whole plus the *absence* of any system.
- Saying what Recomp *doesn't* do is the sharpest way to say what it *is* — per research (Laja): the omitted-feature list carries more of the differentiation load than any positive claim.
- Vocabulary is domain-native (recomp, cut, bulk are allowed as colour, never as forced jargon).
- No "vs. competitor" table with named products. No superlatives.

---

## Section 6 — FAQ (Addressing Potential Objections)

**Purpose.** Name the specific things stopping a persona-fit visitor from installing, defuse each in 2–4 sentences, and earn trust through honesty (about reminders, about the honest 3–6 week timeline, about pricing).

**Full copy.**

- **Section H2:**
  > Answers to what you're probably thinking.

- **Item 1 — Will the reminders be annoying?**
  > One a week, at a time you choose. Silent by default — no sound, no red badge count, no streak shaming. You can reschedule any week, change the cadence any time, or turn reminders off entirely and the app still works (you just take fewer check-ins). We don't send you back-to-training push notifications, and we don't email you at all after signup.

- **Item 2 — How long until I see meaningful change?**
  > Realistically: 3–6 weeks for the first compare that surprises you, three months for a compare that's undeniable, six months for the one you'll show people. The tool is designed to reward consistency, not to fake progress you haven't made. If you're only willing to try it for a week, that's not enough time for the mechanism to work.

- **Item 3 — What if I miss a week?**
  > It's fine. The timeline is date-based, not streak-based — a gap doesn't reset anything, and the compare view doesn't punish you for it. You just have one fewer data point. The point is the six-month arc, not any specific Sunday.

- **Item 4 — Isn't this just an iPhone album?**
  > An album is a folder. Recomp is a timeline. The difference is compare — being able to place any two dates side by side, aligned and dated, without hunting through months of photos. Try it once and the gap is obvious.

- **Item 5 — How do I make sure the compares are honest?**
  > Take check-ins at the same time of day (morning is best), in the same lighting, same pose. Recomp reminds you at your usual time and shows your most recent pose as a ghost overlay while you're setting up the new shot. The rest is on you — the tool doesn't fix bad inputs.

- **Item 6 — Do I have to track weight, workouts, or macros?**
  > No. Weight and notes are optional on every check-in. Workouts and macros aren't in Recomp at all — those tools exist and are good; Recomp handles the piece they skip.

- **Item 7 — How much does it cost?**
  > Free to start — your first check-ins cost nothing. Paid once you're serious, at less than the price of a month of gym coffee. The pricing is stated in-app before anything charges.

- **Item 8 — Where do my photos live? Are they private?**
  > On your phone. Recomp doesn't upload your photos to a server, doesn't share them anywhere, and doesn't publish a feed. If you back up to iCloud Photos, they go where your other photos go. Nothing else.

- **Item 9 — I already have photos — should I import them?**
  > You can, and it's worth doing once — you get a starting compare on day one instead of week six. That flow is covered in more depth on the [import version of this page](../import/). It's optional; the weekly ritual works either way.

- **Item 10 — I already use Hevy / MacroFactor / a spreadsheet. Do I need this?**
  > Probably yes, and for a different reason. Those tools track the inputs — the training, the food, the numbers. Recomp tracks the outcome — the physique itself, over time. It's the missing piece, not a replacement.

- **Item 11 — Is it just iOS?**
  > For now, yes. Recomp is built iOS-native — HealthKit, Photos, the Apple design system — because that's where our first users are. Android will come once the iOS product is where it needs to be.

**Visual guidance.** Expandable accordion, all items collapsed by default. Each row: question in body-large weight, expand chevron on the right. Expanded state reveals the answer in body copy with generous line height. Container is an elevated card layered over the grid.

**CTA placement.** No inline CTAs in the accordion. Below the FAQ, a small transitional line leading into the final CTA:
> Still on the fence? Take your first check-in tonight — the compare view at week six is what convinces you.

**Implementation notes.**

- Item 1 (reminders) is promoted to the top — per the variant spec: this is the persona's first and biggest objection to any app that sends notifications, and answering it in full ("silent by default, no streak shaming, we don't email you") is the whole trust play for the ritual.
- Item 2 (3–6 weeks / three months / six months) is the credibility play — per research (Laja): acknowledging a real tradeoff before the visitor thinks of it lifts trust more than any positive claim. This variant sharpens the release version's answer with the fuller arc (week six → month three → month six), because the visitor is being asked to commit to a *habit*, not a one-time import.
- Item 3 (missing a week) is new and load-bearing — per the variant spec: the anti-streak promise from Section 5 needs a concrete answer here, or the persona will assume it's still a "gamified" app under the hood.
- Item 9 (import) is retained as a short redirect — per the variant spec: don't drop the topic entirely, but keep it small and send the fit visitor to the right page.
- Do not pre-expand any answers — per research: pre-expanded FAQs create visual clutter and defeat the pattern.
- Do not invent objections. Register is flat and precise. No "Great question!" or "Absolutely!" — per research: register-breaks read as low-quality marketing.
- Every accordion row is keyboard-accessible with visible focus rings and `prefers-reduced-motion` respected.

---

## Section 7 — Final Call-to-Action

**Purpose.** The visitors who reach this section are the highest-intent segment on the page. Give them one clean, unmissable install path and the specific act ("take your first check-in tonight") that starts the ritual.

**Full copy.**

- **Section H2:**
  > See the progress you've been working for.
- **Supporting line:**
  > Free to start. Take your first check-in tonight.
- **Primary CTA:** Apple "Download on the App Store" badge, larger than the hero one, centered.
- **Optional density signal below the CTA (small type; ship only when the numbers are real and only if it hasn't already appeared in Section 4):**
  > ★ 4.8 · App Store · 5,000 lifters and counting

**Visual guidance.** Full-bleed accent section — a solid or very-slightly-tinted accent fill that covers the page grid completely (this is one of the ≤2 places on the page that earns this treatment). Copy centered. CTA centered. Optionally, one different compare view above the copy (a different transformation from the hero or the aha moment) so the visitor's last visual impression is a fresh proof point. On mobile, the CTA sits with generous padding — nothing else competes for the tap.

**CTA placement.** One CTA. Centered. No secondary link, no "Follow us on TikTok," no "Subscribe for updates" — per research: any non-install element at the final CTA is an exfiltration from the funnel.

**Implementation notes.**

- The word **tonight** is deliberate and is the whole point of this variant — per research (Wiebe): specificity of action converts general intent into a specific act. Do not soften it to "soon" or "today" or "when you're ready."
- Full-bleed accent is the only section where the grid is fully covered — per research: overusing full-bleed erodes the grid's foundational role.
- CTA copy is varied from the hero: hero says "Free to start · One photo, one prompt, one tap"; final says "Free to start. Take your first check-in tonight." Same badge, different framing.
- Do not put a pricing block or a "Compare plans" table here — per research: introduces last-minute cognitive load right when the visitor should be acting on emotion + evidence.
- If the founder compare has already appeared twice above, use a different transformation here or omit the visual — the CTA can stand alone.

---

## Section 8 — Footer (Minimal)

**Purpose.** Legal completeness, mode control, and identity — nothing else. Every non-legal link is a leak.

**Full copy.**

- **Left:** Recomp wordmark. Under it: `© 2026 Recomp. Made by a lifter.`
- **Center (or right on wider viewports):** three legal links:
  > Privacy · Terms · Contact
- **Right:** mode toggle (three states — System · Light · Dark).
- **Far right (small icons, muted colour):** optional social icons — App Store, X, TikTok, one Instagram or YouTube if used. Muted, small, no more than four.

**Visual guidance.** Single horizontal row on desktop, ~64px tall, with the graph-paper grid still faintly visible beneath. Stacks vertically on mobile with the wordmark on top, legal links in the middle row, mode toggle and socials on the bottom. Type is 13–14px, muted secondary text colour. No borders — the grid handles visual separation.

**CTA placement.** No CTA in the footer. Social icons live here so they don't compete anywhere upstream.

**Implementation notes.**

- Mode toggle persists to `localStorage` and defaults to `prefers-color-scheme` — per research: the persona expects mode-following.
- Legal links only — per research (Gardner Attention Ratio): no product links, no blog, no press page (unless press is truly ambient social proof), no "about us" (the founder story already lives in Section 4).
- Social icons are muted and small — per research: social follows are a leak; they belong here, not near a CTA, and never above it.
- Footer should never contain an email capture — per research: the App Store install is the whole funnel.

---

## Cross-cutting reminders (apply to every section above)

- **Attention Ratio 1:1.** One goal, one CTA type (Apple App Store badge). Vary the badge's surrounding copy across the page, never the badge itself.
- **Grid discipline.** Grid is continuous background. Sections either sit transparently over it, layer as elevated cards, or (final CTA only) full-bleed accent over it. At most two full-bleed accents per page.
- **The reminder is a first-class citizen.** It appears in the hero visual (notification chip), in the diagram (banner on the compare panel), as feature #1, and as FAQ #1. If it were removed from the page, the whole track thesis would collapse — the ritual doesn't hold without the prompt.
- **Mobile-first check per section.** CTA reachable, headline ≤ 6 words rendered lines, hero visual ≤ 45% of viewport height, 44px touch targets, no auto-zoom triggers on inputs.
- **Voice.** Precise, understated, no exclamation points, no motivational-quote energy. The person reading this hasn't started yet — or has started twice and stopped. The page's job is to make the ritual sound so small and so respected that they take a photo tonight. Still restrained. Still Moody's register, not StrongLifts'.
- **Specificity rule.** Every copy pass asks: "Can this be more specific?" Nine times out of ten the answer is yes ("in six months" > "over time"; "3–6 weeks" > "soon"; "one photo, one prompt, one tap" > "quick and easy"; "tonight" > "today").
- **Nothing fabricated.** No invented ratings, no rounded-up install counts, no fake testimonials, no stock photography. The persona detects all of it.
