# LinkedIn Profile Kit — BinAref

A single self-contained page holding the copy-ready text for Abdulrahman Aref's
LinkedIn profile, in the order LinkedIn asks for it, in English, Arabic and Turkish.

## Open it without hosting anything

Double-click `index.html`. It works offline in any browser — no server, no build step,
no dependencies. **This is the simplest option and the one to prefer.**

## Host it on GitHub Pages

Only if a link is genuinely needed instead of a file.

1. Create a repository (e.g. `profile-kit`).
2. Upload `index.html` to the root of the `main` branch.
3. **Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save.**
4. Wait about a minute. The page appears at `https://<username>.github.io/profile-kit/`.

### Read this before you publish it

**A GitHub Pages site from a public repository is readable by anyone with the URL.**
This page contains a personal phone number and email address. The page carries a
`noindex, nofollow` tag, which keeps it out of Google results, but that is a request
search engines honour — it is not access control. Anyone given the URL can open it,
and so can anyone who finds the repository.

Three ways to handle that, best first:

1. **Send the `index.html` file directly** (WhatsApp, email, Telegram). Nothing is
   published, the file works by double-clicking, and it stays between the two of you.
2. **Delete the phone row before publishing.** Open `index.html`, find the line
   containing `+90 536 913 02 60`, delete that whole `<tr>...</tr>`, and send the
   number separately.
3. **Publish as is** — a deliberate choice, made knowing the above.

Delete the repository when the profile is finished; the page has no purpose after that.

## Editing

Everything is in `index.html` — markup, styles and script in one file.
The three language versions live side by side as `data-lang="en" | "ar" | "tr"`
elements; the buttons at the top switch which set is visible.
