# Music Player Web Application

A simple yet elegant music player built with HTML, CSS, and JavaScript.

## Features

- Play/pause functionality
- Next/previous track navigation
- Progress bar with scrubbing
- Album art display
- Error handling for missing files
- Responsive design

## Installation

1. Clone this repository
2. Ensure all media files are in the `media` folder
3. Open `index.html` in any modern browser

## File Structure

```
music-player/
├── index.html        # Main application file
├── style.css         # Styling
├── README.md         # This documentation
└── media/            # Contains all audio files and cover images
    ├── *.mp3         # Audio tracks
    └── *.jpg         # Album covers
```

## Usage

1. The player will automatically load the first song
2. Use the controls:
   - ▶️ Play/pause
   - ⏭ Next song
   - ⏮ Previous song
3. Drag the progress bar to seek through tracks

## Customization

To add more songs:
1. Add MP3 files to the `media` folder
2. Add JPG cover images (500x500 recommended)
3. Update the `songs` array in `index.html` with:
   ```javascript
   {
     title: "Song Title",
     artist: "Artist Name",
     audio: "./media/filename.mp3",
     cover: "./media/cover.jpg"
   }
   ```

## Troubleshooting

- If a song fails to load, check:
  - File exists in media folder
  - Filename matches exactly in code
  - Console for error messages
- Supported browsers: Chrome, Firefox, Edge, Safari

## License

Free for personal use.
