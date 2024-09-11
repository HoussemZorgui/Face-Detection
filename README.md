<<<<<<< HEAD
# Face_Detection_JavaScript
=======
<<<<<<< HEAD
# Face_Detection_JavaScript
=======
<<<<<<< HEAD
# Face_Detection_JavaScript
=======
# IMPORTANT: Bug Fixes

## `navigator.getUserMedia`

`navigator.getUserMedia` is now deprecated and is replaced by `navigator.mediaDevices.getUserMedia`. To fix this bug replace all versions of `navigator.getUserMedia` with `navigator.mediaDevices.getUserMedia`

## Low-end Devices Bug

The video eventListener for `play` fires up too early on low-end machines, before the video is fully loaded, which causes errors to pop up from the Face API and terminates the script (tested on Debian [Firefox] and Windows [Chrome, Firefox]). Replaced by `playing` event, which fires up when the media has enough data to start playing.
>>>>>>> 332fa6a (Initial commit)
>>>>>>> 9f81dfd (Resolve merge conflicts)
>>>>>>> 53f0ccf (Resolve merge conflicts)
