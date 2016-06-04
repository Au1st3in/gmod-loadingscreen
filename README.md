Garry's Mod Material Design Loading Screen (Updated)
==================

![](https://raw.githubusercontent.com/Au1st3in/gmod-loadingscreen-materialize/master/img/gmod-loadingscreen-materialize.png)
https://github.com/Au1st3in/gmod-loadingscreen-materialize<br>
Materialize themed PHP based loading screen for Garry's Mod with Steam Web API support.



Garry's Mod Loading Screen
==================

![](https://raw.githubusercontent.com/Au1st3in/gmod-loadingscreen/master/gmod-loadingscreen.jpg)
PHP based loading screen for Garry's Mod Server with Steam Web API support.

## Features

- Image Slideshow
- Autoplay Background Music
- Welcome Message with SteamID
- Displays Music Name
- Shows Current Map Name

**Additional**
- rules.php can be used to show rules after joining the server for the `motd`
- ULX is required to be installed (http://ulyssesmod.net/)


## Instructions

* Place 3 Music files in `.ogg` format in the music folder. Name them accoridingly `1.ogg`, `2.ogg` and `3.ogg`.
* Put the Music Titles on line 12-14 in `index.php`.
* Requires a Steam Web-API Key (http://steamcommunity.com/dev/apikey)
* Replace the `XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX` in `index.php` on line 24 with your Personal API Key.
* Set the URL of the loading screen in your `server.cfg` like that `sv_loadingurl "http://example.com/gmod-loadingscreen/?steamid=%s&mapname=%m"`

## Credits
* GabrielWanzek (https://github.com/GabrielWanzek/gmod-loadingscreen)
* Thomas Park (https://github.com/thomaspark/bootswatch/tree/gh-pages/cyborg)

## Documentation
* Bootstrap (http://getbootstrap.com)
* Steam Web-API (https://developer.valvesoftware.com/wiki/Steam_Web_API)

_Requires PHP_ &middot; _Styled with [Bootstrap](http://getbootstrap.com/) & [Cyborg Theme](http://bootswatch.com/cyborg/)_
