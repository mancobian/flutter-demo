# example_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Debugging

- Run through the steps described in the codemagic.io article [1] to create a containerized Flutter workspace
- Create a wireless debug connection to your Android device by running the following commands in your container:
    - `adb tcpip 5555`
    - `adb connect <device-ip-address>:5555`
    - `adb devices`

## References
1. https://blog.codemagic.io/how-to-dockerize-flutter-apps/
2. https://android.jlelse.eu/wireless-debugging-through-adb-in-android-using-wifi-965f7edd163a
