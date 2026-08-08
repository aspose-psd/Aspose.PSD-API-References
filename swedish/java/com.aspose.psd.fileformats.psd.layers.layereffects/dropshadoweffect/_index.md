---
title: "DropShadowEffect"
second_title: "Aspose.PSD för Java API-referens"
description: "Skuggkastningslager‑effekt"
type: docs
weight: 12
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Skuggkastningslager‑effekt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Hämtar eller anger vinkeln i grader. |
| [getBlendMode()](#getBlendMode--) | Hämtar eller anger blandningsläget. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Hämtar eller anger färgen. |
| [getDistance()](#getDistance--) | Hämtar eller anger avståndet i pixlar. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Hämtar entiteten |
| [getEffectType()](#getEffectType--) | Hämtar en effekttyp |
| [getKnocksOut()](#getKnocksOut--) | Hämtar eller anger ett värde som indikerar om [knocks out]. |
| [getNoise()](#getNoise--) | Hämtar eller anger brusnivån. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opaciteten. |
| [getSize()](#getSize--) | Hämtar eller anger oskärpevärdet i pixlar. |
| [getSpread()](#getSpread--) | Hämtar eller anger intensiteten i procent. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Hämtar eller anger ett värde som indikerar om [använd denna vinkel i alla lagerffekter]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Hämtar eller anger vinkeln i grader. |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Hämtar eller anger färgen. |
| [setDistance(int value)](#setDistance-int-) | Hämtar eller anger avståndet i pixlar. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | Hämtar eller anger ett värde som indikerar om [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | Hämtar eller anger brusnivån. |
| [setOpacity(byte value)](#setOpacity-byte-) | Hämtar eller anger opaciteten. |
| [setSize(int value)](#setSize-int-) | Hämtar eller anger oskärpevärdet i pixlar. |
| [setSpread(int value)](#setSpread-int-) | Hämtar eller anger intensiteten i procent. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Hämtar eller anger ett värde som indikerar om [använd denna vinkel i alla lagerffekter]. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entitet | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Hämtar eller anger vinkeln i grader.

Värde: Vinkeln.

**Returns:**
int
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
### getColor() {#getColor--}
```
public final Color getColor()
```


Hämtar eller anger färgen.

Värde: Färgen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Hämtar eller anger avståndet i pixlar.

Värde: Avståndet.

**Returns:**
int
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


Hämtar en effekttyp

**Returns:**
int
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


Hämtar eller anger ett värde som indikerar om [knocks out].

Värde:  true  om [knocks out]; annars,  false .

**Returns:**
boolean
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
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar eller anger oskärpevärdet i pixlar.

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
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Hämtar eller anger ett värde som indikerar om [använd denna vinkel i alla lagerffekter].

Värde:  true  om [använd global belysning]; annars,  false .

**Returns:**
boolean
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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


Hämtar eller anger vinkeln i grader.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger färgen.

Värde: Färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Hämtar eller anger avståndet i pixlar.

Värde: Avståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


Hämtar eller anger ett värde som indikerar om [knocks out].

Värde:  true  om [knocks out]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Hämtar eller anger oskärpevärdet i pixlar.

Värde: storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Hämtar eller anger ett värde som indikerar om [använd denna vinkel i alla lagerffekter].

Värde:  true  om [använd global belysning]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

