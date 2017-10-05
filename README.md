## Stereo Camera Calibration

This application is a modified version of the MultiCameraEx sample app given by the flycapture SDK.

Instead of printing the timestamps of the capture, the application saves the image to a file. Saving of the images is queued until all camera's, in my use case of binocular vision, 2, so that the lag between captures is minimized.

#### How to run

Just perform

`make clean && make all`

This will build and make the executable

Now run 

`./MultiCameraEx`

This will start the application, print out the camera meta information and start capturing. The images will be saved to the data folder. To change any of the parameters, just modify the constants at the top of the file
