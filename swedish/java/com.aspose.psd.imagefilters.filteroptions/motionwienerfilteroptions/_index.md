---
title: "MotionWienerFilterOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "Dekonvolutionsfilteralternativ     rörelseavskärpning"
type: docs
weight: 18
url: /sv/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Dekonvolutionsfilteralternativ deblur motion
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Initierar en ny instans av klassen  MotionWienerFilterOptions . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Hämtar eller anger vinkeln i gradus. |
| [getBrightness()](#getBrightness--) | Hämtar eller anger ljusstyrkan. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Hämtar eller anger ett värde som indikerar om denna [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) är gråskala. |
| [getLength()](#getLength--) | Hämtar eller anger längden. |
| [getSmooth()](#getSmooth--) | Hämtar eller anger mjukheten. |
| [getSnr()](#getSnr--) | Hämtar eller anger SNR(signal‑to‑noise‑ratio) rekommenderat intervall 0.002 - 0.009, standardvärde = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Hämtar ett värde som indikerar om denna instans är delvis inläst. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln i gradus. |
| [setBrightness(double value)](#setBrightness-double-) | Hämtar eller anger ljusstyrkan. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Hämtar eller anger ett värde som indikerar om denna [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) är gråskala. |
| [setLength(int value)](#setLength-int-) | Hämtar eller anger längden. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Hämtar ett värde som indikerar om denna instans är delvis inläst. |
| [setSmooth(double value)](#setSmooth-double-) | Hämtar eller anger mjukheten. |
| [setSnr(double value)](#setSnr-double-) | Hämtar eller anger SNR(signal‑to‑noise‑ratio) rekommenderat intervall 0.002 - 0.009, standardvärde = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Initierar en ny instans av klassen  MotionWienerFilterOptions .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| längd | int | Längden. |
| mjukhet | double | Mjukheten. |
| angle | double | Vinkeln i gradus. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


Hämtar eller anger vinkeln i gradus.

Värde: Vinkeln.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Hämtar eller anger ljusstyrkan. rekommenderat intervall 1 - 1.5 standardvärde = 1.15

Värde: ljusstyrkan.

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


Hämtar eller anger ett värde som indikerar om denna [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) är gråskala. Returnerar gråskaleläge eller RGB‑läge.

Värde:  true  om gråskala; annars  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar eller anger längden.

Värde: Längden.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Hämtar eller anger mjukheten.

Värde: Mjukheten.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Hämtar eller anger SNR(signal‑to‑noise‑ratio) rekommenderat intervall 0.002 - 0.009, standardvärde = 0.007

Värde: SNR.

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


Hämtar ett värde som indikerar om denna instans är delvis inläst.

Värde:  true  om denna instans är delvis inläst; annars  false .

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


Hämtar eller anger vinkeln i gradus.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Hämtar eller anger ljusstyrkan. rekommenderat intervall 1 - 1.5 standardvärde = 1.15

Värde: ljusstyrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) är gråskala. Returnerar gråskaleläge eller RGB‑läge.

Värde:  true  om gråskala; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Hämtar eller anger längden.

Värde: Längden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Hämtar ett värde som indikerar om denna instans är delvis inläst.

Värde:  true  om denna instans är delvis inläst; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Hämtar eller anger mjukheten.

Värde: Mjukheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Hämtar eller anger SNR(signal‑to‑noise‑ratio) rekommenderat intervall 0.002 - 0.009, standardvärde = 0.007

Värde: SNR.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

