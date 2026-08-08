---
title: "ColorantCmyk"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar CMYK Colorant."
type: docs
weight: 13
url: /sv/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Representerar CMYK Colorant.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Initierar en ny instans av klassen  ColorantCmyk . |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Initierar en ny instans av klassen  ColorantCmyk . |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Maximalt färgvärde i CMYK-färgämne. |
| [ColorValueMin](#ColorValueMin) | Minimalt färgvärde i CMYK-färgämne. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Lägger till den angivna nyckeln. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Hämtar eller anger värdet för den svarta komponenten. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Hämtar eller anger färgens typ. |
| [getCyan()](#getCyan--) | Hämtar eller anger värdet för cyan-komponenten. |
| [getMagenta()](#getMagenta--) | Hämtar eller anger värdet för magenta-komponenten. |
| [getMode()](#getMode--) | Hämtar  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | Hämtar standardnamnutrymmets URI. |
| [getPrefix()](#getPrefix--) | Hämtar prefixet. |
| [getSwatchName()](#getSwatchName--) | Hämtar eller anger namnet på färgprovet. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar det stränginnehållande värdet i XMP-format. |
| [getYellow()](#getYellow--) | Hämtar eller anger värdet för gul-komponenten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Hämtar eller anger värdet för den svarta komponenten. |
| [setColorType(int value)](#setColorType-int-) | Hämtar eller anger färgens typ. |
| [setCyan(float value)](#setCyan-float-) | Hämtar eller anger värdet för cyan-komponenten. |
| [setMagenta(float value)](#setMagenta-float-) | Hämtar eller anger värdet för magenta-komponenten. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Hämtar eller anger namnet på färgprovet. |
| [setYellow(float value)](#setYellow-float-) | Hämtar eller anger värdet för gul-komponenten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Initierar en ny instans av klassen  ColorantCmyk .

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Initierar en ny instans av klassen  ColorantCmyk .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svart | float | Värdet för den svarta komponenten. |
| cyan | float | Cyan-färgkomponentens värde. |
| magenta | float | Magenta-komponentens värde. |
| gul | float | Gul-komponentens värde. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Maximalt färgvärde i CMYK-färgämne.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Minimalt färgvärde i CMYK-färgämne.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Lägger till den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.Object | Värdet att lägga till i. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Hämtar eller anger värdet för den svarta komponenten.

Värde: Svart-komponentens värde.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Hämtar eller anger färgens typ.

Värde: Färgens typ.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Hämtar eller anger värdet för cyan-komponenten.

Värde: Cyan-komponentens värde.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Hämtar eller anger värdet för magenta-komponenten.

Värde: Magenta-komponentens värde.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Hämtar  ColorMode .

Värde: Färgläget.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Hämtar standardnamnutrymmets URI.

**Returns:**
java.lang.String - Standardnamnutrymmes URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Hämtar prefixet.

**Returns:**
java.lang.String - Prefixet.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Hämtar eller anger namnet på färgprovet.

Värde: Namnet på färgprovet.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Hämtar det stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Hämtar eller anger värdet för gul-komponenten.

Värde: Gul-komponentens värde.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Hämtar eller anger värdet för den svarta komponenten.

Värde: Svart-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Hämtar eller anger färgens typ.

Värde: Färgens typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Hämtar eller anger värdet för cyan-komponenten.

Värde: Cyan-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Hämtar eller anger värdet för magenta-komponenten.

Värde: Magenta-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Hämtar eller anger namnet på färgprovet.

Värde: Namnet på färgprovet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Hämtar eller anger värdet för gul-komponenten.

Värde: Gul-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

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

