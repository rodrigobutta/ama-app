## Mobile App (React Native)
Not over Docker.
Using EXPO.

### Config
`mobile/src/config/config.ts` Set nodejs port and current local IP (for example 192.160.0.120)

### Install and Build
`yarn install`

### Run
//  http://localhost:19002
`yarn start`    
- Run in iOS simulator (xcode)
- Run in Android simulator (Android Studio)
- Run in real iPhone (install Expo app in mobile and then with camera, scan QR code)
- Run in real Android phone (install Expo app in mobile and inside Expo, scan code)

### Debug (VSCODE)
1) Add `React Native Tools` extension
2) Start `App React Native`from `launch.json`
3) `yarn start`
4) Scan QR in Expo App
5) With three fingers over app, Expo menú, `Enable Remote Debugging`

#### Troubleshoot debugging
https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native#expo-applications
`npm install react-native --global`
`npx react-native upgrade`
`npx react-native doctor`
`npm install -g expo-cli`
`expo start -c`
`react-native-clean-project`


# Run Prettier Batch
(shouldnt be needed but if we paste code from somewhere else)

(web and node)

`npx prettier --write .`