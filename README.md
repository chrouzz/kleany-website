# Kleany.com

Static brand showcase website for [Kleany](https://kleany.com) — sustainable compressed towel tablets.

## Structure

```
index.html          Single-page website (inline CSS, no dependencies)
img/                Optimized product & lifestyle images (JPG, ~730KB total)
```

## Development

Open `index.html` in a browser. No build step required.

## Deployment

Hosted via GitHub Pages with a custom domain (`kleany.com`) registered on GoDaddy.

### DNS Setup (GoDaddy)

Add these records for `kleany.com`:

| Type  | Name | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | `<username>.github.io` |

Then in GitHub repo Settings > Pages, set custom domain to `kleany.com` and enable HTTPS.
