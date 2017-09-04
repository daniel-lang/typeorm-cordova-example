# typeorm-cordova-example
This is a simple app to demonstrate the usage of TypeORM in Cordova.

## Installation
1. Cordova: Install Cordova as a global node module: `npm install -g cordova`
2. Download all node dependencies: `npm install`
3. Copy `Reflect.js` and `system.src.js` from the `node_modules` folder into `www/lib`
4. Copy `typeorm-browser.js` from [my fork](https://github.com/daniel-lang/typeorm) by downloading and building the app (for now, until it is merged)

## Running the app
Run `tsc` followed by `cordova run android` or `cordova run ios`
