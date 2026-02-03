# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static landing page for **Piero**, an exhibition diary iOS app. The page drives users to an Apple TestFlight signup link. No framework, build system, or package manager — just plain HTML/CSS.

## Tech Stack

- Static HTML/CSS only, no JavaScript
- No build step — open `index.html` directly or serve with any static file server

## Design Spec

The full specification lives in `piero-landing-spec.md`. Key tokens:

- **Font:** "New York" (macOS system serif) with fallback `"New York", "Times New Roman", Georgia, serif`
- **Background:** `#FAF8F3` (warm off-white)
- **Tagline color:** `#5C5C58`, **Button:** `#2596BE` bg / `#FFFFFF` text
- **Copyright color:** `#B0AEA8`
- **Layout:** Single centered column, full viewport height with `padding-bottom: 8vh` for optical vertical centering

## Architecture

Single-page site with:
- **Logo:** `PieroWebLogo.png` — a 3x retina PNG displayed at 63px height. The logo is an image, not text.
- **Tagline:** "Your exhibition diary"
- **CTA button:** "Try the app" linking to TestFlight (placeholder URL — replace `XXXXXX` with real ID)
- **Copyright:** fixed to bottom-right corner

All main content is vertically and horizontally centered using flexbox on the body.
