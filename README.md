# Class 4 Knowledge Drill

Unofficial practice test for the Alberta Class 4 knowledge test.

- 400 questions written from the *Commercial Driver's Guide* (Spring 2025) and the *Driver's Guide: Cars and Light Trucks* (Spring 2026). Every answer cites its page (CDG / DG).
- Real test format: 30 random questions, 25 to pass, the test stops at 6 wrong.
- Study mode, a drill of your own mistakes, and a table of every number in both guides.
- English interface with a Ukrainian toggle. Questions are in English, as on the test.
- Progress stays in the visitor's browser (localStorage). No server, no accounts, no analytics.

## Files

| File | Contents |
|---|---|
| `index.html` | the app |
| `bank.js` | question bank |
| `numbers.js` | numbers table |

Question format in `bank.js`: `{c, q, o, a, s, w, lo}` — category, question, four options, answer index (always `0`: the correct answer is `o[0]`; options are shuffled at runtime), source page, explanation, and `lo: 1` on low-yield questions (chapter 10 fuel economy).

## Publish on GitHub Pages

1. Create a **public** repository, for example `class4-drill`. On GitHub Free, Pages works only for public repositories.
2. Upload `index.html`, `bank.js`, `numbers.js` and `README.md` to the root of the `main` branch: **Add file → Upload files → Commit changes**.
3. **Settings → Pages** (in the "Code and automation" section) → **Build and deployment → Source: Deploy from a branch** → branch `main`, folder `/ (root)` → **Save**.
4. After a minute or two the site is live at `https://<username>.github.io/class4-drill/`.

To update the site, upload the changed files again. It redeploys automatically.

## Alternative: Cloudflare Pages

In the Cloudflare dashboard: **Workers & Pages → Create application → Get started → Drag and drop your files** → enter a project name, drop the folder → **Deploy site**. The site is served at `https://<project>.pages.dev`. To update it, use **Create a new deployment**.

## Attribution and disclaimer

Contains information licensed under the [Open Government Licence – Alberta](https://open.alberta.ca/licence).
Sources: [Commercial Driver's Guide](https://open.alberta.ca/publications/commercial-drivers-guide) (Spring 2025) and [Driver's Guide: Cars and Light Trucks](https://open.alberta.ca/publications/drivers-guide) (Spring 2026).

Not affiliated with, endorsed by or produced by the Government of Alberta. These are not the questions used on the real test. The licence requires the attribution line to stay on the page.
