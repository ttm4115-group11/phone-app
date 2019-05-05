# Phone app

Phone App developed in native Java for Android devices. The app features a map of Trondheim with a set of markers corresponding to smart bike racks. When a marker is clicked a reservation in that bike rack is made for the user. 

## Run the app
This repository does not contain an APK, so the app must be built. To do so, follow these steps: 
* Install [Android Studio](https://developer.android.com/studio)
* This app makes use the Google Maps API. To use the API you need to configure an API-key. Follow [these steps to set up your own API key](https://developers.google.com/maps/documentation/embed/get-api-key)
* The markers for the map is served by the webserver in this [repository](https://github.com/ttm4115-group11/webserver). So to get any markers, the servers needs to be running. Remember to point the app the IP where the server is hosted. 

After these steps, the app should be good to go. Configure either an Android emulator (with google maps installed), or you can use you own android device. 
