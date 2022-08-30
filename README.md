# Minimal Reproduction of the Cordova Media Plugin not playing streams

## Installation

```
npm i
```

`npm ci` might reproduce better, but I'm not sure my package-lock.json is portable -- please excuse my inexperience.

## Run

```
cordova run ios
```

## Observe

* Click the first or second button - audio should start playing
* Click any other button - Media will report status code 2 (`RUNNING`), but no sound plays  
  (fixed in `hotfix` branch)
