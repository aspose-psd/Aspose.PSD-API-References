---
title: "ResolutionSetting"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图像保存选项的分辨率设置。"
type: docs
weight: 92
url: /zh/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

图像保存选项的分辨率设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | 初始化一个新的 ResolutionSetting 类实例。 |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | 初始化一个新的 ResolutionSetting 类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | 根据从 PdfOptions.ResolutionSettings 获取的 DPI 分辨率（或使用默认值）或图像本身，定义 PDF 页面尺寸。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | 获取或设置水平分辨率。 |
| [getVerticalResolution()](#getVerticalResolution--) | 获取或设置垂直分辨率。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 获取或设置水平分辨率。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 获取或设置垂直分辨率。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


初始化一个新的 ResolutionSetting 类实例。

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


初始化一个新的 ResolutionSetting 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| horizontalResolution | double | 水平分辨率。 |
| verticalResolution | double | 垂直分辨率。 |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


根据从 PdfOptions.ResolutionSettings 获取的 DPI 分辨率（或使用默认值）或图像本身，定义 PDF 页面尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 图像尺寸。 |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | 原始分辨率。 |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | 新分辨率。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


获取或设置水平分辨率。

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


获取或设置垂直分辨率。

**Returns:**
double
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




### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


获取或设置水平分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


获取或设置垂直分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

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

