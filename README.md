# torrent-adder
This script will wait for newly added torrent files and start download with
those file to the folder where that file was found in.

# Requirements
This script is using transmission as the torrent program and inotifywait (from
inotify-tools package) to watch the folder.

Transmission daemon has already be running for the script.
