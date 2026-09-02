# Recomp Landing Page — Generated Structure & Copy

**Phase:** [1 — Deep Research & Strategy](../README.md)
**Source prompt:** [02-landing-page-generation-prompt.md](02-landing-page-generation-prompt.md)

This is the finished landing page for the **release** version of Recomp (App Store install CTA). Every section provides purpose, full ship-ready copy, visual guidance, CTA placement, and implementation notes citing the deep research doc.

Global design constants (apply to every section unless otherwise noted):

- Graph-paper grid runs continuously beneath the whole page as a foundational background layer (40px squares, `rgba(255,255,255,0.05)` on `#0A0A0B` in dark mode; `rgba(0,0,0,0.06)` on `#FAFAF9` in light mode; 24px squares on mobile). Sections either sit transparently over the grid, layer as elevated cards over it, or (final CTA only) cover it with a full-bleed accent.
- Both modes ship, system-following by default. SF Pro type stack. Apple iOS blue (`#0A84FF`) as accent.
- Primary CTA is the official Apple "Download on the App Store" badge — never a custom button.
- Mobile-first: CTA visible above the fold on iPhone 12 (390×844), 44px touch targets, page weight under 1.5MB.

---

## Section 1 — Hero (Above the Fold)

**Purpose.** In roughly six seconds, land a promise the visitor already half-thinks, prove it with the compare view, and offer a one-tap install.

**Full copy.**

- **H1 (headline):**
  > You already have years of progress in your camera roll.
- **Subhead:**
  > Import a Photos album in one tap. Recomp dates them and lets you compare any two — side by side, honest.
- **Primary CTA:** the Apple "Download on the App Store" badge.
- **Micro-copy under the CTA:**
  > Free to start · Import your existing photos in seconds
- **Persona-marker fallback** (use in place of the density signal until real App Store ratings accumulate):
  > Free to start · Made by a lifter, for lifters

**Visual guidance.**

- Pattern B (stacked with dominant demo). Copy stack top-centered; a single iPhone device frame directly below, straight-on, current-generation hardware (thin bezels, Dynamic Island).
- Inside the device: the **compare view** — two real photos of the founder taken 8–12 weeks apart, dated, with weight overlays as the app renders them. A hint of app chrome so the visitor recognises this is *the app*, not just two photos.
- Optional motion: a subtle slider affordance that reveals photo B beneath photo A. Static is fine; motion earns its place only if it teaches the compare interaction.
- On dark backgrounds, ambient light glow behind the phone rather than a drop shadow.
- The app's internal alignment grid on the compare view should visually rhyme with the page grid.

**CTA placement.** One CTA. Centered under the copy stack on mobile; centered above the device on desktop. The badge is the only interactive element above the fold — no secondary "Watch demo" or "Learn more."

**Implementation notes.**

- Ship hero variant V2 (camera-roll-first) as the default — per research: matches Flow A, the dominant first-customer flow. V1 (outcome-first: "See the progress you've been working for.") is queued as the first A/B test, especially for cold TikTok traffic.
- The subhead is one sentence, two clauses (what it does / what you get). No adjective inflation — per research: "beautiful / powerful / revolutionary" all get cut.
- Never say the word "app" in H1 — per research: they know it's an app; that word wastes the most valuable eight words on the page.
- On mobile, the App Store badge must sit inside the iPhone 12 viewport without scroll — verify explicitly.
- Compare view must be the founder's own — per research: it's the only credible visual proof at launch and it doubles as authentic anti-stock-photo signal.
- Attention Ratio 1:1 — no nav, or nav reduced to logo + App Store badge + mode toggle only.

---

## Section 2 — Problem / Agitation

**Purpose.** Recognition. Show the visitor we know the specific version of the problem they have, then hand them off — without moralising — to the solution.

**Full copy.**

- **Section H2:**
  > You see yourself every day. So the person in the mirror never seems to change.
- **Body (four beats, ~105 words):**
  > Your progress photos are buried in your camera roll — hundreds of them, mixed in with screenshots, receipts, and last year's Halloween. Your weight and notes are somewhere else again — a Notes doc, an old spreadsheet, Apple Health. You've done the work. You just can't see it laid out.
  >
  > That's the moment the doubt starts. *Is the diet working? Am I actually gaining muscle? Was the deload worth it?* And doubt is what ends cuts, bulks, and programs early — not lack of discipline.
- **Handoff line into Section 3:**
  > **Recomp starts with the photos you already have. Weight and notes come along for the ride.**
- **Diagram caption (below the visual):**
  > Your camera roll has the evidence. Recomp lays it out — with your weight and notes alongside.

**Visual guidance.** The **convergence diagram** (Option C from the research):

- Left column, camera-roll dominant:
  - A photo-grid mockup styled as iOS Photos — a mix of physique shots, screenshots, receipts, a meme, a Halloween photo. Sized to hold roughly 50% of the left-column visual weight.
  - Below it, a smaller two-up row: an Apple Notes cream card with weight scribbles, and an Apple Health weight chart.
- A subtle thin left-to-right arrow ending in a small chevron.
- Right: the Recomp compare view panel — the largest single element on the right, roughly 40–45% of the composition's width. Shows photos + weight overlay + one line labelled "Apple Health" with a small "in progress" tag.
- The three source mockups on the left must feel visually distinct (each in its own app's design language) — the diversity is the argument.
- Mobile: stack vertically. Camera-roll full-width first, then a two-up row of Notes + Apple Health, then a downward arrow, then the Recomp panel. Never compress the whole diagram horizontally.

**CTA placement.** No CTA in this section. Momentum carries the visitor into Section 3.

**Implementation notes.**

- Camera-roll framing is load-bearing — per research: the camera roll is Recomp's primary competitor and the star of the convergence diagram; Notes/Excel/Apple Health are named as supporting fragments, never co-equal. Do not upgrade them to their own beats.
- The Apple Health "in progress" tag is the only place the future HealthKit direction is stated — per research: no "coming soon" feature block anywhere else on the page.
- Tone is respect, not fear. No "Are you wasting years of gym time?" — per research: the persona bounces on fear-based framing.
- No stock photo of a discouraged person in a mirror. No motivational quote. No fabricated stats.

---

## Section 3 — Solution / Benefits

**Purpose.** Confirm — not teach — the visitor that the loop is short, obvious, and doesn't ask them to change what they already do. Then show the aha visually and hand them a way to start whether they have a photo history or not. Then show the supporting feature set so the product reads as real and considered.

This section runs in four sub-blocks: **3a How it works** → **3b Two ways to start** → **3c The aha moment** → **3d Everything else it does**.

### 3a — How it works

**Full copy.**

- **H2:**
  > Three steps. That's the whole loop.
- **Three steps:**
  1. **Take a weekly check-in.**
     Same pose, same light, same time of day. Recomp reminds you.
  2. **Recomp builds your timeline.**
     Every check-in slots in by date, next to the last one, next to the one from three months ago.
  3. **Compare, side by side.**
     Pick any two check-ins. See the actual difference — the one your day-to-day view hides.
- **Closer (right below the three steps):**
  > That's it. No streaks. No workouts to log. No macros to enter. Just the photos, the timeline, and the comparison.

**Visual guidance.** Horizontal three-column layout on desktop; each column shows a numbered step, a small screenshot, and the one-line description. Step 3's screenshot is visually dominant (larger, or the only one in full colour while 1 and 2 sit slightly muted). Collapses to a vertical scroll on mobile.

**Implementation notes.** Never describe the app's mechanics ("Recomp uses AI to…") — per research: steps describe the user's action, not the app's. The closer is not optional — it does the entire "we're not another generic fitness tracker" work of the page in one sentence. Historical import belongs in the feature strip below, not as a step here — per research: introducing it here complicates the loop.

### 3b — Two ways to start (split card)

**Full copy.**

- **H3:**
  > Two ways to start.
- **Left card:**
  - **Title:** I've been taking photos.
  - **Body:** Group your progress photos into an iOS Photos album and import the whole album in one tap. Recomp dates them and hands you the compare — in minutes.
  - **CTA:** Apple "Download on the App Store" badge.
- **Right card:**
  - **Title:** I'm starting fresh.
  - **Body:** Take your first check-in tonight. Recomp builds the timeline from your first photo forward. Compares get powerful in 3–6 weeks.
  - **CTA:** Apple "Download on the App Store" badge.

**Visual guidance.** Two elevated cards side-by-side on desktop (layered over the grid; 16–24px corner radius; subtle border in dark mode, subtle shadow in light mode). Stacked vertically on mobile. Each card has room for the title, the two-sentence body, and the badge.

**Implementation notes.** Both cards feed the same App Store link — per research: the value is recognition, not routing. Do not implement this as a toggle/tab pattern — per research: toggles hide half the value from every visitor.

### 3c — The aha moment

**Full copy.**

- **H2:**
  > The moment you actually see it.
- **Caption below the compare:**
  > 150 check-ins. Two years of lifting. Here's what the compare view shows.
  > — Mark, founder of Recomp

**Visual guidance.** One full-width compare view — the founder's own transformation, real weight delta, real timeline (e.g. "14 weeks"), dated. Photos land on the page as photos, not inside a device frame — this is the emotional peak; the phone chrome is a distraction here.

**Implementation notes.** This is the emotional peak of the page — per research: if a visitor takes only one image away, this should be it. Full-bleed accent treatment is allowed here as one of the ≤2 accent moments on the page (final CTA gets the other), but a transparent grid treatment also works and is safer. Compare view is a different transformation from the one used in the hero, or the same shot at a different crop — never a stock or generic image.

### 3d — Everything else it does (feature strip)

**Full copy.**

- **H2:**
  > Everything else your physique tracker should be.
- **Feature blocks** (alternating rows; ship four for launch — 1, 2, 3, 4 below — add 5 and 6 later if the page has room):
  1. **Compare any two check-ins.**
     Pick any two dates. Side by side, same scale, honest.
  2. **Import the photos you already have.**
     Group your progress shots into an iOS Photos album, then bring the whole album into Recomp in one tap. Or pick photos one at a time.
  3. **A real timeline, not a photo grid.**
     Every check-in in one scroll — with dates, weights, and notes.
  4. **Your photos never leave your phone unless you say so.**
     No feed. No sharing. Nothing public. Just your own record.
  5. *(hold for later)* **One check-in a week. That's the whole habit.**
     A quick photo, a weight, a note. Recomp reminds you at your usual time.
  6. *(hold for later)* **Weight and notes when you want them. Never required.**
     Track what matters to you. Ignore what doesn't.

**Visual guidance.** Alternating full-width feature rows. Each row: real screenshot on one side (alternating sides between rows), copy on the other. Screenshots are actual product captures at retina resolution — same phone frame, consistent status bar. Two-column grid is the fallback if vertical space is tight.

**Implementation notes.** Order matters — per research: compare view first because it's the anchor, historical import second because it's the highest-leverage acquisition feature, privacy last because it's the closing objection killer. Absence is a persuasion tool — per research: nothing here mentions streaks, workouts, calories, macros, social feeds, or friends; the persona notices what isn't there. No trademarked feature names ("PhysiqueSense™") — per research: persona will laugh.

---

## Section 4 — Social Proof & Trust

**Purpose.** Convert the mid-page moment of maximum consideration into permission to act, using one dominant, checkable story proof plus ambient density signals.

**Full copy.**

- **Density strip (top of section, one line, small type):**
  - **Launch week (persona-marker only):**
    > Made by a lifter, for lifters · Built on 150+ real check-ins · Free to start
  - **Once real ratings accumulate (swap in when honest):**
    > ★ 4.8 on the App Store · 5,000 lifters tracking · Free to start
- **Section H2 (above the story proof block):**
  > Real check-ins. Real timelines.
- **Founder story proof (uses the same visual asset as Section 3c, but framed as proof rather than aha):**
  > **Two years. 150 check-ins. One compare view.**
  > I built Recomp because I couldn't find a tracker that respected the compare view. This is what mine looks like.
  > — Mark, founder
- **User story proof slot (populate when you have consenting users — leave as a "coming from the beta" placeholder in the meantime; each user card holds):**
  - Name (first name + last initial, or handle).
  - Timeline (start → end date).
  - Weight or context ("cutting 200 → 180", "bulking 150 → 165", "post-injury comeback").
  - One-sentence quote about the *moment* of realisation, not the app itself. E.g.:
    > "I didn't believe the diet was working until I hit compare."
  - The user's compare view, with consent, matched to the moment.

**Visual guidance.** The density strip is small, single-row, muted — it's ambient. Below it, one dominant story block: the founder compare view (full-bleed or elevated card) with the caption to its side on desktop, below on mobile. Any real user cards come in as an elevated-card row underneath (3 cards on desktop; single-column carousel on mobile).

**CTA placement.** No CTA in this section. Social proof is a permission event, not a conversion event — the visitor keeps scrolling to the differentiation section, then the FAQ, then the final CTA.

**Implementation notes.**

- One dominant story + ambient density — per research: this pattern outperforms the "wall of five-star screenshots" every consumer app defaults to.
- The user quote is about a moment of realisation, not an evaluation of the app — per research (Wiebe VoC): "I didn't believe the diet was working until I hit compare" outperforms "Best physique app ever."
- Never fabricate. Never round up. Never use "loved by thousands" — per research: the persona will smell it and the whole page loses credibility.
- Every founder / user photo has meaningful alt text ("Two-panel compare view: physique on the left dated April 2024, on the right dated July 2024. Weight: 195 lb → 182 lb.").

---

## Section 5 — Differentiation

**Purpose.** Give the persona the one-glance reason Recomp is not another generic fitness tracker, in the register they respect: understated, precise, and stated by omission as much as by claim.

**Full copy.**

- **H2:**
  > Not a fitness tracker. A tracker for what fitness is for.
- **Lead paragraph:**
  > Recomp exists for one thing: to make the visual outcome of your training visible. Everything the app does builds toward the compare view. Everything it *doesn't* do is a decision.
- **Two-column list — "What Recomp does / What Recomp doesn't do":**

  | What Recomp does | What Recomp doesn't do |
  | --- | --- |
  | Turn your existing photos into a timeline | Log workouts, sets, reps |
  | Compare any two dates, side by side, aligned | Track macros or calories |
  | Weekly check-ins with photo, weight, notes | Award streaks, XP, or badges |
  | Keep everything on your phone by default | Publish a feed, or add friends |
  | Rhyme with your training — precise, quiet, honest | Sell you motivation |

- **Closing line (under the table):**
  > If you already track training, nutrition, and lifts elsewhere, Recomp is the piece those tools skip. The visible outcome.

**Visual guidance.** Two clean columns on desktop, stacked on mobile. The "does" column sits on the left in the accent colour's tint (very restrained — a 6% wash, no more); the "doesn't do" column sits neutral. Row separators are single hairline lines in the grid's opacity. Optional: a small alignment-grid device screenshot at the section head, echoing the app's internal grid and the page grid.

**CTA placement.** No CTA here. This section is a positioning statement; the visitor is being cleared to install, not pushed.

**Implementation notes.**

- Position against the persona's *category exhaustion*, not against named competitors — per research: naming Hevy / MacroFactor is beside the point; the real competitor is the camera roll and the "generic fitness app" category as a whole.
- Saying what Recomp *doesn't* do is the sharpest way to say what it *is* — per research (Laja): the omitted-feature list carries more of the differentiation load than any positive claim.
- Vocabulary is domain-native (recomp, cut, bulk are allowed as colour, never as forced jargon) — per research: the persona hears themselves in it, non-persona readers still parse the sentence.
- No "vs. competitor" table with named products. No superlatives.

---

## Section 6 — FAQ (Addressing Potential Objections)

**Purpose.** Name the specific things stopping a persona-fit visitor from installing, defuse each in 2–4 sentences, and earn trust through honesty (about pricing, about the honest 3–6 week timeline, about what the app can and can't do).

**Full copy.**

- **Section H2:**
  > Answers to what you're probably thinking.

- **Item 1 — Isn't this just an iPhone album?**
  > An album is a folder. Recomp is a timeline. The difference is compare — being able to place any two dates side by side, aligned and dated, without hunting through months of photos. Try it once and the gap is obvious.

- **Item 2 — How do I make sure the compares are honest?**
  > Take check-ins at the same time of day (morning is best), in the same lighting, same pose. Recomp reminds you at your usual time and shows your most recent pose as a ghost overlay while you're setting up the new shot. The rest is on you — the tool doesn't fix bad inputs.

- **Item 3 — Do I have to track weight, workouts, or macros?**
  > No. Weight and notes are optional on every check-in. Workouts and macros aren't in Recomp at all — those tools exist and are good; Recomp handles the piece they skip.

- **Item 4 — How much does it cost?**
  > Free to start — your first check-ins and imports cost nothing. Paid once you're serious, at less than the price of a month of gym coffee. The pricing is stated in-app before anything charges.

- **Item 5 — Where do my photos live? Are they private?**
  > On your phone. Recomp doesn't upload your photos to a server, doesn't share them anywhere, and doesn't publish a feed. If you back up to iCloud Photos, they go where your other photos go. Nothing else.

- **Item 6 — I don't have years of photos yet. Does this still work?**
  > Start now. Recomp gets more powerful every week. Realistically, you'll see the first meaningful compare in 3–6 weeks. The tool is designed to reward consistency, not to fake progress you haven't made.

- **Item 7 — I already use Hevy / MacroFactor / a spreadsheet. Do I need this?**
  > Probably yes, and for a different reason. Those tools track the inputs — the training, the food, the numbers. Recomp tracks the outcome — the physique itself, over time. It's the missing piece, not a replacement.

- **Item 8 — Is it just iOS?**
  > For now, yes. Recomp is built iOS-native — HealthKit, Photos, the Apple design system — because that's where our first users are. Android will come once the iOS product is where it needs to be.

**Visual guidance.** Expandable accordion, all items collapsed by default. Each row: question in body-large weight, expand chevron on the right. Expanded state reveals the answer in body copy with generous line height. Container is an elevated card layered over the grid.

**CTA placement.** No inline CTAs in the accordion. Below the FAQ, a small transitional line leading into the final CTA:
> Still on the fence? Take your first check-in tonight — the compare view is what convinces you.

**Implementation notes.**

- Do not pre-expand any answers — per research: pre-expanded FAQs create visual clutter and defeat the pattern.
- Do not invent objections — per research: inventing them creates them. Every item on this list came from the research doc's known-objection set.
- Answer 4 (pricing) states pricing plainly, in the FAQ, not right above the CTA — per research: pricing at the CTA introduces last-minute cognitive load.
- Answer 6 (3–6 weeks) is the credibility play — per research (Laja): acknowledging a real tradeoff before the visitor thinks of it lifts trust more than any positive claim.
- Register is flat and precise. No "Great question!" or "Absolutely!" — per research: register-breaks read as low-quality marketing.
- Every accordion row is keyboard-accessible with visible focus rings and `prefers-reduced-motion` respected.

---

## Section 7 — Final Call-to-Action

**Purpose.** The visitors who reach this section are the highest-intent segment on the page. Give them one clean, unmissable install path and nothing to trip on.

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

- The word "tonight" is deliberate — per research (Wiebe): specificity of action converts general intent into a specific act.
- Full-bleed accent is the only section where the grid is fully covered — per research: overusing full-bleed erodes the grid's foundational role.
- CTA copy is varied from the hero: hero says "Free to start · Import your existing photos in seconds"; final says "Free to start. Take your first check-in tonight." Same badge, different framing.
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
- **Mobile-first check per section.** CTA reachable, headline ≤ 6 words rendered lines, hero visual ≤ 45% of viewport height, 44px touch targets, no auto-zoom triggers on inputs.
- **Voice.** Precise, understated, no exclamation points, no motivational-quote energy. Closer to Moody's register than to StrongLifts'. Uses "recomp / cut / bulk / progressive overload" as domain colour, never as forced jargon. Passes the grandmother test for marketing terms and the persona test for domain terms.
- **Specificity rule.** Every copy pass asks: "Can this be more specific?" Nine times out of ten the answer is yes ("years of progress" > "lots of progress"; "3–6 weeks" > "soon"; "150 check-ins" > "a lot of data").
- **Nothing fabricated.** No invented ratings, no rounded-up install counts, no fake testimonials, no stock photography. The persona detects all of it.
