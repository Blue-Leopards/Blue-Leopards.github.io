## Table of contents

* [Overview](#overview)
* [How to Run](#how-to-run)


## Overview

Blue Leopards is a reimplementation of the functionality of [Bowfolios](https://bowfolios.github.io) for mobile devices. Work has currently been done on the frontend using [React Native](https://reactnative.dev) for component-based UI design and [React Native Paper](https://callstack.github.io/react-native-paper/) for production-ready components. React Native is a cross-platform UI framework for iOS and Android devices. However, this project is designed with mostly Android devices in mind. These are the current states of the profiles, projects, and interests pages:

### Profiles Page

### Projects Page

### Interests Page


## How To Run

Details on how to run this application on *Windows for Android* will be given. For more information on how to set up the development environment for macOS and Linux, refer to the [react native documentation](https://reactnative.dev/docs/environment-setup).

In order to run this application on your machine, you will need Node, the React Native CLI, Python 2, a JDK, and Android Studio. Although you may use any editor, Android Studio will be used as an emulator in order to run the application. 

You will then need the code which can be forked or downloaded from the [repository](https://github.com/Blue-Leopards/BlueLeopards). 

The current frontend will be in the `client` directory. So, in the BlueLeopards directory, run:

```
cd client
```

You will then need to install the dependencies:

```
npm i
```

To run the application, you will need to start Metro, the JavaScript bundler that ships with React Native:

```
npx react-native start
```

Finally, start the application by opening another terminal and typing:

```
npx react-native run-android
```

If everything went well, you will see the app running in the Android emulator.