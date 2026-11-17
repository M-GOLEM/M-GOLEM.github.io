# m-golem.github.io

Source of the personal site at <https://m-golem.github.io/> - profile, projects
and links for Mr.GOLEM.

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
channel banner and a thumbnail template. All images are PNG; the stylesheet is
the only CSS file.

## Editing

The pages are generated from plain HTML; there is no build step and no
dependency. Open `index.html` in a browser to preview. Keep absolute paths
(`/assets/...`) so the site works from the domain root.
