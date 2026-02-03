# Piero Landing Page Specification

## Overview
A minimal, centered landing page for the Piero app TestFlight signup.

## Layout
- All content vertically and horizontally centered on the page
- Single column layout
- Full viewport height

## Design Tokens

### Colors
| Token | Value |
|-------|-------|
| Background | `#FAF8F3` |
| Logo text | `#1C1C1A` |
| Tagline text | `#5C5C58` |
| Button background | `#2596BE` |
| Button text | `#FFFFFF` |

### Typography
All text uses **New York** font (macOS system serif). Fallback stack: `"New York", "Times New Roman", Georgia, serif`

## Components

### Logo
- Text: `PIERO`
- Font: New York, bold
- Color: `#1C1C1A`
- Letter spacing: `4pt` (0.25em)
- Size: Large (suggest 48-64px)

### Tagline
- Text: `Your exhibition diary`
- Font: New York, regular
- Color: `#5C5C58`
- Letter spacing: normal
- Size: Medium (suggest 18-24px)
- Spacing: Below logo with comfortable margin

### CTA Button
- Text: `Try it now`
- Font: New York, semibold
- Text color: `#FFFFFF`
- Background: `#2596BE`
- Border radius: `3px`
- Padding: Comfortable (suggest 16px 32px)
- Link: `https://testflight.apple.com/join/XXXXXX` (replace with actual TestFlight link)

#### Button States
| State | Style |
|-------|-------|
| Default | Full opacity |
| Pressed/Active | `opacity: 0.85` |
| Hover | Optional subtle effect |

## Spacing
- Logo to tagline: ~16px
- Tagline to button: ~32px

## Technical Notes
- Simple static HTML/CSS (no framework needed)
- Responsive: content should remain centered on all screen sizes
- No JavaScript required except for button press effect
