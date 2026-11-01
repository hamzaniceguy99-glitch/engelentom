# Engelen Tom — engelen tom bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `engelentom.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/engelentom.mjs`).
> To change the content, edit that file and run `node build.mjs engelentom` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@engelentom.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are ENGELEN TOM, based in Maasmechelen in Limburg, working in technical inspection and analysis, engineering support and related business services. We start every job with a question clients are rarely asked: what is this report actually for, and who is legally required to sign it. It matters because accreditation runs per scope. A body accredited for one method is not accredited for another, and a result produced outside an accredited scope is a competent opinion rather than an accredited result, however good the engineer. Several Belgian examinations are reserved to a body holding a specific approval, and no amount of expertise substitutes for that approval. There is a second limit worth stating out loud, which is independence. The inspection standard distinguishes an independent third party from a body inspecting its own organisation or its own supply, and that means no one can validly certify their own design or their own installation. So we tell you the scope we work within, we say when a report has to come from someone else, and we would rather lose the work than hand you a document that cannot carry the weight you need to put on it. Site: engelentom.shop
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
