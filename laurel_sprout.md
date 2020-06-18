

TEST BUILD FOR OTA
=======================
     2020/06/18
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

02c10509fe3 Revert "FODCircleView: Add support for pressed fod layer"
6c6f4cb2ff4 Revert "FODCircleView: account for notch hide"
31283117b68 SystemUI: StatusBarWindowView: Double tap for ambient display improvements
195cfcbc08e SystemUI: use DOUBLE_TAP_TO_WAKE setting also for wake from aod
6c2580cba66 base: Double tap to trigger doze [1/2]
7342d9eb66a fwb: Import missing variables
25cdd87edf2 Allow tuning extra padding for status bar
d0103d94dec Force Expanded Notifications [1/2]
4aac1ece896 Less boring heads up option: always show alarm clock headsup
d1a59e66bb9 Less boring heads up option [1/2]
db95f03f899 SystemUI: fix constant FC on certain devices
76c597007d3 base: Make FP detection in pocket mode configurable [1/2]
75c6a7927cc pocket: Allow to listen for fingerprint

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

c0115a8 ConfigCenter: Force Expanded Notifications [2/2]
d4dad09 ConfigCenter: Less boring heads up option [2/2]
ad19246 ConfigCenter: Make FP detection in pocket mode configurable [2/2]
2d2340c ConfigCenter: Custom Rounded Corner and Padding preferences [2/2]
c384dc4 ConfigCenter: Fix blur intensity value
52a6fa0 ConfigCenter: notch-city: Add 3 mode display cutout handler [3/3]

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_Settings/commits/android_10-official

7803ee9c53 Settings: Double tap to trigger doze [2/2]


=======================
     2020/06/17
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

93b6d8b32d5 StatusBar: Fix setColorOverride on r39
47270977aaa StatusBar: Check if getBackground is null too
b76e7452005 FODCircleView: account for notch hide
e218fd32642 SystemUI: Also allow controlling top and bottom corners with settings
da1b13c5490 base: notch-city: Add 3 mode display cutout handler
6a0dd3c8a63 Update rounded corner radius path for Android 10
8134c033811 ScreenDecorations: Clean up tuner API
06f1ecb8f5d Rounded Corner: Code improvement and clean up
da931ca281f Custom Rounded Corner and Padding preferences [1/2]
3bf34f3b46e Revert "SystemUI: allow setting custom cutout shapes"
ad4e64390b6 Revert "QS: add right/left padding even if it's 0 for collapsed statusbar"
248cb787ddb Revert "add option to hide notch [1/2]"
2fc58fe12df fwb: Remove redundant clock switch in tuner
c13a1372957 base: Fix clock stuff after r37 merge
6cac86ecd77 base: SystemUI: tuner: fix hiding of statusbar clock
fe9d4b0bec0 Do not apply date customization to QS clock
4e08675f2d3 SystemUI: Always show date in QS header
7580be1e350 Statusbar clock: restore qsheader check within a saved instance
8ec1550ae0f base: Status bar clock customizations [1/2]
d870f87700f Lockscreen: Make Pinview Divider invisible
41aaca7ea78 PackageInstaller: Show current and new version on APK installation
d2934600b50 SmoothSpinners: Makes the loading "spinner" animation smoother
972e913d2ca Remove unnecessary videos
051409ac325 Increase Zenmode max hour limit from 12 to 24
250d4b17ff6 ChooserActivity: remove ugly separator
e09aba24564 base: DozeSensors: only use proximity sensor if supported
9336bff3431 fwb: Add Cocon font [2/2]
332afc067a7 SystemUI: Add ColorOS7 recognizing FP animations [1/2]

* Repository: https://github.com/ShapeShiftOS/android_frameworks_native/commits/android_10

25da1f031 Revert "surfaceflinger: Add support for extension lib"

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

04225b2 ConfigCenter: Add date right/left position [2/2]
8914589 ConfigCenter: Statusbar clock customization [2/2]
2395dc3 ConfigCenter: Add Violet to official devices
17c00f8 ConfigCenter: Add all the new FODAnimations

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_Settings/commits/android_10-official

cc8ce0e854 Revert "add option to hide notch [2/2]"
7da659078e Settings: Battery: Redesign BatteryMeterView

* Repository: https://github.com/PixelExperience/system_sepolicy/commits/ten

94bb3a8d DNM

* Repository: https://github.com/ShapeShiftOS/android_vendor_aosp/commits/android_10-official

20a2db37 Revert "soong: Add flag for fod extension"
04273c8f vendor: notch-city: Add 3 mode display cutout handler [2/3]

* Repository: https://github.com/ShapeShiftOS/android_vendor_oplauncher/commits/android_10

32724d7 Add README.md
268aab0 Fixed derp (oneplus recent provider)
5feed9f Added Oneplus Launcher


=======================
     2020/06/16
=======================

* Repository: https://github.com/ShapeShiftOS/android_manifest/commits/android_10

6582c95 Start tracking OnePlus Launcher

* Repository: https://github.com/PixelExperience/system_core/commits/ten

f6f3844c3 Fine tune blkio setting to improve boot time
6547064cc rootdir: init.rc: use default dirty writeout policy

* Repository: https://github.com/ShapeShiftOS/android_vendor_aosp/commits/android_10-official

7c03c20e Optionally build OPLauncher


=======================
     2020/06/15
=======================

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_TouchGestures/commits/android_10

26447d9 TouchGestures: Fix alertDialog theme

* Repository: https://github.com/ShapeShiftOS/android_vendor_pixelstyle/commits/android_10

936463e pixelstyle: Add Cocon font [1/2]


=======================
     2020/06/14
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

028c554193c SystemUI: Add OP Ripple animations [1/2]
f311e327f36 SystemUI: Add OP Recognizing FP animations [1/2]
a0092562fd1 SystemUI: Add PureView recognizing FP animations
9083893cc20 SystemUI: Add BlueFirework recognizing FP animation [1/2]
4a304106280 ExuiUtils: add method to check if device is connected to Wi-Fi
ca75794a66f StichImageUtility: allow taking screenshot on home screen
c3b699020a1 Add Sound tile to Quick Settings
e452ca91e12 SystemUI: Remove annoying log caused by aosp bug
3c51a0c0a5f Add Restart SystemUI button on Advanced Restart Menu (2/2)
d9e0371e504 Add Restart SystemUI button on Advanced Restart Menu (1/2)

* Repository: https://github.com/PixelExperience/frameworks_opt_telephony/commits/ten

5e91d7384 Avoid SubscriptionManager#getUriForSubscriptionId calls with invalid subIds

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

3b12556 ConfigCenter: Add the new official devices

* Repository: https://github.com/PixelExperience/packages_providers_DownloadProvider/commits/ten

338f2ab6 Automatic translation import

* Repository: https://github.com/PixelExperience/packages_services_BuiltInPrintService/commits/ten

2352397 Automatic translation import


=======================
     2020/06/13
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

c24a20a6636 11247: SystemUI: Add VoLIT icon [1/2]
5132ec275b3 base: Add a notch friendly VoLTE icon [1/2]
a3c561e9191 [REVERT] Disable blur on landscape and improve animations
f88f4a868a8 SystemUI: Introduce Adjustable Blur Intensity [1/2]
f17f25b38c1 base: Allow controlling QS blur alpha [1/2]
f2392ddc2ea Revert "blur: increase radius, remove it in landscape && improve animation"
d455728ff74 fwb: String Improvement
e2e9c476cee SystemUI: Add OP Energy FOD animation from OnePlus 8 Pro [1/2]
5fe40125ddf SystemUI: Add PureView recognizing FP animations [1/2]
6ecec2b3d94 Add OP Recognizing FP animations [1/2]
90036dcbf09 FODCycleView: animation picker cleanup
3999e7e093f Revert "Use OnePlus Ripple FOD animations"
9884e80b85d SystemUI: Recognizing fingerprint animation picker [1/2]
a79c52aac83 fw_base: Update OOS Style clear all notifications button icon
b510d013269 Settings dashboard icons: Fix theme for external icons on 10 [1/2]
3d3df154558 Theme settings dashboard icons [1/3]
be50a767ffe Revert "TyepClockAlt: Allign owner info"
a2121dcc62d base: Add Blur Powermenu switch and intensity[1/2]
fffc4f22e6b base: Blur behind powermenu

* Repository: https://github.com/PixelExperience/frameworks_opt_telephony/commits/ten

b0f0355de Remove setIsoCountryProperty method along with partially dead code

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

9b43b53 ConfigCenter: Import missing symbol
163fa43 Add the new VoLTE icons [2/2]
762c98d Introduce Adjustable Blur Intensity [2/2]
9e15268 FODAnim: String improvement
84e3fea Add OP Energy FOD animation from OnePlus 8 Pro [2/2]
847cd3f Add PureView recognizing FP animations [2/2]
3b61b88 Add OP Recognizing FP animations [2/2]
5812c4e Recognizing fingerprint animation picker [2/2]
d0c9226 Theme settings dashboard icons [3/3]
6d65a80 Add Blur Powermenu switch and intensity[2/2]
7b7bc6b Allow controlling QS blur alpha [2/2]

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_Settings/commits/android_10-official

d06a3c65bb Fix crash when going back from battery
ac51d001b4 Settings: show battery times vertically below the title
64c60fc3b6 Deselect items that are not meant to be clicked on in "About Phone"
c13356f8da Screensaver: Tint button to match system theme
ce6ed7d921 Desktop backup password: Tint buttons to match system theme
c74c1f826d Power detail pages: Finish off the rest of the icon tinting
6f916817d7 Settings: Show me more than 4 items in the menus!
7c9899b1b9 Settings: fix icon tinting in power detail pages
376ce0a01a Settings: fix hardcoded black text in storage summary
170123f678 InstalledAppDetails: fix refreshing storage summary after force stop
d9cfdbf2d7 fuelgauge: add back battery level animation
98eb6bc253 fuelgauge: Implement Early Warnings
c0491e6779 fuelgauge: Use Enhanced Battery Prediction from Turbo
79be0c092c Settings: PowerUsageSummary: open advanced usage on header click
67ea24f12d Settings: Black theme is getting nicer
118abec875 Settings: Include device model in About phone
4f83eb3d50 Settings: Add Device codename to Firmware version window
75e2843339 Settings: Address a memory leak
27570f7f10 DarkMode Settings: Use List Preference rather ugly Drop Down
092a408377 Match contextual card side margin with search bar
8b81ea3f70 Settings: Update raw animations and drawables from Pixel 4 XL
88c7870fb3 Settings Icons: add VPN icon
9ffd54e991 Suggestion cards: align them to searchbar
8db5672d51 Settings: Add drawable for Private DNS
d3b9fcea21 Center the suggestion card button
0e7b3ff6fd Settings: Add Pixel UI
6a190e7d87 Settings: Add phone specifications section
b4d03629e6 Bring back on/off toggle for physical SIMs
7b81a3008a Revert "Settings: Tweak some search dimens"
b1d3894665 Revert "Tweak search bar card elevation"
4f335cfc29 Settings dashboard icons: Fix theme for external icons on 10 [2/2]
186bf3574a Theme settings dashboard icons [2/3]


=======================
     2020/06/12
=======================

* Repository: https://github.com/PixelExperience/art/commits/ten

bf0f027891 Revert "Protect/Unprotect regions (region space) only in debug build"
c4d42c9690 art: extend the supported cpu_variant list for arm64

* Repository: https://github.com/PixelExperience/external_selinux/commits/ten

ec398f88 Don't require seinfo for privapps

* Repository: https://github.com/PixelExperience/hardware_interfaces/commits/ten

3793876af Add interface info in boot@1.0-service.rc

* Repository: https://github.com/PixelExperience/packages_providers_MediaProvider/commits/ten

c09e68a MediaProvider: Fix sorting by DATE_TAKEN

* Repository: https://github.com/PixelExperience/system_core/commits/ten

e78ff8af7 init.rc: disable kernel module autoloading

* Repository: https://github.com/PixelExperience/system_sepolicy/commits/ten

51585f31 Export missing audio volume properties
1a919f51 Ignore the denial when system_other is erased
39d0199e Don't require seinfo for priv-apps
eae12840 Allow reading dt fstab in boot control HAL.
4c84f94a Add sepolicy for IBootControl 1.0 and the default HAL.
0cab636f global_macros: trim back various watch* permissions
33321a03 update sepolicy for fs notification hooks

* Repository: https://github.com/PixelExperience/system_vold/commits/ten

3ec2ee0 Expand virtio_block check to other virtual devices


=======================
     2020/06/11
=======================

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

ef7153f Strings: Fix spelling error


=======================
     2020/06/10
=======================

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

3554712 Add Pocophone to Official Devices


=======================
     2020/06/09
=======================

* Repository: https://github.com/ShapeShiftOS/packages_apps_Updates/commits/android_10

85212ab Merge pull request #1 from MezzLasha/patch-1
e556abe fix derp


=======================
     2020/06/08
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

863768c809d fwb: Fix unrequired variable
c30a1eb3d5c Merge pull request #14 from MadeOfGreat/android_10-official
0dcedf06c45 Revert "FODCircleView: Always enable hbm"

* Repository: https://github.com/ShapeShiftOS/android_hardware_custom_interfaces/commits/android_10-official

01422f1 Merge pull request #1 from MadeOfGreat/android_10-official
e77b3b8 Revert "inscreen: Bump hal and add switchHbm methods"

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

2b01943 ConfigCenter: Import missing variables

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_Settings/commits/android_10-official

a6c3179b38 Merge pull request #10 from MezzLasha/patch-9
60b08d8e53 new, fixed play store icon
68e6779f73 Tweak search bar card elevation

* Repository: https://github.com/ShapeShiftOS/android_vendor_aosp/commits/android_10-official

4fc0965d vendor: Add vendor.lineage.biometrics.fingerprint.inscreen permission


=======================
     2020/06/07
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

076aa6ecdcd FOD: Don't animate while dozing
945edae9f90 FODCircleView: Always enable hbm
28e383e9dab Remove bool dependency for DASH charging.
7517fff939b Add the battery percent back for DASH charging.
b6e8fef724b Display DASH charging string accordingly in battery settings [1/2]
c805b2a5572 Add DASH support
e26a899386c Revert current dash charging and warp charging impl
1dd4b74adc6 Live Volume Steps [1/2]
137544d99d6 Add a LineageOS clock
c0ce4e50d9a TextClock: Fix NPE in TextClock
11967b1b289 TyepClockAlt: Allign owner info
cd9c00a3d74 Add center style Typographic clock

* Repository: https://github.com/ShapeShiftOS/android_frameworks_native/commits/android_10

a4dcb7aaa surfaceflinger: change usageBits type to uint64_t

* Repository: https://github.com/ShapeShiftOS/android_hardware_custom_interfaces/commits/android_10-official

25ee1b7 inscreen: Bump hal and add switchHbm methods

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

21ff81f Rebrand to ShapeShifter

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_Settings/commits/android_10-official

b3f4795316 Settings: Tweak some search dimens
ccaee0dc7e Ensure settings dashboard summary changes accordingly for DASH charging.
cda51a3bb8 Display string accordingly in battery settings for DASH charging. [2/2]
2bb2a1416a Revert existing dash charging and warp charging impl  Broken
95647fe407 Live Volume Steps [2/2]

* Repository: https://github.com/ShapeShiftOS/packages_apps_Updates/commits/android_10

ef56221 Updater: Bringup for ExtendedUI
368a600 Updater: Remove duplicate strings

* Repository: https://github.com/ShapeShiftOS/android_vendor_aosp/commits/android_10-official

c256c31d Build the OTA updater
c6efd9fd Revert "Revert "Revert "vendor: Revert caf sf commits"""


=======================
     2020/06/06
=======================

* Repository: https://github.com/ShapeShiftOS/android_build/commits/android_10

e2de97531 releasetools: do not remove dynamic partitions in system-only builds

* Repository: https://github.com/ShapeShiftOS/android_frameworks_base/commits/android_10-official

4552ff02561 Return: Smart Pulldown [1/2]
aef12eebad6 Add QS pull down with one finger [1/2]

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_ConfigCenter/commits/android_10-official

e29df36 Add OnePlus 6 to official devices
26aca69 Add QS pull down with one finger [2/2]
f29f6a5 Return: Smart Pulldown [2/2]
ca71672 ConfigCenter: Move Notifications into StatusBar
b0e6623 ConfigCenter: Move Theme Engine into UITuner

* Repository: https://github.com/ShapeShiftOS/android_packages_apps_Settings/commits/android_10-official

cec49d695b Fix NPE if default supervisor is not defined
ff195fdf2b Fixes ApnEditor not restoring previous UI
f353d99c75 Fix volume slider color is not correct
ed93f4275f translate="false" -> translatable="false"
2cb1be38dc hardwareinfo: Hide hardware revision if empty
2d847b74d2 Preserve icon for "manage space"


=======================
     2020/06/05
=======================

* Repository: https://github.com/ShapeShiftOS/android_frameworks_native/commits/android_10

4a5929cae Correct PowerManager transaction IDs. These transaction IDs must be kept in sync with the method order from IPowerManager.aidl.
3c035aa56 Don't destroy ART profiles after package move.
12f361e0f Add a separate flag in the installer for keeping ART profiles
08c9df324 surfaceflinger: Add support for extension lib

* Repository: https://github.com/ShapeShiftOS/android_manifest/commits/android_10

c119bab Manifest: Fix tracking duplicate repo
a3840f1 Track some repos
7806112 Remove unused frameworks/opt/datetimepicker
57f750f Fetch our fork of build-tools
1559e2f manifest: Use our forks of e/{cldr,icu} and s/timezone
9ef4a07 manifest: Track AOSP related repos from our org

* Repository: https://github.com/ShapeShiftOS/android_vendor_aosp/commits/android_10-official

acf0c790 vendor: Nuke ota permission
bf43f305 BoardConfigKernel: Opt-in for bison and flex

* Repository: https://github.com/ShapeShiftOS/android_vendor_lawnchair/commits/android_10

39e8b86 Update Lawnchair to 2.1-2627-ci-q-merge


