Info from the Ionic Documentation: https://ionicframework.com/docs/angular/your-first-app
### Install Ionic
> npm install -g @ionic/cli native-run cordova-res

### Create Project
> ionic start photo-gallery tabs --type=angular --capacitor

### Install PWA elements
> cd photo-gallery

> npm install @ionic/pwa-elements

### Run APP
> ionic serve

Deploy to mobile (Android):
> ionic build

> ionic cap add android

Every time you perform a build (e.g. ionic build) that updates your web directory
> ionic cap copy

Note: After making updates to the native portion of the code (such as adding a new plugin), use the sync command:
> ionic cap sync

### Then
> ionic cap open android

The above command will open Your android studio which should be installed before hand
From there, you can use Android studio to run the app on a device or emulator.
