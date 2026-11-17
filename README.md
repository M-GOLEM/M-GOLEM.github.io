# mrsayrws.github.io

Source of the personal site at <https://mrsayrws.github.io/> — profile, technical
writing and contact links for Mr Sayrws (mrsayrws).

Static HTML and CSS only: no trackers, no cookies, no external JavaScript.

## Pages

| Path | Content |
|---|---|
| `/` | Profile, selected repositories, writing highlights, contact |
| `/blog/` | Technical writing index |
| `/blog/discord-token-grabbers.html` | How token grabbers work and how to stop them |
| `/blog/adb-fastboot-windows-guide.html` | ADB/fastboot diagnostics on Windows |
| `/blog/android-dns-ad-blocking.html` | Rootless DNS filtering via `VpnService` |
| `/blog/totp-vault-dotnet.html` | TOTP vault design: AES-GCM, PBKDF2, failure modes |
| `/press.html` | Bio, topics and media assets |
| `/feed.xml` | RSS feed for the writing |
| `/sitemap.xml` | Sitemap for search engines |

## Assets

`assets/` holds the shared stylesheet, the social card (`og.png`), the YouTube
channel banner and a thumbnail template. All images are PNG; `site.css` is the
only stylesheet.

## Editing

There is no build step and no dependency. Open `index.html` in a browser to
preview. Keep absolute paths (`/assets/...`) so the site works from the domain
root.
