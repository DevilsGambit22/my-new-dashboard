# ACFA Network Dashboard v2.0 — New Era Upgrade

## Included upgrade

- New ACFA Lady Justice logo throughout the interface
- Four persistent visual themes: Dawn, Tribunal, Emerald, and Midnight
- Animated logo orbit, ambient aura, scan effects, panels, and theme transitions
- Enhanced ACFA Radio album animation and live sound-wave equalizer
- Multiple automatic playlists
- Automatic MP3 detection from GitHub
- Existing live members, matches, calendar, leaderboard, links, and victory system retained

## Add a song to the main radio

Upload an `.mp3` file directly to:

`assets/music/`

Commit it and refresh the deployed page. The radio scans the folder and adds the track automatically.

## Add a brand-new playlist

Create a folder inside:

`assets/music/playlists/`

Example:

`assets/music/playlists/Cinematic Battles/`

Place MP3 files inside that folder, commit, and refresh. The folder name automatically becomes a selectable playlist in ACFA Radio. No HTML editing is required.

## Important repository setting

The live scanner currently uses this public repository:

`devilsgambit22/acfa-network-dashboard`

If the repository name changes, update `RADIO_REPO` in `index.html`.

## Reserved audio

`assets/music/victory-fanfare.mp3` remains reserved for victory events and is excluded from every standard playlist.
