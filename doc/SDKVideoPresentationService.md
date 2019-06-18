# SDKVideoPresentationService

## SDKVideoPresentationService

### Parameters

 - instance **VoxeetSdk**


## onEvent

### Parameters

 - event **VideoPresentationStartedEvent**


## onEvent

### Parameters

 - event **VideoPresentationStoppedEvent**


## onEvent

### Parameters

 - event **VideoPresentationPausedEvent**


## onEvent

### Parameters

 - event **VideoPresentationPlayEvent**


## onEvent

### Parameters

 - event **VideoPresentationSeekEvent**


## startVideoPresentation

### Parameters

 - url **String**

### Returns

__Promise<VideoPresentationStarted>__

## stopVideoPresentation

### Returns

__Promise<VideoPresentationStopped>__

## playVideoPresentation

### Returns

__Promise<VideoPresentationPlay>__

## pauseVideoPresentation

### Parameters

 - timestamp **long**

### Returns

__Promise<VideoPresentationPaused>__

## seekVideoPresentation

### Parameters

 - timestamp **long**

### Returns

__Promise<VideoPresentationSeek>__

