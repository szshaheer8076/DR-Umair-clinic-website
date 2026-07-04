# Dr. Umair Irfan — Dermatology Clinic Website

A single-file static website for a dermatology clinic based in Lahore,
built as an SPA with client-side routing in one `index.html`.

## What this project involved

- **SPA routing**: Client-side navigation without a page reload, implemented
  in vanilla JS.
- **Semantic markup**: Converted the nav structure to semantic HTML for
  accessibility and cleaner DOM structure.
- **Lead capture**: Contact form redirects to WhatsApp with pre-filled
  message content, matching how the clinic actually wants to receive
  inquiries.
- **Visual polish**: Scroll-triggered animations, real Framer CDN assets,
  and an embedded (base64) clinic profile photo — no external image
  hosting dependency.
- **Social integration**: Social media icons linked to the clinic's active
  profiles.

## Stack

- Single `index.html` (HTML/CSS/JS, no framework, no build step)
- Framer CDN assets for animation/motion primitives

## Notes

This is intentionally a single-file deployment — no bundler, no framework.
That was a scope decision for a small clinic site with a fixed, simple
page structure, not a limitation of the build process.
