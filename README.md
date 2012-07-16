ktools
======

Some custom tools developed in sh/bash:

 * **lib**: Supporting libraries
  * **ktools**: Helper shell functions
 * **general**: General purpose tools
  * **kgrep**: Small wrapper for grep to search recursively in php files (by default)
  * **mp3**: Copy a random subset of your mp3 library to another folder (mp3 player usually)
 * **photo**: Scripts to deal with pictures and/or geotagging
   * **miniaturas**: Create thumbnails of your large images
   * **nef2jpg**: Small wrapper around `dcraw` to convert Nikon Raw Format (NEF) to JPG
   * **gpsPhoto.pl**: Original tool from http://www.carto.net/projects/photoTools/gpsPhoto/ to deal with GPS coordinates in pictures
   * **geotagdir**: Wrapper around `gpsPhoto.pl` to geotag entire folders easily
   * **borrar_datos_gps**: Remove all GPS data from pictures
   * **gmaps**: Open a geotagged picture in googlemaps
