# mpdrome
A dirty MPD interface which connects to a navidrome server. Intended for use with ncmpcpp and mpc. Use at your own risk.

## Requirements
Python 3.14, and mpv for media playback.

## Setup
Modify the following constants at the start of the `mpdrome` file:
* `URL`, `USER` and `PASS`: address, username, and password for the remote Navidrome server
* `HOST` and `PORT`: address and port for the local MPD server
