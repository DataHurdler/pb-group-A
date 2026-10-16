# UNO Brand Specification for the Workshop

Status: **blocked on the brand source.** The request said to follow the
University of Nebraska Omaha brand guidelines and assets in a repository, but
gave the link as `[GitHub repo URL]`. No brand repository was available, so
**every brand value below is marked NEEDS CONFIRMATION** rather than guessed.

When the brand repository is available, fill each `NEEDS CONFIRMATION` cell
from it, put logo files in `logos/`, and note the source file beside each
value. The layouts in section 3 don't need to change: they refer to these
values by name.

## 1. Brand values

### Colors

| Name used in layouts | Use | Value | Source |
| --- | --- | --- | --- |
| `brand-primary` | Title and divider backgrounds, headings | NEEDS CONFIRMATION | |
| `brand-secondary` | Accent bars, YOUR TURN banner | NEEDS CONFIRMATION | |
| `brand-text-on-primary` | Text on `brand-primary` backgrounds | NEEDS CONFIRMATION | |
| `brand-text` | Body text on light backgrounds | NEEDS CONFIRMATION | |
| `brand-background` | Standard slide and page background | NEEDS CONFIRMATION | |

### Fonts

| Name used in layouts | Use | Value | Fallback | Source |
| --- | --- | --- | --- | --- |
| `font-heading` | Slide titles, syllabus headings | NEEDS CONFIRMATION | NEEDS CONFIRMATION | |
| `font-body` | Slide text, syllabus body | NEEDS CONFIRMATION | NEEDS CONFIRMATION | |

### Logos

| Name used in layouts | Version | File | Source |
| --- | --- | --- | --- |
| `logo-primary` | Full color, for light backgrounds | NEEDS CONFIRMATION (`logos/`) | |
| `logo-reversed` | For dark or `brand-primary` backgrounds | NEEDS CONFIRMATION (`logos/`) | |

### Rules

| Rule | Value | Source |
| --- | --- | --- |
| Logo placement on title slides | NEEDS CONFIRMATION | |
| Logo placement on section dividers and content slides | NEEDS CONFIRMATION | |
| Logo placement on print documents (syllabus) | NEEDS CONFIRMATION | |
| Clear space around the logo | NEEDS CONFIRMATION | |
| Minimum logo size | NEEDS CONFIRMATION | |
| Official slide template (PowerPoint, Google Slides, or other) | NEEDS CONFIRMATION | |
| Official document or letterhead template | NEEDS CONFIRMATION | |
| Required wordmark, department lockup, or co-branding | NEEDS CONFIRMATION | |

If the brand repository includes an official slide template, its layouts
replace the descriptions in section 3. Keep the accessibility rules in section
2 either way.

## 2. Accessibility requirements

These come from the request and from WCAG 2.1, not from the brand, so they
apply now.

- **Contrast:** at least 4.5:1 between text and background, for every color
  pair, including text on `brand-primary` and on the YOUR TURN banner. Check
  each pair once brand colors are confirmed; if an official pair fails, use a
  passing pair from the brand palette and record the change.
- **Text size:** 24 pt minimum for all slide body text; titles larger. The
  25-word slide limit leaves room for this.
- **Alt text on every image.** Logos: `University of Nebraska Omaha`. Other
  images get alt text written beside them in the slide file. Purely decorative
  shapes are marked decorative so screen readers skip them.
- **Never rely on color alone.** The traffic-light colors (slides 67, 72 and
  the handout) always appear with their words: go ahead, check first, don't.
- **Reading order:** title first, then body, then logo, in each slide's
  accessibility order.

## 3. Layouts

Four branded layouts. Every slide file names its layout on the slides that use
one; all other slides use the brand's standard content layout (NEEDS
CONFIRMATION) with the accessibility rules above.

### 3.1 Title (slide 1)

- Background: `brand-primary`; text: `brand-text-on-primary`
- Course title in `font-heading`; subtitle and date line in `font-body`, 24 pt minimum
- `logo-reversed`, placed and spaced per the brand's title-slide rule
- Alt text on the logo: `University of Nebraska Omaha`

### 3.2 Section divider (slides 8, 21, 37, 51, 64, 77)

- Background: `brand-primary`; text: `brand-text-on-primary`
- "Module N" small above the module name, both in `font-heading`
- `logo-reversed`, placed per the brand's divider rule; alt text as above
- No body text beyond the module name

### 3.3 YOUR TURN (exercise slides 17, 18, 32, 33, 46, 47, 59, 60, 61, 72, 73, 81, 82)

- Standard background (`brand-background`) with a full-width banner in
  `brand-secondary` across the top
- Banner text: the slide's first line (`YOUR TURN · ⏱ N MIN · Format`, or the
  bake-off equivalent), in `font-heading`, text color chosen to pass 4.5:1 on
  `brand-secondary`
- The timer duration is the largest text on the slide after the banner, so it
  can be read from the back of the room
- Instruction line below in `font-body`, 24 pt minimum
- `logo-primary` per the brand's content-slide rule, if the brand calls for a
  logo on content slides; alt text as above

### 3.4 Syllabus (print, two pages)

- Header on page 1: `logo-primary` per the brand's print rule, course title in
  `font-heading`, color `brand-primary`
- Section headings in `font-heading`, `brand-primary`; body in `font-body`,
  11 pt minimum for print (NEEDS CONFIRMATION if the brand sets a print size)
- Footer on both pages: course title and page number
- Alt text on the logo in the digital (PDF) version: `University of Nebraska Omaha`
