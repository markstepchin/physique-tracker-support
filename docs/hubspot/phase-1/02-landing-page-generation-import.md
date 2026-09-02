# Recomp Landing Page — Generated Structure & Copy (Import variant)

**Phase:** [1 — Deep Research & Strategy](../README.md)
**Source prompt:** [02-landing-page-generation-prompt.md](02-landing-page-generation-prompt.md)
**Variant:** Import-focused, pre-release

This is the **import-forward, pre-release** variant of the Recomp landing page. The thesis: the visitor already has hundreds or thousands of physique photos scattered in their camera roll; Recomp turns that pile into a coherent, comparable, dated physique history in minutes. Because Recomp is not yet on the App Store, every install CTA is replaced with an email waitlist / early access capture — never an App Store badge. Every section provides purpose, full ship-ready copy, visual guidance, CTA placement, and implementation notes citing the deep research doc.

Global design constants (apply to every section unless otherwise noted):

- Graph-paper grid runs continuously beneath the whole page as a foundational background layer (40px squares, `rgba(255,255,255,0.05)` on `#0A0A0B` in dark mode; `rgba(0,0,0,0.06)` on `#FAFAF9` in light mode; 24px squares on mobile). Sections either sit transparently over the grid, layer as elevated cards over it, or (final CTA only) cover it with a full-bleed accent.
- Both modes ship, system-following by default. SF Pro type stack. Apple iOS blue (`#0A84FF`) as accent.
- **Primary CTA is a waitlist email capture** — a single email input + a button, or a "Join the waitlist" button that opens one. No Apple "Download on the App Store" badge appears anywhere on this page (the app is not yet on the App Store). Button labels vary across the page so no two CTAs read identical: **Get early access** · **Notify me at launch** · **Join the waitlist** · **Send me the link when it drops**.
- Mobile-first: waitlist form visible above the fold on iPhone 12 (390×844), 44px touch targets, email input uses `type="email"` and `inputmode="email"` with `autocomplete="email"`, page weight under 1.5MB.

---

## Section 1 — Hero (Above the Fold)

**Purpose.** In roughly six seconds, land a promise the visitor already half-thinks — *my camera roll is quietly the record of my training* — prove it with the compare view, and offer a one-field waitlist signup.

**Full copy.**

- **H1 (headline):**
  > You already have years of progress in your camera roll.
- **Subhead:**
  > Point Recomp at your camera roll. It finds your physique photos, dates them, aligns them, and hands you a compare view of two years of work — in minutes.
- **Primary CTA:** waitlist email capture. Single email field + button labeled **Get early access**.
- **Micro-copy under the CTA:**
  > Early access opens in weeks · Import your camera roll first · One email at launch, then nothing.
- **Persona-marker fallback below the micro-copy:**
  > Made by a lifter, for lifters · Built on 150+ real check-ins

**Visual guidance.**

- Pattern B (stacked with dominant demo). Copy stack top-centered; a single iPhone device frame directly below, straight-on, current-generation hardware (thin bezels, Dynamic Island).
- Inside the device: the **compare view** — two real photos of the founder pulled from his camera roll, taken 8–12 weeks apart, dated, with weight overlays as the app renders them. A hint of app chrome so the visitor recognises this is *the app*, not just two photos.
- Optional motion: a subtle slider affordance that reveals photo B beneath photo A. Static is fine; motion earns its place only if it teaches the compare interaction.
- On dark backgrounds, ambient light glow behind the phone rather than a drop shadow.
- The app's internal alignment grid on the compare view should visually rhyme with the page grid.
- Consider a small ghost of a Photos-app grid behind or above the phone, half-faded, so the visual whisper is "this pile becomes that compare."

**CTA placement.** One CTA. The waitlist form (single email field + button) sits centered under the copy stack on mobile; centered above the device on desktop. The form is the only interactive element above the fold — no secondary "Watch demo" or "Learn more."

**Implementation notes.**

- Ship this hero as the default — per research: matches Flow A, the dominant first-customer flow, and the import angle *is* Flow A stripped of its forward-tracking half.
- The subhead is one sentence, two clauses (what it does / what you get). No adjective inflation — per research: "beautiful / powerful / revolutionary" all get cut.
- Never say the word "app" in H1 — per research: they know it's an app; that word wastes the most valuable eight words on the page.
- On mobile, the email input + button must sit inside the iPhone 12 viewport without scroll — verify explicitly.
- Email field is `type="email"`, `inputmode="email"`, `autocomplete="email"`, single field only. No name, no "how did you hear about us," no marketing checkbox — the whole point of a pre-release capture is friction ≈ zero.
- Compare view must be the founder's own — per research: it's the only credible visual proof at pre-release and it doubles as authentic anti-stock-photo signal.
- Attention Ratio 1:1 — no nav, or nav reduced to logo + waitlist button + mode toggle only.

---

## Section 2 — Problem / Agitation

**Purpose.** Recognition, sharpened to one specific pain: *the camera roll has the evidence, and I can't read it.* Show the visitor we know the specific version of the problem they have, then hand them off — without moralising — to the import solution.

**Full copy.**

- **Section H2:**
  > The evidence is already on your phone. You just can't read it.
- **Body (four beats, ~110 words):**
  > Your progress photos are buried in your camera roll — hundreds of them, sometimes thousands, mixed in with screenshots, receipts, and last year's Halloween. April is somewhere near a boarding pass. October is next to a meme. The physique shot from the morning after your last deload is three swipes past a photo of your dog.
  >
  > You've done the work. The record of it is right there in your hand. You just can't lay it out. And what you can't lay out, you can't see — so the doubt starts. *Is the diet working? Was the cut worth it? Did I actually gain anything back?* Doubt is what ends programs early. Not lack of discipline.
- **Handoff line into Section 3:**
  > **Recomp reads the record you already built. Point it at your camera roll and it does the rest.**
- **Diagram caption (below the visual):**
  > Your camera roll has the evidence. Recomp finds it, dates it, and lays it out.

**Visual guidance.** A weighted version of the **convergence diagram** (Option C from the research), tipped even further toward the camera-roll fragment:

- Left column, camera-roll dominant: a photo-grid mockup styled as iOS Photos — a mix of physique shots, screenshots, receipts, a meme, a Halloween photo. Sized to hold roughly 70–75% of the left-column visual weight (up from 50% in the release version).
- Below it, a much smaller supporting row: an Apple Notes cream card with weight scribbles, and a small spreadsheet fragment. Kept present so the "fragments" story is honest, but visibly de-weighted.
- A subtle thin left-to-right arrow ending in a small chevron.
- Right: the Recomp compare view panel — the largest single element on the right, roughly 40–45% of the composition's width. Shows photos, dates, and weight overlays as they'd appear post-import.
- The camera-roll mockup must feel unmistakably like Photos — the visual asymmetry between the noisy grid on the left and the ordered compare on the right is the whole argument.
- Mobile: stack vertically. Camera-roll full-width first, then the small Notes + spreadsheet row, then a downward arrow, then the Recomp panel. Never compress the whole diagram horizontally.

**CTA placement.** No CTA in this section. Momentum carries the visitor into Section 3.

**Implementation notes.**

- Camera-roll framing is now single-competitor — per research: the camera roll is Recomp's primary competitor and, in the import variant, essentially the only one worth naming. Notes / spreadsheet stay as small fragments so the visual doesn't feel dishonest, but they don't get their own beats.
- **Cut the Apple Health "in progress" tag.** Per the variant spec: the release version's HealthKit hint distracts from the import story at pre-release. Save it for the release page.
- Tone is respect, not fear. No "Are you wasting years of gym time?" — per research: the persona bounces on fear-based framing.
- No stock photo of a discouraged person in a mirror. No motivational quote. No fabricated stats.

---

## Section 3 — Solution / Benefits

**Purpose.** Confirm — not teach — the visitor that the import loop is short, obvious, and delivers value inside a single sitting. Then show the aha visually and hand them a way to start that assumes they already have a library. Then show the supporting feature set with import promoted to the top.

This section runs in four sub-blocks: **3a How it works** → **3b Bring your camera roll** → **3c The aha moment** → **3d Everything else it does**.

### 3a — How it works

**Full copy.**

- **H2:**
  > Three steps. That's the whole import.
- **Three steps:**
  1. **Point Recomp at your camera roll.**
     Grant photo access. Recomp does the reading — nothing gets included until you confirm.
  2. **Recomp finds and dates your physique photos.**
     On-device. Sorted by date, laid out on a timeline, ready to compare.
  3. **Compare any two — see two years of work in one view.**
     Pick any two dates. Side by side, aligned, honest. The compare your camera roll couldn't give you.
- **Closer (right below the three steps):**
  > That's it. No workouts to log. No macros to enter. No "start fresh" required. Just the photos you already took, finally laid out.

**Visual guidance.** Horizontal three-column layout on desktop; each column shows a numbered step, a small screenshot, and the one-line description. Step 3's screenshot is visually dominant (larger, or the only one in full colour while 1 and 2 sit slightly muted). Collapses to a vertical scroll on mobile.

**Implementation notes.** Steps describe the *user's* action, not the app's mechanics — per research. The closer is not optional — it does the entire "we're not another generic fitness tracker" work of the page in one sentence, and adds the import-specific reassurance ("no start fresh required"). Do not say "AI" — per research: the persona bounces on the word, and "finds and dates" is more concrete anyway.

### 3b — Bring your camera roll (single card)

**Full copy.**

- **H3:**
  > Bring your camera roll.
- **Single card:**
  - **Title:** I've been taking photos.
  - **Body:** Import your camera roll. Recomp finds the physique photos, dates them, aligns them, and shows you the compare — in minutes, not weeks. Nothing gets included until you confirm.
  - **CTA:** waitlist email capture. Button labeled **Notify me at launch**.
- **Small muted link below the card:**
  > Starting fresh, no library yet? [See the forward-tracking version →](../track/)

**Visual guidance.** One elevated card centered on the section (layered over the grid; 16–24px corner radius; subtle border in dark mode, subtle shadow in light mode). On mobile, the card is full-width with generous internal padding. The muted "starting fresh" link sits under the card in body-small type, secondary text colour — visible to the visitor who needs it, quiet enough not to compete.

**Implementation notes.**

- The release version's two-card split is collapsed to one — per the variant spec: this page is not for people starting fresh, and offering both flows equally would dilute the import thesis. The muted link is the escape hatch for the fit-but-wrong-flow visitor, not a co-equal path.
- The card's CTA feeds the same waitlist as the hero — per research: the value is recognition, not routing.
- Do not implement the muted link as a toggle/tab — per research: toggles hide half the value and the point here is to send a small minority elsewhere, not to negotiate the choice inline.

### 3c — The aha moment

**Full copy.**

- **H2:**
  > The moment you actually see it.
- **Caption below the compare:**
  > 150 check-ins pulled straight from my camera roll. Two years of lifting, in one view.
  > — Mark, founder of Recomp

**Visual guidance.** One full-width compare view — the founder's own transformation, real weight delta, real timeline (e.g. "14 weeks"), dated. Photos land on the page as photos, not inside a device frame — this is the emotional peak; the phone chrome is a distraction here.

**Implementation notes.** This is the emotional peak of the page — per research: if a visitor takes only one image away, this should be it. The caption is rewritten to reinforce that the compare came *from* an imported library, not from a fresh forward-tracking cadence — that's the import thesis rendered in one line. Full-bleed accent treatment is allowed here as one of the ≤2 accent moments on the page (final CTA gets the other), but a transparent grid treatment also works and is safer.

### 3d — Everything else it does (feature strip)

**Full copy.**

- **H2:**
  > Everything else your physique tracker should be.
- **Feature blocks** (alternating rows; ship four for launch — 1, 2, 3, 4 below):
  1. **Import the photos you already have.**
     Point Recomp at your camera roll. It'll find the physique photos and organise them by date. See a year of progress in the first minute.
  2. **Compare any two check-ins.**
     Pick any two dates. Side by side, same scale, honest.
  3. **A real timeline, not a photo grid.**
     Every check-in in one scroll — with dates, weights, and notes.
  4. **Works on the history you already built. No minimum required.**
     Ten photos or ten thousand — Recomp lays out what's there. You don't need to start over.
  5. *(hold for later)* **Your photos never leave your phone unless you say so.**
     No feed. No sharing. Nothing public. Just your own record.
  6. *(dropped from this variant)* **One check-in a week. That's the whole habit.**
     Forward-tracking cadence belongs on the [track variant](../track/), not here.

**Visual guidance.** Alternating full-width feature rows. Each row: real screenshot on one side (alternating sides between rows), copy on the other. Screenshots are actual product captures at retina resolution — same phone frame, consistent status bar. Two-column grid is the fallback if vertical space is tight.

**Implementation notes.** Order is reworked for the variant — per the spec: **import promoted to #1** (highest-leverage acquisition feature *and* the whole page's thesis), compare to #2, timeline to #3, "works on what you have" as a new #4 that reinforces the no-minimum, no-restart promise. The forward-looking "one check-in a week" feature is dropped — it belongs on the track variant. Absence is a persuasion tool — per research: nothing here mentions streaks, workouts, calories, macros, social feeds, or friends; the persona notices what isn't there. No trademarked feature names ("PhysiqueSense™") — per research: persona will laugh.

---

## Section 4 — Social Proof & Trust

**Purpose.** Convert the mid-page moment of maximum consideration into permission to sign up, using one dominant, checkable story proof plus honest pre-release density signals. At pre-release the founder's own 150-check-in imported library *is* the proof — no fabricated ratings.

**Full copy.**

- **Density strip (top of section, one line, small type):**
  > Made by a lifter · Built on 150+ real check-ins imported from one camera roll · Early access opens this fall
- **Section H2 (above the story proof block):**
  > Real check-ins. Real camera roll.
- **Founder story proof (uses the same visual asset as Section 3c, but framed as proof rather than aha):**
  > **Two years. 150 check-ins. All imported from my camera roll.**
  > I built Recomp because I couldn't find a tracker that respected the compare view — and because I already had the record, sitting on my phone, unreadable. This is what mine looks like once Recomp reads it.
  > — Mark, founder
- **Early-access placeholder (populate when consenting beta users produce imported compares — until then, leave this slot dark or fill with a second founder compare from a different training block):**
  - Name (first name + last initial, or handle).
  - Timeline (start → end date, drawn from their imported library).
  - Context ("cutting 200 → 180", "bulking 150 → 165", "post-injury comeback").
  - One-sentence quote about the *moment* of realisation on first import. E.g.:
    > "I didn't know I had a compare like this on my phone."
  - The user's compare view, with consent, matched to the moment.

**Visual guidance.** The density strip is small, single-row, muted — it's ambient. Below it, one dominant story block: the founder compare view (full-bleed or elevated card) with the caption to its side on desktop, below on mobile. Any real early-access user cards come in as an elevated-card row underneath (3 cards on desktop; single-column carousel on mobile).

**CTA placement.** No CTA in this section. Social proof is a permission event, not a conversion event — the visitor keeps scrolling to the differentiation section, then the FAQ, then the final CTA.

**Implementation notes.**

- One dominant story + ambient density — per research: this pattern outperforms the "wall of five-star screenshots" every consumer app defaults to.
- The founder story works *better* here than on the release page — because he's proving the import thesis with his own imported library, not just showing off progress.
- Never fabricate. Never round up. Never invent "join 5,000 lifters on the waitlist" if the number isn't real. Per research: the persona will smell it and the whole page loses credibility. It is honest and adequate at pre-release to say only what's true: the app is coming, the founder built it on 150 real imports, early access opens on a specific window.
- Every founder / user photo has meaningful alt text ("Two-panel compare view: physique on the left dated April 2024, on the right dated July 2024, imported from the founder's camera roll. Weight: 195 lb → 182 lb.").

---

## Section 5 — Differentiation

**Purpose.** Give the persona the one-glance reason Recomp is not another generic fitness tracker, in the register they respect: understated, precise, and stated by omission as much as by claim. On this variant, add one explicit row about import so the differentiation reinforces the page's thesis.

**Full copy.**

- **H2:**
  > Not a fitness tracker. A tracker for what fitness is for.
- **Lead paragraph:**
  > Recomp exists for one thing: to make the visual outcome of your training visible — including the outcome you've already lived through. Everything the app does builds toward the compare view. Everything it *doesn't* do is a decision.
- **Two-column list — "What Recomp does / What Recomp doesn't do":**

  | What Recomp does | What Recomp doesn't do |
  | --- | --- |
  | Works on the years of photos you already have | Require you to start over |
  | Turn your existing photos into a dated timeline | Log workouts, sets, reps |
  | Compare any two dates, side by side, aligned | Track macros or calories |
  | Weekly check-ins with photo, weight, notes | Award streaks, XP, or badges |
  | Keep everything on your phone by default | Publish a feed, or add friends |
  | Rhyme with your training — precise, quiet, honest | Sell you motivation |

- **Closing line (under the table):**
  > If you already track training, nutrition, and lifts elsewhere, Recomp is the piece those tools skip. It reads the record you already built.

**Visual guidance.** Two clean columns on desktop, stacked on mobile. The "does" column sits on the left in the accent colour's tint (very restrained — a 6% wash, no more); the "doesn't do" column sits neutral. Row separators are single hairline lines in the grid's opacity. Optional: a small alignment-grid device screenshot at the section head, echoing the app's internal grid and the page grid.

**CTA placement.** No CTA here. This section is a positioning statement; the visitor is being cleared to sign up, not pushed.

**Implementation notes.**

- The new first row — "Works on the years of photos you already have / Doesn't require you to start over" — is the import thesis rendered as differentiation. Per the variant spec: keep it top-of-table.
- Closing line is tuned from the release version to reinforce that Recomp is the piece that *reads* an existing record, not just a piece that fills a forward gap.
- Position against the persona's *category exhaustion*, not against named competitors — per research: naming Hevy / MacroFactor is beside the point; the real competitor is the camera roll and the "generic fitness app" category as a whole.
- Saying what Recomp *doesn't* do is the sharpest way to say what it *is* — per research (Laja): the omitted-feature list carries more of the differentiation load than any positive claim.
- Vocabulary is domain-native (recomp, cut, bulk are allowed as colour, never as forced jargon).
- No "vs. competitor" table with named products. No superlatives.

---

## Section 6 — FAQ (Addressing Potential Objections)

**Purpose.** Name the specific things stopping a persona-fit visitor from signing up to a pre-release waitlist, defuse each in 2–4 sentences, and earn trust through honesty (about the timeline, about how import actually works, about pricing).

**Full copy.**

- **Section H2:**
  > Answers to what you're probably thinking.

- **Item 1 — When can I use it?**
  > Early access opens this fall, in waves — waitlist first. We'll email you a TestFlight link when it's your turn; you're not obligated to accept it, and we'll only email you at launch and once when your invite is ready. No drip campaign.

- **Item 2 — How does the import actually work? Will it grab photos I don't want it to?**
  > You stay in control. Recomp asks for photo access, scans on-device (nothing gets uploaded), and shows you what it thinks are physique photos. You confirm before anything is included in your timeline. If it flags a photo that isn't a physique shot, you exclude it in one tap. Nothing goes into a compare without your say-so.

- **Item 3 — What if my old photos aren't consistent — different poses, lighting, distance?**
  > That's most people's camera roll, and it's fine. The compare view has alignment tools — you can nudge, scale, and match reference points between two shots so the delta reads honestly. Recomp doesn't fix bad inputs, but it makes uneven inputs comparable in a way a bare Photos album never will.

- **Item 4 — Isn't this just an iPhone album?**
  > An album is a folder. Recomp is a timeline. The difference is compare — being able to place any two dates side by side, aligned and dated, without hunting through months of photos. Try it once on your imported library and the gap is obvious.

- **Item 5 — Do I have to track weight, workouts, or macros?**
  > No. Weight and notes are optional on every check-in and on every import. Workouts and macros aren't in Recomp at all — those tools exist and are good; Recomp handles the piece they skip.

- **Item 6 — How much will it cost?**
  > Free to start — importing your camera roll and the first stretch of compares cost nothing. Paid once you're serious, at less than the price of a month of gym coffee. Waitlist members will see the pricing before anything charges.

- **Item 7 — Where do my photos live? Are they private?**
  > On your phone. Recomp doesn't upload your photos to a server, doesn't share them anywhere, and doesn't publish a feed. Import scans and compare alignment happen on-device. If you back up to iCloud Photos, they go where your other photos go. Nothing else.

- **Item 8 — Do I need to keep taking photos after the import?**
  > No — the import alone is worth the download; your existing library becomes a proper timeline. But once you've seen the compare, you'll want to keep the cadence going. The [track variant](../track/) covers the weekly ritual in more depth.

- **Item 9 — I already use Hevy / MacroFactor / a spreadsheet. Do I need this?**
  > Probably yes, and for a different reason. Those tools track the inputs — the training, the food, the numbers. Recomp tracks the outcome — the physique itself, over time. It's the missing piece, not a replacement.

- **Item 10 — Is it just iOS?**
  > For now, yes. Recomp is built iOS-native — Photos, HealthKit, the Apple design system — because that's where our first users are and because that's where the years of camera-roll history lives. Android will come once the iOS product is where it needs to be.

**Visual guidance.** Expandable accordion, all items collapsed by default. Each row: question in body-large weight, expand chevron on the right. Expanded state reveals the answer in body copy with generous line height. Container is an elevated card layered over the grid.

**CTA placement.** No inline CTAs in the accordion. Below the FAQ, a small transitional line leading into the final CTA:
> Still on the fence? Get on the waitlist — the first compare from your own camera roll is what convinces you.

**Implementation notes.**

- Item 1 (timeline) is promoted to the top — per the variant spec: it's the first question any pre-release visitor asks, and honesty about the window is the entire trust play at this stage. If no firm date exists, keep the phrasing seasonal ("this fall"), not date-precise; do not promise a specific week you can't hit.
- Item 2 (how import works) is new and load-bearing — per the variant spec: the persona will worry about photo access before they'll sign up. Answering this in the FAQ is more credible than a "your privacy matters" microcopy line.
- Item 3 (uneven old photos) is the credibility play — per research (Laja): acknowledging a real tradeoff before the visitor thinks of it lifts trust more than any positive claim. Ship it.
- The release version's "3–6 weeks" item is reworked as Item 8 ("Do I need to keep taking photos after the import?") — per the variant spec: the forward-tracking-lag question is off-thesis here; the equivalent honest question for this variant is whether the import alone earns its download.
- Do not pre-expand any answers — per research: pre-expanded FAQs create visual clutter and defeat the pattern.
- Do not invent objections. Register is flat and precise. No "Great question!" or "Absolutely!" — per research: register-breaks read as low-quality marketing.
- Every accordion row is keyboard-accessible with visible focus rings and `prefers-reduced-motion` respected.

---

## Section 7 — Final Call-to-Action

**Purpose.** The visitors who reach this section are the highest-intent segment on the page. Give them one clean, unmissable waitlist path and nothing to trip on.

**Full copy.**

- **Section H2:**
  > Import your camera roll first.
- **Supporting line:**
  > Early access opens in weeks. Get the link the day it drops — before the public list.
- **Primary CTA:** waitlist email capture, larger than the hero one, centered. Button labeled **Send me the link when it drops**.
- **Optional density signal below the CTA (small type; ship only if honest):**
  > No drip campaign · One email at launch · Unsubscribe in one tap

**Visual guidance.** Full-bleed accent section — a solid or very-slightly-tinted accent fill that covers the page grid completely (this is one of the ≤2 places on the page that earns this treatment). Copy centered. Waitlist form centered. Optionally, one different compare view above the copy (a different transformation from the hero or the aha moment, still drawn from the founder's imported library) so the visitor's last visual impression is a fresh proof point. On mobile, the form sits with generous padding — nothing else competes for the tap.

**CTA placement.** One CTA. Centered. No secondary link, no "Follow us on TikTok," no "Subscribe for updates" separately from the waitlist itself — per research: any non-signup element at the final CTA is an exfiltration from the funnel.

**Implementation notes.**

- CTA copy varies across the page: hero says **Get early access** with the micro-line "Early access opens in weeks · Import your camera roll first"; section 3b says **Notify me at launch**; the final says **Send me the link when it drops**. Same form, different framing — same pattern as the release version's badge-with-varied-microcopy rule.
- Full-bleed accent is the only section where the grid is fully covered — per research: overusing full-bleed erodes the grid's foundational role.
- Do not put a pricing block or a "Compare plans" table here — per research: introduces last-minute cognitive load right when the visitor should be acting on emotion + evidence.
- Do not stack "email me + follow us on X" here. The waitlist is the whole funnel at pre-release; social follows belong in the footer, muted.

---

## Section 8 — Footer (Minimal)

**Purpose.** Legal completeness, mode control, and identity — nothing else. Every non-legal link is a leak.

**Full copy.**

- **Left:** Recomp wordmark. Under it: `© 2026 Recomp. Made by a lifter.`
- **Center (or right on wider viewports):** three legal links:
  > Privacy · Terms · Contact
- **Right:** mode toggle (three states — System · Light · Dark).
- **Far right (small icons, muted colour):** optional social icons — X, TikTok, one Instagram or YouTube if used. Muted, small, no more than three at pre-release (no App Store icon — the app isn't there yet).

**Visual guidance.** Single horizontal row on desktop, ~64px tall, with the graph-paper grid still faintly visible beneath. Stacks vertically on mobile with the wordmark on top, legal links in the middle row, mode toggle and socials on the bottom. Type is 13–14px, muted secondary text colour. No borders — the grid handles visual separation.

**CTA placement.** No CTA in the footer. Social icons live here so they don't compete anywhere upstream.

**Implementation notes.**

- Mode toggle persists to `localStorage` and defaults to `prefers-color-scheme` — per research: the persona expects mode-following.
- Legal links only — per research (Gardner Attention Ratio): no product links, no blog, no press page, no "about us" (the founder story already lives in Section 4).
- No App Store icon in the footer socials for the pre-release page — per the variant spec: nothing on the page pretends the App Store listing exists.
- Social icons are muted and small — per research: social follows are a leak; they belong here, not near a CTA, and never above it.
- The waitlist form has already appeared three times above; the footer does *not* repeat it — per research: repeating the primary conversion in the footer trains the eye to ignore it above.

---

## Cross-cutting reminders (apply to every section above)

- **Attention Ratio 1:1.** One goal — waitlist signup — one CTA type (email capture form). Vary the button label across the page (Get early access · Notify me at launch · Join the waitlist · Send me the link when it drops), never the form itself.
- **No App Store badge anywhere.** The app isn't on the App Store yet. Every place the release version used the badge, this variant uses a waitlist capture. When the app ships, this page either redirects to the release page or gets its badge-and-copy swap in a single release commit.
- **Grid discipline.** Grid is continuous background. Sections either sit transparently over it, layer as elevated cards, or (final CTA only) full-bleed accent over it. At most two full-bleed accents per page.
- **Mobile-first check per section.** Email input + button reachable above the fold in the hero, headline ≤ 6 words rendered lines, hero visual ≤ 45% of viewport height, 44px touch targets, email input does not trigger auto-zoom on iOS (font-size ≥ 16px).
- **Voice.** Precise, understated, no exclamation points, no motivational-quote energy. This variant runs slightly more emotional-reveal ("the evidence is already on your phone") than the release version, and that's the point — the visitor secretly hopes their camera roll contains proof of years of work; the page's job is to say *yes, it does.* Still restrained. Still Moody's register, not StrongLifts'.
- **Specificity rule.** Every copy pass asks: "Can this be more specific?" Nine times out of ten the answer is yes ("years of progress" > "lots of progress"; "in minutes" > "quickly"; "150 check-ins from one camera roll" > "a lot of data").
- **Nothing fabricated.** No invented waitlist counts, no rounded-up numbers, no fake testimonials, no stock photography, no invented launch date. The persona detects all of it — and at pre-release, honesty about what's known and what isn't is the whole trust play.
