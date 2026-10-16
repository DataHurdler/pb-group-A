# UNO Brand Specification for the Workshop

Status: **mostly resolved** from the University of Nebraska Omaha's official
online brand guide, run by the Office of Strategic Marketing and
Communications. Open items are in
[NEEDS-CONFIRMATION.md](../../NEEDS-CONFIRMATION.md). The values here are
applied in the [consolidated deck](../slides/consolidated-deck.md#brand-and-accessibility).

Sources, all official `unomaha.edu` pages, checked October 16, 2026:

| Key | Page |
| --- | --- |
| COLORS | [Brand Colors](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/online-brand-guide/graphic-styles/index.php) |
| VIDEO | [Branding in Video and Bug](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/online-brand-guide/photography-and-videography/branding-in-video.php) |
| TYPE | [Typography](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/online-brand-guide/graphic-styles/typography.php) |
| LOGO | [University Logo (System Logo)](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/online-brand-guide/official-logos-and-marks/index.php) |
| LOCKUP | [Logo Lock-up](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/online-brand-guide/official-logos-and-marks/lock-up.php) |
| ICON | [Campus Icon](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/online-brand-guide/official-logos-and-marks/campus-icon.php) |
| FILES | [Logos (downloads)](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/marketing-and-brand/logos.php) |
| TEMPLATES | [UNO-Branded Templates](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/marketing-and-brand/uno-templates.php) |
| WCAG | [WCAG 2.1, contrast minimum](https://www.w3.org/TR/WCAG21/#contrast-minimum) (W3C, for the contrast check only) |

## 1. Resolution log, items 1–19

| # | Issue | Resolved value | Source | Status |
| --- | --- | --- | --- | --- |
| 1 | Brand source given as `[GitHub repo URL]` | No brand repository was provided. Used UNO's official online brand guide and Logos download page instead | All pages above | **Resolved** (official source substituted) |
| 2 | Primary color | **Black.** "Black should be front and center"; black, gray, or white must dominate. Screen value **#000000**, read from the official RGB logo file `uno-logo-color.png`; the brand pages show swatches only, no hex | COLORS; FILES ([uno-logo-color.png](https://www.unomaha.edu/office-of-strategic-marketing-and-communications/_files/uno-logo-color.png)) | **Resolved** (hex from official file) |
| 3 | Secondary or accent color | Secondary: **dark gray #474648** (RGB 71/70/72), **light gray #BCBBBA** (188/187/186), **white**. Accent: **red**, PMS 186; screen value **#DE1D24** from the official RGB logo file. Red at most 20% of a composition, never dominant, never a slide background | COLORS; VIDEO; LOGO; FILES | **Resolved** (red hex from official file) |
| 4 | Text colors on primary and light backgrounds | White text on black; black text on white ("use on white background slide only" / "use on black background slide only") | VIDEO | **Resolved** |
| 5 | Standard background color | White for content and YOUR TURN slides; black for title and divider slides. Never red | VIDEO; COLORS | **Resolved** |
| 6 | Heading font and fallback | **URW Grotesk** (required for UNO-branded publications), Medium weight for headings. Fallback where unavailable, e.g. PowerPoint: **Arial Narrow or Helvetica**. Licence limited to UNO employees | TYPE | **Resolved** |
| 7 | Body font and fallback | **URW Grotesk** Regular or Light; same fallback. Secondary serif: Liberation Serif (fallback Times New Roman or Sabon Roman), not used in this deck | TYPE | **Resolved** |
| 8 | Full-color logo file | University Logo two-color: `uno-logo-color.png` (screen), `uno-logo-color.eps` / `uno-logo-pantone.eps` (print). Also Lock-up "Color - Black" and Campus Icon color versions | FILES | **Resolved** |
| 9 | Reversed logo for dark backgrounds | All-white versions: `uno-logo-white.png`, `uno-lock-up-white.png`, `uno-icon-white.png` (EPS for print). On dark backgrounds all type is white; no two-color logo on black | LOGO; FILES | **Resolved** |
| 10 | Logo placement on each layout | The brand guide gives no placement rule; it only requires legibility and strong contrast behind the logo. The official PowerPoint template probably sets placement, but it's hosted on University of Nebraska SharePoint and wasn't opened | LOGO; TEMPLATES | **Open** |
| 11 | Logo clear space | University Logo and Lock-up: the height of the "O" in "Omaha", scaling with the logo. Campus Icon: the width of the O's black and red bands | LOGO; LOCKUP; ICON | **Resolved** |
| 12 | Minimum logo size | University Logo 1 in wide · Lock-up 1.75 in (including divider line) · Campus Icon 0.35 in print, 38 px digital | LOGO; LOCKUP; ICON | **Resolved** |
| 13 | Official slide template | A UNO PowerPoint template exists (on SharePoint), and Canva templates for licensed users. Not opened, so its layouts haven't been compared with this deck | TEMPLATES | **Partly resolved** |
| 14 | Document or letterhead template | "Digital Letterhead" (Word) and "General Document" templates are downloadable. Not yet downloaded or applied to the syllabus | TEMPLATES | **Partly resolved** |
| 15 | Required wordmark, lockup, or co-branding | University Logo required on all communications; Campus Icon required too but doesn't replace the logo; use the Lock-up when space is short. No unit-specific logos. No guidance found on department names or partner logos | LOGO; ICON; LOCKUP | **Partly resolved** |
| 16 | Print body size | The typography page gives no size guidance. The syllabus keeps 11 pt minimum, an accessibility choice, not a brand value | TYPE | **Open** |
| 17 | Contrast of every text and background pair | White on black 21:1 · white on dark gray 9.39:1 · black on light gray 10.96:1 · dark gray on white 9.39:1 · red on white 4.88:1. **Red on black 4.31:1 fails** 4.5:1, so red is never used for text on black | WCAG, using the values in rows 2–3 | **Resolved** |
| 18 | Syllabus fits two pages in brand fonts | Can't verify: URW Grotesk is licensed to UNO employees and isn't available here. Needs a print test | TYPE | **Open** |
| 19 | Date | A scheduling decision, not a brand value; a brand search can't answer it | — | **Open** |

## 2. Brand values in use

| Name | Value |
| --- | --- |
| `brand-primary` | Black #000000 |
| `brand-secondary` | Dark gray #474648 |
| `brand-secondary-light` | Light gray #BCBBBA |
| `brand-accent` | Red #DE1D24 (PMS 186), non-text accents only, at most 20% |
| `brand-background` | White #FFFFFF |
| `font-heading` | URW Grotesk Medium (fallback Helvetica or Arial Narrow) |
| `font-body` | URW Grotesk Regular or Light (fallback Helvetica or Arial Narrow) |
| `logo-primary` | `uno-logo-color.png`; Lock-up `uno-lock-up-color-black.png` |
| `logo-reversed` | `uno-logo-white.png`; Lock-up `uno-lock-up-white.png` |

Download logos from the official Logos page (FILES) rather than copying them
from elsewhere. Use PNG for screens and EPS for print. Don't alter, recolor,
redraw, distort, or add anything to a logo.

For PowerPoint, Helvetica is the better fallback for body text: Arial Narrow is
condensed and harder to read from the back of a room at 24 pt.

## 3. Accessibility requirements

- **Contrast:** at least 4.5:1 for all text. Every pair in use passes (row 17).
- **Text size:** 24 pt minimum for slide body text; titles larger.
- **Alt text on every image.** Logos: `University of Nebraska Omaha`. The
  feedback QR code (slide 89) has its own alt text.
- **Never rely on color alone.** Traffic-light colors always come with their
  words.
- **Reading order:** title, then body, then logo.

## 4. Layouts

| Layout | Slides | Spec |
| --- | --- | --- |
| Title | 1 | Black background; white URW Grotesk; all-white Lock-up, at least 1.75 in, clear space = height of the "O" in "Omaha" |
| Section divider | 8, 21, 37, 51, 64, 77 | Black background; white URW Grotesk Medium; all-white University Logo, at least 1 in; optional red accent rule |
| YOUR TURN | 17, 18, 32, 33, 46, 47, 59, 60, 61, 72, 73, 83, 84 | White background; dark gray banner with white text (9.39:1); timer is the largest text; black body text, 24 pt minimum; thin red accent bar |
| Standard content | All others | White background; black URW Grotesk |
| Syllabus (print) | — | Two-color Lock-up in the header; black headings in URW Grotesk Medium; body in URW Grotesk Regular, 11 pt minimum; red only as a thin rule |

Logo position on every layout stays open (item 10).
