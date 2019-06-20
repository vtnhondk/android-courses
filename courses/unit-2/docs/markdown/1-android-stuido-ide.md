![CorssTech](../../../assets/ic-cross-tech.png "CrossTech")

# AndroidMainifest.xml

Original docs: [Meetup Android Studio](https://developer.android.com/studio/intro "AndroidStuido")

``` xml
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
          package="dev.nxonxon.examples">
    <application
            android:allowBackup="false"
            android:icon="@mipmap/ic_launcher"
            android:label="@string/app_name"
            android:roundIcon="@mipmap/ic_launcher_round"
            android:supportsRtl="true"
            android:theme="@style/AppTheme">

        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN"/>
                <action android:name="android.intent.action.VIEW"/>
                <category android:name="android.intent.category.LAUNCHER"/>
            </intent-filter>
        </activity>
    </application>
</manifest>
```