The calibration function of the camera and the function of correcting the distortion caused by using convex lenses were implemented.
__CALIBRATION__
!["Calibration"](https://github.com/wingun322/chessboard-camera-calibration/blob/main/calibration.JPG)
calibration
## Camera Calibration Results
* The number of selected images = 32
* RMS error = 0.41714337241308863
* Camera matrix (K) = 
[[607.16011727   0.         379.132154  ]
 [  0.         607.90544323 639.39593463]
 [  0.           0.           1.        ]]
* Distortion coefficient (k1, k2, p1, p2, k3, ...) = [ 0.03823143 -0.07851611  0.00179163  0.0093133   0.02999782]
__DISTRORTION CORRECTION__
!["Original1"]( https://github.com/wingun322/chessboard-camera-calibration/blob/main/distortion_correction1.JPG)
!["Distrotion_Correction1"](https://github.com/wingun322/chessboard-camera-calibration/blob/main/distortion_correction2.JPG)
bad example
!["Original2"]( https://github.com/wingun322/chessboard-camera-calibration/blob/main/distortion_correction3.JPG)
!["Distrotion_Correction2"]( https://github.com/wingun322/chessboard-camera-calibration/blob/main/distortion_correction4.JPG)
good example

In the case of images that do not require correction, it comes out even stranger.