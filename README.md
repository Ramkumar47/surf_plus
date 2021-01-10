# surf_plus
Extended surf browser configuration with custom shellfunctions for bookmarks, searchbar etc..

## Extentions implemented
major modifications are done on the surf/config.def.h file starting at
line number 94 and few keybindings defined starting at line number 211

things implemented are
* home page key, configured at F1 key and loads google.com
* custom shell functions to perform bookmark save, load and clear
* implementation of search bar. These are defined at file "surfFunctions"
* master control key Ctrl+m to open command bar.

## Installation instructions
the version of **surf** used for this configurationw was 2.0 and the extensions
are believed to work on higher versions as well.

* copy the surf/ folder to a place like Software/ directory
* place the surfFunctions shellscript inside the ~/.scripts/ folder
* open terminal in surf/ directory and type *sudo make clean install* to install the browser

dependenices are listed in the pkglist.txt file and will be installed during master installation itself.

## things to be configured
* History operations, like storing, loading and clearing.

this configuration was partially abandoned because of its resource heavy usage.
The browser is minimal but the webgtk engine it uses is quite heavy.

## links
* surf.suckless.org
