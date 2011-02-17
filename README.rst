====
EzGz
====

EzGz is an incredibly simple `WordPress <http://wordpress.org>`_ plugin that
enables gzip compression on your WordPress-generated pages via PHP's
output-buffering mechanism.

EzGz will only apply to content generated from WordPress, like HTML, and not to
static files served by the web server, like CSS and JavaScript. Most web
servers can be configured to gzip that content easily enough.

EzGz does not buffer or compress admin pages to avoid interfering with, for
example, WordPress's automatic update script.
