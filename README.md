# alpridgecoffee

Static demo site for **Alpine Ridge Coffee Roasters** — a *fictional* luxury-minimal
café set in Antarctica.

> ⚠️ **This is a test fixture, not a business.** The brand, menu, prices, hours,
> location and contact details are invented. It is not affiliated with, endorsed by,
> or meant to resemble any real company, café, roastery, research station or person.
> Nothing is for sale and no data is collected.

Built while testing [goodhelp.ai](https://goodhelp.ai) workflows.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The whole site — one page |
| `style.css` | Styles (no frameworks, no build step) |
| `assets/*.svg` | Original line art / illustrations drawn for this page |

No dependencies, no JavaScript, no external requests. Fonts are system stacks so
the page renders identically offline.

## Running locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

Served by GitHub Pages from the `main` branch root.

## License

Code and illustrations: MIT (see `LICENSE`). The fictional brand name is not a
trademark and is not in use by any real entity.
