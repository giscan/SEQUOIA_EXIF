# SEQUOIA_EXIF

Allow exiftool config file to write XMP tags from Parrot Sequoia Tif images.

1) Download config file present in this repository


2) Example : Remove Roll, Picth, Yaw

exiftool -config sequoia.config -XMP-Camera:Yaw= -XMP-Camera:Roll= -XMP-Camera:Pitch= IMG_XXX.TIF


3) Control tags : 

exiftool -g1 -s -a IMG_XXX.TIF
