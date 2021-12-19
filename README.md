# penguin_detection
Running inference at the zoo.

* Google computer vision if you have no idea what these boxes mean.

* Doesn't work in real time...yet. I have architecture in mind that might work. EDIT. Works in real time now. Needs more training and framerate optimization.
* UPDATE!!! I was able to make it alot faster and have I have a idea to get it even more faster. Achieved 7fps while running detections in real time.

* Seems to have trouble staying confident in ROIs that are far away from the viewing point. => Need to gather more data or try out a different algorithm or reconfigure training pipeline.

* Continue training from saved model latest checkpoint where last training finished.

![Test Image 2](https://github.com/al-lu/penguin_detection/blob/main/demo_3.gif)
![Test Image 2](https://github.com/al-lu/penguin_detection/blob/main/demo_2.gif)
![Test Image 3](https://github.com/al-lu/penguin_detection/blob/main/demo_1.gif)
![Test Image 4](https://github.com/al-lu/penguin_detection/blob/main/0000003000.jpg)
