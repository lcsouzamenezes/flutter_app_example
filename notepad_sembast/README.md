# Sembast flutter notepad example

Note pad demo using sembast based persistency. [Online demo](https://alextekartik.github.io/flutter_app_example/notepad_sembast/).

Works on Flutter iOS/Android/Web/MacOS/Linux/windows.

Simple sembast example:
* Usage of `StreamBuilder` with `Query.onSnapshots()`
* Works on the web using `sembast_web`
* Works on flutter mobile using `sembast_sqflite`
* Works on flutter desktop using `sembast_sqflite` and `sqflite_common_ffi`

## Setup

Project files are not checked in, simply run:

```bash
flutter create .
flutter run
```

To allow running on iOS/Android. For other platforms, Make sure you are on the proper flutter channel (as of 2020/07/01: beta for the web, dev for MacOS/Linux, master for Windows)