## 0.0.1

- NudgeCoreV2 initial release.

## 0.0.2

- Bug Fixes

## 0.0.3

- Dynamic Asset Url

## 0.0.4

- Added Navigator Key in the Nudge Provider

## 0.0.5

- Schema Change In Track

## 0.0.6

- Asset URL Added

## 0.0.7

- Track Caching Issue Fixed

## 0.0.8

- Logger and Caching Logic fixed

## 0.0.9

- Performance upgrades and bug fixes

## 0.0.10

- Signout function Added

## 0.0.11

- Added No campaign Callback

## 0.0.12

- Bluetooth Permission Removed

## 0.0.13

- Track Retry Mech

## 0.0.14

- Track Retry Mech of InitSession

## 0.0.15

- User to Local and iOS bug fixes

## 0.0.16

- WidgetsFlutterBinding added in Nudge Constructor

## 0.0.17

- SessionId handling for User Signout case

## 0.0.18

- Added Updated Header

## 0.0.19

- Added Updated Header and Updated Submit

## 1.0.0

- Major Release (Breaking Changes)

## 1.0.1

- Custom SessionID generator added

## 1.0.2

- Fixed datatype of callback for trackResponse

## 1.0.3

- Provider campaign type changes for challenges

## 1.0.4

- Improvements

## 1.0.5

- Improvements and Feature Implementation

## 1.0.6

- Callbacks and Submit Centralization

## 1.0.7

- Callbacks Fix

## 2.0.2

- Major Release (Breaking Changes)

## 2.0.3

- Android Support JAVA 1_8

## 2.0.4

- Method Channel for Android Modified

## 2.0.5

- Method Channel for Android Modified

## 2.0.6

- Method Channel for iOS Modified

## 2.0.7

- Firebase Background Thread Issue Resolved

## 2.0.8

- iOS Stories Improvements

## 2.0.9

- Minor embedded widget improvements and deeplink callback added

## 2.0.10

- iOS callback listeners improved

## 2.0.11

- Android deeplink handling from flutter implemented

## 3.0.0

- Major Release

## 3.0.1

- Fix Incorrect iOS SDK Version Fetching

## 3.0.2

- Enabled interaction with nudges and background and disabled interaction with the background when
  experiences in the foreground

## 3.0.3

- Fixed App Component and Stories sizing during navigation

## 3.0.4

- Bug Fixes

## 3.0.5

- Bug Fixes

## 4.0.0

- Major Release [Breaking Changes]

## 4.0.1

- Native Wrappers Added

## 4.0.2

- Background interactions fixed in iOS

## 4.0.3

- RefreshToken and Auth callback reverted back to proper convention

## 4.0.4

- FIX: Fixed issue where app component label was unexpectedly updated during lifecycle
  events [ANDROID]

## 4.1.0

- IMPROVEMENT: Added support for iOS 12.0 and above [iOS]

## 4.1.1

- IMPROVEMENT: Added strict type checking for invalid data types in event and track
  properties [iOS, ANDROID]
- REFACTOR: Refactored logging and error handling for better clarity [iOS, ANDROID]

## 4.1.2

- IMPROVEMENT: Enhanced logging and method channel handling for better debugging [iOS, ANDROID]

## 4.1.3

- FIX: Handled multiple engines being created in the same app [iOS, ANDROID]

## 4.1.4

- IMPROVEMENT: Removed `FileProvider` dependency to avoid conflicts with other
  plugins [ANDROID]
- FIX: Users can now upload screenshots without marking any widgets [iOS, ANDROID]

## 4.2.0

- FEATURE: Added support for getting user details [iOS, ANDROID]
- IMPROVEMENT: Fixed dependency clash for RiveRuntime on iOS 12.0 [iOS]

## 4.2.2

- FIX: Enhanced method channel handling and multi-engine scenarios handled [ANDROID]

## 4.2.3

- FIX: Enhanced method channel handling and multi-engine scenarios handled [ANDROID]

## 4.3.0

- FEATURE: Added support to clear experiences [iOS, ANDROID]
- IMPROVEMENT: Enhanced method channel handling and multi-engine scenarios handled [iOS, ANDROID]

## 4.3.1

- FIX: Using screen size from `PlatformDispatcher` to avoid issues with `MediaQuery` [iOS, ANDROID]

## 4.3.2

- FIX: Fixed issue with `MediaQuery` and `PlatformDispatcher` not being available in some
  scenarios [iOS]

## 4.3.3

- FIX: Remove the screen blocking logic from the scroll [iOS, ANDROID]

## 4.3.4

- IMPROVEMENT: Added Thread safe implementation for callbacks [iOS, ANDROID]

## 4.3.5

- IMPROVEMENT: Added method to update registrar [iOS]

## 4.3.6

- IMPROVEMENT: Improved method channel communication in multi-engine setup [iOS]

## 4.3.7

- FIX: Minor Bug Fix [iOS]

## 5.0.0

- MAJOR RELEASE: Breaking Changes - Android and iOS SDKs updated to latest versions
- FEATURE: Added support for google fonts
- FIX: Surveys and Nudges fixed

## 5.0.1

- IMPROVEMENT: Native SDKs updated to latest versions [iOS, ANDROID]
- FIXES: App Component and Stories sizing during navigation [iOS, ANDROID]

## 5.0.2

- IMPROVEMENT: Improved empty API Key handling [iOS]

## 5.0.3

- IMPROVEMENT: Handled empty API Key and uninitialized Nudge [iOS, ANDROID]

## 5.0.4

- FEATURE: Added `disableNudge` flag to disable Nudge in the app [iOS, ANDROID]

## 5.0.5

- IMPROVEMENT: Native SDKs bumped [iOS, ANDROID]

## 5.0.6

- IMPROVEMENT: Made `disableNudge` flag more optional [iOS, ANDROID]
- IMPROVEMENT: Improved app component rendering [ANDROID]

## 5.0.7

- IMPROVEMENT: Nudges will not show if target is out of bounds [iOS, ANDROID]

## 5.0.8

- IMPROVEMENT: Nudges will not show if target is moving [iOS, ANDROID]

## 5.0.9

- IMPROVEMENT: Nudge shutdown on all channels [iOS]

## 5.0.10

- IMPROVEMENT: App component improved [iOS, ANDROID]

## 5.0.11

- FIX: Nudges scaling improved [ANDROID]
- CHORE: Downgraded `url_launcher` to support lower dart SDK versions [iOS, ANDROID]

## 5.0.12

- FIX: Nudges fixed for iOS [iOS]

## 5.0.13

- FIX: App component initial size glitch fixed [ANDROID]

## 5.0.14

- Rx dart downgraded

## 6.0.0

- Major Release

## 6.0.1

- IMPROVEMENT: Handled callbacks for multiple flutter engines 

## 6.0.2

- IMPROVEMENT: Handled callbacks for multiple flutter engines 

## 6.0.3

- FIX : updateAll method fixed for nullable string

## 6.1.0-alpha

- Added the wrapper support for tracking widgets for In App Nudges

## 6.1.1

- Releasing wrapper support for all customers.

## 7.0.0

- Stable Release. Removed auto update for native SDKs
