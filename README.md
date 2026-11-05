# Damage Claims (Storm Damage) Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) landing page for **storm damage insurance claim help** sponsored by **McIntyre Law P.C.**, built on the framework of your uploaded resident care page (`index-9.html` / `style-9.css` — byte-identical to the delivered resident care files, so the same infrastructure carries forward) and filled with content from **damageclaimshelp.com**. Per your instruction, the law firm and disclaimer information were updated to this firm, and placeholder areas were left for pictures, branding, and parallax section backgrounds.

## Kept from your framework, unchanged

- Page structure, classes, the MTAA CIPA block script, your Meta Pixel (`1238664640565416`, including your `fbq('track', "ViewContent")` line), and your form embed: `forms.mtaa.ai/f/nf_14bb49f057af4602b5676b8892df3c32`, in the overflow form card — the container hangs past the hero over the section below it, the frame scrolls internally with `overflow: auto` if the embed runs tall, and your mobile values are preserved.
- Your design elements from the framework: the `.basic-imaga` photo style, the two parallax variants (`.section-parallax` on the hero, `.section-parallax-info1` on the middle section), the two-column image layout in the middle section, and the two-column attorney area.
- The call/text consent paragraph and the footer legal links to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com, as in the framework.

## Phone number — none

The page is **phoneless**: the live rendered damageclaimshelp.com displays no phone number anywhere (header, hero, middle, and footer all checked). Nothing to add unless the firm provides one.

## Placeholders left for you, as instructed

- **Branding:** the logo slots (hero eyebrow and footer) are `images/REPLACE-LOGO.png`. (Their logo is a red serif wordmark, "NOBLE McINTYRE / McIntyreLaw P.C."; the commented-out header carries the firm name as a text logo, and the CSS logo text keeps a serif for that reason — see below.)
- **Pictures:** the middle section's side photo is `images/REPLACE-DAMAGE-IMAGE.jpg`. The attorney area's photos are slots: `images/attorney-photo-1.jpg` under **Noble McIntyre — Senior Partner** (his name, title, and role as senior partner and owner of the firm are real, from the sample; only his photo is a placeholder) and `images/attorney-photo-2.jpg` with a `[Attorney Name]` / `[Title]` caption.
- **Parallax backgrounds:** both parallax blocks keep your code, overlay tint recolored to this site's slate hero tone (`--overlay-rgb: 53, 95, 112`, opacity 0.75), and the image lines were already placeholders in your upload — `YOUR-IMAGE-URL-HERE` (hero) and `YOUR-IMAGE-URL-HERE-2` (middle section) in `css/style.css`.

## Colors and typeface

`css/style.css` is your uploaded `style-9.css` with **color values and heading font-family values only** changed (diff-verified). Palette sampled from the rendered damageclaimshelp.com on 2026-11-04:

- Slate blue-grey `#355f70` and blue `#5499b6` through the hero gradient, into dark teal `#305869` for the top bar, dark surfaces, and footer
- Gold `#c9a86a` for kickers, headline accents, checkmark circles (white checks), and the CTA buttons with white text — their buttons are a pale-to-dark gold gradient (`#e8d5a3` to `#8c6d2e`); the framework's flat button takes the mid gold, with the dark gold-brown `#8c6d2e` as the hover state
- Sky blue `#9ad3eb` (their "State Farm" headline accent) for highlights on dark backgrounds
- Near-white `#fafafa` (their footer tone) for the results band; white page background. Their red logo accent (`#a6192e`) was not mapped — the framework's logo areas are image placeholders.
- Typeface: their headlines and body are a bold, clean sans-serif (Montserrat/Arial-like), so the hero title and section titles switch **back** from the last build's Georgia serif to Inter/Arial sans. The one serif element on their page is the logo wordmark, so the CSS `.logo-text` keeps Georgia. The form heading stays sans, as in the framework. Colors are close visual approximations sampled from the rendered page.

## Content (from damageclaimshelp.com)

- Hero: their headline — "Did State Farm Deny or Underpay for Storm Damage?" — with "You don't have to accept your insurer's decision," the free case review, and "No upfront costs, no pressure."
- The Help You Need. The Justice You Deserve. — the team focuses exclusively on helping homeowners recover what they're owed after the storm; insurer tactics to delay, deny, or diminish; time limits apply.
- You Deserve Full Compensation — Not Excuses — their checklist: challenge denied wind and hail damage claims, fight back against underpaid settlements, get the funds to fully repair and restore your home.
- Damage They Delay, Deny, or Diminish — nine cards: hail (including the long-running lawsuits accusing State Farm of a billion-dollar hail scheme), wind, tornado, roof damage (contractors requiring full replacement), denied claims, underpaid settlements, delay tactics, L.A. fire claims, and time limits.
- Over 100 Years of Combined Experience — their experience heading, their track-record line (helped over 200 cases in property insurance claims alone), and their contingency terms: "we don't get paid unless you win," no fees until we win, serving clients in Oklahoma, New Mexico & nationwide.
- What We Look At — their partner-with-us copy and their form's details: the insurer, denied in full / part denied / underpaid, damage type, and the damage year (2026 back to before 2020).
- Disclaimer: their sponsor line — "THIS IS ATTORNEY ADVERTISING sponsored by McIntyre Law P.C. located at 8601 S. Western Ave, Oklahoma City, OK 73139, USA" — plus the contingency line and the framework consent paragraph.

## Files

```
github-damage-claims-landing-page/
├── index.html
├── css/style.css   (your framework CSS, colors + heading fonts only changed)
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
