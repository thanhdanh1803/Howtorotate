
cabbage zoom - v1 2020-11-21 10:24am
==============================

This dataset was exported via roboflow.ai on November 21, 2020 at 3:24 AM GMT

It includes 152 images.
Cabbage are annotated in Tensorflow TFRecord (raccoon) format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 800x800 (Stretch)
* Auto-contrast via contrast stretching

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 26 percent of the image
* Random shear of between -22° to +22° horizontally and -17° to +17° vertically
* Random brigthness adjustment of between -18 and +18 percent


