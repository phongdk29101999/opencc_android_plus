# opencc_android
[OpenCC](https://github.com/BYVoid/OpenCC) binary package for opencc_flutter_ffi plugin.

Current version is `1.1.4`.

[![](https://jitpack.io/v/dolphinxx/opencc_android.svg)](https://jitpack.io/#dolphinxx/opencc_android)

It does not contain JNI bindings or any other code, just the native libraries for dlopen.

To depend on this, add jitpack in your root build.gradle at the end of repositories:

```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

and add the dependency:

```
dependencies {
  implementation 'com.github.dolphinxx:opencc_android:0.0.3'
}
```
