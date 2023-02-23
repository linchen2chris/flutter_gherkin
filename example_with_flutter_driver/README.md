# example_with_flutter_driver

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

to run this test

1. using existing app,
   start your app first: =flutter run -d chrome test_driver/app.dart=
2. record the app Uri
3. replace with test_harness `runningAppProtocolEndpointUri`
4. run test `flutter test test_driver/test_harness.dart`
   ![result](https://i.imgur.com/qXqZE3U.png "test-result")
5. you will get test_driver/report.json
