# Physique Tracker — Core Product Requirements (Business + Product Focus)

## Product Summary

Physique Tracker is a simple, high-frequency body progress tracking app focused on helping users visually assess physique changes over time.

The product must feel fast, clean, and effortless. Users should be able to:

1. Capture progress photos quickly
2. Review historical logs easily
3. Compare any two check-ins visually
4. Adjust images for accurate side-by-side comparison
5. Navigate large photo histories smoothly

While the user-facing experience is simple, the core challenge is delivering professional-grade image comparison performance inside a lightweight mobile app.

---

# Primary User Jobs To Be Done

## 1. Log Progress Consistently

Users need to quickly create a new check-in with minimal friction.

Each log may contain:

- Up to 3 progress photos
- Date
- Body weight
- Notes

### Business Requirement

The logging flow must be fast enough that users maintain long-term consistency.

If logging feels slow or annoying, retention drops.

---

## 2. Review Historical Progress

Users need a gallery-style timeline showing all uploaded progress photos.

### Requirements

- Fast scrolling through all historical logs
- Thumbnail-based performance optimization
- Tap any image to open full screen
- Clear chronological organization

### Business Goal

Users should feel motivated by seeing accumulated progress.

The gallery is a retention surface.

---

## 3. Inspect Individual Logs

Users need to open a specific check-in and view:

- All photos from that session
- Date
- Weight
- Notes

### Business Goal

Users need confidence that each check-in was stored accurately and can be revisited later.

---

# Core Differentiator: Compare View

## Purpose

The compare screen is the most valuable feature.

It allows users to compare two logs ("before" vs "after") and visually validate progress.

This is where users emotionally experience results.

---

# Critical Product Requirements — Compare View

## 1. Freeform Image Alignment

Users must be able to manually adjust images for fair comparison.

Required interactions:

- Pan image
- Zoom image
- Reposition image
- Fine tune alignment visually

### Important Constraint

No rigid overlay system is required yet.

Instead, users compare one image visually against another and manually align.

This flexibility is a strategic product choice.

### Why It Matters

Real progress photos are inconsistent:

- Different camera distance
- Different crop
- Different stance
- Different framing

Without alignment controls, comparisons feel inaccurate.

---

## 2. Instant Before/After Switching

Users must be able to scrub through logs and rapidly change either:

- Before image
- After image

Without leaving compare mode.

### Example

User keeps "Today" fixed as After, then scrubs prior months as Before.

This creates strong habit loops and engagement.

---

## 3. Preserve Adjustments While Scrubbing

If practical, image adjustments should feel stable and predictable while switching images.

Users should not feel like controls reset unexpectedly.

---

# Primary Technical Constraint

## Performance Under Heavy Image Interaction

The compare screen combines two expensive workloads:

### A. Real-Time Image Manipulation

- Zoom
- Pan
- Scale
- Gesture handling
- Smooth rendering

### B. Rapid Timeline Scrubbing

- Switching many historical images quickly
- Loading adjacent assets
- Updating UI instantly

These must coexist smoothly.

### Risk Areas

- Memory pressure
- Jank during gestures
- Delayed image swaps
- Crashes on older devices
- Excessive re-renders

---

# Product Priorities (Highest to Lowest)

## P0 — Must Win

### Compare screen responsiveness

The compare feature is the product.

If compare feels bad, product value collapses.

Must achieve:

- Smooth gestures
- Fast image switching
- Stable memory usage
- No lag during scrubbing

---

## P1 — Fast Logging Flow

Creating a check-in must feel quick and habitual.

---

## P2 — Smooth Gallery Browsing

Users with many logs should browse without lag.

(Thumbnail optimization already improved this.)

---

## P3 — Detailed Log Viewing

Useful but secondary to compare and logging.

---

# UX Principles

## Simplicity Over Feature Bloat

From the user perspective, app should feel minimal:

- Gallery
- Add log
- Details
- Compare

No clutter.

---

## Power Hidden Beneath Simplicity

Advanced capability exists in compare interactions, not visible complexity.

---

## Speed Feels Like Quality

Users interpret performance as trustworthiness and premium quality.

---

# Non-Goals (For Now)

Do not prioritize yet:

- Complex overlays
- AI auto-alignment
- Social features
- Analytics dashboards
- Heavy editing tools
- Excessive customization

Stay focused on the core loop.

---

# Success Metrics

## Engagement

- Compare view usage frequency
- Time spent in compare mode
- Return sessions

## Retention

- Weekly check-ins created
- Consecutive logging streaks

## Performance

- Time to open compare screen
- Image switch latency while scrubbing
- Crash-free sessions
- Memory usage during compare

---

# Engineering Guidance for Cursor Models

When making technical decisions, optimize for:

## First Priority

Compare view speed + smoothness

## Second Priority

Memory efficiency with many photos

## Third Priority

Simple maintainable architecture

## Fourth Priority

Feature additions

---

# Product Thesis

Users do not care about logs.

Users care about proof.

The compare screen turns stored photos into proof of progress.

That experience must feel exceptional.
