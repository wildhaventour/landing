---
version: alpha
name: Wild Haven Tour
description: Calm, warm and trustworthy booking site for stays and packs on Isabela Island, Galapagos. Sand, ocean and one gold accent.
colors:
  primary: "#0B4B52"
  on-primary: "#FFFFFF"
  deep: "#0B2E35"
  on-deep: "#FFFFFF"
  accent: "#D9A13B"
  on-accent: "#1A1405"
  wood: "#8A5A36"
  neutral: "#F6F1E8"
  surface: "#FFFDF9"
  sea: "#E6EFEA"
  on-surface: "#13262A"
  muted: "#566A6B"
  line: "#E4DACB"
  field: "#9A8E7C"
  error: "#B3261E"
  dark-neutral: "#0E1A1C"
  dark-surface: "#152629"
  dark-on-surface: "#EDF3F1"
  dark-primary: "#6CC7BE"
typography:
  display:
    fontFamily: Lora
    fontSize: 3.4rem
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.012em
  headline-lg:
    fontFamily: Lora
    fontSize: 2.4rem
    fontWeight: 600
    lineHeight: 1.12
    letterSpacing: -0.012em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 1.7rem
    fontWeight: 800
    lineHeight: 1.1
  title:
    fontFamily: Bricolage Grotesque
    fontSize: 1.15rem
    fontWeight: 700
    lineHeight: 1.2
  body-md:
    fontFamily: Bricolage Grotesque
    fontSize: 1.05rem
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 0.88rem
    fontWeight: 400
    lineHeight: 1.5
  label-md:
    fontFamily: Bricolage Grotesque
    fontSize: 0.9rem
    fontWeight: 600
    lineHeight: 1.3
  price-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 2.4rem
    fontWeight: 800
    lineHeight: 1
    fontFeature: '"tnum" 1'
rounded:
  sm: 8px
  md: 12px
  lg: 16px
  xl: 18px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 54px
  page-max: 1080px
  gutter: 18px
components:
  button-book:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-accent}"
    typography: "{typography.title}"
    rounded: "{rounded.md}"
    padding: 15px
  button-book-pressed:
    backgroundColor: "{colors.accent}"
  button-secondary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
    padding: 14px
  button-ghost:
    textColor: "{colors.on-deep}"
    rounded: "{rounded.md}"
    padding: 14px
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: 21px
  card-featured:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.lg}"
  hero-panel:
    backgroundColor: "{colors.deep}"
    textColor: "{colors.on-deep}"
    rounded: "{rounded.xl}"
  price-box:
    backgroundColor: "{colors.sea}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: 16px
  input-field:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: 10px
  chip:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.full}"
    padding: 8px
  badge-offer:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-accent}"
    typography: "{typography.label-md}"
    rounded: "{rounded.full}"
---

# Wild Haven Tour

## Overview

Wild Haven Tour sells stays at a small wooden lodge in Puerto Villamil and simple packs with tours on Isabela Island, Galapagos. Visitors are mostly couples, families and retirees from the United States, Canada and Europe, plus residents of Ecuador. Most arrive on a phone, often on mobile data.

The feeling is a quiet beach town at the end of the day: sand underfoot, deep ocean, warm wood and a little gold light. The page must feel calm, honest and personal, never like a discount portal. Trust comes from real photos of the place, plain prices and a real person on WhatsApp.

The page is a Persuade surface. The first screen states the offer and shows two working actions: see the packs, or ask for a room only. Every price is final and visible, and the booking action is always one tap away through the bottom bar on phones.

The site works in Spanish (root) and US English (/en/). Both versions share one layout; copy must fit both languages without breaking.

## Colors

The palette is sand, ocean and one gold accent.

- **Neutral, sand (#F6F1E8):** the page ground. Warmer and softer than white.
- **Surface (#FFFDF9):** cards, forms and panels sit on this off white.
- **Primary, ocean teal (#0B4B52):** links, selected states, prices and secondary buttons.
- **Deep ocean (#0B2E35):** the hero panel, the sticky header, the bottom bar and dark bands.
- **Accent, gold (#D9A13B):** only for booking actions (reserve, quote, WhatsApp) and the launch offer badge. Text on gold is always the near black #1A1405.
- **Wood (#8A5A36):** small warm details such as icons and tour metadata.
- **Sea (#E6EFEA):** the background of price summaries.
- **Muted (#566A6B):** secondary text. It meets 4.5:1 on sand, surface and sea.
- **Line (#E4DACB):** hairline dividers only. Form fields use the darker field color (#9A8E7C) so their edges reach 3:1.

A dark theme follows the system setting with the dark tokens (ground #0E1A1C, surface #152629, text #EDF3F1, teal #6CC7BE).

## Typography

Two self hosted families, no external font requests.

- **Lora (serif, 600):** the hero title and section headings. It gives the editorial, unhurried voice.
- **Bricolage Grotesque (400 to 800):** everything else: body, labels, buttons, card titles and prices.
- Body text is 1.05rem with 1.55 line height and a measure under 65 characters.
- Prices use heavy weight and tabular numbers so totals do not jump while the configurator updates.
- No uppercase tracked labels above headings. A heading stands on its own.

## Layout

A single centered column, max 1080px, with 18px side padding on phones. Sections are separated by generous vertical space (about 54px) and a hairline. Grids go from one column on phones to two or three on wider screens. Horizontal strips with scroll snap are used for photo sets on phones.

On phones a fixed bottom bar holds the two main actions (see packs, WhatsApp). The assistant button sits above it and stays hidden while the hero is on screen, so it never covers the hero actions.

## Elevation & Depth

Depth is soft and low. Cards use a two layer shadow (1px close shadow plus a 30px diffuse shadow at about 7 percent opacity) and a hairline border. The featured card and the gold buttons carry a faint warm gold glow. The sticky header and bottom bar use deep ocean at 90 to 94 percent opacity with a light background blur, which is the only use of blur.

## Shapes

Rounded and friendly, never pill shaped for large containers. Inputs 8px, buttons and small panels 12px, cards 16px, the hero and pack cards 18px. Badges, chips and the language switch ends are fully rounded. Photos always have rounded corners that match their container.

## Components

- **Booking button:** gold background, near black text, 12px radius, full width inside forms. Press feedback scales to 0.97 in 160ms with a strong ease out. Hover lift of 1px only with a real mouse.
- **Secondary button:** ocean teal with white text. **Ghost button:** transparent with a 2px current color border, used on the deep hero.
- **Pack card:** cover video or photo on top, title in Bricolage 800, list of inclusions with small teal dots, price block, collapsible day by day plan, booking button at the bottom.
- **Price summary:** sea background, big tabular total, struck regular price beside it, line items with dashed dividers.
- **Consent boxes:** two separate checkboxes (booking terms with refund policy, privacy policy) right before every booking request button. The request cannot be sent until both are ticked.
- **Include and exclude boxes:** surface cards with a filled teal dot (includes) or an open wood ring (does not include) before the title.
- **Badges:** gold pill for the launch offer and "our pick".
- **Videos:** muted, looped, no controls, poster image first. They load only when they come into view and pause when they leave it. With reduced motion or data saver they never play on their own.

## Do's and Don'ts

- Do keep gold for booking actions only. One gold button per card or form.
- Do show final prices with the regular price struck through during the launch offer. Never show the hotel's internal cost.
- Do use real photos of the lodge and the island with credits in the legal page. Never stock photos presented as the lodge.
- Do keep every interactive target at least 44px tall on phones.
- Do write copy in plain, warm language. Spanish and US English carry the same facts.
- Don't add kicker labels above headings, numbered section markers or gradient text.
- Don't use thick colored borders on the left or right of cards.
- Don't animate whole sections on scroll. Motion is for feedback: button presses, the lightbox and small state changes, all under 300ms with a strong ease out, and gentler with reduced motion.
- Don't load autoplay video that is off screen.
- Don't promise wildlife sightings. Say it is common to see them.
