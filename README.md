# KoombeaChallengeMobile
This project was made to measure my abilities automating a requirement for Koombea, the project needed to be on a "page object model" format, and also needed the use of cucumber, however that last part has not been done yet, instead the project is currently using TestNG which will be replaced in future updates. 

## Prerequisites 
Besides this project, you will need to setup your local environment with the following:
* Android Studio.
* IntelliJ (or other IDE).
* Set the JAVA_HOME environment variable for the Java SDK.
* Set the ANDROID_HOME environment variable for the Android SDK.

## Configuration required to run the project
Before you start executing the test cases, you will need to:
* Create an android emulador with your desire capabilities.
* Change the current capabilities on the LenghtTestCase.java for the ones corresponding to your emulator, and also add your local Path to the project on the "app" section of the capabilities.

```
        cap.setCapability("platformName", "android");
        cap.setCapability("platformVersion", "11");
        cap.setCapability("deviceName", "emulator-5554");
        cap.setCapability("app","[Add local Path to the project]\\KoombeaAutov2\\src\\main\\resources\\PreciseUnitConversion.apk");
```

