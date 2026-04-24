# Music Player

A Flutter-based audio player with background playback support and queue management, built for Android and cross-platform.

## Features

- **Audio Playback:** Play local audio files from your device storage
- **Background Playback:** Keeps playing when the app is minimized, with a media notification in the notification bar including playback controls
- **Queue Management:** Add multiple songs and build a playlist queue
- **Playback Controls:** Play, pause, skip to next, go to previous and seek through tracks
- **Progress Bar:** Visual seek bar with current position and total duration display
- **Metadata Extraction:** Automatically reads track title and artist from file metadata or filename
- **Responsive Layout:** Adapts to both portrait and landscape orientations — landscape shows playlist and controls side by side

## Screenshots

<img src="screenshots/screenshot1.png" width="800"/>
<img src="screenshots/screenshot2.png" width="800"/>

## Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **Audio Engine:** just_audio
- **Background Service:** audio_service
- **Session Management:** audio_session
- **File Picker:** file_picker
