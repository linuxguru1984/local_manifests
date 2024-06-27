# download:

     repo init -u https://android.googlesource.com/platform/manifest -b android-8.1.0_r52

     git clone https://github.com/alexoid1linuxoid/local_manifests.git .repo/local_manifests -b aosp-8.1.0_p4

     git config --global http.version HTTP/1.1

     repo sync 
     
# build:

     . build/envsetup.sh
     lunch p4wifi-userdebug
     mka bacon -j2
     
credits:
[Decatf](https://github.com/decatf/)
