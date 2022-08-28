# [Jitsi Video Call ](https://jitsi.github.io/handbook/docs/intro)
## Error 
To avoid the error "Manifest merger failed : android:exported needs to be explicitly specified for element <service#org.jitsi.meet.sdk.ConnectionService>. Apps targeting Android 12 and higher are required to specify an explicit value for `android:exported` when the corresponding component has an intent filter defined."
set "targetSdk 30" in build.gradle file when we have #implementation ('org.jitsi.react:jitsi-meet-sdk:2.9.0') { transitive = true }#
