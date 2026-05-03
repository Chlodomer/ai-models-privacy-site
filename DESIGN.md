---
version: alpha
name: AI Models, Privacy, and Academic Practice
description: Design system for a faculty-facing educational website based on the April 27, 2026 HIGH AI meeting.
colors:
  primary: "#062F22"
  forest: "#062F22"
  deep: "#031A13"
  moss: "#466B43"
  ochre: "#D9A23A"
  rust: "#B65A3C"
  plum: "#5A4668"
  blue: "#3F6F95"
  paper: "#FBF7EE"
  cream: "#F2EADB"
  ink: "#171814"
  muted: "#66665D"
  white: "#FFFFFF"
typography:
  display:
    fontFamily: Georgia
    fontSize: 72px
    fontWeight: 700
    lineHeight: 0.96
  headline:
    fontFamily: Georgia
    fontSize: 46px
    fontWeight: 700
    lineHeight: 1.0
  body:
    fontFamily: Avenir Next
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.58
  label:
    fontFamily: Avenir Next
    fontSize: 12px
    fontWeight: 800
    lineHeight: 1.2
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 72px
rounded:
  sm: 6px
  md: 8px
  lg: 16px
components:
  editorial-hero:
    backgroundColor: "{colors.forest}"
    textColor: "{colors.white}"
    rounded: "{rounded.sm}"
    padding: 72px
  button-primary:
    backgroundColor: "{colors.ochre}"
    textColor: "{colors.deep}"
    rounded: "{rounded.md}"
    padding: 16px
  button-dark:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 16px
  tab-panel:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: 40px
  privacy-options:
    backgroundColor: "{colors.deep}"
    textColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: 18px
  evidence-card:
    backgroundColor: "{colors.deep}"
    textColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: 20px
  privacy-accent:
    backgroundColor: "{colors.rust}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 12px
  reasoning-accent:
    backgroundColor: "{colors.plum}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 12px
  evidence-accent:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 12px
  reading-surface:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: 24px
  menu-surface:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: 12px
  secondary-action:
    backgroundColor: "{colors.moss}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    padding: 16px
---

# Design System

## Overview
This website turns the April 27, 2026 meeting into a polished faculty guide. It should feel like an academic editorial feature: serious, useful, warm, and visually composed.

The adapted interview module gives these answers:
- **Purpose:** Turn the meeting into a usable reference site for AI privacy, model choice, context, validation, and assessment.
- **Audience:** Bar-Ilan faculty, clinicians, researchers, and students who need practical AI guidance.
- **Desired feeling:** Polished, credible, intelligent, and less like a generic documentation page.
- **Visual preference:** Photo-led academic editorial design with richer color, strong section changes, and compact interactive areas.
- **Constraints:** Avoid jargon when possible. Keep content scannable. Do not use underlines. Do not use abstract circle-and-square tech animations.

## Colors
Do not let the page collapse into only green and light blue.

- **Deep / Forest:** Institutional seriousness, navigation, dark bands, and strong contrast.
- **Ochre:** Primary action, warmth, and important teaching moments.
- **Rust:** Privacy warnings and human stakes.
- **Plum:** reasoning, assessment, and reflective moments.
- **Blue:** limited use for evidence and verification.
- **Paper / Cream:** readable academic surfaces.

## Typography
Use Georgia for editorial headlines and a clean non-default sans-serif stack for practical UI/body text. Headlines should feel like a magazine feature, not a dashboard. Body copy should remain plain and readable for non-technical readers.

## Imagery
Use generated photographic imagery, not abstract tech decoration. Preferred subjects:
- faculty workshop or seminar discussion
- secure local workstation with documents
- annotated sources and validation practice

Images should have warm academic lighting, real texture, books, papers, laptops, and institutional atmosphere. Avoid stock-photo smiles, neon cyber imagery, fake UI overlays, logos, and readable text inside images.

## Layout
Avoid endless scroll made of repeated cards. The main experience should behave like a guided set of screens inside one stable stage: one major page visible at a time, with top navigation and persistent yellow side arrows for previous/next movement. Hidden screens must never occupy layout space or peek into view. Use distinct modes:
- photo-led first viewport
- side-swipe tabbed guide for core principles
- interactive split image/text band for privacy
- visible privacy options rather than dropdown menus
- compact model-selection studio with direct choice buttons
- fade-through evidence viewer
- short next-session panel

## Motion & Interaction
Motion should feel polished and restrained:
- main page changes use side/fade transitions inside a fixed stage, not vertical scroll jumps
- wheel or trackpad gestures should advance screens when the current screen has no more local content to reveal
- tab panels side-swipe horizontally
- privacy choices update the image focus and detail copy in place
- model studio changes recommendation in place
- evidence examples fade between states
- cards lift subtly on hover
- screen content enters with staggered movement; photography can breathe or pan subtly

Do not use decorative animations made from circles, squares, or generic geometric tech motifs.

## Links And Emphasis
Never underline. Use color, weight, spacing, background surfaces, or border accents to show emphasis and interaction states.

## Components
- **Editorial hero:** full-bleed generated image with strong headline.
- **Direct navigation:** plain top-level links plus yellow side arrows for previous/next movement. Arrows should fade in only when the cursor nears a screen edge, then collapse so they do not cover text. The header lives in a reserved safe zone above the screen stage, may visually collapse after interaction, and must never cover page text. No dropdown menus.
- **Logo mark:** simple ochre square with centered AI letters and enough internal spacing to feel intentional.
- **Tabbed guide:** compact topic switching with horizontal side-swipe motion.
- **Privacy options:** visible choices for cloud, local, and university infrastructure that update the visual panel.
- **Model studio:** direct choice buttons that produce a recommendation.
- **Evidence viewer:** one example at a time with previous/next controls and fade transitions.

## Do's and Don'ts
- Do use real-feeling generated images.
- Do broaden the color palette with ochre, rust, plum, and warm paper tones.
- Do make each section feel like a different viewing mode.
- Do transition between major sections as pages, not as one long downward scroll.
- Do preserve the practical recommendations from the meeting.
- Don't underline text.
- Don't use abstract circle/square animations.
- Don't make the page a repetitive endless scroll.
- Don't hide practical advice under decorative content.
