![GitHub last commit](https://img.shields.io/github/last-commit/UFTHaq/Motion-Capture-Leg-Limp?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/UFTHaq/Motion-Capture-Leg-Limp?label=Python&logo=python&logoColor=white&style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/UFTHaq/Motion-Capture-Leg-Limp?logo=Jupyter&style=for-the-badge)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/UFTHaq/Motion-Capture-Leg-Limp?style=for-the-badge)

# Motion Capture - Leg Limp
Limp Detection in Leg using OpenCV and MediaPipe with Motion Capture

This project combines the power of OpenCV and MediaPipe with advanced motion capture techniques to create a robust system for real-time limp detection in the leg. By integrating motion capture capabilities, the application achieves enhanced precision in identifying and analyzing irregularities in leg movement.

If you consider this page is useful, please leave a star

## MediaPipe - Pose Landmark

<p align="center">
  <img src="https://mediapipe.dev/images/mobile/pose_tracking_full_body_landmarks.png" height="350" />
</p>

## I. You need the videos

https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/84dbb9bd-0af4-40f3-8cc3-2725bbdb9dd0

https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/bca10186-cbb4-4c3b-89bd-026db75f3112

## II. Then, you capture the motion
Here is the visualize graphic about the leg range of motion data captured from the video
|Normal (right-left) leg|Limp (right-left) leg|
|:-:|:-:|
|<img src="https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/395454cc-2f82-4143-bcc0-85e555e5a060" width="500" />|<img src="https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/9c1095c9-33d8-4b1a-8277-15fec37e1f05" width="500" /> |

|Normal (right) leg & Limp (right) leg|Normal (left) leg & Limp (left) leg|
|:-:|:-:|
|<img src="https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/1e92fe98-5970-4a84-91b9-1f6e1deb3e30" width="500" />|<img src="https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/5f368834-bf8c-4103-9c81-a8fad3124fd6" width="500" /> |

## III. Take Conclusion
<p align="center">
  <img src="https://github.com/UFTHaq/Motion-Capture-Leg-Limp/assets/104829519/9c1095c9-33d8-4b1a-8277-15fec37e1f05" width="800" />
</p>
In image Limp (right-left) leg, it can be observed that there is a significant difference in the range of motion between the left and right legs. From this, it can be assumed that there is a limp in the left leg. The range of motion angle in the left leg (red line) tends to be smaller than the range of motion angle in the right leg because, in the limping left leg, the joint tends to lock the angle to alleviate pain caused by excessive leg movement. The larger the range of motion angle, the more pronounced the perceived pain.

<hr>
</hr>
<p align="center">
  If you consider this page is useful, please leave a star
</p>
