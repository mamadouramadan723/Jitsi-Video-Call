# Jitsi-Video-Call
## Error 
To avoid the error "Manifest merger failed : android:exported needs to be explicitly specified for element <service#org.jitsi.meet.sdk.ConnectionService>. Apps targeting Android 12 and higher are required to specify an explicit value for `android:exported` when the corresponding component has an intent filter defined."
set "targetSdk 30" in build.gradle file
