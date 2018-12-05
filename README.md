pod2mpd
------

# Requirements
[mpc](http://www.musicpd.org/clients/mpc/)
Any shell

#Useage
	
Simply run `pod2mpd <link to RSS feed>`, and this will add a link to all of the items in the RSS feed to the MPD playlist.

Arguements:

`-f` (`pod2mpd -f <filename>`) reads from a local file
`-i` (`pod2mpd -i <link to rss feed>`) inverts the playlist order
`-h` (`pod2mpd -h <MPD Host IP> <link to RSS feed>`) allows you to specify an IP or hostname to talk to a remote MPD server
