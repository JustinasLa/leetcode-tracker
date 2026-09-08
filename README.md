# LeetCode Tracker

Single-file spaced-repetition tracker (`index.html`), hosted at https://justinaslaunikonis.github.io/leetcode-tracker/ (page is public, contains no data).
Progress lives in `data.json` on the private `data` branch, readable only with your token.

## Setup on a new machine
1. Open the URL above.
2. Click **Load** or **Save**, paste a fine-grained PAT with **Contents: Read and write** on this repo only.
   Create at https://github.com/settings/personal-access-tokens/new. Browser remembers it.

## Daily use
- **Load** at start of a session — pulls progress from GitHub (overwrites this browser's copy).
- **Save** at end of a session — pushes progress to GitHub (overwrites GitHub's copy).
- Shift+click **Save** to clear the stored token.

Last write wins, no merge: always Load before, Save after.
