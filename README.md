# Mobile Akarinti

Hello there, esteemed code reviewer! 👋 Welcome to the Mobile Core project, where we're not just building apps, we're compiling dreams and debugging nightmares! 🚀🐛

Before you dive into this React Native masterpiece, let me assure you that this project is so cross-platform, it makes the USB-C port jealous. We've got more build configurations than a Lego enthusiast's wildest fantasies!

Remember, in the world of mobile development, we don't have bugs - we have undocumented features. And trust me, we've documented everything here... except maybe where we hid the coffee machine. That's for you to debug! ☕

So, buckle up your development environment, because this project is about to take your code review skills on a journey from 'Hello World' to 'Hello Multiverse'!

May your builds be swift and your runtime errors be few. Let the review begin! 🎭🖥️

## Prerequisites

- Node.js (version 18 or higher)
- Yarn (version 3.6.4 or higher)
- React Native CLI
- Android SDK and tools for Android development
- Xcode for iOS development

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

Make sure to replace "YourProjectName" in the iOS build commands with your actual Xcode project/workspace name.

For iOS builds, ensure you have the necessary certificates, provisioning profiles, and export option plists set up correctly.
