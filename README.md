# alpridgecoffee

Static site for **Alpine Ridge Coffee Roasters** — an imagined café and roastery
in Antarctica.

> **The café does not exist.** It isn't real — not yet, anyway. There is no shop,
> no roaster and no coffee; the page describes the place as though you could walk
> in, and says plainly that you can't. Nothing is for sale, nothing is being built,
> and no orders, bookings or investment are taken. It is not affiliated with,
> endorsed by, or meant to resemble any real company, café, roastery, research
> station, national programme or person.

There are no contact details on the site, by design — there is nobody to contact.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The whole site — one page |
| `style.css` | Styles (no frameworks, no build step) |
| `assets/*.svg` | Original line art / illustrations drawn for this page |

No dependencies, no JavaScript, no external requests, no analytics. Fonts are
system stacks so the page renders identically offline.

## Running locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

Served by GitHub Pages from the `main` branch root:
<https://simbae1.github.io/alpridgecoffee/>

The page carries `<meta name="robots" content="noindex, nofollow">`. Remove that
line if you want it indexed by search engines.

## License

Code and illustrations: MIT (see `LICENSE`).
