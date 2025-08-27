# ArcGIS Maps SDK for Flutter Samples - Case #03982075

- Checkout repository
- Run: `dart tool/initialize.dart`
- Create env.json with an API_KEY 
- Run the 'Custom Sample' Configuration on Android
- Allow Notifications

Actual behaviour:
- You see a Notification with the text `Example app 2 will continue to receive...`.

Expected behaviour:
- You see a Notification with the text `THIS WILL ALSO BE OVERWRITTEN BY THE ARCGIS SDK`
- or you can set the text as a parameter in the `_locationDataSource.enableBackgroundLocationUpdates()` function