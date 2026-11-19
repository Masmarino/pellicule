---
title: "Pellicule — Privacy Policy"
lang: en
permalink: /privacy/
---

# Pellicule Privacy Policy

*Last updated: November 13, 2026*

Pellicule is a video player for iPhone, iPad, Apple TV and Mac. It plays videos from **your own servers**: a Jellyfin server, network shares (SMB) and the files on your device.

## Summary

**Pellicule collects no data.** The developer receives nothing: no account, no usage statistics, no advertising identifier, no crash reports. The app contains no analytics, no ads and no third-party tracking services.

All data stays between the app, your device and the servers you choose to add.

## What Pellicule exchanges with your servers

- **Jellyfin server.** Pellicule connects with the address, username and password you enter. It reads your libraries and records what a Jellyfin player normally records: playback progress, watched items and favorites. This information is stored on your server, under your control.
- **Network shares (SMB).** Pellicule connects with the credentials you enter, only to list and play your files.
- **Online subtitles.** Subtitle search goes through your Jellyfin server, which queries the providers you have configured on it (OpenSubtitles, for example). Pellicule does not contact these providers directly.
- **Online trailers.** When you tap "Trailer" and the movie has none on your server, Pellicule opens the link provided by your metadata (usually YouTube) in your browser or the matching app. That site's privacy policy then applies.

## What Pellicule keeps on your device

- **Credentials.** Jellyfin sign-in tokens and SMB share passwords are kept in Apple's Keychain, encrypted by the system.
- **Settings and saved accounts.** They are kept in the app's preferences.
- **Downloads.** Videos downloaded for offline playback stay in the app's storage. They are removed with the app or from the Downloads tab.
- **System integration.**
  - Spotlight search, Siri shortcuts and the Resume widget use the titles and thumbnails of your recent videos.
  - On Apple TV, the Top Shelf does the same.
  - This information is prepared and stored on the device only.

## Local network

Pellicule asks for local network access to reach your Jellyfin server and SMB shares at home. This access is used only for those connections.

## Children

Pellicule is not specifically directed at children and collects no data, whatever the user's age.

## Your rights

Since the developer holds no data about you, there is nothing to access, correct or delete on their side. Playback data lives on your Jellyfin server, where you can manage it. To erase everything Pellicule keeps on a device, sign out of your accounts or delete the app.

## Contact

For any question about this policy: [florian.simon@skolln.com](mailto:florian.simon@skolln.com).

If this policy changes, the new version will be published at the same address, with its update date.
