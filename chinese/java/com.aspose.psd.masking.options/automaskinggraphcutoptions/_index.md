---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "GraphCut 自动掩码选项。"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

GraphCut 自动掩码选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | 初始化 [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | 背景对象编号 |
## Methods

| Method | 描述 |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | 追加自动遮罩参数。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | 填充默认笔画。 |
| [getArgs()](#getArgs--) | 获取分割算法的参数。 |
| [getAssumedObjects()](#getAssumedObjects--) | 获取假定的对象。 |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | 获取背景替换颜色。 |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | 获取一个指示是否应计算默认笔画的值。 |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | 获取组合对象的矩形。 |
| [getDecompose()](#getDecompose--) | 获取一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。 |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | 获取默认背景笔画。 |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | 获取预先计算的默认前景笔画。 |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | 获取默认对象矩形。 |
| [getExportOptions()](#getExportOptions--) | 获取图像导出选项。 |
| [getFeatheringRadius()](#getFeatheringRadius--) | 获取羽化半径。 |
| [getMaskingArea()](#getMaskingArea--) | 获取掩码区域。 |
| [getMethod()](#getMethod--) | 获取分割方法。 |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | 获取默认点预计算过程进度事件处理程序。 |
| [hasHumans_internalized()](#hasHumans-internalized--) | 获取一个值，指示假定对象集合中是否包含人类对象。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | 设置分割算法的参数。 |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | 设置假定对象。 |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | 设置背景替换颜色。 |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | 设置一个值，指示是否应计算默认笔画。 |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | 组合对象的矩形。 |
| [setDecompose(boolean value)](#setDecompose-boolean-) | 设置一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。 |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | 默认背景笔画。 |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | 预先计算的默认前景笔画。 |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | 默认对象矩形。 |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | 设置图像导出选项。 |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | 设置羽化半径。 |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | 一个值，指示假定对象集合中是否包含人类对象。 |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | 设置掩码区域。 |
| [setMethod(int value)](#setMethod-int-) | 设置分割方法。 |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 设置默认点预计算过程进度事件处理程序。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


初始化 [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) 类的新实例。

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


背景对象编号

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


追加自动遮罩参数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 图像。 |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


填充默认笔画。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 图像。 |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


获取分割算法的参数。

值：分割算法的参数。

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


获取假定的对象。

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - 假定对象。
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


获取背景替换颜色。

值：背景替换颜色。此颜色将在生成的图像中用作背景颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


获取一个指示是否应计算默认笔画的值。

**Returns:**
boolean - 一个值，指示是否应计算默认笔画。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


获取组合对象的矩形。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


获取一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。

值：如果分解则为 true；否则为 false。

**Returns:**
boolean - 一个指示是否不需要将每个 Shape 从遮罩中分离为单独对象或作为从遮罩中分离的背景的联合对象的值。
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


获取默认背景笔画。

**Returns:**
com.aspose.psd.Point[] - 默认背景笔画。
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


获取预先计算的默认前景笔画。

**Returns:**
com.aspose.psd.Point[] - 预先计算的默认前景笔画。
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


获取默认对象矩形。

**Returns:**
com.aspose.psd.Rectangle[] - 默认对象矩形。
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


获取图像导出选项。

值：将用于创建生成图像的图像导出选项。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


获取羽化半径。

**Returns:**
int - 羽化半径。
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


获取掩码区域。

值：遮罩区域，是源图像的部分区域。Rectangle.Empty 值表示整个源图像区域。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


获取分割方法。

值：分割方法。

**Returns:**
int - 分割方法。
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


获取默认点预计算过程进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


获取一个值，指示假定对象集合中是否包含人类对象。

**Returns:**
boolean - 一个值，指示假定对象集合中是否包含人类对象。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


设置分割算法的参数。

值：分割算法的参数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | 分割算法的参数。 |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


设置假定对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | 假定对象。 |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


设置背景替换颜色。

值：背景替换颜色。此颜色将在生成的图像中用作背景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 背景替换颜色。 |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


设置一个值，指示是否应计算默认笔画。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个值，指示是否应计算默认笔画。 |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


组合对象的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | 组合对象的矩形。 |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


设置一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。

值：如果分解则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个指示是否不需要将每个 Shape 从遮罩中分离为单独对象或作为从遮罩中分离的背景的联合对象的值。 |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


默认背景笔画。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 默认背景笔画。 |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


预先计算的默认前景笔画。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 预先计算的默认前景笔画。 |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


默认对象矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 默认对象矩形。 |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


设置图像导出选项。

值：将用于创建生成图像的图像导出选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像导出选项。 |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


设置羽化半径。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 羽化半径。 |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


一个值，指示假定对象集合中是否包含人类对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示假定对象集合中是否包含人类对象的值。 |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


设置掩码区域。

值：遮罩区域，是源图像的部分区域。Rectangle.Empty 值表示整个源图像区域。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | 遮罩区域。 |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


设置分割方法。

值：分割方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 分割方法。 |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


设置默认点预计算过程进度事件处理程序。

值：进度事件处理程序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 默认点预计算过程进度事件处理程序。 |

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

