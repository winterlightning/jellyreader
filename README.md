jellyreader
===========

![app screenshot](http://jellyreader.com/app_screenshot.png)

RSS Reader or JellyReader is an app that stores all your articles on Google Drive and Dropbox! The data is completely self-hosted on your personal cloud, so it can never go down or go away.

##You can also clone this to run your own self-hosted version on github pages!

1. Fork this repository, the site should now be on a new gh-page
2. Dropbox works right away in your new site, however, Google Drive needs an app key with the new domain and redirect url set. You can either just update Google Drive, or both at https://github.com/NimbusBase/jellyreader/blob/gh-pages/js/multi.coffee

  For Dropbox, go to: https://www.dropbox.com/developers/apps

  For Google, go to: https://cloud.google.com/console/project and create your own id and add your current github page URL as to both the domain and the URL redirect settings.

  This NimbusBase tutorial tells you where to change things: http://nimbusbase.com/learn.html

3. Everything should now run!

<a href="http://nimbusbase.com/" target="_blank"><img src="http://jellyreader.com/badge.png" /></a>

*change to build*
