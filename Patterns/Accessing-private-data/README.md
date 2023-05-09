# Accessing private data

## Requesting permission
Here are several examples of the things you must request permission to access:

- Personal data, including location, health, financial, contact, and other personally identifying information
- User-generated content like emails, messages, calendar data, contacts, gameplay information, Apple Music activity, HomeKit data, and audio, video, and photo content
- Protected resources like Bluetooth peripherals, home automation features, Wi-Fi connections, and local networks
- Device capabilities like camera and microphone
- The device’s advertising identifier, which supports app tracking

- Request permission only when your app clearly needs access to the data or resource.
- Avoid requesting permission at launch unless the data or resource is required for your app to function.
- Write copy that clearly describes how your app uses the ability, data, or resource you’re requesting.

## Location button (iOS15+)
- Consider using the location button to give people a lightweight way to share their location for specific app features.
- Consider customizing the location button to harmonize with your UI.

## Pre-alert screens
- Include only one button and make it clear that it opens the system alert.
- Don’t include additional actions in your custom screen.

## Tracking requests
- Never precede the system-provided alert with a custom screen that could confuse or mislead people.

## Protecting data
- Avoid relying solely on passwords for authentication.
- Store sensitive information in a keychain.
- Never store passwords or other secure content in plain-text files.
- Avoid inventing custom authentication schemes.

https://developer.apple.com/design/human-interface-guidelines/accessing-private-data
