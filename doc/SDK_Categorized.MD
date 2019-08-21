# Category Reference SDK
# uncategorized
## SoundManager

### SoundManager

#### Parameters

 - context **Context**


### getAvailableRoutes

#### Returns

__List<AudioRoute>__

### currentRoute

#### Returns

__AudioRoute__

### setAudioRoute

#### Parameters

 - route **AudioRoute**

#### Returns

__boolean__

### getSystemRingtone

#### Returns

__Ringtone__

### isBluetoothHeadsetConnected

#### Returns

__boolean__

### isWiredHeadsetOn

#### Returns

__boolean__

### setSpeakerMode

#### Parameters

 - isSpeaker **boolean**

#### Returns

__SoundManager__

### isSpeakerOn

#### Returns

__boolean__

### acquireLocks

#### Returns

__SoundManager__

### releaseLocks

#### Returns

__SoundManager__

### resetDefaultSoundType

#### Returns

__SoundManager__

### enableMedia

#### Returns

__SoundManager__

### setMediaRoute

#### Returns

__SoundManager__

### unsetMediaRoute

#### Returns

__SoundManager__

### abandonAudioFocusRequest

#### Returns

__SoundManager__

### requestAudioFocus

#### Returns

__SoundManager__

### checkOutputRoute

#### Returns

__SoundManager__

### setSound

#### Parameters

 - type **AudioType**
 - assetName **String**

#### Returns

__boolean__

### setSound

#### Parameters

 - type **AudioType**
 - assetName **String**
 - soundMode **int**

#### Returns

__boolean__

### playSoundType

#### Parameters

 - type **AudioType**

#### Returns

__SoundManager__

### playSoundType

#### Parameters

 - type **AudioType**
 - soundMode **int**

#### Returns

__SoundManager__

### playSoundTypeForce

#### Parameters

 - type **AudioType**

#### Returns

__SoundManager__

### playSoundTypeForce

#### Parameters

 - type **AudioType**
 - soundMode **int**

#### Returns

__SoundManager__

### stopSoundType

#### Parameters

 - audioType **AudioType**

#### Returns

__SoundManager__

### stopSoundType

#### Parameters

 - audioType **AudioType**
 - soundMode **int**

#### Returns

__SoundManager__

### stop

#### Parameters

 - soundMode **int**

#### Returns

__SoundManager__

### stop

#### Returns

__SoundManager__

### onConferencePreJoinedEvent

#### Returns

__SoundManager__

### onConferenceDestroyedPush

#### Returns

__SoundManager__

### enable

#### Returns

__SoundManager__

### disable

#### Returns

__SoundManager__

## UserPosition

### distance

#### Returns

__double__

### angle

#### Returns

__double__

### UserPosition

#### Parameters

 - distance **double**
 - angle **double**


## ChatService

### ChatService

#### Parameters

 - instance **VoxeetSdk**


### onEvent

#### Parameters

 - event **MessageReceived**


### sendMessage

#### Parameters

 - conference **Conference**
 - chatMessage **ChatMessage**

#### Returns

__Promise<Boolean>__

## AudioService

### AudioService

#### Parameters

 - instance **VoxeetSdk**


### getSoundManager

#### Returns

__SoundManager__

### preInitSounds

#### Parameters

 - applicationContext **Context**

#### Returns

__boolean__

### onEvent

#### Parameters

 - event **ConferencePreJoinedEvent**


### onEvent

#### Parameters

 - event **ConferenceEndedEvent**


### onEvent

#### Parameters

 - event **ConferenceDestroyedPush**


### getAvailableRoutes

#### Returns

__List<AudioRoute>__

### currentRoute

#### Returns

__AudioRoute__

### setAudioRoute

#### Parameters

 - route **AudioRoute**

#### Returns

__boolean__

### checkOutputRoute

#### Returns

__AudioService__

### setSpeakerMode

#### Parameters

 - isSpeaker **boolean**


### isBluetoothHeadsetConnected

#### Returns

__boolean__

### isWiredHeadsetOn

#### Returns

__boolean__

### isSpeakerOn

#### Returns

__boolean__

### acquireLocks

#### Returns

__AudioService__

### releaseLocks

#### Returns

__AudioService__

### resetDefaultSoundType

#### Returns

__AudioService__

### abandonAudioFocusRequest

#### Returns

__AudioService__

### requestAudioFocus

#### Returns

__AudioService__

### setSound

#### Parameters

 - type **AudioType**
 - assetName **String**

#### Returns

__boolean__

### setSound

#### Parameters

 - type **AudioType**
 - assetName **String**
 - soundMode **int**

#### Returns

__boolean__

### playSoundType

#### Parameters

 - type **AudioType**

#### Returns

__AudioService__

### playSoundType

#### Parameters

 - type **AudioType**
 - soundMode **int**

#### Returns

__AudioService__

### stopSoundType

#### Parameters

 - audioType **AudioType**

#### Returns

__AudioService__

### stopSoundType

#### Parameters

 - audioType **AudioType**
 - soundMode **int**

#### Returns

__AudioService__

### stop

#### Returns

__AudioService__

### enable

#### Returns

__AudioService__

### enableMedia

#### Returns

__AudioService__

### unsetMediaRoute

#### Returns

__AudioService__

### setMediaRoute

#### Returns

__AudioService__

### disable

#### Returns

__AudioService__

### updateSensors

#### Parameters

 - route **AudioRoute**


### releaseSensors


### enableAec

#### Parameters

 - enable **boolean**

#### Returns

__boolean__

### enableNoiseSuppressor

#### Parameters

 - enable **boolean**

#### Returns

__boolean__

## ConferenceService

### ConferenceService

#### Parameters

 - instance **VoxeetSdk**
 - timeout **long**


### mute

#### Parameters

 - mute **boolean**

#### Returns

__boolean__

### isMuted

#### Returns

__boolean__

### isUserMuted

#### Parameters

 - userId **String**

#### Returns

__boolean__

### setListenerMode

#### Parameters

 - isListener **boolean**


### register


### unregister


### toggleVideo


### toggleScreenShare


### getCurrentConferenceId

#### Returns

__String__

### currentSpeaker

#### Returns

__String__

### getSdkPeerVuMeter

#### Parameters

 - peerId **String**

#### Returns

__double__

### findUserById

#### Parameters

 - userId **String**

#### Returns

__User__

### getAliasId

#### Returns

__String__

### setTelecomMode

#### Parameters

 - telecomMode **boolean**


### isTelecomMode

#### Returns

__boolean__

### getAutomaticTelecomModePrefix

#### Returns

__String__

### getConferenceId

#### Returns

__String__

### getEglContext

#### Returns

__EglBaseMethods.Context__

### getTimeout

#### Returns

__long__

### toggleRecording


### muteUser

#### Parameters

 - userId **String**
 - shouldMute **boolean**

#### Returns

__boolean__

### isVideoOn

#### Returns

__boolean__

### isScreenShareOn

#### Returns

__boolean__

### setDefaultVideo

#### Parameters

 - default_state **boolean**

#### Returns

__boolean__

### setDefaultMute

#### Parameters

 - default_state **boolean**

#### Returns

__boolean__

### setDefaultBuiltInSpeaker

#### Parameters

 - default_state **boolean**

#### Returns

__boolean__

### setTimeOut

#### Parameters

 - timeout **long**

#### Returns

__boolean__

### setUserPosition

#### Parameters

 - userId **String**
 - angle **double**
 - distance **double**

#### Returns

__boolean__

### getConferenceType

#### Returns

__LocalConferenceType__

### getConference

#### Returns

__Conference__

### isInConference

#### Returns

__boolean__

### getPeerVuMeter

#### Parameters

 - peerId **String**

#### Returns

__double__

### getConferenceUsers

#### Returns

__List<User>__

### getLastInvitationUsers

#### Returns

__List<User>__

### isLive

#### Returns

__boolean__

### isListenerMode

#### Returns

__boolean__

### getUser

#### Parameters

 - userId **String**

#### Returns

__User__

### getMapOfStreams

#### Returns

__HashMap<String, MediaStream>__

### getMapOfScreenShareStreams

#### Returns

__HashMap<String, MediaStream>__

### cancelTimeout

#### Returns

__ConferenceService__

### decline

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<DeclineConferenceResultEvent>__

### sendRequestStartScreenShare


### onUserCanceledScreenShare


### startScreenShare

#### Parameters

 - intent **Intent**
 - width **int**
 - height **int**

#### Returns

__Promise<Boolean>__

### stopScreenShare

#### Returns

__Promise<Boolean>__

### startVideo

#### Returns

__Promise<Boolean>__

### startVideo

#### Parameters

 - isDefaultFrontFacing **boolean**

#### Returns

__Promise<Boolean>__

### stopVideo

#### Returns

__Promise<Boolean>__

### create

#### Returns

__Promise<ConferenceResponse>__

### create

#### Parameters

 - metadata **MetadataHolder**
 - params **ParamsHolder**

#### Returns

__Promise<ConferenceResponse>__

### create

#### Parameters

 - conferenceAlias **String**

#### Returns

__Promise<ConferenceResponse>__

### create

#### Parameters

 - conferenceAlias **String**
 - metadata **MetadataHolder**
 - paramsholder **ParamsHolder**

#### Returns

__Promise<ConferenceResponse>__

### create

#### Parameters

 - conferenceCreateInformation **ConferenceCreateInformation**

#### Returns

__Promise<ConferenceResponse>__

### listenConference

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### broadcastConference

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### join

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### demo

#### Returns

__Promise<Boolean>__

### inviteUserInfos

#### Parameters

 - conferenceId **String**
 - userInfos **List<UserInfo>**

#### Returns

__Promise<List<ConferenceRefreshedEvent>>__

### invite

#### Parameters

 - conferenceId **String**
 - ids **List<String>**

#### Returns

__Promise<List<ConferenceRefreshedEvent>>__

### logout

#### Returns

__Promise<Boolean>__

### replay

#### Parameters

 - conferenceId **String**
 - offset **long**

#### Returns

__Promise<Boolean>__

### startRecording

#### Returns

__Promise<Boolean>__

### stopRecording

#### Returns

__Promise<Boolean>__

### getConferenceStatus

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<GetConferenceStatusEvent>__

### conferenceHistory

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<GetConferenceHistoryEvent>__

### switchCamera

#### Returns

__Promise<Boolean>__

### subscribe

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### unSubscribe

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### subscribeForCall

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### unSubscribeFromCall

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<Boolean>__

### onEvent

#### Parameters

 - event **OwnConferenceUserSwitchEvent**


### onEvent

#### Parameters

 - event **SocketConnectEvent**


### getInvitedUsers

#### Parameters

 - conferenceId **String**

#### Returns

__Promise<ConferenceUsersInvitedEvent>__

### sendMessage

#### Parameters

 - conferenceId **String**
 - message **String**

#### Returns

__Promise<Boolean>__

### leave

#### Returns

__Promise<Boolean>__

### onEvent

#### Parameters

 - event **ConferenceStatsEvent**


### onEvent

#### Parameters

 - event **ConferenceUpdatedEvent**


### onEvent

#### Parameters

 - invitation **InvitationReceived**


### onEvent

#### Parameters

 - invitation **InvitationReceivedEvent**


### onEvent

#### Parameters

 - ownConferenceStartedEvent **OwnConferenceStartedEvent**


### onEvent

#### Parameters

 - event **StartVideoAnswerEvent**


### onEvent

#### Parameters

 - event **RenegociationUpdate**


### onEvent

#### Parameters

 - event **OfferCreatedEvent**


### onEvent

#### Parameters

 - event **ConferenceUserAddedEvent**


### onEvent

#### Parameters

 - event **ParticipantUpdatedEvent**


### onEvent

#### Parameters

 - event **ConferenceUserCallDeclinedEvent**


### onEvent

#### Parameters

 - event **ConferenceUserLeftEvent**


### onEvent

#### Parameters

 - event **ConferenceDestroyedPushEvent**


### onEvent

#### Parameters

 - event **ConferenceEndedEvent**


### onEvent

#### Parameters

 - event **QualityUpdatedEvent**


### onEvent

#### Parameters

 - event **RecordingStatusUpdate**


### getEventBus

#### Returns

__EventBus__

### getCurrentConferenceInformation

#### Returns

__ConferenceInformation__

### hasParticipants

#### Returns

__boolean__

### setICERestartEnabled

#### Parameters

 - new_state **boolean**


### isICERestartEnabled

#### Returns

__boolean__

### getContext

#### Returns

__Context__

## LocalStatsService

### int

#### Parameters

 - 500 **NEXT_LOOP_FETCH_MS**


### LocalStatsService

#### Parameters

 - instance **VoxeetSdk**


### getLocalStats

#### Parameters

 - peer **String**

#### Returns

__LocalStats__

### startAutoFetch

#### Returns

__boolean__

### stopAutoFetch

#### Returns

__boolean__

### run


### getUserInfo

#### Parameters

 - conferenceId **String**
 - userId **String**

#### Returns

__LocalStatsUserInfo__

## MediaService

### MediaService

#### Parameters

 - instance **VoxeetSdk**


### hasMedia

#### Returns

__boolean__

### getMedia

#### Returns

__MediaSDK__

### getLocalStats

#### Parameters

 - peer **String**

#### Returns

__LocalStats__

### releaseMedia


### void

#### Parameters

 - Context **createMedia**
 - String **context**
 - MediaEngine.StreamListener **userId**
 - CameraVideoCapturer.CameraEventsHandler **mediaStreamListener**
 - boolean **cameraEventsHandler**
 - boolean **videoOn**
 - MediaEngineException **useMic**


### getEglContext

#### Returns

__EglBaseMethods.Context__

### setCryptoCallback

#### Parameters

 - callback **AbstractNativeMediaCryptoCallback**


### attachMediaStream

#### Parameters

 - stream **MediaStream**
 - videoSink **VideoSink**

#### Returns

__boolean__

### unAttachMediaStream

#### Parameters

 - stream **MediaStream**
 - videoSink **VideoSink**

#### Returns

__boolean__

### isAudio3DEnabled

#### Returns

__boolean__

### setAudio3DEnabled

#### Parameters

 - enable **boolean**

#### Returns

__boolean__

### switchCamera

#### Returns

__Promise<Boolean>__

### getCameraInformationProvider

#### Returns

__CameraInformationProvider__

## ScreenShareService

### ScreenShareService

#### Parameters

 - instance **VoxeetSdk**


### toggleScreenShare


### startScreenShare

#### Parameters

 - intent **Intent**

#### Returns

__Promise<Boolean>__

### stopScreenShare

#### Returns

__Promise<Boolean>__

### setScreenSizeInformation

#### Parameters

 - point **Point**

#### Returns

__ScreenShareService__

### sendRequestStartScreenShare


### sendUserPermissionRequest

#### Parameters

 - activity **Activity**

#### Returns

__boolean__

### consumeRightsToScreenShare


### onActivityResult

#### Parameters

 - requestCode **int**
 - resultCode **int**
 - data **Intent**

#### Returns

__boolean__

### getScreenSize

#### Parameters

 - context **Context**

#### Returns

__Point__

### getScreenSizeScaled

#### Parameters

 - screen_size **Point**
 - height **int**

#### Returns

__Point__

## SDKFilePresentationService

### SDKFilePresentationService

#### Parameters

 - instance **VoxeetSdk**


### onEvent

#### Parameters

 - event **FilePresentationStartedEvent**


### onEvent

#### Parameters

 - event **FilePresentationStoppedEvent**


### onEvent

#### Parameters

 - event **FilePresentationUpdatedEvent**


### onEvent

#### Parameters

 - event **FileConvertedEvent**


### getImage

#### Parameters

 - fileId **String**
 - pageNumber **int**

#### Returns

__String__

### getThumbnail

#### Parameters

 - fileId **String**
 - pageNumber **int**

#### Returns

__String__

### convertFile

#### Parameters

 - file **java.io.File**

#### Returns

__Promise<FilePresentationConverted>__

### startPresentation

#### Parameters

 - body **FilePresentationConverted**

#### Returns

__Promise<FilePresentationStarted>__

### startPresentation

#### Parameters

 - body **FilePresentationConverted**
 - position **int**

#### Returns

__Promise<FilePresentationStarted>__

### stopPresentation

#### Parameters

 - fileId **String**

#### Returns

__Promise<FilePresentationStopped>__

### updatePresentation

#### Parameters

 - fileId **String**
 - position **int**

#### Returns

__Promise<FilePresentationUpdated>__

### register

#### Parameters

 - mediaPlayerProvider **AbstractMediaPlayerProvider**


### getCompatibleMediaPlayerProvider

#### Parameters

 - url **String**

#### Returns

__AbstractMediaPlayerProvider__

## SDKVideoPresentationService

### SDKVideoPresentationService

#### Parameters

 - instance **VoxeetSdk**


### onEvent

#### Parameters

 - event **VideoPresentationStartedEvent**


### onEvent

#### Parameters

 - event **VideoPresentationStoppedEvent**


### onEvent

#### Parameters

 - event **VideoPresentationPausedEvent**


### onEvent

#### Parameters

 - event **VideoPresentationPlayEvent**


### onEvent

#### Parameters

 - event **VideoPresentationSeekEvent**


### startVideoPresentation

#### Parameters

 - url **String**

#### Returns

__Promise<VideoPresentationStarted>__

### stopVideoPresentation

#### Returns

__Promise<VideoPresentationStopped>__

### playVideoPresentation

#### Returns

__Promise<VideoPresentationPlay>__

### pauseVideoPresentation

#### Parameters

 - timestamp **long**

#### Returns

__Promise<VideoPresentationPaused>__

### seekVideoPresentation

#### Parameters

 - timestamp **long**

#### Returns

__Promise<VideoPresentationSeek>__

## UserService

### UserService

#### Parameters

 - instance **VoxeetSdk**


### connectSocket

#### Parameters

 - provider **VoxeetHttp**


### getUploadToken


### login

#### Parameters

 - userInfo **UserInfo**

#### Returns

__Promise<Boolean>__

### login

#### Returns

__Promise<Boolean>__

### closeSocket


### cleanUserSession

#### Parameters

 - id **String**


### isSocketOpen

#### Returns

__boolean__

### getUserInfo

#### Returns

__UserInfo__

### getUserId

#### Returns

__String__

### logout

#### Returns

__Promise<Boolean>__

### onEvent

#### Parameters

 - event **SocketConnectEvent**


### onEvent

#### Parameters

 - event **SocketConnectErrorEvent**


## AbstractMediaPlayerProvider<MEDIA_PLAYER_VIEW extends AbstractMediaPlayerView>

### isUrlCompatible

#### Parameters

 - url **String**

#### Returns

__boolean__

### createMediaPlayerView

#### Parameters

 - context **Context**

#### Returns

__MEDIA_PLAYER_VIEW__

## AbstractMediaPlayerView

### AbstractMediaPlayerView

#### Parameters

 - context **Context**


### AbstractMediaPlayerView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**


### AbstractMediaPlayerView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**
 - defStyleAttr **int**


### AbstractMediaPlayerView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**
 - defStyleAttr **int**
 - defStyleRes **int**


### start

#### Parameters

 - videoPresentationStarted **VideoPresentationStarted**


### stop

#### Parameters

 - videoPresentationStopped **VideoPresentationStopped**


### play

#### Parameters

 - videoPresentationPlay **VideoPresentationPlay**


### pause

#### Parameters

 - videoPresentationPaused **VideoPresentationPaused**


### seek

#### Parameters

 - videoPresentationSeek **VideoPresentationSeek**


## VoxeetSdk

### getInstance

#### Returns

__VoxeetSdk__

### instance

#### Returns

__VoxeetSdk__

### setApplication

#### Parameters

 - application **Application**


### initialize

#### Parameters

 - appId **String**
 - password **String**


### initialize

#### Parameters

 - application **Application**
 - appId **String**
 - password **String**


### initialize

#### Parameters

 - application **Application**
 - accessToken **String**
 - refreshToken **RefreshTokenCallback**


### initialize

#### Parameters

 - accessToken **String**
 - refreshToken **RefreshTokenCallback**


### chat

#### Returns

__ChatService__

### conference

#### Returns

__ConferenceService__

### mediaDevice

#### Returns

__MediaService__

### screenShare

#### Returns

__ScreenShareService__

### user

#### Returns

__UserService__

### filePresentation

#### Returns

__SDKFilePresentationService__

### videoPresentation

#### Returns

__SDKVideoPresentationService__

### audio

#### Returns

__AudioService__

### localStats

#### Returns

__LocalStatsService__

### getUserService

#### Returns

__UserService__

### getFilePresentationService

#### Returns

__SDKFilePresentationService__

### getVideoPresentationService

#### Returns

__SDKVideoPresentationService__

### getMediaService

#### Returns

__MediaService__

### getLocalStatsService

#### Returns

__LocalStatsService__

### manageRemoteMessage

#### Parameters

 - context **Context**
 - remoteMessage **Map<String, String>**

#### Returns

__boolean__

### resetVoxeetHttp


### getConferenceService

#### Returns

__ConferenceService__

### getScreenShareService

#### Returns

__ScreenShareService__

### getAudioService

#### Returns

__AudioService__

### decode

#### Parameters

 - message **String**

#### Returns

__Event__

### getRetrofit

#### Returns

__Retrofit__

### getClient

#### Returns

__OkHttpClient__

### getApplicationContext

#### Returns

__Context__

### getVoxeetEnvironmentHolder

#### Returns

__AbstractVoxeetEnvironmentHolder__

### resetServices


### getEventBus

#### Returns

__EventBus__

### register

#### Parameters

 - subscriber **Object**

#### Returns

__boolean__

### unregister

#### Parameters

 - subscriber **Object**


## Conference

### Conference

#### Parameters

 - fromConference **com.voxeet.sdk.models.v1.Conference**


### getId

#### Returns

__String__

### getAlias

#### Returns

__String__

### getUsers

#### Returns

__CopyOnWriteArrayList<User>__

### updateUsers

#### Parameters

 - user **ConferenceUser**

#### Returns

__Conference__

### updateUser

#### Parameters

 - participant **Participant**

#### Returns

__Conference__

### updateUser

#### Parameters

 - user **User**

#### Returns

__Conference__

### updateUsers

#### Parameters

 - users **List<ConferenceUser>**

#### Returns

__Conference__

### updateParticipants

#### Parameters

 - participants **List<Participant>**

#### Returns

__Conference__

### setConferenceId

#### Parameters

 - id **String**

#### Returns

__Conference__

### setConferenceAlias

#### Parameters

 - alias **String**

#### Returns

__Conference__

### findUserById

#### Parameters

 - userId **String**

#### Returns

__User__

### findUserByExternalId

#### Parameters

 - externalId **String**

#### Returns

__User__

### setConferenceInfos

#### Parameters

 - conferenceInfos **ConferenceInfos**


### getConferenceInfos

#### Returns

__ConferenceInfos__

### setRecordingInformation

#### Parameters

 - recordingInformation **RecordingInformation**


### getRecordingInformation

#### Returns

__RecordingInformation__

## User

### User

#### Parameters

 - id **String**
 - userInfo **UserInfo**


### User

#### Parameters

 - conferenceUser **ConferenceUser**


### User

#### Parameters

 - userInfo **UserInfo**


### User

#### Parameters

 - participant **Participant**


### getId

#### Returns

__String__

### getUserInfo

#### Returns

__UserInfo__

### updateStatus

#### Parameters

 - status **ConferenceUserStatus**

#### Returns

__User__

### getStatus

#### Returns

__ConferenceUserStatus__

### equals

#### Parameters

 - obj **Object**

#### Returns

__boolean__

### setUserInfo

#### Parameters

 - userInfo **UserInfo**

#### Returns

__User__

### setQuality

#### Parameters

 - quality **String**


### updateIfNeeded

#### Parameters

 - name **String**
 - avatarUrl **String**


### toString

#### Returns

__String__

## ConferenceUserStatus

## ChatMessage

### date

#### Returns

__Date__

### content

#### Returns

__String__

### type

#### Returns

__ChatMessageType__

### ChatMessage

#### Parameters

 - date **Date**
 - content **String**
 - type **ChatMessageType**


### ChatMessage

#### Parameters

 - source **InternalChatMessage**


## ChatMessageType

## VideoView

### VideoView

#### Parameters

 - context **Context**


### VideoView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**


### setVisibility

#### Parameters

 - visibility **int**


### addListener

#### Parameters

 - listener **RendererCommon.RendererEvents**


### removeListener

#### Parameters

 - listener **RendererCommon.RendererEvents**


### clearListeners


### setVideoFit


### setVideoFill


### setVideoBalanced


### setFlip

#### Parameters

 - flip **boolean**


### setMirror

#### Parameters

 - mirror **boolean**


### setSurfaceViewRenderer


### getScalingType

#### Returns

__RendererCommon.ScalingType__

### isAutoUnAttach

#### Returns

__boolean__

### setAutoUnAttach

#### Parameters

 - autoUnAttach **boolean**


### release


### reinit

#### Returns

__boolean__

### getRenderer

#### Returns

__VoxeetRenderer__

### enableLog

#### Parameters

 - tag **String**


### isAttached

#### Returns

__boolean__

### attach

#### Parameters

 - peerId **String**
 - mediaStream **MediaStream**


### unAttach


### getPeerId

#### Returns

__String__

### isScreenShare

#### Returns

__boolean__

### hasVideo

#### Returns

__boolean__

### onFirstFrameRendered


### onFrameResolutionChanged

#### Parameters

 - videoWidth **int**
 - videoHeight **int**
 - rotation **int**


### getCurrentMediaStreamType

#### Returns

__MediaStreamType__

### getBitmap

#### Returns

__Bitmap__

### getBitmap

#### Parameters

 - bitmap **Bitmap**

#### Returns

__Bitmap__

### getBitmap

#### Parameters

 - width **int**
 - height **int**

#### Returns

__Bitmap__

### setIsCircle

#### Parameters

 - isCircle **boolean**

#### Returns

__VideoView__

### setCornerRadius

#### Parameters

 - cornerRadius **float**

#### Returns

__VideoView__

### activateSafeRefreshEglBase

#### Parameters

 - state **boolean**


### onEvent

#### Parameters

 - event **EglBaseRefreshEvent**


### resetDelta


### commitDelta


### startTouch

#### Parameters

 - event **MotionEvent**


### applyDelta

#### Parameters

 - event **MotionEvent**


## VoxeetRenderer

### VoxeetRenderer

#### Parameters

 - context **Context**


### VoxeetRenderer

#### Parameters

 - context **Context**
 - attrs **AttributeSet**


### init

#### Parameters

 - sharedContext **EglBaseMethods.Context**
 - rendererEvents **RendererCommon.RendererEvents**


### init

#### Parameters

 - sharedContext **EglBaseMethods.Context**
 - rendererEvents **RendererCommon.RendererEvents**
 - configAttributes **int[]**
 - drawer **RendererCommon.GlDrawer**


### release


### addFrameListener

#### Parameters

 - listener **SafeRenderFrameEglRenderer.FrameListener**
 - scale **float**
 - drawerParam **RendererCommon.GlDrawer**


### addFrameListener

#### Parameters

 - listener **SafeRenderFrameEglRenderer.FrameListener**
 - scale **float**


### removeFrameListener

#### Parameters

 - listener **SafeRenderFrameEglRenderer.FrameListener**


### setEnableHardwareScaler

#### Parameters

 - enabled **boolean**


### setMirror

#### Parameters

 - mirror **boolean**


### isMirror

#### Returns

__boolean__

### isFirstFrameRendered

#### Returns

__boolean__

### setScalingType

#### Parameters

 - scalingType **RendererCommon.ScalingType**


### setScalingType

#### Parameters

 - scalingTypeMatchOrientation **RendererCommon.ScalingType**
 - scalingTypeMismatchOrientation **RendererCommon.ScalingType**


### getScalingType

#### Returns

__RendererCommon.ScalingType__

### setFpsReduction

#### Parameters

 - fps **float**


### disableFpsReduction


### pauseVideo


### onFrame

#### Parameters

 - frame **VideoFrame**


### forceRecalculateWidthHeight


### onSurfaceTextureAvailable

#### Parameters

 - surface **SurfaceTexture**
 - width **int**
 - height **int**


### onSurfaceTextureSizeChanged

#### Parameters

 - surface **SurfaceTexture**
 - width **int**
 - height **int**


### onSurfaceTextureDestroyed

#### Parameters

 - surface **SurfaceTexture**

#### Returns

__boolean__

### onSurfaceTextureUpdated

#### Parameters

 - surface **SurfaceTexture**


### clearImage


### getScreenWidth

#### Returns

__int__

### getScreenHeight

#### Returns

__int__

### setFirstFrameRendered

#### Parameters

 - isFirstFrameRendered **boolean**


### setDeltaX

#### Parameters

 - dx **float**


### setDeltaY

#### Parameters

 - dy **float**


### getTranslationY

#### Returns

__float__

### getTranslationX

#### Returns

__float__

### getRendererScaleX

#### Returns

__float__

### getRendererScaleY

#### Returns

__float__

### getRotatedFrameWidth

#### Returns

__float__

### getRotatedFrameHeight

#### Returns

__float__

