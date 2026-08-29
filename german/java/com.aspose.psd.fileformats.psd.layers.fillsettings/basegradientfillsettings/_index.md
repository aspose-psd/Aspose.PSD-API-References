---
title: "BaseGradientFillSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Basisklasse für Gradienten-Definition."
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Base-Gradient-Definitionsklasse. Sie enthält gemeinsame Eigenschaften für beide Gradiententypen (Solid und Noise).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Initialisiert eine neue Instanz der Klasse [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) class. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Liest oder setzt einen Wert, der angibt, ob [align with layer]. |
| [getAngle()](#getAngle--) | Liest oder setzt den Winkel. |
| [getClass()](#getClass--) |  |
| [getDither()](#getDither--) | Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither ist. |
| [getFillType()](#getFillType--) | Der Fülltyp. |
| [getGradientMode()](#getGradientMode--) | Ruft den Modus für diesen Gradient ab. |
| [getGradientName()](#getGradientName--) | Liest oder setzt den Namen des Gradienten. |
| [getGradientType()](#getGradientType--) | Liest oder setzt den Typ des Farbverlaufs. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Liest oder setzt den horizontalen Versatz in Prozent. |
| [getReverse()](#getReverse--) | Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) umgekehrt ist. |
| [getScale()](#getScale--) | Liest oder setzt die Skalierung. |
| [getVerticalOffset()](#getVerticalOffset--) | Liest oder setzt den vertikalen Versatz in Prozent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Löst die Wertänderung aus. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Liest oder setzt einen Wert, der angibt, ob [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Liest oder setzt den Winkel. |
| [setDither(boolean value)](#setDither-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither ist. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Ruft den Modus für diesen Gradient ab. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Liest oder setzt den Namen des Gradienten. |
| [setGradientType(int value)](#setGradientType-int-) | Liest oder setzt den Typ des Farbverlaufs. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Liest oder setzt den horizontalen Versatz in Prozent. |
| [setReverse(boolean value)](#setReverse-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) umgekehrt ist. |
| [setScale(int value)](#setScale-int-) | Liest oder setzt die Skalierung. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Liest oder setzt den vertikalen Versatz in Prozent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Initialisiert eine neue Instanz der Klasse [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) class.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Liest oder setzt einen Wert, der angibt, ob [align with layer].

Wert:  true  wenn [align with layer]; andernfalls  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Liest oder setzt den Winkel.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDither() {#getDither--}
```
public final boolean getDither()
```


Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither ist.

Wert: true wenn dither; andernfalls false.

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Der Fülltyp.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Ruft den Modus für diesen Gradient ab. Bestimmt 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Liest oder setzt den Namen des Gradienten.

Wert: Der Name des Gradienten.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Liest oder setzt den Typ des Farbverlaufs.

Wert: Der Typ des Farbverlaufs.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Liest oder setzt den horizontalen Versatz in Prozent.

Wert: Der horizontale Versatz.

**Returns:**
double
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) umgekehrt ist.

Wert: true wenn reverse; andernfalls false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Liest oder setzt die Skalierung.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Liest oder setzt den vertikalen Versatz in Prozent.

Wert: Der vertikale Versatz.

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Löst die Wertänderung aus.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [align with layer].

Wert:  true  wenn [align with layer]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Liest oder setzt den Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither ist.

Wert: true wenn dither; andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Ruft den Modus für diesen Gradient ab. Bestimmt 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Liest oder setzt den Namen des Gradienten.

Wert: Der Name des Gradienten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Liest oder setzt den Typ des Farbverlaufs.

Wert: Der Typ des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Liest oder setzt den horizontalen Versatz in Prozent.

Wert: Der horizontale Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) umgekehrt ist.

Wert: true wenn reverse; andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Liest oder setzt die Skalierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Liest oder setzt den vertikalen Versatz in Prozent.

Wert: Der vertikale Versatz.

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

