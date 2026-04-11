# doreataru

> **どれあたる** — Spin the wheel and let fate decide.

A zero-dependency roulette spinner that runs entirely in your browser, deployed on Cloudflare Pages.

## Deployed

<https://doreataru.kotaoue.workers.dev/>

## Features

- Canvas-drawn colorful spinning wheel
- Item list input (one item per line)
- URL sharing — items encoded as a query parameter so you can bookmark or send a loaded wheel
- Smooth spin animation with easing
- Result display after each spin
- Video recording and WebM download of each spin
- Toast notifications for user feedback
- Mobile-friendly responsive layout

## Getting Started

### Local preview

Open `index.html` directly in a browser. No server, build tool, or dependencies required.

### Deploy to Cloudflare Pages

1. Push this repository to GitHub.
2. In the Cloudflare Dashboard, go to **Workers & Pages → Create application → Pages**.
3. Connect this GitHub repository.
4. Leave build settings empty (pure static HTML — no build command, no output directory).
5. Click **Save and Deploy** — your site will be live in seconds.

## Usage

1. Enter items in the text area, one per line (e.g. names, food options, choices).
2. Click **▶ 回す** to spin the wheel.
3. The result is shown once the wheel stops.
4. Use **🔗 URLをコピー** to copy a shareable link with your current item list.
5. Use **⬇ 動画をDL** to download a WebM recording of the spin.

## License

[MIT](LICENSE)
