# AndroidSystemBlur
Library to provide easy access to cross-window blur platform API on Android 12 and above.
On older versions fallback to solid background

# Limitations
The AOSP [BackgroundBlurDrawable](https://github.com/aosp-mirror/platform_frameworks_base/blob/master/core/java/com/android/internal/graphics/drawable/BackgroundBlurDrawable.java) implementation can only blur the content behind the window, but not content inside it.

Device must ship with ro.surface_flinger.supports_background_blur=1 to support blur effects

# TODO
- Window content blur implementation
