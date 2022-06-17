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

## License

Unless otherwise specified, code samples in this repository are licensed under the APACHE 2.0 open source license.

Copyright 2022 EdgeImpulse, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.