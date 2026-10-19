# GemGauge — landing page

**Live site:** https://asim-ali-peerzada.github.io/gemgauge/

The marketing page for **GemGauge**, a browser extension that shows your
Google Gemini quota and reset countdown on the prompt box itself.

| | |
| --- | --- |
| Chrome Web Store | [Add to Chrome](https://chromewebstore.google.com/detail/gieijfeaidpoohehhicphnplekkppajh) |
| Edge Add-ons | [Get for Edge](https://microsoftedge.microsoft.com/addons/detail/gemgauge-usage-quota-t/abgfffmbmmkoipnlhkdlioogmclagcke) |
| Privacy policy | [Read the policy](https://gist.github.com/asim-ali-peerzada/f8acfd704bf170763088a069a79f7224) |

## How this repo works

This is the **built** site, not its source.

- The `gh-pages` branch is what GitHub Pages serves. It is the compiled
  HTML/CSS/JS of a Next.js static export, mounted at `/gemgauge`.
- The `main` branch holds this README.

The landing page's source lives in the private
[`gem-gauge-extension`](https://github.com/asim-ali-peerzada/gem-gauge-extension)
repository, under `landing-v3/`, alongside the extension itself. Pushing new
copy there and re-running its deploy script updates this site.

`.nojekyll` is required. Without it, Jekyll skips any directory whose name
starts with an underscore — which would drop `/_next/` and leave a blank
page.

## Other links

- Portfolio: https://asimali.is-a.dev/
