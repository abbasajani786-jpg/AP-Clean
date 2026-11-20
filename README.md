# Nagpur Business Websites

A collection of responsive static websites built for local businesses in Nagpur, Maharashtra, using plain HTML, CSS and JavaScript (no build step).

## Projects

| Project | Description | Status |
| --- | --- | --- |
| [`mafia-fashion/`](mafia-fashion/) | Men's clothing store landing page (Jaripatka) | Complete |
| [`pickle-park/`](pickle-park/) | Pickleball club landing page with slot-booking call-to-action | Complete |
| [`zafran-restaurant/`](zafran-restaurant/) | Mughlai restaurant menu page with category filter | In progress |

## Features

- Responsive layout with a mobile hamburger menu
- Smooth in-page scrolling and scroll-based navbar styling
- Accessible navigation (`aria-expanded`, labelled controls)
- Click-to-call phone links

## Getting started

No installation needed.

```bash
git clone https://github.com/abbasajani786-jpg/AP.git
cd AP
```

Open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Project structure

```
.
├── index.html              # Landing page linking to every project
├── mafia-fashion/
│   ├── index.html
│   ├── css/style.css
│   └── js/main.js
├── pickle-park/
│   ├── index.html
│   ├── css/style.css
│   └── js/main.js
└── zafran-restaurant/
    ├── menu.html
    └── README.md
```

## Deployment

The site works on GitHub Pages: go to **Settings → Pages**, choose the `main` branch and the `/ (root)` folder.

## Tech stack

HTML5, CSS3, vanilla JavaScript, Google Fonts, Font Awesome.

## License

Released under the [MIT License](LICENSE).
