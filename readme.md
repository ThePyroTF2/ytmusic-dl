# ytmusic-dl

Download music from youtube music! (Or from youtube. I don't care)

Just run `ytmusic-dl [URL]` and it'll download a song, playlist, or album to `~/Music`. If you give it a playlist or album, it'll make a new folder to hold all the songs, and also put an `m3u` file with the correct information for media players.

You can change the target directory by editing `dir.txt`.

`ytmusic-dl` should be installed to `/usr/local/ytmusic-dl`.

## Usage

	Usage: ytmusic-dl -[h|v|V] --[version|help|verbose|very-verbose] [URL]

	Options:
	-h, --help: display this info
	--version: display the program version
	-v, --verbose: print progress to the console.
	-V, --very-verbose: run youtube-dl in verbose mode

## Dependencies

This script requires [`youtube-dl`](https://www.github.com/ytdl-org/youtube-dl). Also, if you're on mac, you'll need to install the better version of `getopt`. I just used the `gnu-getopt` Homebrew formula.
