---
title: "PatternOverlayEffect"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Pattern-Layer-Effekt"
type: docs
weight: 16
url: /de/java/com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class PatternOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Pattern-Layer-Effekt
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Liest oder setzt den Mischmodus. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Ruft die Entität ab. |
| [getEffectType()](#getEffectType--) | Liest einen Effekt-Typ |
| [getOpacity()](#getOpacity--) | Liest oder setzt die Opazität. |
| [getSettings()](#getSettings--) | Liest oder setzt die Einstellungen. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Liest oder setzt den Mischmodus. |
| [setOpacity(byte value)](#setOpacity-byte-) | Liest oder setzt die Opazität. |
| [setSettings(PatternFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Liest oder setzt die Einstellungen. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static PatternOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect)
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


Liest einen Effekt-Typ

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Liest oder setzt die Opazität.

Wert: Die Opazität.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final PatternFillSettings getSettings()
```


Liest oder setzt die Einstellungen.

Wert: Die Einstellungen.

**Returns:**
[PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)
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

### setSettings(PatternFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setSettings(PatternFillSettings value)
```


Liest oder setzt die Einstellungen.

Wert: Die Einstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) |  |

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

