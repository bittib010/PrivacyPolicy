# PrivacyPolicy

The privacy policies for bittib010's apps, served by GitHub Pages from the
root of `main`: <https://bittib010.github.io/PrivacyPolicy/>

| Page | URL | For |
| --- | --- | --- |
| `index.html` | `/PrivacyPolicy/` | the front page: pick an app |
| `matte.html` | `/PrivacyPolicy/matte.html` | Matte (`no.matte.matte`) |
| `noteworthy.html` | `/PrivacyPolicy/noteworthy.html` | NoteWorthy |
| `style.css` | — | the one stylesheet all three share |

**The NoteWorthy policy moved.** It used to be the front page, so anything
pointing at `/PrivacyPolicy/` for NoteWorthy — the Play Console listing above
all — now lands on the app chooser instead, and needs repointing at
`/PrivacyPolicy/noteworthy.html`.

`matte.md` is the Markdown the Matte page was made from, kept in step with
`docs/PRIVACY.md` in the Matte repository, which is where that policy is
written. **Editing `matte.md` does not change the site**: `matte.html` is what
is served, so a change has to be made in both.

## Adding another app

Copy one of the policy pages, keep the `<link rel="stylesheet">` and the
`← All privacy policies` link, and add a card for it to `index.html`. The card
takes its colour from `class="mark <app>"`, defined in `style.css`.
