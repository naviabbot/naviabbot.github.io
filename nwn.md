---
layout: page
title: How to Install Neverwinter Nights - Linux
permalink: /projects/nwnlinux/
---

# How to install Neverwinter Nights on Linux (GOG.com ver)

## Requirements
* A copy of NwN Diamond from GOG.com
* [This post made by GOG.com User vv221](https://www.gog.com/forum/neverwinter_nights_series/linux_install_neverwinter_nights_on_debianubuntumintsteamos/post12) *note: if you are not a debian user, the files on this post are helpful*
* __Optional__: [NwMovies](https://github.com/nwnlinux/nwmovies)
* __OPTIONAL__: A video editor that uses FFMPEG. My choice - [Shotcut](http://www.shotcut.org/)  
*7zip  
*Kingmaker Reinstaller

## Steps
1. First, download your copy of Neverwinter Nights.
2. Download the files and the shell script from the forum post.
3. Run the shell script and install the deb it gives you.
4. `sudo chown <user> /usr/local/share/games/neverwinter-nights` (Hereby refered to as `NWN/`)
5. Place your unique CD Key into your install.
6. `7z x /path/to/Kingmaker/Reinstaller` - Move into `NWN` directory
7. __Optional__: Download the NWMovies package and extract into `NWN`. Install Mplayer.
8. __Optional__: Re-encode your Bink videos into mpeg or ogg using your video editor of choice. Move into your `NWN/movies` directory. Uncomment BinkPlayer and PlayMPEG.
