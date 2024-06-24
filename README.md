# download:

     repo init -u https://android.googlesource.com/platform/manifest -b android-8.1.0_r52

copy manifest to .repo/local_manifests

     repo sync --force-sync
     
After that, if there are any errors use this command

     repo sync -j1 --fail-fast

credits:
[Decatf](https://github.com/decatf/)
