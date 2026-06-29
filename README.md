# AnyDown

<div align="center">
  <h3>The Ultimate Universal Media Downloader</h3>
  <p>A powerful, headless download engine paired with a seamless browser extension for 1-click video and playlist extraction.</p>
</div>

---

## 🚀 Overview

**AnyDown** is an ultra-fast, professional-grade media downloader. Unlike traditional clunky download managers, AnyDown splits its architecture into two distinct, highly optimized components:
1. **The Engine:** A lightweight, headless desktop application running silently in your system tray. It handles complex queueing, rate-limiting, merging, and hardware-accelerated processing.
2. **The Extension:** A sleek Chrome/Edge browser extension that automatically sniffs media streams, injects a floating download button onto your favorite sites, and sends tasks to the engine instantly.

## ✨ Key Features

- **One-Click Floating Button:** Instantly download content without leaving the page. A non-intrusive floating button appears directly on video players.
- **Massive Playlist & Course Extraction:** Full support for extracting massive YouTube playlists or premium Udemy / Teachable courses directly into neatly organized folders.
- **Premium Local Dashboard:** Manage your active queue, view your download history, and configure global settings from a beautiful, dark-themed local web dashboard (`localhost:6789`).
- **Private Content Support:** Securely pass `cookies.txt` to the engine to download private Instagram Reels, age-restricted YouTube videos, or paid course lectures.
- **Intelligent Engine Updates:** The backend engine automatically self-updates to bypass the latest bot-protection mechanisms from major platforms.
- **Any Quality, Any Format:** Select resolutions ranging from 144p to 4K, or extract audio directly to MP3.

## 🌍 Supported Platforms

AnyDown supports virtually any platform that streams media, including but not limited to:
- **YouTube** (Shorts, Videos, Playlists)
- **Instagram** (Reels, Posts)
- **TikTok** (Feed, Profiles)
- **LinkedIn** (Feed, Posts)
- **X / Twitter**
- **Udemy & Teachable** (Courses)
- **SoundCloud** (Tracks, Playlists)
- **Facebook** (Watch, Groups)

## 📥 Installation

### Step 1: Install the Desktop Engine
1. Go to the [Releases](#) page and download `AnyDownSetup.exe`.
2. Run the installer.
3. Once installed, AnyDown will silently run in your system tray and serve the local dashboard.

### Step 2: Install the Browser Extension
*Note: AnyDown is currently distributed as an unpacked extension while pending Web Store approval.*
1. Download the `AnyDown_Extension.zip` file from the [Releases](#) page and extract it to a folder.
2. Open Chrome or Edge and navigate to `chrome://extensions/`.
3. Enable **Developer mode** in the top right corner.
4. Click **Load unpacked** and select the extracted `AnyDown_Extension` folder.
5. Pin the extension to your toolbar!

## ⚙️ How to Use

1. **Browse:** Navigate to a supported platform (e.g., YouTube or Udemy).
2. **Click:** Click the floating AnyDown button injected into the page, or click the extension icon to choose specific resolutions and formats.
3. **Track:** Click the AnyDown system tray icon to open the **Dashboard** and track your download progress in real-time.

### Advanced: Downloading Private Content
To download content that requires a login (e.g., Udemy, Private Instagram accounts):
1. Open the AnyDown Dashboard from your system tray.
2. Go to **Global Settings**.
3. Under *Default Cookie Source*, select **Use Cookies (cookies.txt)**.
4. Paste your exported Netscape HTTP cookies into the secure input box.
5. AnyDown will now authenticate securely when downloading.

## ⚠️ Disclaimer

AnyDown is built for personal archiving and educational purposes only. Please respect the copyright and terms of service of the platforms you are downloading from. The developers are not responsible for any misuse of this software.
