[简体中文](./README.md) | [English](./README_EN.md)

# project instruction

    1. Explore the RN features of the new version;
    2. Integrate component experiments and build your own wheels!
    3. Hone my architectural skills and continue coding and code optimization.
    Welcome to join us:
    QQ group: 783071253
    Email address: supervons@sina.com
    Current RN version: 0.64.1

# Features

| Name | Description | Use component name and version |
| ------------- | -------------------------------- | ------------------------------------------------------------ |
| Picture selection | Choose a picture in the album, or take a photo | react-native-image-picker@2.3.4 |
| Scan | Scan the QR code to get the information in the QR code | react-native-camera@3.8.0 |
| Theme change | Change system navigation head and button colors | react-navigation@3.11.1 |
| UI library | Project UI library | react-native-elements@3.1.0 |
| Redux Family Bucket | Use of redux and middleware | redux@4.0.4<br />redux-persist@5.10.0<br />redux-logger@3.0.6<br />redux-thunk@2.3 .0 |
| Network request | Unified package network request | axios@0.19.0 |
| Refactoring based Hook | Refactoring class page based on hook | react@17.0.1 |
| Skeleton screen | Improve the list and page browsing experience | react-native-shimmer-placeholder@2.0.7 |
| Language Localize | APP language switch, with the local system Settings | react-native-localize@2.0.3 + i18n-js@3.8.0 |
| Components-Dragged | Component elements move with touch drag and drop | react-native-draggable@3.3.0 |

# TODO LIST

- [x] Theme Change
- [x] Skeleton
- [x] Language Localize
- [x] Morandi-Colors
- [x] Components are drag-and-drop supported
- [ ] Perfect preview page
- [ ] Multiple Bundle Support

# Project Structure

```
|-- android	// android
|-- ios	// iOS
| -- src	// project folder
|   | -- actions	// interface-related directories
|   | --common	// common configuration constant directory
|   | -- components	// System-level component catalog
|   |--hook// Custom hook directory
|   | -- redux	// redux-related directories
|   |   |-- action
|   |   |-- reducer
|   |   |-- store
|   | -- resource	// resource directory
|   | -- routers	// route navigation directory
|   | -- screens	// System page directory
|   | --styles	// system common style directory
|   | -- utils	// System tool catalog
| -- App .js	// Entry file
| -- buildAndroid.sh	// android packaging script
| -- package.json	// This needless to say
| -- package-lock.json	// i.e
|-- . preettierrc	// Prettierrc code format the directory
```

# Installation dependencies

```sh
npm install
# If it is iOS, you need to perform the following operations to ensure that the network is unblocked
cd ios && pod install
```

# Run

    android: react-native run-android
    ios: Xcode selects AwesomeProject.xcworkspace to start

# Test account

    Username: test
    Password: test
