hls-proxy
=========

A simple HLS-to-HTTP proxy, useful for those players without (full) HTTP Live Streaming support (i.e. mplayer).

hls-proxy is a frankenstein hack based on hls-client (http://code.google.com/p/hls-player/).


Usage:

- python proxy.py [--port PORT] (default: 8081)

- mplayer http://localhost:PORT/?url=http://YOUR_HLS_URL 


Requirements:

- python-twisted
