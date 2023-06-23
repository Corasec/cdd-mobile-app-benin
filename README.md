### Installation
1. Install packages using `yarn`
1. Run the porject as `npx expo start`

### Configuration URL

Update `remoteDB` in `src/utils/databaseManager.js` with your CouchDB Database url

Update `baseURL` in `src/services/API.js` with your web app url

### Development 
`expo start`
### Build the App
Build the app for android
`eas build -p android --profile preview `

`eas build:run -p android --latest`
