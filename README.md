# Air_canvas
#Algorithm
Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
Prepare the canvas frame and put the respective ink buttons on it.
Adjust the values of teh mediapipe intilization to detect one hand only.
Detect teh landmarks by passing the RGB frame to the mediapipe hand detector
Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
Finally draw the points stored in array on the frames and canvas .
