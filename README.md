<div align="center">

# 🎬 MovieBox — Stremio Addon

**Stream Movies, TV Shows, Asian Dramas, 4K UHD Remuxes & High-Speed BDIX Media directly in Stremio.**

[![Stremio Addon](https://img.shields.io/badge/Stremio-Install%20Addon-7B5BF2?style=for-the-badge&logo=stremio&logoColor=white)](stremio://140.245.124.105:7000/manifest.json)
[![Status](https://img.shields.io/badge/Status-Online%20%26%20Active-brightgreen?style=for-the-badge)](http://140.245.124.105:7000/manifest.json)
[![Quality](https://img.shields.io/badge/Streams-4K%20UHD%20%7C%201080p%20%7C%20HDR-orange?style=for-the-badge)]()
[![BDIX Supported](https://img.shields.io/badge/BDIX-High%20Speed%20FTP-blue?style=for-the-badge)]()
[![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-lightgrey?style=for-the-badge)](LICENSE-MIT)

<br/>

```text
http://140.245.124.105:7000/manifest.json
```

<p align="center">
  <a href="#-quick-install">🚀 Quick Install</a> •
  <a href="#-catalogs--providers">📦 Catalogs & Providers</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-device-compatibility">📱 Compatibility</a> •
  <a href="#-troubleshooting">🔧 Troubleshooting</a>
</p>

---

### 📸 Preview in Stremio

![MovieBox Stremio Catalogs](assets/stremio-preview.png)
*Catalogs from 4KHDHub, MovieBox, Dramachi, and CircleFTP (BDIX) seamlessly integrated into the Stremio Home & Discover view.*

</div>

---

## 🚀 Quick Install

### Method 1: 1-Click Install (Desktop & Mobile)

If you have Stremio installed, simply click the button below:

[![Install Addon in Stremio](https://img.shields.io/badge/Click%20Here%20To%20Install-stremio://140.245.124.105:7000/manifest.json-7B5BF2?style=for-the-badge&logo=stremio&logoColor=white)](stremio://140.245.124.105:7000/manifest.json)

> **Link:** [`stremio://140.245.124.105:7000/manifest.json`](stremio://140.245.124.105:7000/manifest.json)

---

### Method 2: Manual Installation (All Devices & Smart TVs)

Works on **Windows, macOS, Linux, Android, Android TV, Google TV, Fire TV Stick, and Stremio Web**:

1. Copy the manifest URL:
   ```http
   http://140.245.124.105:7000/manifest.json
   ```
2. Open **Stremio**.
3. Go to the **Addons** tab (the puzzle piece icon 🧩) or click into the top search bar (*"Search or paste link"*).
4. **Paste the URL** into the search bar and press `Enter` / click Search.
5. Click the green **Install** button when prompted.
6. Done! Navigate to your **Discover** or **Home** tab to browse catalogs and stream.

---

## 📦 Catalogs & Providers

The MovieBox addon aggregates top scrapers and direct high-speed CDN / FTP sources under a unified catalog interface:

| Provider | Type | Description | Best For |
| :--- | :--- | :--- | :--- |
| **4KHDHub** | `Movies & Series` | Ultra HD 4K Remux, Dolby Vision (DV), HDR10+, HEVC x265, Multi-Audio (Hindi, English Atmos 7.1/5.1). | Home theater enthusiasts & 4K streaming |
| **MovieBox** | `Movies & Series` | Massive library of Hollywood releases, trending box office, and popular TV series. | Everyday binge-watching & new releases |
| **Dramachi** | `Movies & Series` | Curated Korean Dramas (K-Drama), Chinese Dramas (C-Drama), Anime, and Japanese dramas. | Asian drama fans & anime lovers |
| **CircleFTP** | `BDIX FTP` | Direct ultra-high-speed ISP peering streams with zero buffering for Bangladesh & regional users. | Instant loading without international bandwidth limits |
| **DhakaFlix** | `BDIX FTP` | Bangladeshi & international entertainment hub served directly via BDIX nodes. | Local high-speed media access |

---

## ✨ Features

- **⚡ Native Stremio Integration:** Custom catalogs appear right on your Stremio Home and Discover feeds.
- **💎 4K UHD & HDR10 / Dolby Vision:** Direct access to pristine BluRay REMUX and encoded releases with multi-channel TrueHD Atmos and DTS-HD audio tracks.
- **🚀 High-Speed BDIX Nodes:** Dedicated BDIX server scrapers (CircleFTP, DhakaFlix) for buffer-free streaming across South Asian broadband networks.
- **🔍 Global Search:** Search for any title across all providers directly from the Stremio global search bar.
- **🎯 Multi-Resolution Stream Selection:** Choose between `4K 2160p`, `1080p FHD`, `720p HD`, and bandwidth-efficient `480p` streams.
- **🌐 Header & Token Forwarding:** Transparent request proxying and behavior hints ensure streams never drop due to referer checks or hotlinking restrictions.
- **🔒 Zero Telemetry:** Privacy-first design with no analytics, user tracking, or credential logging.

---

## 📱 Device Compatibility

| Platform | Supported | Notes |
| :--- | :---: | :--- |
| **Windows / macOS / Linux** | ✅ Yes | One-click or manual URL install. |
| **Android / Android TV / Google TV** | ✅ Yes | Supported natively in the Stremio app. |
| **Amazon Fire TV / FireStick** | ✅ Yes | Paste manifest via Stremio TV interface or sync via Stremio account. |
| **Stremio Web** | ✅ Yes | Available at [web.strem.io](https://web.stremio.com) (use Stremio Service or external player for non-browser codecs). |
| **iOS / iPadOS** | ✅ Yes | Accessible via Stremio Web with external player (VLC / Outplayer). |

> **Pro Tip:** If you log into your Stremio account, installing the addon once on your PC or phone will automatically sync it to your TV and other devices!

---

## 🔧 Troubleshooting & Tips

<details>
<summary><b>Playback Error or Codec Not Supported?</b></summary>

Some 4K UHD REMUX files use HEVC 10-bit or Dolby Vision profiles that may not be supported by your platform's default player:
1. In Stremio, go to **Settings** ⚙️ -> **Player**.
2. Set **Hardware-accelerated decoding** to **Enabled**.
3. If issues persist on Desktop or Android, enable **Play in external player** and select **VLC** or **mpv**.

</details>

<details>
<summary><b>CircleFTP / DhakaFlix streams not loading?</b></summary>

BDIX (Bangladesh Internet Exchange) servers require an ISP connection that participates in BDIX routing. If your network does not route through BDIX, select alternative stream links (such as **4KHDHub** or **MovieBox Cloud / FSL / HubCloud** mirrors) which work worldwide.

</details>

<details>
<summary><b>How to update or re-install the addon?</b></summary>

1. In Stremio, open **Addons** 🧩 -> **My Addons**.
2. Find **MovieBox Stremio** and click **Uninstall**.
3. Paste `http://140.245.124.105:7000/manifest.json` back into the search bar and click **Install**.

</details>

---

## 💻 Self-Hosting & Development

If you wish to host your own instance of the MovieBox Stremio addon server:

```bash
# Clone the repository
git clone https://github.com/mesamirh/MovieBox-Tui.git
cd MovieBox-Tui

# Build the release binary
cargo build --release

# Run the addon service (defaults to port 7000)
cargo run --release
```

### Environment Variables

| Variable | Default | Purpose |
| :--- | :--- | :--- |
| `MOVIEBOX_PORT` | `7000` | Port for the Stremio HTTP server |
| `MOVIEBOX_FOURKHDHUB_URL` | *Auto* | Custom mirror for 4KHDHub |
| `MOVIEBOX_LOG` | `info` | Logging verbosity (`off`, `error`, `warn`, `info`, `debug`) |

---

## ⚖️ Legal Disclaimer

This project and Stremio extension do not host, store, upload, or transmit any video or audio files. All scrapers and endpoints resolve publicly accessible links on the internet. End users are responsible for complying with copyright and content regulations in their respective jurisdictions.

---

<div align="center">

Made with ❤️ for the Stremio and MovieBox community.

</div>
</div>
