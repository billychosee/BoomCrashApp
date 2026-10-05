How to install: Copy folder to phone, open index.html in Chrome/Safari, Menu > Add to Home Screen. Enter Deriv API token from app.deriv.com > Settings > API Token and Telegram bot token from @BotFather

PWA note: Browser security permits service-worker caching and installable PWA behavior only from HTTPS or localhost. Opening index.html directly can show the interface and attempt the live Deriv WebSocket, but cannot register the service worker or guarantee Add to Home Screen support. Tailwind CSS and web fonts are loaded from CDNs and require internet access. Market prices and signals require a live Deriv connection.

Credential note: Deriv and Telegram tokens are stored in this browser's localStorage, which is not encrypted. Avoid using this on a shared or untrusted device.
