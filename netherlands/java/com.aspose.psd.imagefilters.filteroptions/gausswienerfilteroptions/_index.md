---
title: "GaussWienerFilterOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Gauss Wiener filteropties Deblur gauss"
type: docs
weight: 15
url: /nl/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Gauss Wiener filteropties Deblur gauss
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Initialiseert een nieuw exemplaar van de  GaussWienerFilterOptions  klasse. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Initialiseert een nieuw exemplaar van de  GaussWienerFilterOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Geeft of stelt de helderheid in. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Haalt of stelt een waarde in die aangeeft of deze [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) grijswaarden is. |
| [getRadius()](#getRadius--) | Haalt op of stelt de radius in. |
| [getSmooth()](#getSmooth--) | Haalt of stelt de gladheid in. |
| [getSnr()](#getSnr--) | Haalt of stelt de SNR (signaal-ruisverhouding) aanbevolen bereik 0.002 - 0.009, standaardwaarde = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Haalt een waarde op die aangeeft of dit exemplaar gedeeltelijk geladen is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Geeft of stelt de helderheid in. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Haalt of stelt een waarde in die aangeeft of deze [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) grijswaarden is. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Haalt een waarde op die aangeeft of dit exemplaar gedeeltelijk geladen is. |
| [setRadius(int value)](#setRadius-int-) | Haalt op of stelt de radius in. |
| [setSmooth(double value)](#setSmooth-double-) | Haalt of stelt de gladheid in. |
| [setSnr(double value)](#setSnr-double-) | Haalt of stelt de SNR (signaal-ruisverhouding) aanbevolen bereik 0.002 - 0.009, standaardwaarde = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Initialiseert een nieuw exemplaar van de  GaussWienerFilterOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | int | De radius. |
| gladheid | double | De gladheid. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Initialiseert een nieuw exemplaar van de  GaussWienerFilterOptions  klasse. Met standaardinstellingen.

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
### getRadius() {#getRadius--}
```
public int getRadius()
```


Haalt op of stelt de radius in.

Waarde: De radius.

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

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Haalt op of stelt de radius in.

Waarde: De radius.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

