# ShopEase 🛍️

An e-commerce landing page showcasing products across five categories, plus account registration and login pages.

## Features

- **Hero section** with a search bar (UI only — not yet wired to any search logic)
- **Five shopping categories** in an interactive fanned-card layout: Fashion, Electronics, Home & Living, Gaming, Books & Stationery
- **Per-category product grids**, responsive from 5 columns down to 1 depending on screen width
- **Featured Products** section highlighting one item from each category
- **Register** and **Login** pages with client-side form validation (required fields, password-match check)
- Fully responsive layout with breakpoints at 1100px, 1000px, and 700px

## Tech stack

Plain HTML, CSS, and vanilla JavaScript (form validation only) — no frameworks, build step, or dependencies.

## File structure

```
├── index.html      Homepage: hero, category cards, product sections
├── login.html      Login form
├── register.html   Registration form
├── style2.css      Styles for index.html
├── style.css       Styles for login.html and register.html
├── script.js       Login/registration form validation
└── images/         Referenced by index.html but not included in this upload — see below
```

## Setup

This is a static site — no installation required.

1. Clone the repo
2. Add an `images/` folder with the product photos `index.html` expects (e.g. `images/fashion/tshirt.jpg`, `images/product1.jpg`)
3. Open `index.html` directly in a browser, or serve the folder with any static server

## Known issues / to-do

- `index.html` references image paths (e.g. `images/fashion/tshirt.jpg`, `images/product1.jpg`, `images/product2.jpg`, etc.) that aren't part of this upload — the page will show broken images until that folder is added
- The hero search bar on `index.html` is still just markup — it isn't wired up to filter or search the product grids
- No backend: form submissions just show an `alert()` on success — nothing is actually saved or authenticated

## License

No license specified yet — add one (e.g. MIT) if you plan to share this publicly.
