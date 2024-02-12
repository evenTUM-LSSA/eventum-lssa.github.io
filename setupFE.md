---
title: Setup
layout: default
parent: Frontend
nav_order: 1
---

### Pre-Setup
- Install the latest versions of `node` and `npm` (recommended, but other solutions are possible - the commands will change)
- Download Android Studio on your PC (recommended) **or** the Expo Go App on your smart phone

#### Android Studio
1. Open `More Actions` - `Virtual Device Manager` - `+`
2. Add a Smartphone to emulate
    - Most often used during testing: Google Pixel 6 with API-Level 33 and Android 13.0

### Setup

1. Run `npm install` and `npm update` to ensure latest versions.
2. Change the variable `stdurl` in `GlobalParameters.tsx` to the location of the backend-server. This will be used as the default route for accesses to the backend.
    - For locally hosted backend: Only put your IP in the field IP and it should be enough (Open cmd and type `ipconfig` - use the ipv4-address)
    - For not locally hosted backend: Override the field stdurl with the servers destination.
3. Locally hosted backend: If You want a populated App run `npm test Setup`
    - please do not do this step multiple times
4. Start an emulator or the Expo Go App on your smart phone 
5. Run `npm start` for starting the server.
6. Either Scan the QR-Code in the Expo Go App or type `a` in the terminal for opening the application in a running emulator.
    - Android Studio: First time running this will need some time due to software which has to be installed on the emulated phone
7. The App should start to render

#### Setup-Problems with the Expo Go App

Though opening the application on a different device and not in an emulator is essential for testing some usecases, it will provide problems. The easiest to prevent are following ones:
1. Both devices (mobile device and computer running the application) have to be in the same network
2. The computer has to be visible in the network (in other words: has to set the network as a private one)

Sadly often even with this two fixes it will not be possible. Please use emulators like Android Studio in this cases.