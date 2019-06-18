# VoxeetSdk

## instance

### Returns

__VoxeetSdk__

## conference

### Returns

__ConferenceService__

## screenShare

### Returns

__ScreenShareService__

## audio

### Returns

__AudioService__

## mediaDevice

### Returns

__MediaService__

## localStats

### Returns

__LocalStatsService__

## user

### Returns

__UserService__

## filePresentation

### Returns

__SDKFilePresentationService__

## videoPresentation

### Returns

__SDKVideoPresentationService__

## setApplication

### Parameters

 - application **Application**


## initialize

### Parameters

 - appId **String**
 - password **String**


## initialize

### Parameters

 - application **Application**
 - appId **String**
 - password **String**


## initialize

### Parameters

 - application **Application**
 - accessToken **String**
 - refreshToken **RefreshTokenCallback**


## initialize

### Parameters

 - accessToken **String**
 - refreshToken **RefreshTokenCallback**


## getVoxeetEnvironmentHolder

### Returns

__AbstractVoxeetEnvironmentHolder__

## getConferenceService

### Returns

__ConferenceService__

## getScreenShareService

### Returns

__ScreenShareService__

## getAudioService

### Returns

__AudioService__

## getMediaService

### Returns

__MediaService__

## getLocalStatsService

### Returns

__LocalStatsService__

## getUserService

### Returns

__UserService__

## getFilePresentationService

### Returns

__SDKFilePresentationService__

## getVideoPresentationService

### Returns

__SDKVideoPresentationService__

## T

### Parameters

 - AbstractVoxeetService> **extends**
 - getServiceForKlass **T**
 - klass **Class<T>**


## decode

### Parameters

 - message **String**

### Returns

__Event__

## getApplicationContext

### Returns

__Context__

## resetServices


## getEventBus

### Returns

__EventBus__

## register

### Parameters

 - context **Context**

### Returns

__boolean__

## register

### Parameters

 - context **Context**
 - subscriber **Object**

### Returns

__boolean__

## unregister

### Parameters

 - subscriber **Object**


## manageRemoteMessage

### Parameters

 - context **Context**
 - remoteMessage **Map<String, String>**

### Returns

__boolean__

## registerEventCallback

### Parameters

 - callback **EventCallback**


## getVoxeetHttp

### Returns

__VoxeetHttp__

