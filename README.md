# android_manifest

In this page, we assume that <ANDROID_TOP> is the top level folder for your Android environment. e.g.:
```
$ mkdir <ANDROID_TOP>
$ cd <ANDROID_TOP>
```
Then run:
```
$ repo init -u https://android.googlesource.com/platform/manifest -b master
$ git clone https://github.com/johnstultz-work/android_manifest.git .repo/local_manifests -b master
$ repo sync -j$(nproc)
```
Then build AOSP
