# Nouri Baby — website

Privacy Policy and Terms of Service for the **Nouri Baby** iOS app, in English,
Ukrainian and Spanish. Static HTML, no build step, designed for GitHub Pages.

```
index.html          landing page, links to all six documents
style.css           design tokens lifted from the app's NouriTheme
icon.png            app icon, used as favicon and og:image
en/ uk/ es/         privacy.html and terms.html per language
```

## Who these name

Developer: **Mykola Kobetiak** · Contact: **kobetiakm@gmail.com** ·
Governing law: **the Province of Manitoba, Canada**.

The developer name is written in Latin script in all three languages, so it
matches the name on the Apple Developer account rather than transliterating
per language.

The `[your name]` / `[ваше імʼя]` / `[tu nombre]` in the iCloud deletion
instructions is deliberate — that is how iOS labels the row in Settings.

## Publishing on GitHub Pages

1. Create an empty repository on GitHub, e.g. `nouri-baby-site`.
2. Push this directory to it.
3. Repository → **Settings → Pages** → Source: *Deploy from a branch*,
   Branch: `main`, folder: `/ (root)`. Save.
4. After a minute the site is at `https://<user>.github.io/nouri-baby-site/`.

## URLs for App Store Connect

App Store Connect takes one privacy policy URL per localisation:

- English — `https://<user>.github.io/nouri-baby-site/en/privacy.html`
- Ukrainian — `https://<user>.github.io/nouri-baby-site/uk/privacy.html`
- Spanish — `https://<user>.github.io/nouri-baby-site/es/privacy.html`

Terms of Service is optional in App Store Connect; if you leave it blank Apple
applies its standard EULA. Supply `.../en/terms.html` to use these instead —
they contain the medical disclaimer, which Apple's standard EULA does not.

## These documents are a draft, not legal advice

They describe accurately what the app does, which is the hard part and the part
most templates get wrong. They have not been reviewed by a lawyer. Have someone
qualified check them before release, particularly the GDPR sections — you are
shipping to the EU.
