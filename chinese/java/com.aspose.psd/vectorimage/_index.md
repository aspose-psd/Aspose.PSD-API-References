---
title: "VectorImage"
second_title: "Aspose.PSD 的 Java API 参考"
description: "矢量图像是所有类型矢量图像的基类。"
type: docs
weight: 111
url: /zh/java/com.aspose.psd/vectorimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.interfaces.IObjectWithSizeF](../../com.aspose.psd.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

矢量图像是所有类型矢量图像的基类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorImage()](#VectorImage--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | 当图像被加载时发生 |
| [OnLoad_internalized](#OnLoad-internalized) | 当图像通过 createFirstSupportedLoader 加载时发生 |
| [OnSave_internalized](#OnSave-internalized) | 当图像被加载或保存时发生 |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | 当使用 credit 时发生 |
## Methods

| Method | 描述 |
| --- | --- |
| [cacheData()](#cacheData--) | 缓存数据并确保不会从底层的 DataStreamSupporter.DataStreamContainer 加载额外的数据。 |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | 确定是否可以从指定的流加载图像。 |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | 确定是否可以从指定的流加载图像，并可选地使用指定的 loadOptions。 |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | 确定是否可以从指定的文件路径加载图像。 |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的 open options。 |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | 确定是否可以将图像保存为由传入的 save options 表示的指定文件格式。 |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | 转换为 aps。 |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | 使用指定的 create options 创建新图像。 |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | 使用指定的图像作为页面创建新图像。 |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | 使用指定的图像作为页面创建新图像。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | 获取一个值，指示是否自动调整调色板。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置背景颜色的值。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数。 |
| [getBounds()](#getBounds--) | 获取图像边界。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | 获取 Image 容器。 |
| [getDataStreamContainer()](#getDataStreamContainer--) | 获取对象的数据流。 |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | 获取深度调整的调色板。 |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | 获取默认选项。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFileFormat()](#getFileFormat--) | 获取文件格式的值 |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | 获取文件格式。 |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | 获取文件格式。 |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | 获取文件格式。 |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | 获取适合当前图像的矩形。 |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | 获取适合当前图像的矩形。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getHeightF()](#getHeightF--) | 获取对象的高度，单位为英寸。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 获取中断监视器。 |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | 获取内存管理器。 |
| [getOriginalOptions()](#getOriginalOptions--) | 根据原始文件设置获取选项。 |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | 获取可绘制的图像。 |
| [getPalette()](#getPalette--) | 获取颜色调色板。 |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | 创建私有字体缓存。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取进度事件处理程序信息。 |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | 获取进度事件处理程序信息。 |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | 获取比例高度。 |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | 获取比例宽度。 |
| [getSize()](#getSize--) | 获取图像尺寸。 |
| [getSizeF()](#getSizeF--) | 获取对象的尺寸，单位为英寸。 |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | 获取源图像的文件路径（如果存在）。 |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | 获取一个值，指示对象是否使用内存优化策略 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 获取风险许可证。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getWidthF()](#getWidthF--) | 获取对象的宽度，单位为英寸。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 获取一个值，指示图像是否具有背景颜色。 |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | 获取或设置一个值，指示此图像实例在加载后是否已更改。 |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | 获取或设置进度最大值 |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | 指示进度。 |
| [isCached()](#isCached--) | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| [isUsePalette()](#isUsePalette--) | 获取一个值，指示是否使用图像调色板。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从指定的流加载新图像。 |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | 从指定的流加载新图像。 |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | 从指定的流加载新图像。 |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | 从指定的流加载新图像。 |
| [load(String filePath)](#load-java.lang.String-) | 从指定的文件加载新图像。 |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | 从指定的文件加载新图像。 |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | 从指定的流加载新图像。 |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | 从指定的流加载新图像。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | 当此 [Image](../../com.aspose.psd/image) 的容器被设置时调用。 |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | 调整图像大小。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小。 |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | 按比例调整高度。 |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | 按比例调整高度。 |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | 按比例调整高度。 |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | 按比例调整宽度。 |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | 按比例调整宽度。 |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | 按比例调整宽度。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | 旋转、翻转或同时旋转并翻转图像。 |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | 设置一个值，指示是否自动调整调色板。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 获取或设置一个值，指示图像是否具有背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 获取或设置背景颜色的值。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | 设置 Image 容器。 |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | 设置对象的数据流。 |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 设置一个值，指示是否 [ignore after save]。 |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | 获取或设置一个值，指示此图像实例在加载后是否已更改。 |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | 设置中断监视器。 |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | 设置内存管理器。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 设置颜色调色板。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | 设置图像调色板。 |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | 所有 Aspose 产品都应实现此方法。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorImage() {#VectorImage--}
```
public VectorImage()
```


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

### cacheData() {#cacheData--}
```
public abstract void cacheData()
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


转换为 aps。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像选项。 |
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
### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
public abstract int getBitsPerPixel()
```


获取图像每像素位数。

**Returns:**
int - 图像每像素位数。
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

**Returns:**
int - 图像高度。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


获取对象的高度，单位为英寸。

**Returns:**
float - 对象高度（英寸）。
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


获取中断监视器。

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


获取内存管理器。

值：内存管理器。

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - 内存管理器。
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
### getSize() {#getSize--}
```
public Size getSize()
```


获取图像尺寸。

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


获取对象的尺寸，单位为英寸。

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the object size, in inches.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


获取源图像的文件路径（如果存在）。如果找不到源路径，则返回空字符串。

**Returns:**
java.lang.String - 源图像的文件路径。
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


获取一个值，指示对象是否使用内存优化策略

值：  true  如果对象使用内存优化策略；否则，  false .

**Returns:**
boolean - 表示对象是否使用内存优化策略的值
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


获取风险许可证。

**Returns:**
java.lang.Object - Teh venture 许可证作为对象。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

**Returns:**
int - 图像宽度。
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


获取对象的宽度，单位为英寸。

**Returns:**
float - 对象宽度（英寸）。
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


获取一个值，指示对象的数据当前是否已缓存且无需读取数据。

**Returns:**
boolean - 一个值，指示对象的数据当前是否已缓存且无需读取数据。
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


获取一个值，指示是否使用图像调色板。

值：  true  如果图像中使用调色板；否则，  false .

**Returns:**
boolean - 表示是否使用图像调色板的值
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


旋转、翻转或同时旋转并翻转图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转的类型。 |

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




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


设置 Image 容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image 容器。 |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


设置对象的数据流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | 对象的数据流。 |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


设置中断监视器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | 中断监视器。 |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


设置图像调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为  true  颜色将根据新调色板更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，不变的索引可能导致图像加载时崩溃。 |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


所有 Aspose 产品都应实现此方法。该方法由 GroupDocs 产品调用，以指示 GroupDocs 本身是否已授权，并指定自定义水印。当 GroupDocs 获得授权时，即使 Aspose 产品未授权，此文档实例也应表现为已授权。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

