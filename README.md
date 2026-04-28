# balloonshaper.xyz

Static GitHub Pages site for the Aeronaut balloon/airship `.nbt` generator.

## Local dev

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This repo is intended to be published with GitHub Pages from the default branch.

## Custom domain DNS

To point `balloonshaper.xyz` at GitHub Pages, add DNS records at your registrar:

- `A` records for apex (`@`) → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- Optional: `AAAA` records for apex (`@`) → `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
- Optional: `CNAME` for `www` → `<your-github-username>.github.io`

The `CNAME` file in this repo sets the Pages custom domain to `balloonshaper.xyz`.
