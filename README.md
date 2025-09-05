<ul>
  <li>
    <a href="https://keyelty-dev.github.io/music-player/"> Online demo</a>
  </li>




# Music Streaming Web Application

A simple music streaming web application built using HTML, CSS, and JavaScript. This project allows users to browse trending songs and popular artists, play audio tracks, and interact with a basic media player interface.

## Features
- Display a list of trending songs with images, titles, and playable audio.
- Showcase popular artists with their images and names.
- Interactive music player with play/pause, next/previous track controls, and a progress bar.
- Volume control with mute/unmute functionality.
- Horizontal scrolling for song and artist sections with navigation arrows.
- Responsive design with a sidebar and header for navigation.

## Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- Local server environment (recommended, e.g., Live Server in VS Code) for proper file loading.

## Installation
1. Clone or download the repository to your local machine.
2. Ensure the project structure includes the following folders:
   - `img/` (for image files).
   - `musics/` (for audio files).
   - `src/` (for CSS files like `output.css`).
3. Open `index.html` in a web browser or use a local server to run the application.

## Usage
- Browse the "Trending songs" and "Popular artists" sections.
- Click on a song to play it; use the player controls at the bottom to manage playback.
- Use the left and right arrows to scroll through the song and artist lists.
- Adjust the volume or mute the audio using the slider on the player.

## File Structure
- `index.html`: Main HTML file containing the structure and embedded JavaScript.
- `src/output.css`: Custom CSS file for styling (ensure it’s linked correctly).
- `img/`: Directory for song and artist images.
- `musics/`: Directory for audio files.

## Troubleshooting
- **Images or audio not loading**: Check file paths in the code (e.g., use `./img/filename.jpg`) and ensure files are in the correct directories. Use browser developer tools (F12) to debug 404 errors.
- **Responsive issues**: Test on different screen sizes and adjust CSS as needed.
- **Playback issues**: Ensure audio files are in a supported format (e.g., `.mp3`) and the local server is running.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Suggestions for new features or bug fixes are welcome!

## License
This project is open-source and available under the MIT License.
