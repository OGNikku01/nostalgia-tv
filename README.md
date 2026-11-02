# Nostalgia TV — Bachpan Wala TV

A responsive static Hindi TV and childhood-cartoon directory for GitHub Pages.

## Publish
1. Create a GitHub repository (for example, `nostalgia-tv`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Wait for the published Pages URL.

## Playback and rights
This is a front-end directory, not a TV-streaming service. The channel cards intentionally do not contain invented stream URLs. To enable playback, add broadcaster-authorized HLS or official embeddable-player URLs in the `channels` array in `index.html`. Do not use scraped/pirated IPTV playlists or rebroadcast paid channels without permission. Some providers require login/DRM or block embedding; GitHub Pages cannot bypass those restrictions.

The cartoon buttons open YouTube search results, not verified episode links. Select uploads from the rights holder or an authorized distributor. A quality selector can only be added when the provider exposes multiple renditions or adaptive streaming.
