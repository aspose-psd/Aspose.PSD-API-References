---
title: "OuterGlowEffect"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Outer-Glow-Layer-Effekt"
type: docs
weight: 15
url: /de/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Outer-Glow-Layer-Effekt
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
| [getFillColor()](#getFillColor--) | Liest oder setzt die Farbe. |
| [getIntensity()](#getIntensity--) | Liest oder setzt den Winkel in Grad. |
| [getJitter()](#getJitter--) | Liest oder setzt das Rauschen. |
| [getNoise()](#getNoise--) | Liest oder setzt das Rauschen. |
| [getOpacity()](#getOpacity--) | Liest oder setzt die Opazität. |
| [getRange()](#getRange--) | Liest oder setzt das Rauschen. |
| [getSize()](#getSize--) | Liest den Unschärfewert in Pixeln. |
| [getSpread()](#getSpread--) | Liest oder setzt die Intensität als Prozentsatz. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Liest oder setzt den aktivierten AntiAliasing-Effekt |
| [isSoftBlend()](#isSoftBlend--) | Liest oder setzt einen Wert, der angibt, ob [knocks out]. |
| [isVisible()](#isVisible--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Liest oder setzt den aktivierten AntiAliasing-Effekt |
| [setBlendMode(long value)](#setBlendMode-long-) | Liest oder setzt den Mischmodus. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Liest oder setzt die Farbe. |
| [setIntensity(int value)](#setIntensity-int-) | Liest oder setzt den Winkel in Grad. |
| [setJitter(int value)](#setJitter-int-) | Liest oder setzt das Rauschen. |
| [setNoise(int value)](#setNoise-int-) | Liest oder setzt das Rauschen. |
| [setOpacity(byte value)](#setOpacity-byte-) | Liest oder setzt die Opazität. |
| [setRange(int value)](#setRange-int-) | Liest oder setzt das Rauschen. |
| [setSize(int value)](#setSize-int-) | Liest den Unschärfewert in Pixeln. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Liest oder setzt einen Wert, der angibt, ob [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Liest oder setzt die Intensität als Prozentsatz. |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Liest oder setzt die Farbe.

Wert: Die Farbe.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Liest oder setzt den Winkel in Grad.

Wert: Der Winkel.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Liest oder setzt das Rauschen.

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Liest oder setzt das Rauschen.

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
### getRange() {#getRange--}
```
public final int getRange()
```


Liest oder setzt das Rauschen.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Liest den Unschärfewert in Pixeln.

Wert: Die Größe.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Liest oder setzt die Intensität als Prozentsatz.

Wert: Die Ausdehnung.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


Liest oder setzt den aktivierten AntiAliasing-Effekt

Wert: Die Entfernung.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Liest oder setzt einen Wert, der angibt, ob [knocks out].

Wert:  true  wenn [knocks out]; andernfalls,  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Liest oder setzt den aktivierten AntiAliasing-Effekt

Wert: Die Entfernung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Liest oder setzt die Farbe.

Wert: Die Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Liest oder setzt den Winkel in Grad.

Wert: Der Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Liest oder setzt das Rauschen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Liest oder setzt das Rauschen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Liest oder setzt das Rauschen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Liest den Unschärfewert in Pixeln.

Wert: Die Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [knocks out].

Wert:  true  wenn [knocks out]; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Liest oder setzt die Intensität als Prozentsatz.

Wert: Die Ausdehnung.

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

