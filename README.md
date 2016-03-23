# FXTest
 
## Requirements just to run
 - Java 1.8

## Requirements to build and deploy
 - Java 1.8 runtime
 - eclipse(fx) plugin, available from the eclipse marketplace
 - JavaFX scene build
 - [JavaFX Material Design component library](https://github.com/jfoenixadmin/JFoenix)
 
 
## How to build
clicking run in eclispe should work.

## How to deploy
 - Open the build.fxbuild
 - Go to the bottom and check "exe" for windows, or "deb" for linux. Not sure about mac...
 - On the top right click "Generate ant build.xml only"
 - You should see a build directory created with build.xml in it
 - In eclipse, right click and do "run as" > "and build" (the first one)
