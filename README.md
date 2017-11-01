Copy Profile Add-on Firefox on Android
============================================

This add-on adds a "Copy Profile" menu item to your Firefox for Android menu,
which will copy your Firefox profile to your sdcard.

**The APIs this add-on uses are deprecated and it may stop working at any
time.** To get this development version to run, you need to be running Nightly
or a
local build and change:
- `xpinstall-signatures.required` to false **at your own risk**
- `extensions.legacy.enabled` to true

After hitting this menu item, to get your profile onto your desktop, run:
```
adb pull /sdcard/mozilla_profile [target directory]
```

Available on [addons.mozilla.org](https://addons.mozilla.org/en-US/android/addon/copy-profile/).
