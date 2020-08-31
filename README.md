# Android Native Library Examples

## Useful Links
* Android App Reverse Engineering 101- Section 5 | [Link](https://maddiestone.github.io/AndroidAppRE/reversing_native_libs.html)
* Add JNI(C/C++) into your existing Android app | [Link](https://erev0s.com/blog/add-jnicc-your-existing-android-app/)
* How to hook Android Native methods with Frida (Noob Friendly) | [Link](https://erev0s.com/blog/how-hook-android-native-methods-frida-noob-friendly/)
* Frida Android Native Library Hooking | [Link](https://berkayyildiz.com/frida-android-native-library-hooking/)
* JNIEnv Struct offsets spreadsheet | [Link](
https://docs.google.com/spreadsheets/d/1yqjFaY7mqyVIDs5jNjGLT-G8pUaRATzHWGFUgpdJRq8/edit?usp=sharing)
* JNI Functions Oracle | [Link](https://docs.oracle.com/javase/7/docs/technotes/guides/jni/spec/functions.html)


## Example Apps
| App Name    | App Link | Source | Write Up |
|   :----:    |    :----:   | :----:  |:----: |
|My Backdoor  | [My Backdoor] | Aperi CTF 2019 | [My Backdoor Write-up] |
|DroidCoinStealer  | [Droid Coin Stealer] | DroidCon, SEC-T CTF 2019 | [Droid Coin Stealer Write-up] |
|MediaCode| [Media Code] | AndroidAppRE - Exercise 5 | [Media Code Solution] |
|HDWallpaper| [HD Wallpaper] | AndroidAppRE -Exercise 6 | [HD Wallpaper Solution] |

[My Backdoor]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/blob/master/Aperi_CTF_2019/My_Backdoored_Gallery/mygallery.apk
[My Backdoor Write-up]: https://www.aperikube.fr/docs/aperictf_2019/my_backdoored_gallery/

[Droid Coin Stealer]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/blob/master/DroidCon_SEC-T_CTF_2019/DroidCoinStealer/DroidCoinStealer.apk
[Droid Coin Stealer Write-up]: https://anee.me/droidcon-sec-t-ctf-2019-d796be91bb3f

[Media Code]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/AndroidAppRE/Mediacode.apk
[Media Code Solution]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/blob/master/AndroidAppRE/samples/Mediacode.apk

[HD Wallpaper]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/blob/master/AndroidAppRE/samples/HDWallpaper.apk
[HD Wallpaper Solution]: https://maddiestone.github.io/AndroidAppRE/reversing_native_libs.html#exercise-6---find-and-reverse-the-native-function