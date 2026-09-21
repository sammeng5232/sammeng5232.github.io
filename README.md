# sammeng5232.github.io

This repository publishes the personal website served at
<https://sammeng5232.github.io/>.

**No website files are stored in this repository.** The site is deployed
from an AES-256-encrypted package kept as a release asset on a private
source repository, which keeps the website's file list, history, and
sources private while the site itself is publicly served.

Technique adapted from
[Phuker/phuker.github.io](https://github.com/Phuker/phuker.github.io)
(GPL-3.0).

- **Deploy to GitHub Pages** workflow: downloads, decrypts, and publishes
  the encrypted package.
- **Clean up** workflow: removes successful deployment runs from the
  public Actions history.
