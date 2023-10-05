---
title: GaussWienerFilterOptions
second_title: Aspose.PSD for Java API Reference
description: Gauss Wiener Filter Options Deblur gauss
type: docs
weight: 15
url: /java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Gauss Wiener Filter Options Deblur gauss
## Constructors

| Constructor | Description |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Initializes a new instance of the  GaussWienerFilterOptions  class. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Initializes a new instance of the  GaussWienerFilterOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Gets or sets the brightness. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Gets or sets a value indicating whether this [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) is grayscale. |
| [getRadius()](#getRadius--) | Gets or sets the radius. |
| [getSmooth()](#getSmooth--) | Gets or sets the smooth. |
| [getSnr()](#getSnr--) | Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Gets a value indicating whether this instance is partial loaded. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Gets or sets the brightness. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Gets or sets a value indicating whether this [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) is grayscale. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Gets a value indicating whether this instance is partial loaded. |
| [setRadius(int value)](#setRadius-int-) | Gets or sets the radius. |
| [setSmooth(double value)](#setSmooth-double-) | Gets or sets the smooth. |
| [setSnr(double value)](#setSnr-double-) | Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Initializes a new instance of the  GaussWienerFilterOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | int | The radius. |
| smooth | double | The smooth. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Initializes a new instance of the  GaussWienerFilterOptions  class. With default settings.

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
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Gets or sets the brightness. recommended range 1 - 1.5 default value = 1.15

Value: The brightness.

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


Gets or sets a value indicating whether this [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) is grayscale. Return grayscale mode or RGB mode.

Value:  true  if grayscale; otherwise,  false .

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


Gets or sets the radius.

Value: The radius.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Gets or sets the smooth.

Value: The smooth.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007

Value: The SNR.

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


Gets a value indicating whether this instance is partial loaded.

Value:  true  if this instance is partial loaded; otherwise,  false .

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


Gets or sets the brightness. recommended range 1 - 1.5 default value = 1.15

Value: The brightness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Gets or sets a value indicating whether this [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) is grayscale. Return grayscale mode or RGB mode.

Value:  true  if grayscale; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Gets a value indicating whether this instance is partial loaded.

Value:  true  if this instance is partial loaded; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Gets or sets the radius.

Value: The radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Gets or sets the smooth.

Value: The smooth.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007

Value: The SNR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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

