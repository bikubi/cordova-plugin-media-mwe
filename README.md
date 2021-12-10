# Minimal Reproduction of the Cordova Media Plugin not playing streams

## Installation

```
npm ci
```

## Run

```
cordova platform add ios
cordova run ios
```

## Observe

* Click the first button - audio should start playing
* Click any other button - Media will report status code 2 (`RUNNING`), but no sound plays
