# ConferenceService

## ConferenceService

### Parameters

 - instance **VoxeetSdk**
 - timeout **long**


## mute

### Parameters

 - mute **boolean**

### Returns

__boolean__

## isMuted

### Returns

__boolean__

## isUserMuted

### Parameters

 - userId **String**

### Returns

__boolean__

## setListenerMode

### Parameters

 - isListener **boolean**


## register


## unregister


## toggleVideo


## toggleScreenShare


## getCurrentConferenceId

### Returns

__String__

## currentSpeaker

### Returns

__String__

## getSdkPeerVuMeter

### Parameters

 - peerId **String**

### Returns

__double__

## findUserById

### Parameters

 - userId **String**

### Returns

__User__

## getAliasId

### Returns

__String__

## setTelecomMode

### Parameters

 - telecomMode **boolean**


## isTelecomMode

### Returns

__boolean__

## getAutomaticTelecomModePrefix

### Returns

__String__

## getConferenceId

### Returns

__String__

## getEglContext

### Returns

__EglBaseMethods.Context__

## getTimeout

### Returns

__long__

## toggleRecording


## muteUser

### Parameters

 - userId **String**
 - shouldMute **boolean**

### Returns

__boolean__

## isVideoOn

### Returns

__boolean__

## isScreenShareOn

### Returns

__boolean__

## setDefaultVideo

### Parameters

 - default_state **boolean**

### Returns

__boolean__

## setDefaultMute

### Parameters

 - default_state **boolean**

### Returns

__boolean__

## setDefaultBuiltInSpeaker

### Parameters

 - default_state **boolean**

### Returns

__boolean__

## setTimeOut

### Parameters

 - timeout **long**

### Returns

__boolean__

## setUserPosition

### Parameters

 - userId **String**
 - angle **double**
 - distance **double**

### Returns

__boolean__

## getConferenceType

### Returns

__LocalConferenceType__

## getConference

### Returns

__Conference__

## isInConference

### Returns

__boolean__

## getPeerVuMeter

### Parameters

 - peerId **String**

### Returns

__double__

## getConferenceUsers

### Returns

__List<User>__

## getLastInvitationUsers

### Returns

__List<User>__

## isLive

### Returns

__boolean__

## isListenerMode

### Returns

__boolean__

## getUser

### Parameters

 - userId **String**

### Returns

__User__

## getMapOfStreams

### Returns

__HashMap<String, MediaStream>__

## getMapOfScreenShareStreams

### Returns

__HashMap<String, MediaStream>__

## cancelTimeout

### Returns

__ConferenceService__

## decline

### Parameters

 - conferenceId **String**

### Returns

__Promise<DeclineConferenceResultEvent>__

## sendRequestStartScreenShare


## onUserCanceledScreenShare


## startScreenShare

### Parameters

 - intent **Intent**
 - width **int**
 - height **int**

### Returns

__Promise<Boolean>__

## stopScreenShare

### Returns

__Promise<Boolean>__

## startVideo

### Returns

__Promise<Boolean>__

## startVideo

### Parameters

 - isDefaultFrontFacing **boolean**

### Returns

__Promise<Boolean>__

## stopVideo

### Returns

__Promise<Boolean>__

## create

### Returns

__Promise<ConferenceResponse>__

## create

### Parameters

 - metadata **MetadataHolder**
 - params **ParamsHolder**

### Returns

__Promise<ConferenceResponse>__

## create

### Parameters

 - conferenceAlias **String**

### Returns

__Promise<ConferenceResponse>__

## create

### Parameters

 - conferenceAlias **String**
 - metadata **MetadataHolder**
 - paramsholder **ParamsHolder**

### Returns

__Promise<ConferenceResponse>__

## create

### Parameters

 - conferenceCreateInformation **ConferenceCreateInformation**

### Returns

__Promise<ConferenceResponse>__

## listenConference

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## broadcastConference

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## join

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## demo

### Returns

__Promise<Boolean>__

## inviteUserInfos

### Parameters

 - conferenceId **String**
 - userInfos **List<UserInfo>**

### Returns

__Promise<List<ConferenceRefreshedEvent>>__

## invite

### Parameters

 - conferenceId **String**
 - ids **List<String>**

### Returns

__Promise<List<ConferenceRefreshedEvent>>__

## logout

### Returns

__Promise<Boolean>__

## replay

### Parameters

 - conferenceId **String**
 - offset **long**

### Returns

__Promise<Boolean>__

## startRecording

### Returns

__Promise<Boolean>__

## stopRecording

### Returns

__Promise<Boolean>__

## getConferenceStatus

### Parameters

 - conferenceId **String**

### Returns

__Promise<GetConferenceStatusEvent>__

## conferenceHistory

### Parameters

 - conferenceId **String**

### Returns

__Promise<GetConferenceHistoryEvent>__

## switchCamera

### Returns

__Promise<Boolean>__

## subscribe

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## unSubscribe

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## subscribeForCall

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## unSubscribeFromCall

### Parameters

 - conferenceId **String**

### Returns

__Promise<Boolean>__

## onEvent

### Parameters

 - event **OwnConferenceUserSwitchEvent**


## onEvent

### Parameters

 - event **SocketConnectEvent**


## getInvitedUsers

### Parameters

 - conferenceId **String**

### Returns

__Promise<ConferenceUsersInvitedEvent>__

## sendMessage

### Parameters

 - conferenceId **String**
 - message **String**

### Returns

__Promise<Boolean>__

## leave

### Returns

__Promise<Boolean>__

## onEvent

### Parameters

 - event **ConferenceStatsEvent**


## onEvent

### Parameters

 - event **ConferenceUpdatedEvent**


## onEvent

### Parameters

 - invitation **InvitationReceived**


## onEvent

### Parameters

 - invitation **InvitationReceivedEvent**


## onEvent

### Parameters

 - ownConferenceStartedEvent **OwnConferenceStartedEvent**


## onEvent

### Parameters

 - event **StartVideoAnswerEvent**


## onEvent

### Parameters

 - event **RenegociationUpdate**


## onEvent

### Parameters

 - event **OfferCreatedEvent**


## onEvent

### Parameters

 - event **ConferenceUserAddedEvent**


## onEvent

### Parameters

 - event **ParticipantUpdatedEvent**


## onEvent

### Parameters

 - event **ConferenceUserCallDeclinedEvent**


## onEvent

### Parameters

 - event **ConferenceUserLeftEvent**


## onEvent

### Parameters

 - event **ConferenceDestroyedPushEvent**


## onEvent

### Parameters

 - event **ConferenceEndedEvent**


## onEvent

### Parameters

 - event **QualityUpdatedEvent**


## onEvent

### Parameters

 - event **RecordingStatusUpdate**


## getEventBus

### Returns

__EventBus__

## getCurrentConferenceInformation

### Returns

__ConferenceInformation__

## hasParticipants

### Returns

__boolean__

## setICERestartEnabled

### Parameters

 - new_state **boolean**


## isICERestartEnabled

### Returns

__boolean__

## getContext

### Returns

__Context__

