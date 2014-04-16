FotorSDK-android
================
FotorSDK is a complete set of photo editing tools comes standard in Fotor's all-platform SDK. You can select the tools that are best for your app, or use them all.

Get more info and downloads of FotorSDK (for iOS and Android) via the [FotorSDK mobile portal](https://github.com/Fotor)

[Click here for official documentation for FotorSDK-android](https://github.com/Fotor)


Installing
----------------

* Link FotorSDK library project with eclipse  <br />
  Import FotorSDK-android library project in your eclipse workspace <br / >

  Right click on your Android project root directory, select `Properties` -> `Android`, Click `Add..` button to choose FotorSDK library project which your imported previously.

* Manual link library <br /> 
  Add the following code to your application project.properties <br />

``` java

android.library.reference.1=../FotorSDK

```
  NOTE: if your project.properties file was contained `android.library.reference.1` <br />
  you must changed to another number  e.g. android.library.reference.2<br/>
  `../FotorSDK` is the FotorSDK-android library project path




