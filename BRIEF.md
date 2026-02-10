# BRIEF.md — Website Build Brief
> Claude Code: This file defines the technical constraints, visual direction, and page structure for the UMB Cyber Spring 2026 website.

---

## Project Overview

Build a **single-page scrollable website** for the UMass Boston Cyber Security Club — Spring 2026.

The site serves as the public-facing objectives and vision page linked in the club's welcome email. It must communicate who we are, what we're building, and how to join — clearly and beautifully.

---

## Technical Constraints

- **Stack:** HTML, CSS, JavaScript only — no frameworks, no build tools, no dependencies
- **Single file preferred:** `index.html` with embedded or linked CSS/JS
- **GitHub Pages compatible:** Must deploy with zero configuration at `username.github.io/repo`
- **No backend:** Everything is static
- **Mobile responsive:** Must look excellent on mobile and desktop
- **Performance:** Fast load, no heavy libraries, no external fonts that block render (Google Fonts via CDN is acceptable)

---

## Visual Direction

**Dominant:** Black — deep, true black (`#0a0a0a` or `#000000`). This is the foundation.

**Accent:** Modern AI/Cyber taste — not Matrix green, not neon. Think:
- Electric blue (`#00AAFF` or similar) for primary highlights
- Clean white (`#FFFFFF`) for headings and key text
- Subtle gray (`#888888`) for secondary text
- One rare, intentional accent pop — a gradient or glow used sparingly

**Aesthetic:** Modern, minimal, premium. Think Apple meets cybersecurity. Clean whitespace. Sharp typography. No clutter. Every element earns its place.

**Typography:**
- Use a clean sans-serif — Inter, Space Grotesk, or similar via Google Fonts
- Headings: bold, large, confident
- Body: readable, comfortable line height

**Vibe:** A student picks up the flyer, scans the QR code, lands on this page — and immediately thinks: *"This club is different. This is serious. I want in."*

---

## Design Philosophy

> "Take a pause. Take a deep breath. You are Steve Jobs. You have his design sense and his sense of urgency. You want to make this page beautiful — use everything in your power to do so. Do not change the functionality. Instead, scour every design decision, look for areas of improvement, and make all of them. The design of this page sets the culture of the entire organization. Beautify. Elevate the human experience."

Apply this philosophy to every section, every margin, every color choice, every hover state.

---

## Page Structure

Build the page in this exact section order:

### 1. Hero
- Club name: **UMass Boston Cyber Security Club**
- Shorthand badge: **UMB Cyber | Spring 2026**
- Primary tagline: *"Secure the Future. Master the Machine."*
- Subtext: Strategic positioning — *"The AI x Cyber Hub"*
- CTA button: **"Fill Out the Form"** → `[FORM LINK]` *(this is the most important element on the page)*
- Secondary link: Join Discord → `[DISCORD LINK]`

### 2. Who We Are
- Mission statement
- Vision statement
- Keep it tight — two short, punchy paragraphs

### 3. Our Values
- Display all 4 values as cards or sections:
  - The Augmentation Principle
  - Trial & Error
  - Curiosity & Persistence
  - Ethical Learning
- Each: title + one-sentence principle only (keep it scannable)

### 4. What We're Building — Spring 2026
- Curriculum overview: 3 phases, clean visual treatment
- Brief description of each phase
- Convey the arc: beginner → AI agent builder → security practitioner

### 5. Join Us *(Footer / Final CTA)*
- Headline: *"Ready to build the future of security?"*
- Primary CTA: **"Fill Out the Form"** → `[FORM LINK]`
- Secondary: Discord link
- Club name + semester as closing line

---

## Interaction & Polish

- Smooth scroll between sections
- Subtle scroll-triggered fade-in animations on sections (CSS or lightweight JS)
- Hover states on all buttons and cards
- Active nav dots or a minimal sticky nav (optional but nice)
- No unnecessary animations — every motion has a purpose

---

## Placeholders

Use these exact strings as link placeholders — the human will replace them:
- `[FORM LINK]`
- `[DISCORD LINK]`
