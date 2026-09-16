---
name: Timmy Digital
description: A clear, connected digital presence for New Zealand small businesses.
colors:
  canvas: "#f3f6ef"
  section: "#e6ecdf"
  ink: "#142c28"
  muted-ink: "#465c51"
  signal: "#f46e43"
  signal-text: "#b34724"
  line: "#cdd2c7"
typography:
  display:
    fontFamily: "Bricolage, sans-serif"
    fontSize: "clamp(58px, 5.8vw, 103px)"
    fontWeight: 700
    lineHeight: 0.99
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Bricolage, sans-serif"
    fontSize: "clamp(51px, 5.3vw, 88px)"
    fontWeight: 700
    lineHeight: 1.03
    letterSpacing: "-0.035em"
  title:
    fontFamily: "Bricolage, sans-serif"
    fontSize: "clamp(30px, 3vw, 45px)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.035em"
  body:
    fontFamily: "DM Sans, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.62
  label:
    fontFamily: "DM Sans, sans-serif"
    fontSize: "14px"
    fontWeight: 600
components:
  button-dark:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.canvas}"
    padding: "20px 24px"
    height: "60px"
  button-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    padding: "20px 24px"
    height: "60px"
---

# Design System: Timmy Digital

## Overview

**Creative North Star: "Connected Paths"**

An editorial layout pairs the direct hero offer with a diagram of the ways a small business can be found. Below it, visible explanations lead from familiar business situations to relevant services, then to two possible starting points and an email conversation. Strong display type, broad color fields, and fine dividers keep the long page legible. This is a starting identity pending owner review.

**Key Characteristics:** clear hierarchy, purposeful color, visible connections between services, direct language.

## Colors

The pale green canvas and deep green ink carry most content. Coral marks connections and moments of action.

- **Canvas**: main page background and light action surface.
- **Section**: service section background.
- **Ink**: main text, hero diagram, and contact surface.
- **Muted ink**: supporting copy on light surfaces.
- **Signal**: diagram core, dots, and focus outlines.
- **Signal text**: readable headline accent on light surfaces.
- **Line**: light dividers.

## Typography

Bricolage Grotesque 700 is the display voice; DM Sans 400 and 600 carry body, labels, and navigation. Both are self-hosted. Display headings have compact line height and tight tracking; body copy has open line spacing. Large headings adapt at the 760px and 440px breakpoints.

## Layout

The desktop hero pairs the offer with a CSS channel diagram. The service section uses open two-column rows: a visitor situation at left, the service explanation at right. The paid campaigns row adds a compact Google Ads, Meta Ads, and TikTok Ads fit guide. Two bordered starting points follow, then a dark contact section pairs a first-email guide with a prefilled email action. Below 760px, these sections become one column and navigation moves behind a menu button. The page also adjusts the hero below 1050px and 440px.

## Elevation & Depth

Most sections use flat color fields and fine dividers. The hero diagram uses soft shadows to lift its central business node and channel labels; the open mobile menu also casts a shadow.

## Shapes

Sections and controls are mostly square edged. Circles are reserved for the channel diagram and brand and signal dots.

## Components

- The typographic logo uses an orange dot as its accent.
- Dark and light filled buttons use arrows to indicate forward movement. Text links use an underline or border and the same arrow cue. All interactive controls have visible focus outlines.
- Service rows are always visible, separated by rules, and pair a situation with the relevant service. Channel fit cues sit inside the paid campaigns row.
- The two starting points sit side by side on desktop and stack on mobile.
- The hero diagram is CSS geometry with an accessible description.
- The mobile navigation toggles with an accessible button and closes after selection or Escape. Reduced motion preferences disable smooth scrolling and transitions.

## Do's and Don'ts

- Do keep service explanations readable for New Zealand small business owners.
- Do use signal color deliberately and keep text contrast high.
- Do keep service content visible without requiring interaction.
- Don't add unverified results, clients, certifications, or testimonials.
- Don't replace the open editorial sections with generic cards or dashboards.
