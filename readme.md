# ITP Images Downloader

Ruby script to parse a CSV of student directory information and download images. You will need a csv of the data, get this from a resident.

## Usage:

    $ ruby save_images.rb PATH_TO_CSV

### Options:

- `-y XXXX` : Specify a year
- `-w XXXX` : Integer value for width of images, defaults to 200
- `-h XXXX` : Integer value for height of images, defaults to 300