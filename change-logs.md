# Change-logs
## 10.  Dec 02, 2019
*Release status: beta-v10.4*
jro1979oliver - smartpack: fixes for build adreno idler
sunilpaulmathew - devfreq: enable adreno_idler
linckandrea - adreno_idler: clean-up and enable it by default
Joe Maples - adreno_idler: Declare display_on correctly
Joe Maples - adreno_idler: Add display state awareness
Joe Maples - adreno idler: Ramp down more agressively
arter97 - adreno_idler: fix typos :)
arter97 - adreno_idler: fix-up some comments
arter97 - adreno_idler: fix-up type definitions
arter97 - adreno_idler: remove frequency bump
arter97 - adreno_idler: switch to count based instead of time based
arter97 - Introduce Adreno idler for devfreq-based Adreno devices
jro1979oliver - Revert "Added support for Adreno IDLER"
jro1979oliver - smartpack: up a tag
Sultan Qasim Khan - msm8916: Mild undervolt
Sultan Qasim Khan - msm8939: mild undervolt for heat reduction
jro1979oliver - Revert "cpuset: Add allow_attach hook for cpusets on android."

## 9. Oct 13, 2019
*Release status: beta-v9*
Changes: Compatible with Oreo, Pie and Q. Added memfd backports.Compiled with kernel toolchain 8.3-2019.03 

## 8. Feb 01, 2019
*Release status: beta-v8*
Changes: Updated & enabled cpusets. Some commit to improving memory management. 

## 7. Jan 19, 2019
*Release status: beta-v7*
Changes: Implemented interface to configure Linux PrintK logging. GPU: msm_adreno_tz: added adrenoboost (3 levels of boosting). Removed buggy features like Intelli thermal, MSM limiter, Adreno Idler etc. Wakelocks: cleanups and updated the list of default blocked wakelocks.

## 6. Jan 10, 2019
*Release status: beta-v6*
Changes: Added a bunch of *kgsl* commits to improve the GPU performance. SmartPack boot script: Tweaked Alucard hotplug, impulse CPU Freq  gov and more (credits @DanGLES3).

## 5. Dec 31, 2018
*Release status: beta-v5*
Changes: Added I/O schedule switcher, a driver to change the I/O scheduler when the screen turns off. CPU Govs: Added Chill & Adaptive. CPU: Added MSM Limiter driver v5.3. MSM Thermal: Added IntelliThermal v3.1. binder: some patches suggested by @DanGLES3. SmartPack boot script: a bunch of updates (credits mainly to @DanGLES3). Misc: set westwood as the default tcp. Misc. Update wireguard. Bunch of other changes. Please check my Github source for more info.

## 4. Dec 27, 2018
*Release status: beta-v4*
Changes: Unified to work on both Oreo& Pie. Incorporating recent patches from osm0sis's AnyKernel2 repo. Ramdisk: removed spectrum support and added SmartPack boot script. Misc changes.

## 3. Oct 15, 2018
*Release status: beta-v3*
Changes: thermal: msm_thermal: Added advanced parameters. cpufreq: Added tripndroid & Impulse govs. cpufreq: implement zen-tune v4.10 for Ondemand gov. fs: added sdFAT file system. A lot of optimizations and patched for everywhere to make the kernel much snappier.

## 2. Sep 07, 2018
*Release status: beta-v2*
Changes: Add control over Min Display Backlight. Added Interactive Pro, Pegasusq Yankactive & Alucard Governers. Add MSM Sleeper CPU Hotplug. Add OS check to the anykernel script so that it won't be installed on any android version except Android 8.1.0 (Oreo).

## 1. Aug 27, 2018
*Release status: beta-v1*
The very first release for Moto G3 2015 running Lineage OS 15.1 (Android 8.1.0).
Based on the [source code](https://github.com/MOTO-M8916/kernel_motorola_msm8916).
