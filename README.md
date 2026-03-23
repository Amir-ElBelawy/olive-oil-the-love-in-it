# Olive Oil The Love in It 
# زيت الزيتون طعم الأصالة

A fully RTL Arabic product landing page for a premium olive oil and thyme business based in Al Gharbia, Egypt. Built and deployed as a real commercial asset — not a demo. 

## What This Is

A single-file HTML/CSS landing page featuring:

- Full **right-to-left (RTL) Arabic** layout with proper typographic hierarchy
- **Arabic web fonts** — Amiri, Aref Ruqaa, Rakkas — loaded via Google Fonts
- Premium product menu with **tiered pricing** (500ml glass, dark glass, 3L tin, half-litre gift)
- **Light/dark theme toggle** with CSS custom properties
- Mobile-first responsive design
- Zero JavaScript dependencies — pure HTML and CSS

## The Build Story

The entire page was written through **English prompts to an Arabic-output target** — a deliberate cross-language AI-assisted workflow. The product content, pricing, and branding decisions are real business data. The code was generated, iterated, and debugged across a 26-message session covering layout issues, font rendering failures, RTL alignment edge cases, and screenshot/PDF export challenges.

This repo documents what it looks like when AI-assisted development crosses a language boundary — prompting in English to build something that functions entirely in Arabic, for an Arabic-speaking market, with Arabic typography that most Western-trained developers would not instinctively get right.

## Live Deployment

Deployed via GitHub Pages:  
👉 **[https://amir-elbelawy.github.io/olive-oil-the-love-in-it.io/](https://amir-elbelawy.github.io/olive-oil-the-love-in-it.io/)**

## Product Context

The olive oil is sourced and sold independently — extra virgin, acidity below 0.8%, verified by lab analysis. The menu reflects real SKUs and real pricing in EGP. This is not a portfolio mockup.

## Technical Notes

- All styling uses **CSS custom properties** for theming — no Sass, no build step
- RTL layout handled via `dir="rtl"` on the `<html>` element and logical CSS properties
- Font pairing chosen for premium Arabic calligraphic feel: Rakkas for display, Amiri for body, Aref Ruqaa for accents
- Fully static — deployable anywhere with zero configuration

## License

MIT
