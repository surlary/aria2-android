# aria2-android

[![Build aria2](https://github.com/devgianlu/aria2-android/actions/workflows/build.yml/badge.svg)](https://github.com/devgianlu/aria2-android/actions/workflows/build.yml)

All you need to cross-compile [aria2](https://github.com/aria2/aria2) for Android.

## Build

Clone the repository with submodules (`--recurse-submodules`), install the Android NDK r23, set the `ANDROID_NDK_HOME`
env variable and run `./build_all.sh`.

This will compile aria2 for `armeavi-v7a`, `arm64-v8a`, `x86` and `x86_64`. The binaries can be found inside the `bin`
folder.
