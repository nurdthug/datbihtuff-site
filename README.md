# DATBIHTUFF Landing Site

Static GitHub Pages landing page for the first DATBIHTUFF drop by OPIN Global.

No frameworks, no build step, no paid services required.

## Files

- `index.html` - homepage
- `main.css` - responsive streetwear drop styling
- `CNAME` - custom domain for GitHub Pages
- `assets/datbihgah.png` - DATBIHGAH design preview
- `assets/datbihtuff.png` - DATBIHTUFF design preview
- `assets/mockup-datbihgah.png` - product mockup
- `assets/mockup-datbihtuff.png` - product mockup
- `assets/print-datbihgah-4500x5400.png` - print-prep PNG
- `assets/print-datbihtuff-4500x5400.png` - print-prep PNG

## GitHub Pages Setup

1. Open the repo settings on GitHub.
2. Go to `Pages`.
3. Set source to `Deploy from a branch`.
4. Set branch to `main` and folder to `/ (root)`.
5. Save.
6. Set custom domain to `datbihtuff.com`.
7. Enable HTTPS after GitHub provisions the certificate.

## DNS For Namecheap

Add these records for `datbihtuff.com`.

Root domain A records:

```text
@  A  185.199.108.153
@  A  185.199.109.153
@  A  185.199.110.153
@  A  185.199.111.153
```

WWW record:

```text
www  CNAME  <the GitHub Pages username or OPIN Global organization domain shown by GitHub>
```

Shop subdomain:

```text
shop  reserved for Printify Pop-Up Store
```

Do not point `shop.datbihtuff.com` until Printify gives the required DNS instructions.

## Email Capture

The form is visually ready and currently points to:

```text
https://formspree.io/f/YOUR_FORM_ID
```

Create a free Formspree, ConvertKit, Beehiiv, Mailchimp, or Google Forms endpoint and replace `YOUR_FORM_ID`.

## Printify Pop-Up Store Plan

Use Printify Pop-Up Store first. Do not use Shopify yet.

Products:

- `DATBIHGAH tee`
- `DATBIHTUFF tee`

Recommended blanks:

- Bella+Canvas 3001 for standard tee
- Comfort Colors 1717 for premium streetwear tee

Pricing:

- Standard tee: `$34.99`
- Premium tee: `$39.99` to `$44.99`
- Hoodie later: `$64.99` to `$74.99`

Shirt colors:

- Black
- White
- Royal blue
- Cream or ivory if available

## Product Descriptions

DATBIHGAH tee:

The kool-aid pineapple spear became canon. DATBIHGAH front graffiti print featuring the fictional DATBIH character on a streetwear tee. Bold blue, black, white, and red energy. First drop. No restocks unless the internet demands it.

DATBIHTUFF tee:

The jar said everything that needed to be said. DATBIHTUFF sticker-style graffiti print featuring the fictional DATBIH character. Premium feel, meme energy, zero explanation. First drop pricing only.

## Print File Specs

- `4500 x 5400 px`
- Transparent PNG prepared where edge background removal was safe
- 300 DPI preferred
- Centered layout
- No random white box
- No scenery background
- Large readable text

## Legal And IP Cleanup

Before publishing products for sale, clear or revise if needed:

- Any school/team-looking mark, including the hat letter `R`
- Any third-party-looking character or graphic on clothing
- Any real-person identifiers

Current repo assets can be treated as preview placeholders until final print-ready files are uploaded.

## Social Launch Captions

```text
bro turned kool-aid into a clothing line.
DATBIHTUFF first drop loading.
```

```text
DATBIHGAH or DATBIHTUFF?
choose your fighter.
```

```text
the jar said everything.
first drop at datbihtuff.com.
```

```text
two flavors. zero explanation. maximum flavor.
DATBIHTUFF.
```

```text
fictional flavor. real shirt.
DATBIHTUFF by OPIN Global.
```

## Launch Checklist

- Finalize transparent print files
- Create Printify Pop-Up Store
- Upload DATBIHGAH and DATBIHTUFF products
- Set pricing
- Connect `shop.datbihtuff.com`
- Connect `datbihtuff.com` to GitHub Pages
- Post first reveal video
- Collect first orders
- Order samples only after approval

## Blockers

- GitHub Pages still requires account-level settings if not already enabled.
- Namecheap DNS requires registrar access.
- Printify product publishing requires Printify access.
- Printify and Namecheap setup still require logged-in browser access.
- Final merch sale should wait until product assets are reviewed and approved inside Printify.
