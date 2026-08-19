# linkedin-redirect

A one-page GitHub Pages site that exists for a single reason: to give a clean, shareable URL for
LinkedIn's Featured section.

- **Live:** https://quasimodallabs.github.io/linkedin-redirect/
- **Redirects to:** a pre-filled ChatGPT prompt asking for a brutally honest analysis of
  [QuasiModalLabs/tender-vault](https://github.com/QuasiModalLabs/tender-vault)

`index.html` redirects via `window.location.replace()` and carries a visible fallback link for
browsers with JavaScript disabled. No external dependencies.

Kept deliberately separate from the tender-vault repository.
