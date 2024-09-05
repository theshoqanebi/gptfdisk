# gptfdisk
## build for android
[**1. Download ndk**](https://developer.android.com/ndk/downloads):
Download ndk and extract zip file

**2. build**
```
make -f  Makefile.android NDK=~/toolchain/android-ndk-r27 TARGET=aarch64-linux-android API=33
```
**✔️ Target Options**: Choose base on your android architecture

aarch64-linux-android

armv7a-linux-androideabi

i686-linux-android

x86_64-linux-android

**✔️ API**

Change base on your android version 24<=
