# Category Reference Toolkit
# uncategorized
## VoxeetActionBarView

### VoxeetActionBarView

#### Parameters

 - context **Context**


### VoxeetActionBarView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**


### setDisplayMute

#### Parameters

 - displayMute **boolean**


### setDisplayCamera

#### Parameters

 - displayCamera **boolean**


### setDisplaySpeaker

#### Parameters

 - displaySpeaker **boolean**


### setDisplayScreenShare

#### Parameters

 - displayScreenShare **boolean**


### setDisplayLeave

#### Parameters

 - displayLeave **boolean**


### VoxeetActionBarView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**
 - defStyleAttr **int**


### onResume


### onStop


### onMediaStreamUpdated

#### Parameters

 - userId **String**
 - mediaStreams **Map<String, MediaStream>**


### onScreenShareMediaStreamUpdated

#### Parameters

 - userId **String**
 - screen_share_media_streams **Map<String, MediaStream>**


### init


### onConferenceJoined

#### Parameters

 - conference_id **String**


### onConferenceCreating


### onConferenceCreation

#### Parameters

 - conferenceId **String**


### onConferenceJoining

#### Parameters

 - conference_id **String**


### onToggleSize

#### Parameters

 - isMaxedOut **boolean**


### onEvent

#### Parameters

 - event **StopScreenShareAnswerEvent**


### onEvent

#### Parameters

 - event **StartScreenShareAnswerEvent**


### onEvent

#### Parameters

 - event **AudioRouteChangeEvent**


### setView3dListener

#### Parameters

 - listener **OnView3D**


## VoxeetSpeakerView

### VoxeetSpeakerView

#### Parameters

 - context **Context**


### VoxeetSpeakerView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**


### VoxeetSpeakerView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**
 - defStyleAttr **int**


### onConferenceDestroyed


### onConferenceLeft


### init


### onConferenceUsersListUpdate

#### Parameters

 - conferenceUsers **List<User>**


### findUserById

#### Parameters

 - userId **String**

#### Returns

__User__

### lockScreen

#### Parameters

 - userId **String**


### unlockScreen


### getSelectedUserId

#### Returns

__String__

### onResume


### onPause


## VoxeetUsersView

### VoxeetUsersView

#### Parameters

 - context **Context**


### VoxeetUsersView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**


### VoxeetUsersView

#### Parameters

 - context **Context**
 - attrs **AttributeSet**
 - defStyleAttr **int**


### setNamesEnabled

#### Parameters

 - enabled **boolean**


### setSelectedUserColor

#### Parameters

 - color **int**


### isDisplaySelf

#### Returns

__boolean__

### isDisplayNonAir

#### Returns

__boolean__

### onConferenceUserJoined

#### Parameters

 - conferenceUser **User**


### onConferenceUserLeft

#### Parameters

 - conferenceUser **User**


### onConferenceUserUpdated

#### Parameters

 - conference_user **User**


### onMediaStreamUpdated

#### Parameters

 - userId **String**
 - mediaStreams **Map<String, MediaStream>**


### onScreenShareMediaStreamUpdated

#### Parameters

 - userId **String**
 - mediaStreams **Map<String, MediaStream>**


### onScreenShareMediaStreamUpdated

#### Parameters

 - screenShareMediaStreams **Map<String, MediaStream>**


### onConferenceDestroyed


### onConferenceLeft


### init


### setParticipantListener

#### Parameters

 - listener **IParticipantViewListener**


### notifyDatasetChanged


## VoxeetActiveSpeakerTimer

### VoxeetActiveSpeakerTimer

#### Parameters

 - listener **ActiveSpeakerListener**


### start


### stop


### getCurrentActiveSpeaker

#### Returns

__String__

