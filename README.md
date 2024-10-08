# reCAPTCHA Enterprise Flutter Module

Please note that issues filed in this repository are not an official Google
support channel and are answered on a best effort basis. For official support,
please visit: https://cloud.google.com/support-hub.

If you have an issue with the Flutter plugin please post issues in this
repository. If you are having issues with the underlying SDK, please post issues
in
[https://github.com/GoogleCloudPlatform/recaptcha-enterprise-mobile-sdk](https://github.com/GoogleCloudPlatform/recaptcha-enterprise-mobile-sdk).

For general documentation on reCAPTCHA Enterprise for mobile applications, see
[Android](https://cloud.google.com/recaptcha-enterprise/docs/instrument-android-apps)
and
[iOS](https://cloud.google.com/recaptcha-enterprise/docs/instrument-ios-apps).

## Sample App

Copy example/assets/configs/dev.json.example to example/assets/configs/dev.json
and add your sitekeys to the file.

Change ios bundle id in example/ios/Runner.xcodeproj/project.pbxproj from
google.FlutterTestApp in three places to your own bundle id.

Change the Android bundle id in example/android/app/build.gradle from
google.FlutterTestApp to your own.

Start an emulator, e.g. `open -a Simulator` or
`~/Library/Android/sdk/emulator/emulator -avd Pixel_4_API_32`

### Run app:

```bash
cd example && flutter run
```

### Run unit tests:

```bash
flutter test
```

### Running Integration Tests

```bash
cd example && flutter test integration_test/app_test.dart
```