# Mobile Development Environment Setup

## Objective

The goal of this task is to set up and test a mobile development environment using the **Expo Framework for React Native**. This setup ensures smooth app development and testing across both iOS and Android devices.

## Requirements

- Node.js (LTS)
- Visual Studio Code
- macOS / Linux / Windows
- Expo Go (Android or iOS)

## Why Expo Go?

Expo Go simplifies mobile development by allowing apps to run directly on physical devices without emulators. This provides a cost-effective and efficient way to test applications across different platforms.

## Setup Steps

1. Visit [https://expo.dev/go](https://expo.dev/go)
2. Select the latest SDK version.
3. Install **Expo Go**:
   - **Android:** from Google Play Store
   - **iOS:** from Apple App Store
4. Open the Expo Go app and log in or create a new account.
5. Verify Node.js installation:

```bash
node -v
npm -v
```

6. Create and test a new Expo project:

```bash
npm install -g expo-cli
npx create-expo-app testApp
cd testApp
npx expo start
```

7. Scan the QR code in Expo Go to run the app on your device.
