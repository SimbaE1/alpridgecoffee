# alpridgecoffee

Static site for **Alpine Ridge Coffee Roasters** — a concept for a small, simple
café and roastery in Antarctica.

> **The café does not exist.** It has not been built. There is no shop, no roaster
> and no coffee. The site describes what it would be and states plainly what stands
> in the way. Nothing is for sale, no bookings or deposits are taken, and no
> investment is being raised. It is not affiliated with, endorsed by, or meant to
> resemble any real company, café, roastery, research station, national programme
> or person.

Contact: ezra.l.allison+alpridgecoffee@gmail.com

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

The page currently carries `<meta name="robots" content="noindex, nofollow">`.
Remove that line if you want it indexed by search engines.

## License

Code and illustrations: MIT (see `LICENSE`).
