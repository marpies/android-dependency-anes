# Android dependency ANEs (GooglePlayServices, Android Support v4)

Repository with extensions that package JAR libraries required by multiple extensions.

## AIR SDK note

Including these extensions in your app increases the number of method references that must be stored in Android dex file. AIR currently supports a single dex file and since the number of such references is limited to a little over 65k, it is possible to exceed the limit by including several native extensions. This will prohibit you from building your app for Android, unless you reduce the number of features the app provides. Please, leave a vote in the report below to help adding multidex support to AIR SDK:

* [Bug 4190396 - Multidex support for Adobe AIR](https://bugbase.adobe.com/index.cfm?event=bug&id=4190396)

## Versions

* Google Play Services `v9.4.0`
* Android Support `v24.0.0`