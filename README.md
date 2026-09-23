# odperez.com

Personal academic website of Omar David Perez, served with GitHub Pages.
Plain HTML and CSS, so there is no build step.

| File | Page |
|---|---|
| `index.html` | Home: bio, research questions, recent publications |
| `publications.html` | Full publication list, grouped by year |
| `collaborators.html` | Collaborators |
| `contact.html` | Contact details |
| `404.html` | Not-found page |
| `home/`, `publications/`, `collaborators/`, `contact/` | Redirects from the old Google Sites URLs |
| `assets/style.css` | All styles (light and dark mode) |

To add a paper, copy an existing `<li>` in `publications.html` (and in
the "Recent publications" list in `index.html`, if it's recent) and edit it.

## Going live

1. Make the repository public (Settings → General → Danger zone → Change visibility).
2. Settings → Pages → Source: *Deploy from a branch*, pick the branch and `/ (root)`.
3. At the domain registrar for `odperez.com`, replace the Google Sites records with:
   - `A` records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www`: `omadav.github.io`
4. Back in Settings → Pages, set the custom domain to `odperez.com` and tick *Enforce HTTPS* once available.
