# :exclamation: A re-write of this app is happening [here](https://github.com/razinj/context_launcher).

# Context Launcher

Context Launcher is an Android list-based launcher made to be simple, practical and straight forward to use.

## Run

Install dependencies:

```shell
# NPM
npm ci
# Gradle
cd android && ./gradlew build
```

Install and launch app in an android device/emulator:

```shell
npm run start:all
```

## Build

Debug `apk`:

```shell
cd android && ./gradlew assembleDebug
```

Release `apk` and `aab`

Before generating release builds, change the `versionCode` and `versionName` in `android/app/build.gradle`.

```shell
./gradlew assembleRelease # Release 'apk'
./gradlew bundleRelease # Release 'aab'
```

Or run the `build.sh` script.

## Tests

Only RN/Jest are implemented at the moment.

Run:

```shell
npm run test
```

## Misc

Open up the debugging menu:

```shell
adb shell input keyevent 82
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=razinj/context_launcher&type=Date)](https://star-history.com/#razinj/context_launcher&Date)
