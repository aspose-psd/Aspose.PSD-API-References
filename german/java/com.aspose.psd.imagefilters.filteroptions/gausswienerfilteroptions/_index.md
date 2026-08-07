---
title: "GaussWienerFilterOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Gauss‑Wiener-Filteroptionen Deblur gauss"
type: docs
weight: 15
url: /de/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Gauss‑Wiener-Filteroptionen Deblur gauss
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Initialisiert eine neue Instanz der Klasse GaussWienerFilterOptions. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Initialisiert eine neue Instanz der Klasse GaussWienerFilterOptions. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Liest oder setzt die Helligkeit. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Liest oder setzt einen Wert, der angibt, ob diese [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) Graustufen ist. |
| [getRadius()](#getRadius--) | Liest oder setzt den Radius. |
| [getSmooth()](#getSmooth--) | Liest oder setzt die Glättung. |
| [getSnr()](#getSnr--) | Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis), empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Liest oder setzt die Helligkeit. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) Graustufen ist. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist. |
| [setRadius(int value)](#setRadius-int-) | Liest oder setzt den Radius. |
| [setSmooth(double value)](#setSmooth-double-) | Liest oder setzt die Glättung. |
| [setSnr(double value)](#setSnr-double-) | Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis), empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Initialisiert eine neue Instanz der Klasse GaussWienerFilterOptions.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | int | Der Radius. |
| Glättung | double | Die Glättung. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Initialisiert eine neue Instanz der Klasse GaussWienerFilterOptions. Mit Standardeinstellungen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Liest oder setzt die Helligkeit, empfohlener Bereich 1 - 1,5, Standardwert = 1,15

Wert: Die Helligkeit.

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


Liest oder setzt einen Wert, der angibt, ob diese [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) Graustufen verwendet. Gibt Graustufen‑Modus oder RGB‑Modus zurück.

Wert:  true  wenn Graustufen; sonst  false .

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


Liest oder setzt den Radius.

Wert: Der Radius.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Liest oder setzt die Glättung.

Wert: Die Glättung.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis), empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007

Wert: Das SNR.

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


Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist.

Wert:  true  wenn diese Instanz teilweise geladen ist; sonst  false .

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


Liest oder setzt die Helligkeit, empfohlener Bereich 1 - 1,5, Standardwert = 1,15

Wert: Die Helligkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) Graustufen verwendet. Gibt Graustufen‑Modus oder RGB‑Modus zurück.

Wert:  true  wenn Graustufen; sonst  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist.

Wert:  true  wenn diese Instanz teilweise geladen ist; sonst  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Liest oder setzt den Radius.

Wert: Der Radius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Liest oder setzt die Glättung.

Wert: Die Glättung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis), empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007

Wert: Das SNR.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

