---
title: PsdImage
second_title: Aspose.PSD for Java API Reference
description: Defines the PsdImage class that provides the ability to load edit save PSD files as well as update properties add watermarks perform graphics operations or convert one file format to another.
type: docs
weight: 14
url: /java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as update properties, add watermarks, perform graphics operations or convert one file format to another. Aspose.PSD supports import as a layer and export to the following formats: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text
## Constructors

| Constructor | Description |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in path). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in path) with constructor parameters. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in stream). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in stream) with constructor parameters. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from existing raster image (not psd image) with RGB color mode with 4 channels 8 bit/channel and no compression. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from existing raster image (not psd image) with constructor parameters. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class with specified width and height. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class with specified width,height, paletter, color mode, channels count and channels bit-length and specified compression mode parameters. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | The default encoding name |
| [DefaultVersion](#DefaultVersion) | The default PSD version. |
| [OnCreate_internalized](#OnCreate-internalized) | Occurs when image was loaded |
| [OnLoad_internalized](#OnLoad-internalized) | Occurs when image was loaded by createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Occurs when image was loaded or saved |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Occurs when credit was used |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | The object that can be used to synchronize access to the layers. |
| [horizontalResolution](#horizontalResolution) |  |
## Methods

| Method | Description |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Adds the black white adjustment layer. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Adds the brightness/contrast adjustment layer. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Adds the channel mixer adjustment layer with default parameters |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Adds the color balance adjustment layer. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Adds the Curves Adjustment layer. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Adds the exposure adjustment layer. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Adds the hue/saturation adjustment layer. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Adds an invert adjustment layer. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Adds the layer. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Adds the layer group. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Adds the layer at the index. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Adds the Levels adjustment layer. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Adds the photofilter layer. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Adds Posterize Adjustment layer. |
| [addRegularLayer()](#addRegularLayer--) | Adds a new regular layer. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Adds the selective color adjustment layer. |
| [addShapeLayer()](#addShapeLayer--) | Add empty Shape layer. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Adds a new Text layer. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Adds the Threshold adjustment layer. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Adds the Vibrance adjustment layer. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Adjust of a brightness for image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Image contrasting |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-correction of an image. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correction of an image. |
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
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Converts this image format to the one specified in options. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converts to aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Creates a new image using the specified create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Creates a new image using the specified images as pages |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Creates a new image the specified images as pages. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Creates the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filters the specified rectangle. |
| [flattenImage()](#flattenImage--) | Flattens all layers. |
| [getActiveLayer()](#getActiveLayer--) | Gets or sets the active layer. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Gets an image 32-bit ARGB pixel. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Gets a value indicating whether automatic adjust palette. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets a value for the background color. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Gets the bits per channel. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getBounds()](#getBounds--) | Gets the image bounds. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getChannelsCount()](#getChannelsCount--) | Gets the PSD channels count. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Gets or sets the CMYK color profile for CMYK PSD images. |
| [getColorMode()](#getColorMode--) | Gets or sets the color mode. |
| [getCompression()](#getCompression--) | Gets the compression method. |
| [getContainer()](#getContainer--) | Gets the  Image  container. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Gets the current image options. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Gets the object's data stream. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Gets the deeply adjust palette. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Gets the default 32-bit ARGB pixels array. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Gets the default pixels array using partial pixel loader. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Gets the default raw data array using partial pixel loader. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Gets the default raw data array. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Gets or sets the default replacement font. |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Gets the file format. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Gets the file format. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Gets the file format. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Gets rectangle which fits the current image. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Gets rectangle which fits the current image. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Gets palette from format-specific places |
| [getGlobalAngle()](#getGlobalAngle--) | Gets or sets the global angle. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Gets the global layer mask info. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Gets or sets the global layer resources. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Gets or sets the GRAY (monochrome) color profile for Grayscale PSD images. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Gets or sets the horizontal resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Gets or sets the PSD layers. |
| [getImageOpacity()](#getImageOpacity--) | Gets opacity of this image. |
| [getImageResources()](#getImageResources--) | Gets or sets the PSD image resources. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Gets the inner data transformer. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Gets the interrupt monitor. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Gets the layer and mask. |
| [getLayers()](#getLayers--) | Gets or sets the PSD layers. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Gets the linked layers manager. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Gets or sets the max allowed allocation for partial rotate save. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Gets the memory manager. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Gets the date and time the resource image was last modified. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Gets the paintable image. |
| [getPalette()](#getPalette--) | Gets the color palette. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Gets an image pixel. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Gets or sets a value indicating whether the image components must be premultiplied. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Creates the private font cache. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets the progress event handler information. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Gets the progress event handler information. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Gets a proportional height. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Gets a proportional width. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Gets or sets the PSD header. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Gets or sets the custom color converter |
| [getRawDataFormat()](#getRawDataFormat--) | Gets the raw data format. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Gets or sets the fallback index to use when palette index is out of bounds |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Gets or sets the indexed color converter |
| [getRawLineSize()](#getRawLineSize--) | Gets the raw line size in bytes. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Gets or sets the RGB color profile for CMYK PSD images. |
| [getRotateMode()](#getRotateMode--) | Gets or sets the rotate mode. |
| [getSize()](#getSize--) | Gets the image size. |
| [getSkewAngle()](#getSkewAngle--) | Gets the skew angle. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Gets the smart object provider. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Gets the file path of source image if it's exist. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Gets the synchronize root. |
| [getTimeline()](#getTimeline--) | Gets the  Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Gets the image transparent color. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Gets or sets a value indicating whether to update the XMP metadata. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Gets updated resources with brand new resource block. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Gets a value indicating whether object uses memory optimization strategy |
| [getUseRawData()](#getUseRawData--) | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Gets the used palette. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Gets the venture license. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [getVerticalResolution()](#getVerticalResolution--) | Gets or sets the vertical resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata. |
| [grayscale()](#grayscale--) | Transformation of an image to its grayscale representation |
| [hasAlpha()](#hasAlpha--) | Gets or sets the vertical resolution, in pixels per inch, of this  RasterImage . |
| [hasBackgroundColor()](#hasBackgroundColor--) | Gets a value indicating whether image has background color. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Gets or sets a value indicating whether this instance of image has changed after loading. |
| [hasTransparencyData()](#hasTransparencyData--) | Gets or sets a value indicating whether first alpha channel contains the transparency data for the merged result when specifying layers data. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether image has transparent color. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Gets or sets the progress max value |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indicates the progress. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Inserts the layer after the specified layer with all preparations |
| [isCached()](#isCached--) | Gets a value indicating whether image data is cached currently. |
| [isFlatten()](#isFlatten--) | Gets a value indicating whether psd image is flattened. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Gets a value indicating whether raw data loading is available. |
| [isUsePalette()](#isUsePalette--) | Gets a value indicating whether the image palette is used. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
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
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Merges the layers. |
| [normalizeAngle()](#normalizeAngle--) | Normalizes the angle. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalizes the angle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoke when container of this [Image](../../com.aspose.psd/image) was set. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Reads the whole scan line by the specified scan line index. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Reads the whole scan line by the specified scan line index. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Removes the global text engine resource - Method is used for some text-layered psd files, that can not be opened in Adobe Photoshop after processing (almostly for absent fonts text layers related). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Resizes the image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
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
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the object's data to the specified stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Saves the image's data to the specified stream in the specified file format according to save options. |
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
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Gets or sets the active layer. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Sets an image 32-bit ARGB pixel for the specified position. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Sets a value indicating whether automatic adjust palette. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Gets or sets a value indicating whether image has background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Gets or sets a value for the background color. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Gets or sets the CMYK color profile for CMYK PSD images. |
| [setColorMode(short value)](#setColorMode-short-) | Gets or sets the color mode. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Sets the  Image  container. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Sets the data loader directly. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Sets the object's data stream. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Sets palette into format-specific places |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | The global angle. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Gets or sets the global layer resources. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | The GRAY (monochrome) color profile for Grayscale PSD images. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Gets or sets the horizontal resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Sets a value indicating whether [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Gets or sets a value indicating whether this instance of image has changed after loading. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Gets or sets the PSD image resources. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Sets the inner data transformer. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Sets the interrupt monitor. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Gets or sets the PSD layers. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Gets or sets the max allowed allocation for partial rotate save. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Sets the memory manager. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Sets the color palette. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Sets the image palette. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Sets an image pixel for the specified position. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Gets or sets a value indicating whether the image components must be premultiplied. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Gets or sets the custom color converter |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Gets or sets the fallback index to use when palette index is out of bounds |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Gets or sets the indexed color converter |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Sets the resolution for this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Gets or sets the RGB color profile for CMYK PSD images. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Gets or sets the rotate mode. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Gets or sets a value indicating whether first alpha channel contains the transparency data for the merged result when specifying layers data. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Gets a value indicating whether image has transparent color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Gets the image transparent color. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Gets or sets a value indicating whether to update the XMP metadata. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Sets the venture license. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the version. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Gets or sets the vertical resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata. |
| [toBitmap()](#toBitmap--) | Converts raster image to the bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Writes the whole scan line to the specified scan line index. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Writes the whole scan line to the specified scan line index. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in path). Used to initialize psd image with default parameters - Color mode - rgb, 4 channels, 8 bit per channel, Compression - Raw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load pixel and palette data from and initialize with. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in path) with constructor parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load pixel and palette data from and initialize with. |
| colorMode | short | The color mode. |
| channelBitDepth | short | The PSD bit depth per channel. |
| channels | short | The PSD channels count. |
| psdVersion | int | The PSD version. |
| compression | short | The compression to use. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in stream). Used to initialize psd image with default parameters - Color mode - rgb, 4 channels, 8 bit per channel, Compression - Raw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load pixel and palette data from and initialize with. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from specified path from raster image (not psd image in stream) with constructor parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load pixel and palette data from and initialize with. |
| colorMode | short | The color mode. |
| channelBitDepth | short | The PSD bit depth per channel. |
| channels | short | The PSD channels count. |
| psdVersion | int | The PSD version. |
| compression | short | The compression to use. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from existing raster image (not psd image) with RGB color mode with 4 channels 8 bit/channel and no compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | The image to load pixel and palette data from and initialize with. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class from existing raster image (not psd image) with constructor parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | The image to load pixel and palette data from and initialize with. |
| colorMode | short | The color mode. |
| channelBitDepth | short | The PSD bit depth per channel. |
| channels | short | The PSD channels count. |
| psdVersion | int | The PSD version. |
| compression | short | The compression to use. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class with specified width and height. Used to initialize empty psd image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initializes a new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class with specified width,height, paletter, color mode, channels count and channels bit-length and specified compression mode parameters. Used to initialize empty psd image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |
| colorMode | short | The color mode. |
| channelBitDepth | short | The PSD bit depth per channel. |
| channels | short | The PSD channels count. |
| psdVersion | int | The PSD version. |
| compression | short | The compression to use. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


The default encoding name

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


The default PSD version.

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

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


The object that can be used to synchronize access to the layers.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Adds the black white adjustment layer.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Adds the brightness/contrast adjustment layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | The brightness. |
| contrast | int | The contrast. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Adds the channel mixer adjustment layer with default parameters

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Adds the color balance adjustment layer.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Adds the Curves Adjustment layer.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exposure | float |  |
| offset | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Adds the exposure adjustment layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exposure | float | The exposure. |
| offset | float | The offset. |
| gammaCorrection | float | The gamma correction. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Adds the hue/saturation adjustment layer.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Adds an invert adjustment layer.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Adds the layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Adds the layer group.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupName | java.lang.String | Name of the group. |
| index | int | The index of the layer to insert after. |
| startBehaviour | boolean | if set to  true  [start behaviour] than group will be in open state on start up, otherwise in minimized state. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Adds the layer at the index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer. |
| index | int | The index. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Adds the Levels adjustment layer.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Adds the photofilter layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | The color. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Adds Posterize Adjustment layer.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Adds a new regular layer.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Adds the selective color adjustment layer.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Add empty Shape layer. Without paths. They should be added to shape layer before save.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Adds a new Text layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The layer's text. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The layer's rectangle. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Adds the Threshold adjustment layer.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Adds the Vibrance adjustment layer.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
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

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Converts this image format to the one specified in options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | The new options. |

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
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Creates the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | The PSD header. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | The color data. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | The image resources. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | The layer and mask info. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | The image data. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |
| version | int | The PSD version. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |
| noLayerLoad | boolean | No Layer load |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
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
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Flattens all layers.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Gets or sets the active layer.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Gets a value indicating whether automatic adjust palette.

**Returns:**
boolean -  true  if enable automatic adjust palette; otherwise,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets or sets a value for the background color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Gets the bits per channel.

Value: The bits per channel.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

Value: The image bits per pixel count.

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
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Gets the PSD channels count.

Value: The PSD channels count.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


Gets or sets the CMYK color profile for CMYK PSD images. Must be in pair with RgbColorProfile for correct color conversion.

Value: The CMYK color profile.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Gets or sets the color mode.

Value: The color mode.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Gets the compression method.

Value: The compression.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Gets the  Image  container.

Value: The  Image  container.

If this property is not null it indicates the image is contained whithin another image.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Gets the current image options.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
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
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Gets or sets the default replacement font. If the Replacement font is set then it will be used for rendering. We need this method for internal support

**Returns:**
java.lang.String - The name of Replacement font
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Gets the file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream.

--------------------

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether stream may be loaded. |

**Returns:**
long - The determined file format.
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
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Gets palette from format-specific places

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Gets or sets the global angle.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Gets the global layer mask info.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Gets or sets the global layer resources.

Value: The global layer resources.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Gets or sets the GRAY (monochrome) color profile for Grayscale PSD images.

Value: The GRAY (monochrome) color profile.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
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


Gets or sets the horizontal resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Gets or sets the PSD layers.

Value: The PSD layers.

--------------------

Note that if there are no layers the other related information within layer and mask information section will not be preserved (layer masks, resources and etc).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Gets opacity of this image.

**Returns:**
float - The opacity value between 0.0 (fully transparent) and 1.0 (fully opaque).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Gets or sets the PSD image resources.

Value: The PSD image resources.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
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
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Gets the layer and mask.

Value: The layer and mask.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Gets or sets the PSD layers.

Value: The PSD layers.

--------------------

Note that if there are no layers the other related information within layer and mask information section will not be preserved (layer masks, resources and etc).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Gets the linked layers manager.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
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
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the  DataStreamSupporter.Save(string)  method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the  Image.Save(string, ImageOptionsBase)  method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Gets the paintable image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

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
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Creates the private font cache.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - The private font cache.
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
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Gets or sets the PSD header.

Value: The PSD header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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

Value: The raw data format.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
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
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Gets or sets the RGB color profile for CMYK PSD images. Must be in pair with CmykColorProfile for correct color conversion.

Value: The RGB color profile.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Gets or sets the rotate mode.

**Returns:**
int - The rotate mode.
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
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Gets the smart object provider.

Value: The smart object provider.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Gets the file path of source image if it's exist. Returns an empty string if can't find the source path.

**Returns:**
java.lang.String - The file path of source image.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Gets the synchronize root.

Value: The synchronize root.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Gets the  Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
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
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Gets updated resources with brand new resource block.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | The resources. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | The resource to add to existing resources. |
| removeDuplicates | boolean | if set to  true  removes resources with identical IDs. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Returns an array with updated resources blocks.
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets or sets the version.

Value: The version.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets or sets the vertical resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
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

Value: The XMP metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation of an image to its grayscale representation

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets or sets the vertical resolution, in pixels per inch, of this  RasterImage .

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

Value:  true  if this instance has image changed; otherwise,  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Gets or sets a value indicating whether first alpha channel contains the transparency data for the merged result when specifying layers data.

Value:  true  if first alpha channel contains the transparency data for the merged result when specifying layers data; otherwise,  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gets a value indicating whether image has transparent color.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Inserts the layer after the specified layer with all preparations

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer to insert. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether image data is cached currently.

**Returns:**
boolean -  true  if image data is cached; otherwise,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Gets a value indicating whether psd image is flattened.

Value:  true  if this instance is flatten; otherwise,  false .

**Returns:**
boolean
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
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




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
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Merges the layers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The bottom layer. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The top layer. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
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


Invoke when container of this [Image](../../com.aspose.psd/image) was set.

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
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Removes the global text engine resource - Method is used for some text-layered psd files, that can not be opened in Adobe Photoshop after processing (almostly for absent fonts text layers related). After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -> "Process absent fonts". After that operation all text will appear again. Please note, that this operation may cause some final layout changes.

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

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save the image's data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

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
| stream | com.aspose.ms.System.IO.Stream | The stream to save the image's data to. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Gets or sets the active layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Gets or sets the CMYK color profile for CMYK PSD images. Must be in pair with RgbColorProfile for correct color conversion.

Value: The CMYK color profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Gets or sets the color mode.

Value: The color mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


The global angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Gets or sets the global layer resources.

Value: The global layer resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


The GRAY (monochrome) color profile for Grayscale PSD images.

Value: The GRAY (monochrome) color profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Gets or sets the horizontal resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Gets or sets the PSD image resources.

Value: The PSD image resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Gets or sets the PSD layers.

Value: The PSD layers.

--------------------

Note that if there are no layers the other related information within layer and mask information section will not be preserved (layer masks, resources and etc).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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


Sets the resolution for this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the  RasterImage . |
| dpiY | double | The vertical resolution, in dots per inch, of the  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Gets or sets the RGB color profile for CMYK PSD images. Must be in pair with CmykColorProfile for correct color conversion.

Value: The RGB color profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Gets or sets the rotate mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The rotate mode. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Gets or sets a value indicating whether first alpha channel contains the transparency data for the merged result when specifying layers data.

Value:  true  if first alpha channel contains the transparency data for the merged result when specifying layers data; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

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


Sets the venture license.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ventureLicense | java.lang.Object | The venture license. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Gets or sets the version.

Value: The version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Gets or sets the vertical resolution, in pixels per inch, of this [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata.

Value: The XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

