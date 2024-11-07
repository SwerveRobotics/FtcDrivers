# Header
This is a library of a collection of I2C drivers for FIRST Tech Challenge.

# Description:
This repository contains drivers for the FTC SDK.

# Installation:
## Step 1:
First, go to your `build.gradle` file and go to `repositories`. Add `maven { url "https://jitpack.io" }` as a repository. (If it's already there, don't do anything.)
```Java
repositories {
  // Your other stuff here...
  maven { url "https://jitpack.io" }
}
```

## Step 2:
Then, go to `dependencies` in the same `build.gradle` file. Add `com.github.SwerveRobotics:FtcDrivers:0.0.1` as a dependency.
```Java
dependencies {
  // Your other stuff here...
  implementation 'com.github.SwerveRobotics:FtcDrivers:0.0.1'
}
```

