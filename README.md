# Android_Firebase_Authentication
User authentication in android app using firebase with all authentication methods and auto signout functionality.

To implement firebase authentication wee need to add library in our android app. In build.app(Module:app) file add below line in dependencies.
and then sync project.
```
implementation 'com.google.firebase:firebase-auth:16.2.0'
```
Add below line of code below dependencies in your build.gradle(Module:App) file.
```
apply plugin: 'com.google.gms.google-services'
```

Add below line of code below dependencies in your build.gradle(Project) file.
```
classpath 'com.google.gms:google-services:4.0.1'
```

You also need to create a project in firebase console. to connect your firebase project with your android app you can simply follow steps given by firebase.
In your android app you need to allow Internet permission. You can do it by adding below single line of code in your android menifest file.
```
<uses-permission android:name="android.permission.INTERNET" />
```

By following above code you get connected with your firebase project. Now to create firebase authentication in your app you can simply follow code of this app.
This app allows users to sign up, login, forget password, and change password activities. moreover it also allows users to implement auto signout in application.


Icons in this application has been taken from www.flaticon.com you can also see their multiple icons and can download as well.
