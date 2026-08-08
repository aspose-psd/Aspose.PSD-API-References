---
title: "OuterGlowEffect"
second_title: "Aspose.PSD för Java API-referens"
description: "Yttre glödlager‑effekt"
type: docs
weight: 15
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Yttre glödlager‑effekt
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
| [getFillColor()](#getFillColor--) | Hämtar eller anger färgen. |
| [getIntensity()](#getIntensity--) | Hämtar eller anger vinkeln i grader. |
| [getJitter()](#getJitter--) | Hämtar eller anger brusnivån. |
| [getNoise()](#getNoise--) | Hämtar eller anger brusnivån. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opaciteten. |
| [getRange()](#getRange--) | Hämtar eller anger brusnivån. |
| [getSize()](#getSize--) | Hämtar oskärpevärdet i pixlar. |
| [getSpread()](#getSpread--) | Hämtar eller anger intensiteten i procent. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Hämtar eller anger aktiverad AntiAliasing-effekt |
| [isSoftBlend()](#isSoftBlend--) | Hämtar eller anger ett värde som indikerar om [knocks out]. |
| [isVisible()](#isVisible--) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Hämtar eller anger aktiverad AntiAliasing-effekt |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Hämtar eller anger färgen. |
| [setIntensity(int value)](#setIntensity-int-) | Hämtar eller anger vinkeln i grader. |
| [setJitter(int value)](#setJitter-int-) | Hämtar eller anger brusnivån. |
| [setNoise(int value)](#setNoise-int-) | Hämtar eller anger brusnivån. |
| [setOpacity(byte value)](#setOpacity-byte-) | Hämtar eller anger opaciteten. |
| [setRange(int value)](#setRange-int-) | Hämtar eller anger brusnivån. |
| [setSize(int value)](#setSize-int-) | Hämtar oskärpevärdet i pixlar. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Hämtar eller anger ett värde som indikerar om [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Hämtar eller anger intensiteten i procent. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entitet | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Hämtar eller anger färgen.

Värde: Färgen.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Hämtar eller anger vinkeln i grader.

Värde: Vinkeln.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Hämtar eller anger brusnivån.

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Hämtar eller anger brusnivån.

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
### getRange() {#getRange--}
```
public final int getRange()
```


Hämtar eller anger brusnivån.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar oskärpevärdet i pixlar.

Värde: storleken.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Hämtar eller anger intensiteten i procent.

Värde: Spridningen.

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


Hämtar eller anger aktiverad AntiAliasing-effekt

Värde: Avståndet.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Hämtar eller anger ett värde som indikerar om [knocks out].

Värde:  true  om [knocks out]; annars,  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Hämtar eller anger aktiverad AntiAliasing-effekt

Värde: Avståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Hämtar eller anger färgen.

Värde: Färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Hämtar eller anger vinkeln i grader.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Hämtar eller anger brusnivån.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Hämtar eller anger brusnivån.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Hämtar eller anger brusnivån.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Hämtar oskärpevärdet i pixlar.

Värde: storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Hämtar eller anger ett värde som indikerar om [knocks out].

Värde:  true  om [knocks out]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Hämtar eller anger intensiteten i procent.

Värde: Spridningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

