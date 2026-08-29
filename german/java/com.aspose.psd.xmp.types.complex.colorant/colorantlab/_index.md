---
title: "ColorantLab"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt LAB-Farbant dar."
type: docs
weight: 14
url: /de/java/com.aspose.psd.xmp.types.complex.colorant/colorantlab/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantLab extends ColorantBase
```

Stellt LAB-Farbant dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorantLab()](#ColorantLab--) | Initialisiert eine neue Instanz der ColorantLab-Klasse. |
| [ColorantLab(int a, int b, float l)](#ColorantLab-int-int-float-) | Initialisiert eine neue Instanz der ColorantLab-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MaxA](#MaxA) | Der maximale A-Komponentenwert |
| [MaxB](#MaxB) | Der maximale A-Komponentenwert |
| [MaxL](#MaxL) | Der maximale A-Komponentenwert |
| [MinA](#MinA) | Der minimale A-Komponentenwert |
| [MinB](#MinB) | Der minimale B-Komponentenwert |
| [MinL](#MinL) | Der minimale L-Komponentenwert |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Fügt den angegebenen Schlüssel hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | Liest oder setzt die A-Komponente. |
| [getB()](#getB--) | Liest oder setzt die B-Komponente. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Liest oder setzt den Typ der Farbe. |
| [getL()](#getL--) | Liest oder setzt die L-Komponente. |
| [getMode()](#getMode--) | Liest ColorMode. |
| [getNamespaceUri()](#getNamespaceUri--) | Liest den Standard-Namespace-URI. |
| [getPrefix()](#getPrefix--) | Liest das Präfix. |
| [getSwatchName()](#getSwatchName--) | Liest oder setzt den Namen des Farbfelds. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenkettenwert im XMP-Format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(int value)](#setA-int-) | Liest oder setzt die A-Komponente. |
| [setB(int value)](#setB-int-) | Liest oder setzt die B-Komponente. |
| [setColorType(int value)](#setColorType-int-) | Liest oder setzt den Typ der Farbe. |
| [setL(float value)](#setL-float-) | Liest oder setzt die L-Komponente. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Liest oder setzt den Namen des Farbfelds. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantLab() {#ColorantLab--}
```
public ColorantLab()
```


Initialisiert eine neue Instanz der ColorantLab-Klasse.

### ColorantLab(int a, int b, float l) {#ColorantLab-int-int-float-}
```
public ColorantLab(int a, int b, float l)
```


Initialisiert eine neue Instanz der ColorantLab-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | int | Eine Komponente. |
| b | int | B Komponente. |
| l | float | L Komponente. |

### MaxA {#MaxA}
```
public static final int MaxA
```


Der maximale A-Komponentenwert

### MaxB {#MaxB}
```
public static final int MaxB
```


Der maximale A-Komponentenwert

### MaxL {#MaxL}
```
public static final float MaxL
```


Der maximale A-Komponentenwert

### MinA {#MinA}
```
public static final int MinA
```


Der minimale A-Komponentenwert

### MinB {#MinB}
```
public static final int MinB
```


Der minimale B-Komponentenwert

### MinL {#MinL}
```
public static final float MinL
```


Der minimale L-Komponentenwert

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
### getA() {#getA--}
```
public int getA()
```


Liest oder setzt die A-Komponente.

Wert: Die A Komponente.

**Returns:**
int
### getB() {#getB--}
```
public int getB()
```


Liest oder setzt die B-Komponente.

Wert: Die B Komponente.

**Returns:**
int
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
### getL() {#getL--}
```
public float getL()
```


Liest oder setzt die L-Komponente.

Wert: Die L Komponente.

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




### setA(int value) {#setA-int-}
```
public void setA(int value)
```


Liest oder setzt die A-Komponente.

Wert: Die A Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setB(int value) {#setB-int-}
```
public void setB(int value)
```


Liest oder setzt die B-Komponente.

Wert: Die B Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setL(float value) {#setL-float-}
```
public void setL(float value)
```


Liest oder setzt die L-Komponente.

Wert: Die L Komponente.

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

