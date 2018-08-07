# Introduction

This is a Visiting card sharing application. Developed in ionic using NFC and firebase.

# Ionic Setup

Ionic apps are created and developed primarily through the Ionic command line utility (the “CLI”), and use Cordova to build/deploy as a native app. This means we need to install a few utilities to get developing.

1.  <strong>Getting Node and NPM</strong>

    Most of the tooling in the CLI is based on Node and is managed through npm. The quickest way to get Node and NPM installed on your machine is through the [NodeJS installer](https://nodejs.org/en/). Be sure to install the LTS version of Node. Close any terminals/command prompts you may have open, run the installer, and launch a new terminal window. To verify you have everything installed correctly, you can run npm --version and node --version. If this errors, please resolve before moving on.

1)  <strong>Ionic CLI and Cordova</strong>

    With Node and NPM setup, let’s install the Ionic and Cordova CLI.

    `$ npm install -g ionic cordova`

# Project Setup

1.  [Download code](https://google.com)
2.  Unzip folder.
3.  Open terminal.
4.  Go to Root directory of project.
5.  Write following command in terminal

    ```
    $ npm install
    $ ionic cordova platform add android // for android
    $ ionic cordova platform add ios // for ios
    $ ionic cordova run android // for android
    $ ionic cordova run ios // for ios
    ```

# Firebase Setup

1.  [Login](https://firebase.google.com/) into firebase console.
2.  Got to [Firebase Console](https://console.firebase.google.com/u/0/).
3.  Create
