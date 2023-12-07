---
title: FillLayer
second_title: Aspose.PSD for Java API Reference
description: Fill layer.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.psd.layers.filllayers/filllayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
```
public class FillLayer extends Layer
```

Fill layer. Color Fill, Gradient Fill or Pattern Fill Layer which differs by  FillSettings ([getFillSettings](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer\#getFillSettings)/[setFillSettings(IFillSettings)](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer\#setFillSettings-IFillSettings-))
## Fields

| Field | Description |
| --- | --- |
| [BlendSignature](#BlendSignature) | Represents blend mode signature. |
| [LayerHeaderSize](#LayerHeaderSize) | The layer header size. |
| [OnCreate_internalized](#OnCreate-internalized) | Occurs when image was loaded |
| [OnLoad_internalized](#OnLoad-internalized) | Occurs when image was loaded by createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Occurs when image was loaded or saved |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Occurs when credit was used |
| [resources_internalized](#resources-internalized) | The resources |
## Methods

| Method | Description |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Gets the resource associated with the specified type. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Adds the mask to current layer. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Adds the resource. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Adjust of a brightness for image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Image contrasting |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-correction of an image. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correction of an image. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Applies the layer style setting from input [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) to current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) instance. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Begins the resize process. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarization of an image with predefined threshold |
| [binarizeOtsu()](#binarizeOtsu--) | Binarization of an image with Otsu thresholding |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying  DataStreamSupporter.DataStreamContainer . |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Determines whether image can be loaded from the specified stream. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Determines whether image can be loaded from the specified stream and optionally using the specified  loadOptions . |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Determines whether image can be loaded from the specified file path. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converts to aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Creates a new image using the specified create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Creates a new image using the specified images as pages |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Creates a new image the specified images as pages. |
| [createInstance(int fillType)](#createInstance-int-) | Build a new instance of the [FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer) class by type of fill. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Creates the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class. |
| [createLayerState_internalized()](#createLayerState-internalized--) | Creates the new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Cropping the image. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop image with shifts. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Performs dithering on the current image. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Performs dithering on the current image. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Cropping the image. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Resizes the image. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Rotates, flips, or rotates and flips the image. |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Draws the image on layer. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object, is equal to this instance. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filters the specified rectangle. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Finds the assignable resource. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Finds the  PattResource  |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Finds the resource by unique key |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Gets or sets the absolute bounds. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Gets an image 32-bit ARGB pixel. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets a value for the background color. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Gets or sets the blending of clipped element. |
| [getBlendModeKey()](#getBlendModeKey--) | Gets or sets the blend mode key. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Gets the blend mode signature. |
| [getBlendingOptions()](#getBlendingOptions--) | Gets the blending options. |
| [getBottom()](#getBottom--) | Gets or sets the bottom layer position. |
| [getBounds()](#getBounds--) | Gets the image bounds. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Gets the bytes per row for full mask mode. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Gets the bytes per row. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Gets the bytes per row. |
| [getChannelInformation()](#getChannelInformation--) | Gets or sets the channel information. |
| [getChannelsCount()](#getChannelsCount--) | Gets the layer's channels count. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Gets or sets the layer clipping. |
| [getContainer()](#getContainer--) | Gets the  Image  container. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Gets the object's data stream. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Gets the deeply adjust palette. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Gets the default 32-bit ARGB pixels array. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Gets the default pixels array using partial pixel loader. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Gets the default raw data array using partial pixel loader. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Gets the default raw data array. |
| [getDisplayName()](#getDisplayName--) | Gets the display name of the layer. |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getExtraLength()](#getExtraLength--) | Gets the layer extra information length in bytes. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Gets the file format. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Gets the file format. |
| [getFileFormatInternal_internalized(System.IO.Stream stream)](#getFileFormatInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [getFillImageProcessor_internalized(IPixelsSaver imageToProcess, Rectangle bounds)](#getFillImageProcessor-internalized-com.aspose.internal.IPixelsSaver-com.aspose.psd.Rectangle-) | Gets the rendering processor for [FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer). |
| [getFillOpacity()](#getFillOpacity--) | Gets or sets the fill opacity. |
| [getFillSettings()](#getFillSettings--) | Gets the fill settings. |
| [getFillType()](#getFillType--) | Gets the type of the fill. |
| [getFiller()](#getFiller--) | Gets or sets the layer filler. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Gets rectangle which fits the current image. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Gets rectangle which fits the current image. |
| [getFlags()](#getFlags--) | Gets or sets the layer flags. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Gets the list of [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) folders hierarchy of current layer. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Gets palette from format-specific places |
| [getGUID_internalized()](#getGUID-internalized--) | Gets the unique identifier of this Layer instance. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Gets or sets the horizontal resolution, in pixels per inch, of this  RasterImage . |
| [getImageOpacity()](#getImageOpacity--) | Gets opacity of this image. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Gets the inner data transformer. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Gets the interrupt monitor. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Gets or sets the layer blending ranges data. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Gets or sets the layer creation date time. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Gets or sets the layer lock. |
| [getLayerMaskData()](#getLayerMaskData--) | Gets or sets the layer mask data. |
| [getLayerOptions()](#getLayerOptions--) | Gets the layer options. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Gets or sets the layer palette. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Gets the type of the layer. |
| [getLeft()](#getLeft--) | Gets or sets the left layer position. |
| [getLength()](#getLength--) | Gets the overall layer length in bytes. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Gets or sets the max allowed allocation for partial rotate save. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Gets the memory manager. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Gets the date and time the resource image was last modified. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Gets or sets the layer name. |
| [getOpacity()](#getOpacity--) | Gets or sets the layer opacity. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Gets the total opacity. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |
| [getPaintableImage_internalized()](#getPaintableImage-internalized--) | Gets the paintable image. |
| [getPalette()](#getPalette--) | Gets the color palette. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Gets an image pixel. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Gets or sets a value indicating whether the image components must be premultiplied. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets the progress event handler information. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Gets the progress event handler information. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Gets a proportional height. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Gets a proportional width. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Gets or sets the custom color converter |
| [getRawDataFormat()](#getRawDataFormat--) | Gets the raw data format. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Gets or sets the fallback index to use when palette index is out of bounds |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Gets or sets the indexed color converter |
| [getRawLineSize()](#getRawLineSize--) | Gets the raw line size in bytes. |
| [getResources()](#getResources--) | Gets or sets the layer resources. |
| [getRight()](#getRight--) | Gets or sets the right layer position. |
| [getRotateMode()](#getRotateMode--) | Gets or sets the rotate mode. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Gets or sets the decorative sheet color highlight in layers' list |
| [getSize()](#getSize--) | Gets the image size. |
| [getSkewAngle()](#getSkewAngle--) | Gets the skew angle. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Gets the file path of source image if it's exist. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Gets the synchronize root. |
| [getTop()](#getTop--) | Gets or sets the top layer position. |
| [getTransparentColor()](#getTransparentColor--) | Gets the image transparent color. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Gets or sets a value indicating whether to update the XMP metadata. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Gets a value indicating whether object uses memory optimization strategy |
| [getUseRawData()](#getUseRawData--) | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Gets the used palette. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Gets the venture license. |
| [getVerticalResolution()](#getVerticalResolution--) | Gets or sets the vertical resolution, in pixels per inch, of this  RasterImage . |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata. |
| [grayscale()](#grayscale--) | Transformation of an image to its grayscale representation |
| [hasAlpha()](#hasAlpha--) | Gets a value indicating whether this instance has alpha. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Gets a value indicating whether image has background color. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Gets or sets a value indicating whether this instance of image has changed after loading. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether image has transparent color. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Gets or sets the progress max value |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indicates the progress. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | Gets a value indicating whether automatic adjust palette. |
| [isCached()](#isCached--) | Gets a value indicating whether image data is cached currently. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Gets a value indicating whether raw data loading is available. |
| [isUsePalette()](#isUsePalette--) | Gets a value indicating whether the image palette is used. |
| [isVisible()](#isVisible--) | Gets or sets a value indicating whether the layer is visible |
| [isVisibleInGroup()](#isVisibleInGroup--) | Gets a value indicating whether this instance is visible in group(If layer is not in group it means root group). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a new image from the specified stream. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Loads a new image from the specified stream. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Loads a new image from the specified stream. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Loads a new image from the specified stream. |
| [load(String filePath)](#load-java.lang.String-) | Loads a new image from the specified file. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Loads a new image from the specified file. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Loads 32-bit ARGB pixels. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Loads 64-bit ARGB pixels. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Loads pixels in CMYK format. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Loads pixels in CMYK format. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Loads 32-bit ARGB pixels partially by packs. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Loads pixels partially by packs. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Loads pixels. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Loads raw image data using the partial processing mechanism. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Loads raw data. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Loads a new image from the specified stream. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Loads a new image from the specified stream. |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Merges the layer to specified layer |
| [normalizeAngle()](#normalizeAngle--) | Normalizes the angle. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalizes the angle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoke when container of this  Image  was set. |
| [onGlobalResourcesChanged_internalized(Object sender, GlobalResourceChangedEventArgs eventArgs)](#onGlobalResourcesChanged-internalized-java.lang.Object-com.aspose.internal.fileformats.psd.sections.GlobalResourceChangedEventArgs-) | Called when [global resources changed]. |
| [onResourcesChange_internalized()](#onResourcesChange-internalized--) | Called when [resources change]. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Reads the whole scan line by the specified scan line index. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Reads the whole scan line by the specified scan line index. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Removes the resource. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Resizes the image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Resizes the channels data |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Resizes the height proportionally. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Resizes the height proportionally. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Resizes the height proportionally. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Resizes the width proportionally. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Resizes the width proportionally. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Resizes the width proportionally. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Resizes the layer with the specified inverse scale. |
| [rotate(float angle)](#rotate-float-) | Rotate image around the center. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Rotate image around the center. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Saves the image data to the underlying stream. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the object's data to the specified stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Saves the object's data to the specified stream. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(String filePath)](#save-java.lang.String-) | Saves the object's data to the specified file location. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Saves the object's data to the specified file location. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Saves the 32-bit ARGB pixels. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Saves the pixels. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Saves the pixels. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Saves the pixels. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Saves the raw data. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Saves data to the specified stream container. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Gets or sets the absolute bounds. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Sets an image 32-bit ARGB pixel for the specified position. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Sets a value indicating whether automatic adjust palette. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Gets or sets a value indicating whether image has background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Gets or sets a value for the background color. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Gets or sets the blending of clipped element. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Gets or sets the blend mode key. |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the bottom layer position. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Gets or sets the channel information. |
| [setClipping(byte value)](#setClipping-byte-) | Gets or sets the layer clipping. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Sets the  Image  container. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Sets the data loader directly. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Sets the object's data stream. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets the display name of the layer. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Gets the fill opacity. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Gets the fill settings. |
| [setFiller(byte value)](#setFiller-byte-) | Gets or sets the layer filler. |
| [setFlags(byte value)](#setFlags-byte-) | Gets or sets the layer flags. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Sets palette into format-specific places |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Gets or sets the horizontal resolution, in pixels per inch, of this  RasterImage . |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Sets a value indicating whether [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Gets or sets a value indicating whether this instance of image has changed after loading. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Sets the inner data transformer. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Sets the interrupt monitor. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Gets or sets the layer blending ranges data. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Gets or sets the layer creation date time. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Gets or sets the layer lock (Note that if flag LayerFlags.TransparencyProtected is set it will be overritten by layer lock flag. |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Gets or sets the layer mask data. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Gets or sets the layer palette. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the left layer position. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Gets or sets the max allowed allocation for partial rotate save. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Sets the memory manager. |
| [setName(String name)](#setName-java.lang.String-) | Sets the layer name. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Gets or sets the layer name. |
| [setOpacity(byte value)](#setOpacity-byte-) | Gets or sets the layer opacity. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Sets the color palette. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Sets the image palette. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Sets an image pixel for the specified position. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Gets or sets a value indicating whether the image components must be premultiplied. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Gets or sets the custom color converter |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Gets or sets the fallback index to use when palette index is out of bounds |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Gets or sets the indexed color converter |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Sets the resolution for this  RasterImage . |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Gets or sets the layer resources. |
| [setRight(int value)](#setRight-int-) | Gets or sets the right layer position. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Gets or sets the rotate mode. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Gets or sets the decorative sheet color highlight in layers' list |
| [setTop(int value)](#setTop-int-) | Gets or sets the top layer position. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Gets a value indicating whether image has transparent color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Gets the image transparent color. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Gets or sets a value indicating whether to update the XMP metadata. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | All Aspose products should implement this method. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Gets or sets the vertical resolution, in pixels per inch, of this  RasterImage . |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets a value indicating whether the layer is visible |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata. |
| [shallowCopy()](#shallowCopy--) | Creates a shallow copy of the current Layer. |
| [toBitmap()](#toBitmap--) | Converts raster image to the bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [update()](#update--) | Updates Fill Layer Pixels Data according to actual [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings). |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Updates the blending options after layer or global resources change. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Writes the whole scan line to the specified scan line index. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Writes the whole scan line to the specified scan line index. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Represents blend mode signature.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


The layer header size.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Occurs when image was loaded

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Occurs when image was loaded by createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Occurs when image was loaded or saved

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Occurs when credit was used

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


The resources

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Gets the resource associated with the specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| resource | T[] | When this method returns, contains the resource associated with the specified key type, if the key is found; otherwise, returns null.

 T : The key type of the value to get. |

**Returns:**
boolean -   if contains an resource with the specified type; otherwise,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Adds the mask to current layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | The layer mask. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Adds the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | The resource. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Adjust of a brightness for image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Image contrasting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contrast | float | Contrast value (in range [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma-correction of an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-correction of an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | float | Gamma for red channel coefficient |
| gammaGreen | float | Gamma for green channel coefficient |
| gammaBlue | float | Gamma for blue channel coefficient |

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Applies the layer style setting from input [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) to current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | The layer state with new style. |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Begins the resize process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new image width. |
| newHeight | int | The new image height. |

**Returns:**
com.aspose.internal.IResizeController - The resize controller.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | int | The size of s x s window of pixels centered around this pixel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarization of an image with predefined threshold

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarization of an image with Otsu thresholding

### cacheData() {#cacheData--}
```
public void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying  DataStreamSupporter.DataStreamContainer .

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Determines whether image can be loaded from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load from. |

**Returns:**
boolean -  true  if image can be loaded from the specified stream; otherwise,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Determines whether image can be loaded from the specified stream and optionally using the specified  loadOptions .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load from. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
boolean -  true  if image can be loaded from the specified stream; otherwise,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Determines whether image can be loaded from the specified file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |

**Returns:**
boolean -  true  if image can be loaded from the specified file; otherwise,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
boolean -  true  if image can be loaded from the specified file; otherwise,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Determines whether image can be saved to the specified file format represented by the passed save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options to use. |

**Returns:**
boolean -  true  if image can be saved to the specified file format represented by the passed save options; otherwise,  false .
### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Converts to aps.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options. |
| mode | int | The mode. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The clipping rectangle. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - The APS page.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Creates a new image using the specified create options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The image options. |
| width | int | The width. |
| height | int | The height. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Creates a new image using the specified images as pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | The images. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Creates a new image the specified images as pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | The images. |
| disposeImages | boolean | if set to  true  [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance(int fillType) {#createInstance-int-}
```
public static FillLayer createInstance(int fillType)
```


Build a new instance of the [FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer) class by type of fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillType | int | The type of fill layer. |

**Returns:**
[FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer) - Returns a new instance of the [FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer) class by type of fill.
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Creates the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | The header. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The palette. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | The LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Creates the new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| width | int |  |
| height | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Cropping the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Crop image with shifts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | int | The left shift. |
| rightShift | int | The right shift. |
| topShift | int | The top shift. |
| bottomShift | int | The bottom shift. |

### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Performs dithering on the current image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | The dithering method. |
| bitsCount | int | The final bits count for dithering. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Performs dithering on the current image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | The dithering method. |
| bitsCount | int | The final bits count for dithering. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The custom palette for dithering. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Cropping the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | The resize settings. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Rotates, flips, or rotates and flips the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotate flip type. |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Draws the image on layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | The location. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The image. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean -  true  if the specified Object is equal to this instance; otherwise,  false .
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filters the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | The options. |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Finds the assignable resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | The type. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Finds the  PattResource 

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Finds the resource by unique key

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeToolKey | int | The type tool key. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Gets or sets the absolute bounds.

Value: The absolute bounds.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Gets an image 32-bit ARGB pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |

**Returns:**
int - The 32-bit ARGB pixel for the specified location.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets or sets a value for the background color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

Value: The image bits per pixel count.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Gets or sets the blending of clipped element.

Value: The blending of clipped element.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Gets or sets the blend mode key.

Value: The blend mode key.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Gets the blend mode signature.

Value: The blend mode signature.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Gets the blending options.

Value: The blending options.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Gets or sets the bottom layer position.

Value: The bottom layer position.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets the image bounds.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Gets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Returns:**
int - the buffer size hint which is defined max allowed size for all internal buffers.
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Gets the bytes per row for full mask mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitDepth | int | The bit depth. |

**Returns:**
int - Bytes needed for storing 1 row
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Gets the bytes per row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitDepth | int | The bit depth. |

**Returns:**
int - Bytes needed for storing 1 row
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Gets the bytes per row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitDepth | int | The bit depth. |

**Returns:**
int - Bytes needed for storing 1 row
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Gets or sets the channel information.

Value: The channel information.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Gets the layer's channels count.

Value: The layer's channels count.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Gets or sets the layer clipping. 0 = base, 1 = non-base.

Value: The layer clipping.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Gets the  Image  container.

Value: The  Image  container.

If this property is not null it indicates the image is contained whithin another image.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Gets the object's data stream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Gets the deeply adjust palette.

**Returns:**
boolean - The deeply adjust palette.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Gets the default 32-bit ARGB pixels array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to get pixels for. |

**Returns:**
int[] - The default pixels array.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Gets the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Gets the default pixels array using partial pixel loader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to get pixels for. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | The partial pixel loader. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Gets the default raw data array using partial pixel loader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to get pixels for. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | The partial raw data loader. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | The raw data settings. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Gets the default raw data array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to get raw data for. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | The raw data settings. |

**Returns:**
byte[] - The default raw data array.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name of the layer.

Value: The display name of the layer.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Gets the layer extra information length in bytes.

Value: The extra layer length.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Gets the file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream.

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether stream may be loaded. |

**Returns:**
long - The determined file format.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Gets the file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path.

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether file may be loaded. |

**Returns:**
long - The determined file format.
### getFileFormatInternal_internalized(System.IO.Stream stream) {#getFileFormatInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormatInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
long
### getFillImageProcessor_internalized(IPixelsSaver imageToProcess, Rectangle bounds) {#getFillImageProcessor-internalized-com.aspose.internal.IPixelsSaver-com.aspose.psd.Rectangle-}
```
public final IPartialProcessor getFillImageProcessor_internalized(IPixelsSaver imageToProcess, Rectangle bounds)
```


Gets the rendering processor for [FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageToProcess | com.aspose.internal.IPixelsSaver | The image to rendering to. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds to process. |

**Returns:**
com.aspose.internal.IPartialProcessor - Return the rendering processor for [FillLayer](../../com.aspose.psd.fileformats.psd.layers.filllayers/filllayer).
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Gets or sets the fill opacity.

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Gets the fill settings.

Value: The fill settings.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getFillType() {#getFillType--}
```
public final int getFillType()
```


Gets the type of the fill.

Value: The type of the fill.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Gets or sets the layer filler.

Value: The layer filler.

**Returns:**
byte
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Gets rectangle which fits the current image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to get fitting rectangle for. |
| width | int | The object width. |
| height | int | The object height. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Gets rectangle which fits the current image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to get fitting rectangle for. |
| pixels | int[] | The 32-bit ARGB pixels. |
| width | int | The object width. |
| height | int | The object height. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Gets or sets the layer flags. bit 0 = transparency protected; bit 1 = visible; bit 2 = obsolete; bit 3 = 1 for Photoshop 5.0 and later, tells if bit 4 has useful information; bit 4 = pixel data irrelevant to appearance of document.

Value: The layer flags.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Gets the list of [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) folders hierarchy of current layer.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Returns the list of [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) folders hierarchy of current layer.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Gets palette from format-specific places

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Gets the unique identifier of this Layer instance.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Gets or sets the header.

Value: The header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

Value: The image height.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Gets or sets the horizontal resolution, in pixels per inch, of this  RasterImage .

**Returns:**
double - The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Gets opacity of this image.

**Returns:**
float - The opacity value between 0.0 (fully transparent) and 1.0 (fully opaque).
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Gets the inner data transformer.

Value: The inner data transformer.

**Returns:**
com.aspose.internal.IInnerDataTransformer - the inner data transformer.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Gets the interrupt monitor.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Gets or sets the layer blending ranges data.

Value: The layer blending ranges data.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Gets or sets the layer creation date time.

Value: The layer's creation date time. If there is no data about creation DateTime then returns Unix Time first epoch

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Gets or sets the layer lock. Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag. To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags |= LayerFlags.TransparencyProtected

Value: The layer lock.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Gets or sets the layer mask data.

Value: The layer mask data.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Gets the layer options.

Value: The layer options.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Gets or sets the layer palette.

Value: The layer palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Gets the type of the layer.

Value: The type of the layer.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Gets or sets the left layer position.

Value: The left layer position.

**Returns:**
int
### getLength() {#getLength--}
```
public final int getLength()
```


Gets the overall layer length in bytes.

**Returns:**
int
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Gets or sets the max allowed allocation for partial rotate save.

**Returns:**
int - The max allowed allocation for partial rotate save.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Gets the memory manager.

Value: The memory manager.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - the memory manager.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Gets the date and time the resource image was last modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useDefault | boolean | if set to  true  uses the information from FileInfo as default value. |

**Returns:**
java.util.Date - The date and time the resource image was last modified.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the layer name.

Value: The layer name.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Gets or sets the layer opacity. 0 = transparent, 255 = opaque.

Value: The layer opacity.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Gets the total opacity. The total opacity is the multiplication of the Layer Opacity and Layer Fill Opacity. It used for layer blending

Value: The total opacity.

**Returns:**
byte
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the  DataStreamSupporter.Save(string)  method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the  Image.Save(string, ImageOptionsBase)  method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized() {#getPaintableImage-internalized--}
```
public Image getPaintableImage_internalized()
```


Gets the paintable image.

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Gets the color palette. The color palette is not used when pixels are represented directly.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Gets an image pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Gets or sets a value indicating whether the image components must be premultiplied.

**Returns:**
boolean -  true  if the image components must be premultiplied; otherwise,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Gets the progress event handler information.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Gets the progress event handler information.

Value: The progress event handler information.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Gets a proportional height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |
| newWidth | int | The new width. |

**Returns:**
int - The proportional height.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Gets a proportional width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |
| newHeight | int | The new height. |

**Returns:**
int - The proportional width.
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Gets or sets the custom color converter

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Gets the raw data format.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Gets the current raw data settings. Note when using these settings the data loads without conversion.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Gets or sets the fallback index to use when palette index is out of bounds

**Returns:**
int - The fallback index to use when palette index is out of bounds
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Gets or sets the indexed color converter

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Gets the raw line size in bytes.

**Returns:**
int - The raw line size in bytes.
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Gets or sets the layer resources.

Value: The layer resources.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public final int getRight()
```


Gets or sets the right layer position.

Value: The right layer position.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Gets or sets the rotate mode.

**Returns:**
int - The rotate mode.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Gets or sets the decorative sheet color highlight in layers' list

Value: The sheet color highlight.

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


Gets the image size.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning.

**Returns:**
float - The skew angle, in degrees.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Gets the file path of source image if it's exist. Returns an empty string if can't find the source path.

**Returns:**
java.lang.String - The file path of source image.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Gets the synchronize root.

Value: The synchronize root.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public final int getTop()
```


Gets or sets the top layer position.

Value: The top layer position.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Gets the image transparent color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Gets or sets a value indicating whether to update the XMP metadata.

**Returns:**
boolean -  true  if update the XMP metadata; otherwise,  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Gets a value indicating whether object uses memory optimization strategy

Value:  true  if object uses memory optimization strategy; otherwise,  false .

**Returns:**
boolean - a value indicating whether object uses memory optimization strategy
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Gets or sets a value indicating whether to use raw data loading when the raw data loading is available.

**Returns:**
boolean -  true  if use raw data loading when the raw data loading is available.; otherwise,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Gets the used palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Gets the venture license.

**Returns:**
java.lang.Object - Teh venture license as object.
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets or sets the vertical resolution, in pixels per inch, of this  RasterImage .

**Returns:**
double - The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

Value: The image width.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation of an image to its grayscale representation

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets a value indicating whether this instance has alpha.

Value:  true  if this instance has alpha; otherwise,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Gets a value indicating whether image has background color.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Gets or sets a value indicating whether this instance of image has changed after loading.

**Returns:**
boolean -  true  if this instance has image changed; otherwise,  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gets a value indicating whether image has transparent color.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Gets or sets the progress max value

Value: The progress max value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Indicates the progress.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


Gets a value indicating whether automatic adjust palette.

**Returns:**
boolean -  true  if enable automatic adjust palette; otherwise,  false .
### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether image data is cached currently.

**Returns:**
boolean -  true  if image data is cached; otherwise,  false .
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Gets a value indicating whether raw data loading is available.

**Returns:**
boolean -  true  if this raw data loading is available; otherwise,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Gets a value indicating whether the image palette is used.

Value:  true  if the palette is used in the image; otherwise,  false .

**Returns:**
boolean - a value indicating whether the image palette is used.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Gets or sets a value indicating whether the layer is visible

Value:  true  if this instance is visible; otherwise,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Gets a value indicating whether this instance is visible in group(If layer is not in group it means root group).

Value:  true  if this instance is visible in group; otherwise,  false .

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Loads a new image from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Loads a new image from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Loads a new image from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The file to load image from. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Loads a new image from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The file to load image from. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Loads a new image from the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load image from. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Loads a new image from the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load image from. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Loads 32-bit ARGB pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns:**
int[] - The loaded 32-bit ARGB pixels array.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Loads 64-bit ARGB pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns:**
long[] - The loaded 64-bit ARGB pixels array.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Loads pixels in CMYK format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns:**
int[] - The loaded CMYK pixels presentes as 32-bit inateger values.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Loads pixels in CMYK format. This method is deprecated. Please use more effective the  loadCmyk32Pixels(Rectangle)  method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns:**
com.aspose.psd.CmykColor[] - The loaded CMYK pixels array.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Loads 32-bit ARGB pixels partially by packs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The desired rectangle. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | The 32-bit ARGB pixel loader. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Loads pixels partially by packs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The desired rectangle. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | The pixel loader. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Loads pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load pixels from. |

**Returns:**
com.aspose.psd.Color[] - The loaded pixels array.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Loads raw image data using the partial processing mechanism.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The desired rectangular area of the image to load data from. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | The raw data settings. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | The raw data loader. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Loads raw data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load raw data from. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | The dest image bounds. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | The raw data loader. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Loads a new image from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to load image from. |
| startPosition | long | The start position to load image from. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Loads a new image from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to load image from. |
| startPosition | long | The start position to load image from. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Merges the layer to specified layer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer to merge into. |

### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [.getSkewAngle](../../null/\#getSkewAngle) and [.rotate(float)](../../null/\#rotate-float-) methods.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [.getSkewAngle](../../null/\#getSkewAngle) and [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) methods.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeProportionally | boolean | if set to  true  you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Color of the background. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Invoke when container of this  Image  was set.

### onGlobalResourcesChanged_internalized(Object sender, GlobalResourceChangedEventArgs eventArgs) {#onGlobalResourcesChanged-internalized-java.lang.Object-com.aspose.internal.fileformats.psd.sections.GlobalResourceChangedEventArgs-}
```
public final void onGlobalResourcesChanged_internalized(Object sender, GlobalResourceChangedEventArgs eventArgs)
```


Called when [global resources changed].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object | The sender. |
| eventArgs | com.aspose.internal.fileformats.psd.sections.GlobalResourceChangedEventArgs | The EventArgs instance containing the event data. |

### onResourcesChange_internalized() {#onResourcesChange-internalized--}
```
public void onResourcesChange_internalized()
```


Called when [resources change].

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Reads the whole scan line by the specified scan line index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Zero based index of the scan line. |

**Returns:**
int[] - The scan line 32-bit ARGB color values array.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Reads the whole scan line by the specified scan line index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Zero based index of the scan line. |

**Returns:**
com.aspose.psd.Color[] - The scan line pixel color values array.
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Removes the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | The resource. |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Old color to be replaced. |
| oldColorDiff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| newColor | [Color](../../com.aspose.psd/color) | New color to replace old color with. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldColorArgb | int | Old color ARGB value to be replaced. |
| oldColorDiff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| newColorArgb | int | New color ARGB value to replace old color with. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | New color to replace non transparent colors with. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorArgb | int | New color ARGB value to replace non transparent colors with. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Resizes the image. The default  ResizeType.LeftTopToLeftTop  is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | The resize settings. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Resizes the channels data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The rect. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Resizes the height proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Resizes the height proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | The image resize settings. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Resizes the height proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |
| resizeType | int | Type of the resize. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Resizes the width proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Resizes the width proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | The image resize settings. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Resizes the width proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| resizeType | int | Type of the resize. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Resizes the layer with the specified inverse scale. (new width = old width / scale; new height = old height / scale)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | double | The scale X. |
| scaleY | double | The scale Y. |
| resizeType | int | Type of the resize. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotate image around the center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotate image around the center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | boolean | if set to  true  you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Color of the background. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rotates, flips, or rotates and flips the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Saves the image data to the underlying stream.

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the object's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save the object's data to. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save the image's data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options. |

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dstStream | java.io.OutputStream | The stream to save the image's data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Saves the object's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The stream to save the object's data to. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The file to save the image's data to. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The file to save the image's data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves the object's data to the specified file location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the object's data to. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Saves the object's data to the specified file location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the object's data to. |
| overWrite | boolean | if set to  true  over write the file contents, otherwise append will occur. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Saves the 32-bit ARGB pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to save pixels to. |
| pixels | int[] | The 32-bit ARGB pixels array. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Saves the pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to save pixels to. |
| pixels | int[] | The CMYK pixels presented as the 32-bit integer values. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Saves the pixels. This method is deprecated. Please use more effective the  saveCmyk32Pixels(Rectangle, int[])  method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to save pixels to. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | The CMYK pixels array. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Saves the pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to save pixels to. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | The pixels array. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Saves the raw data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The raw data. |
| dataOffset | int | The starting raw data offset. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The raw data rectangle. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | The raw data settings the data is in. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Saves data to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| psdVersion | int | The PSD version. |
| bitDepth | int | The bit depth. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Gets or sets the absolute bounds.

Value: The absolute bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Sets an image 32-bit ARGB pixel for the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| argb32Color | int | The 32-bit ARGB pixel for the specified position. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Sets a value indicating whether automatic adjust palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if enable automatic adjust palette; otherwise,  false . |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Gets or sets a value indicating whether image has background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Gets or sets a value for the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Gets or sets the blending of clipped element.

Value: The blending of clipped element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Gets or sets the blend mode key.

Value: The blend mode key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Gets or sets the bottom layer position.

Value: The bottom layer position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the buffer size hint which is defined max allowed size for all internal buffers. |

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Gets or sets the channel information.

Value: The channel information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Gets or sets the layer clipping. 0 = base, 1 = non-base.

Value: The layer clipping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Sets the  Image  container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | The  Image  container. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Sets the data loader directly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | The data loader. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Sets the object's data stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | The object's data stream. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Gets or sets the display name of the layer.

Value: The display name of the layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Gets the fill opacity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public void setFillSettings(IFillSettings value)
```


Gets the fill settings.

Value: The fill settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Gets or sets the layer filler.

Value: The layer filler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Gets or sets the layer flags. bit 0 = transparency protected; bit 1 = visible; bit 2 = obsolete; bit 3 = 1 for Photoshop 5.0 and later, tells if bit 4 has useful information; bit 4 = pixel data irrelevant to appearance of document.

Value: The layer flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Sets palette into format-specific places

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | New 32-bit ARGB palette. |

**Returns:**
boolean
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Gets or sets the header.

Value: The header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Gets or sets the horizontal resolution, in pixels per inch, of this  RasterImage .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Sets a value indicating whether [ignore after save].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if [ignore after save]; otherwise,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Gets or sets a value indicating whether this instance of image has changed after loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if this instance has image changed; otherwise,  false . |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Sets the inner data transformer.

Value: The inner data transformer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.IInnerDataTransformer | the inner data transformer. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Sets the interrupt monitor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | the interrupt monitor. |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Gets or sets the layer blending ranges data.

Value: The layer blending ranges data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Gets or sets the layer creation date time.

Value: The layer's creation date time. If there is no data about creation DateTime then returns Unix Time first epoch

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Gets or sets the layer lock (Note that if flag LayerFlags.TransparencyProtected is set it will be overritten by layer lock flag. To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags |= LayerFlags.TransparencyProtected

Value: The layer lock.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Gets or sets the layer mask data.

Value: The layer mask data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Gets or sets the layer palette.

Value: The layer palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Gets or sets the left layer position.

Value: The left layer position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Gets or sets the max allowed allocation for partial rotate save.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The max allowed allocation for partial rotate save. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Sets the memory manager.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | The memory manager. |
| needDispose | boolean | if set to  true  [need dispose]. |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Sets the layer name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The layer name. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Gets or sets the layer name.

Value: The layer name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Gets or sets the layer opacity. 0 = transparent, 255 = opaque.

Value: The layer opacity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Sets the color palette. The color palette is not used when pixels are represented directly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Sets the image palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to  true  colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Sets an image pixel for the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| color | [Color](../../com.aspose.psd/color) | The pixel color for the specified position. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Gets or sets a value indicating whether the image components must be premultiplied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if the image components must be premultiplied; otherwise,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Gets or sets the custom color converter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | The custom color converter |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Gets or sets the fallback index to use when palette index is out of bounds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The fallback index to use when palette index is out of bounds |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Gets or sets the indexed color converter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | The indexed color converter |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Sets the resolution for this  RasterImage .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the  RasterImage . |
| dpiY | double | The vertical resolution, in dots per inch, of the  RasterImage . |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Gets or sets the layer resources.

Value: The layer resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Gets or sets the right layer position.

Value: The right layer position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Gets or sets the rotate mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The rotate mode. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Gets or sets the decorative sheet color highlight in layers' list

Value: The sheet color highlight.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Gets or sets the top layer position.

Value: The top layer position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Gets a value indicating whether image has transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Gets the image transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Gets or sets a value indicating whether to update the XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if update the XMP metadata; otherwise,  false . |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Gets or sets a value indicating whether to use raw data loading when the raw data loading is available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if use raw data loading when the raw data loading is available.; otherwise,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


All Aspose products should implement this method. It is called by a GroupDocs product to indicate whether GroupDocs itself is licensed or not and specify a custom watermark. When GroupDocs is licensed, this document instance should behave as licensed too even if the Aspose product is not licensed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Gets or sets the vertical resolution, in pixels per inch, of this  RasterImage .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Gets or sets a value indicating whether the layer is visible

Value:  true  if this instance is visible; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | The XMP metadata. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Creates a shallow copy of the current Layer. Please   for explanation.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Converts raster image to the bitmap.

**Returns:**
java.awt.image.BufferedImage - The bitmap
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### update() {#update--}
```
public final void update()
```


Updates Fill Layer Pixels Data according to actual [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings).

### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Updates the blending options after layer or global resources change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Writes the whole scan line to the specified scan line index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Zero based index of the scan line. |
| argb32Pixels | int[] | The 32-bit ARGB colors array to write. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Writes the whole scan line to the specified scan line index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Zero based index of the scan line. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | The pixel colors array to write. |

