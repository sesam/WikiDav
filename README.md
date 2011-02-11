WikiDav
=======

WikiDav is a minimalistic wiki based on WebDAV, incron and markdown.

* [incron](http://incron.aiken.cz/), a linux cron for file events
* [markdown](http://xbeta.org/wiki/show/Markdown), friendlier than wikipedia's codes
* [WebDAV](http://en.wikipedia.org/wiki/WebDAV), edit your files from any modern operating system

This project is in use at <http://wiki.zash.se/>

## Installation
1. apt-get install markdown incron lighttpd
2. set up lighttpd using etc/lighttpd-webdav.conf (or roll your own for any other webserver)
2. set up incron using etc/incrontab [learn moar](http://www.pablumfication.co.uk/2010/09/23/incron-file-system-event-monitoring/)
3. profit?
