## Project_Atlas
 kernel-level tweaks by 🍉 for the best build.prop enhancements!

## What it does to build prop:

 ```bash
 # Rendering Tweaks
debug.composition.type=c2d
debug.egl.hw=1
debug.enabletr=true
debug.overlayui.enable=1
debug.qctwa.preservebuf=1
debug.performance.tuning=1
debug.sf.hw=1
dev.pm.dyn_samplingrate=1
hw3d.force=1
ro.config.disable.hw_accel=false
ro.fb.mode=1
ro.sf.compbypass.enable=0
ro.vold.umsdirtyratio=20
persist.sys.composition.type=c2d
persist.sys.ui.hw=1
video.accelerate.hw=1

# Allow purge of assets to free more ram
persist.sys.purgeable_assets=1
dalvik.vm.dexopt-flags=m=y
persist.sys.purgeable_assets=1
persist.service.pcsync.enable=0
persist.service.lgospd.enable=0

# Increase general Performance
debug.performance.tuning=1
ro.secure=0
persist.sys.use_16bpp_alpha=1
ro.product.gpu.driver=1
ro.min.fling_velocity=8000

# Better Scrolling responsiveness and speed
windowsmgr.max_events_per_sec=150
ro.max.fling_velocity=12000
ro.min.fling_velocity=8000
ro.min_pointer_dur=8

# Smoothens UI
persist.service.lgospd.enable=0
persist.service.pcsync.enable=0
ro.ril.enable.a52=1
ro.ril.enable.a53=0

# Smoother video streaming and tweak media
media.stagefright.enable-player=true
media.stagefright.enable-meta=true
media.stagefright.enable-scan=true
media.stagefright.enable-http=true
media.stagefright.enable-aac=true
media.stagefright.enable-qcp=true
media.stagefright.enable-record=true

# Disable Error reporting and logs
profiler.force_disable_err_rpt=1
profiler.force_disable_ulog=1

# Disable Sending Usage Data
ro.config.nocheckin=1
logcat.live=disable

# Touch 
peak_refresh_rate=60-120
user_refresh_rate=60-120
touch.pressure.scale=0.001
af.resampler.quality=255
```
## How to install:
 1. Download the latest release according to your phones display `refreshrate`
 2. Flash in Magisk.
 3. Done and *profit.



