# lein-droid-template

This is a Clojure/Android application.

## Usage

Assuming that zou have already installed and updated the Android SDK.
Set the ANDROID_SDK_LOCATION path in the `project.clj` under `:android :sdk-path`

Then

```bash
lein droid doall
```

will pull all dependencies, build the app, assemble and sign the APK,
eventually deploy the APK to a running emulator.

## License

Copyright © 2019 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
