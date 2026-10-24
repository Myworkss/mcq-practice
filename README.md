# MCQ Practice – Pakistan Studies

Single-page web app (no build step). 2946 MCQs split into 10 tests (9 x 300, last = 246).
Correct = green, wrong = red + correct answer shown. Wrong answers go to **Again Practice**.
Progress is saved in the browser (localStorage).

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g. `mcq-practice`), upload `index.html` and `.nojekyll` to the root.
2. Repo -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main` / `(root)` -> Save.
3. After ~1 minute your URL will be `https://<your-username>.github.io/mcq-practice/`

## Sync between laptop and phone
Progress lives in each browser, so the app can sync it through a private GitHub Gist on your own account.
On EACH device: open the app -> "Sync between devices" -> create a GitHub token with only the `gist` permission
(the link in the app pre-selects it) -> paste it -> Connect. Do the laptop first so your existing progress is uploaded.
