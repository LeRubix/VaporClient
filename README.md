# Vapor Client

**Vapor Client** is a modern, cross-platform game client application for downloading, torrenting, and managing your game library. Inspired by popular game launchers, Vapor Client provides a steam-like, user-friendly interface to organize, launch, and keep track of your games, whether they are downloaded directly or via torrents.

## Features

- **Game Store & Library**: Browse a curated store of games, search and filter by categories, and add games to your personal library.
- **Game Management**: Download games directly or via torrent, track download status, and launch games from within the client.
- **Wishlist**: Add games to your wishlist for easy access and notifications.
- **Profile Management**: Customize your profile with a display name, avatar, bio, and location. View your last played games and activity.
- **Community Section**: (Planned) Connect with other users, share profiles, and view community activity.
- **Game Details**: View detailed information for each game, including description, categories, release date, developer, publisher, and system requirements.
- **Data Persistence**: All user data, including library, profile, and settings, are saved locally for privacy and offline access.
- **Cross-Platform**: Built with Electron and Node.js, runs on Windows, macOS, and Linux.

## Main Components

- **Electron App**: The main application is built using Electron, providing a desktop experience with web technologies.
- **UI**: The interface is defined in `index.html`, styled with `styles.css`, and powered by `scripts.js`.
- **Game Data**: Games are stored in a structured JSON file (`VaporClient/data/games.json`), including metadata and download/torrent links.
- **Profile & Settings**: User profile and settings are managed and persisted locally.
- **Python Game Manager**: A separate `game_manager_gui.py` tool allows advanced users to manage the games database with a GUI.
- **Game Add Tool**: The `gameAdd.py` script provides a CLI for adding new games to the database.

## How It Works

1. **Store & Library**: Browse the store, search for games, and add them to your library or wishlist.
2. **Download & Play**: Download games directly or via torrent. Launch installed games from your library.
3. **Profile**: Edit your profile, view your last played games, and export/import profile data.
4. **Game Management**: Use the Python GUI or CLI tools to add or edit games in the database.

## How To Use

1. Run the Installer
2. The program will automatically run once installed
3. The program can then be found on your desktop, the start menu, or C:\Users\USERNAME\AppData\Local\Programs\VaporClient