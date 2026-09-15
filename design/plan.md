# ICEWEAR VEZZO — ROP 4 Premium Upgrade Plan

Copyright (c) 2026 Icewear Vezzo, Iced Up Records, Foundation Media, and Digital Currensy Inc. All rights reserved. See /NOTICE.

## Profile
- Mode: M, in-place iteration of an existing released browser game.
- Time: real-time with pause-at-will.
- Space: continuous pseudo-3D lane road rendered in 2D canvas.
- Agency: one embodied luxury sedan.
- Conflict: player versus traffic, hazards, time, and personal rank.
- Content: authored patterns with seeded variation.
- Outcome: finite six-mile run with score/rank result.
- Players: solo.
- Session: approximately 1–3 minutes.
- Primary engagement: execution and self-improvement.
- Platforms: desktop web and mobile web.
- Inputs: keyboard, touch/swipe, gamepad.
- Language: English, all visible strings externalized.
- Performance: 60 fps target; mobile draw-call proxy budget 80; DPR cap 1.5; worst case is boost active during dense traffic, particles, billboards, HUD, rain, and result transition.

## Experience formula
The player feels like they are driving inside a premium Detroit rap-album campaign because every screen, roadside landmark, vehicle surface, sound cue, and result moment reinforces nocturnal luxury, speed, status, and the ROP 4 identity. The game constantly rewards precise lane choices with immediate audiovisual response and turns each completed run into a shareable campaign asset.

## Laws and patterns
- Learnable patterns: lane timing, reading traffic gaps, collectible risk/reward, near-miss timing, shield conservation, boost timing.
- Short loop: scan lanes → move/dodge → collect → receive feedback.
- Medium loop: build combo/boost/shield resources across each mile.
- Long loop: improve score/rank, best score, and vehicle style.
- Uncertainty: execution timing carried by lane changes; anticipation carried by seeded spawn patterns; self-competition carried by persistent best score/rank.

## Verbs and feedback
- Change lane → immediate lateral easing and light sweep → affects collision, pickups, near misses, and combo.
- Boost → immediate FOV/speed/light-trail response → affects distance pace and scoring opportunity.
- Pause/resume → immediate overlay → preserves current run.
- Select vehicle → active premium card and persistent save → selected vehicle appears in gameplay and result card.
- Share/download/copy → native share or deterministic fallback with confirmation → exports score, rank, stats, vehicle, branded result image, and game URL.
- Navigate → explicit Home/Back/Start/Drive buttons on every non-gameplay screen.

## Preservation contract
- Preserve lane-based driving, seeded traffic, collectibles, near misses, boost, shield, scoring, six-mile distance, best score/rank persistence, current game URL, and project ownership.
- No catalog publish without explicit approval.
- No browser Back requirement.

## Presentation scope
1. Repair native share and fallback actions.
2. Add result-card PNG generation and download.
3. Redesign Home with vehicle hero, two exact album-cover placements, premium hierarchy, motion, and sound control.
4. Redesign Garage with showroom platform, descriptors, selected state, Drive This Car, and Home.
5. Add perspective-correct album billboards and secondary environmental branding across the route.
6. Redesign How to Play as six icon cards with Start Game and Home.
7. Consolidate typography, buttons, ROP-red warnings, acid-lime primary actions, purple selection, spacing, and responsive behavior.
8. Upgrade HUD, pickups, boost, near-miss, crash, transitions, and mobile controls without obscuring the road.

## STYLE FORMULA
Cinematic illustrated automotive advertising with polished 2.5D canvas compositing and restrained film grain; sleek geometric silhouettes, crisp chrome edges, and spacious editorial framing; environments in black, charcoal, and deep violet, the white hero sedan held in high contrast, ROP 4 red reserved for warnings and campaign lettering, acid lime reserved for primary actions, and purple for pickups and selected states; nocturnal Detroit rain, wet reflections, fog, rim light, and controlled sparkle; high readability with consistent rear-facing road perspective and frontal interface perspective.

## Prototype question and preservation check
Question: can navigation/share/presentation be upgraded without changing the existing run model? Cheap verification: static state-transition audit plus deterministic smoke route from Home → Garage → Drive → Play → Results → Share fallback → Play Again → Home. Existing simulation constants and spawn tables remain untouched unless a functional test identifies a regression.
