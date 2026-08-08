---
title: "MotionWienerFilterOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Deconvolutiefilteropties     beweging onscherp maken"
type: docs
weight: 18
url: /nl/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Deconvolutiefilteropties deblur beweging
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Initialiseert een nieuw exemplaar van de  MotionWienerFilterOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Haalt of stelt de hoek in graden. |
| [getBrightness()](#getBrightness--) | Geeft of stelt de helderheid in. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Haalt of stelt een waarde in die aangeeft of deze [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) grijswaarden is. |
| [getLength()](#getLength--) | Haalt of stelt de lengte in. |
| [getSmooth()](#getSmooth--) | Haalt of stelt de gladheid in. |
| [getSnr()](#getSnr--) | Haalt of stelt de SNR (signaal-ruisverhouding) aanbevolen bereik 0.002 - 0.009, standaardwaarde = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Haalt een waarde op die aangeeft of dit exemplaar gedeeltelijk geladen is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | Haalt of stelt de hoek in graden. |
| [setBrightness(double value)](#setBrightness-double-) | Geeft of stelt de helderheid in. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Haalt of stelt een waarde in die aangeeft of deze [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) grijswaarden is. |
| [setLength(int value)](#setLength-int-) | Haalt of stelt de lengte in. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Haalt een waarde op die aangeeft of dit exemplaar gedeeltelijk geladen is. |
| [setSmooth(double value)](#setSmooth-double-) | Haalt of stelt de gladheid in. |
| [setSnr(double value)](#setSnr-double-) | Haalt of stelt de SNR (signaal-ruisverhouding) aanbevolen bereik 0.002 - 0.009, standaardwaarde = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Initialiseert een nieuw exemplaar van de  MotionWienerFilterOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lengte | int | De lengte. |
| gladheid | double | De gladheid. |
| angle | double | De hoek in graden. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


Haalt of stelt de hoek in graden.

Waarde: De hoek.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Haalt op of stelt de helderheid in. aanbevolen bereik 1 - 1.5 standaardwaarde = 1.15

Waarde: De helderheid.

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


Haalt op of stelt een waarde in die aangeeft of deze [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) grijswaarden is. Retourneert grijswaardenmodus of RGB-modus.

Waarde: true als grijswaarden; anders false.

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Haalt of stelt de lengte in.

Waarde: De lengte.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Haalt of stelt de gladheid in.

Waarde: De gladde.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Haalt of stelt de SNR (signaal-ruisverhouding) aanbevolen bereik 0.002 - 0.009, standaardwaarde = 0.007

Waarde: De SNR.

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


Haalt een waarde op die aangeeft of dit exemplaar gedeeltelijk geladen is.

Waarde: true als deze instantie gedeeltelijk geladen is; anders false.

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


Haalt of stelt de hoek in graden.

Waarde: De hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Haalt op of stelt de helderheid in. aanbevolen bereik 1 - 1.5 standaardwaarde = 1.15

Waarde: De helderheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) grijswaarden is. Retourneert grijswaardenmodus of RGB-modus.

Waarde: true als grijswaarden; anders false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Haalt of stelt de lengte in.

Waarde: De lengte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Haalt een waarde op die aangeeft of dit exemplaar gedeeltelijk geladen is.

Waarde: true als deze instantie gedeeltelijk geladen is; anders false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Haalt of stelt de gladheid in.

Waarde: De gladde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Haalt of stelt de SNR (signaal-ruisverhouding) aanbevolen bereik 0.002 - 0.009, standaardwaarde = 0.007

Waarde: De SNR.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

