# react-native-cordova-webview

**React Native Cordova WebView** is Cordova Web View component for React Native. It is similar to https://github.com/react-native-community/react-native-webview but it also provides a way to commnicate between the web content and the native code using Cordova Plugin APIO

## Features

1. Display web content inside a React Native view.
2. Use the features of any Cordova plugin (https://cordova.apache.org/plugins/) from the Javascript loaded by the CordovaWebView. (Each plugin need to be install separately)
3. Send messages to React Native from the Javascript loaded by the CordovaWebView.

## Platform compatibility

This project is compatible with **iOS** and  **Android**.  

## Usage

Import the `CordovaWebView` component from `react-native-cordova-webview` and use it like so:

```tsx
import React from 'react';
import { CordoWebView } from 'react-native-cordova-webview';

// ...
const MyWebComponent = () => {
  return <CordoWebView source={{ uri: 'https://reactnative.dev/' }} style={{ flex: 1 }} />;
}
```
