# audio_service_refactor

Refactored example of the flutter audio_service package.  This is the identical example out on Ryan Heise's github repo for audio_service as of July 2021, https://github.com/ryanheise/audio_service.

This repo is provided as a reasonable starting point for a project that requires background audio using flutter audio_service.  All dependencies are as specified in the pubspec.yaml found in the example directory, with the exception that the audio_service dependency is specified as the latest version (0.17.1).  All code is identical to that found in example/main.dart, however the various classes have been broken out in a reasonably logical way.  No BLoC code or any other code has been added.

Please remember that there is additional code that may need to be added to the AndroidManifest.xml, the build.gradle files and the iOS info.plist, as specified in the pub.dev pages for audio_service, audio_session, and just_audio.

https://pub.dev/packages/audio_service
https://pub.dev/packages/audio_session
https://pub.dev/packages/just_audio

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
