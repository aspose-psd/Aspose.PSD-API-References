---
title: "MultiPageOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "支持多页的格式的基类"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

支持多页的格式的基类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | 初始化 MultiPageOptions 类的新实例。 |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | 初始化 MultiPageOptions 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | 获取或设置导出区域。 |
| [getMergeLayers()](#getMergeLayers--) | 获取指示是否 [merege layers] 的值。 |
| [getMode()](#getMode--) | 获取或设置模式。 |
| [getOutputLayersNames()](#getOutputLayersNames--) | 获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd，则有效） |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | 获取页面光栅化选项。 |
| [getPageTitles()](#getPageTitles--) | 获取或设置页面标题。 |
| [getPages()](#getPages--) | 获取或设置页面。 |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | 获取时间间隔。 |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | 从 ranges 数组初始化页面 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | 获取或设置导出区域。 |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | 设置指示是否 [merege layers] 的值。 |
| [setMode(int value)](#setMode-int-) | 获取或设置模式。 |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | 获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd，则有效） |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | 设置页面光栅化选项。 |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | 获取或设置页面标题。 |
| [setPages(int[] value)](#setPages-int---) | 获取或设置页面。 |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | 设置时间间隔。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


初始化 MultiPageOptions 类的新实例。

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 页面 | int[] | 这些页面。 |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 页面 | int[] | 页面数组。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 导出区域。 |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | 页面标题。 |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | 页面标题。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 导出区域。 |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | IntRange |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | IntRange |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 导出区域。 |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | IntRange |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | IntRange |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 导出区域。 |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 页面 | int | 页面索引。 |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


初始化 MultiPageOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 页面 | int | 页面索引。 |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 导出区域。 |

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
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


获取或设置导出区域。

值：导出区域。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


获取指示是否 [merege layers] 的值。

值：如果 [merege layers] 为 true；否则为 false。

**Returns:**
boolean - 表示是否 [merege layers] 的值。
### getMode() {#getMode--}
```
public int getMode()
```


获取或设置模式。

值：模式。

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd，则有效）

值：输出图层名称。

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


获取页面光栅化选项。

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - 页面光栅化选项。
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


获取或设置页面标题。

值：页面标题。

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


获取或设置页面。

值：页面。

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


获取时间间隔。

值：时间间隔。

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


从 ranges 数组初始化页面

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | 范围。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


获取或设置导出区域。

值：导出区域。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


设置指示是否 [merege layers] 的值。

值：如果 [merege layers] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 表示是否 [merege layers] 的值。 |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


获取或设置模式。

值：模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


获取或设置输出图层名称（如果导出格式支持图层命名，例如 Psd，则有效）

值：输出图层名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


设置页面光栅化选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | 页面光栅化选项。 |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


获取或设置页面标题。

值：页面标题。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


获取或设置页面。

值：页面。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


设置时间间隔。

值：时间间隔。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | 时间间隔。 |

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

