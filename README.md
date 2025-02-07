 
# Music Player

## Description
A simple HTML, CSS, and JavaScript-based music player.

## Features
- Play, pause, and skip through songs
- Display song title, artist, and album cover
- Progress bar to track the current song position

## Getting Started
### Prerequisites
- Web browser (e.g., Google Chrome, Mozilla Firefox, Safari)

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/music-player.git
   ```
2. Navigate to the project directory:
   ```
   cd music-player
   ```
3. Open the `index.html` file in your web browser.

## Configuration
1. Add your songs to the `songs` array in the `script.js` file:
   ```javascript
   const songs = [
     {
       title: 'Song 1',
       artist: 'Artist 1',
       src: 'song1.mp3',
       cover: 'album-cover1.jpg'
     },
     {
       title: 'Song 2',
       artist: 'Artist 2',
       src: 'song2.mp3',
       cover: 'album-cover2.jpg'
     },
     // Add more songs as needed
   ];
   ```
2. Make sure the `src` and `cover` properties in the `songs` array match the file names of your audio and album cover files, respectively.
3. Place your audio files (`.mp3`) and album cover images (`.jpg` or `.png`) in the project directory.

## Development
1. Make any desired changes to the HTML, CSS, or JavaScript files.
2. Test the changes in your web browser.
3. Commit and push your changes to the repository.

## Contributing
If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
