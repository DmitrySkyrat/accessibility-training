
# training.epam.com
1. Lighthouse accessibility report has 71 points.
Issues were found:
- Buttons do not have an accessible name - `Lighthouse issue1.png`
- Image elements do not have [alt] attributes - `Lighthouse issue2.png`
- Links do not have a discernible name - `Lighthouse issue3.png`
- [user-scalable="no"] is used in the <meta name="viewport"> element or the [maximum-scale] attribute is less than 5 - `Lighthouse issue4.png`
- Background and foreground colors do not have a sufficient contrast ratio - `Lighthouse issue5.png`
Full report can be viewed by `Lighthouse accessibility report.html`

2. Siteimprove plugin
Issues can be found - `Siteimprove1.png`, `Siteimprove1.png`

3. WAVE plugin
During audit there are:
14 errors
- 4 X Missing alternative text
- 2 X Empty heading
- 8 X Empty button
33 contact errors
- 33 X Very low contrast
Summary - `wave audit`

4. NVDA
Issues found by nvda:
- "Sign in" button is not highlighted by TAB - `nvda-no-tab-highlighting.png`
- Incorrect using of `<h1>, <h2>`. "Choose a training program for your skill level" shoud be `<h2>`  - `nvda-incorrect-headings.png`
- Some form fields and buttons are unlabeled - `nvda-form-fields.png`, `nvda-buttons.png`
- Page doesn't have good semantisc (header, footer, nav, section, aside, article).