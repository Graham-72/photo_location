# Photo Location Formatter

This module adds a formatter for an image field, enabling a display or
a view to output the latitude and longitude of a photo where this
information exists in an image file.

This is a contributed module developed for BackdropCMS.

## Usage

+ After installing this module, when managing the display of an image field,
  "Photo with location" can be selected instead of "Image" as the format.

+ Also, when adding an image field in a View, 'Photo with location' can be 
  chosen as the formatter instead of 'Image'.
  
+ Please note, this module relies on the existence of the GPS location 
  within the EXIF data within a JPEG image file. It is intended to be used
  with image files that contain this EXIF data though it provides for the
  display of derived versions of the image according to the style selection.

## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.

## Credits
+ Implementation inspired by the module image_url_formatter.
+ Includes a GPS coordinate calculation function from
https://stackoverflow.com/questions/2526304/php-extract-gps-exif-data/16437888#16437888

### Developer for BackdropCMS
+ Graham Oliver (github.com/Graham-72)
