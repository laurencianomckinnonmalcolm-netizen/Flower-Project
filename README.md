# The Garden

A password-gated page: enter the right password and pink/white flowers
fall and fill the screen. Leave (scroll down, switch tabs, or click away)
and a hidden message fades in.

## Deploy it on GitHub Pages (free, ~2 minutes)

1. Create a new repository on GitHub (any name, e.g. `the-garden`).
2. Upload `index.html` from this folder to the repository
   (use "Add file" → "Upload files" on the GitHub website — no command
   line needed).
3. Go to the repo's **Settings** → **Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   pick the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will give you a live URL after a minute or two, usually:
   `https://<your-username>.github.io/<repo-name>/`
6. Open that URL. You'll see the setup screen — type your password and
   message and click "Create the garden". Because the page now has a
   real address, it'll build the link correctly on its own (the
   "published link" field can stay blank).
7. Copy the generated link, shorten it with tinyurl.com if you like,
   and send it to anyone — it'll work the same on any device.

## Notes

- The password and message are encoded in the link itself (not stored
  on a server), so anyone with the link and the right password can open
  it. It's a fun surprise, not real encryption.
- Everything is in the single `index.html` file — no build step,
  no dependencies to install.
