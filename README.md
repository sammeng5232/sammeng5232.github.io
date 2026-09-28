# sammeng5232.github.io

This repository publishes the personal website served at
<https://sammeng5232.github.io/>.

**No readable website files are stored in this repository.** Each site file
is stored AES-256-encrypted as an asset of a
[release](https://github.com/sammeng5232/sammeng5232.github.io/releases) on
this repository, named by a keyed hash of its content, together with an
encrypted manifest that maps the assets to site paths. Without the encryption
key, which is held only in Actions secrets, the assets are opaque ciphertext
with meaningless names. This keeps the website's file list, history, and
sources private while the site itself is publicly served. Because every file
is its own asset, a publish uploads only the files that changed.

Technique adapted from
[Phuker/phuker.github.io](https://github.com/Phuker/phuker.github.io)
(GPL-3.0).

- **Deploy to GitHub Pages** workflow: downloads and decrypts the files, and
  publishes the site.
- **Clean up** workflow: removes successful deployment runs from the public
  Actions history.
