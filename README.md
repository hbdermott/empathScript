# empathScript

This script is inteded to automate the Activity frontend creation process in Android Studio.
It is specifically for the Empath text based game and does not work as a general purpose
automation tool.

Use:

./textScript -s name

The -s option indicates whether the activity needs to be scrollable or not. The name is the name
of the activity. After running 2 new files will be created with the format activity_name.xml and
name.java. Additionally, the files strings.xml and AndroidManifest.xml will be updated appropriately.
