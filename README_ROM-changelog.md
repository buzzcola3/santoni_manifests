# santoni_manifests
modified repo manifests for POSP santoni
1. repo init -POSP sources-
2. repo sync -POSP sources-
3. replace included files in .repo with these files
4. repo sync again
5. . build/envsetup.sh
6. brunch potato_santoni-userdebug
7. enjoy

ROM changelog (same as crDroid, made by Jabieff):

===== 2021.05.20 =====
- Updated blobs from LA.UM.9.6.2.r1-04200-89xx.0
- Updated more QMI blobs from LA.UM.9.6.2.r1-04200-89xx.0
- Updated Mapper & Allocator from LA.UM.9.6.3.r1-01700-89xx.0
- Added sound gain control feature (Settings/Sound)
- Increased incall volume level
- Selinux: Address denials
- Kernel: 4.9.268 - LA.UM.9.6.2.r1-04200-89xx.0 (clang 12.0.5)
- Reverted back Mapper and Allocator from LA.UM.9.6.2.r1-04600-89xx.0
- Reverted back GPS blobs from LA.UM.9.6.2.r1-04100-89xx.0
- Fixed HAL3 front camera issue
- Misc. Fixes and Improvements

===== 2021.04.15 =====
- Merged April patch
- Updated blobs from LA.UM.9.6.2.r1-04100-89xx.0
- Updated Widevine and aptX blobs from Nokia/DPL_sprout:11
- Updated perf configs from Nokia/DPL_sprout:11
- Updated prebuilt biometrics blobs
- Updated dalvik values
- Updated audio configs
- Restored back perf blobs from LA.UM.8.6.2.r1-08600-89xx.0
- Restored back old thermal config
- Enabled FUSE for default
- Added Lineage LiveDisplay support
- Added WiFi MAC Randomization support
- Removed useless blobs and configs
- Removed sound_trigger support
- Selinux: Address denials
- Kernel: 4.9.266 - LA.UM.9.6.2.r1-04200-89xx.0 (clang 12.0.4)
- Misc. Fixes and Improvements
- ZRAM set to 512mb
