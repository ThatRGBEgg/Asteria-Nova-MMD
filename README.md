Asteria Nova MMD

Asteria Nova MMD (Mobile Media Device) is a browser-based music player designed for mobile devices. It is the mobile extension of the Asteria Nova CMD (Central Media Device). The goal of the MMD is to provide a simple way to browse, manage, and play a personal music library from a mobile interface.

The application runs entirely in the browser and does not require a server. Users can upload a folder of audio files directly from their device, and the player will scan the files, read metadata, and build a local music library.

Asteria Nova MMD focuses on a clean mobile layout, smooth playback controls, and quick access to music without needing external services or accounts.

⸻

Features

Local music playback
The player loads music directly from a folder on the device. Files are not uploaded anywhere and remain local to the browser session.

Metadata reading
Track information such as title, artist, and album artwork is read using media tags embedded in the audio files.

Mobile-first interface
The layout is designed primarily for phones, with large touch controls and a simple navigation structure.

Library browser
Songs appear in a searchable list that allows users to quickly select and play tracks.

Playback controls
The player includes play, pause, next, previous, shuffle, and repeat functionality.

Audio scrubber
Users can move through a track using a timeline slider with current time and total duration indicators.

Volume control
A volume slider allows real-time adjustment of playback level.

Playback speed control
Users can change playback speed between 0.5x and 2.0x.

Theme customization
Accent colors can be changed through the settings menu.

Atmosphere blur
Background blur strength can be adjusted to change the visual appearance of the interface.

Up Next display
The player shows the next track that will play in the queue.

⸻

How It Works

The application uses standard web technologies:

HTML for the layout
TailwindCSS for styling
JavaScript for logic and audio control

The player uses the browser Audio API to handle playback and gain control. When a user uploads a folder, the application scans the files, filters for audio formats, and reads metadata using the jsmediatags library.

Each track is converted into a temporary local URL so it can be played directly in the browser without uploading the file.

All library data exists only during the current browser session.

⸻

How To Use
	1.	Open the application in a browser.
	2.	Tap the upload button in the top left corner.
	3.	Select a folder containing audio files.
	4.	The player will scan the folder and build the library.
	5.	Open the library menu to browse the loaded songs.
	6.	Tap any track to begin playback.
	7.	Use the playback controls at the bottom of the screen to control the music.

⸻

Controls

Upload button
Opens a folder selection dialog to load music.

Library button
Opens the song list.

Settings button
Opens playback and visual settings.

Play button
Starts or pauses the current track.

Next / Previous
Moves through the playlist.

Shuffle
Randomizes playback order.

Repeat
Cycles through repeat modes.

Scrubber
Moves to a different point in the track.

Volume slider
Adjusts playback volume.

Playback speed slider
Changes how fast the track plays.

Atmosphere blur slider
Adjusts background blur.

⸻

Notes

The player does not permanently store music files. Files are only available during the current browser session.

Closing or refreshing the page will clear the library and require the folder to be uploaded again.

The interface is optimized for mobile screens but can also run on desktop browsers.
