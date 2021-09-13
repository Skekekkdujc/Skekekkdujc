Start app Ads



App Components
<provider
android:name="com.startapp.sdk.adsbase.StartAppInitProvider"
android:authorities="YourAppId.startappinitprovider"
android:exported="false" />
    <activity
android:name="com.startapp.sdk.adsbase.consent.ConsentActivity"
android:configChanges="orientation|screenSize|screenLayout|keyboardHidden" android:theme="@android:style/Theme.Translucent"/>
<activity
 android:name="com.startapp.sdk.ads.list3d.List3DActivity"
 android:theme="@android:style/Theme"/>
 <activity
android:name="com.startapp.sdk.adsbase.activities.OverlayActivity"
android:configChanges="orientation|screenSize|screenLayout|keyboardHidden"
 android:theme="@android:style/Theme.Translucent"/>
<activity
android:name="com.startapp.sdk.adsbase.activities.FullScreenActivity"
android:configChanges="orientation|screenSize|screenLayout|keyboardHidden"
android:theme="@android:style/Theme"/>
<service android:name="com.startapp.sdk.adsbase.InfoEventService" />
 <service
    android:name="com.startapp.sdk.adsbase.PeriodicJobService"
    android:permission="android.permission.BIND_JOB_SERVICE" />
    <receiver android:name="com.startapp.sdk.adsbase.remoteconfig.BootCompleteListener">
      <intent-filter>
      <action android:name="android.intent.action.BOOT_COMPLETED"/>
      </intent-filter>
    </receiver>





Import


com.startapp.sdk.ads.banner.*;
import com.startapp.sdk.adsbase.*; 
import com.startapp.sdk.adsbase.adlisteners.*
