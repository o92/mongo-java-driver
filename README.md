## Release Notes

This is an Android porting of Java MongoDB Driver - 3.2.0-SNAPSHOT version - updated on 5 November 2015.

You can download compiled JAR from https://github.com/matfur92/mongo-java-driver/blob/gh-pages/JARs/mongo-java-driver-3.2.0-SNAPSHOT.jar?raw=true 

I've forked from ufficial mongodb/mongo-java-driver (master branch) and integrated classes from
https://github.com/koterpillar/android-sasl
to fix javax.security.sasl on Android.

## Feel free to open new issues and contact me

## Important
No driver-async is not ported because java.nio.channels.AsynchronousSocketChannel doesn't exist on Android and doesn't exist any porting.
