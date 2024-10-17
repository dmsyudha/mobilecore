# Mobile Akarinti

Hello there, code reviewer! 👋 Welcome to the Mobile Core project, where we're not just building apps, we're compiling dreams and debugging nightmares! 🚀🐛

Before you dive into this code masterpiece, let me assure you that this project is so cross-platform, it makes the USB-C port jealous. We've got more build configurations than a Lego enthusiast's wildest fantasies!

Remember, in the world of mobile development, we don't have bugs - we have undocumented features.

May your builds be swift and your runtime errors be few. Let the review begin! 🎭🖥️

## Prerequisites

- Node.js (version 18 or higher)
- Yarn (version 3.6.4 or higher)
- React Native CLI
- Android SDK and tools for Android development
- Xcode for iOS development


## Setup React Native Environment

1. Install Node.js and npm:
   Download and install Node.js (which includes npm) from [nodejs.org](https://nodejs.org/)

2. Install Yarn:
   ```
   npm install -g yarn
   ```

3. Install React Native CLI:
   ```
   npm install -g react-native-cli
   ```

4. Set up Android and iOS development environment:
   Follow the official React Native documentation for [Android and iOS setup](https://reactnative.dev/docs/set-up-your-environment)


5. Clone the repository and install dependencies:
   ```
   git clone <repository-url>
   cd <project-directory>
   yarn install
   ```

Now you're ready to start developing with This Project!


## Environment Setup

The project uses different environment configurations for development, staging, and production. Make sure you have the following files in your project root:

- `.env.dev`
- `.env.staging`
- `.env.prod`

Each file should contain the appropriate environment variables for its respective environment.

## Build Commands

### Android

Clean the Android build:
```
npm run android:clean
```


Build debug APK for different environments:
```
npm run android:build:dev:debug
npm run android:build:staging:debug
npm run android:build:prod:debug
```

Build release APK for different environments:
```
npm run android:build:dev:release
npm run android:build:staging:release
npm run android:build:prod:release
```

Build all debug APKs:
```
npm run android:build:all:debug
```

Build all release APKs:
```
npm run android:build:all:release
```

### Build Output Locations

When building APKs for Android, the output locations will be as follows:

- Dev Debug APK:
  `android/app/build/outputs/apk/dev/debug/app-dev-debug.apk`

- Dev Release APK:
  `android/app/build/outputs/apk/dev/release/app-dev-release.apk`

- Staging Debug APK:
  `android/app/build/outputs/apk/staging/debug/app-staging-debug.apk`

- Staging Release APK:
  `android/app/build/outputs/apk/staging/release/app-staging-release.apk`

- Prod Debug APK:
  `android/app/build/outputs/apk/prod/debug/app-prod-debug.apk`

- Prod Release APK:
  `android/app/build/outputs/apk/prod/release/app-prod-release.apk`

These locations are based on the standard output directories for Android Gradle builds. After running the respective build commands, you can find the APK files in these locations within your project directory.


### iOS

Clean the iOS build:
```
npm run ios:clean
```

Build debug IPA for different environments:
```
npm run ios:build:dev:debug
npm run ios:build:staging:debug
npm run ios:build:prod:debug
```

Build release IPA for different environments:
```
npm run ios:build:dev:release
npm run ios:build:staging:release
npm run ios:build:prod:release
```

Build all debug IPAs:
```
npm run ios:build:all:debug
```

Build all release IPAs:
```
npm run ios:build:all:release
```

## Development

Start the Metro bundler:
```
npm run start
```

Start the development server for different environments:
```
npm run android
```

Run the app on iOS:
```
npm run ios
```

Run ESLint:
```
npm run lint
```

Run Prettier:
```
npm run prettier
```

## Note


For iOS builds, ensure you have the necessary certificates, provisioning profiles, and export option plists set up correctly.
