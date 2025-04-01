# Airplane Mode Scheduler App

## Overview
Airplane Mode Scheduler is an Android application that allows users to automatically schedule airplane mode to turn on and off at specific times. The app is particularly useful for setting up sleep schedules where users want their phone to automatically enter airplane mode during sleep hours.

## Features
- Simple time-based scheduling for airplane mode
- Sleep hours scheduling with customizable times
- Profile management for different scenarios
- Notifications before and after airplane mode changes
- Dark and light theme support
- Automatic restoration of schedules after device reboot

## Technical Details
- Minimum SDK: Android 6.0 (API level 23)
- Target SDK: Android 13 (API level 33)
- Architecture: MVVM (Model-View-ViewModel)
- Data Storage: SharedPreferences with Gson serialization
- Scheduling: AlarmManager for precise time-based scheduling
- Permissions: WRITE_SETTINGS (for airplane mode control), POST_NOTIFICATIONS, RECEIVE_BOOT_COMPLETED

## Installation
1. Download the APK file from the release folder
2. Enable "Install from Unknown Sources" in your device settings
3. Open the APK file to install the application
4. Grant the necessary permissions when prompted

## Usage
1. Open the app and set up your sleep schedule
2. Configure notification preferences
3. Activate the profile
4. The app will automatically toggle airplane mode according to your schedule

## Permissions
- **WRITE_SETTINGS**: Required to toggle airplane mode
- **POST_NOTIFICATIONS**: Required to show notifications before and after airplane mode changes
- **RECEIVE_BOOT_COMPLETED**: Required to restore schedules after device reboot

## Future Improvements
- Calendar integration for more advanced scheduling
- Location-based triggers
- Exceptions for emergency contacts
- Battery usage statistics
- Backup and restore functionality

## License
This application is provided as-is without any warranty. All rights reserved.
