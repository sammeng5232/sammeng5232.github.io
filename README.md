# sammeng5232.github.io

This repository publishes the personal website served at
<https://sammeng5232.github.io/>.

**No readable website files are stored in this repository.** The site is
deployed from an AES-256-encrypted package attached to a
[release](https://github.com/sammeng5232/sammeng5232.github.io/releases) on
this repository — opaque ciphertext without the encryption key, which is held
only in Actions secrets. This keeps the website's file list, history, and
sources private while the site itself is publicly served.

Technique adapted from
[Phuker/phuker.github.io](https://github.com/Phuker/phuker.github.io)
(GPL-3.0).

- **Deploy to GitHub Pages** workflow: downloads, decrypts, and publishes the
  encrypted package.
- **Clean up** workflow: removes successful deployment runs from the public
  Actions history.
