---
name: Enrique Valle Construction
description: A job-site layout in slate and yellow chalk; taut, pluckable chalk lines frame a phone-first one-pager that sells the guarantee and 45 years.
colors:
  slate-ground: "#172433"
  slate-raised: "#1d2e41"
  slate-deep: "#132030"
  yellow-chalk: "#f5c518"
  seam-chalk: "#d6a800"
  chalk-white: "#eef2f6"
  dust-grey: "#aebdcd"
  slab: "#ece7dc"
  slab-muted: "#46566b"
  blue-chalk: "#2c64a8"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(40px, 12.4vw, 104px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(34px, 9vw, 76px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  quote:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(26px, 6.6vw, 52px)"
    fontWeight: 800
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "normal"
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0.02em"
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 900
    lineHeight: 1.15
    letterSpacing: "0.02em"
  numeral:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "44px"
    fontWeight: 900
    lineHeight: 1
rounded:
  r: "14px"
  focus: "6px"
spacing:
  pad-phone: "20px"
  pad-desk: "40px"
  gap: "12px"
  stack: "22px"
  section-phone: "40px 0 72px"
  section-desk: "56px 0 104px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.yellow-chalk}"
    textColor: "{colors.slate-ground}"
    typography: "{typography.button}"
    rounded: "{rounded.r}"
    padding: "10px 22px"
    height: "64px"
  button-primary-desk:
    padding: "10px 30px"
  button-primary-narrow:
    padding: "10px 14px"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.chalk-white}"
    typography: "{typography.button}"
    rounded: "{rounded.r}"
    padding: "10px 22px"
    height: "64px"
  dock-button:
    backgroundColor: "{colors.yellow-chalk}"
    textColor: "{colors.slate-ground}"
    rounded: "{rounded.r}"
    height: "56px"
  tick-list-item:
    textColor: "{colors.slate-ground}"
    typography: "{typography.label}"
    height: "46px"
  bay:
    textColor: "{colors.slate-muted}"
    padding: "24px 0 26px"
  step:
    textColor: "{colors.dust-grey}"
    padding: "22px 0"
---

# Design System: Enrique Valle Construction

## Overview

**Creative North Star: "The Snapped Layout"**

The page is a job site being laid out, not a contractor template. A slate-navy ground stands in for the slab before the pour; yellow chalk lines are snapped across it to frame the work. The lines are real objects: taut 2px strings with a soft cast shadow that sway constantly, catch on a finger or cursor, stretch, slip and twang, leaving a powder print and a puff of dust where they snapped. Everything else is heavy uppercase type and layout marks (dimension lines with slash ticks, tick lists, rules between bays) in the same two chalks.

Density is low and the voice is loud: one idea per section, huge display type, one action (call). The palette is the owner's flyer (black, safety yellow, white) translated onto a ground that is never black. A single pale slab section with blue chalk breaks the navy once, the way a sheet of plywood breaks a slab.

Confirmed rejections from the direction contract: no stock-photo hero, no icon-card grid, no fake reviews.

**Key Characteristics:**
- Slate-navy ground, never black; yellow chalk is the one trade color.
- Taut chalk lines (canvas and SVG) as the only decoration and every section boundary.
- Heavy uppercase system type, tight negative tracking at display sizes.
- Layout marks as components: dimension line, tick list, ruled bays, numbered steps.
- One action everywhere: a 64px yellow call button with the number shown.
- Phone first; desktop is the phone layout given columns.

## Colors

Two chalks on a slate ground, with one pale slab interlude; the yellow does all the talking.

### Primary
- **Yellow Chalk** (yellow-chalk): the flyer's safety yellow. Chalk lines, dust, the primary button fill, emphasis words in headlines (`em`), quote highlight, step numerals, dimension rule, wordmark sub-line, focus ring, selection, scrollbar thumb.
- **Seam Chalk** (seam-chalk): a deeper yellow used only for seam lines that touch the pale slab, where full yellow chalk would vanish against the cream.

### Secondary
- **Blue Chalk** (blue-chalk): chalk on the pale slab only. Emphasis words in slab headlines, the "Also on the list" heading, tick icons, bay rules (at 55% alpha), focus ring inside the slab.

### Neutral
- **Slate Ground** (slate-ground): the layout surface for the bar, hero and since section; also the ink on yellow and on the slab.
- **Slate Raised** (slate-raised): a half-step lighter ground for "How it works", so consecutive navy sections read as separate pours.
- **Slate Deep** (slate-deep): the close and footer, and the dock's translucent backing (at 92%).
- **Chalk White** (chalk-white): primary text and outline-button text on navy.
- **Dust Grey** (dust-grey): secondary text on navy (pitch, notes, step bodies, footer).
- **Slab** (slab): the pale services section.
- **Slab Muted** (slab-muted): secondary text on the slab.

Hairline rules are alpha tints of these colors, never new hues: yellow chalk at 28% (step rules) and 22% (hero list rules), slate ink at 14% (tick-list rules), dust grey at 16% (footer top rule).

### Named Rules
**The Never-Black Rule.** The ground is slate navy in three steps (ground, raised, deep). The flyer's black survives only as the shadow tint `rgba(6,12,20,…)`.

**The Chalk Per Surface Rule.** Yellow chalk marks navy; blue chalk marks the slab. Chalk marks (emphasis words, ticks, rules, focus rings) never use the other surface's chalk. Two things cross: the seam line (seam-chalk) at the boundary, and the yellow call button, which is the same object on every surface.

## Typography

**Display Font:** system UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

**Character:** One family, pushed to weight 900 and uppercase for everything that announces; plain 400 for everything that explains. The system stack is a product constraint (PRODUCT.md: no web fonts, fast in Facebook's in-app browser); weight, case and tracking carry the character instead of a typeface.

### Hierarchy
- **Display** (900, clamp(40px, 12.4vw, 104px), 0.98, uppercase, -0.02em, balanced): the hero headline. The closing name uses the same role at clamp(38px, 11vw, 104px).
- **Headline** (900, clamp(34px, 9vw, 76px), 0.98, uppercase): section headings ("The whole house", "How it works").
- **Quote** (800, clamp(26px, 6.6vw, 52px), 1.08, sentence case): the owner's guarantee quote; the only large type that is not uppercase.
- **Dimension figures** (900, clamp(22px, 5.6vw, 40px), tabular): the 1981 / TODAY ends of the dimension line.
- **Title** (900, 21-22px, 1.1-1.15, uppercase): bay and step headings.
- **Numeral** (900, 44px, 1, yellow chalk): step counters.
- **Body** (400, 17px, 1.55): all running text; measure capped at 34-36em. Pitch scales to clamp(17px, 1.7vw, 20px).
- **Label** (800, 15px, uppercase, 0.02em): tick-list items; 0.06em in the desktop hero list. The list heading "Also on the list" is 900, 15px, 0.16em, blue chalk.
- **Button** (900, 17px, uppercase, 0.02em) with a sub-line (700, 14px, sentence case, 0.04em, tabular, 85% opacity) that carries the phone number or a hint.

### Named Rules
**The Shout-Then-Explain Rule.** Anything uppercase is 800-900; anything 400 is sentence case. No middle weights for headings.

**The Tabular Number Rule.** Every phone number and year is set with tabular figures (`font-variant-numeric: tabular-nums`).

**The Two-Line Lockup Rule.** The wordmark is set in type as the flyer's lockup: ENRIQUE VALLE (900) over CONSTRUCTION (800, widely tracked at 0.31em, yellow chalk). The closing name repeats it at display size with the sub-line at 0.42em and 0.2em tracking. Never redraw it as a logo.

## Layout

Single column on phones, with sections stacked full-bleed and content in a centered container (1180px max) with 20px side padding, rising to 40px at 760px.

- **Section rhythm:** 40px top / 72px bottom on phones; 56px / 104px on desktop. The hero runs 96px / 64px (phone) and pulls up under the bar (margin-top -68px / -84px) so the gable can rise behind the wordmark. The close is taller (120px / 72px, desktop 170px / 110px) to give the gable room.
- **Inner stack:** 22px between hero headline, pitch and actions; 12px between buttons.
- **Breakpoints:** 379px and below compacts buttons (15.5px, zero tracking, 14px side padding) so "Call for a free estimate" never wraps at 360px. 760px is the phone/desktop switch: buttons go side by side at auto width, bays and steps become three columns (36px gutters), the tick list becomes five columns, the since section becomes a 1.2fr / 1fr grid, the dock is removed. 1080px adds the hero's right-hand service list (1.3fr / 0.7fr) and hides the duplicate list in the slab.
- **Footer** reserves `110px + safe-area-inset-bottom` on phones so the dock never covers it.

**The Phone-First Rule.** The first phone viewport must hold the wordmark and number, the gable, the headline, the pitch, and the full-width call button. Desktop adds columns; it never adds content the phone lacks (the 1080px hero list is the slab list relocated, not new).

**The Thumb Rule.** Every tap target is at least 44px tall: buttons 64px (dock 56px), bar links 44px, tick rows 46px, inline links padded by 11px vertically with matching negative margin.

## Elevation & Depth

Flat surfaces, lifted lines. Depth comes from the chalk strings casting soft shadows onto the ground and from tonal steps between the three slate grounds, not from cards or panels.

### Shadow Vocabulary
- **String cast shadow** (canvas: `rgba(5,10,18,.32)`, 3.2px, blur 1.6px, offset grows with displacement; SVG seam: `rgba(6,12,20,.28)`, 3px, blur 1.5px, offset 1.5px x / 3px+ y): under every chalk line. The offset grows as the line is pulled, so a plucked line visibly lifts.
- **Button lift on the slab** (`0 10px 22px -12px rgba(23,36,51,.45), 0 3px 8px rgba(23,36,51,.18)`): the primary button on the pale slab.
- **Dock shadow** (`0 -8px 24px rgba(6,12,20,.35)` with 10px backdrop blur): the sticky call bar, cast upward.

**The Lifted-Line Rule.** Only things that are physically raised cast shadows: the strings and the floating dock. Text, sections and lists never do.

## Shapes

One radius: gently rounded buttons (14px). Everything else is square: sections, bays, list rows and rules have no radius and no enclosing box. The focus ring rounds at 6px. Lines are drawn with round caps and joins. The recurring geometry is the gable (two chalk lines meeting at a peak) and the long, slightly tilted ground line; seams rise left to right (62% to 38% of their height).

## Components

### Buttons
Big, blunt and always a phone call.
- **Shape:** gently rounded (14px), 2px yellow chalk outline on both variants, 64px minimum height.
- **Primary:** yellow chalk fill, slate ink; leading phone icon (22px); label plus a sub-line with the number.
- **Outline:** transparent fill, chalk-white text, trailing down-arrow; used once, for "What I do".
- **Hover (hover-capable devices only):** rises 2px; primary deepens its shadow, outline gains an 8% yellow wash. Transition 0.25s `cubic-bezier(.16,1,.3,1)`.
- **Active:** presses 2px down and scales to 0.99.
- **Focus:** 3px yellow chalk outline, 3px offset (blue chalk inside the slab).

### Call Dock
A fixed bottom bar on phones (hidden at 760px+) holding one 56px primary button. It slides up (0.4s, same ease) once the hero buttons leave the viewport and slides away when the closing call button is visible, so two call buttons never share the screen. It is `aria-hidden` and untabbable while off-screen. Backing is slate deep at 92% with 10px blur; padding respects the bottom safe area.

### Top Bar
Wordmark lockup left, phone number right (icon in yellow chalk, 800 weight, tabular). Not sticky; sits over the hero's canvas.

### Dimension Line
A surveyor's dimension: a figure, a yellow chalk rule with two 45-degree slash ticks near its ends, and a figure. The label ("45+ years", 14px, yellow chalk) sits on the rule's midpoint with a ground-colored knockout. Exposed to assistive tech as one image with a full-sentence label. Currently static CSS.

### Tick List
Uppercase labels (800, 15px) beside a 16px stroked tick icon in the surface's chalk, each row 46px with a 1px hairline beneath. Two columns on phones, five at 760px. On navy (desktop hero list) the ticks and hairlines are yellow chalk and tracking widens to 0.06em.

### Bays
Open service blocks on the slab: a 2px blue chalk rule (55% alpha) on top, an uppercase title, a muted body with the key nouns bolded in slab ink. No box, no background, no icon. Stacked on phones, three columns at 760px.

### Steps
A numbered list: a 52px column holding a yellow chalk numeral (44px, 900) spanning both rows, title and body to its right, each step ruled above by a 28% yellow hairline. Stacked on phones, three columns at 760px.

### Chalk Lines (signature)
The motion system. One shared physics model, one `requestAnimationFrame` loop for every surface.

- **String model:** 44 nodes per string; a 1-D wave equation with stiffness 0.42, damping 0.9955 per substep, 4 substeps per frame; ends are fixed. Frame delta capped at 50ms.
- **Ambient sway:** every string sways at all times with a sine envelope (still at the ends) built from three layered sines (k x 1.9, k x 3.7, and a travelling s x 7 - k x 2.6 term), amplitude 3.2px breathing between 75% and 110%, tempo 1.0. Each string gets its own phase so nothing moves in unison.
- **Grab:** a pointer or finger that crosses a line (or moves within 7.5px of it) catches the nearest node; the node then follows the pointer along the line.
- **Snap:** pull beyond 70px (scaled by the sine envelope, never below 25%), slide off the end 2%, or release, and the line lets go and rings out.
- **Pluck:** a tap or click within 30px of a line kicks it 26px away from the tap side.
- **Prints:** each string carries a pre-rendered powder print (scattered yellow specks, 8-30% alpha). It always shows at 42%; every snap brightens it (by 0.4 + force/90) and it fades back over 3.5s.
- **Dust:** ambient motes (70 on phones, 180 on desktop, half that in the close) drift on a slow wandering field and wrap at the edges; within 90px of the pointer (110px for touch) they are pushed aside and spring back. A snap bursts 16 to 40 particles out along the line's normal; they fall gently and fade over 1.6-3.4s. Hard cap 420 particles per surface.
- **Rendering:** canvas at up to 2x device pixel ratio; chalk line 2.1px yellow chalk with round caps.
- **Layouts:** hero = gable (peak centered on phones, at 42% of the headline column on desktop, eaves clear the first line of the headline) plus a ground line 30px under the buttons tilting up 10-14px; close = the same gable over the name. Layouts are recomputed from the live headline and button positions on resize (120ms debounce) and after fonts load.
- **Seams:** section boundaries are 56px SVG strips running the same string physics: one line from 62% to 38% height, the area below the line filled with the next section's color so the boundary itself moves when plucked. Line color is yellow chalk between navy grounds, seam chalk at the slab.
- **Static fallback:** the hero ships an SVG gable at 80% opacity, swapped out once the canvas runs.
- **Reduced motion:** with `prefers-reduced-motion`, every surface draws a single still frame (lines straight, prints and dust in place) and redraws on resize and font load; no loop runs, smooth scrolling is off.
- **Pause off-screen:** an IntersectionObserver (80px margin) marks surfaces visible; only visible ones step, and the loop stops entirely when none are, waking on pointer movement, resize or visibility.

**The Living Line Rule.** Every snapped chalk line (a string spanning a surface or a section boundary) is the same string: it sways, it can be grabbed, and it snaps with dust and a print. Drawn layout marks (dimension rules, hairlines, bay rules, button outlines) are a different material and stay still.

## Do's and Don'ts

### Do:
- **Do** keep the ground slate navy (slate-ground, slate-raised, slate-deep) and step between them to separate sections.
- **Do** mark every section boundary with a chalk seam whose fill follows the line.
- **Do** make every action a `tel:` call on a 64px yellow chalk button with the number in its sub-line.
- **Do** set announcing type at 900 uppercase with -0.02em tracking at display sizes, and running text at 400, 17px, 1.55.
- **Do** use tabular figures for every number and year.
- **Do** build new content from layout marks: dimension lines, tick lists, ruled bays, numbered steps.
- **Do** give new chalk lines the shared physics, a cast shadow, a powder print, the reduced-motion still frame and the off-screen pause.
- **Do** keep every tap target at least 44px tall and keep the phone's first viewport holding the call button.

### Don't:
- **Don't** use black as a ground; it exists only as shadow tint.
- **Don't** use a stock-photo hero, an icon-card grid, or fake reviews.
- **Don't** use yellow chalk marks on the pale slab or blue chalk on navy; only the seam line and the yellow call button cross surfaces.
- **Don't** wrap content in cards, boxes or rounded panels; only buttons are rounded.
- **Don't** add a snapped chalk line (gable, ground line, seam) that does not run the shared string physics.
- **Don't** show two call buttons at once on phones (the dock hides at the hero and the close).
- **Don't** invent a logo or name variant; the wordmark is type only.
