# Power BI Custom Theming with JSON
Custom Power BI theme produced for Scottish Government-wide Power BI development efficiency

![Power BI](https://img.shields.io/badge/Power%20BI-Custom%20Theming-yellow)
![JSON](https://img.shields.io/badge/JSON-Configuration-blue)
![Accessibility](https://img.shields.io/badge/UI-Accessibility-green)

---

## Overview

This repository documents the creation of a reusable Power BI JSON theme aligned to the Scottish Government Design System.

The objective was to standardise dashboard appearance, improve readability and maintain consistency across reports.

Two theme versions are included:

- SG Theme v1.0.json
- SG Theme v1.1.json

---

## Why Custom Themes?

Power BI's built-in theme editor is limited.

JSON themes allow:

- Unlimited colour definitions
- Global styling rules
- Typography standardisation
- Visual-specific configuration
- Organisation-wide consistency

---

## Scottish Government Design System Alignment

The theme was built to align dashboards with established design standards used across Scottish Government digital services.

Objectives:

- Consistent user experience
- Accessibility
- Improved readability
- Reduced visual clutter

---

## Theme Colours

### Data Colours

11 colours were selected from official design system palettes.

Categories include:

- Dark blue
- Teal
- Purple
- Orange
- Dark green
- Green
- Brown
- Pink
- Blue
- Light blue
- Grey

---

## Sentiment Colours

Used by:

- KPI visuals
- Waterfall charts

| State | Colour |
|------|--------|
| Good | #1a7032 |
| Neutral | #000000 |
| Bad | #d32205 |

---

## Gradient Colours

Used for conditional formatting.

| Value | Colour |
|-------|--------|
| Maximum | #002d54 |
| Centre | #0065bd |
| Minimum | #55a8f2 |

---

## Typography

Typography standardisation implemented using:

### Font

Roboto

### Heading Scale

| Element | Size |
|---------|------|
| H1 | 30px |
| H2 | 22px |
| H3 | 19px |
| H4 | 16px |
| H5 | 14px |

### Body Text

16px

### Small Text

14px

---

## Colour Classes

Global classes were created for:

- Foreground
- Secondary foreground
- Tertiary foreground
- Background
- Secondary background
- Table accents

These control visual consistency throughout reports.

---

## Visual Styling

Additional configuration was implemented for:

### Filter Pane

- Background colours
- Border colours
- Typography

### Buttons

Four states configured:

- Default
- Hover
- Pressed
- Disabled

### Page Navigators

Added support for accent bars unavailable in native buttons.

### Bookmark Navigators

Styling aligned to page navigators.

### Tables

Customisation included:

- Header colours
- Alternating row colours
- Borders
- Typography

---

## Repository Contents

```text
README.md

SG Theme v1.0.json

SG Theme v1.1.json
```

---

## Skills Demonstrated

- Power BI
- JSON
- UI/UX principles
- Accessibility
- Data visualisation
- Design systems
- Technical documentation

---
## Disclaimer

This work was produced during a placement within Scottish Government.

The information contained within this repository is either publicly available knowledge, derived from official Microsoft documentation, or has been deemed non-sensitive before publication.

No confidential or personal data is included.