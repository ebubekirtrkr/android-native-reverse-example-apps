# Android Native Library Examples

## Useful Links
* Mobil Zararlı Analizi - Bölüm 1: Ortamı Kuralım  | TR [Link](https://eybisi.run/Mobil-Zararli-Analizi-Bolum-1-Ortami-Kuralim/)
* Android App Reverse Engineering 101- Section 5 | EN [Link](https://maddiestone.github.io/AndroidAppRE/reversing_native_libs.html)
* Add JNI(C/C++) into your existing Android app | EN [Link](https://erev0s.com/blog/add-jnicc-your-existing-android-app/)
* How to hook Android Native methods with Frida (Noob Friendly) | EN [Link](https://erev0s.com/blog/how-hook-android-native-methods-frida-noob-friendly/)
* Frida Android Native Library Hooking | [Link](https://berkayyildiz.com/frida-android-native-library-hooking/)
* JNIEnv Struct offsets spreadsheet | EN [Link](
https://docs.google.com/spreadsheets/d/1yqjFaY7mqyVIDs5jNjGLT-G8pUaRATzHWGFUgpdJRq8/edit?usp=sharing)
* JNI Functions Oracle | EN [Link](https://docs.oracle.com/javase/7/docs/technotes/guides/jni/spec/functions.html)
* JNIEnv gdt file for Ghidra | EN [Link](https://github.com/Ayrx/JNIAnalyzer/blob/master/JNIAnalyzer/data/jni_all.gdt)


## Example Apps
| App Name    | App Link | Source | Write Up |
|   :----:    |    :----:   | :----:  |:----: |
|Ololo County Checker  | [Ololo County Checker] | CTFZone 2018 | [Ololo County Checker Write-up] |
|My Backdoored Gallery  | [My Backdoored Gallery] | Aperi CTF 2019 | [My Backdoored Gallery Write-up] |
|DroidCoinStealer  | [Droid Coin Stealer] | DroidCon, SEC-T CTF 2019 | [Droid Coin Stealer Write-up] |
|MediaCode| [Media Code] | AndroidAppRE - Exercise 5 | [Media Code Solution] |
|HDWallpaper| [HD Wallpaper] | AndroidAppRE -Exercise 6 | [HD Wallpaper Solution] |


[Ololo County Checker]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/raw/master/CTFZone_2018/android_ololo_country_checker/ololo.s.apk
[Ololo County Checker Write-up]: https://eybisi.run/CTFZone-2018-android-ololo-country-checker/


[My Backdoored Gallery]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/raw/master/Aperi_CTF_2019/My_Backdoored_Gallery/mygallery.apk
[My Backdoored Gallery Write-up]: https://www.aperikube.fr/docs/aperictf_2019/my_backdoored_gallery/

[Droid Coin Stealer]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/raw/master/DroidCon_SEC-T_CTF_2019/DroidCoinStealer/DroidCoinStealer.apk
[Droid Coin Stealer Write-up]: https://anee.me/droidcon-sec-t-ctf-2019-d796be91bb3f

[Media Code]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/raw/master/AndroidAppRE/samples/Mediacode.apk
[Media Code Solution]: https://maddiestone.github.io/AndroidAppRE/reversing_native_libs.html#exercise-5---find-the-address-of-the-native-function

[HD Wallpaper]: https://github.com/ebubekirtrkr/android-native-reverse-example-apps/raw/master/AndroidAppRE/samples/HDWallpaper.apk
[HD Wallpaper Solution]: https://maddiestone.github.io/AndroidAppRE/reversing_native_libs.html#exercise-6---find-and-reverse-the-native-function