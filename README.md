# Blur_xiomi_Emerald
Some ways to release blur on M6 pro 4g/ Note 13 Pro 4g


# First we have the non-root option:
In the middle without root we will use the Adb command to disable the overlay that contains the blur lock, however, there will still be no fingerprint unlock animation and animation when connecting the charger. 
# Command to disable it with Adb:
adb shell pm uninstall --user 0 com.miui.systemui.devices.overlay

# However, we have a root version that doesn't sacrifice anything and works perfectly.

(It will be in the release section as a module for magisk / ksu / aptch)
