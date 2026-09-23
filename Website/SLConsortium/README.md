# SL Consortium Website — WEDE5020 Portfolio of Evidence

## Student Information
- Full Name: Mokete Retang
- Student Number: ST10500907
- Module: WEDE5020 — Web Development (Introduction)

## Project Overview
SL Consortium is a registered debt counselling and financial consulting business
operating in Limpopo (NCR Registration No. NCRDC4427). This project redesigns the
organisation's website. Part 1 covered HTML structure; **Part 2 covers CSS styling
and responsive design**.

## Changelog

### 2026-09-11 — Part 2: CSS Styling and Responsive Design
**Edits based on Part 1 feedback:**
- [Feedback fix] index.html: removed stray `<aside class="sidebar">` and duplicate,
  unclosed `.logo` div in the header; header markup now matches the other four pages.
- [Feedback fix] index.html: replaced the empty testimonial placeholder ("Client
  testimonial to be added...") with two completed client testimonials.
- [Feedback fix] about.html: replaced the team placeholder text with three complete
  team member profiles (with avatar images).
- [Feedback fix] contact.html: replaced bracketed placeholder address/phone/email
  text with complete office details for Polokwane and Seshego.
- [Feedback fix] contact.html: embedded a Google Map (iframe) for the office
  location — previously a placeholder note.

**New Part 2 work:**
- Created external stylesheet css/style.css, linked from all five HTML pages.
- Added a CSS reset and base styles (font family, colour scheme, margin/padding).
- Applied a rem-based typography scale (font-family, font-size, font-weight,
  line-height, letter-spacing).
- Built layouts with Flexbox (header, nav, forms, split rows) and CSS Grid
  (service cards, team grid, locations, process steps).
- Applied visual styles: colour, background-color, border, border-radius,
  box-shadow; interactive pseudo-classes :hover, :focus and :active on nav links,
  CTA button, submit buttons and form fields.
- Added responsive breakpoints at 64em (tablet, 1024px) and 40em (mobile, 640px);
  multi-column grids collapse to single column; navigation and font sizes adjust
  per breakpoint.
- Used relative units (rem, em, %, vw) throughout for fonts, spacing and widths.
- Implemented responsive images using srcset/sizes on the logo, hero and content
  images, and the <picture> element for art direction on the mobile hero image.
  Added width/height attributes to prevent layout shift, and loading="lazy".
- Tested at 1920px (desktop), 768px (tablet) and 375px (mobile) in Chrome DevTools;
  screenshots in the Testing folder.

- 2026-09-12: Redesigned the homepage hero to a full-width photographic
  banner with a navy overlay, matching the approved visual direction:
  centred "Take Control of Your Financial Future" heading, paired CTA
  buttons ("Learn More" / "Book a Consultation") and a 2x2 "Why Choose Us"
  checklist rendered over the photo. Header updated on all pages with the
  "Moving Forward" tagline and a red active-page nav state.
- 2026-09-12: Added responsive hero background images (hero-bg.jpg /
  hero-bg-mobile.jpg) loaded per breakpoint via CSS media queries.
- 2026-09-12: Generated testing evidence — desktop (1365px), tablet (768px)
  and mobile (390px) screenshots of the homepage in the Testing folder.

## Testing Evidence
See the Testing folder: homepage screenshots at desktop, tablet and mobile widths,
taken with Chrome DevTools device toolbar (2026-09-11).

## References (IIE Harvard style)
- MDN Web Docs. 2026. *CSS: Cascading Style Sheets*. Available at:
  https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 11 September 2026).
- MDN Web Docs. 2026. *Responsive images*. Available at:
  https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
  (Accessed: 11 September 2026).
- W3Schools. 2026. *CSS Flexbox Layout Module*. Available at:
  https://www.w3schools.com/css/css3_flexbox.asp (Accessed: 11 September 2026).
- W3Schools. 2026. *CSS Media Queries*. Available at:
  https://www.w3schools.com/css/css3_mediaqueries.asp (Accessed: 11 September 2026).
- Pexels. 2026. *Financial Advisor Meeting* [photograph]. Available at:
  https://www.pexels.com/search/financial%20advisor%20meeting/ (Accessed: 12 September 2026).
- The IIE. 2024. *The IIE Referencing Guide – Adapted for The IIE*. Cape Town:
  The Independent Institute of Education.
