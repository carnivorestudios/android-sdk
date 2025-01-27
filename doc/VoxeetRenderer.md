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


## forceRecalculateWidthHeight


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

## setFirstFrameRendered

### Parameters

 - isFirstFrameRendered **boolean**


## setDeltaX

### Parameters

 - dx **float**


## setDeltaY

### Parameters

 - dy **float**


## getTranslationY

### Returns

__float__

## getTranslationX

### Returns

__float__

## getRendererScaleX

### Returns

__float__

## getRendererScaleY

### Returns

__float__

## getRotatedFrameWidth

### Returns

__float__

## getRotatedFrameHeight

### Returns

__float__

