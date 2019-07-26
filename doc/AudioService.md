# AudioService

## AudioService

### Parameters

 - instance **VoxeetSdkTemplate**


## getSoundManager

### Returns

__SoundManager__

## preInitSounds

### Parameters

 - applicationContext **Context**

### Returns

__boolean__

## onEvent

### Parameters

 - event **ConferencePreJoinedEvent**


## onEvent

### Parameters

 - event **ConferenceEndedEvent**


## onEvent

### Parameters

 - event **ConferenceDestroyedPush**


## getAvailableRoutes

### Returns

__List<AudioRoute>__

## currentRoute

### Returns

__AudioRoute__

## setAudioRoute

### Parameters

 - route **AudioRoute**

### Returns

__boolean__

## checkOutputRoute

### Returns

__AudioService__

## setSpeakerMode

### Parameters

 - isSpeaker **boolean**


## isBluetoothHeadsetConnected

### Returns

__boolean__

## isWiredHeadsetOn

### Returns

__boolean__

## isSpeakerOn

### Returns

__boolean__

## acquireLocks


## releaseLocks


## resetDefaultSoundType


## abandonAudioFocusRequest


## requestAudioFocus


## setSound

### Parameters

 - type **AudioType**
 - assetName **String**

### Returns

__boolean__

## playSoundType

### Parameters

 - type **AudioType**


## stopSoundType

### Parameters

 - audioType **AudioType**


## stop


## enable


## disable


## updateSensors

### Parameters

 - route **AudioRoute**


## releaseSensors


## enableAec

### Parameters

 - enable **boolean**

### Returns

__boolean__

## enableNoiseSuppressor

### Parameters

 - enable **boolean**

### Returns

__boolean__

