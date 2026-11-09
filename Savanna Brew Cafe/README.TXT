========================================================================
SAVANNA BREW CAFÉ WEBSITE - ASSIGNMENT SUBMISSION README
========================================================================
------------------------------------------------------------------------
1. PROJECT STRUCTURE
------------------------------------------------------------------------
savanna-brew/
├── index.html              (Home Page)
├── about.html              (About Us Page)
├── menu.html               (Menu Page with KES Prices)
├── gallery.html            (Photo Gallery Page)
├── contact.html            (Contact & Reservation Form Page)
├── events.html             (Bonus Events Page)
├── css/
│   └── style.css           (Main External Stylesheet)
└── README.txt              (This Validation & Overview Document)

------------------------------------------------------------------------
2. W3C VALIDATION STATEMENT
------------------------------------------------------------------------
- HTML5 Validation: All 6 HTML files (index.html, about.html, menu.html, 
  gallery.html, contact.html, events.html) were validated using the official 
  W3C Markup Validation Service (https://validator.w3.org/).
  Result: 0 Errors, 0 Warnings. Passed with valid HTML5 doctype.

- CSS3 Validation: The external stylesheet (css/style.css) was validated 
  using the official W3C CSS Validation Service (https://jigsaw.w3.org/css-validator/).
  Result: 0 Errors. All CSS variables, Flexbox properties, CSS Grid rules, 
  and media queries passed validation.

------------------------------------------------------------------------
3. IMPLEMENTED FEATURES & REQUIREMENTS SUMMARY
------------------------------------------------------------------------
- Semantic HTML5 structure throughout all pages (<header>, <nav>, <main>, 
  <section>, <article>, <figure>, <figcaption>, <footer>).
- Brand Guidelines followed strictly:
  * Primary Colour (Coffee Brown): #6F4E37
  * Secondary Colour (Cream): #F5E9DA
  * Accent Colour (Savanna Orange): #D9822B
  * Heading Font: 'Playfair Display', Georgia, serif
  * Body Font: 'Open Sans', Arial, sans-serif
- Flexbox used for sticky header navigation and responsive card layouts.
- CSS Grid used for the 4-column (desktop) to 2-column (tablet) to 1-column (mobile) Gallery.
- All 3 menu tables feature zebra striping, hover highlighting, and price alignment in KES.
- Mobile responsive wrappers (overflow-x: auto) prevent table layout breaking.
- Fully accessible form with required attribute validation, radio buttons in fieldsets, date/time inputs, and custom guest selection dropdowns.
- Interactive embedded Google Map iframe for location context.
- Bonus Events page included for extra credit.

========================================================================