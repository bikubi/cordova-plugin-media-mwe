# Minimal Reproduction of the Cordova Media Plugin not playing streams

Created via `cordova create` and minimal changes, following [the guide](https://github.com/apache/cordova-contribute/blob/master/create-reproduction.md).

## Installation

```
npm ci
```

## Run

```
cordova platform add ios
cordova run ios # --ide, --device, ymmv
```

## Observe

* Click the first button - audio should start playing
* Click any other button - Media will report status code 2 (`RUNNING`), but no sound plays
