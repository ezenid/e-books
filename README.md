# E-Books

An online Ethiopian bookstore.

---

## Project Directory Structure

```text
e-books/
├── index.html
├── README.md
├── about/
│   └── index.html
├── contact/
│   └── index.html
└── order/
    └── index.html

```
### Why this Project structure?

I organized each page into its own folder with an index.html file so the site gets clean URLs (like /order/ instead of /order.html), keeps relative links consistent across every subpage

---

## Layout & W3C Validator Notes

Because using CSS is not allowed, table elements and attributes like (width, cellpadding, cellspacing, valign, align ...etc) were intentionally used to handle multi-column layouts, spacing, and alignment across the screen (such as the featured books grid and footer column s). 

Running the pages through [validator.w3.org](https://validator.w3.org/) will flag warnings about these attributes being obsolete in HTML5 in favor of CSS. Those warnings are expected.
