# See Through Script Reader Website

Static GitHub Pages website for the **See Through Script Reader** Android app.

This repository contains only the public product website, legal pages, and support information. It does **not** contain the Android application source code, APKs, AABs, signing keys, or development roadmap.

## Included pages

- `index.html` — product homepage
- `about.html` — product background and principles
- `privacy.html` — app and website privacy policy
- `support.html` — support and troubleshooting
- `terms.html` — terms of use
- `404.html` — custom not-found page

## Recommended repository

Create this public repository:

```text
https://github.com/Coinimain/see-through-script-reader-site
```

The GitHub Pages URL will be:

```text
https://coinimain.github.io/see-through-script-reader-site/
```

The privacy-policy URL for Google Play and the app will be:

```text
https://coinimain.github.io/see-through-script-reader-site/privacy.html
```

## Publish with Git

Create the empty repository on GitHub first. Then open Git Bash inside this folder and run:

```bash
git init
git add .
git commit -m "Launch See Through Script Reader website"
git branch -M main
git remote add origin https://github.com/Coinimain/see-through-script-reader-site.git
git push -u origin main
```

Then on GitHub:

1. Open **Settings** for the repository.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Save.

## Before launch

Review these items:

- Confirm that `Coinimain` matches the public developer/provider name you will use.
- Confirm the support email: `contact.countdowntodo+scriptreader@gmail.com`.
- Confirm the Android package: `com.seeThrough.scriptreader`.
- Update the privacy-policy effective date if publication occurs later.
- Replace the “Google Play · Coming soon” element on `index.html` with the live listing link after publication.
- Update the privacy policy and Data safety disclosures before adding ads, analytics, crash reporting, accounts, cloud sync, or any other data-collecting service.
- Do not place the Android source project or release signing key in this repository.

## Google Play button after launch

Replace the coming-soon element with:

```html
<a class="button button-primary"
   href="https://play.google.com/store/apps/details?id=com.seeThrough.scriptreader">
  Get it on Google Play
</a>
```

## Ads later

Do not add `app-ads.txt` until you have the final advertising network publisher ID. When ads are introduced:

1. Update `privacy.html` with the advertising provider and data practices.
2. Update the in-app privacy link or text.
3. Update Google Play Data safety.
4. Change the Play Console declaration to **Contains ads**.
5. Add the network-authorized `app-ads.txt` line at the site root if required.

## Local preview

Double-click `index.html`, or use a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Licence

Website content and branding are copyright Coinimain. No licence is granted for reuse of the design, copy, or brand assets merely because the repository is publicly visible.
