# Pornslash Downloader (Browser Extension)

> Save PornSlash videos from your browser with detected MP4/HLS options, a player button, and 3 free trial downloads.

Pornslash Downloader gives viewers a browser-native way to detect and save media from supported PornSlash watch pages without switching to a separate downloader site. Open a PornSlash video page, start playback if the stream needs to load, then use the download button near the player, the extension popup, or the right-click menu. The extension checks the active page for playable media signals such as video/source tags, Open Graph video metadata, observed media resources, and static media URLs found in page scripts.

- Purpose-built URL matching for pornslash.com and www.pornslash.com
- In-player download button configured for the shared player wrapper
- Detects video/source tags, metadata streams, performance resources, and static media URLs
- Handles direct MP4 and HLS candidates through the shared offscreen pipeline
- Right-click menu labeled "Download PornSlash Video"
- Download manager with visible in-page progress
- Saves to a PornSlash download folder
- GitHub release update checks for the extension repository
- OTP activation through the SERP auth service
- 3 free trial downloads before the licensing flow

## Links

- :rocket: Get it here: [Pornslash Downloader](https://serp.ly/pornslash-downloader)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/pornslash-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/pornslash-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/pornslash-downloader/issues)

## Preview

![Pornslash Downloader workflow preview](https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/source-repo-readmes/pornslash-downloader/assets/workflow-preview.png)

## Table of Contents

- [Why Pornslash Downloader](#why-pornslash-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download Videos from Pornslash](#step-by-step-tutorial-how-to-download-videos-from-pornslash)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [Notes](#notes)
- [License](#license)
- [About Pornslash](#about-pornslash)

## Why Pornslash Downloader

PornSlash watch pages are built around an embedded player experience where the final video URL is not always visible through normal browser save controls. Generic web downloaders can misread page assets, previews, or ad media as the actual video, leaving you with unusable files or extra steps.

Pornslash Downloader adds PornSlash-specific page matching, an in-player download control, direct media and HLS candidate detection, an organized download folder, and the shared SERP offscreen download pipeline. Instead of copying URLs to external downloader sites, you stay on the page you are already viewing and use extension controls that understand the PornSlash context.

## Features

- Purpose-built URL matching for pornslash.com and www.pornslash.com
- In-player download button configured for the shared player wrapper
- Detects video/source tags, metadata streams, performance resources, and static media URLs
- Handles direct MP4 and HLS candidates through the shared offscreen pipeline
- Right-click menu labeled "Download PornSlash Video"
- Download manager with visible in-page progress
- Saves to a PornSlash download folder
- GitHub release update checks for the extension repository
- OTP activation through the SERP auth service
- 3 free trial downloads before the licensing flow
- Quality labels from detected media metadata or URL hints where available
- Popup controls for scanning and downloading detected media

## How It Works

1. Install the extension from the latest release.
2. Open Pornslash and go to a supported video page.
3. Start playback so the extension can detect the media.
4. Open the popup or use the on-page controls.
5. Choose the quality option you want.
6. Start the download and wait for the MP4 export to finish.
7. Save the final file locally.

## Step-by-Step Tutorial: How to Download Videos from Pornslash

1. Install the Pornslash Downloader extension from the latest GitHub release.
2. Activate the extension using your email and the one-time password sent to your inbox.
3. Navigate to any supported PornSlash watch page in your browser.
4. Press the play button on the video player so the page exposes the stream URLs.
5. Look for the download button that appears near the player, or open the extension popup.
6. Click the download button or popup icon to scan the page for available media candidates.
7. Choose the MP4 or HLS option you want from the list of detected formats.
8. Wait for the download to complete and save the file from your browser.

## Supported Formats

- Input: Direct MP4 URLs and HLS/M3U8-style media candidates when the page exposes them
- Output: MP4

Saved files use MP4 so they are easier to replay on standard media players, move between devices, or archive locally.

## Who It's For

- PornSlash viewers who want a straightforward browser workflow for offline personal viewing
- Users who prefer browser extensions over copy-paste downloader sites
- People who need a player-level download button instead of searching network logs
- Anyone testing or evaluating generated extension candidates before public release

## Common Use Cases

- Save a PornSlash watch-page video for offline viewing
- Check whether the active page exposes direct MP4 or HLS media candidates
- Use a player-level download button instead of searching network logs
- Trigger detection from the extension popup or right-click menu
- Document release-readiness gaps for a generated PornSlash candidate

## Troubleshooting

**No video candidates appear after clicking the button**
Press play on the video player first, as some pages only reveal stream URLs during playback. Refresh the page and try again.

**The extension says no media detected**
The page may use a video delivery pattern outside the generic adapter. Try a different PornSlash watch page to confirm the issue.

**Downloads fail or produce broken files**
Make sure you have a stable internet connection. The offscreen pipeline needs continuous access to stream segments during processing.

**The player download button does not appear**
The page may not have loaded the player wrapper yet. Wait for the full page to render and try refreshing if the button stays hidden.

**The extension asks for activation every time**
Your OTP session may have expired. Sign in again using your email to receive a new one-time password.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/pornslash-downloader](https://serp.ly/pornslash-downloader)

## Installation Instructions

1. Open the latest release page: [GitHub Releases](https://github.com/serpapps/pornslash-downloader/releases/latest)
2. Download the correct build for your browser.
3. Install the extension.
4. Open a supported Pornslash page.
5. Use the popup to detect and download the media.

## FAQ

**How do I download a PornSlash video?**
Open a PornSlash watch page, press play if needed, then use the player download button, extension popup, or right-click menu to scan for available media options.

**Does this work on every PornSlash page?**
Not guaranteed. The current build uses a generic static-media extraction approach, so each important PornSlash page type should be tested before relying on it.

**What file types can it detect?**
The extension is designed to normalize direct MP4 URLs and HLS/M3U8-style media candidates when the page exposes them.

**Why might no video appear?**
The player may not have loaded the stream yet, the page may use a pattern outside the generic adapter, or the detected URL may be filtered as non-content media.

**Where do downloads go?**
The offscreen configuration organizes saved files under a PornSlash download folder in your browser.

**Does it send videos to a remote server?**
No remote media downloader is involved. Auth and update checks call SERP and GitHub services, while media handling happens through browser and offscreen processing.

## Notes

- Only download content you own or have explicit permission to save
- An internet connection is required for downloads
- Press play first if detection is empty on a PornSlash watch page
- The current PornSlash adapter is generated and should be tested against real playback before store submission

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## About Pornslash

PornSlash is a video platform that hosts adult content organized by categories and tags. Pornslash Downloader helps viewers save videos from watch pages without leaving the browser or relying on external downloader sites.
