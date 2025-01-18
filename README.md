# Expo Android Build Error: Missing google-services.json

This repository demonstrates a common error encountered when building Android APKs using the Expo CLI: the missing `google-services.json` file. This file is essential for using Firebase or other Google services within your React Native application.

The `bug.js` file simulates a project setup where the `google-services.json` file might be missing or incorrectly placed. The `bugSolution.js` file showcases how to correctly configure your project to resolve this issue.

## Steps to Reproduce the Bug

1. Clone this repository.
2. Try to build the Android APK using `expo build:android`.  You'll encounter the error indicating that `google-services.json` is missing.

## Solution

The solution involves ensuring the `google-services.json` file is correctly placed within the `android/app` directory of your Expo project.

See `bugSolution.js` for a working example.

## Additional Notes

- Make sure you have correctly configured your Firebase project and downloaded the `google-services.json` file.
- Double-check the file's location and permissions.  Sometimes an incorrect file path is the issue.
- Clean and rebuild your project to ensure the changes are applied correctly.