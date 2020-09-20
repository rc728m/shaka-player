Shaka demo-player instructions

To install, clone the repo and ensure "shaka-player.compiled.js" is in the "shaka-player/dist" folder.
	If it is not, download the archive from the following link and unzip the files in shaka-player/dist:

	https://github.com/mirasoldavila13/Teamname-player/blob/jeff/dist.rar

In the shaka-player directory, open the player-demo.html.

To load a source into the playlist, enter a link into the "Video Link" field and click "Add"

To scroll through the playlist, click "Next" or "Previous"

To clear the playlist, click the "Clear Playlist" button.

To load a source upon opening in a browser, open player-demo.html in any text editor
	Go to line 36 and post any link and make sure it is enclosed in the single quotes ''
	Note: This source will not be added to the playlist function nor will it give you the startup time.
	         Since shaka-player preloads the video, it is impossible to track when exactly it starts loading the video you designate in "manifestUri".