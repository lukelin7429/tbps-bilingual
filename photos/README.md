# Photos needed from Taibao Elementary

The page heroes currently render as **gradients** (no broken images), and the principal photo shows a placeholder box. To swap in real photos, drop the files here and follow the comments in `assets/css/main.css` and the page HTML.

Per Luke's school-site rules: **hero / banner images use buildings, gates, the school crest, or landscape — not photos of people** (privacy + they don't go out of date). Student/activity photos may be used in body cards only with portrait-rights consent.

| Filename | Used on | Spec | Notes |
|---|---|---|---|
| `hero-school.jpg` | Home title hero | ≥ 1920×1080, landscape | School gate / building / crest. Uncomment the `url()` line in `.title` in `main.css`. |
| `principal-portrait.jpg` | Home + Principal page | ≥ 1200×1200 (square-ish) | Replace the `.placeholder` block in `index.html` and `principal/index.html`. |
| `crest.png` | (optional) topbar / favicon | transparent PNG | School crest if the school provides one. |
| `around-*.jpg` | (optional) Around Taibao stations | ≥ 1600×1200 | Fuji Temple, Wang Family Shrine, Southern Palace Museum, etc. — only if cleared for reuse. |

Also pending from the school (see the project notes in the vault): the principal's **name romanisation, biography, and portrait**, and the current **class / student counts** (registry shows 17–18 classes, ~345 students — confirm before publishing any number).
