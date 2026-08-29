---
title: "GaussWienerFilterOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Gauss Wiener Filter Options Deblur gauss"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Gauss Wiener Filter Options Deblur gauss
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | 初始化 GaussWienerFilterOptions 类的新实例。 |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | 初始化 GaussWienerFilterOptions 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | 获取或设置亮度。 |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | 获取或设置一个值，指示此 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) 是否为灰度。 |
| [getRadius()](#getRadius--) | 获取或设置半径。 |
| [getSmooth()](#getSmooth--) | 获取或设置平滑度。 |
| [getSnr()](#getSnr--) | 获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007。 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | 获取一个值，指示此实例是否已部分加载。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | 获取或设置亮度。 |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | 获取或设置一个值，指示此 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) 是否为灰度。 |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | 获取一个值，指示此实例是否已部分加载。 |
| [setRadius(int value)](#setRadius-int-) | 获取或设置半径。 |
| [setSmooth(double value)](#setSmooth-double-) | 获取或设置平滑度。 |
| [setSnr(double value)](#setSnr-double-) | 获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


初始化 GaussWienerFilterOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 半径 | int | 半径。 |
| 平滑 | double | 平滑。 |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


初始化 GaussWienerFilterOptions 类的新实例。使用默认设置。

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
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15。

值：亮度。

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


获取或设置一个值，指示此 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) 是否为灰度。返回灰度模式或 RGB 模式。

值： true 如果为灰度；否则， false。

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


获取或设置半径。

值：半径。

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


获取或设置平滑度。

值：平滑。

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007。

值：信噪比。

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


获取一个值，指示此实例是否已部分加载。

值： true 如果此实例已部分加载；否则， false 。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15。

值：亮度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


获取或设置一个值，指示此 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) 是否为灰度。返回灰度模式或 RGB 模式。

值： true 如果为灰度；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


获取一个值，指示此实例是否已部分加载。

值： true 如果此实例已部分加载；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


获取或设置半径。

值：半径。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


获取或设置平滑度。

值：平滑。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007。

值：信噪比。

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

