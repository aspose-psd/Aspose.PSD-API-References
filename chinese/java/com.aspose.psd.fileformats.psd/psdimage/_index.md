---
title: "PsdImage"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 PsdImage 类，提供加载、编辑、保存 PSD 文件的能力，以及更新属性、添加水印、执行图形操作或将一种文件格式转换为另一种格式的功能。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

定义 PsdImage 类，提供加载、编辑、保存 PSD 文件的能力，以及更新属性、添加水印、执行图形操作或将一种文件格式转换为另一种格式的功能。Aspose.PSD 支持将导入作为图层，并导出为以下格式：Png、Jpeg、Jpeg2000、Gif、Bmp、Tiff、Psd、Psb，以及导出为可选择文本的 Pdf。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | 从指定路径的光栅图像（路径中不是 PSD 图像）初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | 从指定路径的光栅图像（路径中不是 PSD 图像）并使用构造函数参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | 从指定流中的光栅图像（流中不是 PSD 图像）初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | 从指定流中的光栅图像（流中不是 PSD 图像）并使用构造函数参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | 从现有光栅图像（不是 PSD 图像）且使用 RGB 颜色模式、4 个通道、每通道 8 位且无压缩，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | 从现有光栅图像（不是 PSD 图像）并使用构造函数参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | 使用指定的宽度和高度，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | 使用指定的宽度、高度、调色板、颜色模式、通道数、通道位深以及指定的压缩模式参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | 默认编码名称 |
| [DefaultVersion](#DefaultVersion) | 默认 PSD 版本。 |
| [OnCreate_internalized](#OnCreate-internalized) | 当图像被加载时发生 |
| [OnLoad_internalized](#OnLoad-internalized) | 当图像通过 createFirstSupportedLoader 加载时发生 |
| [OnSave_internalized](#OnSave-internalized) | 当图像被加载或保存时发生 |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | 当使用 credit 时发生 |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | 可用于同步对图层访问的对象。 |
| [horizontalResolution](#horizontalResolution) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | 添加黑白调整图层。 |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | 添加亮度/对比度调整图层。 |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | 使用默认参数添加通道混合器调整图层。 |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | 添加色彩平衡调整图层。 |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | 添加曲线调整图层。 |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | 添加曝光调整图层。 |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | 添加渐变映射调整图层。 |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | 添加色相/饱和度调整图层。 |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | 添加反相调整图层。 |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | 添加图层。 |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | 添加图层组。 |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | 在索引处添加图层。 |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | 添加色阶调整图层。 |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | 添加照片滤镜图层。 |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | 添加色调分离调整图层。 |
| [addRegularLayer()](#addRegularLayer--) | 添加一个新的常规图层。 |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | 添加选择性颜色调整图层。 |
| [addShapeLayer()](#addShapeLayer--) | 添加空形状图层。 |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | 添加一个新的文本图层。 |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | 添加阈值调整图层。 |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | 添加活力调整图层。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 调整图像的亮度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 图像对比度 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 图像的伽马校正。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 图像的伽马校正。 |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | 开始调整大小的过程。 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值对图像进行二值化。 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值对图像进行二值化。 |
| [cacheData()](#cacheData--) | 缓存数据并确保不会从底层的 DataStreamSupporter.DataStreamContainer 加载额外的数据。 |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 确定是否可以从指定的流加载图像。 |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 确定是否可以从指定的流加载图像，并可选地使用指定的 loadOptions。 |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 确定是否可以从指定的文件路径加载图像。 |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的 open options。 |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 确定是否可以将图像保存为由传入的 save options 表示的指定文件格式。 |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | 将此图像格式转换为选项中指定的格式。 |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | 转换为 aps。 |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 使用指定的 create options 创建新图像。 |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 使用指定的图像作为页面创建新图像。 |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 使用指定的图像作为页面创建新图像。 |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | 创建 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。 |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | 裁剪图像。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 使用位移裁剪图像。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | 对当前图像执行抖动处理。 |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | 对当前图像执行抖动处理。 |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | 裁剪图像。 |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | 调整图像大小。 |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | 旋转、翻转或同时旋转并翻转图像。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | 过滤指定的矩形。 |
| [flattenImage()](#flattenImage--) | 合并所有图层。 |
| [getActiveLayer()](#getActiveLayer--) | 获取或设置活动图层。 |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | 获取图像的 32 位 ARGB 像素。 |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 获取一个值，指示是否自动调整调色板。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置背景颜色的值。 |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | 获取或设置背景颜色。 |
| [getBitsPerChannel()](#getBitsPerChannel--) | 获取每通道的位数。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数。 |
| [getBounds()](#getBounds--) | 获取图像边界。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getChannelsCount()](#getChannelsCount--) | 获取 PSD 通道数量。 |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | 获取或设置 CMYK PSD 图像的 CMYK 色彩配置文件。 |
| [getColorMode()](#getColorMode--) | 获取或设置颜色模式。 |
| [getCompression()](#getCompression--) | 获取压缩方式。 |
| [getContainer()](#getContainer--) | 获取 Image 容器。 |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | 获取当前图像选项。 |
| [getDataStreamContainer()](#getDataStreamContainer--) | 获取对象的数据流。 |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 获取深度调整的调色板。 |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | 获取默认的 32 位 ARGB 像素数组。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认选项。 |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 获取使用部分像素加载器的默认像素数组。 |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | 获取使用部分像素加载器的默认原始数据数组。 |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | 获取默认原始数据数组。 |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | 获取或设置默认替换字体。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFileFormat()](#getFileFormat--) | 获取文件格式的值 |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | 获取文件格式。 |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | 获取文件格式。 |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | 获取文件格式。 |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 获取适合当前图像的矩形。 |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 获取适合当前图像的矩形。 |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | 从特定格式的位置获取调色板。 |
| [getGlobalAngle()](#getGlobalAngle--) | 获取或设置全局角度。 |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | 获取全局图层蒙版信息。 |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | 获取或设置全局图层资源。 |
| [getGrayColorProfile()](#getGrayColorProfile--) | 获取或设置灰度（单色）PSD 图像的 GRAY 色彩配置文件。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的水平分辨率（每英寸像素数）。 |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | 获取或设置 PSD 图层。 |
| [getImageOpacity()](#getImageOpacity--) | 获取此图像的不透明度。 |
| [getImageResources()](#getImageResources--) | 获取或设置 PSD 图像资源。 |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | 获取内部数据转换器。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 获取中断监视器。 |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | 获取图层和蒙版。 |
| [getLayers()](#getLayers--) | 获取或设置 PSD 图层。 |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | 获取已链接图层管理器。 |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | 获取或设置部分旋转保存的最大允许分配。 |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | 获取内存管理器。 |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | 获取资源图像上次修改的日期和时间。 |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | 根据原始文件设置获取选项。 |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | 获取可绘制的图像。 |
| [getPalette()](#getPalette--) | 获取颜色调色板。 |
| [getPixel(int x, int y)](#getPixel-int-int-) | 获取图像像素。 |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | 创建私有字体缓存。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取进度事件处理程序信息。 |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | 获取进度事件处理程序信息。 |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | 获取比例高度。 |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | 获取比例宽度。 |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | 获取或设置 PSD 标头。 |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | 获取或设置自定义颜色转换器 |
| [getRawDataFormat()](#getRawDataFormat--) | 获取原始数据格式。 |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | 获取或设置索引颜色转换器 |
| [getRawLineSize()](#getRawLineSize--) | 获取原始行大小（字节）。 |
| [getRgbColorProfile()](#getRgbColorProfile--) | 获取或设置 CMYK PSD 图像的 RGB 色彩配置文件。 |
| [getRotateMode()](#getRotateMode--) | 获取或设置旋转模式。 |
| [getSize()](#getSize--) | 获取图像尺寸。 |
| [getSkewAngle()](#getSkewAngle--) | 获取倾斜角度。 |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | 获取智能对象提供程序。 |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | 获取源图像的文件路径（如果存在）。 |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | 获取同步根目录。 |
| [getTimeline()](#getTimeline--) | 获取此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的时间轴 ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-))。 |
| [getTransparentColor()](#getTransparentColor--) | 获取图像透明颜色。 |
| [getUpdateXmpData()](#getUpdateXmpData--) | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | 获取带有全新资源块的更新资源。 |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | 获取一个值，指示对象是否使用内存优化策略 |
| [getUseRawData()](#getUseRawData--) | 获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。 |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | 获取使用的调色板。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 获取风险许可证。 |
| [getVersion()](#getVersion--) | 获取或设置版本。 |
| [getVerticalResolution()](#getVerticalResolution--) | 获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的垂直分辨率（每英寸像素数）。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getXmpData()](#getXmpData--) | 获取或设置 XMP 元数据。 |
| [grayscale()](#grayscale--) | 将图像转换为其灰度表示。 |
| [hasAlpha()](#hasAlpha--) | 获取或设置此 RasterImage 的垂直分辨率（每英寸像素数）。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 获取一个值，指示图像是否具有背景颜色。 |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 获取或设置一个值，指示此图像实例在加载后是否已更改。 |
| [hasTransparencyData()](#hasTransparencyData--) | 获取或设置一个值，以指示在指定图层数据时，第一个 alpha 通道是否包含合并结果的透明度数据。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示图像是否具有透明颜色。 |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 获取或设置进度最大值 |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 指示进度。 |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | 在指定图层之后插入该图层并完成所有准备工作 |
| [isCached()](#isCached--) | 获取一个值，指示当前是否缓存了图像数据。 |
| [isFlatten()](#isFlatten--) | 获取一个值，以指示 PSD 图像是否已展平。 |
| [isRawDataAvailable()](#isRawDataAvailable--) | 获取一个值，指示是否可用原始数据加载。 |
| [isUsePalette()](#isUsePalette--) | 获取一个值，指示是否使用图像调色板。 |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从指定的流加载新图像。 |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | 从指定的流加载新图像。 |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | 从指定的流加载新图像。 |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | 从指定的流加载新图像。 |
| [load(String filePath)](#load-java.lang.String-) | 从指定的文件加载新图像。 |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | 从指定的文件加载新图像。 |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | 加载 32 位 ARGB 像素。 |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | 加载 64 位 ARGB 像素。 |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | 以 CMYK 格式加载像素。 |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | 以 CMYK 格式加载像素。 |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 按包部分加载 32 位 ARGB 像素。 |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | 按包部分加载像素。 |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | 加载像素。 |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 使用部分处理机制加载原始图像数据。 |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 加载原始数据。 |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | 从指定的流加载新图像。 |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | 从指定的流加载新图像。 |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | 合并图层。 |
| [normalizeAngle()](#normalizeAngle--) | 归一化角度。 |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | 归一化角度。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | 当此 [Image](../../com.aspose.psd/image) 的容器被设置时调用。 |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | 通过指定的扫描线索引读取整条扫描线。 |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | 通过指定的扫描线索引读取整条扫描线。 |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | 删除全局文本引擎资源 - 此方法用于某些文本图层的 PSD 文件，处理后无法在 Adobe Photoshop 中打开（主要针对缺少字体的文本图层）。 |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小。 |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | 按比例调整高度。 |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | 按比例调整高度。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 按比例调整高度。 |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | 按比例调整宽度。 |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | 按比例调整宽度。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 按比例调整宽度。 |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | 使用指定的逆比例缩放调整图层大小。 |
| [rotate(float angle)](#rotate-float-) | 围绕中心旋转图像。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | 围绕中心旋转图像。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | 将图像数据保存到底层流。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将对象的数据保存到指定流。 |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | 将对象的数据保存到指定流。 |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | 根据保存选项，将对象的数据以指定的文件格式保存到指定文件位置。 |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
| [save(String filePath)](#save-java.lang.String-) | 将对象的数据保存到指定文件位置。 |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | 将对象的数据保存到指定文件位置。 |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | 根据保存选项，将对象的数据以指定的文件格式保存到指定文件位置。 |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 根据保存选项，将对象的数据以指定的文件格式保存到指定文件位置。 |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | 保存 32 位 ARGB 像素。 |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | 保存像素。 |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | 保存像素。 |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | 保存像素。 |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | 保存原始数据。 |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | 使用指定的保存选项和边界将图像数据保存到指定的流中。 |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | 获取或设置活动图层。 |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 设置一个值，指示是否自动调整调色板。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 获取或设置一个值，指示图像是否具有背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 获取或设置背景颜色的值。 |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置背景颜色。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | 获取或设置 CMYK PSD 图像的 CMYK 色彩配置文件。 |
| [setColorMode(short value)](#setColorMode-short-) | 获取或设置颜色模式。 |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | 设置 Image 容器。 |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | 直接设置数据加载器。 |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | 设置对象的数据流。 |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | 将调色板设置到特定格式的位置。 |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | 全局角度。 |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | 获取或设置全局图层资源。 |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | 灰度（单色）PSD 图像的 GRAY 色彩配置文件。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的水平分辨率（每英寸像素数）。 |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 设置一个值，指示是否 [ignore after save]。 |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 获取或设置一个值，指示此图像实例在加载后是否已更改。 |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | 获取或设置 PSD 图像资源。 |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | 设置内部数据转换器。 |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 设置中断监视器。 |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | 获取或设置 PSD 图层。 |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | 获取或设置部分旋转保存的最大允许分配。 |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | 设置内存管理器。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 设置颜色调色板。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 设置图像调色板。 |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | 为指定位置设置图像像素。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | 获取或设置自定义颜色转换器 |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | 获取或设置索引颜色转换器 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的分辨率。 |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | 获取或设置 CMYK PSD 图像的 RGB 色彩配置文件。 |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | 获取或设置旋转模式。 |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | 获取或设置一个值，以指示在指定图层数据时，第一个 alpha 通道是否包含合并结果的透明度数据。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 获取一个值，指示图像是否具有透明颜色。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | 获取图像透明颜色。 |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | 获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。 |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | 设置企业许可证。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置版本。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的垂直分辨率（每英寸像素数）。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | 获取或设置 XMP 元数据。 |
| [toBitmap()](#toBitmap--) | 将光栅图像转换为位图。 |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | 将整条扫描线写入指定的扫描线索引。 |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | 将整条扫描线写入指定的扫描线索引。 |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


从指定路径的光栅图像（路径中不是 PSD 图像）初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。用于使用默认参数初始化 PSD 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩方式 - Raw。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载像素和调色板数据并进行初始化的路径。 |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


从指定路径的光栅图像（路径中不是 PSD 图像）并使用构造函数参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载像素和调色板数据并进行初始化的路径。 |
| colorMode | short | 颜色模式。 |
| channelBitDepth | short | 每通道的 PSD 位深度。 |
| 通道 | short | PSD 通道计数。 |
| psdVersion | int | PSD 版本。 |
| 压缩 | short | 要使用的压缩方式。 |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


从指定路径的光栅图像（而非流中的 psd 图像）初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 个通道，每通道 8 位，压缩方式 - Raw。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载像素和调色板数据并进行初始化的流。 |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


从指定流中的光栅图像（流中不是 PSD 图像）并使用构造函数参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载像素和调色板数据并进行初始化的流。 |
| colorMode | short | 颜色模式。 |
| channelBitDepth | short | 每通道的 PSD 位深度。 |
| 通道 | short | PSD 通道计数。 |
| psdVersion | int | PSD 版本。 |
| 压缩 | short | 要使用的压缩方式。 |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


从现有光栅图像（不是 PSD 图像）且使用 RGB 颜色模式、4 个通道、每通道 8 位且无压缩，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | 用于加载像素和调色板数据并进行初始化的图像。 |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


从现有光栅图像（不是 PSD 图像）并使用构造函数参数，初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | 用于加载像素和调色板数据并进行初始化的图像。 |
| colorMode | short | 颜色模式。 |
| channelBitDepth | short | 每通道的 PSD 位深度。 |
| 通道 | short | PSD 通道计数。 |
| psdVersion | int | PSD 版本。 |
| 压缩 | short | 要使用的压缩方式。 |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


使用指定的宽度和高度初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。用于初始化空的 psd 图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


使用指定的宽度、长度、调色板、颜色模式、通道数、通道位深以及指定的压缩模式参数初始化 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。用于初始化空的 psd 图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |
| colorMode | short | 颜色模式。 |
| channelBitDepth | short | 每通道的 PSD 位深度。 |
| 通道 | short | PSD 通道计数。 |
| psdVersion | int | PSD 版本。 |
| 压缩 | short | 要使用的压缩方式。 |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


默认编码名称

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


默认 PSD 版本。

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


当图像被加载时发生

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


当图像通过 createFirstSupportedLoader 加载时发生

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


当图像被加载或保存时发生

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


当使用 credit 时发生

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


可用于同步对图层访问的对象。

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


添加黑白调整图层。

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


添加亮度/对比度调整图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 亮度 | int | 亮度。 |
| 对比度 | int | 对比度。 |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


使用默认参数添加通道混合器调整图层。

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


添加色彩平衡调整图层。

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


添加曲线调整图层。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| 曝光 | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 曝光 | float |  |
| offset | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


添加曝光调整图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 曝光 | float | 曝光。 |
| offset | float | 偏移量。 |
| 伽马校正 | float | 伽马校正。 |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


添加渐变映射调整图层。

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


添加色相/饱和度调整图层。

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


添加反相调整图层。

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


添加图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 该图层。 |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


添加图层组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| groupName | java.lang.String | 组的名称。 |
| index | int | 要在其后插入的图层的索引。 |
| 启动行为 | boolean | 如果设置为 true，则 [start behaviour] 组将在启动时处于打开状态，否则为最小化状态。 |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


在索引处添加图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 该图层。 |
| index | int | 该索引。 |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


添加色阶调整图层。

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


添加照片滤镜图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 颜色。 |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


添加色调分离调整图层。

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


添加一个新的常规图层。

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


添加选择性颜色调整图层。

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


添加空的 Shape 图层。无路径。应在保存前将路径添加到 Shape 图层。

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


添加一个新的文本图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 图层的文本。 |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 图层的矩形。 |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


添加阈值调整图层。

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


添加活力调整图层。

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


调整图像的亮度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 亮度 | int | 亮度值。 |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


图像对比度

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


图像的伽马校正。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


图像的伽马校正。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| gammaRed | float | 红色通道的伽马系数 |
| gammaGreen | float | 绿色通道的伽马系数 |
| gammaBlue | float | 蓝色通道的伽马系数 |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


开始调整大小的过程。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的图像宽度。 |
| newHeight | int | 新的图像高度。 |

**Returns:**
com.aspose.internal.IResizeController - 大小调整控制器。
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素与以该像素为中心的 s x s 窗口像素平均值之间的亮度差。 |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brightnessDifference | double | 像素与以该像素为中心的 s x s 窗口像素平均值之间的亮度差。 |
| windowSize | int | 以该像素为中心的 s x s 像素窗口的大小 |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


使用预定义阈值对图像进行二值化。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| threshold | byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


使用 Otsu 阈值对图像进行二值化。

### cacheData() {#cacheData--}
```
public void cacheData()
```


缓存数据并确保不会从底层的 DataStreamSupporter.DataStreamContainer 加载额外的数据。

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


确定是否可以从指定的流加载图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加载的流。 |

**Returns:**
boolean -  true  如果可以从指定的流加载图像；否则，  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


确定是否可以从指定的流加载图像，并可选地使用指定的 loadOptions。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要加载的流。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
boolean -  true  如果可以从指定的流加载图像；否则，  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


确定是否可以从指定的文件路径加载图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |

**Returns:**
boolean -  true  如果可以从指定的文件加载图像；否则，  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


确定是否可以从指定的文件路径加载图像，并可选地使用指定的 open options。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
boolean -  true  如果可以从指定的文件加载图像；否则，  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


确定是否可以将图像保存为由传入的 save options 表示的指定文件格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 要使用的保存选项。 |

**Returns:**
boolean -  true  如果可以使用传入的保存选项将图像保存为指定的文件格式；否则，  false .
### close() {#close--}
```
public void close()
```


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


将此图像格式转换为选项中指定的格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | 新的选项。 |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


转换为 aps。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项。 |
| mode | int | 模式。 |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 裁剪矩形。 |

**Returns:**
com.aspose.foundation.rendering.ApsPage - APS 页面。
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


使用指定的 create options 创建新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像选项。 |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


使用指定的图像作为页面创建新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | 图像。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


使用指定的图像作为页面创建新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | 图像。 |
| disposeImages | boolean | 如果设置为 true [dispose images]。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


创建 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | The PSD header. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | 颜色数据。 |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | 图像资源。 |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | 图层和蒙版信息。 |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | 图像数据。 |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |
| version | int | PSD 版本。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |
| noLayerLoad | boolean | 不加载图层 |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| 宽度 | int |  |
| 高度 | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| 通道 | short |  |
| psdVersion | int |  |
| 压缩 | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


裁剪图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 矩形。 |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


使用位移裁剪图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| leftShift | int | 左移。 |
| rightShift | int | 右移。 |
| topShift | int | 上移。 |
| bottomShift | int | 下移。 |

### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


对当前图像执行抖动处理。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


对当前图像执行抖动处理。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ditheringMethod | int | 抖动方法。 |
| bitsCount | int | 抖动的最终位计数。 |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 抖动的自定义调色板。 |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


裁剪图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 矩形。 |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


调整图像大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 缩放设置。 |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


旋转、翻转或同时旋转并翻转图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


过滤指定的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 矩形。 |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | 选项。 |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


合并所有图层。

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


获取或设置活动图层。

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


获取图像的 32 位 ARGB 像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 像素 x 位置。 |
| y | int | 像素 y 位置。 |

**Returns:**
int - 指定位置的 32 位 ARGB 像素。
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


获取一个值，指示是否自动调整调色板。

**Returns:**
boolean -  true  如果启用自动调整调色板，则为 true；否则为  false 。
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取或设置背景颜色的值。

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


获取或设置背景颜色。它可以在透明对象下看到。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


获取每通道的位数。

值：每通道的位数。

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数。

值：图像每像素位数计数。

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取图像边界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int - 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


获取 PSD 通道数量。

值：PSD 通道计数。

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


获取或设置 CMYK PSD 图像的 CMYK 颜色配置文件。必须与 RgbColorProfile 配对以实现正确的颜色转换。

值：CMYK 颜色配置文件。

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


获取或设置颜色模式。

值：该颜色模式。

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


获取压缩方式。

值：压缩方式。

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


获取 Image 容器。

值： 图像 容器。

如果此属性不为 null，则表示该图像包含在另一个图像中。

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


获取当前图像选项。

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


获取对象的数据流。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


获取深度调整的调色板。

**Returns:**
boolean - 深度调整调色板。
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


获取默认的 32 位 ARGB 像素数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于获取像素的矩形。 |

**Returns:**
int[] - 默认像素数组。
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


获取默认选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 参数 | java.lang.Object[] | 参数。 |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


获取使用部分像素加载器的默认像素数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于获取像素的矩形。 |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 部分像素加载器。 |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


获取使用部分像素加载器的默认原始数据数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于获取像素的矩形。 |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 部分原始数据加载器。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 原始数据设置。 |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


获取默认原始数据数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于获取原始数据的矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 原始数据设置。 |

**Returns:**
byte[] - 默认原始数据数组。
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


获取或设置默认替换字体。如果设置了 Replacement 字体，则将在渲染时使用。我们需要此方法来进行内部支持

**Returns:**
java.lang.String - Replacement 字体的名称
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取文件格式的值

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


获取文件格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | 流。 |

--------------------

确定的文件格式并不意味着可以加载指定的图像。使用 CanLoad 方法的重载之一来确定是否可以加载流。 |

**Returns:**
long - 确定的文件格式。
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


获取文件格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 流。 |

确定的文件格式并不意味着可以加载指定的图像。使用 CanLoad 方法的重载之一来确定是否可以加载流。 |

**Returns:**
long - 确定的文件格式。
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


获取文件格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文件路径。 |

确定的文件格式并不意味着可以加载指定的图像。使用 CanLoad 方法的重载之一来确定是否可以加载文件。 |

**Returns:**
long - 确定的文件格式。
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


获取适合当前图像的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于获取适配矩形的矩形。 |
| 宽度 | int | 对象的宽度。 |
| 高度 | int | 对象的高度。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


获取适合当前图像的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于获取适配矩形的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素。 |
| 宽度 | int | 对象的宽度。 |
| 高度 | int | 对象的高度。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


从特定格式的位置获取调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


获取或设置全局角度。

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


获取全局图层蒙版信息。

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


获取或设置全局图层资源。

值：全局图层资源。

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


获取或设置灰度（单色）PSD 图像的 GRAY 色彩配置文件。

值：GRAY（单色）颜色配置文件。

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

值：图像高度。

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的水平分辨率（每英寸像素数）。

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


获取或设置 PSD 图层。

值：PSD 图层。

--------------------

请注意，如果没有图层，图层和蒙版信息部分中的其他相关信息（图层蒙版、资源等）将不会被保留。

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


获取此图像的不透明度。

**Returns:**
float - 不透明度值，范围在 0.0（完全透明）到 1.0（完全不透明）之间。
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


获取或设置 PSD 图像资源。

值：PSD 图像资源。

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


获取内部数据转换器。

值：内部数据转换器。

**Returns:**
com.aspose.internal.IInnerDataTransformer - 内部数据转换器。
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


获取中断监视器。

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


获取图层和蒙版。

值：图层和蒙版。

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


获取或设置 PSD 图层。

值：PSD 图层。

--------------------

请注意，如果没有图层，图层和蒙版信息部分中的其他相关信息（图层蒙版、资源等）将不会被保留。

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


获取已链接图层管理器。

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


获取或设置部分旋转保存的最大允许分配。

**Returns:**
int - 部分旋转保存的最大允许分配。
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


获取内存管理器。

值：内存管理器。

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - 内存管理器。
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


获取资源图像上次修改的日期和时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| useDefault | boolean | 如果设置为 true，使用来自 FileInfo 的信息作为默认值。 |

**Returns:**
java.util.Date - 资源图像上次修改的日期和时间。
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


获取基于原始文件设置的选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 `DataStreamSupporter.Save(string)` 方法保存，输出的 PNG 图像将是每像素 8 位。为了避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将它们作为第二个参数传递给 `Image.Save(string, ImageOptionsBase)` 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


获取可绘制的图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


获取颜色调色板。当像素直接表示时，不使用颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


获取图像像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 像素 x 位置。 |
| y | int | 像素 y 位置。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


获取或设置一个值，指示图像组件是否必须预乘。

**Returns:**
boolean - true 表示图像组件必须预乘；否则为 false。
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


创建私有字体缓存。

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - 私有字体缓存。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


获取进度事件处理程序信息。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


获取进度事件处理程序信息。

值：进度事件处理程序信息。

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


获取比例高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |
| newWidth | int | 新的宽度。 |

**Returns:**
int - 比例高度。
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


获取比例宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |
| newHeight | int | 新的高度。 |

**Returns:**
int - 比例宽度。
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


获取或设置 PSD 标头。

值：PSD 标头。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


获取或设置自定义颜色转换器

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


获取原始数据格式。

值：原始数据格式。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


获取或设置当调色板索引超出范围时使用的回退索引

**Returns:**
int - 当调色板索引超出范围时使用的回退索引
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


获取或设置索引颜色转换器

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


获取原始行大小（字节）。

**Returns:**
int - 原始行大小（字节）。
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


获取或设置 CMYK PSD 图像的 RGB 颜色配置文件。必须与 CmykColorProfile 配对以实现正确的颜色转换。

值：RGB 颜色配置文件。

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


获取或设置旋转模式。

**Returns:**
int - 旋转模式。
### getSize() {#getSize--}
```
public Size getSize()
```


获取图像尺寸。

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


获取倾斜角度。此方法适用于扫描的文本文档，用于在扫描时确定倾斜角度。

**Returns:**
float - 倾斜角度（单位：度）。
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


获取智能对象提供程序。

值：智能对象提供程序。

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


获取源图像的文件路径（如果存在）。如果找不到源路径，则返回空字符串。

**Returns:**
java.lang.String - 源图像的文件路径。
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


获取同步根目录。

值：同步根。

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


获取此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的时间轴 ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-))。

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


获取图像透明颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


获取或设置一个值，指示是否更新 XMP 元数据。

**Returns:**
boolean -  true  如果更新 XMP 元数据；否则，  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


获取带有全新资源块的更新资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | 资源。 |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | 要添加到现有资源的资源。 |
| removeDuplicates | boolean | 如果设置为  true  将删除具有相同 ID 的资源。 |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - 返回包含已更新资源块的数组。
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


获取一个值，指示对象是否使用内存优化策略

值：  true  如果对象使用内存优化策略；否则，  false .

**Returns:**
boolean - 表示对象是否使用内存优化策略的值
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。

**Returns:**
boolean -  true  如果在原始数据加载可用时使用原始数据加载；否则，  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


获取使用的调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


获取风险许可证。

**Returns:**
java.lang.Object - Teh venture 许可证作为对象。
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取或设置版本。

值：版本。

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的垂直分辨率（每英寸像素数）。

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

值：图像宽度。

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取或设置 XMP 元数据。

值：XMP 元数据。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


将图像转换为其灰度表示。

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取或设置此 RasterImage 的垂直分辨率（每英寸像素数）。

值：  true  如果此实例具有 alpha 通道；否则，  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


获取一个值，指示图像是否具有背景颜色。

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


获取或设置一个值，指示此图像实例在加载后是否已更改。

值：如果此实例的图像已更改则为  true ，否则为  false 。

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


获取或设置一个值，以指示在指定图层数据时，第一个 alpha 通道是否包含合并结果的透明度数据。

值：如果在指定图层数据时第一个 alpha 通道包含合并结果的透明度数据，则为  true ，否则为  false 。

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取一个值，指示图像是否具有透明颜色。

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


获取或设置进度最大值

值：进度最大值

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


指示进度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


在指定图层之后插入该图层并完成所有准备工作

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 该图层。 |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 要插入的图层。 |

### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个值，指示当前是否缓存了图像数据。

**Returns:**
boolean -  true  如果图像数据已缓存；否则，  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


获取一个值，以指示 PSD 图像是否已展平。

值：如果此实例已展平则为  true ，否则为  false 。

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


获取一个值，指示是否可用原始数据加载。

**Returns:**
boolean -  true  如果此原始数据加载可用；否则，  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


获取一个值，指示是否使用图像调色板。

值：  true  如果图像中使用调色板；否则，  false .

**Returns:**
boolean - 表示是否使用图像调色板的值
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


从指定的流加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载图像的流。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


从指定的流加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载图像的流。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


从指定的流加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 用于加载图像的文件。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


从指定的流加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 用于加载图像的文件。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


从指定的文件加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于加载图像的文件路径。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


从指定的文件加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于加载图像的文件路径。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


加载 32 位 ARGB 像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns:**
int[] - 已加载的 32 位 ARGB 像素数组。
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


加载 64 位 ARGB 像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns:**
long[] - 已加载的 64 位 ARGB 像素数组。
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


以 CMYK 格式加载像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns:**
int[] - 已加载的 CMYK 像素，以 32 位整数值表示。
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


以 CMYK 格式加载像素。此方法已弃用。请使用更有效的 loadCmyk32Pixels(Rectangle) 方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns:**
com.aspose.psd.CmykColor[] - 已加载的 CMYK 像素数组。
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


按包部分加载 32 位 ARGB 像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 所需的矩形。 |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 32 位 ARGB 像素加载器。 |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


按包部分加载像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 所需的矩形。 |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | 像素加载器。 |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


加载像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载像素的矩形。 |

**Returns:**
com.aspose.psd.Color[] - 已加载的像素数组。
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


使用部分处理机制加载原始图像数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 图像中用于加载数据的所需矩形区域。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 原始数据设置。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 原始数据加载器。 |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


加载原始数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载原始数据的矩形。 |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 原始数据加载器。 |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


从指定的流加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 用于加载图像的流。 |
| startPosition | long | 用于加载图像的起始位置。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


从指定的流加载新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 用于加载图像的流。 |
| startPosition | long | 用于加载图像的起始位置。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


合并图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 底部图层。 |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 顶部图层。 |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


归一化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [.getSkewAngle](../../null/\\#getSkewAngle) 和 [.rotate(float)](../../null/\\#rotate-float-) 方法。

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


归一化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [.getSkewAngle](../../null/\\#getSkewAngle) 和 [.rotate(float, boolean, Color)](../../null/\\#rotate-float--boolean--Color-) 方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| resizeProportionally | boolean | 如果设置为 true，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | [Color](../../com.aspose.psd/color) | 背景颜色。 |

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


当此 [Image](../../com.aspose.psd/image) 的容器被设置时调用。

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


通过指定的扫描线索引读取整条扫描线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |

**Returns:**
int[] - 扫描线的 32 位 ARGB 颜色值数组。
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


通过指定的扫描线索引读取整条扫描线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |

**Returns:**
com.aspose.psd.Color[] - 扫描线像素颜色值数组。
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


移除全局文本引擎资源 - 此方法用于某些在处理后无法在 Adobe Photoshop 中打开的文本图层 PSD 文件（主要与缺失字体的文本图层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：Menu "Text" -> "Process absent fonts"。完成该操作后，所有文本将再次出现。请注意，此操作可能导致部分最终布局的更改。

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | 要被替换的旧颜色。 |
| oldColorDiff | byte | 允许的旧颜色差异，以便能够扩大被替换颜色的色调。 |
| newColor | [Color](../../com.aspose.psd/color) | 用于替换旧颜色的新颜色。 |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| oldColorArgb | int | 要被替换的旧颜色 ARGB 值。 |
| oldColorDiff | byte | 允许的旧颜色差异，以便能够扩大被替换颜色的色调。 |
| newColorArgb | int | 用于替换旧颜色的新颜色 ARGB 值。 |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | 用于替换非透明颜色的新颜色。 |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorArgb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


调整图像大小。默认使用 ResizeType.LeftTopToLeftTop。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


调整图像大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 缩放设置。 |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


调整图像大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整类型。 |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


按比例调整高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


按比例调整高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 图像缩放设置。 |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


按比例调整高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newHeight | int | 新的高度。 |
| resizeType | int | 缩放类型。 |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


按比例调整宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


按比例调整宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | 图像缩放设置。 |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


按比例调整宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| resizeType | int | 缩放类型。 |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


使用指定的逆比例缩放图层。（新宽度 = 旧宽度 / 比例；新高度 = 旧高度 / 比例）

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scaleX | double | X 方向比例。 |
| scaleY | double | Y 方向比例。 |
| resizeType | int | 缩放类型。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


围绕中心旋转图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（度）。正值将顺时针旋转。 |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


围绕中心旋转图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（度）。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 true，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | [Color](../../com.aspose.psd/color) | 背景颜色。 |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


旋转、翻转或同时旋转并翻转图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


将图像数据保存到底层流。

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


将对象的数据保存到指定流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存对象数据的流。 |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


根据保存选项，将图像的数据以指定的文件格式保存到指定流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存图像数据的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存选项。 |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


根据保存选项，将图像的数据以指定的文件格式保存到指定流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于保存图像数据的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存选项。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


将对象的数据保存到指定流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 用于保存对象数据的流。 |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


根据保存选项，将对象的数据以指定的文件格式保存到指定文件位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 用于保存图像数据的文件。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项。 |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


根据保存选项，将图像的数据以指定的文件格式保存到指定流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件 | java.io.RandomAccessFile | 用于保存图像数据的文件。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存选项。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界矩形。设置空矩形以使用 sourse 边界。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


将对象的数据保存到指定文件位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存对象数据的文件路径。 |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


将对象的数据保存到指定文件位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存对象数据的文件路径。 |
| overWrite | boolean | 如果设置为 true，则覆盖文件内容，否则将进行追加。 |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


根据保存选项，将对象的数据以指定的文件格式保存到指定文件位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项。 |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


根据保存选项，将对象的数据以指定的文件格式保存到指定文件位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界矩形。设置空矩形以使用 sourse 边界。 |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


保存 32 位 ARGB 像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


保存像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于保存像素的矩形。 |
| 像素 | int[] | 以 32 位整数值表示的 CMYK 像素。 |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


保存像素。此方法已弃用。请使用更有效的 saveCmyk32Pixels(Rectangle, int[]) 方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于保存像素的矩形。 |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 像素数组。 |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


保存像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于保存像素的矩形。 |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 像素数组。 |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


保存原始数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 原始数据。 |
| dataOffset | int | 起始原始数据偏移量。 |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 原始数据矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 原始数据所在的设置。 |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


使用指定的保存选项和边界将图像数据保存到指定的流中。可选地，仅导出指定的图层以进行渲染预览。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 图像数据将被保存的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 要使用的保存选项。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界矩形。设置为  Rectangle.Empty  以使用源边界。 |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | 要导出的特定图层。null 值表示默认行为，即导出所有图层。 |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


根据保存选项，将图像的数据以指定的文件格式保存到指定流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 用于保存图像数据的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存选项。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


获取或设置活动图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


为指定位置设置图像的 32 位 ARGB 像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 像素 x 位置。 |
| y | int | 像素 y 位置。 |
| argb32Color | int | 指定位置的 32 位 ARGB 像素。 |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


设置一个值，指示是否自动调整调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true 如果启用自动调整调色板；否则为 false。 |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


获取或设置一个值，指示图像是否具有背景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


获取或设置背景颜色的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


获取或设置背景颜色。它可以在透明对象下看到。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。 |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


获取或设置 CMYK PSD 图像的 CMYK 颜色配置文件。必须与 RgbColorProfile 配对以实现正确的颜色转换。

值：CMYK 颜色配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


获取或设置颜色模式。

值：该颜色模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


设置 Image 容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image 容器。 |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


直接设置数据加载器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | 数据加载器。 |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


设置对象的数据流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | 对象的数据流。 |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


将调色板设置到特定格式的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 新的 32 位 ARGB 调色板。 |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


全局角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


获取或设置全局图层资源。

值：全局图层资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


灰度（单色）PSD 图像的 GRAY 色彩配置文件。

值：GRAY（单色）颜色配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的水平分辨率（每英寸像素数）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


设置一个值，指示是否 [ignore after save]。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true 如果 [ignore after save]；否则为 false。 |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


获取或设置一个值，指示此图像实例在加载后是否已更改。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true 如果此实例的图像已更改；否则为 false。 |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


获取或设置 PSD 图像资源。

值：PSD 图像资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


设置内部数据转换器。

值：内部数据转换器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.IInnerDataTransformer | 内部数据转换器。 |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


设置中断监视器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | 中断监视器。 |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


获取或设置 PSD 图层。

值：PSD 图层。

--------------------

请注意，如果没有图层，图层和蒙版信息部分中的其他相关信息（图层蒙版、资源等）将不会被保留。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


获取或设置部分旋转保存的最大允许分配。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 部分旋转保存的最大允许分配。 |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


设置内存管理器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | 内存管理器。 |
| needDispose | boolean | 如果设置为  true  [需要释放]。 |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


设置颜色调色板。颜色调色板在像素直接表示时不使用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


设置图像调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为  true  颜色将根据新调色板更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，不变的索引可能导致图像加载时崩溃。 |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


为指定位置设置图像像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 像素 x 位置。 |
| y | int | 像素 y 位置。 |
| color | [Color](../../com.aspose.psd/color) | 指定位置的像素颜色。 |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


获取或设置一个值，指示图像组件是否必须预乘。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true  如果图像组件必须预乘；否则，  false 。 |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


获取或设置自定义颜色转换器

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | 自定义颜色转换器 |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


获取或设置当调色板索引超出范围时使用的回退索引

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 调色板索引超出范围时使用的回退索引 |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


获取或设置索引颜色转换器

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | 索引颜色转换器 |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dpiX | double | RasterImage 的水平分辨率（每英寸点数）。 |
| dpiY | double | RasterImage 的垂直分辨率（每英寸点数）。 |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


获取或设置 CMYK PSD 图像的 RGB 颜色配置文件。必须与 CmykColorProfile 配对以实现正确的颜色转换。

值：RGB 颜色配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


获取或设置旋转模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 旋转模式。 |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


获取或设置一个值，以指示在指定图层数据时，第一个 alpha 通道是否包含合并结果的透明度数据。

值：如果在指定图层数据时第一个 alpha 通道包含合并结果的透明度数据，则为  true ，否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


获取一个值，指示图像是否具有透明颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


获取图像透明颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


获取或设置一个值，指示是否更新 XMP 元数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true  如果更新 XMP 元数据；否则，  false 。 |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true  如果在原始数据加载可用时使用原始数据加载；否则，  false 。 |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


设置企业许可证。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ventureLicense | java.lang.Object | venture license。 |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


获取或设置版本。

值：版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


获取或设置此 [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) 的垂直分辨率（每英寸像素数）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


获取或设置 XMP 元数据。

值：XMP 元数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


将光栅图像转换为位图。

**Returns:**
java.awt.image.BufferedImage - 位图
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


将整条扫描线写入指定的扫描线索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |
| argb32Pixels | int[] | 要写入的 32 位 ARGB 颜色数组。 |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


将整条扫描线写入指定的扫描线索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scanLineIndex | int | 扫描线的零基索引。 |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 要写入的像素颜色数组。 |

