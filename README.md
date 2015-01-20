# led-controller

Program for controlling LED strips using the PixelPusher. It provides a framework for connecting with Atlassian Bamboo to display build status and for connecting to Keen.io to display event data.

See it in action here: https://www.youtube.com/watch?v=N1RMju-E5qU

Products Used:
http://www.heroicrobotics.com/products/pixelpusher
http://www.heroicrobotics.com/products/strip
https://www.atlassian.com/software/bamboo
https://keen.io/
https://segment.com/

You'll probably want to use the java-json package which can be found here http://www.java2s.com/Code/Jar/j/Downloadjavajsonjar.htm

The classes in src/common/ src/devices/ src/discovery/ and src/registry/ were written by the PixelPusher team. They can be found here: https://github.com/robot-head/PixelPusher-java
The classes in src/led_control_classes were writtin by David Cook at Jut. If you would like to modify the code to work in your environment, you probably only need to touch these classes.
