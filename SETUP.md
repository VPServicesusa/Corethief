# Publishing this page

Same shape as the Say the Names site.

## 1. Make the repository

On GitHub, create a new **public** repository named `Corethief`
(the name becomes the URL, so the capital C matters for how it reads).

## 2. Add these files to the root

- `index.md`
- `icon.png`
- `_config.yml`

Drag them in via **Add file → Upload files** if you would rather not use git.

## 3. Turn Pages on

**Settings → Pages → Build and deployment**
Source: *Deploy from a branch*
Branch: `main`, folder `/ (root)` → **Save**

It takes a minute or two, then the site is live at:

    https://vpservicesusa.github.io/Corethief/

## 4. Fill in the App Store link

`index.md` has a placeholder:

    [Download on the App Store](#)

Replace the `#` with your real App Store URL once the app is approved.

## What App Store Connect needs

Two of the fields on the app submission form want URLs, and this one page
serves both:

- **Support URL** → `https://vpservicesusa.github.io/Corethief/`
- **Privacy Policy URL** → `https://vpservicesusa.github.io/Corethief/`

The privacy section at the bottom of the page is what review will read.
It says the app collects nothing and makes no network requests, which is
true — every font, sound and image is embedded in the HTML.

When you fill in **App Privacy** in App Store Connect, answer
*"Data Not Collected"* for every category.

## If you change the repo name

Update the four `meta-og:` lines at the top of `index.md`, which contain
the full URL in three places.
