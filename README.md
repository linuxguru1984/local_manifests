# Download:
    repo init -u https://github.com/LineageOS/android.git -b lineage-20.0 --git-lfs
    git clone https://github.com/alexoid1linuxoid/local_manifests.git .repo/local_manifests -b lineage-20-a33x
    repo sync --force-sync -j1
# Build:
    . build/envsetup.sh
     lunch lineage_a33x-userdebug
     mka bacon

credits: [Samsung Exynos 1280 devs](https://github.com/s5e8825)
