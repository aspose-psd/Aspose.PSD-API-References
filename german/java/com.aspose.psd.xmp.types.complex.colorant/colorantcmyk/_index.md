---
title: "ColorantCmyk"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt CMYK-Farbant dar."
type: docs
weight: 13
url: /de/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Stellt CMYK-Farbant dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Initialisiert eine neue Instanz der  ColorantCmyk  Klasse. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Initialisiert eine neue Instanz der  ColorantCmyk  Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Maximaler Farbwert im CMYK-Farbanteil. |
| [ColorValueMin](#ColorValueMin) | Minimaler Farbwert im CMYK-Farbanteil. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Fügt den angegebenen Schlüssel hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Liest oder setzt den Schwarz-Komponentenwert. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Liest oder setzt den Typ der Farbe. |
| [getCyan()](#getCyan--) | Liest oder setzt den Cyan-Komponentenwert. |
| [getMagenta()](#getMagenta--) | Liest oder setzt den Magenta-Komponentenwert. |
| [getMode()](#getMode--) | Liest ColorMode. |
| [getNamespaceUri()](#getNamespaceUri--) | Liest den Standard-Namespace-URI. |
| [getPrefix()](#getPrefix--) | Liest das Präfix. |
| [getSwatchName()](#getSwatchName--) | Liest oder setzt den Namen des Farbfelds. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenkettenwert im XMP-Format. |
| [getYellow()](#getYellow--) | Liest oder setzt den Gelb-Komponentenwert. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Liest oder setzt den Schwarz-Komponentenwert. |
| [setColorType(int value)](#setColorType-int-) | Liest oder setzt den Typ der Farbe. |
| [setCyan(float value)](#setCyan-float-) | Liest oder setzt den Cyan-Komponentenwert. |
| [setMagenta(float value)](#setMagenta-float-) | Liest oder setzt den Magenta-Komponentenwert. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Liest oder setzt den Namen des Farbfelds. |
| [setYellow(float value)](#setYellow-float-) | Liest oder setzt den Gelb-Komponentenwert. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Initialisiert eine neue Instanz der  ColorantCmyk  Klasse.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Initialisiert eine neue Instanz der  ColorantCmyk  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schwarz | float | Der Schwarz-Komponentenwert. |
| cyan | float | Der Cyan-Farbkomponentenwert. |
| magenta | float | Der Magenta-Komponentenwert. |
| gelb | float | Der Wert der gelben Komponente. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Maximaler Farbwert im CMYK-Farbanteil.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Minimaler Farbwert im CMYK-Farbanteil.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Fügt den angegebenen Schlüssel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.Object | Der Wert, zu dem hinzugefügt werden soll. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Liest oder setzt den Schwarz-Komponentenwert.

Wert: Der Wert der schwarzen Komponente.

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


Liest oder setzt den Typ der Farbe.

Wert: Der Typ der Farbe.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Liest oder setzt den Cyan-Komponentenwert.

Wert: Der Wert der cyanfarbenen Komponente.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Liest oder setzt den Magenta-Komponentenwert.

Wert: Der Wert der magentafarbenen Komponente.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Liest ColorMode.

Wert: Der Farbmodus.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Liest den Standard-Namespace-URI.

**Returns:**
java.lang.String - Der Standard-Namespace-URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Liest das Präfix.

**Returns:**
java.lang.String - Das Präfix.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Liest oder setzt den Namen des Farbfelds.

Wert: Der Name des Farbfelds.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenkettenwert im XMP-Format.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Liest oder setzt den Gelb-Komponentenwert.

Wert: Der Wert der gelben Komponente.

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


Liest oder setzt den Schwarz-Komponentenwert.

Wert: Der Wert der schwarzen Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Liest oder setzt den Typ der Farbe.

Wert: Der Typ der Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Liest oder setzt den Cyan-Komponentenwert.

Wert: Der Wert der cyanfarbenen Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Liest oder setzt den Magenta-Komponentenwert.

Wert: Der Wert der magentafarbenen Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Liest oder setzt den Namen des Farbfelds.

Wert: Der Name des Farbfelds.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Liest oder setzt den Gelb-Komponentenwert.

Wert: Der Wert der gelben Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

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

