<img src="icon.svg" width="128" alt="Radio icon">

# Radio

Internet radio made for E Ink: black and white, no animations, no account.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/tintako)

## What it can do

**Stations**
- Browse stations by country, language and genre, or search by name
- Advanced search that combines several criteria
- Favorites with their own search; the station that plays is a black row
- Add your own stream link with the black +, typed in or scanned from a QR code (with a flashlight for dark rooms)
- Open a playlist link (.pls, .m3u) from your browser or files: Radio fills in the link, and you add it with ✓

Stations come from the public [Radio Browser](https://www.radio-browser.info) directory. It isn't ours and we don't update it. If a station is missing or its link doesn't work, add your own link with +.

**Listening**
- Keeps playing with the phone locked
- Sleep timer: 30, 60 or 90 minutes
- A play button in the car, on headphones or in a navigation app starts your favorites from the station you heard last
- Your favorites and own links stay available without internet

**Audio output**
- Choose the phone speaker, headphones or Bluetooth
- Send the radio to Sonos and DLNA speakers on your Wi-Fi; the speaker then plays it by itself. If a speaker can't play a station, the sound comes back to the phone

**Quiet by design:** no notifications and there won't be any, apart from Android's playback control while the radio plays. Radio was made on a personal request and has what it has for a reason.

**Languages:** English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Czech. Radio follows the phone's language.

## Permissions
- Internet: to find stations and play audio
- Network state: to tell "no internet" from "station directory not responding"
- Foreground service, media playback and wake lock: to keep audio playing with the screen off
- Notifications: only the playback controls (Android 13 and newer: offered once, the first time something plays)
- Camera: only to scan a QR code, while the scanner is open; no picture is saved. Asked once with a short reason; you can allow it later in Settings → Permissions

## Privacy
Radio collects no personal data and has no server of its own. The station list comes from the Radio Browser directory; audio comes straight from each station's own server. The app also connects to speakers on your local network while Audio output is open or a speaker is playing. Full text: [PRIVACY.md](PRIVACY.md) · Terms: [TERMS.md](TERMS.md) · Open-source licenses: [LICENSES.md](LICENSES.md)

Made by Tintako · app@tintako.com

## Install
Download the latest APK from [Releases](../../releases/latest) and install it on your device.
