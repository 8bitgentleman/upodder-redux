(Idea and first version from Stan Vitkovsky. Forked from
https://code.google.com/p/upodder/ and then https://github.com/m3nu/upodder)

This is a work in progress

More than a simple podcast downloader for the command line
=========================

Upodder, in its original form, did exactly what it said it did.
It downloaded new podcast episodes from a simple list of RSS feeds.
It was quick and dirty but it got the job done.
This project is an attempt to expand on the original script.
Adding a more complete database, breaking it out into modules,
adding a human-readable directory system for saving each podcast, and (eventually) running it all through a docker container.


Since I'm re-imaginge most of this script it currently does not work and (I'm sure) has a multitude of bugs.
Please report any bugs on
`Github <https://github.com/8bitgentleman/upodder-redux>`__. I'll do my best to fix
them.

Installation
------------



Usage
-----

This is in flux

Motivation
----------------------

I've been a big user of `Plex <https://www.plex.tv/>` for years. Recently they added "support" for podcasts. What they actually added was the ability to stream podcasts but not download them on the server side. The defeats the whole archival purpose of Plex and doesn't prevent old episodes from disappearing. Ideally this scrip could be run from a cron job and refresh Plex when new episodes or podcasts are added.
