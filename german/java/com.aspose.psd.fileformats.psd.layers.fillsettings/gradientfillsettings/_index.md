---
title: "GradientFillSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Einstellungen für den Gradient-Füllungseffekt."
type: docs
weight: 14
url: /de/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Einstellungen für den Gradient-Füllungseffekt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Initialisiert eine neue Instanz der Klasse [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) class. |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Liest oder setzt die Begrenzungen des Ebenencontainers, um die Position des Farbverlaufs korrekt zu berechnen. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Berechnet und gibt die  **denormalized**  Farbverlaufs-Skala (UI-Skala) zurück, die dem aktuellen  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) Wert entspricht. |
| [getDither()](#getDither--) | Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dithernd ist. |
| [getFillType()](#getFillType--) | Der Fülltyp. |
| [getGradient()](#getGradient--) | Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Liest oder setzt den Typ des Farbverlaufs. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Liest oder setzt den horizontalen Versatz in Prozent. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Liest oder setzt die Interpolationsmethode für den Verlauf. |
| [getReverse()](#getReverse--) | Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) umgekehrt ist. |
| [getScale()](#getScale--) | Liest oder setzt die  **normalized**  Farbverlaufs-Skala (in Prozent) |
| [getVerticalOffset()](#getVerticalOffset--) | Liest oder setzt den vertikalen Versatz in Prozent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Löst die Wertänderung aus. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Liest oder setzt einen Wert, der angibt, ob [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Liest oder setzt den Winkel. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Liest oder setzt die Begrenzungen des Ebenencontainers, um die Position des Farbverlaufs korrekt zu berechnen. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Konvertiert den angegebenen denormalized Skalenwert (UI) in sein  **normalized**  Äquivalent und weist ihn der  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) zu. |
| [setDither(boolean value)](#setDither-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dithernd ist. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Liest oder setzt den Typ des Farbverlaufs. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Liest oder setzt den horizontalen Versatz in Prozent. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Liest oder setzt die Interpolationsmethode für den Verlauf. |
| [setReverse(boolean value)](#setReverse-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) umgekehrt ist. |
| [setScale(int value)](#setScale-int-) | Liest oder setzt die  **normalized**  Farbverlaufs-Skala (in Prozent) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Liest oder setzt den vertikalen Versatz in Prozent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Initialisiert eine neue Instanz der Klasse [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) class.

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Liest oder setzt die Begrenzungen des Ebenencontainers, um die Position des Farbverlaufs korrekt zu berechnen.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Berechnet und gibt die  **denormalized**  Farbverlaufs-Skala (UI-Skala) zurück, die dem aktuellen  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Die Begrenzungen des Farbverlaufs. |

**Returns:**
int - Die denormalisierte (UI)-Skala in Prozent, wie in Photoshop angezeigt.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dithernd ist.

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
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Liest oder setzt die Interpolationsmethode für den Verlauf.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) umgekehrt ist.

Wert: true wenn reverse; andernfalls false.

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Liest oder setzt die  **normalized**  Farbverlaufs-Skala (in Prozent)

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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Liest oder setzt die Begrenzungen des Ebenencontainers, um die Position des Farbverlaufs korrekt zu berechnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Konvertiert den angegebenen denormalisierten Skalenwert (UI) in sein **normalisiertes** Äquivalent und weist ihn der  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) zu. Die Umwandlung wendet den aktuellen Winkel des Gradienten\\u2019s ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) und das bereitgestellte  fillArea  an, um den Normalisierungsfaktor zu berechnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die denormalisierte Skala, UI-Skala in Prozent, wie von Photoshop angezeigt; |
| fillArea | [Size](../../com.aspose.psd/size) | Die Begrenzungen des Farbverlaufs. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dithernd ist.

Wert: true wenn dither; andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Liest oder setzt die spezifische Gradientendefinitionsinstanz (Solid/Noise).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Liest oder setzt die Interpolationsmethode für den Verlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) umgekehrt ist.

Wert: true wenn reverse; andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Liest oder setzt die  **normalized**  Farbverlaufs-Skala (in Prozent)

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

