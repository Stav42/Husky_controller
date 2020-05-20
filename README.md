# Husky_controller
Packages to send coordinates and navigate to that point


Unzip the feedcontrol package. Type source feedback/devel/setup.bash

Rosrun feedback points.py sends coordinates to topic '/nav'. It takes a list of coordinates

Rosrun feedback gotogoal.py sends the bot to the points. Set tolerance at around 0.4 to get good results.

Give gotogoal.py and points.py executable permission
