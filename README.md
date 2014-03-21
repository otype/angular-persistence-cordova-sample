# angular-persistence-cordova-sample

This is a sample [AngularJS](http://angularjs.org/) project showing the usage of the Cordova support ([persistence.store.cordovasql.js](https://github.com/otype/persistencejs/blob/cordovasupport/lib/persistence.store.cordovasql.js)) in [persistencejs](https://github.com/zefhemel/persistencejs) when writing mobile apps in [Cordova](https://cordova.apache.org/).

With the Cordova support, we are able to take advadvantage of the [Cordova SQLitePlugin](https://github.com/brodysoft/Cordova-SQLitePlugin) if it is loaded. If not, it will automatically fall back to [Cordova WebSQL](http://docs.phonegap.com/en/edge/cordova_storage_storage.md.html#Storage).
