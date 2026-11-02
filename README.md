# Nostalgia TV — Bachpan Wala TV

Responsive static Hindi TV and childhood-cartoon directory for GitHub Pages.

## Publish
1. Create a GitHub repository, e.g. `nostalgia-tv`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.

## Live viewing
The project includes a starter set of official WAVES watch-page links. These open the broadcaster's official player in a new page; sign-in or regional availability limits may apply. Prasar Bharati says WAVES offers live TV/Radio, including 35 Doordarshan channels and 40+ other TV channels.

For direct in-page HLS playback, add a broadcaster-authorized `.m3u8` URL to that channel's `stream` field in the `channels` array. hls.js support and native-HLS fallback are included. Do not add scraped/pirated IPTV URLs or rebroadcast paid channels without permission. GitHub Pages cannot bypass DRM, login, regional restrictions, or embedding blocks.

Cartoon cards open YouTube search results, not verified episode streams. Choose uploads from rights holders or authorized distributors.
