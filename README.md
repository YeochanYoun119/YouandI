# YouandI
<img src="https://github.com/YeochanYoun119/YeochanYoun119.github.io/blob/master/assets/images/UNI.jpg" alt="Youn and I app" width="300" height="500">
Android app for couples to privately share photos, chat, track visited places and plan events

# Feature

With this app, you can
- Chat with your partner in real time
- Add and share photos with partner
- Add events on calendar
- Count days of dating 
- Add markers on a map to see where you have visited with your partner

# How to use this source
Since this app uses Firebase and Google Map, you will need your own google API key. Please follow the steps below.

- Go to YouandI/app/src/main/AndroidManifest.xml
- Scoll down to meta data part
```
 <meta-data
            android:name="com.google.android.geo.API_KEY"
            android:value="Your API key"/>
        <meta-data
            android:name="com.google.android.gms.version"
            android:value="@integer/google_play_services_version" />
    </application>
```
- Replace 'Your API key' with your API
- Run the app
# Libraries
- [picasso](https://github.com/square/picasso) - for loading and caching images
- [glide](https://github.com/bumptech/glide) - for loading and caching images
