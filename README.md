mtg-proxy-printer
=================

This project is a fork of:

* [Shawn Sansom's Proxy Printer](https://github.com/ssansom/mtg-proxy-printer), which itself is a fork of...
* [mtg-proxy-printer found on Google code](https://code.google.com/archive/p/mtg-proxy-printer/source/default/source), with some modifications to work with the current magiccards.info site.

 Some slight reorganization and "fixes" have already occurred.

* Main proxy printer code was ALWAYS using the Settings_Default file
* Using the Scrython library instead of HTML Parsing to grab Card Images using the Scryfall API

Future Development
------------------

Planned additions include (Likely in the listed order):

* Ability to select Set from input line
* Ability to print lists from Txt, Csv, and Dec format (MTGO Imports)
* Better Error Logging (Print statements are Unuseful in the long term)
