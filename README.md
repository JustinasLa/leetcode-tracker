# LeetCode Tracker

Single-file spaced-repetition tracker (`index.html`). Data syncs to `data.json` in this repo.

## Setup on a new machine
1. `git clone https://github.com/JustinasLa/leetcode-tracker` and open `index.html` in a browser.
2. Click **Sync**, paste a fine-grained PAT with **Contents: Read and write** on this repo only.
   Create at https://github.com/settings/personal-access-tokens/new
3. Data pulls on open and pushes ~1.5s after every change. `Sync ✓` / `Sync ✗` in the header shows status.

Remote wins on open, local wins on save (last write wins — don't edit offline on two machines at once).
`git pull` occasionally to get tracker updates.
