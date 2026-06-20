# ytmusic-lrc-srt-maker 🎵

A Tampermonkey script for YouTube Music that lets you generate highly precise LRC and SRT files using a rhythm-game style hotkey. Say goodbye to tedious software switching and turn lyric syncing into a smooth, rhythmic experience!

## ✨ Key Features

* **⚡ Millisecond Precision**: Supports the `[mm:ss.xxx]` 3-digit millisecond standard, making your outputs perfectly compatible with major lyric databases like LRCLIB.
* **🎮 Rhythm-Game Feel**: Uses the `Insert` key as a trigger to precisely capture the underlying `<video>` timestamp without interfering with native playback controls.
* **👁️ Smart Interlude Handling**: Leave blank lines in your lyrics to mark interludes. The script intelligently skips these during SRT conversion, preventing lingering empty subtitles on screen.
* **🛡️ Rock-Solid Stability**: Bypasses YouTube Music's strict CSP (Trusted Types) by pre-mounting the DOM. Access the UI cleanly through the Tampermonkey extension menu without breaking the page layout.
* **📦 Dual Format Export**: Automatically fetches the current song title for one-click downloading of both `.lrc` and `.srt` files.

## 🛠️ Installation

1. Install the [Tampermonkey](https://www.tampermonkey.net/) extension for your browser.
2. Add the `ytmusic-lrc-srt-maker.user.js` script to Tampermonkey. *(Note: Link your script file or Greasy Fork page here)*
3. Open or refresh [YouTube Music](https://music.youtube.com/).
4. Click the Tampermonkey icon in your browser extension bar and select **"⚙️ 📝 開啟 / 關閉 LRC 產生器"** to toggle the panel.

## 📖 How to Use

1. **Prepare Lyrics**: Paste your plain text lyrics into the panel. Keep a blank line for long instrumental breaks.
2. **Start Syncing**: Click the "▶ 開始同步" (Start Sync) button, then click anywhere on the background page to remove focus from the text box.
3. **Hit the Beats**: Follow the music! Whenever the singer reaches the highlighted green line, strike the `Insert` key to log the exact timestamp.
4. **Export**: Once finished, switch between the LRC and SRT tabs to copy or download your perfectly synced files.

## 📝 License

This project is licensed under the [MIT License](LICENSE). Contributions, issues, and feature requests are welcome!

## 🙏 Acknowledgements
This script was co-created and refined through a collaborative brainstorming session with Google Gemini.
