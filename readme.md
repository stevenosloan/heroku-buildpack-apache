Apache+PHP build pack
========================

This is a build pack bundling PHP and Apache for Heroku apps. It tests for the presence of an `index.html` or `index.php` file and then serves out of root with Apache.


Configuration
-------------

The config files are bundled with the build pack itself:

* conf/httpd.conf
* conf/php.ini


Hacking
-------

To change this buildpack, fork it on Github. Push up changes to your fork, then create a test app with --buildpack <your-github-url> and push to it.