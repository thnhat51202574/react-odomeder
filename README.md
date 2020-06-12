## 1. Getting started

0. Install [Sass](https://sass-lang.com/install). Use the Cholatey installer.
1. Install [NodeJS](https://nodejs.org/en/download/).
2. ```npm install``` inside project directory.
3. ```npm run lang``` inside project directory.
4. If you want to run Web version, follow steps 5 and 6; for PC version, follow steps 7 and 8.
5. [Web] Add ```127.0.0.1 chat.zalo.me``` to *hosts* file.
6. [Web] ```npm run start``` inside project directory. Web version should launch after a moment.
7. [PC] ```npm run pc-start-dev```.
8. [PC] Open new command window and run ```npm run pc-compile```, app should launch after a moment.
9. To build public version of PC app, run ```npm run dist```.

*Note*

* When running ```pc-compile```, the error with Electron not being installed properly may be thrown. In that case, just follow the instructions shown on screen (delete *electron* folder inside *node_modules* and run ```npm install electron``` again).

*Web Dev optional Chrome extensions*
 
* React devtools: https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
* Redux devtools: https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd

set flag : ELECTRON_BUILDER_ALLOW_UNRESOLVED_DEPENDENCIES=true