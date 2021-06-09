# SampleReactAppElectronBuilder

#electron Builder will create exe file for your react application

Steps to install
----------------

1.clone this repository

2.npm install

3.npm run electron-pack


Commands to build
------------------

1. "preelectron-pack": "react-scripts build"

    npm run electron-pack - not necessary while using the "electron-pack command"

2. "electron-pack": "electron-builder -c.extraMetadata.main=build/electron.js"

    -c.extraMetadata.main=build/electron.js - it will copy the electron.js file from public folder to build folder

3. npm run electron-pack

    it runs the "preelectron-pack" by default to create the build file and after that will create the exe file in dist folder.



