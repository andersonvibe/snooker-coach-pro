# Snooker Coach Pro

Snooker practice, coaching, trick shots and matches against the computer, as an installable web app.

Live app: https://andersonvibe.github.io/snooker-coach-pro/

- `index.html` is the whole app. `manifest.webmanifest`, `sw.js` and the icons let Chrome install it and open it offline.
- Your stats, best breaks and saved matches are stored in Chrome on the phone you play on.
- The optional coach's write-up uses your own Anthropic API key, stored only on your phone. Never put the key in any file here.

## Updating
Replace `index.html`, then change `scp-v1` in `sw.js` to the next number (`scp-v2`, `scp-v3`…) so phones pick up the new version.
