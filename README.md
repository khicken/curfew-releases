# Curfew

Curfew locks your Mac, Windows PC, or Android phone during your bedtime.

You can still unlock it. But you must write at least 50 words explaining why.

Every override shows on your public page at `kalebkim.com/sleep/<handle>`. Your friends can see when you broke your own curfew, and what you said.

## Download

These links always point to the newest stable release.

- [Curfew for macOS (.dmg)](https://github.com/khicken/curfew-releases/releases/latest/download/Curfew-macOS.dmg)
- [Curfew for Windows (.exe)](https://github.com/khicken/curfew-releases/releases/latest/download/Curfew-Windows-Setup.exe)
- [Curfew for Android (.apk)](https://github.com/khicken/curfew-releases/releases/latest/download/Curfew-Android.apk)

All versions are on the [Releases page](https://github.com/khicken/curfew-releases/releases).

## Install

Curfew is not signed with a paid developer certificate. Your system will warn you the first time. This is expected. Follow the steps for your system.

### macOS

1. Open the `.dmg`. Drag Curfew to Applications.
2. Open Curfew once. macOS will block it.
3. On macOS Sequoia or newer, go to System Settings > Privacy & Security. Scroll down and click **Open Anyway**.
4. Confirm. Curfew now opens normally.

You can also skip steps 2 and 3. Run this in Terminal instead:

```
xattr -dr com.apple.quarantine /Applications/Curfew.app
```

### Windows

1. Run `Curfew-Windows-Setup.exe`.
2. If SmartScreen says "Windows protected your PC", click **More info**.
3. Click **Run anyway**.
4. Finish the installer.

### Android

1. Open the `.apk` on your phone.
2. Android will ask you to allow installs from this source. Turn on **Allow from this source**.
3. On Android 13 or newer, Android blocks accessibility for apps installed this way. Fix this first:
   - Open Settings > Apps > Curfew (App info).
   - Tap the three dots (⋮) at the top right.
   - Tap **Allow restricted settings**.
4. Now open Curfew and enable its accessibility service when it asks.

## Limits

Curfew is not a hard lock. It is a speed bump that makes you think. You can get around it. For example:

- On Windows, Ctrl+Alt+Del still works.
- Safe mode skips Curfew.
- You can uninstall Curfew outside your bedtime window.

That is by design. Curfew relies on honesty and a public record, not force.

## Updates

`latest.json` on each release lists the version and download links for each platform.
