# flappy-droid

A fork of Marshmallow Land - Android M Easter Egg.

This project was forked from https://github.com/rubenochiavone/flappy-droid-mhttps://github.com/rubenochiavone/flappy-droid-m

Take a look at Android 6.x.x branches or tags from [https://android.googlesource.com/platform/frameworks/base.git](https://android.googlesource.com/platform/frameworks/base.git).

## API level compat

Compatible with API level 21 or higher.

## What were changed from the original project?

### build.gradle (flappy-droid-m)

- Dependency "com.android.tools.build:gradle" was updated to version "7.2.0".

- The repository to retrieve the files was changed from "jcenter()" to "google()".

### build.gradle (:app)

- "compileSdkVersion" and "targetSdkVersion" were updated to "31"

- The application ID was changed to "net.tlfoxhuman.marshmallowland" to avoid conflict with the original.

- "compile" is obsolete so it was replaced to " implementation". The same process was applied to "androidTestCompile" and "testCompile".

### gradle-wrapper.properties

- "distributionUrl" was changed to "https\://services.gradle.org/distributions/gradle-7.3.3-bin.zip"

### Other

- The application ID was changed to "net.tlfoxhuman.marshmallowland" to avoid conflict with the original.

## Known issues

- Vibration does not work on Android 12. (Maybe another version will also not work. Since I tested only on Android 12, I don't know how other versions behave.)
