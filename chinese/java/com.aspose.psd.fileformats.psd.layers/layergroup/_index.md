---
title: "LayerGroup"
second_title: "Aspose.PSD 的 Java API 参考"
description: "组图层类"
type: docs
weight: 19
url: /zh/java/com.aspose.psd.fileformats.psd.layers/layergroup/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
```
public class LayerGroup extends Layer
```

组图层类
## 字段

| 字段 | 描述 |
| --- | --- |
| [BlendSignature](#BlendSignature) | 表示混合模式签名。 |
| [LayerHeaderSize](#LayerHeaderSize) | 图层头部大小。 |
| [OnCreate_internalized](#OnCreate-internalized) | 当图像被加载时发生 |
| [OnLoad_internalized](#OnLoad-internalized) | 当图像通过 createFirstSupportedLoader 加载时发生 |
| [OnSave_internalized](#OnSave-internalized) | 当图像被加载或保存时发生 |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | 当使用 credit 时发生 |
| [resources_internalized](#resources-internalized) | 资源 |
## Methods

| Method | 描述 |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | 获取与指定类型关联的资源。 |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | 将图层添加到图层组。 |
| [addLayer(Layer layer, int index)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-int-) | 将图层添加到图层组。 |
| [addLayerGroup(String groupName, int index)](#addLayerGroup-java.lang.String-int-) | 添加图层组。 |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | 将遮罩添加到当前图层。 |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | 添加资源。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 调整图像的亮度。 |
| [adjustContrast(float contrast)](#adjustContrast-float-) | 图像对比度 |
| [adjustGamma(float gamma)](#adjustGamma-float-) | 图像的伽马校正。 |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | 图像的伽马校正。 |
| [applyLayerMask()](#applyLayerMask--) | 将图层蒙版应用于图层，然后删除该蒙版。 |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | 将输入的 [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) 的图层样式设置应用于当前的 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 实例。 |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | 开始调整大小的过程。 |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。 |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | 使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。 |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | 使用预定义阈值对图像进行二值化。 |
| [binarizeOtsu()](#binarizeOtsu--) | 使用 Otsu 阈值对图像进行二值化。 |
| [buildGroupLayerMarkers_internalized(String groupName, PsdHeader psdHeader, IColorPalette colorPalette, int layerNestingLevel)](#buildGroupLayerMarkers-internalized-java.lang.String-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-int-) | 构建开始和结束组标记。 |
| [cacheData()](#cacheData--) | 缓存数据并确保不会从底层的 DataStreamSupporter.DataStreamContainer 加载额外的数据。 |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 确定是否可以从指定的流加载图像。 |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 确定是否可以从指定的流加载图像，并可选地使用指定的 loadOptions。 |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 确定是否可以从指定的文件路径加载图像。 |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的 open options。 |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 确定是否可以将图像保存为由传入的 save options 表示的指定文件格式。 |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | 转换为 aps。 |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 使用指定的 create options 创建新图像。 |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 使用指定的图像作为页面创建新图像。 |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 使用指定的图像作为页面创建新图像。 |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | 创建 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 类的新实例。 |
| [createLayerState_internalized()](#createLayerState-internalized--) | 根据当前 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 值创建新的 [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) 实例。 |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, IColorPalette palette)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
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
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | 在图层上绘制图像。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | 过滤指定的矩形。 |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | 查找可分配的资源。 |
| [findPattResource_internalized()](#findPattResource-internalized--) | 查找 PattResource。 |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | 通过唯一键查找资源。 |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | 获取或设置绝对边界。 |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | 获取图像的 32 位 ARGB 像素。 |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 获取一个值，指示是否自动调整调色板。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置背景颜色的值。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数。 |
| [getBlendClippedElements()](#getBlendClippedElements--) | 获取或设置剪裁元素的混合方式。 |
| [getBlendModeKey()](#getBlendModeKey--) | 获取或设置混合模式键。 |
| [getBlendModeSignature()](#getBlendModeSignature--) | 获取混合模式签名。 |
| [getBlendingOptions()](#getBlendingOptions--) | 获取混合选项。 |
| [getBottom()](#getBottom--) | 获取或设置底层位置。 |
| [getBounds()](#getBounds--) | 获取图像边界。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | 获取完整掩码模式的每行字节数。 |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | 获取每行字节数。 |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | 获取每行字节数。 |
| [getChannelInformation()](#getChannelInformation--) | 获取或设置通道信息。 |
| [getChannelsCount()](#getChannelsCount--) | 获取图层的通道计数。 |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | 获取或设置图层剪裁。 |
| [getContainer()](#getContainer--) | 获取 Image 容器。 |
| [getDataStreamContainer()](#getDataStreamContainer--) | 获取对象的数据流。 |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 获取深度调整的调色板。 |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | 获取默认的 32 位 ARGB 像素数组。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认选项。 |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | 获取使用部分像素加载器的默认像素数组。 |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | 获取使用部分像素加载器的默认原始数据数组。 |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | 获取默认原始数据数组。 |
| [getDisplayName()](#getDisplayName--) | 获取图层的显示名称。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getExtraLength()](#getExtraLength--) | 获取图层额外信息的字节长度。 |
| [getFileFormat()](#getFileFormat--) | 获取文件格式的值 |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | 获取文件格式。 |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | 获取文件格式。 |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | 获取文件格式。 |
| [getFillOpacity()](#getFillOpacity--) | 获取或设置填充不透明度。 |
| [getFiller()](#getFiller--) | 获取或设置图层填充器。 |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 获取适合当前图像的矩形。 |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 获取适合当前图像的矩形。 |
| [getFlags()](#getFlags--) | 获取或设置图层标志。 |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | 获取当前图层的 [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) 文件夹层次列表。 |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | 从特定格式的位置获取调色板。 |
| [getGUID_internalized()](#getGUID-internalized--) | 获取此 Layer 实例的唯一标识符。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getHeight()](#getHeight--) | 获取图层组的高度。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 获取或设置此 RasterImage 的水平分辨率（每英寸像素数）。 |
| [getImageOpacity()](#getImageOpacity--) | 获取此图像的不透明度。 |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | 获取内部数据转换器。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 获取中断监视器。 |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | 获取或设置图层混合范围数据。 |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | 获取或设置图层创建日期时间。 |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | 获取或设置图层锁定。 |
| [getLayerMaskData()](#getLayerMaskData--) | 获取或设置图层蒙版数据。 |
| [getLayerOptions()](#getLayerOptions--) | 获取图层选项。 |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | 获取或设置图层调色板。 |
| [getLayerType_internalized()](#getLayerType-internalized--) | 获取图层的类型。 |
| [getLayers()](#getLayers--) | 获取图层组中的图层 |
| [getLayersBounds_internalized()](#getLayersBounds-internalized--) | 获取 LayerGroup 中所有图层的联合边界。 |
| [getLeft()](#getLeft--) | 获取或设置左侧图层位置。 |
| [getLength()](#getLength--) | 获取图层的整体字节长度。 |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | 获取或设置部分旋转保存的最大允许分配。 |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | 获取内存管理器。 |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | 获取资源图像上次修改的日期和时间。 |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | 获取或设置图层名称。 |
| [getOpacity()](#getOpacity--) | 获取或设置图层不透明度。 |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | 获取总体不透明度。 |
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
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | 获取或设置自定义颜色转换器 |
| [getRawDataFormat()](#getRawDataFormat--) | 获取原始数据格式。 |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | 获取或设置索引颜色转换器 |
| [getRawLineSize()](#getRawLineSize--) | 获取原始行大小（字节）。 |
| [getResources()](#getResources--) | 获取或设置图层资源。 |
| [getRight()](#getRight--) | 获取或设置右侧图层位置。 |
| [getRotateMode()](#getRotateMode--) | 获取或设置旋转模式。 |
| [getSectionResource_internalized()](#getSectionResource-internalized--) | 从资源中获取 LayerSectionResource。 |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | 获取或设置图层列表中的装饰纸张颜色高亮 |
| [getSize()](#getSize--) | 获取图像尺寸。 |
| [getSkewAngle()](#getSkewAngle--) | 获取倾斜角度。 |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | 获取源图像的文件路径（如果存在）。 |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | 获取同步根目录。 |
| [getTop()](#getTop--) | 获取或设置顶部图层位置。 |
| [getTransparentColor()](#getTransparentColor--) | 获取图像透明颜色。 |
| [getUpdateXmpData()](#getUpdateXmpData--) | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | 获取一个值，指示对象是否使用内存优化策略 |
| [getUseRawData()](#getUseRawData--) | 获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。 |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | 获取使用的调色板。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 获取风险许可证。 |
| [getVerticalResolution()](#getVerticalResolution--) | 获取或设置此 RasterImage 的垂直分辨率（每英寸像素数）。 |
| [getWidth()](#getWidth--) | 获取图层组的宽度。 |
| [getXmpData()](#getXmpData--) | 获取或设置 XMP 元数据。 |
| [grayscale()](#grayscale--) | 将图像转换为其灰度表示。 |
| [hasAlpha()](#hasAlpha--) | 获取一个值，指示此实例是否具有 alpha 通道。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 获取一个值，指示图像是否具有背景颜色。 |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 获取或设置一个值，指示此图像实例在加载后是否已更改。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示图像是否具有透明颜色。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 获取或设置进度最大值 |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 指示进度。 |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | 向 Resources 集合插入资源。 |
| [isCached()](#isCached--) | 获取一个值，指示当前是否缓存了图像数据。 |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | 检测图层是否可用于保存到文件。 |
| [isOpen()](#isOpen--) | 获取或设置文件夹是否打开；如果设置为 true，则组在启动时处于打开状态，否则为最小化状态。 |
| [isRawDataAvailable()](#isRawDataAvailable--) | 获取一个值，指示是否可用原始数据加载。 |
| [isUsePalette()](#isUsePalette--) | 获取一个值，指示是否使用图像调色板。 |
| [isVisible()](#isVisible--) | 获取或设置一个值，指示该图层是否可见 |
| [isVisibleInGroup()](#isVisibleInGroup--) | 获取一个值，指示此实例在组中是否可见（如果图层不在组中，则表示根组）。 |
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
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | 将图层合并到指定图层 |
| [normalizeAngle()](#normalizeAngle--) | 归一化角度。 |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | 归一化角度。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | 在设置此 Image 的容器时调用。 |
| [onResourcesChange_internalized()](#onResourcesChange-internalized--) |  |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | 通过指定的扫描线索引读取整条扫描线。 |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | 通过指定的扫描线索引读取整条扫描线。 |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | 移除资源。 |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小。 |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | 调整通道数据的大小 |
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
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将对象的数据保存到指定流。 |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 根据保存选项，将图像的数据以指定的文件格式保存到指定流中。 |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | 将数据保存到指定的流容器。 |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | 获取或设置绝对边界。 |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 设置一个值，指示是否自动调整调色板。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 获取或设置一个值，指示图像是否具有背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 获取或设置背景颜色的值。 |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | 获取或设置剪裁元素的混合方式。 |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | 获取或设置混合模式键。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置底层位置。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | 获取或设置通道信息。 |
| [setClipping(byte value)](#setClipping-byte-) | 获取或设置图层剪裁。 |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | 设置 Image 容器。 |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | 直接设置数据加载器。 |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | 设置对象的数据流。 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | 获取或设置图层的显示名称。 |
| [setFillOpacity(int value)](#setFillOpacity-int-) | 获取填充不透明度。 |
| [setFiller(byte value)](#setFiller-byte-) | 获取或设置图层填充器。 |
| [setFlags(byte value)](#setFlags-byte-) | 获取或设置图层标志。 |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | 将调色板设置到特定格式的位置。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 获取或设置此 RasterImage 的水平分辨率（每英寸像素数）。 |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 设置一个值，指示是否 [ignore after save]。 |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 获取或设置一个值，指示此图像实例在加载后是否已更改。 |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | 设置内部数据转换器。 |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 设置中断监视器。 |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | 获取或设置图层混合范围数据。 |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | 获取或设置图层创建日期时间。 |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | 获取或设置图层锁定（注意，如果标志 LayerFlags.TransparencyProtected 已设置，它将被图层锁定标志覆盖）。 |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | 获取或设置图层蒙版数据。 |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | 获取或设置图层调色板。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置左侧图层位置。 |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | 获取或设置部分旋转保存的最大允许分配。 |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | 设置内存管理器。 |
| [setName(String name)](#setName-java.lang.String-) | 设置图层名称。 |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | 获取或设置图层名称。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 获取或设置图层不透明度。 |
| [setOpen(boolean value)](#setOpen-boolean-) | 获取或设置文件夹是否打开；如果设置为 true，则组在启动时处于打开状态，否则为最小化状态。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 设置颜色调色板。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 设置图像调色板。 |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | 为指定位置设置图像像素。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | 获取或设置自定义颜色转换器 |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | 获取或设置索引颜色转换器 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 设置此 RasterImage 的分辨率。 |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | 获取或设置图层资源。 |
| [setRight(int value)](#setRight-int-) | 获取或设置右侧图层位置。 |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | 获取或设置旋转模式。 |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | 获取或设置图层列表中的装饰纸张颜色高亮 |
| [setTop(int value)](#setTop-int-) | 获取或设置顶部图层位置。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 获取一个值，指示图像是否具有透明颜色。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | 获取图像透明颜色。 |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | 获取或设置一个值，指示在原始数据加载可用时是否使用原始数据加载。 |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | 所有 Aspose 产品都应实现此方法。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 获取或设置此 RasterImage 的垂直分辨率（每英寸像素数）。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置一个值，指示该图层是否可见 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | 获取或设置 XMP 元数据。 |
| [shallowCopy()](#shallowCopy--) | 创建当前 Layer 的浅拷贝。 |
| [toBitmap()](#toBitmap--) | 将光栅图像转换为位图。 |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | 在图层或全局资源更改后更新混合选项。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | 将整条扫描线写入指定的扫描线索引。 |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | 将整条扫描线写入指定的扫描线索引。 |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


表示混合模式签名。

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


图层头部大小。

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


资源

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


获取与指定类型关联的资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | 当此方法返回时，包含与指定键类型关联的资源（如果找到键）；否则返回 null。 |

T : 要获取的值的键类型。 |

**Returns:**
boolean -   如果包含具有指定类型的资源；否则，  。
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


将图层添加到图层组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 该图层。 |

### addLayer(Layer layer, int index) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public final void addLayer(Layer layer, int index)
```


将图层添加到图层组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 该图层。 |
| index | int | 将在此插入图层的索引。无效值表示图层列表的末尾。 |

### addLayerGroup(String groupName, int index) {#addLayerGroup-java.lang.String-int-}
```
public final LayerGroup addLayerGroup(String groupName, int index)
```


添加图层组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| groupName | java.lang.String | 组的名称。 |
| index | int | 要在其后插入的图层的索引。 |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


将遮罩添加到当前图层。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | 图层蒙版。 |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


添加资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | 资源。 |

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

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


将图层蒙版应用于图层，然后删除该蒙版。

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


将输入的 [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) 的图层样式设置应用于当前的 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | 具有新样式的图层状态。 |

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

### buildGroupLayerMarkers_internalized(String groupName, PsdHeader psdHeader, IColorPalette colorPalette, int layerNestingLevel) {#buildGroupLayerMarkers-internalized-java.lang.String-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-int-}
```
public static Layer[] buildGroupLayerMarkers_internalized(String groupName, PsdHeader psdHeader, IColorPalette colorPalette, int layerNestingLevel)
```


构建开始和结束组标记。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| groupName | java.lang.String | 组的名称。 |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | psd 标头。 |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |
| layerNestingLevel | int |  |

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[] - 返回一个包含两个 LayerGroup 对象的数组，其中第一个 [0] 是开始组标记，第二个 [1] 是结束组标记。
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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


创建 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | 头部。 |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 调色板。 |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | LinkedLayersRegistry。 |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


根据当前 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 值创建新的 [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) 实例。

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
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
### create_internalized(PsdHeader header, IColorPalette palette) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-}
```
public static LayerGroup create_internalized(PsdHeader header, IColorPalette palette)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


在图层上绘制图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | 位置。 |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 图像。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的对象。 |

**Returns:**
布尔值 -  true  如果指定的对象等于此实例；否则为  false .
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

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


查找可分配的资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | 类型。 |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


查找 PattResource。

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


通过唯一键查找资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| typeToolKey | int | 类型工具键。 |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


获取或设置绝对边界。

值：绝对边界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数。

值：图像每像素位数计数。

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


获取或设置剪裁元素的混合方式。

值：剪裁元素的混合。

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


获取或设置混合模式键。

值：混合模式键。

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


获取混合模式签名。

值：混合模式签名。

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


获取混合选项。

值：混合选项。

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


获取或设置底层位置。

值：底层位置。

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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


获取完整掩码模式的每行字节数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitDepth | int | 位深度。 |

**Returns:**
int - 存储 1 行所需的字节数
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


获取每行字节数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitDepth | int | 位深度。 |

**Returns:**
int - 存储 1 行所需的字节数
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


获取每行字节数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitDepth | int | 位深度。 |

**Returns:**
int - 存储 1 行所需的字节数
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


获取或设置通道信息。

值：通道信息。

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


获取图层的通道计数。

值：图层通道计数。

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


获取或设置图层剪裁。0 = 基础，1 = 非基础。

值：图层剪裁。

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


获取 Image 容器。

值： 图像 容器。

如果此属性不为 null，则表示该图像包含在另一个图像中。

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取图层的显示名称。

值： 图层的显示名称。

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


获取图层额外信息的字节长度。

值： 额外图层长度。

**Returns:**
int
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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


获取或设置填充不透明度。

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


获取或设置图层填充器。

值：图层填充器。

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


获取或设置图层标志。bit 0 = 透明受保护; bit 1 = 可见; bit 2 = 已废弃; bit 3 = 对于 Photoshop 5.0 及更高版本为 1，指示 bit 4 是否包含有用信息; bit 4 = 像素数据与文档外观无关。

值：图层标志。

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


获取当前图层的 [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) 文件夹层次列表。

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - 返回当前图层的 [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) 文件夹层次结构列表。
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


从特定格式的位置获取调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


获取此 Layer 实例的唯一标识符。

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


获取或设置标题。

值：头部。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图层组的高度。

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


获取或设置此 RasterImage 的水平分辨率（每英寸像素数）。

**Returns:**
double - 水平分辨率。

注意：默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


获取此图像的不透明度。

**Returns:**
float - 不透明度值，范围在 0.0（完全透明）到 1.0（完全不透明）之间。
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
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


获取或设置图层混合范围数据。

值：图层混合范围数据。

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


获取或设置图层创建日期时间。

值：图层的创建日期时间。如果没有创建 DateTime 的数据，则返回 Unix 时间的起始纪元。

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


获取或设置图层锁定。注意，如果设置了标志 LayerFlags.TransparencyProtected，它将被图层锁定标志覆盖。要返回 LayerFlags.TransparencyProtected 标志，需要在图层选项中使用 layer.Flags |= LayerFlags.TransparencyProtected。

值：图层锁定。

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


获取或设置图层蒙版数据。

值：图层蒙版数据。

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


获取图层选项。

值：图层选项。

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


获取或设置图层调色板。

值：图层调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


获取图层的类型。

值：图层的类型。

**Returns:**
byte
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


获取图层组中的图层

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLayersBounds_internalized() {#getLayersBounds-internalized--}
```
public Rectangle getLayersBounds_internalized()
```


获取 LayerGroup 中所有图层的联合边界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The union bounds of the all layers in LayerGroup
### getLeft() {#getLeft--}
```
public int getLeft()
```


获取或设置左侧图层位置。

值：左侧图层位置。

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


获取图层的整体字节长度。

**Returns:**
long
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
### getName() {#getName--}
```
public final String getName()
```


获取或设置图层名称。

值：图层名称。

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


获取或设置图层不透明度。0 = 透明，255 = 不透明。

值：图层不透明度。

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


获取总不透明度。总不透明度是图层不透明度与图层填充不透明度的乘积。它用于图层混合。

值：总不透明度。

**Returns:**
byte
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


获取或设置图层资源。

值：图层资源。

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


获取或设置右侧图层位置。

值：右侧图层位置。

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


获取或设置旋转模式。

**Returns:**
int - 旋转模式。
### getSectionResource_internalized() {#getSectionResource-internalized--}
```
public BaseLayerSectionResource getSectionResource_internalized()
```


从资源中获取 LayerSectionResource。

**Returns:**
[BaseLayerSectionResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource) - Returns the  LayerSectionResource  from resources.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


获取或设置图层列表中的装饰纸张颜色高亮

值：工作表颜色高亮。

**Returns:**
short
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


获取源图像的文件路径（如果存在）。如果找不到源路径，则返回空字符串。

**Returns:**
java.lang.String - 源图像的文件路径。
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


获取同步根目录。

值：同步根。

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


获取或设置顶部图层位置。

值：顶部图层位置。

**Returns:**
int
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


获取或设置此 RasterImage 的垂直分辨率（每英寸像素数）。

**Returns:**
double - 垂直分辨率。

注意：默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图层组的宽度。

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取或设置 XMP 元数据。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


将图像转换为其灰度表示。

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取一个值，指示此实例是否具有 alpha 通道。

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

**Returns:**
boolean -  true  如果此实例的图像已更改；否则，  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取一个值，指示图像是否具有透明颜色。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


向 Resources 集合插入资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 应插入的资源的索引。 |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | 应插入的资源。 |

### isCached() {#isCached--}
```
public boolean isCached()
```


获取一个值，指示当前是否缓存了图像数据。

**Returns:**
boolean -  true  如果图像数据已缓存；否则，  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


检测图层是否可用于保存到文件。

**Returns:**
boolean -
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


获取或设置文件夹是否打开；如果设置为 true，则组在启动时处于打开状态，否则为最小化状态。

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
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


获取或设置一个值，指示该图层是否可见

值：  true  如果此实例可见；否则，  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


获取一个值，指示此实例在组中是否可见（如果图层不在组中，则表示根组）。

值： true 如果此实例在组中可见；否则， false 。

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


将图层合并到指定图层

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 要合并到的图层。 |

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


在设置此 Image 的容器时调用。

### onResourcesChange_internalized() {#onResourcesChange-internalized--}
```
public void onResourcesChange_internalized()
```




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
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


移除资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | 资源。 |

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

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


调整通道数据的大小

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 矩形。 |

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

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


根据保存选项，将图像的数据以指定的文件格式保存到指定流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dstStream | java.io.OutputStream | 用于保存图像数据的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 保存选项。 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像边界矩形。设置空矩形以使用 sourse 边界。 |

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

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


将数据保存到指定的流容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| psdVersion | int | PSD 版本。 |
| bitDepth | int | 位深度。 |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


获取或设置绝对边界。

值：绝对边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


获取或设置剪裁元素的混合方式。

值：剪裁元素的混合。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


获取或设置混合模式键。

值：混合模式键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


获取或设置底层位置。

值：底层位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


获取或设置通道信息。

值：通道信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


获取或设置图层剪裁。0 = 基础，1 = 非基础。

值：图层剪裁。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

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

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


获取或设置图层的显示名称。

值： 图层的显示名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


获取填充不透明度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


获取或设置图层填充器。

值：图层填充器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


获取或设置图层标志。bit 0 = 透明受保护; bit 1 = 可见; bit 2 = 已废弃; bit 3 = 对于 Photoshop 5.0 及更高版本为 1，指示 bit 4 是否包含有用信息; bit 4 = 像素数据与文档外观无关。

值：图层标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

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
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


获取或设置标题。

值：头部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


获取或设置此 RasterImage 的水平分辨率（每英寸像素数）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | double | 水平分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

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

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


获取或设置图层混合范围数据。

值：图层混合范围数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


获取或设置图层创建日期时间。

值：图层的创建日期时间。如果没有创建 DateTime 的数据，则返回 Unix 时间的起始纪元。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


获取或设置图层锁定（注意，如果设置了标志 LayerFlags.TransparencyProtected，它将被图层锁定标志覆盖。要返回 LayerFlags.TransparencyProtected 标志，需要对图层选项应用 layer.Flags |= LayerFlags.TransparencyProtected）

值：图层锁定。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


获取或设置图层蒙版数据。

值：图层蒙版数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


获取或设置图层调色板。

值：图层调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


获取或设置左侧图层位置。

值：左侧图层位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


设置图层名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 图层名称。 |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


获取或设置图层名称。

值：图层名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


获取或设置图层不透明度。0 = 透明，255 = 不透明。

值：图层不透明度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


获取或设置文件夹是否打开；如果设置为 true，则组在启动时处于打开状态，否则为最小化状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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


设置此 RasterImage 的分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dpiX | double | RasterImage 的水平分辨率（每英寸点数）。 |
| dpiY | double | RasterImage 的垂直分辨率（每英寸点数）。 |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


获取或设置图层资源。

值：图层资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


获取或设置右侧图层位置。

值：右侧图层位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


获取或设置旋转模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 旋转模式。 |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


获取或设置图层列表中的装饰纸张颜色高亮

值：工作表颜色高亮。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


获取或设置顶部图层位置。

值：顶部图层位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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


所有 Aspose 产品都应实现此方法。该方法由 GroupDocs 产品调用，以指示 GroupDocs 本身是否已授权，并指定自定义水印。当 GroupDocs 获得授权时，即使 Aspose 产品未授权，此文档实例也应表现为已授权。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


获取或设置此 RasterImage 的垂直分辨率（每英寸像素数）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | double | 垂直分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


获取或设置一个值，指示该图层是否可见

值：  true  如果此实例可见；否则，  false .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


获取或设置 XMP 元数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP 元数据。 |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


创建当前图层的浅拷贝。请   参考说明。

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
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
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


在图层或全局资源更改后更新混合选项。

**Parameters:**
| Parameter | Type | 描述 |
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

