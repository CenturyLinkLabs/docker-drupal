Drupal
=====================

[![](https://badge.imagelayers.io/centurylink/drupal.svg)](https://imagelayers.io/?images=centurylink/drupal:latest 'Get your own badge on imagelayers.io')

Drupal docker image without a DB included in the image. This image is designed to be used with centurylink/mysql or similar stand-alone DB image in order to create a multi-container cluster.

On docker run, browse to Port 80 on the container to complete initial setup.
Example usage:

`$ docker run --rm --name DRUPAL --link DB:DB centurylink/drupal:7.38`

...where `DB:DB` matches the name and alias of your DB instance. Use the values from your linked DB image to complete GUI setup.

From [CenturyLink Labs](http://www.centurylinklabs.com)
