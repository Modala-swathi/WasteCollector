# WasteCollector

A mobile application built with React Native and Expo for managing waste collection schedules, complaints, and billing.

## Overview

WasteCollector is a comprehensive waste management mobile app that allows users to:
- Schedule waste collection pickups
- File complaints and support requests
- View billing information and payment history
- Track collection schedules with map-based location selection
- Manage their profile and account settings

## Features

- **User Authentication**: Phone number-based authentication with OTP verification
- **Schedule Management**: Easy-to-use interface for scheduling waste collection
- **Complaints & Support**: Submit and track complaints with support team
- **Billing System**: View bills and payment history
- **Map Integration**: Location selection for pickup points
- **Profile Management**: User profile and account settings
- **Multi-platform**: Runs on iOS, Android, and Web

## Tech Stack

- **Framework**: React Native with Expo
- **Navigation**: React Navigation (Bottom Tabs + Native Stack)
- **Maps**: React Native Maps
- **Camera**: Expo Camera & Image Picker
- **State Management**: React Context API
- **UI Components**: React Native built-in components + SVG support

## Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **Expo CLI**: Install globally with `npm install -g expo-cli`

## Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd WasteCollector
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

## Running the App

### Development Server
Start the Expo development server:
```bash
npm start
```

### Android
```bash
npm run android
```
Or press `a` in the Expo CLI

### iOS
```bash
npm run ios
```
Or press `i` in the Expo CLI

### Web
```bash
npm run web
```
Or press `w` in the Expo CLI

## Project Structure

```
├── App.js                    # Main app component
├── AppNavigator.js           # Navigation setup
├── UserContext.js            # Global user state management
├── index.js                  # Entry point
├── app.json                  # Expo configuration
├── package.json              # Dependencies
├── assets/                   # App icons and splash screens
└── screens/                  # Screen components
    ├── OnboardingScreen.js    # Initial onboarding flow
    ├── MobileNumberScreen.js  # Phone number entry
    ├── OtpScreen.js           # OTP verification
    ├── ProfilePictureScreen.js # Profile picture upload
    ├── HomeScreen.js          # Main home screen
    ├── ScheduleScreen.js      # Schedule waste collection
    ├── MapPickerScreen.js     # Select location on map
    ├── ComplaintScreen.js     # File complaints
    ├── BillingScreen.js       # View bills and payments
    ├── ProfileScreen.js       # User profile management
    ├── SupportScreen.js       # Customer support
    ├── MoreSettingsScreen.js  # Additional settings
    └── BottomTabs.js          # Bottom tab navigation
```

## Key Components

- **UserContext**: Manages global user authentication and profile state
- **AppNavigator**: Configures navigation stack and tab-based navigation
- **BottomTabs**: Tab-based navigation for main app screens

## Scripts

- `npm start` - Start the Expo development server
- `npm run android` - Run on Android emulator/device
- `npm run ios` - Run on iOS simulator
- `npm run web` - Run in web browser

## Dependencies

Key packages used:
- `react-native` - Mobile app framework
- `expo` - Development platform
- `@react-navigation/*` - Navigation library
- `react-native-maps` - Map functionality
- `expo-camera` - Camera access
- `expo-image-picker` - Image selection
- `expo-location` - Location services
- `react-native-svg` - SVG support

## Contributing

1. Create a feature branch (`git checkout -b feature/amazing-feature`)
2. Commit your changes (`git commit -m 'Add amazing feature'`)
3. Push to the branch (`git push origin feature/amazing-feature`)
4. Open a Pull Request

## License

This project is private and proprietary.

## Support

For support, please contact the development team or use the in-app support feature.

## Version

Current version: 1.0.0
