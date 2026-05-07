# CapturePush

**Free macOS screenshot & screen recording app.** Capture, annotate, and instantly upload to your own server.

[Download for Mac](https://capturepush.com/CapturePush.dmg) · [Website](https://capturepush.com)

## Features

- **Multiple capture modes** — Area selection, window, full screen, timed, and scrolling capture
- **Screen recording** — Record GIF or MP4 of any screen region
- **Annotation tools** — Rectangles, arrows, text, highlights, and redaction/obfuscation
- **Upload to your own server** — SSH/SCP, S3-compatible (AWS, Cloudflare R2, Backblaze B2, MinIO), or local save
- **Instant clipboard URL** — One click from screen to shareable link
- **Menu bar app** — Lives in your macOS menu bar, always one click away
- **Global hotkeys** — Configurable keyboard shortcuts for all capture modes
- **Scrolling capture** — Capture entire web pages and long documents
- **Smart upload routing** — Upload recordings while saving screenshots locally, or upload everything
- **Privacy-first** — Your files go to YOUR server, not someone else's cloud

## Requirements

- macOS 13.0 (Ventura) or later
- Apple Silicon (arm64)

## Install

Download the latest DMG from [capturepush.com](https://capturepush.com/CapturePush.dmg), drag to Applications, and launch.

The app is code-signed and notarized by Apple for Gatekeeper compatibility.

## Why CapturePush?

**vs ShareX** — ShareX is Windows-only. CapturePush brings the same core workflow (capture → annotate → upload to custom host) to macOS as a native app.

**vs CleanShot X** — CleanShot X costs $29+ and uses their cloud for hosting ($8/mo). CapturePush is free and uploads to your own infrastructure — no subscriptions, no vendor lock-in, full privacy.

**vs built-in macOS screenshots** — macOS screenshots save to Desktop with no upload workflow. CapturePush adds instant upload, annotation, GIF/MP4 recording, and scrolling capture.

## Upload Backends

| Backend | Use Case |
|---------|----------|
| **SSH/SCP** | Upload to any Linux server with SSH access |
| **S3-compatible** | AWS S3, Cloudflare R2, Backblaze B2, MinIO |
| **Local** | Save to a folder with optional Finder integration |

## How It Works

1. **Capture** — Trigger via menu bar or global hotkey. Select area, window, or full screen.
2. **Annotate** (optional) — Add arrows, text, highlights, or redact sensitive info.
3. **Push** — File uploads to your configured server automatically.
4. **Share** — URL is copied to clipboard instantly. Paste anywhere.

## Support

- File issues on this repository
- Email: support@capturepush.com

## License

CapturePush is free to use. Source code is not currently open source.
