# react-new ✨
This boilerplate aims on writing react code once that runs on all platforms 📱💻🌐🔥

utilizing 
* React
* React-Native
* Electron

and

* TypeScript
* Redux
* Jest
* Babel


[<img src="https://icons-for-free.com/iconfiles/png/512/design+development+facebook+framework+mobile+react+icon-1320165723839064798.png" width="100">](https://facebook.github.io/react-native/)
[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Electron_Software_Framework_Logo.svg/1200px-Electron_Software_Framework_Logo.svg.png" width="100">](https://electronjs.org/)
[<img src="https://raw.githubusercontent.com/remojansen/logo.ts/master/ts.png" width="100">](https://www.typescriptlang.org/)
[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Redux.png/220px-Redux.png" width="100">](https://redux.js.org/)
[<img src="https://camo.githubusercontent.com/b8606e6a237d8e7e7800067f0f739129da1fa6f8/687474703a2f2f7365656b6c6f676f2e636f6d2f696d616765732f4a2f6a6573742d6c6f676f2d463939303145424246372d7365656b6c6f676f2e636f6d2e706e67" width="100">](https://jestjs.io/)

## Getting Started 💪

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation
```
npm i
```
### iOS
```
cd ios
pod install
```

## Quick Start

### iOS 📱
```
npm run ios
```
 
### Android 📱
```
npm run android
```

### Desktop 💻
```
npm run electron
```

### Web 🌐
```
npm run web
```
## Troubleshooting 🐛

* When the Shell (.sh) scripts can't be executed:
Set the bash path (under Windows) 
```bash
npm config set script-shell "C:\\Program Files\\git\\bin\\bash.exe"
```

## Notes 📝

skipped enabling windows because react-native windows works on react-native 0.59 and react-native 0.61 is used

TODO:


```javascript
function enableWindows() {
    console.log('EnableWindows);
    execSync('react-native windows', {stdio: 'inherit'});

    unlinkSync(resolve('App.windows.js'));
}

enableWindows();
```

### react-everywhere

Props to react-everywhere. that template delivered the base for this boilerplate.

[![react-everywhere](https://camo.githubusercontent.com/b3394b073659a75910aebdee0eaf430f1c9f2c5e/68747470733a2f2f7332382e706f7374696d6167652e6f72672f3461307a77316567642f72652d73746172745f312e706e67)](https://github.com/react-everywhere)
