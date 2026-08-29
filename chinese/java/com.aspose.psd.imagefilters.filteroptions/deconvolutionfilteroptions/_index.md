---
title: "DeconvolutionFilterOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Deconvolution Filter Options 抽象类"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase)
```
public abstract class DeconvolutionFilterOptions extends FilterOptionsBase
```

去卷积过滤器选项，抽象类
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | 获取或设置亮度。 |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | 获取或设置一个值，指示此 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) 是否为灰度。 |
| [getSnr()](#getSnr--) | 获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007。 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | 获取一个值，指示此实例是否已部分加载。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | 获取或设置亮度。 |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | 获取或设置一个值，指示此 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) 是否为灰度。 |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | 获取一个值，指示此实例是否已部分加载。 |
| [setSnr(double value)](#setSnr-double-) | 获取或设置 SNR（信噪比），推荐范围 0.002 - 0.009，默认值 = 0.007。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

