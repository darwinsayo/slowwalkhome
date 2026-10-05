# Slow Walk Home

Reflections by Emmett Walker — slowwalkhome.com

Built with Eleventy, edited with Pages CMS, and hosted on Cloudflare Pages
(the same setup as manymanytoes).

## Writing posts
Open the repo in Pages CMS (app.pagescms.org) → **Posts** → **Add an entry**.
Fill in title, date, category, a one-line summary, and the body. Tick **Draft**
to keep a post hidden until it's ready.

The two posts dated Oct 1 and Oct 3, 2026 are samples. Delete them when you
publish your first real post.

## Cloudflare Pages settings
- Framework preset: Eleventy (or None)
- Build command: `npm run build`
- Build output directory: `_site`
- Environment variable: `NODE_VERSION` = `22`

Then add the custom domain slowwalkhome.com under the project's
**Custom domains** tab.

## Keeping it anonymous
- Use a GitHub account and email that aren't tied to your real name
  (for example, an Emmett Walker account), or keep the repo private.
- Set git's author name for this repo:
  `git config user.name "Emmett Walker"` and a matching email.
- Check that domain WHOIS privacy is turned on at the registrar.

## Local preview (optional)
    npm install
    npm start
