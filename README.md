# artificial-intelligence

# ImageMagick commands 

Installing on Ubuntu

`sudo apt-get install imagemagick`

# ImageMagick utils

Quick overview of image properties in folder example

`identify *.jpg`

Get the colorspace of all jpegs in a folder

`identify -format %[colorspace] *.jpg`

Get the colorspace of all jpegs in a folder with newlines

`identify -format "%[colorspace]\n" *.jpg`

# GPU Services
Paperspace, can be used normally or with their job runner service called gradient. 
