# Swervebot Driver Station setup and run.

1. #### Check with others that the current code deployed and running on the bot is working and functional code. The items needed are:
	1. SwerveDrive bot (with a full battery)
	2. Driver Station laptop
	3. Xbox Controller
	
2. #### Boot up the laptop, connect the controller and launch the Driver Station.
	1. Open the laptop, sign-in and wait until you see the desktop. It is highly recommended to have the laptop plugged into the wall.
	2. Connect the controller with a USB micro B. This connector looks like the charger that older Android phones used. The Xbox logo should be solid white.
	3. Launch the "FRC Driver Station" app (likely located on the desktop). If a UAC prompt pops up, press "Yes" and in a few moments the whole screen should be occupied by the app (which runs as two interconnected windows).
	
3. #### Boot up robot and connect to it
	1. Find a fully charged battery (above 100%), strap it in and plug it in. (Double check that the robot's breaker is broken and the power is cut.)
	2. Switch the breaker on and verify the big amber light is solid and that each Spark Max has a blinking magenta light for around 10-20 seconds before blinking cyan. Check RoboRIO for any red lights.
	3. Connect to the robot's WIFI. (This can take a few minutes).
	
4. #### Running the bot
	1. Check on the bottom panel of the Driver Station for three green bars (Comms, Robot code and Joystick).
	2. Set mode into TeleOperated mode
	3. Enabled the robot. **If the robot goes nuts, press the DISABLE button or the Enter key on your keyboard**
	
5. #### How to drive SwerveDrive with an Xbox controller
	With the default settings:
	| Controller  |   Action    |
	| ----------- | ----------- |
	| Left stick: Up & Down     | Moves the robot forwards and backwards  |
	| Left stick: Left & Right  | Moves the robot left and right *(not rotation)*  |
	| Right stick: Left & Right | Left rotates the robot CCW and right CW *(not pan)* |
	| View button (Two window button) | Resets the gyro or in other words sets the new forward |

	Note that this robot is field oriented so it can identify what is forward and backward from its original orientation. (If you were to rotate the robot, it still will continue straight from your perspective). Pressing the view button will define a new forward. (The amber light is the front). 
