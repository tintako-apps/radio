<img src="icon.svg" width="128" alt="Radio icon">

# Radio

Internet radio and podcasts, made for E Ink: black and white, no animations, no account.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/tintako)

## What it can do

**Radio**
- Search stations by name, or browse by country, genre and language
- Advanced search that combines several criteria
- Favorites with their own search; the station that plays is a black row, and each station shows its logo
- Add your own stream links, typed in or scanned from a QR code (with a flashlight button for dark rooms)
- Open a playlist link (.pls, .m3u) from your browser or files: Radio fills in the link, and you add it with ✓

**Podcasts**
- Follow any podcast by its RSS or Atom address
- Import and export your podcast list as an OPML file; an OPML file opened from your files shows a preview before importing
- Podcast links (itpc:, podcast:) open Radio with the address filled in
- Search your podcasts and their episodes
- See which episodes are new, in progress or played, and continue where you left off
- Read episode notes
- Skip back 15 seconds or forward 30 seconds

**Listening**
- Keeps playing with the phone locked
- Sleep timer for radio, podcasts or both
- A play button in the car, on headphones or in a navigation app starts your favorites from the station you heard last
- Your favorites and own links stay available without internet

**Audio output**
- Choose the phone speaker, headphones or Bluetooth
- Send the radio or a podcast to Sonos and DLNA speakers on your Wi-Fi; the speaker then plays it by itself. HLS stations are sent too; if a speaker can't play one, the sound comes back to the phone
- Optional sleep timer while a speaker plays

**Languages:** Croatian, English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Czech

## Permissions
- Internet: to find stations and play audio
- Network state: to tell "no internet" from "station directory not responding"
- Foreground service, media playback and wake lock: to keep audio playing with the screen off
- Notifications: playback controls (Android 13 and newer: offered once, the first time something plays)
- Camera: only to scan a QR code, while the scanner is open; no picture is saved. Asked once with a short reason; you can allow it later in Settings → General

## Privacy
Radio collects no personal data and has no server of its own. The station list comes from the Radio Browser directory; audio comes straight from each station's or podcast's own server. The app also connects to speakers on your local network while Audio output is open or a speaker is playing. Full text: [PRIVACY.md](PRIVACY.md) · Terms: [TERMS.md](TERMS.md) · Open-source licenses: [LICENSES.md](LICENSES.md)

Made by Tintako · app@tintako.com

## Install
Download the latest APK from [Releases](../../releases/latest) and install it on your device.
