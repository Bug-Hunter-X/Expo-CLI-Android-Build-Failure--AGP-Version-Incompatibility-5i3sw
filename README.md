# Expo CLI Android Build Failure: AGP Version Incompatibility

This repository demonstrates a bug where building an Android app using the Expo CLI fails due to an incompatibility between the Android Gradle Plugin (AGP) version and other dependencies.  The issue is commonly caused by version mismatches that can arise from updates to Expo CLI, Android Studio, or Gradle.

## Reproducing the Bug

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to build the Android app using `expo prebuild` or `expo build:android`.
4. Observe the build failure and the related error message indicating an AGP version conflict.

## Solution

The solution involves carefully managing the AGP version and ensuring consistency across your project's dependencies. The provided solution demonstrates how to resolve the issue by explicitly specifying a compatible AGP version or updating to a compatible set of versions.