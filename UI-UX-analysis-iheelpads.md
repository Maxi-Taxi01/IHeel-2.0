# UI/UX Analysis — iheelpads.com (current site)

Reviewed 2 July 2026, desktop viewport. Scope: homepage (which doubles as the product page — there is no dedicated product page). Benchmark: the 2026 iHeel® brandbook and the stated primary audience (women).

## Summary

The site communicates *what* the product does, but the execution undercuts the premium positioning. It looks like a template store from 2018: mixed visual styles, clinical blister photography, inconsistent buttons, and a wall of SEO text on the homepage. For a product whose main buyers are women choosing comfort for heels and flats, the current experience feels neither warm nor trustworthy. Conversion path is also muddled: the site sells on Bol.com but presents itself like a shop.

## What works

The tagline "Step comfortably, every day" is already in place and matches the new brand promise. The four USP blocks (Precision-Cut Comfort, Long Lasting, Stop Blisters, Easy to Attach) map 1:1 onto the brandbook's USP framework, so the content skeleton can be kept. Free-shipping bar and multilingual instructions signal care. Navigation is short and understandable.

## Key issues

**1. Visual identity is incoherent.** The hero uses three overlapping circular photo crops on a flat beige block; below it sits a product shot on a *black perforated-metal* background (directly against the brandbook's "warm, never clinical/dark" imagery rule); the benefit sections use amateur cut-out photos of blistered heels with a pile of used band-aids. Premium claim, drugstore execution.

**2. Clinical/medical imagery.** Close-ups of open blisters and red, irritated skin are exactly what the brandbook's Imagery Don'ts prohibit ("no medical close-up foot imagery"). For the core female audience this reads as repellent rather than empathetic — the pain point can be told through a slipping pump or a paused walk, not a wound.

**3. CTA chaos.** At least four button styles compete: black-outline "SHOP NOW ON BOL.COM", a beige "Where to buy?" ghost button with low contrast (white text on light taupe — fails WCAG AA), and a text link "Check Availability on Bol.com". No single visual hierarchy tells the user what the one desired action is. Buttons also mix casing and copy style.

**4. Typography and logo.** Body text is rendered in a rounded display-ish font throughout, with near-identical weight for headings and paragraphs, so nothing establishes hierarchy. The current logo (grey handwritten wordmark + beige pad icon) is low-contrast against the white header and disappears at small sizes.

**5. The homepage is an SEO article.** Roughly half the page is a 1,000-word blog post ("Say Goodbye to Heel Discomfort…") pasted onto the homepage, including academic-style citations. It buries the conversion moment and signals "affiliate site", not brand.

**6. Contradictory claims.** "Highest Quality Product" and "Best Price — lowest price on the market guaranteed" sit in the same trust bar. The brandbook explicitly forbids combining premium-quality and lowest-price claims because they undermine each other.

**7. Missing social proof.** The brand's strongest assets — 4.4/5 on Bol.com, 9.4/10 seller rating, 5,000+ users, #1 seller, founder story — are absent from the homepage. Reviews are the primary trust driver for this category and audience.

**8. Performance/robustness.** Sections load with heavy scroll-triggered fade-ins that leave blank screens mid-scroll (observed repeatedly during testing: whole viewports rendering empty for seconds). Scroll-jacking animations on a content site add friction with zero payoff, and hurt Core Web Vitals.

**9. Women are not addressed.** Imagery is generic stock; copy is gender-neutral to a fault. The one photo of pink pumps is the closest the page gets. High heels, flats and the "new shoes, first blister" moment — the highest-intent female use cases — are never spoken to directly.

**10. No founder presence.** The brand's differentiator (Rik's story, small batches, <1% rejection rate) exists only on a secondary page. The homepage tells the customer nothing an anonymous drop-shipper couldn't claim.

## Priority recommendations (implemented in the rebranded page)

1. One CTA style: Rosewood primary button, imperative copy ("Shop now on Bol.com"), repeated per section.
2. Replace clinical imagery with warm, lifestyle-led photography direction per brandbook (feet/shoes in motion, linen backgrounds, golden light; women's shoes as hero context).
3. Move the SEO article to The Blog; homepage keeps pain → solution → proof → CTA.
4. Surface social proof (Bol.com ratings, user count, #1 seller) high on the page, and the founder story with the "Your pain was my pain too" quote.
5. Apply the brandbook type system (Neue Einstellung display / Libre Franklin body) and 60/15/10/10/5 palette ratio.
6. Drop "lowest price guaranteed"; keep quality, shipping, returns.
7. Rewrite copy in founder voice: "I" and "you", short active sentences, every claim backed by a number.
