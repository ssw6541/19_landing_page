# Korean Stripe-Inspired Landing Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Build a polished Korean payments-platform landing page inspired by Stripe's visual language without copying its branding or content.

**Architecture:** Keep the project buildless and dependency-free. Put semantic page structure in `index.html`, responsive visuals and motion in `style.css`, and only the mobile navigation toggle in `script.js`.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript.

**Spec:** Approved in-chat design brief from 2026-10-21.

## Global Constraints

- All visible copy is Korean and uses original service naming/copy.
- No external runtime dependencies or image assets are required.
- Preserve accessible labels, keyboard focus, contrast, and responsive behavior.
- Use Stripe-like layout patterns and gradients, but do not reproduce Stripe logos or proprietary copy.

## Review Focus

- Mobile navigation must open and close from the menu button and remain keyboard accessible.
- Hero and card layouts must remain readable at narrow viewport widths.
- CTA links and navigation anchors must point to real page sections.
- Decorative gradients must not reduce text contrast or create horizontal overflow.

### Task 1: Replace starter markup with the landing page

**Files:**

- Modify: `index.html`
- Create: `script.js`

- [ ] Add semantic header, hero, product cards, trust section, developer code panel, CTA, and footer with Korean copy and anchor IDs.
- [ ] Add mobile menu button with `aria-expanded` and `aria-controls` attributes plus `script.js` toggle behavior.

### Task 2: Build responsive visual system

**Files:**

- Modify: `style.css`

- [ ] Define typography, color tokens, gradient backdrops, grid/card layout, responsive breakpoints, hover/focus states, and lightweight reveal animation.
- [ ] Verify no horizontal overflow and preserve readable type at widths from 360px through desktop.

### Task 3: Verify the static page

**Files:**

- No new files.

- [ ] Inspect the final source for valid links, missing alt text, and accidental mojibake.
- [ ] Run a local static preview or equivalent syntax check and confirm the page renders from `index.html`.
