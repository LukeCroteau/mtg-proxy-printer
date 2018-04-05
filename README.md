mtg-proxy-printer
=================

This project is a fork of:

* [Shawn Sansom's Proxy Printer](https://github.com/ssansom/mtg-proxy-printer), which itself is a fork of...
* [mtg-proxy-printer found on Google code](https://code.google.com/archive/p/mtg-proxy-printer/source/default/source), with some modifications to work with the current magiccards.info site.

Some slight reorganization and "fixes" have already occurred.

* Main proxy printer code was ALWAYS using the Settings_Default file
* Fixed the regex using for Image download (MagicCards.Info has changed their HTML, as of a few years ago)

Future Development
------------------

Planned additions include (Likely in the listed order):

* Reorganization of code to use BeautifulSoup instead of hard regexing
* Incorporate usage of the [MTG JSON](http://www.mtgjson.com) project
* Ability to select Set from input line
* Downloading of images from Gatherer instead of MagicCards.info
* Ability to print lists from Txt, Csv, and Dec format (MTGO Imports)
* Better Error Logging (Print statements are Unuseful in the long term)

There's also a likely chance of moving development to Python 3, as Python 2 is going into Maintenance only mode soon.