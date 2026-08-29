---
title: "GraphCutMaskingOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "GraphCut 自动掩码选项。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

GraphCut 自动掩码选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | 背景对象编号 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | 获取分割算法的参数。 |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | 获取背景替换颜色。 |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | 获取一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。 |
| [getExportOptions()](#getExportOptions--) | 获取图像导出选项。 |
| [getFeatheringRadius()](#getFeatheringRadius--) | 获取羽化半径。 |
| [getMaskingArea()](#getMaskingArea--) | 获取掩码区域。 |
| [getMethod()](#getMethod--) | 获取分割方法。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | 设置分割算法的参数。 |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | 设置背景替换颜色。 |
| [setDecompose(boolean value)](#setDecompose-boolean-) | 设置一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。 |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | 设置图像导出选项。 |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | 设置羽化半径。 |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | 设置掩码区域。 |
| [setMethod(int value)](#setMethod-int-) | 设置分割方法。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


背景对象编号

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


获取分割算法的参数。

值：分割算法的参数。

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


获取背景替换颜色。

值：背景替换颜色。此颜色将在生成的图像中用作背景颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


获取一个值，指示是否无需将掩码中的每个 Shape 分离为单独的对象，或将其作为与背景分离的统一对象。

值：如果分解则为 true；否则为 false。

**Returns:**
boolean - 一个指示是否不需要将每个 Shape 从遮罩中分离为单独对象或作为从遮罩中分离的背景的联合对象的值。
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

