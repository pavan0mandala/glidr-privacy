# Privacy Policy — Glidr

_Last updated: 21 June 2026_

Glidr ("the app", "we") is an IPTV client published by **Syntaxer**. This policy explains what data the app handles and how it is used.

## Summary

- We do **not** operate any backend server.
- We do **not** collect, store, or transmit your personal information.
- All credentials and playlists you enter stay on your device.
- The app only communicates with the IPTV servers **you** add and with YouTube when you choose to play a trailer.

## Data You Provide

When you connect a source (Xtream Codes account or M3U/M3U8 playlist URL), the app stores the following **locally on your device only**, using Android's encrypted preferences (`AsyncStorage`):

- Xtream server URL, username, and password (if you use Xtream).
- M3U playlist URL or imported playlist content (if you use M3U).
- Your in-app preferences (favourite languages/categories/countries, last selected category, continue-watching history).

This information is **never transmitted to Syntaxer** and is **never sent to any third party** other than the IPTV provider you yourself configured. Uninstalling the app removes all of it.

## Data Sent to Third Parties

Glidr communicates with:

1. **Your IPTV provider** — the server URL you entered. The app fetches channel lists, EPG data, and video streams from it. Whatever logging that provider performs is governed by **their** privacy policy, not ours.
2. **YouTube (Google LLC)** — when you tap "Watch trailer" on a movie or series, the app loads a YouTube embed in an in-app web view. This is subject to [YouTube's Terms of Service](https://www.youtube.com/t/terms) and [Google's Privacy Policy](https://policies.google.com/privacy).
3. **Channel logo CDNs** — public image URLs included in the playlist you configured. Used only to display logos.

Glidr does not send any analytics, telemetry, crash reports, or advertising identifiers.

## Permissions Glidr Requests

| Permission | Why |
|---|---|
| `INTERNET` | To reach the IPTV server and YouTube when you ask it to. |
| `READ_EXTERNAL_STORAGE` / `WRITE_EXTERNAL_STORAGE` (Android 12 and below) | To let you import a local `.m3u` file if you choose to. |
| `VIBRATE` | For optional haptic feedback. |
| `SYSTEM_ALERT_WINDOW` | Picture-in-picture playback. |

## Content Disclaimer

Glidr is a **player only**. It does not ship, host, recommend, or curate any content. You are solely responsible for the streams you connect to and must ensure you have the right to access them in your jurisdiction. We do not bundle, suggest, or distribute any default playlist.

## Children

Glidr is not directed at children under 13 and does not knowingly collect data from anyone.

## Changes

If this policy changes, the "Last updated" date above will change and the new version will be posted at the same URL.

## Contact

For privacy questions, email: **bills0mandala@gmail.com**

