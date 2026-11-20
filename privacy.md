---
title: "Pellicule — Privacy Policy"
lang: en
permalink: /privacy/
---

# Pellicule Privacy Policy

*Last updated: November 20, 2026*

Pellicule is a video player for iPhone, iPad, Apple TV and Mac. It plays videos from **your own servers**: a Jellyfin server, network shares (SMB) and the files on your device.

## Summary

**Pellicule collects no data.** The developer receives nothing: no account, no usage statistics, no advertising identifier, no crash reports. The app contains no analytics, no ads and no third-party tracking services.

All data stays between the app, your device, the servers you choose to add and, if you turn on Pellicule+ sync, your own iCloud account.

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

## Pellicule+: purchases and iCloud sync

- **Purchases.** The Pellicule+ subscription and lifetime purchase are processed by Apple (App Store). The developer receives neither your name, nor your email address, nor your payment details. The app only checks with the App Store, on the device, that a purchase is valid.
- **iCloud sync (optional).** With Pellicule+, and as long as the option is on in Settings, Pellicule syncs between your devices:
  - your Jellyfin accounts (server address, username and sign-in token, **no password**; the token lets a new device sign in without typing anything);
  - your network shares (name, address, user and password);
  - your playback settings;
  - the playback position and watched state of files from network shares and the device.
- **Where this data goes.** Into the app's iCloud key-value storage, private to your iCloud account and encrypted by Apple. Only you and your devices can access them: the developer can neither read nor receive them. Apple's privacy policy applies to iCloud.
- **Erasing.** Settings › Pellicule+ › "Erase iCloud Data" removes everything Pellicule stored in iCloud. You can also do it from your device's iCloud settings.
- **Local network.** To tell whether your Jellyfin server is on your local network (remote access is part of Pellicule+), the app looks, on the device, at the address it reaches and the connection type. Nothing is sent.

## Local network

Pellicule asks for local network access to reach your Jellyfin server and SMB shares at home. This access is used only for those connections.

## Children

Pellicule is not specifically directed at children and collects no data, whatever the user's age.

## Your rights

Since the developer holds no data about you, there is nothing to access, correct or delete on their side. Playback data lives on your Jellyfin server, where you can manage it, and sync data in your iCloud account. To erase everything Pellicule keeps on a device, sign out of your accounts or delete the app.

## Contact

For any question about this policy: [florian.simon@skolln.com](mailto:florian.simon@skolln.com).

If this policy changes, the new version will be published at the same address, with its update date.
