Features & limitations
======================

* Only one Java file
* Java 1.1 compatible
* Released as open source, Modified BSD licence
* No fixed config files, logging, authorization etc. (Implement by yourself if you need them.)
* Supports parameter parsing of GET and POST methods
* Parameter names must be unique. (Adding support to multiple instance of a parameter is not difficult, but would make the interface a bit more cumbersome to use.)
* Supports both dynamic content and file serving
* Supports file upload (since version 1.2, 2010)
* Never caches anything
* Doesn't limit bandwidth, request time or simultaneous connections
* Default code serves files and shows all HTTP parameters and headers
* File server supports directory listing, index.html and index.htm
* File server does the 301 redirection trick for directories without /
* File server supports simple skipping for files (continue download)
* File server uses current directory as a web root
* File server serves also very long files without memory overhead
* Contains a built-in list of most common mime types
* All header names are converted lowercase so they don't vary between browsers/clients

Ways to use
===========

* Run as a standalone app (serves files from current directory and shows requests)
* Subclass serve() and embed to your own program (see HelloServer.java for a simple example)
* Call serveFile() from serve() with your own base directory
* To test file uploading, try browsing file-upload-test.htm through NanoHTTPD, upload something and watch the console output.