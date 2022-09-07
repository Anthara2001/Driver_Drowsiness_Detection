# Driver_Drowsiness_Detection
Driver drowsiness detection is a car safety technology which helps prevent accidents caused by the driver getting drowsy.
This system continuously assesses the driver's eyes and alerts him with alarms if the system detects that the driver closes his eyes very often.
A webcam is required for this project for the system to monitor the driver's eyes regularly.
This python project uses OpenCV, NumPy, Dlib, imutils python packages.

### Working
The project works with the 6 facial landmark detector and face detector of the Dlib library. The 68 facial landmark detector detects the points on the human face using which we determine whether the eyes are open or they are closed.

![Screenshot (20)](https://user-images.githubusercontent.com/112397401/188824078-b9d5a0cf-8a50-4604-a7df-5d557fc98848.png)

In the above screenshot the landmarks are detected using the detector.
Now we take the ratio of sum of distances of vertical landmarks to twice the distance between horizontal landmarks.
This ratio depends on the system which we may configure accordingly for the thresholds of active,drowsy,sleeping.

![Screenshot (23)](https://user-images.githubusercontent.com/112397401/188825655-88050275-d442-4e90-bdd1-165505bd6eb1.png)

![Screenshot (24)](https://user-images.githubusercontent.com/112397401/188825708-c08985d8-9a46-4d81-9750-0a54e2d725bd.png)

![Screenshot (22)](https://user-images.githubusercontent.com/112397401/188825734-d06c6e64-0191-4f63-90d0-7fa60d214aca.png)
