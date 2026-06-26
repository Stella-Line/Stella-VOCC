# Stella VOCC

Marketing website for Stella VOCC — vessel operator and ship & cargo brokerage serving
the Gulf of America, Caribbean Basin, Central America and northern South America.

## Contents
- `index.html` — single-page site (services, weekly market letter, quote form, about)
- `stella-line-logo.png` — brand logo

## Local preview
Open `index.html` in any browser, or run a static server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy (Vercel)
This is a static site — no build step. Import the repo into Vercel as a new project;
the default settings work (framework preset: "Other", output: root).

## To do
- [ ] Wire the quote form: replace `REPLACE_WITH_YOUR_ID` in `index.html` with a
      Formspree form ID (https://formspree.io) so inquiries reach chartering@stella-line.com
- [ ] Publish weekly market letter issues
- [ ] Connect custom domain
