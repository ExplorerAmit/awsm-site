# awsm brand: instructions for AI tools

Paste this whole file into any AI assistant (Claude, ChatGPT, Gemini, Canva AI, Copilot, etc.) before asking it to design, write code for, or describe anything for **awsm**, a co-working space and reading room in Kalyan West, Maharashtra. Web address: **awsm.im**.

These rules are strict. When a request conflicts with them, follow these rules and say so.

---

## 1. The most important rule

**Never redraw, regenerate or "recreate" the logo.** Always place the official file from the brand kit.

- Image generators (Midjourney, DALL·E, Firefly, Canva Magic Media, Gemini/Imagen, etc.) cannot reproduce a logo accurately. They will distort the symbol and misspell the name.
- For posters, social posts and mockups: generate the background artwork **without any logo or brand text**, leave clear empty space, and tell the person to place the official logo file there afterwards. Name the exact file to use (see section 6).
- In code (HTML, SVG, Flutter, React), use the official SVG files, or the exact symbol code in section 7. Do not approximate the symbol with letters, emoji or icon fonts.

---

## 2. Name

| Item | Correct | Wrong |
|---|---|---|
| Logo wordmark | `awsm` (all lowercase) | AWSM, Awsm, aWSM, awesome |
| Web-address wordmark | `awsm.im` (all lowercase) | AWSM.im, awsm.IM, awsm.in, awsm.com, www.awsm.im |
| Name inside sentences | **AWSM** (capitals) is fine in running text, e.g. "Welcome to AWSM." | Do not set "AWSM" in the logo typeface as if it were a logo |
| Meaning | AWSM = **A**wesome **W**ork **S**tudy **M**eeting place | |
| Domain | `awsm.im` (dot-i-m) | awsm.in |

---

## 3. Two versions of the logo, each with one job

Both are lowercase and use the same symbol, typeface and colours.

**`awsm`: the main logo (identity).** Use it for:
- shop sign, entrance door, reception wall, any physical signage
- website header and footer (people are already on the website)
- visiting cards, access cards, letterhead, invoices, receipts, stationery
- profile pictures and small spaces
- **default: if unsure, use `awsm`.**

**`awsm.im`: the web-address logo (promotion).** Use it where people must remember the address and visit later:
- posters, flyers, banners, standees, newspaper inserts
- social preview image (og:image), Instagram/Facebook/LinkedIn posts and ads
- event, hackathon and college tie-up material, sponsor slides

**Never put both versions on the same item.** If the main logo is `awsm` and the address is needed, write `awsm.im` as plain text (Inter, not the logo typeface), e.g. in a contact line.

---

## 4. Colours

Use these exact values. Do not invent tints, gradients or extra colours for the logo.

| Name | Hex | RGB | Use |
|---|---|---|---|
| Powder blue | `#8CAFCD` | 140, 175, 205 | Symbol tile; `.im` on dark backgrounds; buttons and accents on dark |
| Deep blue | `#3A5F80` | 58, 95, 128 | `.im` on light backgrounds; links and accent text on light |
| Ink | `#14161A` | 20, 22, 26 | The m and dot in the symbol; wordmark on light; dark backgrounds |
| Paper | `#F6F3EE` | 246, 243, 238 | Wordmark on dark; light backgrounds |
| White | `#FFFFFF` | 255, 255, 255 | One-colour version on photos/dark; cut-out signage |

Rules:
- The symbol is **always** an ink m-and-dot on a powder-blue rounded tile (except one-colour and cut-out uses in sections 5 and 8).
- `awsm` wordmark: ink on light backgrounds, paper on dark. Never blue.
- `awsm.im` wordmark: `awsm` as above; `.im` deep blue on light, powder blue on dark.
- **Never** use powder blue for text on light/white backgrounds (contrast is only about 2:1, unreadable). Use deep blue instead.
- The brand colour is powder blue. It was amber (`#F2A93B`) in early drafts. **Do not use amber, orange or teal anywhere.**

---

## 5. Typography

- **Logo wordmark:** Bricolage Grotesque, ExtraBold (800), all lowercase, letter-spacing **-0.035em** (tight). Free on Google Fonts.
- **Headings:** Bricolage Grotesque 700–800.
- **Body text, tagline, contact lines:** Inter 400–600.
- Tagline (optional, never inside the logo files): `CO-WORKING · READING ROOM`, Inter 600, all caps, wide letter-spacing (~0.25em).
- Do not substitute Montserrat, Poppins, Arial or other fonts for the wordmark. If the typeface is unavailable, use the outlined SVG/PNG files instead of typing the name.

---

## 6. Which file to use

All files are in the brand kit. SVG for anything that scales or prints; PNG for documents, slides and social tools.

| Need | File |
|---|---|
| Main logo, light background | `awsm/svg/awsm-horizontal-on-light.svg` |
| Main logo, dark background | `awsm/svg/awsm-horizontal-on-dark.svg` |
| Main logo, centred / square space | `awsm/svg/awsm-stacked-on-light.svg` or `-on-dark.svg` |
| Main logo, one colour (stamps, engraving, photos) | `awsm/svg/awsm-horizontal-mono-ink.svg` or `-mono-white.svg` |
| Web-address logo, light background | `awsm-im/svg/awsm-im-horizontal-on-light.svg` |
| Web-address logo, dark background | `awsm-im/svg/awsm-im-horizontal-on-dark.svg` |
| Web-address logo, stacked | `awsm-im/svg/awsm-im-stacked-on-light.svg` or `-on-dark.svg` |
| App icon, profile picture | `icon/png/awsm-icon-1024.png` (rounded) |
| Website favicon | `website/favicon.ico` + `website/images/favicon.svg` |
| Social link preview (og:image) | `social/og-image.png` (1200×630, uses `awsm.im`) |
| Physical signage cut-outs | `signage-cutout/` (see section 8) |

---

## 7. The symbol, exact geometry

The symbol is a lowercase **m** drawn as an open book seen side-on, with a dot above the middle stroke: a person reading behind a book. The middle stroke and the dot also form an "i", echoing ".im". Never add details, faces, shadows, outlines, 3D, gradients or extra marks.

Exact SVG (copy as-is; scale with width/height only):

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 120" role="img" aria-label="awsm">
  <rect width="120" height="120" rx="27" fill="#8CAFCD"/>
  <path d="M27 95V67a16.5 16.5 0 0 1 33 0v28M60 67a16.5 16.5 0 0 1 33 0v28"
        fill="none" stroke="#14161A" stroke-width="14" stroke-linejoin="round"/>
  <circle cx="60" cy="33" r="9.5" fill="#14161A"/>
</svg>
```

Proportions to keep:
- Tile corner radius = 22.5% of tile width (27 of 120).
- Below 32 px, use the heavier favicon variant (`icon/svg/awsm-favicon.svg`: stroke 16.5, dot radius 11.5).
- The symbol is never used without its tile except in the one-colour versions (`icon/svg/awsm-symbol-*.svg`).

HTML/CSS lockup for websites (matches the official files):

```html
<a href="/" class="awsm-logo" aria-label="awsm home">
  <svg viewBox="0 0 120 120" aria-hidden="true">
    <rect width="120" height="120" rx="27" fill="#8CAFCD"/>
    <path d="M27 95V67a16.5 16.5 0 0 1 33 0v28M60 67a16.5 16.5 0 0 1 33 0v28" fill="none" stroke="#14161A" stroke-width="14" stroke-linejoin="round"/>
    <circle cx="60" cy="33" r="9.5" fill="#14161A"/>
  </svg>
  <span>awsm</span>
</a>
<style>
  .awsm-logo { display:inline-flex; align-items:center; gap:0.4em; text-decoration:none;
    font-family:"Bricolage Grotesque",sans-serif; font-weight:800; font-size:25px;
    line-height:1; letter-spacing:-0.035em; color:#14161A; }      /* on light */
  .awsm-logo svg { width:1.36em; height:1.36em; flex:none; }
  .on-dark .awsm-logo { color:#F6F3EE; }                          /* on dark  */
</style>
<!-- Load: https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,800&display=swap -->
```

For `awsm.im` in HTML: `<span>awsm<span style="color:#3A5F80">.im</span></span>` on light, `#8CAFCD` on dark.

---

## 8. Cut-out version (physical signage only)

Files in `signage-cutout/`: the m and dot are cut away from the tile so the surface behind shows through. One single compound path, ready for laser cutting, etching on frosted glass, vinyl cutting, CNC routing or debossing.

- Use **only** for physical signage and materials.
- **Never** use the cut-out on screens, websites, apps, social media, favicons or print documents. Use the solid versions there.

---

## 9. Layout rules

- **Clear space:** keep empty space around the logo of at least half the tile's height on every side. Nothing (text, edges, photos' busy areas) inside it.
- **Minimum size:** horizontal logo at least 24 px tall on screen / 8 mm in print; icon at least 16 px.
- **Gap** between tile and wordmark = 22% of tile height. Wordmark x-height is centred on the tile. Do not rearrange, resize one part, or put the wordmark on the left.
- On photos, place the logo on a calm, dark or light area. If contrast is weak, use the one-colour white or ink version, or a solid backing panel.

---

## 10. Never do this

- Never redraw the logo with an AI image generator, or type it in another font.
- Never change capitalisation: no "AWSM" or "Awsm" in the logo.
- Never write "awsm.in", "awsm.com" or "www.awsm.im".
- Never use amber/orange (old draft colour), teal, purple, gradients, glows, shadows, outlines or 3D effects on the logo.
- Never recolour the tile (except one-colour and cut-out versions) or make the m and dot blue.
- Never stretch, squash, rotate, skew or crop the logo.
- Never put powder-blue text on a white/light background.
- Never show `awsm` and `awsm.im` logos together on one item.
- Never add the tagline, address or phone number inside the logo artwork; set them separately in Inter.
- Never use emoji, a building, a laptop, a coffee cup or a generic "co-working" icon as a stand-in for the symbol.

---

## 11. Brand facts (for copy)

- Name: AWSM (Awesome Work Study Meeting place). Logo: awsm. Web: awsm.im
- What: a quiet co-working space and reading room
- Where: Office 212, 2nd Floor, Corner Stone, Near Yogidham, Kalyan West, Maharashtra 421301
- Hours: 7:00 am – 10:00 pm, all 7 days
- Phone / WhatsApp: +91 98909 30707
- Map: https://maps.app.goo.gl/SVDUFAnnZykLd4G38
- Tone: calm, friendly, focused, clear. No hype, no exclamation-mark marketing.
- Check prices and offers with the owner before publishing; they change.

---

## 12. Prompt template for image generators

Use this when creating a poster, post or mockup background. The logo is added afterwards.

> Create a [poster / Instagram post / banner] background, [size, e.g. 1080×1350]. Calm, modern, minimal style. Colour palette strictly: powder blue #8CAFCD, ink #14161A, warm paper #F6F3EE, white, with deep blue #3A5F80 for small accents. Subject: [e.g. a quiet reading room with desks, warm daylight, people studying]. **Do not include any logo, letters, brand name, text or watermark.** Leave a clear, uncluttered empty area at the [top-left / bottom-centre] about [25%] of the width for a logo to be placed later. No orange, no amber, no teal, no neon, no gradients.

Then place `awsm-im/png/awsm-im-horizontal-on-dark.png` (or `-on-light`) in the empty area, and set headline and details in Bricolage Grotesque / Inter.

---

## 13. Self-check before delivering

An AI must confirm all of these before handing over work:

1. The logo is an official file (or the exact SVG in section 7), not a redraw.
2. Lowercase `awsm` / `awsm.im` in the logo; correct domain `awsm.im`.
3. Right version for the job: `awsm` for identity, `awsm.im` for promotion; not both together.
4. Colours are exactly `#8CAFCD`, `#3A5F80`, `#14161A`, `#F6F3EE`, `#FFFFFF`; no amber.
5. `.im` is deep blue on light / powder blue on dark; no powder-blue text on light.
6. Clear space and minimum size respected; nothing stretched or effects added.
7. Cut-out version used only for physical signage.
