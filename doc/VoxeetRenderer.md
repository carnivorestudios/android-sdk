# VoxeetRenderer

## VoxeetRenderer

### Parameters

 - context **Context**


## VoxeetRenderer

### Parameters

 - context **Context**
 - attrs **AttributeSet**


## init

### Parameters

 - sharedContext **EglBaseMethods.Context**
 - rendererEvents **RendererCommon.RendererEvents**


## init

### Parameters

 - sharedContext **EglBaseMethods.Context**
 - rendererEvents **RendererCommon.RendererEvents**
 - configAttributes **int[]**
 - drawer **RendererCommon.GlDrawer**


## release


## addFrameListener

### Parameters

 - listener **SafeRenderFrameEglRenderer.FrameListener**
 - scale **float**
 - drawerParam **RendererCommon.GlDrawer**


## addFrameListener

### Parameters

 - listener **SafeRenderFrameEglRenderer.FrameListener**
 - scale **float**


## removeFrameListener

### Parameters

 - listener **SafeRenderFrameEglRenderer.FrameListener**


## setEnableHardwareScaler

### Parameters

 - enabled **boolean**


## setMirror

### Parameters

 - mirror **boolean**


## isMirror

### Returns

__boolean__

## isFirstFrameRendered

### Returns

__boolean__

## setScalingType

### Parameters

 - scalingType **RendererCommon.ScalingType**


## setScalingType

### Parameters

 - scalingTypeMatchOrientation **RendererCommon.ScalingType**
 - scalingTypeMismatchOrientation **RendererCommon.ScalingType**


## getScalingType

### Returns

__RendererCommon.ScalingType__

## setFpsReduction

### Parameters

 - fps **float**


## disableFpsReduction


## pauseVideo


## onFrame

### Parameters

 - frame **VideoFrame**


## onSurfaceTextureAvailable

### Parameters

 - surface **SurfaceTexture**
 - width **int**
 - height **int**


## onSurfaceTextureSizeChanged

### Parameters

 - surface **SurfaceTexture**
 - width **int**
 - height **int**


## onSurfaceTextureDestroyed

### Parameters

 - surface **SurfaceTexture**

### Returns

__boolean__

## onSurfaceTextureUpdated

### Parameters

 - surface **SurfaceTexture**


## clearImage


## getScreenWidth

### Returns

__int__

## getScreenHeight

### Returns

__int__

