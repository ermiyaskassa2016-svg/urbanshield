# UrbanShield Janitorial website: launch guide

Files in this folder:

- `index.html`: the website (one page, no build step)
- `privacy.html`: the privacy notice linked from the form
- `404.html`: friendly "page not found" page
- `robots.txt`
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## 1. Before you go live (10 minutes)

1. **Connect the form.** Create a free account at formspree.io and make a new form that sends to `ermiyas@perseavitalis.ca`. Copy the form ID (it looks like `xyzabcd`). In `index.html`, find `https://formspree.io/f/YOUR_FORM_ID` and replace `YOUR_FORM_ID` with your ID. Until you do this, the form tells visitors to call or email instead.
2. **Only claim what's true on launch day.** The site says you are incorporated, HST-registered, insured ($2M CGL), bonded, WSIB-covered, police-checked and using ATP testing. Make sure each one is in place (see file 08, Owner Actions) before the site is public.
3. **Privacy notice.** In `privacy.html`, replace `[date of launch]` with the real date.
4. **Founder quote.** The founder note on the page is a draft written for you. Edit it in your own words if you want to.

## 2. Publish on GitHub Pages (free)

1. Sign in to GitHub with the Persea Vitalis account.
2. Click **New repository** and name it `urbanshield-website` (or `<account-name>.github.io` if you want the site at the account's root address). Make it **Public**.
3. Click **Add file > Upload files** and drag in **all** the files from this folder, including `.nojekyll`. If your computer hides it, any empty file named `.nojekyll` works. Click **Commit changes**.
4. Go to **Settings > Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After about 1-2 minutes, the site is live at `https://<account-name>.github.io/urbanshield-website/`.

## 3. Use your own domain (recommended for credibility)

1. Buy a domain, for example `urbanshieldjanitorial.ca` (a .ca domain is about $15-25 a year from a CIRA-certified registrar).
2. In GitHub **Settings > Pages > Custom domain**, enter the domain and save. GitHub creates a `CNAME` file.
3. At your registrar, add the DNS records GitHub shows: four `A` records for the root domain, plus a `CNAME` for `www` pointing to `<account-name>.github.io`.
4. Back in GitHub Pages, tick **Enforce HTTPS** once it becomes available.
5. Set up a matching email (for example `hello@urbanshieldjanitorial.ca`) with Google Workspace. Then update the email address in `index.html`, `privacy.html` and the Formspree form.

## 4. After launch

- Create a Google Business Profile (service-area business, North York) and link to the site.
- Add the site link to the LinkedIn company page, email signature, capability statement (06f) and proposals.
- Once you have real clients, and with their written permission, add 2-3 short testimonials or ATP before/after results.
