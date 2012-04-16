# Summary

`scan2web` is a Bash script that uses
[ImageMagick](http://www.imagemagick.org/) to convert full size image
files (assumed to have been output from a photo or film scanner in any
standard format) to web-sized JPEGs with "appropriate" levels adjustment
and sharpening. "Appropriate" is best defined as "a broadly acceptable
amount for minimal acceptability". The various parameters can be adjusted
via command line flags.

For example, assuming a full size scanned image file called crop0001.tif:

    $ ./scan2web crop0001.tif

...will produce a sharpened file with some automated contrast improvement
called `crop0001-web.jpg` that is 750px on the longest edge.

scan2web is not a substitute for proper post-processing in an image
editor; it is intended to quickly produce acceptable, "first cut" gallery
files for large batches of images (equivalent to digital proof prints for
online viewing).
