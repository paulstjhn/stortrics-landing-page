# Landing page design review

## Final local implementation: 2026-10-15

Status: implementation rounded up on `codex/landing-page-approved-mockup-implementation`. The owner asked to omit the proposed receipt example and additional business-fit/device refinement. No publication or deployment was performed.

### Final page

- Premium hero with the familiar exercise-books-and-guesswork message, one primary demo action and a real mixed product/service checkout in a laptop frame.
- Original Problem section retained, followed by a separate light/dark Difference comparison.
- Accepted Track, Profit, Offline and Control showcase retained with real demo screens.
- Existing concise business fit, getting-started and accessible FAQ sections retained.
- Final pale-mint demo panel and clean white footer replace the old dark closing treatment. The floating WhatsApp shortcut is hidden because the header, setup and closing sections already provide demo actions.
- Removed three unused generated preview images from discarded iterations. The pre-existing `.DS_Store` modification remains unrelated and excluded.

### Final verification

- Full page checked at 320, 390, 768, 1024 and 1440 pixels with no horizontal overflow. All images loaded and the responsive hero, Difference, showcase, setup and closing layouts switched at the intended breakpoints.
- All five FAQ answers open one at a time, fit without clipping and close by keyboard. Browser console has no warnings or errors.
- Mobile navigation reaches The Difference and closes after selection. Unique IDs and internal anchors resolve; inline JavaScript syntax and Git whitespace checks pass.
- Final review images are stored under `stortrics-landing-review/final-roundup/` in the Codex visualization workspace.

## Approved-mockup implementation checkpoint one: 2026-10-15

Status: implemented locally on `codex/landing-page-approved-mockup-implementation` and awaiting owner review. This checkpoint changes the hero and The Difference only. The existing Problem section is retained. The accepted four-card showcase and all later sections remain in place. Nothing has been committed, pushed or published.

### Implementation

- Hero restores the familiar exercise-books-and-guesswork headline, adds the plain product category label and supporting copy from the approved mockup, and keeps one black WhatsApp demo pill plus the See how it works link.
- The current mixed product/service checkout is presented inside a code-native laptop frame. Its real demo values and UI are unchanged and the caption identifies it as demo data.
- Navigation now includes The difference and retains Product, Getting started, FAQ and the demo action.
- The Problem section retains its existing two-column structure, questions, familiar business examples and wording.
- The Difference is a separate light-versus-dark comparison with four concrete current-setup and Stortrics pairs. It avoids absolute accuracy and recovery claims.
- Removed the experimental three-card benefit strip from the flow. The accepted Track, Profit, Offline and Control showcase remains unchanged.

### Verification

- Layout checked at 320, 390, 768, 1024 and 1440 pixels. The hero, comparison cards and document have no horizontal overflow; the CTA stays 56px high and the mixed-sale image loads at every width.
- Desktop hero typography was tightened to match the approved mockup's three-line composition, with the product display remaining prominent.
- The Difference renders one column on phones and two columns on desktop/tablet. Its surfaces compute to off-white `#FBFBF9` and ink `#1D211E`, with white text on the dark card.
- Mobile navigation opens, reaches The difference, closes after selection and leaves the heading below the fixed header. The floating contact shortcut remains hidden while the guided sections are being read.
- Unique IDs, internal anchors, two comparison cards and the preserved four-card showcase were checked. Browser console and Git whitespace checks are clean.
- Desktop and mobile review images are saved under `stortrics-landing-review/approved-implementation-checkpoint-1/` in the Codex visualization workspace.

### Next action

Owner reviews the hero and The Difference at `http://127.0.0.1:4175/`. Apply feedback before implementing the practical sale example and remaining approved-mockup sections.

## Current reference revision: 2026-10-11

Status: owner-requested revisions to the problem/difference messaging and product showcase completed locally, awaiting visual review. Branch remains `codex/landing-page-first-two-sections`. Final demo CTA and footer are still outside this checkpoint. No commit, push or publication.

### Requested revisions

- Restored The Problem and The Difference as one focused section below the existing benefits. Four paired questions connect stock records, profit, poor network and staff accountability with Stortrics' capabilities. Retained the relatable original heading and the `problems`/`compare` anchors.
- Replaced the three-screen walkthrough with Track, Profit, Offline and Control in four equal cards. The supplied currency-page screenshot guided the centered heading, spacious white canvas, alternating near-white/black surfaces, 2:1 card proportions, rounded corners, faint tonal accents, soft shadows and partially cropped phone frames.
- Device frames are code-native and contain actual Stortrics screenshots. The layout uses a 2x2 grid above 700px and a single column below that breakpoint, keeping descriptions readable and separated from devices.
- Stock and profit wording refers to recorded transactions and costs. Descriptions retain the intended benefits without claiming guaranteed physical stock accuracy or profit beyond recorded inputs. New copy has no em/en dashes.

### Asset provenance

- `feature-track-demo.png`: existing light-theme Product List fixture, including stock quantities.
- `feature-profit-demo.png`: existing analytics overview fixture, including its sample unsynced-transaction state.
- `feature-offline-demo.png`: existing mobile POS fixture illustrating the checkout used for offline sales. This asset is a UI example, not a new live offline smoke-test result.
- `feature-control-demo.png`: newly rendered existing ManageTeamMembersScreen with mocked auth/team states and three synthetic accounts at reserved example.invalid addresses. Uses the current app theme and temporary preview font loading, as in earlier UI fixtures. Temporary `fvm flutter test --no-pub` fixture passed; main app source/data were not changed. Original screenshots remain untouched.

### Verification and preservation

- Header, hero and benefit-strip markup preserved byte for byte. All markup after the showcase, including business fit, onboarding, FAQ and closing content, preserved. Only the existing contact-visibility selector was extended to the two revised sections to avoid covering descriptions/device links.
- Existing CSS preserved apart from the shared palette/container selector extension. All new visual rules are scoped. No new dependencies or application logic.
- Responsive checks at 320, 390, 700, 701, 768, 1024 and 1440px passed: equal 2:1 cards, correct grid transition, loaded images, no page/section overflow, no clipped descriptions or overlap with the device frames. Desktop cards measured 576x288px each.
- Fixed a keyboard-focus alignment issue by using non-scrolling card clipping. All four card scroll positions remained zero after keyboard navigation; white focus outlines are visible on black cards, and ink outlines on light cards.
- Device links use only the visible phone region as their interactive area. Clicking Control opened the full 780x1688 screenshot in a new tab; native image delivery was verified and the temporary image tab was closed.
- Unique IDs, internal anchors, image-file references, plain copy and Git whitespace checks passed. Browser console had no warnings/errors observed.
- Desktop, tablet and mobile captures of each section and the combined flow were rendered and reviewed against the reference. Evidence and metrics are under `stortrics-landing-review/reference-revision/` in the Codex visualization workspace.

### Next action

Owner review at `http://127.0.0.1:4175/#features`; the merged context section is immediately above and reachable at `#problems`. Apply feedback before proceeding to the final demo CTA/footer. The pre-existing .DS_Store modification and unrelated main-app edits remain outside this work.

## Third checkpoint: 2026-10-10

Status: getting started with pricing guidance, followed by FAQs, completed locally and awaiting the owner's review. Stop before the final demo CTA and footer. Branch remains `codex/landing-page-first-two-sections`; nothing has been committed or published during these landing-page checkpoints.

### Scope and copy

- A soft peach getting-started panel with three steps: Book your demo, Talk through your setup, Set up your shop. Quote guidance and a black pill-shaped WhatsApp demo link follow the steps.
- Five concise FAQ topics: offline selling, the distinction from a bank POS terminal, supported devices/printers, adding existing stock records and pricing.
- Replaced the old comparison/onboarding/customer-story/FAQ range with these two sections, following the agreed shorter page structure. No unverified customer story, guaranteed recovery claim, fixed demo/setup duration, universal printer support or unsupported spreadsheet-import promise was introduced.
- Plain-English copy without em/en dashes. Price guidance requests a quote rather than inventing a tariff or free-trial offer.
- Reused the existing palette, container and pill-CTA rules through scoped selector extensions. No new dependencies or image assets.

### Functionality and verification

- Preserved the first four sections byte for byte and preserved the closing CTA/footer/contact markup. Existing scripts differ only for FAQ answer visibility and the new-section contact-shortcut overlap guard.
- FAQ still opens one answer at a time. Each button has an answer ID in `aria-controls`, an accurate `aria-expanded` state and a controlled panel with the native `hidden` attribute when closed. Removed the old fixed-height clipping for the new answers.
- All five answers opened correctly at 320 pixels, with exactly one expanded button and visible answer, and no clipped text. Space and Enter close the selected answer; keyboard focus stays on its button with a visible 2px outline. Closed answers are absent from the accessible snapshot.
- Layout checks at 320, 390, 768, 769, 1024 and 1440 pixels passed. No section or document overflow, 56px demo CTA, 64px minimum FAQ target and correct one/three-column step layouts. The 768/769 pair checks the responsive transition.
- Internal anchors and answer-control references resolve without duplicate IDs. The new demo link matches the existing business WhatsApp demo destination. No message was sent.
- Mobile header navigation to FAQ passed. The floating contact shortcut is hidden while either new section is on screen, preventing overlap with copy and FAQ controls; header, setup and closing demo links remain available.
- Browser console had no warnings/errors. Inline JavaScript syntax and Git whitespace checks passed. Shared CSS rules were compared with the checkpoint-two baseline after removing only the new selector extensions.
- Final desktop, tablet and mobile screenshots were rendered and reviewed, including a mobile expanded-answer example. Evidence is saved under `stortrics-landing-review/third-pair/` in the Codex visualization workspace.

### Next action

Have the owner review `http://127.0.0.1:4175/#how-it-works` and the FAQs below it. Apply requested corrections if needed. Continue to the final demo CTA and footer only after the owner authorizes the next checkpoint.

The old final CTA/footer styling and copy remain for that checkpoint. The pre-existing `.DS_Store` modification is unrelated and remains untouched by this work.

## Second checkpoint: 2026-10-10

Status: the owner authorized continuation to checkpoint three after reviewing the product walkthrough and business-fit sections. Work stays on `codex/landing-page-first-two-sections`; nothing is published.

### Scope and copy

- Replaced the repeated problem/outcome/feature/gallery/business blocks with two sections immediately after the existing benefits, following the agreed shorter page structure.
- Product walkthrough: checkout, stock updates and sales reports, with peach, mint and lavender descriptions. Real app screenshots are explicitly labelled as demo data. Native image links open the larger screens in a new tab.
- Business fit: Pharmacies, Supermarkets, Gadget shops and Salons, followed by the existing supported-device messaging for Windows desktops/laptops and Android phones/tablets. No appointment-scheduling claims.
- Desktop and wider-tablet previews use three columns. Narrower layouts use compact thumbnail/text rows. Business examples change from four columns to two.
- New copy is plain English, without em/en dashes, invented testimonials, numeric business outcomes or absolute sync/accuracy promises.

### Preservation and verification

- Header, hero and benefits markup compared with checkpoint one: identical. All markup and JavaScript from the comparison section onward: identical.
- Checkpoint-one CSS remains an unchanged prefix. New section styling is scoped; no new JavaScript or dependencies were introduced.
- Layout checks at 320, 390, 600, 601, 768, 1024 and 1440 pixels: no overflow in either section or the document, loaded screenshots and correct responsive grids. The 600/601 pair verifies the tablet transition.
- Mobile menu navigation to the new Product section and keyboard focus on screenshot links passed. Clicking the checkout preview opened its native full-resolution 1280x1000 image in a new tab.
- All internal anchor links resolve and IDs are unique. Text contrast passed on white, off-white and all three pastel surfaces; muted body copy measures at least 5.68:1.
- Browser console: no warnings or errors observed. Git whitespace check passed.
- Final desktop, tablet and mobile screenshots were rendered and reviewed. Evidence is saved in `stortrics-landing-review/next-two/` under the Codex visualization workspace.

### Asset provenance

All three new images are copies of existing rendered Flutter test fixtures, with their originals unchanged:

- `images/checkout-current-demo.png`: POS desktop-header fixture, mixed product/service order.
- `images/stock-current-demo.png`: stock-adjustment UI fixture.
- `images/reports-current-demo.png`: analytics overview UI fixture, including its sample unsynced-transaction state. These are product examples, not customer results.

The remaining comparison, getting-started, story, FAQ and final CTA sections still have their old content and styles. They will be reviewed in later checkpoints; this record does not certify their marketing claims. The pre-existing `.DS_Store` modification remains unrelated.

### Next action

Have the owner review sections three and four at `http://127.0.0.1:4175/#features`. Apply requested corrections if needed. Continue to the remaining page sections only after the owner has verified this checkpoint.

## First checkpoint: 2026-10-10

Branch: `codex/landing-page-first-two-sections`, created from local `main` at `f955d9d`.

Status: first two sections were reviewed and the owner authorized the next two sections. Their markup and styles have been preserved during checkpoint two. Nothing has been published.

### Scope

- Header and hero: white surfaces, Inter typography, a black pill-shaped WhatsApp demo CTA, a simple product link, clear product messaging and a current checkout preview.
- Core benefits: three muted lavender, mint and peach cards covering offline sales, stock movement and staff permissions. These replace the previous statistics strip while retaining its `stats` anchor.
- Copy: plain English, no em dashes, no invented customer results or guaranteed sales outcomes. Profit wording refers to recorded costs.
- Header interactions: mobile menu state exposed through ARIA, Escape to close, visible keyboard focus, and anchor spacing beneath the fixed header. The existing floating WhatsApp shortcut is hidden during the intro and remains available further down the page.

The later section markup is unchanged. Existing styles were retained; the new styles are scoped to the header and two review sections, apart from fixed-header anchor spacing, reduced-motion scrolling and the intro contact-shortcut visibility rule.

### Product preview

`images/pos-current-demo.png` is an existing rendered Flutter UI fixture from the current Stortrics POS/sidebar verification work. It shows sample services, not a customer's records. The caption explicitly labels the data as demo data. The original screenshot remains untouched.

### Verification

- Browser layout checks at 320, 390, 768, 1024 and 1440 pixels: no overflow within the changed sections, correct grid stacking, loaded preview image and pill-shaped CTA.
- Mobile menu open/close, Escape, Tab focus, navigation link closure and contact-shortcut visibility: passed.
- Browser console: no warnings or errors observed.
- Inline JavaScript syntax check and Git whitespace check: passed.
- Later section markup compared with the captured baseline: identical. Original CSS remains an unchanged prefix.
- Changed visible copy: checked for em/en dashes and removed unsupported numeric statistics.

Existing overflow in the untouched mobile gallery/feature sections remains outside this checkpoint. The existing `.DS_Store` modification was present before work and is unrelated.

Review screenshots and responsive metrics are saved separately under the Codex visualization workspace in `stortrics-landing-review/`. Local preview: `http://127.0.0.1:4175/` while the preview server is running.
