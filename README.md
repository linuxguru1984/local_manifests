# download:

     repo init -u https://android.googlesource.com/platform/manifest -b android-8.1.0_r52

     git clone https://github.com/alexoid1linuxoid/local_manifests.git .repo/local_manifests -b aosp-8.1.0_p4

     repo sync --force-sync
     
After that, if there are any errors use this command

     repo sync -j1 --fail-fast

credits:
[Decatf](https://github.com/decatf/)
