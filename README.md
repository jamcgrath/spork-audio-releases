# Spork Audio — Releases

Public download & release channel for **[Spork Audio](https://sporkaudio.com)** — a
macOS app for browsing, auditioning, and tempo-fitting audio samples (drum breaks,
one-shots, loops).

The application source lives in a separate, private repository. **This repo hosts only the
packaged desktop builds**, published as [GitHub Releases](../../releases).

## Download

Get the latest macOS build (`.dmg`) from the [**Releases**](../../releases/latest) page,
or from **[sporkaudio.com/download](https://sporkaudio.com/download)**.

Builds are signed and notarized by Apple, so macOS opens them without a Gatekeeper warning.

## Auto-update

Desktop builds check this repo for updates. Each release publishes an update feed
(`latest.json`) alongside the `.dmg`, which the in-app [Tauri](https://tauri.app) updater
reads to offer new versions.

## License

Spork Audio is distributed under the MIT License.
