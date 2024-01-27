# tOdO LiSt App
Setting up the development environment

npx create-expo-app tOdO-LiSt

cd tOdO-LiSt
npx expo start

Install the Expo Go app on your iOS or Android phone and connect to the same wireless network as your computer. On Android, use the Expo Go app to scan the QR code from your terminal to open your project. On iOS, use the built-in QR code scanner of the default iOS Camera app.

Expo Go app on your Android phone: https://play.google.com/store/apps/details?id=host.exp.exponent&referrer=www
Expo Go app on your iOS: https://itunes.apple.com/app/apple-store/id982107779

# Install dependencies
To run the project on the web, we need to install the following dependencies that will help to run the project on the web: 
`npx expo install react-dom react-native-web @expo/webpack-config`

# Run the app on mobile and web
In the project directory, run the following command to start a development server from the terminal:

npx expo start
# Project structure
App.js
The App.js file is the default screen of your project. It is the root file that loads after running the development server with npx expo start. You can edit this file to see the project update instantly. Generally, this file will contain root-level React Contexts and navigation.

app.json
The app.json file contains configuration options for the project. These options change the behavior of your project while developing, in addition to while building, submitting, and updating our app.

assets folder
The assets folder contains adaptive-icon.png used for Android and an icon.png used for iOS as an app icon. It also contains splash.png which is an image for the project's splash screen and a favicon.png if the app runs in a browser.

# Splash screen using figma
Search in figma community for expo app icons and splash

Draw your logo within the background circles for both ios and android. Then  delete the background circle guides

