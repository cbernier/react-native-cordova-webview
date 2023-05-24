# react-native-cordova-webview

**React Native Cordova WebView** is Cordova Web View component for React Native. The main reason to use this component instead of react-native-webview (https://github.com/react-native-community/react-native-webview) is to use Cordova plugins (https://cordova.apache.org/plugins/).

## Features

1. Display web content inside a React Native view.
2. Use the features of any Cordova plugin from the Javascript loaded by the CordovaWebView. (Each plugin need to be install separately)
3. Send messages to React Native from the Javascript loaded by the CordovaWebView.

## Platform compatibility

This project is compatible with **iOS** and  **Android**.  

## Usage

Import the `CordovaWebView` component from `react-native-cordova-webview` and use it like so:

```tsx
import React from 'react';
import { CordovaWebView } from 'react-native-cordova-webview';

// ...
const MyWebComponent = () => {
  return <CordovaWebView source={{ uri: 'https://reactnative.dev/' }} style={{ flex: 1 }} />;
}
```
