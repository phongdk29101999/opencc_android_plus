# opencc_android
[OpenCC](https://github.com/BYVoid/OpenCC) binary package for opencc_flutter_ffi plugin.

Current version is `1.1.4`.

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
  implementation 'com.github.phongdk29101999:opencc_android_plus:1.0.0'
}
```
