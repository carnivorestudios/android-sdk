# Voxeet Android SDK

The SDK is a Java library allowing users to:

  - Create demo/normal conferences
  - Join conferences
  - Change sounds angle and direction for each conference user
  - Broadcast messages to other participants
  - Mute users/conferences
  - Enable/disable camera
  - Screen share
  - Record conferences
  - Replay recorded conferences
  - If you use External login like O365, LDAP, or custom login to retrieve contact details, it is now possible to also add your contact ID with the display name and the photo url avatar.
   This allows you to ask guest users to introduce themselves and provide their display name and for your authenticated users in your enterprise or for your clients the ID that can be retrieved from O365 (name, department, etc).

### Version

public-sdk: 1.4.6
toolkit: 1.4.6

### Beta Version

Improved, tested but currently in beta

public-sdk: 2.0.32
toolkit: 2.0.32

### Documentation [WIP feature]

You can access to a simple reference documentation [here](./doc/Doc.md)

### What's New ?

v2.0.32:
  - VoxeetSdk.getInstance() removed
  - Service's getter deprecated (use VoxeetSdk.user(), VoxeetSdk.audio(), etc... instead)
  - fix various Camera issues on some Huawei, Xiaomi devices

v2.0.x:
  - class refactored ! In case of missing package, reimport the various classes
v1.4.x:
  - improve wired and bluetooth headset management
  - fix non firebase project crash

v1.3 :
  - fix various network connectivity
  - improve socket management
  - fix issue in oauth management
  - fix screen recording calls

v1.1.8.32 :
  - add localstats with support of auto management and report event

v1.1.8.28/31 :
  - fix default toolkit behaviour
  - add local stats management

v1.1.8.27 :
  - fix incoming calls issues
  - improve integration
  - lighter sample application to work with

v1.1.8.26 :
  - fix crash on peer vu meter

v1.1.8.24 : 
  - add sound in incoming calls

v1.1.8.23 : 
  - improves the overall SDK experience
  - fix workflows
  - improve video management
  - sync experience with the iOS implementation

v1.1.7.1.1 :
  - fix a crash when SDK is not initialized and using `VoxeetAppCompatActivity`

v1.1.7.1 :
  - fix overlay behaviour

v1.1.6 :
  - new Media management

v1.1.5 :
  - from previous vversion, Media.AudioRoute is now AudioRoute
  - Audio related APIs are now in `VoxeetSdk.getInstance().getAudioService()`
  - fix issues with ids from the SDK
  - add VideoPresentation api
  - sample app : integration of the api and fix with butterknife

v1.1.0 :
  - various fixes (issue with speaker button)
  - add screenshare capabilities
  - easier integration
  - dual initialization mode (keys or oauth)

v1.0.4 :
  - upgrade api calls
  - fix issue with answers
  - fix conference alias in history

v1.0.3 :
  - initialize Promises during the Voxeet initialization

v1.0.2 :
  - fix CTA
  - fix issue with crash on same calls
  - fix controllers behaviour

v1.0 :
  - complete rework of most internal method
  - File Presentation management (start, stop, update)
  - event on QualityIndicators with MOS


## Usage & Documentation

For reference, please head to our [developer portal reference documentation](https://developer.voxeet.com/reference/android/reference-Android/)

## Sample Application

A sample application is available on our [sample public repository](https://github.com/voxeet/android-sdk-sample) on GitHub.

© Voxeet, 2019

   [Official Android Documentation]: <http://developer.android.com/training/permissions/requesting.html>
   [sample]: <https://github.com/voxeet/android-sdk-sample.git>
   [GreenRobot/EventBus]: <https://github.com/greenrobot/EventBus>
   [Jackson]: <https://github.com/FasterXML/jackson>
   [Picasso]: <http://square.github.io/picasso>
   [Recyclerview]: <https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html>
   [Butterknife]: <http://jakewharton.github.io/butterknife>
   [Apache Commons]: <https://commons.apache.org>
   [RxAndroid]: <https://github.com/ReactiveX/RxAndroid>
   [Retrofit2]: <http://square.github.io/retrofit/>
   [SimplePromise]: <https://github.com/codlab/android_promise>
