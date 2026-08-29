---
title: "ColorantCmyk"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt CMYK Colorant voor."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Stelt CMYK Colorant voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Initialiseert een nieuw exemplaar van de  ColorantCmyk  klasse. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Initialiseert een nieuw exemplaar van de  ColorantCmyk  klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Maximale kleurwaarde in CMYK-kleurstof. |
| [ColorValueMin](#ColorValueMin) | Minimale kleurwaarde in CMYK-kleurstof. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Voegt de opgegeven sleutel toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Haalt op of stelt de zwart componentwaarde in. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Haalt op of stelt het type van de kleur in. |
| [getCyan()](#getCyan--) | Haalt op of stelt de cyaan componentwaarde in. |
| [getMagenta()](#getMagenta--) | Haalt op of stelt de magenta componentwaarde in. |
| [getMode()](#getMode--) | Haalt ColorMode op. |
| [getNamespaceUri()](#getNamespaceUri--) | Haalt de standaard namespace‑URI op. |
| [getPrefix()](#getPrefix--) | Haalt het voorvoegsel op. |
| [getSwatchName()](#getSwatchName--) | Haalt op of stelt de naam van het kleurstaal in. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Haalt de tekenreeksinhoud op in XMP-indeling. |
| [getYellow()](#getYellow--) | Haalt op of stelt de geel componentwaarde in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Haalt op of stelt de zwart componentwaarde in. |
| [setColorType(int value)](#setColorType-int-) | Haalt op of stelt het type van de kleur in. |
| [setCyan(float value)](#setCyan-float-) | Haalt op of stelt de cyaan componentwaarde in. |
| [setMagenta(float value)](#setMagenta-float-) | Haalt op of stelt de magenta componentwaarde in. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Haalt op of stelt de naam van het kleurstaal in. |
| [setYellow(float value)](#setYellow-float-) | Haalt op of stelt de geel componentwaarde in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Initialiseert een nieuw exemplaar van de  ColorantCmyk  klasse.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Initialiseert een nieuw exemplaar van de  ColorantCmyk  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| zwart | float | De zwarte componentwaarde. |
| cyaan | float | De waarde van de cyaankleurcomponent. |
| magenta | float | De waarde van de magentacomponent. |
| geel | float | De waarde van de gele component. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Maximale kleurwaarde in CMYK-kleurstof.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Minimale kleurwaarde in CMYK-kleurstof.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Voegt de opgegeven sleutel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is gekoppeld aan de toegevoegde waarde. |
| waarde | java.lang.Object | De waarde om aan toe te voegen. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Haalt op of stelt de zwart componentwaarde in.

Waarde: De zwarte componentwaarde.

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


Haalt op of stelt het type van de kleur in.

Waarde: Het type van de kleur.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Haalt op of stelt de cyaan componentwaarde in.

Waarde: De cyaan componentwaarde.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Haalt op of stelt de magenta componentwaarde in.

Waarde: De magenta componentwaarde.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Haalt ColorMode op.

Waarde: De kleurmodus.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Haalt de standaard namespace‑URI op.

**Returns:**
java.lang.String - De standaard namespace-URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Haalt het voorvoegsel op.

**Returns:**
java.lang.String - De prefix.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Haalt op of stelt de naam van het kleurstaal in.

Waarde: De naam van het kleurstaal.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Haalt de tekenreeksinhoud op in XMP-indeling.

**Returns:**
java.lang.String - Retourneert de tekenreeksinhoud in XMP-indeling.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Haalt op of stelt de geel componentwaarde in.

Waarde: De gele componentwaarde.

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


Haalt op of stelt de zwart componentwaarde in.

Waarde: De zwarte componentwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Haalt op of stelt het type van de kleur in.

Waarde: Het type van de kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Haalt op of stelt de cyaan componentwaarde in.

Waarde: De cyaan componentwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Haalt op of stelt de magenta componentwaarde in.

Waarde: De magenta componentwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Haalt op of stelt de naam van het kleurstaal in.

Waarde: De naam van het kleurstaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Haalt op of stelt de geel componentwaarde in.

Waarde: De gele componentwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

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

