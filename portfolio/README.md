# Your Name - Web Developer Portfolio

Web Technologies, BSCS Semester 5. Pages: `index.html` (inline CSS), `information.html` (embedded CSS), `registration.html` (external `style.css`).

Live site: _add your GitHub Pages URL_ | Browsers tested: Chrome and Firefox

## Short Explanation

CSS (Cascading Style Sheets) controls how HTML looks. It separates content from presentation, so one stylesheet can restyle many pages, keeps design consistent, reduces repeated code and makes sites easier to maintain and make responsive.

In the rule `input:focus { border-color: #f2b84b; }` from `style.css`, `input:focus` is the selector, `border-color` is the property and `#f2b84b` is the value.

Inline CSS uses the `style` attribute on one element (used in `index.html`). It is quick but hard to reuse. Embedded CSS sits in a `<style>` element in the head (used in `information.html`) and styles one page. External CSS lives in a separate `.css` file linked from many pages (used in `registration.html`), which is the easiest to maintain.

CSS1 (1996) introduced basic fonts, colours and margins. CSS2/2.1 (1998/2011) added positioning, media types and tables. Modern CSS is split into modules (Flexbox, Grid, Selectors, Colour) that evolve separately.

Browser support matters because browsers render some features differently, and users must get a working page whatever they use. I tested in Chrome and Firefox. Record any differences you notice here (for example, date picker appearance).

Semantic HTML example: `<article id="featured-project">` describes a self-contained piece of content. Non-semantic example: `<div class="choice">` only groups radio and checkbox controls for styling.

## Testing notes
- Empty required fields, invalid email and a 5-character password were all blocked by the browser.
- Validated with https://validator.w3.org/ (add screenshots in `/screenshots`).
