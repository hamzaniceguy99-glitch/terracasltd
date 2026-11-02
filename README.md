# Terracas — terracas ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terracasltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terracasltd.mjs`).
> To change the content, edit that file and run `node build.mjs terracasltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terracasltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($£[AMOUNT] / $£[AMOUNT] pcm / $£[AMOUNT]) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terracas Ltd develops building projects, buys and sells property on its own account and lets property it owns or leases, working from Cambuslang in Glasgow. The company was formed in July 2024, so we claim no long track record, and what we can offer instead is being straight about the ground rules. This is Scotland, and Scots law is a separate legal system rather than a regional variation of the English one. Three differences matter to anyone dealing with us. Most homes cannot be marketed for sale here without a Home Report, which bundles a survey, an energy report and a property questionnaire and is paid for by the seller, where an English buyer would commission their own survey afterwards. A sale becomes binding when missives are concluded, which happens earlier than people expect and is why gazumping is far rarer here. And a private residential tenancy has no fixed term and no end date: there is no no-fault notice in Scotland, and recovering a property requires a statutory ground and a tribunal decision. We would rather you knew all three before dealing with us than afterwards. Site: terracasltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
