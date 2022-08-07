# Drowsiness-detection
Machine Learning Project to detect drowsiness and Yawn.

Objective-- The objective of this project is to develop an accurate and reliable system to detect a person’s drowsiness based on his or her yawning
and eye blinking. This requires computing relevant measures to predict the onset of drowsiness. If it detects drowsiness, the system alerts the
person to take appropriate preventive action in order to avoid serious car crash. It identifies an object as a “face” from live camera and locates
it in the input image, add this to the classifier(HAAR CLassifer,in this case) to detect the face and regions of interest.
We used Shape predictor(dat file) to extract features around the mouth and eyes and plot landmarks. Then the eyes and mouth detected,
are fed to CNN classifier which will predict if eyes and/or mouth are open or closed. Calculate score for the time person's eyes are
closed and mouth is open. If eyes are closed for long time or mouth is open for more than a distance for a certain time then it mentions drowsiness.
The model determines a person is drowsy and beeps the alarm.
