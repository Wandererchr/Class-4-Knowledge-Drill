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


## Attribution and disclaimer

Contains information licensed under the [Open Government Licence – Alberta](https://open.alberta.ca/licence).
Sources: [Commercial Driver's Guide](https://open.alberta.ca/publications/commercial-drivers-guide) (Spring 2025) and [Driver's Guide: Cars and Light Trucks](https://open.alberta.ca/publications/drivers-guide) (Spring 2026).

Not affiliated with, endorsed by or produced by the Government of Alberta. These are not the questions used on the real test. The licence requires the attribution line to stay on the page.
