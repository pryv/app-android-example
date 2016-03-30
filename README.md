# Android sample app

Android skeleton to build an app that will access your data on pryv.io using the [Pryv Java library](https://github.com/pryv/lib-java)

This sample app contains the code that provides the login to your pryv account on the platform that you will have defined [here](https://github.com/pryv/app-android-example/blob/master/app/src/main/java/com/pryv/appAndroidExample/activities/LoginActivity.java#L39).
For example, when using the pryv.me demo platform:

```java
public final static String DOMAIN = "pryv.me";
```

After signing in your account the app fetches the 20 most recent Events, the Stream structure and allows to create a note on the push of a button.

## Usage

get the code `git clone https://github.com/pryv/android-app-example`

### Android studio

To use the skeleton app in Android Studio, go to `File>open` and select the folder that was generated by the `git clone`. Now run in on your emulated device or Android phone.

### Eclipse

[Request it](mailto:tech@pryv.com)

## License

[Revised BSD license](https://github.com/pryv/documents/blob/master/license-bsd-revised.md)
