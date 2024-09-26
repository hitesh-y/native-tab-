**React Native Navigation App**
This is a sample React Native project that demonstrates how to combine Drawer Navigation, Stack Navigation, and Tab Navigation in the same application using the react-navigation library.

Features
Drawer Navigation: A sidebar menu to navigate between different main sections of the app (e.g., Home, Profile).
Tab Navigation: A bottom tab bar for switching between screens within the Home section.
Stack Navigation: A stack for navigating between screens within the Home tab (e.g., Home to Details).
Screens
Home Screen: The main screen of the app inside a tab.
Details Screen: A second screen in the stack navigator.
Settings Screen: A separate tab in the Tab Navigator.
Profile Screen: Accessed through the drawer navigator.
Installation
Follow these steps to set up the app locally.

Prerequisites
Ensure you have the following tools installed:

Node.js
React Native CLI (for non-Expo setups)
Android Studio (for Android) or Xcode (for iOS) for running the application on a simulator or device.

Clone the repository 
git clone https://github.com/your-username/react-native-navigation-app.git
cd react-native-navigation-app

Install dependencies 
npm install

Install React Native Navigation dependencies 
npm install @react-navigation/native @react-navigation/stack @react-navigation/drawer @react-navigation/bottom-tabs react-native-screens react-native-safe-area-context

Install other required dependencies
npx expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

Run the app
For Android:
npx react-native run-android

For iOS: 
npx react-native run-ios

Project Structure
├── App.js              # Main app file containing navigators
├── package.json        # Project configuration and dependencies
└── README.md           # Project documentation (this file)

App.js Structure
Drawer Navigator: Contains the primary routes (Home and Profile).
Tab Navigator (inside Home): Switches between Home and Settings.
Stack Navigator (inside Home Tab): Navigates between Home and Details.

Navigation Overview
Drawer Navigation: Top-level navigation.
Home (Tab Navigation)
Home (Stack Navigation)
Home Screen
Details Screen
Settings Screen
Profile Screen
