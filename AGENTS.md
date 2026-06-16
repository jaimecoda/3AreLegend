# Agent Context Specification (AGENTS.md)

## System Prompt & Purpose
This file provides persistent context for `antigravity-cli` and downstream development agents to continue refining, expanding, and modifying the mobile-responsive travel itinerary HTML application.

---

## 1. Project Overview & Requirements
* **Objective:** A mobile-first, interactive single-page application (SPA) showcasing 2-day outdoor adventure weekend itineraries for active men departing from Boston by car.
* **Core Audience:** Three active men in their 30s seeking mid-to-high difficulty hiking, scenic vistas, craft breweries, and high-impact physical activities (e.g., coastal iron-rung climbing, sea kayaking, alpine roads).
* **Technical Constraints:**
  * Strict mobile-first responsive grid system and touch-friendly target areas.
  * Zero external heavy framework dependencies (Vanilla HTML5, CSS3 Custom Properties, and pure ES6+ JavaScript for tab and component switching).
  * Direct structural Google Maps routing links integrated into action buttons.
  * Inline, clean image presentation utilizing reliable CDN photography placeholders tailored exactly to regional visual markers (White Mountains alpine profiles, Acadia coastal granite).

---

## 2. Established Application State & Variables

### Target Option 1: White Mountains, NH
* **Logistics:** ~2.5–3 hours drive north via I-93 N or NH-16 N. Requires US Forest Service parking permits.
* **Day 1 Day Track:** Mount Willard Trail (Crawford Notch) [3.2-mile, 900ft elevation gain, valley vista overlook] or Franconia Ridge Loop alternative.
* **Day 1 Night Track:** Ledge Brewing Company (Intervale, NH) or Moat Mountain Smoke House.
* **Day 2 Track:** Mount Washington Summit (7.6-mile technical Auto Road) or Saco River open-top kayaking line.

### Target Option 2: Acadia National Park & Bar Harbor, ME
* **Logistics:** ~4.5–5 hours drive via I-95 N to ME-3 E. Requires National Park Vehicle Pass + advanced reservation for Cadillac Mountain.
* **Day 1 Day Track:** The Precipice Trail (strenuous vertical iron-rung route scaling 1,000ft cliffs) or Beehive Trail fallback.
* **Day 1 Night Track:** Downtown Bar Harbor / Atlantic Brewing Midtown taproom + waterfront lobster wharf options.
* **Day 2 Track:** Cadillac Mountain 4:00 AM Sunrise -> Morning execution split: Option A (3-hour guided ocean sea kayaking in Frenchman Bay) or Option B (55°F Atlantic cold-plunge surf swim at Sand Beach). Afternoon exit stop at Trenton Bridge Lobster Pound.

---

## 3. Engineering Guidelines for `antigravity-cli`
When executing iterative workspace modifications inside VS Code via `antigravity-cli`, the following global developer rules must be respected:
1. **Honest, Critical Refinement:** Do not pad generation output with unnecessary pleasantries or filler text. If a component layout or selector implementation can be optimized for performance or mobile responsiveness, implement the improvement directly and provide an honest, objective technical rationale.
2. **Scannability First:** Keep markup and script files cleanly partitioned. Use CSS variables for design system themes and clear semantic element grouping.
3. **No Added Subscriptions:** Ensure all assets, fonts, or code patterns leverage free, open-source, or self-hosted components. Avoid API dependencies requiring paid tokens or third-party client trackers.
4. **Source Fidelity:** Retain the documentation structure and reference citations from the base material to verify geographic accuracy.

---

## 4. Source Material References
* **New Hampshire DES - Swift River Guide:** `https://www.des.nh.gov/sites/g/files/ehbemt341/files/documents/2020-01/rl-12.pdf`
* **Adventure Bound - Kennebec River Rafting Guide:** `https://www.adv-bound.com/kennebec-river-rafting-guide/`
* **Zoar Outdoor - Deerfield River Rapids Overview:** `https://www.zoaroutdoor.com/about/river-information/deerfield-river-rapids-at-a-glance`
* **Ledge Brewing Company:** `https://ledgebrewing.com/`
* **Atlantic Brewing Company:** `https://www.atlanticbrewing.com/`
* **Dirt Church Brewing Company:** `https://dirtchurchvt.com/charlemont`
* **Northern Outdoors - Kennebec River Brewery:** `https://www.northernoutdoors.com/kennebec-river-brewery/`