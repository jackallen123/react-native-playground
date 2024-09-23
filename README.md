# React Native Todo List App

This repository contains a simple todo list app built with React Native. It serves as a starting point for our senior design project.

## Table of Contents
1. [Setting Up the Development Environment](#setting-up-the-development-environment)
2. [Cloning and Running the Project](#cloning-and-running-the-project)
3. [Creating a New Expo App](#creating-a-new-expo-app)
4. [Useful Resources](#useful-resources)

## Setting Up the Development Environment

Before you begin, make sure you have the following tools installed and set up on your machine:

### 1. Node.js
Ensure that Node.js is installed on your system. You can check this by running:
```
node -v
```
If it's not installed, download and install it from [nodejs.org](https://nodejs.org/).

### 2. Expo CLI
Install the Expo CLI globally by running:
```
npm i -g expo-cli
```

### 3. Expo Client App
Install the Expo Client app on your mobile device:
- [Expo for Android](https://play.google.com/store/apps/details?id=host.exp.exponent)
- [Expo for iOS](https://apps.apple.com/us/app/expo-go/id982107779)

Create an account in the Expo Client app.

### 4. Visual Studio Code
Download and install [Visual Studio Code](https://code.visualstudio.com/).

#### Recommended VS Code Extensions
Install the following extensions in VS Code for a better development experience:
- React Native Tools by Microsoft
- ES7 + React/Redux/React-Native snippets by dsznajder
- Prettier - Code Formatter by Prettier
- Material Icon Theme by Phillip Kief

## Cloning and Running the Project

Follow these steps to clone the repository and run the todo list app:

1. Open your terminal and navigate to the directory where you want to clone the project.

2. Clone the repository:
   ```
   git clone [Your GitHub Repository URL]
   ```

3. Navigate into the project directory:
   ```
   cd [Your Project Directory Name]
   ```

4. Install the project dependencies:
   ```
   npm install
   ```

5. Start the Expo development server:
   ```
   npx expo start
   ```

6. Running the app:
   - To run in a web browser, press `w` in the terminal.
   - To run on your mobile device, scan the QR code displayed in the terminal with your device's camera. This will open the app in the Expo Client.

## Creating a New Expo App

If you need to create a new Expo app from scratch in the future, follow these steps:

1. Create a new Expo app:
   ```
   npx create-expo-app@latest [Your App Name]
   ```

2. Navigate into your new app's directory:
   ```
   cd [Your App Name]
   ```

3. Install additional dependencies for web support:
   ```
   npx expo install react-native-web react-dom @expo/metro-runtime
   ```

4. Start the Expo development server:
   ```
   npx expo start
   ```

## Useful Resources

- [React Native Documentation](https://reactnative.dev/docs)
- [Expo Documentation](https://docs.expo.dev/)
- [React Navigation](https://reactnavigation.org/)