# Expo Go Custom URL Scheme Issue

This repository demonstrates an issue with Expo Go's handling of custom URL schemes. When an app attempts to open a URL with a custom scheme (e.g., `myapp://`), Expo Go either crashes or fails to handle the URL appropriately. This is because Expo Go lacks support for custom URL schemes.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Run the app using `expo start`.
4. Try to open a custom URL scheme within the app.

## Solution

This issue can be resolved by using a different testing method for your app that does not rely on custom URL schemes while using Expo Go, or by modifying your app's code to handle URLs in a way that is compatible with Expo Go.