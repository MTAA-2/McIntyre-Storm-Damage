# McIntyre Law P.C. — Storm Claim Justice (Design Build)

Static landing page (HTML + CSS only, no PHP) built directly from the
user's uploaded design image, rather than from the usual landing-page
framework.

## Files

- `index.html` — the page
- `css/style.css` — all styling

## Layout (follows the image closely)

- Dark navy top bar: "Storm damage claim help • No upfront costs"
- White header: McINTYRE LAW P.C. wordmark with the "Storm Claim
  Justice" tagline, nav (How it works / About the firm), gold
  "Free Claim Review" button
- Cream hero: teal eyebrow "Denied or Underpaid Storm Claims," serif
  headline "Allstate denied your claim. What happens next?", intro
  copy, three teal-check trust lines, and the storm-damaged-home photo
  area with its caption
- White form card: "FREE • NO OBLIGATION" pill, "Get your free claim
  review," the **iframe embed area**, the privacy note, and the light
  teal "What happens next?" box
- White trust strip: McIntyre Law P.C. / No upfront costs / Oklahoma
  City (8601 S. Western Ave)
- "A clear path forward." — three numbered cards (Tell us what
  happened / We review your claim / Understand your options)
- "Your home matters. So does who you trust." — Noble McIntyre,
  Senior Partner, beside a 2×2 grid of damage tiles (Hail / Wind /
  Tornado / Roof) with line icons
- "Before you get started" — three FAQ items, first open by default
  (pure HTML `<details>` accordions, no JavaScript)
- Dark navy CTA band: "Find out where your claim stands." + gold
  "Get My Free Claim Review" button
- Footer: firm name and Oklahoma City address; "Attorney advertising.
  Prior results do not guarantee a similar outcome." with Privacy
  Policy / Disclaimer links; the image's "Design concept • Intake
  appearance illustrative" note kept at the foot (remove before
  publishing if not wanted)

Palette: navy #1C2F4B, gold #C07A1E, teal #1F8A70 with tint #E3F2EE,
cream #F7F2EB, lines #E4DDD2. Headlines and brand in Georgia serif, UI
text in Inter.

## Embeds carried over

- Form iframe: the current framework MTAA embed
  (nf_3270a8a1b0e4425cb70e9f97f2fa5a3c) sits in the card's embed area —
  swap its `src` to change forms. The frame area scrolls internally.
  The mock's first-step fields (denied/underpaid, ZIP code, Continue)
  are served by the embedded form itself.
- MTAA CIPA block and Meta Pixel 1238664640565416 (ViewContent) in the
  head, as on the other pages (invisible; does not affect the design).

## Notes

- The headline follows the mock and names **Allstate**. The firm's
  earlier storm-damage page was State Farm-focused — if this campaign
  is also State Farm, the headline is a one-word swap.
- Placeholders: the hero photo is a styled placeholder box. Replace the
  `.photo-box` div with an `<img>` (markup shown in an HTML comment in
  index.html) to drop in the real photo.
