# Air-canvas
Computer vision project implemented with OpenCV with Machine learning using the Mediapipe

#Algorithm
1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3. Adjust the values of teh mediapipe intilization to detect one hand only.
4. Detect teh landmarks by passing the RGB frame to the mediapipe hand detector
5. Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
6. Finally draw the points stored in array on the frames and canvas .
