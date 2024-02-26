# Flutter Android Alarm Manager
Welcome to Flutter Android Alarm Manager! This Flutter plugin allows you to easily schedule and manage alarms on Android devices. Whether you want to set up reminders, notifications, or recurring tasks, this plugin provides a simple and efficient way to implement alarm functionality in your Flutter applications.

## Features
1. **Alarm Scheduling:** Schedule one-time or recurring alarms with customizable options such as date, time, interval, and repeat frequency.

2. **Alarm Management:** Retrieve, update, cancel, and delete scheduled alarms as needed to adapt to changing requirements or user preferences.

3. **Background Execution:** Ensure alarms are triggered even when the app is in the background or the device is in doze mode, providing reliable and consistent functionality.

4. **Customizable Notifications:** Customize alarm notifications with options for title, message, icon, sound, vibration, and other attributes to provide informative and engaging user experiences.

5. **Persistent Storage:** Store alarm data persistently to survive app restarts, device reboots, or other system events, maintaining consistency and reliability.

6. **Platform Compatibility:** Support for Android devices, leveraging native Android APIs to maximize performance, reliability, and compatibility.

## Installation
To use Flutter Android Alarm Manager in your Flutter project, follow these steps:

1. **Install the Package:** Add the flutter_android_alarm_manager package to your pubspec.yaml file:

dependencies:
  flutter:
    sdk: flutter
  flutter_android_alarm_manager: ^1.0.0
  
2. **Install Dependencies:** Run flutter pub get in your terminal to install the package and its dependencies.

3. **Add Permissions:** Ensure the necessary permissions are declared in your Android manifest file (e.g., android/app/src/main/AndroidManifest.xml) for alarm functionality:

## Usage
1. **Schedule Alarms:** Use the AlarmManager.set method to schedule alarms with specific configurations such as interval, frequency, and notification details.

2. **Cancel Alarms:** Use the AlarmManager.cancel method to cancel existing alarms based on their unique alarm IDs.

3. **Retrieve Alarms:** Use the AlarmManager.getAll method to retrieve a list of all scheduled alarms for display or management purposes.

4. **Handle Alarm Callbacks:** Implement the necessary logic to handle alarm callbacks and trigger desired actions when alarms are activated.

5. **Handle Device Reboots:** Ensure alarms are rescheduled after device reboots by listening for the BOOT_COMPLETED broadcast and re-registering alarms as needed.

## Customization
Customize alarm functionality and behavior according to your application's requirements by adjusting alarm settings, notification styles, callback actions, and error handling mechanisms.
