#AOSP SpeedModTeam

Initializing the source


mkdir SpeedMod

cd ~/SpeedMod

repo init -u https://github.com/SpeedGroup/platform_manifest.git -b trebon_aosp

Sync the source

repo sync -j4 

Getting build

. build/envsetup.sh && lunch aosp_trebon-user

make otapackage

Credits

Google for AOSP
SimpleAosp
