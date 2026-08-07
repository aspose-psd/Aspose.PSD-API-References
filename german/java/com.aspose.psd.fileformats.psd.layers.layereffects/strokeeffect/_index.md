---
title: "StrokeEffect"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Adobe Photoshop-Strich-Effekt für die PSD-Ebene."
type: docs
weight: 17
url: /de/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

Der Adobe® Photoshop®-Strich-Effekt für die PSD-Ebene.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Liest oder setzt den Mischmodus. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Ruft die Entität ab. |
| [getEffectType()](#getEffectType--) | Liest einen Effekttyp |
| [getFillSettings()](#getFillSettings--) | Liest oder legt die Füllungseinstellungen fest. |
| [getOpacity()](#getOpacity--) | Liest oder setzt die Opazität. |
| [getOverprint()](#getOverprint--) | Liest oder legt einen Wert fest, der angibt, ob dieser [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) den Strich mit dem aktuellen Ebeneninhalt mischt. |
| [getPosition()](#getPosition--) | Liest oder legt die Position des Strich‑Effekts fest, um die Ausrichtung Ihres Strichs am PSD‑Ebeneninhalt zu steuern. |
| [getSize()](#getSize--) | Liest oder legt die Breite des Strich‑Effekts fest. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Liest oder setzt den Mischmodus. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Liest oder legt die Füllungseinstellungen fest. |
| [setOpacity(byte value)](#setOpacity-byte-) | Liest oder setzt die Opazität. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Liest oder legt einen Wert fest, der angibt, ob dieser [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) den Strich mit dem aktuellen Ebeneninhalt mischt. |
| [setPosition(short value)](#setPosition-short-) | Liest oder legt die Position des Strich‑Effekts fest, um die Ausrichtung Ihres Strichs am PSD‑Ebeneninhalt zu steuern. |
| [setSize(int value)](#setSize-int-) | Liest oder legt die Breite des Strich‑Effekts fest. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Liest oder setzt den Mischmodus.

Wert: Der Mischmodus.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen der Ebenenpixel. |
| globalAngle | int | Der globale Winkel zur Berechnung des globalen Lichtwinkels. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Ruft die Entität ab.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Liest einen Effekttyp

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Liest oder legt die Füllungseinstellungen fest.

Wert: Die Füll‑Einstellungen.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Liest oder setzt die Opazität.

Wert: Die Opazität.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Liest oder legt einen Wert fest, der angibt, ob dieser [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) den Strich mit dem aktuellen Ebeneninhalt mischt.

Wert:  true  wenn der Strich mit dem aktuellen Ebeneninhalt gemischt werden muss; andernfalls  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Liest oder legt die Position des Strich‑Effekts fest, um die Ausrichtung Ihres Strichs am PSD‑Ebeneninhalt zu steuern. Der Wert kann [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) sein, um den Strich innerhalb des PSD‑Ebeneninhalts zu zeichnen, oder [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside), um den Strich um den PSD‑Ebeneninhalt zu zeichnen, und [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center), um den Strich sowohl innen als auch außen zu zeichnen.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Liest oder legt die Breite des Strich‑Effekts fest.

Wert: Die Breite des Strich‑Effekts.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist.

Wert:  true  wenn diese Instanz sichtbar ist; andernfalls  false .

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Liest oder setzt den Mischmodus.

Wert: Der Mischmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Liest oder legt die Füllungseinstellungen fest.

Wert: Die Füll‑Einstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Liest oder setzt die Opazität.

Wert: Die Opazität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob dieser [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) den Strich mit dem aktuellen Ebeneninhalt mischt.

Wert:  true  wenn der Strich mit dem aktuellen Ebeneninhalt gemischt werden muss; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Liest oder legt die Position des Strich‑Effekts fest, um die Ausrichtung Ihres Strichs am PSD‑Ebeneninhalt zu steuern. Der Wert kann [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) sein, um den Strich innerhalb des PSD‑Ebeneninhalts zu zeichnen, oder [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside), um den Strich um den PSD‑Ebeneninhalt zu zeichnen, und [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center), um den Strich sowohl innen als auch außen zu zeichnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Liest oder legt die Breite des Strich‑Effekts fest.

Wert: Die Breite des Strich‑Effekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist.

Wert:  true  wenn diese Instanz sichtbar ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

