# download:

     repo init -u https://android.googlesource.com/platform/manifest -b android-8.1.0_r52

     git clone https://github.com/alexoid1linuxoid/local_manifests.git .repo/local_manifests -b aosp-8.1.0_p4

     repo sync -j1
     
# build:

     . build/envsetup.sh
     lunch p4wifi-userdebug
     mka bacon
     
credits:
[Decatf](https://github.com/decatf/)
