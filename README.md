# LeetCode Tracker

Single-file spaced-repetition tracker (`index.html`). Data syncs to `data.json` on the `data` branch, never on `master`, so the public Pages site serves no data. Repo is private; only token holders can read progress.

## Setup on a new machine
1. Open https://justinaslaunikonis.github.io/leetcode-tracker/ (page is public, contains no data). Or `git clone` and open `index.html`.
2. Click **Sync**, paste a fine-grained PAT with **Contents: Read and write** on this repo only.
   Create at https://github.com/settings/personal-access-tokens/new
3. Data pulls on open and pushes ~1.5s after every change. `Sync ✓` / `Sync ✗` in the header shows status.

Remote wins on open, local wins on save (last write wins — don't edit offline on two machines at once).
