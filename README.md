# Food Spot — Burger Website

A responsive, single-page restaurant landing page built with plain HTML and CSS. Designed and coded by Darian.

## Live Preview

Open `burger.html` directly in any modern browser — no build step or server required.

## Project Structure
Burger-Website/
├── burger.html # Main page markup
└── burger.css # All styles

## Sections
| Section | Description |
|---|---|
| Header | Sticky navigation bar with logo and nav links |
| Banner | Full-viewport hero with background image and CTA button |
| About | Two-column layout with text and food image |
| Menu | Card grid — Burgers, Pizzas, Fries, Sandwiches, Tacos, Drinks |
| Experts | Card grid showcasing kitchen staff |
| Testimonials | Customer quote cards over a background image |
| Contact | Contact form with name, email, and message fields |
| Footer | Social links (LinkedIn, GitHub, CodePen) |
## Tech Stack
- **HTML5** — semantic sectioning, accessible `alt` attributes
- **CSS3** — Flexbox layout, sticky header, background overlays, smooth scroll
- **Google Fonts** — Lato typeface
- **Font Awesome** — social media icons (via CDN kit)
## Getting Started
```bash
git clone https://github.com/prellwitzdarian/burger-website.git
cd burger-website
open burger.html   # macOS
# or: xdg-open burger.html  (Linux)
# or: start burger.html     (Windows)
No dependencies to install.

Customization
Brand colors — primary accent is crimson / red; update in burger.css
Hero image — replace the background URL in the .banner rule in burger.css
Menu items — add or remove .box blocks inside .menucontent in burger.html
Placeholder text — replace the Lorem Ipsum copy in burger.html with real content
