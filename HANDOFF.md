# Enrique Valle Construction — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/enriqueValleConstruction · **Built:** 2026-10-08 from Muse brief (run 2026-10-08, NJ Home Improvement Contractors group post)

## What's built
- **World: snapped chalk line.** Slate-navy layout surface (#172433), yellow chalk (#f5c518, his flyer's yellow), a pale slab section with blue chalk for services.
- **Signature element:** taut yellow chalk lines on canvas. In the hero two lines form a roof gable over the headline (echoing the roof on his flyer) plus a ground line under the buttons; the close repeats the gable. Lines sway all the time (layered sines); drag across one with finger or mouse and it catches, bends with you, slips off and twangs, puffs chalk dust and leaves a fresh powder print that fades. A tap near a line plucks it. Floating chalk dust drifts and gets pushed by the pointer.
- **Dividers** are the same string physics in SVG: pluckable chalk lines whose fill follows the line.
- **Sections:** hero ("Every job guaranteed." + 45 years + Newark), since-1981 dimension line + his guarantee quote, services (his three caption groups verbatim-ish + the flyer's list), how it works (call → I stop by → guaranteed), close with the name, footer with "Demo one-pager — free sample."
- **Contact:** every button is `tel:+19737897425`. Sticky call bar on phones appears once the hero buttons scroll away and hides at the closing button. Desktop buttons show the number.
- Single file, ~36KB, no images, no fonts, no tracking.

## Assumptions I made
- **Colors:** flyer is black + safety yellow + white. Black ground isn't allowed, so slate navy; yellow kept as the chalk/trade color. Blue chalk on the pale section is a real chalk-line color, my choice.
- **Voice:** first person ("What I do", "I stop by"), because his caption is first person ("Give me a call anytime to schedule a time for me to stop by"). Swap to "we" if the business is more than him.
- **Headline** "Every job guaranteed." lifted from his caption, per the brief's "lead with the guarantee + 45 years".
- **"45+ years" / "1981 → TODAY"** from his caption ("over 45 years… since 1981").
- The note "from foundations and concrete to finished kitchens" paraphrases his service list; it's not a quote.
- The quote's attribution reads "Enrique Valle Construction" because the person's name is unconfirmed.
- Flyer spelling "GARANTEED" corrected to "guaranteed".
- No logo exists: wordmark set in type, mirroring the flyer's two-line lockup (name / CONSTRUCTION). Didn't redraw his roof mark as a logo.

## Placeholders and gaps
- **Name mismatch:** flyer says ENRIQUE VALLE CONSTRUCTION, the poster is "Kelvin Valle". Confirm before outreach; the page never names a person.
- **No work photos at all.** The flyer's background art (hard hat, framing) is stock/AI, not his work, so it isn't used. A proof section is the first thing to add once he sends photos.
- No hours, email, service-area towns, reviews, prices, licence/insurance. None are shown.
- Texting unconfirmed: no SMS button.
- **No Facebook link preview image.** `og:image` needs an absolute URL, so it waits until the site is hosted (GitHub Pages isn't turned on). Then render the phone hero at 1200x630 as `og.png` and add `og:image`, `og:image:width/height` and `og:url`. Until then the shared link shows a text-only card.

## Questions for the owner
- Is the business name Enrique Valle Construction? Who's Kelvin, and should the page say "I" or "we"?
- Can you send 6–10 photos of finished jobs (and any before/afters)?
- Do you take texts? (Then we add text-for-an-estimate buttons with the job pre-filled.)
- Which towns do you cover beyond Newark?
- Licensed/insured in NJ (HIC registration number)? Worth showing if so.
- Hours, or "call any time" for real?
- Which jobs do you most want more of?

## Ideas not built (yours to pick)
- **Runner-up world: blueprint & timber framing** — navy blueprint sheet with a live line drawing of a house frame whose studs flex under the finger. Flyer already uses a blueprint backdrop.
- Other candidates: wet concrete you trowel smooth with a finger; sawdust pile with motes in a light beam; spirit-level bubble that tilts with phone motion.
- Photo proof framed as layout: photos pinned at chalk-line intersections, or before/after sliders with a chalk line as the divider (pluckable).
- A plumb-bob line hanging in the hero you can swing.
- Text-to-book module once texting is confirmed.
- Spanish toggle (Newark has a large Spanish-speaking population; his name suggests he may prefer it) — ask first.

## Review round (done once, then stopped)
Fixed from the finish review: reduced-motion users got blank canvases after fonts loaded (now redrawn); an invented "foundations" wording; the "45+ years" label read like an eyebrow (now written on the dimension line); desktop list had a side stripe, shrinking ticks and was hidden from screen readers; a dead band under the desktop hero; the guarantee line repeated word for word in step 3; the Call button wrapped at 360px; the closing gable cut through the name on desktop.
Left for you: the 1981→TODAY dimension rule is static CSS, not a pluckable string; the pale services slab has no chalk marks on it beyond blue text. Both are good candidates to bring alive.

## Not verified
- Real-device touch feel (only simulated touch sweeps headlessly), iOS/Android `tel:` handoff from Facebook's in-app browser, frame rate on old phones, sticky bar behavior with the in-app browser's toolbar.
