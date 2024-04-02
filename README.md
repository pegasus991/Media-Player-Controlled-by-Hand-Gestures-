# Media-Player-Controlled-by-Hand-Gestures-
-	Developed a hand gesture recognition project with the help of Python and heavily involves the use of OpenCV. The main aim of this project is to remove the need of using keyboard to play/pause/forward etc. the video and instead use hand gestures to perform these actions.

# The steps to use this are as follows - 
- Import the necessary files from the "Importing the libraries section".
- Execute the main code.
- After Execution of the main code, you will see 4 dialogue boxes appearing with the names - Filtre, Result, Thresh and Color Adjustments.
- Now Adjust the hyperparameters until your hand is properly detected in the thresh section and contours are properly visible in the Result section.
- Now open a media player (preferably VLC medial player), not the default ones in the OS.
- Now you can perform different actions with the help of your hand gestures !
- Press "q" to end the process.

# A few things to keep in mind -
- First and foremost, your background should be completely clear of any obstruction and preferably of a light color (For eg: A white wall).
- Adjusting the hyperparameters in the Color Adjustments section takes time, choose the hyperparameters which are best suitable for you.
- Responses maybe a bit lagging, or a bit too quick sometimes, but overall the model works quite well.
- To exit the model, press the button "q", this step is necessary otherwise your hands will be mapped to the keyboard which will lead to a whole bunch of operations on your computer as soon as you start moving your hands.
