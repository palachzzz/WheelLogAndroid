# WheelLogAndroid V2.0.6

Updated Gradle configuration to compile with Gradle 4.4, still a few deprecated statements in there

Fixed the Gotway 84V indication issue, the preference change was not processed

Moved the MCM ratio fix for newer MCMs from MainActivity to preference-change processing

Inmotion V8 comms might still be broken, I have no wheel to try it

Revision (A): 
	Bug fixed: 
		- The 84V flag was not honored upon Wheellog restart
	
	New features:
		- When the app is in focus, pressing the volume up or down keys will trigger the native wheel beep (KingSong and Gotway)
		- Pressing the Select button on a connected Pebble watch will trigger the native wheel beep (KingSong and Gotway), if enabled in preferences
		  This feature might work with a Tizen watch as well, please provide feedback as I don't have access to one

Pebble app code

https://github.com/JumpMaster/WheelLogPebble

Samsung Gear app code

https://github.com/juliomap/WheelLog-Tizen
