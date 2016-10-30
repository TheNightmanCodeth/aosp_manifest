# AOSP by TheNightman
This is the default manifest for my custom source-built AOSP rom.
For now it is exactly as I forked it, but it will be mine soon.

If you would like to build it yourself, you're in the right place!
Simply:

# Get the manifest
```
repo init -u https://github.com/TheNightmanCodeth/aosp_manifest.git -b android-7.1
```

# Add your device-specific repos to roomservice
`.repo/local_manifests/roomservice.xml`

#~~Bird~~ Sync Up
```
repo sync
```

# Wait

# Set up build environment
```
source build/envsetup.sh
```

# Choose your target
```
lunch aosp_hammerhead-userdebug
```

# Start build
```
make -j4
```

# Pray
