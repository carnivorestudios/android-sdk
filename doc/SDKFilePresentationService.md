# SDKFilePresentationService

## SDKFilePresentationService

### Parameters

 - instance **VoxeetSdk**


## onEvent

### Parameters

 - event **FilePresentationStartedEvent**


## onEvent

### Parameters

 - event **FilePresentationStoppedEvent**


## onEvent

### Parameters

 - event **FilePresentationUpdatedEvent**


## onEvent

### Parameters

 - event **FileConvertedEvent**


## getImage

### Parameters

 - fileId **String**
 - pageNumber **int**

### Returns

__String__

## getThumbnail

### Parameters

 - fileId **String**
 - pageNumber **int**

### Returns

__String__

## convertFile

### Parameters

 - file **File**

### Returns

__Promise<FilePresentationConverted>__

## startPresentation

### Parameters

 - body **FilePresentationConverted**

### Returns

__Promise<FilePresentationStarted>__

## startPresentation

### Parameters

 - body **FilePresentationConverted**
 - position **int**

### Returns

__Promise<FilePresentationStarted>__

## stopPresentation

### Parameters

 - fileId **String**

### Returns

__Promise<FilePresentationStopped>__

## updatePresentation

### Parameters

 - fileId **String**
 - position **int**

### Returns

__Promise<FilePresentationUpdated>__

