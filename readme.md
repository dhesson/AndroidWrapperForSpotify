# Java Interface
Use Gradle to build the JAR for Android.  I might update the build to where you can just use the jar task.

    gradle clean cRJ jar

# Troubleshooting
During ndk-build, if you get a permission error regarding libspotify.so in the obj output directory, run this command from the project root directory:

    chmod -R 777 *

More info here: https://developer.vuforia.com/forum/android/problem-cygwin
