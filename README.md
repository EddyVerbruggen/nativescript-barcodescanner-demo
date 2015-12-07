# nativescript-barcodescanner demo app

Demo app for the {N} [barcodescanner plugin](https://www.npmjs.com/package/nativescript-barcodescanner)

## Installation

This app is built with the [NativeScript CLI](https://github.com/NativeScript/nativescript-cli).
Once you have the [CLI installed](https://github.com/NativeScript/nativescript-cli#installation), start by cloning the repo:

```
$ git clone https://github.com/EddyVerbruggen/nativescript-barcodescanner-demo
$ cd nativescript-barcodescanner-demo
```

Next, install the app's iOS and Android runtimes, as well as the app's npm dependencies:

```
$ tns install
```

From there you can use the `run` command to run the demo app on iOS:

```
$ tns run ios --emulator
```

.. or on Android

```
$ tns run android --emulator
```

.. or on Android if you have a Genymotion device called `Nexus5X_600`
```
$ tns emulate android --geny Nexus5X_600
```

## Testing
Here, have a QR code:

![](qr.png)


## Screenshots

![](screenshots/ios/ios-1.png)
![](screenshots/ios/ios-2.png)

![](screenshots/android/android-1.png)
![](screenshots/android/android-2.png)