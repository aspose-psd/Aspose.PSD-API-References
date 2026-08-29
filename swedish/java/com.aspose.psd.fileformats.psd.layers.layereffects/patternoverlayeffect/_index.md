---
title: "PatternOverlayEffect"
second_title: "Aspose.PSD för Java API-referens"
description: "Mönster‑lager‑effekt"
type: docs
weight: 16
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class PatternOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Mönster‑lager‑effekt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Hämtar eller anger blandningsläget. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Hämtar entiteten |
| [getEffectType()](#getEffectType--) | Hämtar en typ av effekt. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opaciteten. |
| [getSettings()](#getSettings--) | Hämtar eller anger inställningarna. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setOpacity(byte value)](#setOpacity-byte-) | Hämtar eller anger opaciteten. |
| [setSettings(PatternFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Hämtar eller anger inställningarna. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static PatternOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entitet | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Hämtar eller anger blandningsläget.

Värde: Blandningsläget.

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


Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Lagrets pixelgränser. |
| globalAngle | int | Den globala vinkeln för att beräkna global belysningsvinkel. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Hämtar entiteten

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Hämtar en typ av effekt.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Hämtar eller anger opaciteten.

Värde: Opaciteten.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final PatternFillSettings getSettings()
```


Hämtar eller anger inställningarna.

Värde: Inställningarna.

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


Hämtar eller anger ett värde som indikerar om detta objekt är synligt.

Värde:  true  om detta objekt är synligt; annars  false .

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


Hämtar eller anger blandningsläget.

Värde: Blandningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Hämtar eller anger opaciteten.

Värde: Opaciteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setSettings(PatternFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setSettings(PatternFillSettings value)
```


Hämtar eller anger inställningarna.

Värde: Inställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekt är synligt.

Värde:  true  om detta objekt är synligt; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

