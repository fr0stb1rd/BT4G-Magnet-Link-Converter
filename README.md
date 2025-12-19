# BT4G Magnet Link Converter

A Userscript that automatically converts download links on **BT4G** websites (bt4gprx.com, bt4g.com, bt4g.org) into direct **Magnet links** and copies them to your clipboard with a single click.

## Features

*   **Magnet Conversion:** Automatically changes the default download links to `magnet:` URI schemes.
*   **One-Click Copy:** Clicking the link instantly copies the magnet link to your clipboard.
*   **Visual Feedback:** The link text temporarily changes to "Copied!" (or localized equivalent) to confirm the action.
*   **Tracker Enrichment:** Automatically appends a list of reliable, high-uptime UDP trackers to the magnet link for better connectivity and download speeds.
*   **Multilingual Support:** Metadata includes localized descriptions for multiple languages.

## Supported Sites

*   bt4gprx.com
*   bt4g.com
*   bt4g.org

## Installation

1.  I recommend using the violentmonkey extension. **Tampermonkey** or **Greasemonkey** also works.
    *   [Violentmonkey for Chrome/Edge/Firefox](https://violentmonkey.github.io/)
    *   [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    *   [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
2.  Install the script:
    *   **[Install from Greasy Fork](https://greasyfork.org/tr/scripts/559492-bt4g-magnet-link-converter)** (Recommended)
    *   [Install from GitHub](https://github.com/fr0stb1rd/BT4G-Magnet-Link-Converter/raw/refs/heads/main/bt4g_magnet.user.js)
3.  Confirm the installation in your userscript manager.

## Usage

1.  Visit any torrent page on one of the supported BT4G domains.
2.  Locate the **Download** or **Magnet Link** buttons.
3.  Click the button.
    *   The magnet link is copied to your clipboard.
    *   You will see a "Copied!" message on the button.
4.  Paste the link into your Torrent client (qBittorrent, Transmission, etc.).

## Included Trackers

The script automatically adds these trackers to every magnet link:

*   `udp://tracker.openbittorrent.com:80`
*   `udp://opentor.org:2710`
*   `udp://tracker.ccc.de:80`
*   `udp://tracker.blackunicorn.xyz:6969`
*   `udp://tracker.coppersurfer.tk:6969`
*   `udp://tracker.leechers-paradise.org:6969`
*   `udp://tracker.opentrackr.org:1337`

## License

[MIT License](LICENSE)
