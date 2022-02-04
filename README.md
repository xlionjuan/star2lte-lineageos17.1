# star2lte-lineageos17.1
I build SAMSUNG Galaxy S9+ (Exynos)'s LineageOS 17.1 (Android 10)
## Why I did this things?
Because the offcial LineageOS build for Exynos 9810 isn't continued. But I still want to install LineageOS.<br>
Samsung OneUI's performance sucks, I love it and I hate too, because it is too laggy and stuck very often.
## Why Android 10 or why not using Android 11 or 12?
Because you can found out some people on XDA are working on it. And they're more professional.<br>
I wanna tried LineageOS 18 before, but it has too many strange problem cause I can't running very well.
## What's Works
Almost everything except **VoLTE** and **Iris Scanner**.<br>
But sadly the Samsung Camera has depend on OneUI's framwork, so the qualty of camera sucks. And the video recording only up to **4k30fps**
## How to bypass SafetyNet and using Google Pay?
You need to install [Magisk](https://github.com/topjohnwu/Magisk) first. And these two modules:<br>
* [Universal SafetyNet Fix](https://github.com/kdrag0n/safetynet-fix) (**NO** Setup is required)
* [MagiskHide Props Config](https://github.com/Magisk-Modules-Repo/MagiskHidePropsConf) (Setup is required, follow the instructions in this repository)
## Some strange things or something magical
* The temperature limit of processor has gone! So I can play Genshin Impact on lowest setting
* You can QuickCharge your device even if your screen is on (Temperature protection of battery still exits, don't worry)
* The speaker's loudest volume is more louder than Official ROM
* You may notice LineageOS noticed you the system is using public key, this is because I didn't signing the builds, just ignore<br><br>
~HaveFun~
## How I build this?
I follow the [LineageOS's Wiki](https://wiki.lineageos.org/devices/star2lte/build) to build this things.
But when you doing this step you'll find out some errors occured.
```
source build/envsetup.sh
breakfast star2lte
```
This is because it can't find suitable "Vandor" to build.<br>
The solution is to find the same model's LineageOS's installtion package (And should be the same version you wanna build).<br>
(You can use my package) <br>
Than follow [this Guide (Extracting proprietary blobs from LineageOS zip files)](https://wiki.lineageos.org/extracting_blobs_from_zips)<br>
~Sorry that I can't remember where I download the LineageOS to extracting proprietary blobs~<br>
~I just Google~
# 
Unnnn.....You'll found out I didn't doing anything ~I just good at using Google~<br>
So I don't have the ability to modify the Kernal or the OS... I just run the code, and it works. <br>
So don't ask me the question too technical, English or Chinese is ok.
# How often will I upload the updates?
When I'm free
# My building environment
Ubuntu 20.04 LTS on VMware, give it 8 cores processors and 16GB os RAM, and you **should** allocate some SWAP for your VM, or you'll encounter ***run out of memory*** error.<br>
You may encounter ***run out of memory*** if you has less then 16GB RAM, even if you allocate a lots of SWAP (Yeah I tried this stupid things before)
# 
Host machine equipment :<br>
i5-12400 and 32GB RAM<br>
Others doesn't matter.
