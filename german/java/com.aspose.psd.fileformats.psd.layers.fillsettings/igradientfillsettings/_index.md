---
title: "IGradientFillSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Basis-Interface für Gradient-Füllungseinstellungen."
type: docs
weight: 23
url: /de/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Basis-Interface für Gradient-Füllungseinstellungen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Liest oder setzt einen Wert, der angibt, ob [align with layer]. |
| [getAngle()](#getAngle--) | Liest oder setzt den Winkel. |
| [getDither()](#getDither--) | Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) dither ist. |
| [getGradient()](#getGradient--) | Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Liest oder setzt den Typ des Farbverlaufs. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Liest oder setzt den horizontalen Versatz. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Liest oder setzt die Interpolationsmethode für den Verlauf. |
| [getReverse()](#getReverse--) | Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) umgekehrt ist. |
| [getScale()](#getScale--) | Liest oder setzt die **normalisierte** Gradienten-Skala (in Prozent). |
| [getVerticalOffset()](#getVerticalOffset--) | Liest oder setzt den vertikalen Versatz. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Liest oder setzt einen Wert, der angibt, ob [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Liest oder setzt den Winkel. |
| [setDither(boolean value)](#setDither-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) dither ist. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Liest oder setzt den Typ des Farbverlaufs. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Liest oder setzt den horizontalen Versatz. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Liest oder setzt die Interpolationsmethode für den Verlauf. |
| [setReverse(boolean value)](#setReverse-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) umgekehrt ist. |
| [setScale(int value)](#setScale-int-) | Liest oder setzt die **normalisierte** Gradienten-Skala (in Prozent). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Liest oder setzt den vertikalen Versatz. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Liest oder setzt einen Wert, der angibt, ob [align with layer].

Wert:  true  wenn [align with layer]; andernfalls  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Liest oder setzt den Winkel.

Wert: Der Winkel.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) dither ist.

Wert: true wenn dither; andernfalls false.

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Liest oder setzt den Typ des Farbverlaufs.

Wert: Der Typ des Farbverlaufs.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Liest oder setzt den horizontalen Versatz.

Wert: Der horizontale Versatz.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Liest oder setzt die Interpolationsmethode für den Verlauf.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) umgekehrt ist.

Wert: true wenn reverse; andernfalls false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Liest oder setzt die **normalisierte** Gradienten-Skala (in Prozent).

Wert: Die Skalierung.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Liest oder setzt den vertikalen Versatz.

Wert: Der vertikale Versatz.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [align with layer].

Wert:  true  wenn [align with layer]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Liest oder setzt den Winkel.

Wert: Der Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) dither ist.

Wert: true wenn dither; andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Liest oder setzt den Typ des Farbverlaufs.

Wert: Der Typ des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Liest oder setzt den horizontalen Versatz.

Wert: Der horizontale Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Liest oder setzt die Interpolationsmethode für den Verlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) umgekehrt ist.

Wert: true wenn reverse; andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Liest oder setzt die **normalisierte** Gradienten-Skala (in Prozent).

Wert: Die Skalierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Liest oder setzt den vertikalen Versatz.

Wert: Der vertikale Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

