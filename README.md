android-fingerprint-esp32

how to use Fingerprint scanner Android Mobile phone for a door unlock using ESP32 or ESP8266 Wifi or Arduino wifi module.For making this project you need ESP32, Relay module,Solenoid door lock and Android mobile phone

Create Android App
New Projects -> Empty Activity 
Configure Your Project <br>
Minimum SDK : API 27

Edit AndroidManifest main
<uses-permission android:name="android.permission.USE_BIOMETRIC"/>
<uses-permission android:name="android.permission.INTERNET"/> 
Edit App : build.gradle <br>
implementation 'androidx.biometric:biometric:1.0.0-alpha03'
 build.gradle 4.4.4 
 
