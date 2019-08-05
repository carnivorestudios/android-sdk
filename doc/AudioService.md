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

### Returns

__AudioService__

## releaseLocks

### Returns

__AudioService__

## resetDefaultSoundType

### Returns

__AudioService__

## abandonAudioFocusRequest

### Returns

__AudioService__

## requestAudioFocus

### Returns

__AudioService__

## setSound

### Parameters

 - type **AudioType**
 - assetName **String**

### Returns

__boolean__

## setSound

### Parameters

 - type **AudioType**
 - assetName **String**
 - soundMode **int**

### Returns

__boolean__

## playSoundType

### Parameters

 - type **AudioType**

### Returns

__AudioService__

## playSoundType

### Parameters

 - type **AudioType**
 - soundMode **int**

### Returns

__AudioService__

## stopSoundType

### Parameters

 - audioType **AudioType**

### Returns

__AudioService__

## stopSoundType

### Parameters

 - audioType **AudioType**
 - soundMode **int**

### Returns

__AudioService__

## stop

### Returns

__AudioService__

## enable

### Returns

__AudioService__

## enableMedia

### Returns

__AudioService__

## unsetMediaRoute

### Returns

__AudioService__

## setMediaRoute

### Returns

__AudioService__

## disable

### Returns

__AudioService__

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

