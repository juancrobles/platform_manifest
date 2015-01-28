#AOSP SpeedModTeam

Initializing the source

(Assuming you have a valid build environment setup)

mkdir SpeedModTeam

cd ~/SpeedModTeam

repo init -u https://github.com/SpeedGroup/platform_manifest.git -b trebon_aosp

Sync the source

repo sync -jx -f (x being however many cpu jobs)

Getting ready to build

. build/envsetup.sh

Choose supported device to build

lunch aosp_trebon-eng

Now build it

mka otapackage

For quick dirty rebuilds


Credits

Google for AOSP
SimpleAosp
