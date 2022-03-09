# WEED OS  #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/weedos-project/manifest -b 12

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```




### Build ###

```bash

# Set up environment
$ source build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ make bacon -jX
```

Credits
-------
* [**Project Arcana**](https://github.com/projectarcana-aosp)
* [**AOSPExtended**](https://github.com/AospExtended)
* [**ProtonAOSP**](https://github.com/ProtonAOSP)
* [**GrapheneOS**](https://github.com/GrapheneOS)
* [**OctaviOS**](https://github.com/Octavi-OS)
* [**SparkOS**](https://github.com/Spark-rom)
* [**ProjectXtended**](https://github.com/Project-Xtended)
* [**PixelExperience**](https://github.com/PixelExperience)
* [**AOSP-Krypton**](https://github.com/AOSP-Krypton)
* [**exTHmUI**](https://github.com/exthmui)
* [**YAAP**](https://github.com/yaap)
* [**Evolution-X**](https://github.com/Evolution-X)
* [**ProjectRadiant**](https://github.com/ProjectRadiant)
* [**ProjectStreak**](https://github.com/ProjectStreak)
* [**WaveOS**](https://github.com/)
* [**Descendant-XI**](https://github.com/Descendant-XI)


