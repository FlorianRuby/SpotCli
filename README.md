# SpotCli - Spotify Console Control 🎵

A powerful command-line interface (CLI) tool for controlling Spotify from your terminal, with integrated Last.fm support. Written in Rust for maximum performance and reliability.

## Features

- 🎵 Control Spotify playback (play, pause, skip, previous)
- 🔊 Volume control (including mute/unmute)
- 🔍 Search and play specific songs and playlists
- 🔀 Toggle shuffle mode
- 📊 View currently playing track with progress bar
- 📝 Queue management (view and add tracks)
- 📈 Last.fm integration
  - Scrobbling support
  - View detailed statistics
  - Track listening history
  - Display top artists, tracks, and albums

## Installation

### Windows

Currently working on an installer, however 
### Building from Source

1. Make sure you have Rust and Cargo installed
2. Clone the repository
3. Build the project:
```bash
cargo build --release
```

## Usage

### Basic Commands

```bash
spotcli                     # Show currently playing track
spotcli help               # Show help message
spotcli fetch              # Show Spotify and Last.fm stats in neofetch style
```

### Playback Control

```bash
spotcli play               # Resume playback
spotcli play [song name]   # Play a specific song
spotcli pause              # Pause playback
spotcli next/skip          # Skip to next track
spotcli prev               # Skip to previous track
spotcli shuffle           # Toggle shuffle mode on/off
```

### Volume Control

```bash
spotcli volume/vol [0-100] # Set volume (0-100)
spotcli mute              # Mute volume
spotcli unmute            # Unmute volume (restores previous volume)
```

### Queue Management

```bash
spotcli queue             # Show next 5 tracks in queue
spotcli add [track name]  # Add a track to queue
spotcli playlist [name]   # Play a playlist
```

### Last.fm Integration

```bash
spotcli lastfm login      # Set up Last.fm scrobbling
spotcli lastfm status     # Show Last.fm username
spotcli lastfm stats      # Show Last.fm statistics
spotcli lastfm logout     # Disable Last.fm scrobbling
```

## Configuration

The application stores its configuration files in the following location:
- Windows: `%APPDATA%\spotify-cli\`

Configuration files:
- `token.json`: Stores Spotify authentication tokens
- `lastfm.json`: Stores Last.fm credentials
- `volume_cache.json`: Stores volume state for mute/unmute functionality

## Dependencies

- Rust 2021 edition
- Required crates:
  - reqwest (with blocking and json features)
  - serde (with derive feature)
  - serde_json
  - base64
  - dirs
  - colored
  - tokio
  - webbrowser
  - rpassword
  - md5
  - chrono

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Florian Ruby

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- Spotify Web API
- Last.fm API 



# SpotCli
![image](https://github.com/user-attachments/assets/758e93f9-0c01-429f-84b4-b43b353db87a)

![image](https://github.com/user-attachments/assets/0510fa9a-117c-48b4-883e-a7367c3faf2a)

![image](https://github.com/user-attachments/assets/089ba02a-0094-40b6-b356-dc0898bbaf85)
![image](https://github.com/user-attachments/assets/7bb6d42e-a119-4945-8801-8ce798a51a79)

## Fetch
![image](https://github.com/user-attachments/assets/62e5b20c-c898-4944-b72b-607ffa383a9e)

![image](https://github.com/user-attachments/assets/8fe7dc9e-1664-43ba-b036-91a56810072c)


organise later 
