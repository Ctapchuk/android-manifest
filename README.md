## Custom Android Manifest

This repo contains my own .repo/local_manifests/ that will be used to build twrp for Realme 6 Pro (codename RMX2061).
To replicate this work on your env; first, you must uses minimal-manifest-twrp as the main repo.
```
repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git -b twrp-11

```
then you can clone this repo directly to the .repo/local_manifests
```
git clone git://github.com/Ctapchuk/android-manifest -b android-11 .repo/local_manifests/
```
after that, you can start fetch the sources
```
repo sync --force-sync --no-tags --no-clone-bundle
```
