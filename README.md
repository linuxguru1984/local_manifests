# Download:
    repo init -u https://github.com/LineageOS/android.git -b lineage-20.0 --git-lfs
    git clone https://github.com/linuxguru1984/local_manifests.git .repo/local_manifests -b lineage-20-a33x
    repo sync -j1
# Zram(recommended):
    sudo apt install zram-tools
    echo -e "ALGO=zstd\nPERCENT=90" | sudo tee -a /etc/default/zramswap
    sudo systemctl restart zramswap
# Build:
    . build/envsetup.sh
     lunch lineage_a33x-userdebug
     mka bacon -j1

credits: [Samsung Exynos 1280 devs](https://github.com/s5e8825)
