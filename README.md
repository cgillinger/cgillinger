### Christian Gillinger

Personal projects, built for my own use and published in case they are
useful to others.

#### 📚 Colophon

[Colophon](https://github.com/cgillinger/colophon) — self-hosted e-book
library and metadata manager with wireless Kobo sync, cover art fetching
and an in-browser EPUB reader. Flask + Docker; a lightweight alternative
to Calibre-Web that pairs with Komga and Kavita.

Its distinguishing feature is **AI as a librarian's assistant** — as far
as I know, no other self-hosted book server has this. An LLM helps with
the cataloguing problems regular metadata sources can't solve: series
detection, metadata suggestions and author disambiguation. It is strictly
**propose-only** — every suggestion lands in a review view where you
approve field by field, and nothing is ever written to your library on
the AI's say-so. Entirely optional, and works with any OpenAI-compatible
provider or fully local Ollama for complete privacy.

#### ✏️ SkitchG

[SkitchG](https://github.com/cgillinger/SkitchG) — Skitch-inspired image
annotation tool for Linux: arrows, text, shapes and pixelate on existing
images, copied straight to the clipboard. Python + Qt (PySide6).

#### 🧰 Cockpit plugin suite

Plugins for the [Cockpit](https://cockpit-project.org/) web console,
written in plain HTML/JS without build steps or frameworks:

| Plugin | What it shows |
|--------|---------------|
| 🔗 [cockpit-tailscale](https://github.com/cgillinger/cockpit_tailscale) | Tailscale network overview — device status, warnings, push alerts |
| 🌡️ [cockpit-temps](https://github.com/cgillinger/cockpit_temp) | Hardware temperature history (CPU/NVMe) with thresholds, 120 days of PCP archives |
| 💽 [cockpit-smart](https://github.com/cgillinger/cockpit_smart) | S.M.A.R.T. disk health for HDD/SSD/NVMe with history and trend detection |
| ☁️ [cockpit-pcloud](https://github.com/cgillinger/cockpit-pcloud) | pCloud storage quota, account status and backup folder health |

All plugins are listed under the
[`cockpit-plugin` topic](https://github.com/search?q=user%3Acgillinger+topic%3Acockpit-plugin&type=repositories).

#### 🦋 Bluesky tools

- [Blueskybot](https://github.com/cgillinger/Blueskybot) — posts RSS feed
  updates to Bluesky. Node.js + Docker.
- [Skysplitter](https://github.com/cgillinger/skysplitter) — splits long
  texts into Bluesky-sized posts with thread numbering. Also available as a
  [web app](https://github.com/cgillinger/Skysplitter-web) and a
  [desktop app](https://github.com/cgillinger/Skysplitter-desktop).

#### More

Reading, media and automation tools — see
[all repositories](https://github.com/cgillinger?tab=repositories) for the
full list.
