## Notes

A version of Apache 2.4.4 with some fixes we've submitted.

The `vendor` branch is stock Apache source, with `master` containing our fixes.

These patches fix the following bugs:

  * [53910 -- If: check spuriously succeeds with %-encoded URL and ETag qualifier](https://issues.apache.org/bugzilla/show_bug.cgi?id=53910)
  * [53932 -- PROPFIND doesn't support If, If-Match ETag predicates](https://issues.apache.org/bugzilla/show_bug.cgi?id=53932)
  * [54610 -- COPY doesn't respect If/If-Modified/etc](https://issues.apache.org/bugzilla/show_bug.cgi?id=54610)
  * [54611 -- Location header for dav_created not URI encoded](https://issues.apache.org/bugzilla/show_bug.cgi?id=54611)
  
## Building

The top level contains a basic `build-httpd` script that configures, builds and installs Apache in `/usr/local/apache2`.

