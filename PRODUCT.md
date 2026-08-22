# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Two audiences, treated as roughly equal priority:

- **Local/passerby discovery** — people in Cidade Baixa, Porto Alegre (or searching the neighborhood) encountering Gracejo 831 for the first time, deciding whether it's worth a visit.
- **Existing Instagram followers** — people who already follow @gracejo831_ and land on the page to confirm hours, address, and menu before showing up in person.

Both audiences convert one of three ways: reserving via Instagram DM (there is no booking system), getting directions to the physical address, or walking through the "Pedir Online" mockup to see how a real ordering flow would feel.

## Product Purpose

A two-page presentation site for Gracejo 831, a parrilla-and-bar restaurant in Cidade Baixa, Porto Alegre: `index.html`, the landing page, and `pedir.html`, an honest mockup of an online-ordering flow (pickup only, front-end only, no order actually reaches the kitchen). It exists to convert either audience into a reservation (via Instagram), an in-person visit, or a look at what ordering online could feel like, by conveying the house's food, wine, and atmosphere credibly enough to act on.

**This is currently a pitch mockup**, not the live production site — built to present the concept to the restaurant's owner (the footer explicitly marks it: "Mockup de apresentação"). Treat visual and content decisions accordingly: the bar is "convincing enough to sell the owner on this direction," not yet "shipped and load-bearing for real customers."

## Positioning

Brazilian parrilla with the informality of a corner neighborhood bar — not a formal steakhouse. The stated hook: low-heat asado technique, a hand-picked wine list, and a house that welcomes dogs at the table. Success is being read as a bairro institution you'd return to on a Tuesday, not an occasion-only destination.

## Operating Context

- Reservations happen exclusively through Instagram DM/profile (`@gracejo831_`) — there is no real booking widget or phone-based flow. `pedir.html` simulates an online-ordering flow as a mockup (see Product Principles), but it is not a live reservation or booking system.
- The restaurant is physically pet-friendly (dogs welcome at tables), which is a stated differentiator, not incidental copy.
- Hours: closed Mondays; Tue–Fri 17h–23h59; Sat/Sun/holidays 11h–23h59.
- Location: Av. Venâncio Aires, 831, Cidade Baixa, Porto Alegre — RS.

## Capabilities and Constraints

- Static HTML/CSS, no framework, no backend, no build step. Two pages (`index.html`, `pedir.html`) share design tokens, nav, buttons, and footer via `styles.css`; page-specific styles stay inline per page.
- On the landing page, the menu is presented as six categories (Parrilla, Fake/petiscos, Hambúrgueres, Pizza, Sobremesas, Vinhos & Drinks) with a link out to the full menu in the restaurant's Instagram highlights — the full itemized menu/wine list is not reproduced there by design.
- `pedir.html` is a front-end-only ordering mockup: a real (illustrative) item list with prices across the same six categories, a cart, and a checkout form. Submitting the form clears the cart and shows a JS-only success state that explicitly discloses it is a simulation and points the visitor to Instagram for a real order. No payment, delivery, or backend exists or is implied; pickup only.
- The "Ambiente" mood grid uses AI-generated photography (via Higgsfield) standing in for real venue photos; the page copy itself discloses these are generated images and that the real photo gallery belongs there "na versão final" (in the final version). Real venue photos are a known gap, not an oversight to silently fill with stock imagery — and the generated images should not be mistaken for real photos of this specific venue.
- Portuguese (pt-BR) copy throughout; voice is warm, informal, a little playful (matches the "gracejo" = wisecrack/joke naming).

## Brand Commitments

- Name: Gracejo 831 (831 references the street address).
- Instagram: @gracejo831_ — the sole reservation/contact channel.
- Existing visual system (charcoal/ember/malbec palette, Bricolage Grotesque + Instrument Serif + Archivo type, film-grain texture, ember-glow hero) is the incumbent identity for this project; preserve it as authority unless the user asks for a redesign.
- Real customer quote in use: "O pão de alho é impossível de parar de comer." — cited as "cliente, Tripadvisor." Treat as real evidence, not a placeholder to be swapped without checking.

## Evidence on Hand

- One real testimonial fragment (Tripadvisor, garlic bread quote) — no other reviews, press, or case studies on hand. Do not fabricate additional testimonials, ratings, or press mentions.
- No real venue photography yet; the "Ambiente" section uses AI-generated stand-in images (disclosed as such) awaiting real photos.
- Address, hours, and Instagram handle are confirmed real facts (already live in the copy) and should be preserved exactly across any redesign.

## Product Principles

1. Preserve the bairro-parrilla warmth over polish that reads corporate or fine-dining — the informality is the differentiator, not a gap to close.
2. Reservations stay Instagram-first; don't invent a real booking/contact mechanism this restaurant doesn't have. The one deliberate exception is `pedir.html`: an honest, clearly-disclosed front-end mockup of online ordering, never presented or wired as if it were live.
3. Keep real facts (address, hours, handle, the one real quote) exact and unchanged; keep placeholder content (mood-grid imagery) legible as placeholder rather than dressed up as final.
4. Since this is a pitch mockup, bias toward the version that best sells the owner on the direction — ambition and polish matter more here than they would on a already-launched site.

## Accessibility & Inclusion

No product-specific accessibility requirement has been established beyond standard web accessibility practice.
