# Hi, I'm Jericho 👋

I build **local-first tools** — apps where your data stays on your machine. No accounts, no backend, no telemetry.

## Featured projects

### 🔥 [FirePath](https://github.com/jerichoapo/firepath) · [live demo](https://firepath-one.vercel.app)

A financial independence (FIRE) planner that models your financial future and stress-tests it against 150 years of market history — entirely in the browser. Deterministic year-by-year projections, Monte Carlo simulation, five account types with tax-aware withdrawal ordering, all persisted to IndexedDB.

`TypeScript` · vitest unit tests on the projection engine · full Playwright e2e suite · CI on every push

### 🩺 [PT App](https://github.com/jerichoapo/pt-documentation-app) · [live demo](https://pt-app-zeta.vercel.app)

SOAP-note documentation built for a school-based pediatric physical therapist and shaped by real daily use. Guided documentation wizard, copy-forward from prior sessions, timestamped amendment trail, signed PDF/DOCX exports, 30-day trash with cascade restore — with every note living in the browser's localStorage, nothing on a server.

`React` · localStorage persistence · pdfmake + docx exports

### 📝 [Caption Scribe](https://github.com/jerichoapo/caption-scribe)

A Firefox extension that exports YouTube captions as clean, readable Markdown (plus SRT, WebVTT, and plain text). It reflows fragmentary caption cues into paragraphs, strips the roll-up duplication that makes auto-caption exports unreadable, and carries chapter headings and clickable timestamps into the output.

`JavaScript` · pure browser-independent core · 62 unit tests
