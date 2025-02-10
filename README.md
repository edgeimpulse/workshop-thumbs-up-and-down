# Thumbs Up and Down Workshop

## Train Model on Edge Impulse

[Go here for the public project on Edge Impulse Studio](https://studio.edgeimpulse.com/public/112597/latest)

It needs more data! Add photos of the following classes:
 * Thumbs up
 * Thumbs down
 * Unknown (background, other hand gestures)

## Deploy

Go to Deploy tab in studio. Download the library for your embedded system.

### OpenMV

Copy *labels.txt* and *trained.tflite* files from the downloaded .zip file to the filesystem on the OpenMV Cam. Run *main.py* from this repo. It will read in the *labels.txt* and *trained.tflite* files to perform inference and print the labels to the viewer.
