# Go Green — Corporate Business Website

A responsive multi-page corporate/business website template built with plain HTML5, CSS3, jQuery and Bootstrap 4. Includes a landing page with hero carousel, about, services, pricing, portfolio (filterable), a contact form and a footer with a live-updating year.

Project #01 of my [50 Front-end Projects](https://github.com/hcald91?tab=repositories) series — a run through practical, copy-worthy patterns for corporate/marketing sites.

## Live preview

Clone and open `index.html` in a browser, or serve locally:

```bash
npx serve .
```

## Pages

| File | What it shows |
| --- | --- |
| `index.html` | Landing: hero carousel, about, services, pricing, skills, portfolio, contact |
| `about.html` | Company story / team layout |
| `service.html` | Detailed services grid |
| `portfolio.html` | Filterable portfolio grid with lightbox |
| `price.html` | Pricing table |
| `contact.html` | Contact form + embedded map |

## Tech stack

- HTML5 + CSS3
- Bootstrap 4
- jQuery 3
- Vendor libraries: Superfish (menus), Owl Carousel, Isotope (portfolio filter), Lightbox, Waypoints, CounterUp, Ionicons

## What I changed in this fork

- Added proper `<title>`, `<meta description>`, keywords and Open Graph tags
- Replaced all bundled images with royalty-free stock served from [Picsum Photos](https://picsum.photos/) using stable seeds
- Fixed empty `href=""` attributes across all pages
- Added a small enhancement in `js/main.js`: the footer copyright year updates automatically each year
- Added this README and a `.gitignore`

## Credits

- Original template scaffold: [Sudeep Acharjee](https://sudeep-portfolio.netlify.app)
- Stock imagery: [Picsum Photos](https://picsum.photos/) (Unsplash-sourced, free for any use)

## License

MIT — see `LICENSE` if present, otherwise consider it MIT.
