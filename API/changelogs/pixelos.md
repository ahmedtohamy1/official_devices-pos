# 20-Sept-2024
- Merged September security patches

# 20-Aug-2024
- Fixed PlayIntegrity *yet again*
- Improved variable refresh rate implementation
- New bootanimation from Pixel 9
- Fixed issues with secure window flags
- Fixed minimum delay between an app's notification sounds feature
- Fixed a SystemUI crash
- Further miscellaneous fixes and optimizations

# 29-July-2024
- Fixed Play Integrity once again
- Fixed a SystemUI crash caused by Heads up notifications
- Fixed an NPE with hiding ADB and developer setting status
- Fixed an issue where Annoying notifications reset on each reboot
- Added a toggle to force Carrier Aggregation
- Enabled the LTE+ icon

# 22-July-2024
- Merged July security patches
- Fixed RCS
- Fixed issues with Magic Eraser in Google Photos
- Fixed an issue where crash logs wouldn't upload
- Fixed an issue where face unlock would stop working
- Fixed an issue where high refresh rate wouldn't work on battery saver
- Fixed issues with annoying notifications
- Added a quick setting tile for Autobrightness
- Added an option to hide developer options status from other apps
- Added per-app volume control
- Added back the option for cloning apps
- Added an option for setting different ringtones for both sims
- Added configurable 0, 90, 180 and 270 degree rotation
- Implemented a check for builds which are not updatable

# 28-Jun-2024
- Merged the June security patch (QPR3)

# 11-May-2024
- Brought back Face unlock
- Brought back in-call vibrations
- Brought back Monet bootanimation
- Brought back long press volume key to skip tracks
- Brought back annoying notifications toggle
- Brought back missing USB tethering tile
- Brought back one shot auto brightness
- Fixed advanced reboot toggle
- Fixed bluetooth pairing issues on smartwatches and carplay
- Added missing drawable for quickly open camera gesture

# 17-Apr-2024
- Merged April Security patches
- Refreshed feature set (check blog [here](https://blog.pixelos.net/blogs/2024-04-16-April-Update))
- A lot of bugfixes since last release

# 16-Feb-2024
- Merged February Security patches
- Added expandable volume dialog
- Added in-call vibration options
- Added VPN over tethering/ hotspot
- Integrated link to windows
- Fixed an issue where some apks wouldn't install
- Fixed an issue where separate data and wifi tiles wouldn't work properly
- Fixed an issue where recording notification wouldn't dismiss on delete
- Fixed an issue where DT2S toggle wouldn't work
- Improved refresh rate settings
- Removed Power off alarm notification 
- Updated translations

# 17-Jan-2024
- Added Network traffic indicator
- Added auto-brightness button near brightness slider
- Ability to disable screenshot sounds
- Added extra options for screen recording
- Added new floating volume panel
- Added saner heads up for priority notifications only
- Added back missing NFC tile in quick settings
- System-wide Google sans font
- Rearranged additional sound settings
- Fixed an issue where Private Compute Services wouldn't update from the play store

# 22-Dec-2023
- Ability to disable QS battery estimates
- Ability to hide power menu on lock screen
- Ability to secure tiles from lock screen
- Added new clock faces from QPR1
- Added package name to installed app details
- Double tap to trigger doze
- Face Unlock from Paranoid Android
- High touch polling rate*
- Lineage Health Service*
- LiveDisplay Feature
- One shot AutoBrightness

Note: Recently Google has been taking a proactive approach to blocking fingerprints used to pass Play Protect checks. After trying to work around this, we've decided on a more user friendly approach of having the props in an overlay. This means it can be updated more seamlessly without the need to wait for updates every time a fingerprint is blocked.

# 19-Nov-2023 (Initial PixelOS 14 Release)
- Added the double tap to sleep gesture 
- Added support for window ignore secure
- Added Incall vibration options
- Added an option to allow disabling refresh rate lowering in battery saver 
- Added support for the strict standby policy
- Introduced cutout force full-screen
- Introduced burn-in protection for status/navbar
- Configurable 0, 90, 180 and 270-degree rotation 
- Require unlocking to use sensitive QS tiles 
- Added a Screen-off UDFPS toggle
- Make all user apps cloneable
